## Enum information
```lua
RESignal.SignalBehavior = {
    NewThread;
	Deferred;
	Synced;
}
```

| Mode name | Description                                                                                                                                 |
|-----------|---------------------------------------------------------------------------------------------------------------------------------------------|
| NewThread | Spawns the callback of a connection on a new thread using ``task.spawn()``                                                                  |
| Deferred  | Spawns the callback of a connection on a deferred thread (run callbacks after the thread calling Fire has finished) using ``task.defer()``. |
| Synced    | **NOT YIELD-SAFE**. Execution of a connection callback is handled by the thread calling the fire function.                                  |