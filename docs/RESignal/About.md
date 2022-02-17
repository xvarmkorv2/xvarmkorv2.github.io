## RESignal
RESignal is my own vanilla luau signal implementation, with 3 modes:

| Mode name | Description                                                                                                                                 |
|-----------|---------------------------------------------------------------------------------------------------------------------------------------------|
| NewThread | Spawns the callback of a connection on a new thread using ``task.spawn()``                                                                  |
| Deferred  | Spawns the callback of a connection on a deferred thread (run callbacks after the thread calling Fire has finished) using ``task.defer()``. |
| Synced    | **NOT YIELD-SAFE**. Execution of a connection callback is handled by the thread calling the fire function.                                  |

## Get the module
- [GitHub gist](https://gist.github.com/RealEthanPlayzDev/c66c91006d75fc89c43171a372587bdb) (includes benchmark script that benchmarks all 3 modes on RESignal, Roblox's BindableEvent, FastSignal and GoodSignal and the benchmark result, scroll down to ``RESignal.luau`` to see the source code of RESignal.)

## :Fire() benchmark times
```
Fire benchmark results:
RESignal NewThread = {
    [1] = 0.0024855999999999767
    [2] = 0.0015328000008594245
    [3] = 0.0007339999992836965
    [4] = 0.0007349999996222323
    [5] = 0.0009076000005734386
}
RESignal Deferred = {
    [1] = 0.00001320000046689529
    [2] = 0.000012900000001536682
    [3] = 0.000005899999450775795
    [4] = 0.00000920000093174167
    [5] = 0.000003200000719516538
}
RESignal Synced = {
    [1] = 0.002027099999395432
    [2] = 0.0018845999984478112
    [3] = 0.0006935999990673736
    [4] = 0.0008502999990014359
    [5] = 0.0008068000006460352
}
Roblox BindableEvent = {
    [1] = 0.002909800001361873
    [2] = 0.0007024000005912967
    [3] = 0.0007667999998375308
    [4] = 0.000668700000460376
    [5] = 0.0007311999997909879
}
FastSignal = {
    [1] = 0.003098099999988335
    [2] = 0.0007920999996713363
    [3] = 0.0006828000005043577
    [4] = 0.000713999999788939
    [5] = 0.0011694999993778765
}
GoodSignal = {
    [1] = 0.00272420000146667
    [2] = 0.0008327000014105579
    [3] = 0.0006191000011313008
    [4] = 0.0005775999998149928
    [5] = 0.0009020000015880214
}
```