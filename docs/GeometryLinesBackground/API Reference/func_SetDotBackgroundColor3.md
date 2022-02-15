## Function info
```lua
function GeometryLinesBackground:SetDotBackgroundColor3(newc3: Color3)
```

Sets the dot's default BackgroundColor3

!!! error "Calling this function while the renderer is still active will error"
    Calling this function while the renderer is still active will cause a error! Ensure the renderer is already off before calling this function.

## Arguments
- newc3: Color3 - The new Color3 to be set at the dot's BackgroundColor3 when the [``GeometryLinesBackground:StartRender()``](./func_StartRender.md) is called.