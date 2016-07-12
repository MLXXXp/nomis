nomis
=====

This game was written by Craig N. Caroon. The source was copied from:
https://github.com/ccaroon/arduino/tree/master/arduboy/nomis

It has been modified to use the [Arduboy2](https://github.com/MLXXXp/Arduboy2)
 and [ArduboyTones]() libraries. This allows the RGB LED to be dimmed down so it
 isn't so blinding.

## Description
A simple memory game similar to Simon(tm).

## Instructions
The game starts at level one by showing one of the 6 buttons on the screen 
and playing an associated tone. Your job is to repeat the button press.

At each level a new button is added to the sequence. So by level 5 the Arduboy
will display a sequence of five buttons and play their associated tones and 
you'll have to repeat the sequence of 5.

There's currently no penalty for getting it wrong. You get as many tries as you
like.

You advance levels by successfully repeating the sequence that the Arduboy plays.

How far can you get??

## Download
[From GitHub](https://github.com/ccaroon/arduino/tree/master/arduboy/nomis)

## Development
Nomis was developed with [Platformio](http://platformio.org)

-----

## Work In Progress

### Iteration 0 -- Done!
There's nothing to play. It just runs thru a demo of the various pieces.

### Iteration 1 <--- We Are Here (Jun 16, 2016)
* The game is playable. Might be some bugs. Pretty bare bones.

### Iteration N (Coming Soon)
* Instructions
* Better graphics
    - Game Logo
    - Success/Fail screens
    - Dev Logo
* Menu for...
    - Settings
        - Sound Only
        - Visual Only
        - Both
    - Modes
        - Additive (default)
        - Random
* Scores?
* Pause between levels for user input
    - Continue or Quit
