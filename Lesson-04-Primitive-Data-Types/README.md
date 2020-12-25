[Previous: Code](../Lesson-03-Code/README.md)

# Primitive Data Types

Primitives are the basic data types that are included in a programming language. So far we saw numbers, but JavaScript also has strings (text) and boolean (binary true / false).

## Strings

Strings are text. They are created using double-quotes `"`, as such:

```javascript
name = "Bob"
```

Strings can be added together.

```javascript
name = "Christine"
greeting = "Hello, " + name + "!" // creates a new string: "Hello, Christine!"
```

## Booleans

Booleans are variables that hold only 2 possible values, `true` or `false`.

```javascript
isCool = true
isTall = false
```

Booleans have special arithmatic. These create new boolean values.

```javascript
!true // false
true && true // true
true && false // false
true || true // true
true || false // true
false || false // false
```

## Comparing Values To Create Booleans

You can compare number and string values to create booleans. Example:

```javascript
age = 26
name = "Bob"
isOld = age > 64 // false
age == 26 // true
nameIsCool = name == "Wolfgang" // false
```

Other comparison operators:

|Operator|What it does|
|---|---|
|`<`|Less than|
|`>=`|Greater than, or equal to|
|`<=`|Less than, or equal to|

[Next: Objects](../Lesson-05-Objects/README.md)