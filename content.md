If we create a range and pass it to the `list()` function, the result will be a list whose elements correspond to the numbers in the range. For example:

```py-cell
x = list(range(2, 10, 2))
print(x)
```

This is an efficient way to create a list if the elements follow a predictable numerical pattern defined by the range.