# Cpp-simMedieval
simulator of time dependent at Middle Ages and is designed to use a paradigm MVC including few design patterns


## The geographical space
The geographical space is defined using a two-dimensional Euclidean space; the unit of measure is 10 km (10km), and it is assumed that the space is not finite (no enforcement of language conditions, beyond the storage limits of the float type.) North is defined as the positive direction of y-axis (0 degrees ), The east is the positive direction of the x-axis (90 degrees), the south is the negative direction of the y-axis (180 degrees), and the west is the negative direction of the x-axis (270 degrees).

### Agents
 1. Peasant (deliver boxes from one point to another) 
 3. Knight (patrols area)
 4. Thug (raids Peasants)
 
each agent can be found in one of the states:
- stopped
- dead
- Moving to

### Locations
Farm, Castle

## A detailed characterization of the simulation components
This is a simulation in which the time steps are controlled by solitary commands, with the world "freezing" at each time step, until the next time pass.

## input format of the program
receives 2 files which contains coordintaes of the sites for instance: ./simMedieval castles.dat farms.dat.


## Example of the console after running the program with the input files

```
Time 0: Enter command: create BugPeasant(0.00, 0.00)
Time 0: Enter command: create IrielPeasant(0.00, 0.00)
Time 0: Enter command: create MerryPeasant(0.00, 0.00)
Time 0: Enter command: create PippinPeasant(0.00, 0.00)
Time 0: Enter command: create ZugPeasant(0.00, 0.00)
Time 0: Enter command: create LokiThug(14.00, 14.00)
Time 0: Enter command: create GogThug(24.00, 24.00)
Time 0: Enter command: create WallaceKnightRivendale
Time 0: Enter command: Lokicourse 180 30
Time 0: Enter command: Gogcourse 270 30
Time 0: Enter command: Wallacedestination Sunnybrook
Time 0: Enter command: go
Time 1: Enter command: status
Castle Rivendale at position (20.00, 10.00), Inventory: 100
Castle Blackness at position (10.00, 20.00), Inventory: 20
Castle Sunnybrookat position (30.00, 0.00), Inventory: 50
...
```

