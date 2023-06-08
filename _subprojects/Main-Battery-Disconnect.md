---
index: 19
title: "→ Battery Disconnect Switch"
featured_image: /img/rbs-header.jpeg
---

Mfg. / Part #: Blue Sea ML-RBS 7700
Tags: electrical

This component is the main battery switch which actually has two components - the latching relay and the “contura" control switch which is the pushbutton switch that controls the latching relay. 

⚠️ The ML-RBS must be in the ON position (yellow knob facing down) and the top of the yellow knob must be **depressed** - this is the fully latched ON position

Picture of the ML-RBS disconnected. The control switch is through the hole on the other side. 

![Picture of the ML-RBS disconnected. The contura switch is through the hole on the other side. ](img/rbs-header.jpeg)

Instruction manual wiring diagram: 

![Wiring diagram from the instruction manual](img/instruction-manual-wiring.jpeg)

Actual wiring. The only difference is that we have added an input to Pin 1 which is now connected to the Normally Open relay of the Victron BMV 712. +12V on this pin will force the ML-RBS to Open thus disconnecting the batteries from the system. (From left to right:  BMV diagram, control switch diagram,  actual wiring in the back of the BMV, actual wiring for the control switch)

![wiring schematic](img/bmv-relay-circuit.png)

<div class='gallery' data-columns='2'>
	<img src="/img/IMG_4769.jpg">
	<img src="/img/IMG_4768.jpg">
</div>

## CAD Drawings

Full-size PDF CAD diagrams of the system can be found below:
- [DWG-01-AC-SYSTEM]( /pdf/DWG-01-AC-SYSTEM.pdf)(shows the inverter/charger and the shore power hookup)
- [DWG-02-BATTERY-COMPARTMENT]( /pdf/DWG-02-BATTERY-COMPARTMENT.pdf) (shows the connections in the main electrical battery compartment and also the solar and alternator charger systems)
- [DWG-03-12V-SYSTEM]( /pdf/DWG-03-12V-SYSTEM.pdf) (shows the 12V distribution fuse block, branch circuits, and loads)

---

Next: [alternator-charger](alternator-charger.md)