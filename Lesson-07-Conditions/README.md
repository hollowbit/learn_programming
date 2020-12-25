[Previous: Functions](../Lesson-06-Functions/README.md)

# Conditions

Sometimes you want certain code to only run under certain conditions. In JavaScript, you can do this with `if` and `else`:

```javscript
height = 6.2
shirtSize = ""

if (height > 6) {
    shirtSize = "L"
}

if (height > 5) {
    shirtSize = "M"
} else {
    shirtSize = "S"
}

console.log("Shirt Size: " + shirtSize)
```

You can also chain multiple conditions:

```javascript
age = 19
ageGroup = ""

if (age > 55) {
    ageGroup = "elderly"
} else if (age <= 17) {
    ageGroup = "child"
} else {
    ageGroup = "adult"
}

console.log("You are " + ageGroup)
```

[Next: Games](../Lesson-08-Games/README.md)