# Lists

---

Lists are a special type of datatype which can hold multiple values within it

Lists can hold any type of datatype within it

Lists start at an index of 0(like most things in the virtual world), instead of 1

---

## Things about Lists

### Declaring an List

```python
lst = [ ]
```

This makes an empty list named `lst`

### Adding objects to an List

```python
lst = [ ]
lst.append("Cars")
```

This adds the string "Cars" to the list `lst`. The list now looks like this

```python
> ["Cars"]
```
### Modifying the first item in the List

```python
lst = ["Cars", "Candy", "Apple"]
lst[0] = "Doofus"
```

This will take the item in the 0th index, and replace the previous value with the new value provided. The list now looks like this

```python
> ["Doofus", "Candy", "Apple"]
```

### Find the length of an List

```python
lst = ["Cars", "Candy", "Apple"]
length = len(lst)
```

This will use the `len()` function on the list, `lst`, the is passed in, and give the variable 'length' the length of the list. The value of length is

```python
> 3
```

### Popping an item from an List

```python
lst = ["Cars", "Candy", "Apple"]
lst.pop(1)
```

This will use the `pop()` function to remove the item at index number 1. This will result in the list `lst` being

```python
> ["Cars", "Apple"]
```

### Removing an item from an List

```python
lst = ["Cars", "Candy", "Apple"]
lst.remove("Candy")
```

This will use the `remove()` function to remove the item with the value specified between the parenthesis. It will result in the list `lst` being

```python
> ["Cars", "Apple"]
```

### Clearing an List

```python
lst = ["Cars", "Candy", "Apple"]
lst.clear()
```

This will clear the list, resulting in there being an empty list. It will result in the list `lst` being

```python
> [ ]
```

### Finding the index of an item in an List

```python
lst = ["Cars", "Candy", "Apple"]
index = lst.index("Apple")
```

This will find the item with the value "Apple" in the list `lst` and return the index of its first occurence in the list. It will then store it in the index variable. The index variable, in the end, will hold the value

```python
> 2
```

### Sorting an List

```python
lst = ["Cars", "Candy", "Apple"]
lst.sort()
```

This will sort the list `lst` by ascending to descending. It will result in `lst` being

```python
> ["Apple", "Candy", "Cars"]
```

### Reversing an List

```python
lst = ["Cars", "Candy", "Apple"]
lst.reverse()
```

This will reverse the list `lst`. It will result in `lst` being

```python
> ["Apple", "Candy", "Cars"]
```