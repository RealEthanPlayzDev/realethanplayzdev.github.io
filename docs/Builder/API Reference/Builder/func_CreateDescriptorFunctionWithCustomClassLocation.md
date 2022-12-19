## Function information
```lua
function Builder.CreateDescriptorFunctionWithCustomClassLocation(customclasseslocation: Instance): (classname: string, description: Description?) -> Descriptor
```

Returns a function that wraps around [``Builder.Descriptor()``](./func_Descriptor.md) with the custom classes argument always passed with ``customclasseslocation``.

## Arguments
- ``customclasseslocation: Instance`` - The location where custom classes are located