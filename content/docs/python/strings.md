# Strings

---

You know that Strings are one type of datatype, but there is more to Strings than just that

---

### Strings are like arrays

You can get a certain character at a specific position in a string like an array using an index.

``` python
a = "Hello World"
print(a[1])
```

This will print out

``` python
e
```

since the character `'e'` is at the first index of the String

### The length of a string

You can get the length of a string using the `len()` function

``` python
a = "Hello World"
print(len(a))
```

This will return

``` python
11
```

since there are 11 characters in the string

01. H
02. e
03. l
04. l
05. o

6.

07. W
08. o
09. r
10. l
11. d

### Removing blanks in a string

You can remove leading or trailing blanks in a string using the `strip()` function

``` python
a = " Hello World "
print(a.strip())
```

This will return

``` python
Hello World
```

Without any leading or trailing empty spaces

### Lowercasing the String

The `lower()` method will lowercase the characters in a string

``` python
a = "Hello World"
print(a.lower())
```

This will return

``` python
hello world
```

### Uppercasing the String

The `upper()` method will uppercase the characters in a string

``` python
a = "Hello World"
print(a.upper())
```

This will return

``` python
HELLO WORLD
```

### Replacing characters in a String

The `replace()` method will replace strings with a different string in a string

``` python
a = "Hello World"
print(a.replace("H", "J"))
```

This will return

``` python
Jello World
```

### Splitting a String

The `split()` method will split a string into an array if there is an occurence of a certain string

``` python
a = "Hello World"
print(a.split("l"))
```

This will return

``` python
["He", "", "o Wor", "d"]
```

### Checking if a string is present

The `in` keyword and `not in` keywords can help distinguish whether a certain string is present in a string or not (resulting in a boolean)

``` python
txt = "Hello World"
x = "llo" in txt
print(x)
```

This will return

``` python
True
```

### Adding variables in a string

You can use the `format()` function to easily insert variables into a string

``` python
age = 17
name = "Dino"
intro = "Hi, my name is {}, and I am {} years old"
print(intro.format(name, age))
```

This will return

``` python
Hi, my name is Dino, and I am 17 years old
```

### Special Characters in Strings

There are some special characters within strings

* `\n`
  + New line
* `\\`
  + Backslash
* `\t`
  + Tab
* `\r`
  + Carriage Return

### Finding the index of a certain part

You can find the index of a certain string within the string

``` python
a = "Hello World"
print(a.index("l"))
```

This will return

``` python
2
```

It returned the index of the first occurence of the string within the original string
