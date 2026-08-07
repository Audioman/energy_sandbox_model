# energy_sandbox_model

 The energy-sandbox-model refects a sandbox for any building or flat to play with, log and analyse energy in terms of heating, water heating, eletricity in different prospectivs. It can be seen as a digital twin of your home - in detail of your choice, in order to simulate impact of planned changes.

 ## 1. Simulation base:
- The building location:  download open data resources ==> position and root parameters
- The climate :           download open data ==> historical weather in avg of late 20 years, future scenarios: temp  air, soil, humity, rain, wind 
- building situation:     alone / building environment scan
- building elements:      upload/min data input and location by user
- tubing:                 build an locate tubing system via tubing tool by user

## 2. Reference input:
- sensor data:            import home-assistant entity data in 15.Min slots
- dimension verification: meassurement checks by Laser and internal walls and elements input by user     
- meassurements:          input IR Thermometer temps of defined spots in tempeye tool by user
- wall structure          input by user or import ubakus tables


 
 
## 3. Simulations:
####    building heating:
- heat conduction through walls, roof, elements and basement
- ventilation and air condition
- heating and storage system
- passive storage
- windows solar energy contributions

####    water heating:
- path ways, sources and sinks ==> temp, flow and costs by source.
- storage ==> temp log
- time management: pumps, requests

####    air condition:
- natural ventilation ==> energy losses, air condition
- ventilation ==> energy losses, air condition
- flux
- humity
- passive storage, exchanger
- energy cick back devices

####    electricity:
- consumption ==> home use and consumption
- PV potentials
- Wind potentials
- storage

####    financials:
- Investment ==> costs, split / armortisation
- costs of usage ==> annual timelines

