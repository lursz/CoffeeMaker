# Coffee Maker
## About 
The main idea behind this project is to create a model of coffee machine in AADL. 

## Model
```
System: CoffeeMachine

Processors: cpu1

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