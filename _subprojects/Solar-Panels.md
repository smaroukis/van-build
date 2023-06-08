---
index: 16
title: "→ Solar"
featured_image: /img/solar-header.jpg
---

Mfg. / Part #: Renogy 300W 24V
Tags: electrical, solar

The solar panels are two 300W Renogy 24V panels wired in parallel. This means you can cover one of the panels and the other one will work.

They are wired to the Solar Charge Controller via 8AWG. Note that a fuse isn't needed on the source (panel) side because the short circuit current that the panels can provide is less than the rating of the 8AWG (80A at 105C insulation rating, plus a ~0.8 derating factor for being exposed to the sun). 

A breaker is provided on the 12V system side before it is connected directly to the bus bar with #6 AWG. 

The sizing for the 12V side is given by 600W/12V = 50A. Then I chose a 60A breaker, and made sure the cabling (6AWG) was rated for at least 60A (actually more, taking into account derating factors for multiple conductors).

> Yakima round bars were added to stand-off strut mount pipe clamps to provide a surface above the panels to put a surfboard, for example

**System Diagram:**

![solar schematic](img/screen-solar.png)

Not shown above is the 60A circuit breaker on the 12V/battery side (the 24V/panel side doesn't need a fuse because of the combined short circuit rating of the panels being lower than the ampacity of the wire gauge used)

## Images

![solar-header](img/solar-header.jpg)

![roof-rack-header](img/roof-rack-header.jpg)

**Panel Characteristics**

![Screenshot 2023-02-14 at 2.30.41 PM](img/solar-iv-curve.png)

![Screenshot 2023-02-14 at 2.31.03 PM](img/solar-datasheet.png)


## Full-size PDF CAD diagrams of the system can be found below:

- [DWG-01-AC-SYSTEM]( /pdf/DWG-01-AC-SYSTEM.pdf)(shows the inverter/charger and the shore power hookup)
- [DWG-02-BATTERY-COMPARTMENT]( /pdf/DWG-02-BATTERY-COMPARTMENT.pdf) (shows the connections in the main electrical battery compartment and also the solar and alternator charger systems)
- [DWG-03-12V-SYSTEM]( /pdf/DWG-03-12V-SYSTEM.pdf) (shows the 12V distribution fuse block, branch circuits, and loads)

---

Next: [batteries](batteries.md)