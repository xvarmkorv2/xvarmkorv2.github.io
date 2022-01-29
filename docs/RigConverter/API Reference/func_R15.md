```lua
function RigConverter.R15(plr: number | string | Player): boolean
```

!!! note "Note about the ``plr`` argument accepting 3 types of argument"
    You can pass the following things to the ``plr`` argument as long as the player is inside the server and:
    
    - ``plr`` is the Player's UserId
    - ``plr`` is the Player instance
    - ``plr`` is the Player's **name** (NOT DisplayName)

Converts the target player's character appearence to use the R15 rig.

Returns ``true`` when conversion succeeded.