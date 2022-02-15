## Function info
```lua
function GeometryLinesBackground:StartRender(overridecurrentrendering: boolean?): boolean
```

Start rendering the geometry lines effect visualization, if ``overridecurrentrendering`` is true and the renderer is still active, it will call [``GeometryLinesBackground:StopRender()``](./func_StopRender.md) and then start the renderer again, otherwise if you call this function while the renderer is active, it will error.

!!! warning "Use with caution! Check if the renderer is already active or not."
    Calling this function while the renderer is not active and ``overridecurrentrendering`` is passed as nil/false will result a error!

## Arguments
- overridecurrentrendering: boolean? - If the renderer is already active, override it by calling [``GeometryLinesBackground:StopRender()``](./func_StopRender.md) and start the renderer process again.