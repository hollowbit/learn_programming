[Previous: Objects](../Lesson-05-Objects/README.md)

# Funtions: Reusing Algorithms

The point of algorithms is to calculate different results when different values are given. In our average age example, we saw that by giving different ages at the start, the resulting average was different. Functions can be used to save algorithms by name to use them later. They have inputs and outputs.

```javascript
function isYoung(age) { // age is the input
    return age < 40 // use "return" to send back the result of the algorithm
}
```

Now, you can use the function:

```javascript
young1 = isYoung(19) // passes "19" as the "age" input. true
young2 = isYoung(53) // passes "53" as the "age" input. false
```

## Objects with Functions

```javascript
person.isYoung = function() { // no inputs needed for this, because it uses the object's values
            return this.age < 40
        }

isPersonYoung = person.isYoung()
```

## JavaScript Provided Functions and Objects

JavaScript provides many functions and objects for you to use. For example, JavaScript provides the `console` object. It has a function called `log` that takes in a string. If you call it, it will put a message in the JavsScript console. Example:

```javascript
console.log("Hello, world!")
```

There are also included functions on Strings:
```javascript
word = "concatenate"
word.contains("cat") // true
newWord = word.replace("nate", "john") // "concatejohn"
```

[Next: Conditions](../Lesson-07-Conditions/README.md)