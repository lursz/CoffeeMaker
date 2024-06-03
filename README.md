# Coffee Maker
<img src="https://cdn.dribbble.com/users/1859102/screenshots/4809469/coffee-machine_1.gif" width="400" height="300">

## About 
The main idea behind this project is to create a model of coffee machine in AADL. 

## Model
```
-- SYSTEMS
sstem CoffeeMachine_System
system Sensors_System
system CoffeeDevices_System

-- PROCESSES
process MainProcess
process CoffeeBrewing_Proces
process SensorMonitoringProcess

-- THREADS
thread UserInterface
thread BrewingControl
thread deviceWaterControl
thread deviceCoffeeControl
thread deviceTemperatureControl
thread deviceMilkControl
thread deviceMilkFrotherControl
thread SensorMonitoring
thread ParametersDownloader


------------------
-- Devices
------------------
Screen / Control Panel
Grinder_Device
    -- Pumps
Pump_Device
Heater_Device
Frother_Device
    -- Sensors
Sensor_Device


------------------
-- HARDWARE
------------------
-- CPU
processor GenericProcessor

-- MEMORY
memory GenericMemory
memory SSD

-- BUS
bus DataBus
bus SATA


------------------
-- DATA TYPES
------------------
data Temperature
data Time
data WaterAmount
data CoffeeAmount
data MilkAmount
data BeverageParameters
data NumberOfCycles
```

# Model Diagrams
![CoffeeMachineSystemDiagram](https://github.com/lursz/CoffeeMaker/assets/93160829/6c8c4b37-cf21-4b8f-bb92-44bd943c663e)
![BrewingProcessDiagram](https://github.com/lursz/CoffeeMaker/assets/66112312/47b14ff8-67ac-4968-8c61-adfa0b31a1f5)

