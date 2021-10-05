```lua
function ColorPickerModule.promptPickColor(player: Player, allowCancel: boolean, returnType: ColorPickerModuleEnum.returnType): BrickColor | Color3 | table | number
```

Returns either a BrickColor, Color3, table, or number based on what is passed ``returnType``.

## Return types:
| Passed argument                                     | Returns                                                                                                                       |
| --------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------- |
| ColorPickerModuleEnum.returnType.brickColor         | Returns a [``BrickColor``](https://developer.roblox.com/en-us/api-reference/datatype/BrickColor) based on the player's input. |
| ColorPickerModuleEnum.returnType.color3             | Returns a [``Color3``](https://developer.roblox.com/en-us/api-reference/datatype/Color3) based on the player's input.         |
| ColorPickerModuleEnum.returnType.rgbTableDictionary | Returns a dictionary table with keys R, G, and B ({R=R, G=G, B=B}) based on the player's input.                               |
| ColorPickerModuleEnum.returnType.perValue           | Returns 3 numbers in a ordered way: R, G, B based on the player's input.                                                      |