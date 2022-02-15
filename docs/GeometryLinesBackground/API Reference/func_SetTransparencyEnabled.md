## Function info
```lua
function GeometryLinesBackground:SetTransparencyEnabled(newtoggle: boolean)
```

Sets whether the transparency effect is enabled or not based on ``newtoggle``.

The transparency effect mentioned here is the effect where a line becomes more opaqe the more farther they are between 2 lines.

!!! error "Calling this function while the renderer is still active will error"
    Calling this function while the renderer is still active will cause a error! Ensure the renderer is already off before calling this function.

## Arguments
- newtoggle: boolean - Whether the transparency effect is enabled or not