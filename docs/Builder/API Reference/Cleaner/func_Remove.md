## Function information
```lua
function Cleaner:Remove(... : any)
```

Removes the objects passed to the function as arguments if it exists in the list.

!!! danger "This does NOT destroy the object"
    The point of this function is to remove the object from the cleanup list, not destroy it. For destroying everything in the list, see [``Cleaner:Clean()``](./func_Clean.md).

## Arguments
- ``... : any`` - The objects to be put in the cleanup list