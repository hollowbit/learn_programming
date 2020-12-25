[Previous: Primitive Data Types](../Lesson-04-Primitive-Data-Types/README.md)

# Objects

Objects are custom data types that programmers create to organize and group related data. They are made up of primitives.

```javascript
person = {}
person.name = "Bob"
person.age = 39
person.isNice = true
greeting = "Hi, " + person.name +". You are " + person.age + " and nice? " + person.isNice // "Hi, Bob. You are 39 and nice? true"
```

You can also create objects like this in JavaScript:

```javascript
person = {name: "Bob", age: 39, isNice: true}
greeting = "Hi, " + person.name +". You are " + person.age + " and nice? " + person.isNice // "Hi, Bob. You are 39 and nice? true"
```


[Next: Functions](../Lesson-06-Functions/README.md)