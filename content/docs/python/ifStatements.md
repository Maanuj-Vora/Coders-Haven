# If Statements

---

If Statements are composed of some parts

---

``` python
if(condition):
  code
elif(condition):
  code
else:
  code
```

---

## Breaking it down

* if -> if
  + needs a condition
* elif -> else if
  + needs a conditions
  + the second condition
  + you can have as many of these as you want
* else -> else
  + does not need a condition

---

### There are 3 Rules

1. {{< hint danger >}}

NEVER, NEVER EVER, call a If Statment an If Loop
{{< /hint >}}

2. {{< hint info >}}

The conditions will almost always use operators
{{< /hint >}}

3. {{< hint info >}}

The conditions have to be true for a block of code to execute
{{< /hint >}}

---

## Examples

``` python
x = 4
if(x < 5):
  print("James is super smart")
elif(x == 6):
  print("The smartest boi in the world is currently traveling")
else:
  print("James is a smartie")
```
