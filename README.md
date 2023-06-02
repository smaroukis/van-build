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

The site is current deployed to github pages via the `.github/workflows/pages-deploy.yml` workflow. 

To build the site locally do `bundle exec jekyll serve -i`

To build the full site, e.g. to check the published urls do `bundle exec jekyll serve ENV=PRODUCTION` (but note that the actual site will be built by the `pages=deploy.yml` workflow upon pushing to `main`)
