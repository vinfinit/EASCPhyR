# EASCPhyR - Evolutionary Algorithms in Single-Cell Phylogeny Reconstruction

## How to use
```bash
# Currently available only ipython notebook
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

Model evolution with dynamic MUTPB parameter:
![alt text](https://github.com/vinfinit/EASCPhyR/blob/master/images/model_mut_dynamic.png "Model evolution with dynamic MUTPB parameter")
