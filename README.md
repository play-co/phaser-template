Devkit Phaser Template
======================

The purpose for this template is to provide a mechanism by which Phaser games
can integrate themselves with Devkit with relative ease. By instructing a Phaser
game to talk to a Devkit canvas, one can make use of the canvas backend that
Devkit uses for its native mobile builds on Android and iOS.

Instructions
------------

To integrate an existing Phaser game with Devkit through the use of this template,
you may follow these helpful instructions!

1. Clone this repository!

    git clone https://github.com/weebygames/phaser-template

2. Place your game code into the src/game.js file. Note that the intialization of
   Phaser.Game is done inside the `exports = function(width, height, canvas) { ... }`.
   As of right now, this is necessary. It is also necessary to call `game.setCanvas(canvas)`.
   Note further that the width and height passed into this function are the width
   and height are that of the device.

Additional Notes
----------------

The phaser.js in this repo comes from [here](https://github.com/weebygames/phaser).
