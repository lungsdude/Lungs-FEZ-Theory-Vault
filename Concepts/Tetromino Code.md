Tetromino Code is a writing system scattered around the world, used to communicate a set of instructions to perform in order to reveal a secret connected to it. It's made of [[Tetromino]] pieces joined together. Each tetromino (with an exception of L and reverse L pieces which never appear in the code) represents a game input the player can perform. If the player performs a set of inputs presented by the tetromino script in order in a close proximity, a secret is revealed.
![[Lighthouse Pier Tetromino.png|352]] ![[Waterfall Monolith Code.png|300]]
Tetromino codes are usually written on [[Monolith|monoliths]] and walls, but they can also appear as white symbols on a ground, which are present near a [[First-Person View Pole]]. They are also known to be hidden in the environment, like in the [Code Loop Room](Code%20Loop%20Room.md) or the [[Telescope]] puzzle.

## Structure

Tetromino code is a string of vertically arranged tetromino shapes, usually connected either orthogonally or diagonally with no gap between them, although an exception can be spotted in both [[Zu Ruins Throne Room]] and [[Zu City Throne Room]]. 

They're arranged in a way so that they never leave a space of three vertical columns, which is a minimum required to store all of the symbols.

In order to transform a sequence of tetrominos, they have to be separated into individual tetrominos, then the entire sequence has to be rotated 90 degrees counter-clockwise. Then the entire sequence from left to right can be interpreted as a set of inputs to perform one after another.
![[Tetromino To Input Interpretation.png]]

## Deciphering

The player can understand Tetromino codes by visiting [[Nuzu School]] and [[Code Machine Room]]. Former explains how to separate a code into individual tetrominos. Latter explains how to interpret each tetromino as a game input.

## Invalid tetromino code
In [[Nuzu School]] there's a drawing of a [[monolith]] containing a tetromino code, but it doesn't seem to make any sense, as it contains the number of squares which is undivisible by 4, making it impossible to separate into individual tetrominos:
  ![[Invalid Tetromino Sequence.png]]

### Number of symbols in the code
Most of tetromino codes consist of 8 tetrominos. Most notable exceptions are the [[Zu City Throne Room]] puzzle (requiring in total 16 inputs), [[Waterfall Island]] [[monolith]] code (consisting of 9 tetrominos) and the [[Black Monolith]] puzzle solution (requiring 7 inputs, although no tetromino code representing them is known to exist in the game) .

### Tetromino Cipher Theory
Interestingly, tetromino symbols with a width of 2 squares can have varying horizontal position in a sequence. This doesn't affect how a sequence is read, and for that purrpose it's purely cosmetic, but it introduces a [[Tetromino Cipher Theory]].