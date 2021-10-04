!!! warning
    The module is designed for use in the server!

!!! danger "IMPORTANT"
    This module is __**no longer maintained**__!

## **Enum** ``module.Enum.returnType``
For usage in ``module.promptPickColor()``

Available members:

* brickColor - Tells ``module.promptPickColor()`` to return a ``BrickColor`` instead.
* color3 - Tells ``module.promptPickColor()`` to return a ``Color3`` instead.
* rgbTableDictionary - Tells ``module.promptPickColor()`` to return a ``table`` dictionary with the keys, R, G, B (``{R: number, G: number, B: number}``).
* perValue - Tells ``module.promptPickColor()`` to return 3 values, respectively R, G, and B.

## **function** ``module.promptPickColor(player: Player, allowCancel: boolean, returnType: module.Enum.returnType)``
Prompts the selected ``player`` to pick a color, if ``allowCancel`` is true then the player can cancel and the function will return false, if ``returnType`` is passed as a argument then the function will return based on the picked type (See Enum module.Enum.returnType)