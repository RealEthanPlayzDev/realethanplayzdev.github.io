Builder is a instance building system, similar to Roact and Fusion.

Builder uses a object called [``Descriptor``](./API%20Reference/Descriptor/About.md) to build instances, it contains a description of the instance you want to build.

Builder has additional objects to support you in building a [``Descriptor``](./API%20Reference/Descriptor/About.md):

- [``Event``](./API%20Reference/Event/About.md) - An object to help with connecting to a event when building instances.
- [``Method``](./API%20Reference/Method/About.md) - An object to help with calling a method when building instances.
- [``PropertyChangedSignal``](./API%20Reference/PropertyChangedSignal/About.md) - An object to help with detecting property changes when building instances.
- [``Attribute``](./API%20Reference/Attribute/About.md) - An object to help with setting a attribute when building instances.
- [``AttributeChangedSignal``](./API%20Reference/AttributeChangedSignal/About.md) - An object to help with detecting attribute changes when building instances.
- [``MultiStateResolvable``](./API%20Reference/MultiStateResolvable/About.md) - An object to help with setting a property with a state from a [``MultiState``](./API%20Reference/MultiState/About.md).

Builder also has 2 basic state systems:

- [``State``](./API%20Reference/State/About.md) - An object to store a state, like a variable.
- [``MultiState``](./API%20Reference/MultiState/About.md) - An object to store multiple states, similar to dictionaries.

Builder also has support for custom classes, just ensure it's inside a modulescript, and returns a table with a ``new`` field as the constructor for the class. See [this page](./CustomClasses.md) for more information.

Upon requiring the module, it will return the [``Builder``](./API%20Reference/Builder/About.md) class.

## Get the module
- [GitHub Repository](https://github.com/RealEthanPlayzDev/Builder)