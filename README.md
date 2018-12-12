# Julia vs Python Benchmarks
A short series of benchmarks to compare Julia and Python performance


### For Cycles

|                   | Python  | Numba Python | Julia    |
| ----------------- | ------- | ------------ | -------- |
| handwritten       | 260 ms  | 8.1 ms       | 8.216 ms |
| specific function | 4.24 ms | -----        | 3.561 ms |

### Dot product of 1000x1000 matrices

|                   | Python  | Numba Python | Julia     |
| ----------------- | ------- | ------------ | --------- |
| specific function | 19.8 ms | 17.2 ms      | 19.094 ms |

### Γ(30) function

|                   | Python | Numba Python | Julia     |
| ----------------- | ------ | ------------ | --------- |
| handwritten       | 415 µs | 73.2 µs      | 49.599 μs |
| specific function | 935 ns | -------      | 94.676 ns |

### Vectorized sin function over several elements

|           | Python  | Numba Python | Julia     |
| --------- | ------- | ------------ | --------- |
| 5 elem    | 980 ns  | ------       | 56.376 ns |
| 1000 elem | 11.1 µs | ------       | 11.100 μs |


