# Coffee Maker
![Coffee Machine](https://cdn.dribbble.com/users/1859102/screenshots/4809469/coffee-machine_1.gif)
## About 
The main idea behind this project is to create a model of coffee machine in AADL. 

## Model
```
-- SYSTEM
System: CoffeeMachine

-- CPU
processor GenericProcessor

-- THREADS
thread UserInterface
thread BrewingControl
thread SensorMonitoring

-- Devices --
Device: Screen
Device: Grinder
    -- Pumps
Device: Water pump
Device: Water heater
Device: Milk pump
Device: Milk frother
    -- Sensors
Deivce: Coffee replenishment sensor
Device: Water sensor
Device: Milk sensor