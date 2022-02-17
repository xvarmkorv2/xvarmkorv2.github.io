## Function info
```lua
function RESignal:Destroy()
```

Destroys the current ``RESignal`` object, will make it unusable.

!!! bug "Destroyed object will become completely unusable"
    Calling any functions except Destroy() after this object was destroyed will result in a error!