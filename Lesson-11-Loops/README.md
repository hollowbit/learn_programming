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
