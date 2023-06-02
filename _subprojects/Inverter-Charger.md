---
index: 21
title: "→ Inverter/Charger"
featured_image: /img/inverter-header.jpg
---

Mfg. / Part #: AIMS 2500W Inverter/Charger
Tags: electrical

The AIMS power inverter is a bi-directional inverter/charger. This means it can invert from DC to AC (from 12V DC to 120V AC) but it can also convert from 120V AC shore power to 12V DC to charge the batteries. 

See the drawings [DWG-01-AC-SYSTEM]( /pdf/DWG-01-AC-SYSTEM.pdf) and [DWG-02-BATTERY-COMPARTMENT]( /pdf/DWG-02-BATTERY-COMPARTMENT.pdf)

## Shore Power

The Shore Power plug is a Smart Plug 30A. This allows an upgrade to an AC unit which draws 15-20A. 

The inverter, if ON, will automatically switch to charge mode upon sensing AC source (15s delay). There is a light on the display panel saying that the charge is enabled - this means that shore power is active. Once shore power is active we are no longer using the “inverter”, so the comment about not running the stove at full power with other devices on does not apply anymore. 

![system 12v](img/screen-ac.png)

## Inverter

The inverter is protected by a 250A circuit breaker (no manual trip, trip on overcurrent only).

![F522C33A-BBF1-45F7-97C5-2D2B02910307.jpeg](img/F522C33A-BBF1-45F7-97C5-2D2B02910307.jpeg)

![E50D8072-6840-43A5-90AE-3168B1C606FC.jpeg](img/E50D8072-6840-43A5-90AE-3168B1C606FC.jpeg)

## Charging Profile Limitations for AIMS Inverters

⚠️ There is a limitation on charging the batteries. The charging profile selected is at a lower voltage than the recommended 14.2V for LiFePO4 batteries (likely since this inverter was designed before the proliferation of LiFePO4 batteries). This means the batteries will not be fully charged by the shore power itself. If you plan on going off grid for a while, use the AIMS overnight, and then leave the van in the sun to “top off” with the solar (which uses a more up-to-date charging profile).

## CAD Drawings

Full-size PDF CAD diagrams of the system can be found below:
- [DWG-01-AC-SYSTEM]( /pdf/DWG-01-AC-SYSTEM.pdf)(shows the inverter/charger and the shore power hookup)
- [DWG-02-BATTERY-COMPARTMENT]( /pdf/DWG-02-BATTERY-COMPARTMENT.pdf) (shows the connections in the main electrical battery compartment and also the solar and alternator charger systems)
- [DWG-03-12V-SYSTEM]( /pdf/DWG-03-12V-SYSTEM.pdf) (shows the 12V distribution fuse block, branch circuits, and loads)

---

Next: [12V-System](12V-System)