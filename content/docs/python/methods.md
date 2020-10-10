# Methods

---

{{< hint warning >}}
A general rule of thumb is, if you are copying and pasting a lot, then you are doing something wrong
{{< /hint >}}

---

## What is a Method?

Well, a method is simply a chunk of code, that can be called over and over again by the name it is give

Here is an example of a method that prints out `Hello World` when it is called

``` python
def helloWorld():
    print('Hello World')
```

And to use this method to do our bidding, we would call the following code

``` python
helloWorld()
```

Which should print out

``` python
'Hello World'
```

---

## Is that all a Method is Capable of Doing?

No.

We can also pass in objects into methods for them to use, these are called `inputs` as they are being inputted into the method. This is handy as sometimes the values we need to use change, and by using a variable input, we can have more uses for the same method

Here is how you would define a method that prints out a customized greeting

``` python
def greeting(name):
    print('Hello ' + name)
```

And to use this method to do our bidding, we would call the following code

``` python
name = 'Maanuj'
greeting(name)
```

We can also call it like this way as well, and it doesn't make a difference

``` python
greeting('Maanuj')
```

These two ways, should print out the same thing, being

``` python
'Hello Maanuj'
```

---

## The `return` keyword

What if, instead of printing something out to the console, we want the code to run calculation, but keep it for future use?

In this case, we would use the `return` keyword

What it does is when the method runs, the thing you want outputted from the method is stated after the `return` keyword, and then the method essentially *becomes* that value

Here is an example

``` python
def helloWorld():
    return 'Hello World'
helloWorldStr = helloWorld()
print(helloWorldStr)
```

What this is doing is that it first defines the `helloWorld()` method for use later. Then it creates a variable, `helloWorldStr` and assigns it the value you get from running `helloWorld()` . After that, the method, `helloWorld()` returns the string `'Hello World'` , which is then stored into the variable `helloWorldStr` . Then, the variable is printed out, and we get

``` python
'Hello World'
```

Even though we could have just called `print('Hello World')` , and have finished it in one line, the importance of this piece of code comes into play when you have to run the same piece of code multiple times

---

## Problem Time

Here is a mini-problem for you to code

You are an employee of a start-up company, *EZ Addition*, which is in the works of creating a calculator which can add two numbers together and print out the sum. With your new found coding skills, your boss comes up to you and wants you to create a piece of code, which asks the user for two numbers to add, and then prints out the addition of those two numbers. He also wants you to make it simple since the company wants to reuse the code in multiple places.

Your task: Create the piece of software that the company wants

{{< details title="Click here after attempting it" open=false >}}
Here is one possible way to solve this question

``` python
def addition(num1, num2)
    print(num1 + num2)
num1 = int(input('Please enter in the first number'))
num2 = int(input('Please enter in the second number'))
addition(num1, num2)
```

What we did here was we first created a method, named `addition` , which took in two parameters, `num1` and `num2` , and printed out the addition of them. In the third line, we asked the user for the number, and casted it into an integer, which would let us add the numbers together. Then when we called the method with the inputs, `addition(num1, num2)` , it printed out the sum we wanted
{{< /details >}}
