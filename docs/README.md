This is the website for my van build hosted at <https://van.maroukis.net>


### License

Shield: [![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

This work is licensed under a
[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg


### Note To Self

#### Deployment

The site is current deployed to github pages via the `.github/workflows/pages-deploy.yml` workflow. 

To build the site locally do `bundle exec jekyll serve -i`

> Note the site is set to build to `docs` and not `site` since we were trying to publish directly to GH pages (but didn't get this working)

To build the full site, e.g. to check the published urls do `bundle exec jekyll serve ENV=PRODUCTION` (but note that the actual site will be built by the `pages=deploy.yml` workflow upon pushing to `main`)

> Note we also want to do some image size manipulation before pushing to `main` for the final build. 

#### Development

Start the python script which will watch for changes in the Obsidian vault `.md` files and copy them over to the Jekyll directory. 
- Note that we have to further edit the paths in the Jekyll directory depending on the category of post

Images must be copied over but there is a script for that as well (it looks for all the images mentioned, finds the location of the local image in the Obsidian vault, and copies it over to the Jekyll image destination directory)

`_projects` is for the main Index sidebar, e.g. `01-Build-Features-Design` through `13-Full-Index` as well as `About/00-Intro`. 

`_subprojects` is for the detailed/behind the scenes pages. Basically anything not with a number (excluding `About/00-Intro`)
