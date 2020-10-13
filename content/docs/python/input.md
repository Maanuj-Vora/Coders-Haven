# Input

---

The input() function will pose a prompt to the user, in which the answer to the question will be returned to the program

Remember that all responses will be stored in a string even if they are numbers, so use casting!

---

For example, if I wanted to make a greeting with the user's name, I would need them to input their name into my code for me to use it

```python
name = input('Hello user, what is your name?')
```

This first prints out the statement, `Hello user, what is your name?` to the console, and then waits for the user input. After getting the user input, it then goes off and stores it into the variable, named `name`

To print out a greeting to the user, we would do

```python
print('Hello' + name)
```

Now, if we actually used this, it would go like this

```
Hello user, what is your name? Sleepy
Hello Sleepy
```

Great! But what if we wanted to make a mini-calculator and add two numbers together?

Well, if we did it like it was defined above, we would do

```python
num1 = input('Please enter your first number')
num2 = input('Please enter your second number')
print(num1+num2)
```

Cool, now let us run this

```
Please enter your first number 5
Please enter your second number 10
510
```

Well, it looks like we are doing some basic caveman math here. Well, why did it only combine the two inputs and not actually 'add' them?

The `input()` function takes in an input and keeps it is a string. Wait, a `string`, but don't we want to add two numbers together? This is where casting comes in

We will cast the two inputs we get into integers, and then add them

```python
num1 = int(input('Please enter your first number'))
num2 = int(input('Please enter your second number'))
print(num1+num2)
```

Now let us run this

```
Please enter your first number 5
Please enter your second number 10
15
```

Nice, now it works