## Function information
```lua
function Builder.Descriptor(classname: string, description: Description?, customclasseslocation: Instance?): Descriptor
```

Returns an [``Descriptor``](../Descriptor/About.md) with the base class as ``classname`` and [description](../Types/type_Description.md) as ``description``.

If you want to use a specific custom class location without wanting to pass the location to ``customclasseslocation``, consider using [``Builder.CreateDescriptorFunctionWithCustomClassLocation()``](./func_CreateDescriptorFunctionWithCustomClassLocation.md) that will give you a wrapper around this function with the ``customclasseslocation`` argument always passed with the custom class location you specified at that function.

## Arguments
- ``classname: string`` - The base/root classname
- ``description: Description?`` - The description of the [``Descriptor``](../Descriptor/About.md)
- ``customclasseslocation: Instance?`` - Alternative custom class search path