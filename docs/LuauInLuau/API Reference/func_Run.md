## Function info
```lua
function LuauInLuau.LuauRun(src: string, safeenv: boolean?, optimizationlevel: number?, debuglevel: number?): boolean
```

Compiles and runs Luau code

## Arguments
- ``src: string`` - The source
- ``safeenv: boolean?`` - Indicates whether safeenv features should be enabled or not
- ``optimizationlevel: number?`` - The optimization level for the resulting bytecode
- ``debuglevel: number?`` - The debug level for the resulting bytecode

!!! bug "Important note regarding the optimization and debug level arguments"
    The ``optimizationlevel`` and ``debuglevel`` argument is only available starting with LuauInLuau v0.579