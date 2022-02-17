## Function info
```lua
function RESignal:Fire(... : any)
```

Fires a ``RESignal`` object, calling all connected connection's callback based on the signal behavior.

## Arguments
Anything passed to this function will be passed to each connected connection's callback as it's call arguments.