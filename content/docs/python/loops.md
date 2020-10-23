# Loops

---

What are loops? Loops are used for doing a task a specific number of time, but it also has other uses which we will be exploring below and later on

---

## Types of Loops

There are two types of loops that we will be introducing here

* For Loops
* While Loops

---

## For Loops

Usually, `for loops` are used for iterating over a sequence of objects

Here is an example in which we see that we have a list and we use the `for loop` to print out items in the list one by one

``` python
team = ['Pichu', 'Pikachu', 'Raichu']
for pokemon in team:
    print(pokemon)
```

This will result in the following being printed out to console

``` 
Pichu
Pikachu
Raichu
```

What we did here was first we make a list named `team` which ended up including string objects. The second like essentially said, for every `pokemon` in list `team` , `print` the `pokemon` object

So that is why we had the names of the `pokemon` inside `team` printed out

---

## While Loops

We have seen what we can use `for loops` for, now lets see what we can do with a `while loop` . In a while loop, we have to set a condition, and it will continue to run **until** the condition is deemed to be false

Here is the basic syntax of the `while loop`

``` python
while(condition is true):
    run code
```

As stated before, if the condition is true, only then the code run

{{< hint danger >}}

If the condition never turns false, the `while loop` will keep on running infinitely, which will cause your program to crash
{{< /hint >}}

Here is an example of a `while loop` which will do the same thing that we did using the `for loop` before

``` python
team = ['Pichu', 'Pikachu', 'Raichu']
index = 0
while index < len(team):
    print(team[index])
    index += 1
```

|Line Number|Explanation|
|---|---|
|1|Here we are defining a list named `team` with the elements `'Pichu', 'Pikachu', 'Raichu` (which are strings) in it|
|2|We are defining a counter variable, named `index` , for the condition which will track our location within the list. Remember that the index of a list will start at 0 and not 1|
|3|Here we are entering our `while loop` , the condition we are setting is that as long as the value of our counter variable, `index` , does not exceed nor equal the value of the length of the list, we will continue|
|4|We are now using the counter variable, `index` , to access the current item in the list, `team` , and printing it out|
|5|Finally, we are adding a `1` to the value of the counter variable, `index` , each time the `while loop` runs. Without this, we will be accessing the same item over and over again, and the condition will also not even turn false, resulting in a infinite loop|
