[Previous: Lists/Arrays](../Lesson-10-Lists-Arrays/README.md)

# Loops

If you want to rerun certain code multiple times, or for each item in a list, you can use a loop.

```javascript
enemies.forEach(function(enemy) {
    enemy.x += Math.randomInt(3) - 1
    enemy.y += Math.randomInt(3) - 1
})
```

If you want to spawn 5 enemies:

```javascript
enemiesSpawned = 0
while(enemiesSpawned < 5) {
    enemies.push({ x: Math.randomInt(200), y: Math.randomInt(200)})
    enemiesSpawned++
}
```
