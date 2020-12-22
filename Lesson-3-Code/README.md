[Previous: What is RAM?](../Lesson-2-RAM/README.md)

# What is "code" ?

Code is the set of instructions that a computer understands and can execute.

## Programming Languages

Code can be written in different `programming languages`. Over the years, computer scientists all over the world have created different ones. These languages are human readable but can be understood by computers. *What programming languages do you know?*

## Let's Write Some Code!

The programming language used in this lesson is called `JavaScript`. It was designed in the 1990s for the World-Wide-Web.

### Programming Calculations

In `JavaScript`, calculations are written a lot like we would normally write them. Example:

```javascript
5 + 7 + 9 - 2
```

There are some differences:

```javascript
5 * 4 / 8 + 2 % 3
```

- \* is multiplication
- / is division
- % gets the remainder of a division

Order of operations (BEDMAS/BEMDAS) and parentheses are honored:

```javascript
5 + 6 * (4 - 3) == 11
```

> NOTE: More on `==` later

### Using RAM

Just like in *algebra*, you can create and use `variables` in programming languages to save values to be used later. Variables in programming languages can be anything, even full words (numbers and letters only)! They are assigned a value using the `=` operator. Example:

```javascript
pi = 3.14159
```

You can assign calculated values to variables:

```javascript
result = 5 + 6 * (4 - 3)
```

You can also use variables inside of calculations:

```javascript
pi = 3.14159
radius = 4.5
diameter = 2 * radius
circumference = diameter * pi
areaOfCircle = pi * (radius * radius)
```

Variables and their values are saved in RAM.


### Average Age Algorithm in JavaScript

Let's recall the average age algorithm we made and write some javascript code that does the calculation for us:
1. Get each person's age
2. Add the ages together to get a total
3. Divide the total by how many people

*Try writing this in JavaScript*

https://jsfiddle.net/jde6azso/

Write your code in the `JavaScript` section. Click `Run` to execute your code.

> NOTE: Save your answer in the variable `answer` for it to be displayed on your screen

<details>
<summary>JavaScript Answer</summary>

```javascript
theQueensAge = 94
alliesAge = 19
natesAge = 22
elonMusksAge = 49

total = theQueensAge + alliesAge + natesAge + elonMusksAge
average = total / 4
```
</details>

## HISTORY: Early Computer Programming
 In the early days of computer science, programmers wrote in `assembly`. This is the language that directly translates into the 1s (ones) and 0s (zeros) that computers understand. Nowadays, programmers use programming languages as they are easier to understand and write. However, at some point, all code (including what you are about to write) is translated or interpretted into `assembly` so your computer can read it and execute it. `x86` and `ARM` are some assembly languages you may have heard of.


