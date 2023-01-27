---
share-van: true
---
parent::[[Van-Electrical]]

## Intro

In general, solar is used as a _generating resource_ and batteries are used as a _storage/supply source_. This means that your batteries are the _source_ of power and the solar is there to top them off daily. The energy capacity and power capacity of both systems are intricately related, and designed so that you can go 3 days without any solar power (although it is not recommended to drain the batteries all the way). A backup generating source - the car's alternator - is provided and can be activated by closing the circuit breaker behind the driver seat.

Each generating source (solar and alternator) has its own "charge controller" - this optimizes the charge profile (voltage and current over time) for the specific chemistry of battery used (here Lithium Iron Phosphate, or LiFePo4)️. → See [[LiFePo4 Battery Description]] for more on this battery chemistry. 

The inverter powers the (4) standard home outlets (120V) (countertop, under the sink, and two below the recessed cabinet). Note if the inverter is not on these will not work. The induction stove is plugged into the outlet below the sink and will not work if the inverter is off. **It is recommended to leave the inverter off when not using the stove or outlets** - the inverter will consume power when switched to "On" and not in use. The inverter switch is the blue box located on the control panel (switch 2 is the on source, and in the middle is off). 

## System Sizing and Components
- **Solar Panels**: (2) x 300W Renogy 24V solar panels  connected in _parallel_ (note thet 24V is used for the panels whereas the low voltage system is 12V - the Solar Charge Controller transforms this 24V to the system voltage of 12V)
- **Solar Charge Controller (SCC)**: Victron 100/50 Smart Solar MPPT (maximum values of 100A or 50V). Note the 50V is needed for the 24V panels which actually have an open-circuit voltage of 48V. (controlled through Victron App)
- **Alternator Charger** (also known as B2B Charger): Sterling B2B1260. (12V, 60A) (controlled through remote near driver seat)
- **Batteries**: (2) x 200Ah Renogy LiFePo4 batteries connected in parallel (400Ah total)
- **Battery Monitor and Protection**: Victron BMV 712 w/ bluetooth (controlled through the Victron app). Gives you your battery State of Charge % (SoC), voltage and currents, also provides the over/under voltage and SoC alarm and trip settings. ️→ See [[Battery Protection - Low Voltage Disconnect]] for more on the system protection scheme
- **Inverter**: AIMS power 2500W inverter/charger. This is connected to the shore power plug on the outside and powers all the 120V outlets. It also charges the batteries when connected to shore/grid power. For troubleshooting see [[Troubleshooting]]

## 12V Appliances
- Fridge
- Fan
- Lights
- Webasto Air Heater 
- Water Pump
- Toilet Fan
- 12V USB outlet

## 120V Appliances
- Induction Stove
- 120V Outlets
- Weboost Cell Booster (plugs into 120V outlet underneath)