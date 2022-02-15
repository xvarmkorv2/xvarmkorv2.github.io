## Function info
```lua
function GeometryLinesBackground:SetRootFrame(newrootframe: GuiObject)
```

Sets the renderer root frame.

!!! error "Calling this function while the renderer is still active will error"
    Calling this function while the renderer is still active will cause a error! Ensure the renderer is already off before calling this function.

## Arguments
- newrootframe: GuiObject - The new root frame.