# Coffee Maker
<img src="https://cdn.dribbble.com/users/1859102/screenshots/4809469/coffee-machine_1.gif" width="400" height="300">

## About 
The main idea behind this project is to create a model of coffee machine in AADL. 

## Model
```
-- SYSTEM
System: CoffeeMachine

-- CPU
processor GenericProcessor

-- BUS
bus DataBus

-- MEMORY
memory Mem


-- PROCESSES
process MainProcess

-- THREADS
thread UserInterface
thread BrewingControl
thread SensorMonitoring

-- Devices --
device: Screen / Control Panel
device: Grinder
    -- Pumps
device: Water pump
device: Water heater
device: Milk pump
device: Milk frother
    -- Sensors
deivce: Coffee replenishment sensor
device: Water sensor
device: Milk sensor
```

# Model Diagrams

![CoffeeMachineSystemDiagram](https://github.com/lursz/CoffeeMaker/assets/66112312/ad0bc3ef-c44c-4a90-a523-87f94f010161)
![BrewingProcessDiagram](https://github.com/lursz/CoffeeMaker/assets/66112312/47b14ff8-67ac-4968-8c61-adfa0b31a1f5)


<details>
<summary>Tips </summary>

- Przynajmniej jeden proces na podsystem
- 0 pertów dla głównego systemu
- 0 errorów / warningow
- Analysys (Check connection binding check)
</details>
