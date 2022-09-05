# Feed-a-Mole

Feed-a-Mole is an in-browser computer game developed with JavaScript, HTML, and CSS. A variation of the popular arcade game Whack-a-Mole, it asks users
to feed hungry moles as they emerge from the ground for a short period of time. Players receive points for each mole they feed and win the game by
reaching a set number of points.

## Overview/Implementation

Feed-a-Mole uses modular JavaScript to implement in-game logic and user interaction/display functionality. It handles the state of the game's objects
(gameboard, status bar, etc.), responding dynamically to the player's actions; randomizes the timing/duration of each mole object's appearance;
and updates the DOM according to these changes.

The styling and layout of the game's elements are designed with HTML and CSS.

## How to Play

Feed-a-Mole is hosted on Github Pages and can be played live [here](https://jeremy-gleason.github.io/Feed-a-Mole).

The game will begin automatically, and hungry moles will appear periodically on the board. You should feed them (by clicking on them with your
bird cursor) before they return to their hole. For each mole you feed your score will increase by 1 point and if you reach 10 points you'll win the game.
(The worm-meter at the top of the screen provides a visual representation of your score.)

## Credits

Feed-a-Mole was developed as part of the [Frontend Masters](https://frontendmasters.com) Bootcamp, using artwork designed by Alice Brereton.
