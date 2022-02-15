## Function info
```lua
function GeometryLinesBackground:SetAmountOfDots(newamount: number)
```

Sets the amount of dots.

!!! error "Calling this function while the renderer is still active will error"
    Calling this function while the renderer is still active will cause a error! Ensure the renderer is already off before calling this function.

!!! warning "Do not set high amount of dots!"
    This module is probably unefficient! Do not set a high amount of dots to prevent perfomance issues.

## Arguments
- newamount: number - The new amount of dots in numbers.