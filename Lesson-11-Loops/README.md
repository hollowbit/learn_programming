[Previous: Lists/Arrays](../Lesson-10-Lists-Arrays/README.md)

# Loops

If you want to rerun certain code multiple times, or for each item in a list, you can use a loop.

```javascript
enemies.forEach(function(enemy) {
    enemy.x += Math.random() * 4 - 2
    enemy.y += Math.random() * 4 - 2
})
```

If you want to spawn 5 enemies:

```javascript
enemiesSpawned = 0
while(enemiesSpawned < 5) {
    enemies.push({ x: 10 * enemiesSpawned, y: 3 * enemiesSpawned})
    enemiesSpawned++
}
```

## Using Loops and Lists in Algorithms

Lists and loops make it possible to to write algorithms that take any amount of data and produce a result. For example, our average age algorithm could only calculate the average age using a few people. Adding more people to it would require code changes. If we made a function to get the average age that took in a list of ages to calculate with, our algorithm would be able to get an average age whether we have 5 people or 1000 people. Here is what it could look like:

```javascript
function calculateAverageAge(ages) {
    total = 0
    ages.forEach(function(age) {
        total += age
    })
    return total / ages.length // ages.length is how many items are in the list
}

// Let's use our algorithm
calculateAverageAge([5,98,24]) // 42.33
calculateAverageAge([43,645,5,24,65,35,8,12,22,56,23,54,6,2,39,84,93,15,18,53,74,73,84,65,23,64,46,66,32,98,28,39,24,46,76,43,31,81]) // 60.39
```

## Lists in Our Game

*Try adding some AI to the enemies. You can access them with the `enemies` list:* https://jsfiddle.net/c5L0hsk9/4/

<details>
    <summary>Example Answer</summary>
    
    ```javascript
        enemies.forEach(function(enemy) {
            movementX = 0
            movementY = 0

            if (enemy.x < x) {
                movementX = 2
            }

            if (enemy.x > x) {
                movementX = -2
            }

            if (enemy.y < y) {
                movementY = 2
            }

            if (enemy.y > y) {
                movementY = -2
            }
            
            enemy.x += movementX
            enemy.y += movementY
        })
    ```
</details>
