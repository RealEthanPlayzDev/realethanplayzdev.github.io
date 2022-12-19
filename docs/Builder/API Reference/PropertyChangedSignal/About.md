``PropertyChangedSignal`` is a extended [``Resolvable``](../Resolvable/About.md) class that handles property changes by connecting the passed function handler using ``(Instance | Class):GetPropertyChangedSignal()``.

!!! bug "Custom classes note"
    If you are using this in a custom class based [``Description``](../Types/type_Description.md), ensure it has a ``GetPropertyChangedSignal`` function, the first argument will be a string containing the target property name. It's expected to return a ``RBXScriptSignal`` (or anything with a ``:Connect()`` function)

Using it in a [``Description``](../Types/type_Description.md):
```lua
{
    [Builder.PropertyChangedSignal("PropertyName")] = function() return end
}
``` 