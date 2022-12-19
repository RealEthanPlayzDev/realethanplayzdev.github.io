## Function information
```lua
function Builder.WrappedInstanceNew(classname: string, customclasslocation: Instance?)
```

This is a wrapped ``Instance.new`` function to also support custom classes. See [this page](../../CustomClasses.md) for more information regarding custom class support.

Returns newly constructed class/object/instance.

!!! bug "Can throw error"
    Ensure that the ``classname`` is correct, if it's a custom class, ensure the module returns a table with a ``new`` function as the constructor otherwise it will fallback to Roblox's ``Instance.new``.

## Arguments
- ``classname: string`` - The target class name to be constructed
- ``customclasslocation: Instance?`` - Alternative custom class search location