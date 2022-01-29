```lua
type posv3 = {pos1=Vector3, pos2=Vector3?}
```

- pos1: Vector3 = Main vector of the position for randomisation
- pos2: Vector3 = Optional, second vector, if not defined then the positions will be randomised between -pos1 and pos1 else it will be randomised between pos1 and pos2