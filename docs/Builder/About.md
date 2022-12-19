Builder is a instance building system, similar to Roact and Fusion.

Builder uses a object called [``Descriptor``](./API%20Reference/Descriptor/About.md) to build instances, it contains a description of the instance you want to build.

Builder has additional objects to support you in building a [``Descriptor``](./API%20Reference/Descriptor/About.md):

- ``Event`` - An object to help with connecting to a event when building instances using a [``Descriptor``](./API%20Reference/Descriptor/About.md)
- ``Method``
- ``PropertyChangedSignal``
- ``Attribute``
- ``AttributeChangedSignal``
- ``MultiStateResolvable``

Builder also has 2 basic state systems:

- ``State`` - An object to store a variable
- ``MultiState`` - An object to store multiple variables, similar to dictionaries

Builder also has support for custom classes, just ensure it's inside a modulescript, and returns a table with a ``new`` field as the constructor for the class. See [this page](./CustomClasses.md) for more information.

## Get the module
Right now the module is all packed into one script, I might seperate it into multiple scripts for the sake of maintenance and readability later.

- [GitHub Gist](https://gist.github.com/RealEthanPlayzDev/fa7c8bbb06415937f93ff83d34abbd47)