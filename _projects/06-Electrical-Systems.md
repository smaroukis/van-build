---
index: 15
title: "06 Electrical Systems"
featured_image: /img/electrical-1.jpg
---

Going off-grid and nearly all electric is possible. An induction stove and a gasoline-powered heater plumbed into the van's gas tank allows this build to be propane-free. Undervoltage and low state of charge relay logic is included to protect the batteries from over-discharge.

**By the Numbers**
- 600W solar (2 x 300W panels)
- 100V/50A MPPT solar charger
- 400Ah LiFePO4 batteries
- 2500W combined inverter/charger
- Backup Sources: 60A alternator charger and 120V shore power plug

Lithium Ion Phosphate (LiFePO4) batteries, although expensive, were chosen due to the ability to discharge down to a lower state of charge, and for the high discharge current capacity useful for the power-hungry induction cooktop. 

<div class='gallery' data-columns='2'>
	<img src="/img/electrical-1.jpg">
	<img src="/img/electrical-2.jpeg">
	<img src="/img/sketch-fuse-sizing.jpg">
	<img src="/img/12v-header.jpeg">
</div>


## System Diagrams 

Diagrams of the 120V, solar, alternator charger, and relay circuits are shown below (click to enlarge). For more detail see the individual page in the table above.

<div class='gallery' data-columns='3'>
	<img src="/img/system-120v.png">
	<img src="/img/system-solar.png">
	<img src="/img/system-b2b.png">
	<img src="/img/van-bmv-contura-switch.png">
	<img src="/img/van-bmv-relay.png">
</div>

Full-size PDF CAD diagrams of the system can be found below:
- [DWG-01-AC-SYSTEM]( /pdf/DWG-01-AC-SYSTEM.pdf)(shows the inverter/charger and the shore power hookup)
- [DWG-02-BATTERY-COMPARTMENT]( /pdf/DWG-02-BATTERY-COMPARTMENT.pdf) (shows the connections in the main electrical battery compartment and also the solar and alternator charger systems)
- [DWG-03-12V-SYSTEM]( /pdf/DWG-03-12V-SYSTEM.pdf) (shows the 12V distribution fuse block, branch circuits, and loads)

## Table of Components 

See the table and links below for specific components used.

| System     | Component                           | Model                         |
| ---------- | ----------------------------------- | ----------------------------- |
| 120V AC    | [inverter-charger](inverter-charger)                | AIMS 2500W Inverter/Charger   |
| 120V AC    | [induction-cooktop](induction-cooktop)               | Summit Appliance              |
| Solar      | [solar-panels](solar-panels)                    | 2 x 300W Renogy 24V Panels    |
| Solar      | Solar Charger                       | Victron 100/50 Smart Solar    | 
| Alternator | [alternator-charger](alternator-charger)              | Sterling B2B 1260             |
| Batteries  | [batteries](batteries)                       | 2 x 200Ah Renogy LiFePO4      |
| 12V DC     | [battery-monitor-and-relay](battery-monitor-and-relay) | Victron BMV 712               |
| 12V DC     | [main-battery-disconnect](main-battery-disconnect)         | Blue Seas ML-RBS 7700         |
| 12V DC     | [12V-system](12V-system)                      |                               |
| 12V DC     | [fridge](fridge)                          | Isotherm Cruise Elegance 130L |

---

Next:  [07-plumbing-water-heater](07-plumbing-water-heater)