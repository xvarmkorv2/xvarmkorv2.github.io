## Function info
```lua
function GeometryLinesBackground.new(amountofdots: number?, rootframe: GuiObject?, randomseed: number?): GeometryLinesBackground
```

Creates a new ``GeometryLinesBackground`` object.

!!! info "Another way to create a new ``GeometryLinesBackground``"
    Simply call the table you got after requiring the module with the same arguments as ``GeometryLinesBackground.new()``

## Arguments
- amountofdots: number? - The amount of dots (default 25)
- rootframe: GuiObject? - The root frame, this is where all the dots and lines will go and be rendered at until you change it again.
- randomseed: number? - The random seed for use at ``Random.new()`` (default is nil)