!!! warning "This is a abstract class"
    This class has no real use other than as a abstract class to be extended.

``Resolvable`` is a object that you can put in a [``Description``](../Types/type_Description.md), when [``Descriptor:Build()``](../Descriptor/func_Build.md) is called, if it finds a ``Resolvable`` object it will call [``Resolvable:Resolve()``](./func_Resolve.md) to resolve the object.