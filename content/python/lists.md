# Lists

---

Lists are a special type of datatype which can hold multiple values within it

Lists can hold any type of datatype within it

Lists start at an index of 0(like most things in the virtual world), instead of 1

---

## Things about Lists

### Declaring an List

> arr = [ ]

This makes an empty list named 'arr'

### Adding stuff to an List

> arr = [ ]
>
> arr.append("Cars")

This adds the string "Cars" to the list 'arr'. The list now looks like this

> ["Cars"]

### Modifying the first item in the List

> arr = ["Cars", "Candy", "Apple"]
>
> arr[0] = "Doofus"

This will take the item in the 0th index, and replace the previous value with the new value provided. The list now looks like this

> ["Doofus", "Candy", "Apple"]

### Find the length of an List

> arr = ["Cars", "Candy", "Apple"]
>
> length = len(arr)

This will use the len() function on the list, 'arr', the is passed in, and give the variable 'length' the length of the list. The value of length is

> 3

### Popping an item from an List

> arr = ["Cars", "Candy", "Apple"]
>
> arr.pop(1)

This will use the pop() function to remove the item at index number 1. This will result in the list 'arr' being

> ["Cars", "Apple"]

### Removing an item from an List

> arr = ["Cars", "Candy", "Apple"]
>
> arr.remove("Candy")

This will use the remove() function to remove the item with the value specified between the parenthesis. It will result in the list 'arr' being

> ["Cars", "Apple"]

### Clearing an List

> arr = ["Cars", "Candy", "Apple"]
>
> arr.clear()

This will clear the list, resulting in there being an empty list. It will result in the list 'arr' being

> [ ]

### Finding the index of an item in an List

> arr = ["Cars", "Candy", "Apple"]
>
> index = arr.index("Apple")

This will find the item with the value "Apple" in the list 'arr' and return the index of its first occurence in the list. It will then store it in the index variable. The index variable, in the end, will hold the value

> 2

### Sorting an List

> arr = ["Cars", "Candy", "Apple"]
>
> arr.sort()

This will sort the list 'arr' by ascending to descending. It will result in 'arr' being

> ["Apple", "Candy", "Cars"]

### Reversing an List

> arr = ["Cars", "Candy", "Apple"]
>
> arr.reverse()

This will reverse the list 'arr'. It will result in 'arr' being

> ["Apple", "Candy", "Cars"]
