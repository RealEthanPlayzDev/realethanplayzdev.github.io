## Function information
```lua
function Builder.WrappedTypeof(class: any): string
```

This is a wrapped ``typeof()`` function to also support ``Builder``'s custom classes (it checks for ``class["__type"]``)

Returns the class name

## Arguments
- ``class: any`` - The class to check the class name