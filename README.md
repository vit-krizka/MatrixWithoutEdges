# MatrixWithoutEdges

## Exercise

- write a method RemoveEdges()
- that method should takes matrix (square or not-square) as parameter
- that method should return new matrix which will be the same as input matrix but without all four edges
- write at least two tests (one for edge case)

## Input & Output

### Input 1
```
[
  [1, 0, 1, 5, 4],
  [0, 2, 2, 2, 7],
  [1, 2, 5, 3, 7],
  [4, 0, 4, 7, 1],
  [0, 2, 9, 6, 2],
]
```

### Output 1
```
[
  [2, 2, 2],
  [2, 5, 3],
  [0, 4, 7]
]
```

### Input 12
```
[
  [0, 0, 0, 0, 0],
  [0, 2, 2, 2, 0],
  [0, 2, 2, 2, 0],
  [0, 0, 0, 0, 0]
]
```

### Output 1
```
[
  [2, 2, 2],
  [2, 2, 2]
]
```
