## RESignal
RESignal is my own vanilla luau signal implementation, with 3 modes:

| Mode name | Description                                                                                                                                 |
|-----------|---------------------------------------------------------------------------------------------------------------------------------------------|
| NewThread | Spawns the callback of a connection on a new thread using ``task.spawn()``                                                                  |
| Deferred  | Spawns the callback of a connection on a deferred thread (run callbacks after the thread calling Fire has finished) using ``task.defer()``. |
| Synced    | **NOT YIELD-SAFE**. Execution of a connection callback is handled by the thread calling the fire function.                                  |

## Get the module
- [GitHub gist](https://gist.github.com/RealEthanPlayzDev/c66c91006d75fc89c43171a372587bdb) (includes benchmark script)

## :Fire() benchmark times
**TODO**: As of v2.0.0, RESignal requires to be benchmarked again.
