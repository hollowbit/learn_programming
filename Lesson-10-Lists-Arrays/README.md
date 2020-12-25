[Previous: Bugs](../Lesson-09-Bugs/README.md)

# Lists / Arrays

Often you will want to have multiple values or objects in an organized list.

```javascript
enemies = []

// add enemies with the "push" function
enemies.push({ x: 40, y: 33})
enemies.push({ x: 105, y: 16})
```

You can now access each enemy by `index` number, which is their position in the list (starting with 0):

```javascript
console.log(enemies[0].x) // 40
```

You can also preload lists like this:

```javascript
enemies = [{ x: 40, y: 33}, { x: 105, y: 16}]
console.log(enemies[0].x) // 40
```

*Try adding some enemy objects to the `enemies` list in the game. They need an `x` and `y` value:* https://jsfiddle.net/c5L0hsk9/4/


<details>
    <summary>Answer</summary>
    
    ```javascript
        enemies.push({ x: 40, y: 70})
    ```
</details>


[Next: Loops](../Lesson-11-Loops/README.md)