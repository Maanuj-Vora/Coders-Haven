# Casting

---

Casting is used to switch one type of datatype into another through certain functions

## Whats the point?

It is neccessary to know this since inputs are recieved in the form of strings, and if you wanted a numerical input from the user you would not be able to without the use of casting

---

## Functions for Casting

---

### `int()`

The `int()` function will cast anything inside the parenthesis into an integer, only if it is possible to

This will round down any decimal values inputted

``` python
int("5")
> 5

int("10")
> 10

int("10.4")
> Error

int(10.1)
> 10

int(10.44)
> 10

int("Hi")
> Error

int(True)
> 1

int(False)
> 0
```

---

### `str()`

The `str()` function will convert anything between the parenthesis into a String object if possible(which the answer is it usually is)

``` python
str(5)
> "5"

str(6.11)
> "6.11"

str(True)
> "True"

str("String")
> "String"
```

---

### `float()`

The `float()` function will convert anything between the parenthesis into a float, only if it is possible to do

``` python
float(5)
> 5.0

float(5.1111)
> 5.1111

float("5.1241")
> 5.1241

float(True)
> 1.0

float(False)
> 0.0
```

---

### `bool()`

Will return a True of False value of anything inputted into the parenthesis

Essentially, it will return True for anything inside if it is not a 0 nor empty

``` python
bool(10)
> True

bool(1000.001212144)
> True

bool(0)
> False
```
