```lua
ColorPickerModuleEnum ColorPickerModuleEnum.returnType
```

Contains 4 enum members:

| Member             | Description                                                                                                                      |
| ------------------ | -------------------------------------------------------------------------------------------------------------------------------- |
| brickColor         | Indicates that the return type will be a [``BrickColor``](https://developer.roblox.com/en-us/api-reference/datatype/BrickColor). |
| color3             | Indicates that the return type will be a [``Color3``](https://developer.roblox.com/en-us/api-reference/datatype/Color3).         |
| rgbTableDictionary | Indicates that the return type will be a dictionary table with keys R, G, and B ({R=R, G=G, B=B})                                |
| perValue           | Indicates that the return type will be a 3 numbers in a ordered way: R, G, B                                                     |

## Used by
* [``ColorPickerModule.promptPickColor()``](/ColorPickerModule/API Reference/func_promptPickColor)