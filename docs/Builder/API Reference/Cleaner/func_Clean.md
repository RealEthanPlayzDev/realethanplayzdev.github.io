## Function information
```lua
function Cleaner:Clean()
```

Destroys all objects on the cleanup list.

!!! danger "This WILL DESTROY all objects in the cleanup list"
    If you want to remove objects from the list but not destroy them, see [``Cleaner:Remove()``](./func_Remove.md) instead.