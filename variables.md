

```python
a=1; print(type(a))
```

    <class 'int'>
    


```python
a=1; a=float(a); print(type(a))
```

    <class 'float'>
    


```python
a=1.2; a=int(a); print(type(a))
```

    <class 'int'>
    


```python
a='123'; print(type(a)); print(a[1])
```

    <class 'str'>
    2
    


```python
a='123' ; a=list(a); print(type(a)); print(a); print(a[2])
```

    <class 'list'>
    ['1', '2', '3']
    3
    


```python
a = [1,'2', [3, '4']]; print(type(a)); print(a[0]); print(a[1]); print(a[2])
```

    <class 'list'>
    1
    2
    [3, '4']
    


```python
a = (1,'2', [3, '4']); print(type(a)); print(a[0]); print(a[1]); print(a[2])
```

    <class 'tuple'>
    1
    2
    [3, '4']
    


```python
a = {"a": "apple", "b": "orange", "c": 2014}
print(type(a))
print(a["a"])
```

    <class 'dict'>
    apple
    


```python
a=[(1,2,3), (3,8,0)]
print(type(a))
a
```

    <class 'list'>
    




    [(1, 2, 3), (3, 8, 0)]




```python
import numpy as np
b = np.array(a)
print(b)
print(type(b))
```

    [[1 2 3]
     [3 8 0]]
    <class 'numpy.ndarray'>
    


```python
print(b*b)
```

    [[ 1  4  9]
     [ 9 64  0]]
    


```python
c = np.matrix(b)
print(c)
print(type(c))
```

    [[1 2 3]
     [3 8 0]]
    <class 'numpy.matrixlib.defmatrix.matrix'>
    


```python

```
