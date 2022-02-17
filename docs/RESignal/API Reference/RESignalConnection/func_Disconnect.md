## Function info
```lua
function RESignalConnection:Disconnect()
```

Disconnects a RESignalConnection from a RESignal object so that when [``RESignal:Fire(...)``](../RESignal/func_Fire.md) is called, this disconnected callback won't run.