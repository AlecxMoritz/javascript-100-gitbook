# Numbers and Operators

<!-- numbers -->
## Numbers in JavaScript
When you hear the word number, one usually thinks of things like 1, two, or some larger number. While that isn't exactly wrong, it may not be exactly correct.

In Javascript, when we talk about 'numbers', we are usually referring to a *type* of value. You will see in the next few modules different types of values in JavaScript, but we'll only be talking about numbers for now.

When we say that a variable is 'of type' number. We mean that the value stored in that variable is of numeric value. 

<!-- Operators -->
## Operators
In reference to programming, an operator is a symbol that will execute some kind of action or comparison between values, or variables. The most basic is an addition operator, you can even think of this outside of coding.

If you have 2 + 2. The plus sign is an addition operator, and the values on either side of it will be added. 


### Basic Operators
Most of these should look a bit familiar from simple mathematics. All of them take the values on either side of them, and perform some kind of math.

|Symbol|Name                    |
|------|------------------------|
|+     | Addition Operator      |
|-     | Subtraction Operator   |
|*     | Multiplication Operator|
|/     | Division Operator      |

Lets look at a few examples. What do you think they would print? Try making a guess before you run your code.

```console.log(4 + 4);```

```console.log(10 - 3);```

```console.log(0 * 10);```

```console.log(25 / 5);```

### Shorthand Operators
Let's say we wanted to do some math. We store a number value of 5 in a variable called ```num```

```let num = 5```

What if we wanted to add three onto our new value? We could write that like

```num = num + 5```

Or we could use something known as *shorthand operators*. They are baked into JavaScript, and allow us to do simple mathematical operations with less typing. They're very common.

|Symbol|Name                               |
|------|-----------------------------------|
|+=    | Short Hand Addition Operator      |
|-=    | Short Hand Subtraction Operator   |
|*=    | Short Hand Multiplication Operator|
|/=    | Short Hand Division Operator      |
|++    | Increment Operator                |
|--    | Decrement Operator                |

Lets look at a short hand example for the addition operator.

```num += 5```

This operator will take the original value of num, add five to it, and then store that in the variable ```num```. The other three operators below the addition operator work in the same way, and have similar usage. The two new ones at the bottom are used to either increment or decrement a numeric value. Lets write some examples and see what prints when we run it. Again, try to make predictions for what will print out when we run. Then compare your guess to what actually came out. Was it different than you expected? 

```let num = 5```

```console.log(num -= 2); //3```

```console.log(num *= 4); //12```

```console.log(num /= 3); //4```

```console.log(num++);```

```console.log(num--);```

## Modulus
*Modulus* is it's own, special type of operator, that will calculate the remainder after two values of have been divided. So if we wrote

```console.log(2 % 1);```

It should return 0. Since one can be divided into 2 twice without any remainder.

## Deep Dive
[disection graphic]

[disection conversation points]

## Code Along
[code video here]


## Exercises
Try making ten different variables. ```console.log()``` them with various different operators like we did in the examples and video for practice. 

## Extra Practice
If it's still feeling fuzzy, write them out by hand. Try to predict what value the computer will spit back out. Then write the code and run it to see how close you where.