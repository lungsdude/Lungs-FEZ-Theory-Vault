# Level name: `code_machine`
![[The Code Machine.png]]

A small hidden-in-roots themed puzzle room inside a tree near the [Visitor](Visitor%20Area.md) with a [[Monolith]] containing a [[Tetromino Code]] and The Code Machine - a special device capable of displaying game inputs currently being pressed by a player within the close proximity, in a form of a [[Tetromino]].

## The Code Machine

When the player is close to The Code Machine, it will display last pressed game input for about 2 seconds, and then fade out to its default state, unless another input is pressed. This is meant to teach the player on how to interpret the [[Tetromino Code]].

Interestingly, while shifting perspective, The Code Machine will not detect any game inputs, despite them being correctly detected when executing codes. This is presumably a bug.

![[The Code Machine - States.png]]

## Tetromino Code Monolith

The monolith contains a [[Tetromino Code]] which can be read as sequence of 8 game inputs:
#### `UP JUMP RT LT JUMP DOWN LT RT`

Executing this code anywhere in the level will reveal an [[Anti-Cube]] right above the monolith.