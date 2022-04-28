# MatrixWithoutEdges

## Exercise

- write a method `RemoveEdges()`
- that method should take matrix (squared or not-squared) as parameter
- that method should return new matrix which will be the same as input matrix but without all four edges
- write at least two tests (one for expected case and one edge case)

## Inputs & Outputs

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

### Input 2
```
[
  [0, 0, 0, 0, 0],
  [0, 2, 2, 2, 0],
  [0, 2, 2, 2, 0],
  [0, 0, 0, 0, 0]
]
```

### Output 2
```
[
  [2, 2, 2],
  [2, 2, 2]
]
```


# MatrixWithoutEdges - advanced

## Exercise

- write a method `RemoveEdges()`
- that method should take matrix (squared or not-squared) as parameter
- that method should return new matrix which will be the same as input matrix but without all four edges but when you removing edges of a not-squared array, only ends of longest rows are to be removed, as shown in example 2 bellow
- write at least two tests (one for expected case and one edge case)

## Inputs & Outputs

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

### Input 2
```
[
  [7, 4],
  [2, 4, 1],
  [3, 6, 3, 2],
  [5, 2, 5, 3, 7],
  [1, 3],
  [4, 0, 1, 6, 4],
  [9, 6, 2],
]
```

### Output 2
```
[
  [4, 1],
  [6, 3, 2],
  [2, 5, 3],
  [3],
  [0, 1, 6],
]
```

### Input 3
```
[
  [0, 0, 0, 0, 0],
  [0, 2, 2, 2, 0],
  [0, 2, 2, 2, 0],
  [0, 0, 0, 0, 0]
]
```

### Output 3
```
[
  [2, 2, 2],
  [2, 2, 2]
]
```
