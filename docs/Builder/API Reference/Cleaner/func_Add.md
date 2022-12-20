## Function information
```lua
function Cleaner:Add(... : any)
```

Adds objects passed to the function as a argument to the cleanup list, if a table was passed, then iterate through the values and put them to the cleanup list.

## Arguments
- ``... : any`` - The objects to be put in the cleanup list