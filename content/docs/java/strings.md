# Strings

---

In Java, Strings have many different functions which can be applied to them.

---

## `indexOf()`

With the `indexOf()` function, you can check for the first occurrence of a String inside of another String

``` java
String longStr = "Hi, my name is Kai, and I like Pi";
int indexStr = longStr.indexOf("Kai");
System.out.println(indexStr);
```

This would print out the following to the console

``` 
15
```

This returns the index of which the first character of the String `Kai` is located at, which is 15

We can see this with the following table

| Index Number | Character |
| --- | --- |
| 0 | `H` |
| 1 | `i` |
| 2 | `,` |
| 3 | ` ` |
| 4 | `m` |
| 5 | `y` |
| 6 | ` ` |
| 7 | `n` |
| 8 | `a` |
| 9 | `m` |
| 10 | `e` |
| 11 | ` ` |
| 12 | `i` |
| 13 | `s` |
| 14 | ` ` |
| 15 | `K` |

Here we can see that at the 15th index, it contains the character `K` from the String `Kai` , and it returns the integer `15` , the index

---

## `subString()`

With the `subString()` function, you can get a smaller String out of a larger String

``` java
String longStr = "Hi, my name is Kai, and I like Pi";
String subStr = longStr.substring(0,5);
System.out.println(subStr);
```

This would print out the following to the console

``` 
Hi, m
```

Basically what it is doing here is that it takes the input `(startIndex, endIndex-1)` , as we have seen, we inputted the startIndex as `0` and the endIndex as `5` , but it will only go up till `4`
| Index Number | Character |
| --- | --- |
| 0 | `H` |
| 1 | `i` |
| 2 | `,` |
| 3 | ` ` |
| 4 | `m` |

The table above shows our indexes within the String

Another example is shown here

``` java
String longStr = "Hi, my name is Kai, and I like Pi";
String subStr = longStr.substring(2);
System.out.println(subStr);
```

This would print out the following to the console

``` 
, my name is Kai, and I like Pi
```

Wait, but didn't you just say that the `subString()` function took in two values? Why are you inputting in one value now?

Well, we can also do it with one value, it will go from that index, to the end of the String and return that subString-ed String

| Index Number | Character |
| --- | --- |
| 0 | `H` |
| 1 | `i` |

---

## Adding Strings

Did you know that you can add two Strings together to make one whole String?

``` java
String basic = "H";
basic = basic + "i";
System.out.println(basic);
```

This would print out the following to the console

``` 
Hi
```

What we did, is we took the original String, `"H"` , and we took another String, `"i"` , and added them both together, to make `"Hi"`
We can also do this in a slightly different way

``` java
String basic = "H";
basic += "i";
System.out.println(basic);
```

This would print out the following to the console

``` 
Hi
```

The only thing that changed was the operator of adding. The `+=` basically takes whatever was there and adds to it

One more thing, you can also add a String and an Integer together

``` java
String basic = "H";
basic += 1;
System.out.println(basic);
```

This would print out the following to the console

``` 
H1
```

This converts the int, `1` to a String, `"1"` , and adds it to the String, to make a string `"H"`
