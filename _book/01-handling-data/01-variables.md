# Variables

```let x = 20; ```

Variables are the most used thing in programming. They allow us to hold onto and track values in our computers memory, and use them in different places in our applications and files.

## What Are Variables
Variables, also sometimes called bindings, are a connection between a word, and a place in computer memory where data is stored. So a variable is not the actual data stored, nor is it the name we call it, but the connection between the two.

Using variables allows us to handle data in applications, and not loose track of data as soon as it is created. 

## Creating Variables
### Declaration
When we declare a variable in JavaScript, we do so by using one of three keywords, ```let```, ```var```, and ```const``` followed by a name. We will primarily use ```let```, but the reason behind this is beyond the scope of our prework.

```let num;```

Here we are using ```let``` to *declare* a *variable* named ```num```.

### Assignment

If you compare the example in Declaration with the example at the top of this page, you'll notice it's missing a part. We call that part *assignment*. It's where we *assign* the value, and store that value in memory.

When we assign a variable a value, we use the *assignment operator*, which you may know as an equal sign. When we run our code, JavaScript will attempt to store anything on the right hand side as a value.

```let num = 20;```

In this example, we're *declaring* ```num```, and we're also *assigning* it a value of 20, since 20 is on the right hand side of the *assignment operator*.

## Naming Variables
### Camel Casing
In programming different languages have different conventions. In JavaScript we use something called *camel casing*, which is where the first letter of the first word is undercased, but the first letter of every subsequent word is uppercased. So if we wanted to write Eleven Fifty Academy in camel casing, we would write ```elevenFiftyAcademy```. Use camel casing for names of variables in JavaScript.

### Reserved Words
Some words in JavaScript as reserved, they could be keywords, classes, or methods. What exactly those are is out of scope for now, but it is important to know that not all words are valid names for variables.


### Numbers in Variable Names
There are a few things to be aware of with numbers in variable names. 

First, a variable cannot start with a numeric character. The following example will not work.

```let 2nums = [ 1, 2 ];```

You should also stay away from numeric characters in the variable's name.

```let num1 = 2;```

```let numOne = 2;```

The second line of this example is considered best practice.


## Code Dissection
* Show examples and code dissections of declarations, initializations, and let const and var

[code image with dissection]

[notes about dissection]

## Code Demo
[video here]

## Exercises
Practice on your own by creating a few variables the have numeric values.

Then try declaring a few variables, *without* assigning them values.

Use ```console.log()``` to print the value of those variables to the console.

## Additional Practice
For extra practice with variables, try the above exercises again. Then by hand. You can also write out the code by hand, and annotate the code with your own words.