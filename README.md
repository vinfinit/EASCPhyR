# EASCPhyR - Evolutionary Algorithms in Single-Cell Phylogeny Reconstruction

## How to use
```bash
./eascpr
```

## Input format
**eascpr** accepts the following input format

| Mut_0 | Mut_1 | Mut_2 | Mut_3 | Mut_4 |
|-------|-------|-------|-------|-------|
| 1     | 0     | 1     | 0     | 0     |
| 1     | 1     | 0     | 0     | 1     |
| 0     | 1     | 0     | 0     | 1     |
| 0     | 0     | 1     | 1     | 0     |

The first line is a dummy line of mutation names. If you don't have the mutation names use `header=0` argument.
