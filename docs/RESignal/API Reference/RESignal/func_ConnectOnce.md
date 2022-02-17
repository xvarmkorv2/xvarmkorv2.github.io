## Function info
```lua
function RESignal:ConnectOnce(callback: (...any) -> (...any))
```

Creates a new ``RESignalConnection`` but disconnects it after it's first fire, the callback will be called with the same arguments passed by [``RESignal:Fire()``](func_Fire.md).

## Arguments
- callback: (...any) -> (...any) - The callback that will be called with the arguments passed to [``RESignal:Fire()``](func_Fire.md)