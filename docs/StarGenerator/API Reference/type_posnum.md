```lua
type posnumber = {pos1: number, pos2: number?, minheight: number?, maxheight: number?}
```

- pos1: number = Main number position for randomisation
- pos2: number? = Optional, second number position for randomisation, if not defined then the positions will be randomised between -pos1 and pos1, else it will be randomised between pos1 and pos2
- minheight: number? = Optional, minimum height of star generation for randomisation
- maxheight: number? = Optional, maximum height of star generation for randomisation