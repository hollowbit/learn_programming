[Previous: Conditions](../Lesson-07-Conditions/README.md)

# Games

All games have a game loop, which is code that is executed many times per second. It handles game logic and changes how the game is played.

Write code in the `update` function to control how the game runs. Here are variables you can work with:

|name|What it does|
|---|---|
|x|Where the player is located on the x-axis. Set it to change the player position|
|y|Where the player is located on the y-axis. Set it to change the player position|
|keyboard|Object containing 4 boolean values: up, left, down, right. They are set to true if those respective arrow keys are pressed|

*Using those variables, control the player using the arrow keys:* https://jsfiddle.net/c5L0hsk9/2/

## X and Y on Game Screen

The X and Y position of the player starts from the top-left of the box. Both axes go from 0 to 200. It looks like the following:

```
(x, y)
(0, 0)------------------------> (200x,0y)
    |                          |
    |             (150x, 70y)  |
    |                  X       |
    |                          |
    |                          |
    |                          |
    |                          |
    |                          |
    |                          |
    |                          |
    v--------------------------+
(0x, 200y)
```

[Next: Bugs](../Lesson-09-Bugs/README.md)