15-puzzle
=========

Web Developer Candidate JavaScript Test
=======================================

Please create a simple [15-puzzle](http://en.wikipedia.org/wiki/15_puzzle) 
game application.

Game applications must display the following elements:

-   Playing field with numbered tiles
-   Timer
-   Step counter
-   Basic UI controls (start/stop button and history button)

Game Specifications:

1.  At the beginning, the tiles in playing field must be placed in
    correct order.
2.  Once user presses Start button, the button must be renamed to
    Stop and tiles in playing field must reshuffled in random order.
3.  Timer must indicate duration of time passed from game start in
    minutes and seconds .
4.  Step counter must be increased by one when user moves any tile.
5.  Once user presses Stop button, the tiles in playing field must
    be reverted to ordered state, timer dropped to 00:00 and step
    counter to 0. Stop button must be renamed to Start to let user
    start again.
6.  Once user completed game (i.e. placed all tiles in correct
    order) application must stop timer and show History table with
    current result (time and step count) at the top of the table.
7.  The same table must appear when user presses History button.
    Contents of the table must be stored in local browser storage.

The game must be delivered as a single HTML document with embedded
CSS and JavaScript. Please, do not use images to decorate game.
