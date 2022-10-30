## Enum information
```lua
RESignal.SignalBehavior = {
    NewThread;
	Deferred;
	Synced;
}
```

| Mode name | Description                                                                                                                                 |
|-----------|---------------------------------------------------------------------------------------------------------------------------------------------|
| NewThread | Calls the callback on a new thread using ``task.spawn()``                                                                                   |
| Deferred  | Calls the callback on a deferred thread (runs after thread calling ``RESignal:Fire()`` has finished/yielded) using ``task.defer()``.        |
| Synced    | ^^**{==NOT YIELD-SAFE==}**^^. Execution of a connection callback is handled by the thread calling the fire function.                        |