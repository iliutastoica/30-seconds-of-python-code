### difference

Returns the difference between two iterables.

Use list comprehension to only keep values not contained in `b`.

```python
def difference(a, b):
    _b = set(b)
    return [item for item in a if item not in _b]
```
``` python
difference([1, 2, 3], [1, 2, 4]) # [3]
```
