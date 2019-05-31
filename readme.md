# MSCS Project

This repository overviews an Artificial Intelligence design project which I completed while completing my Master's in Computer Science at Georgia Tech. The source code for this project is not publically available, in compliance with the Georgia Institute of Technology Academic Honor Code<sup>[\[1\]](https://policylibrary.gatech.edu/student-affairs/academic-honor-code)</sup>.

Instead, I have substituted my raw code with a guided walkthrough of the project itself, the steps I went through to complete it, and the skills I acquired by solving it.

# AI Isolation

Isolation<sup>[\[2\]](https://en.wikipedia.org/wiki/Isolation_(board_game))</sup> is a two player board game in which players attempt to "isolate" their opponent's piece, which makes it an excellent AI challenge to tackle!

A simple version of the game might look like this:

<p align="center"><img width="182" height="182" src=images/isolation-basic.png></img></p>
<div align="center"><b>Fig 1. Basic Isolation Board</b></div>

* Players each place their tile on a 7x7 grid.
* Take turns moving their tile any number of spaces, in a straight horizontal or diagonal line, but not into a space occupied by another player.
* Spaces which previously contained a player **are no longer accessible.**
* A player wins the game when their opponent can no longer move.


Because the game can be modified easily, numerous AI challenges can be generated. 

For example, here is a game of Isolation played using the "Knight" piece from chess, meaning it can only move in an "L" pattern:

<p align="center"><img width="182" height="182" src=images/isolation-demo.png></img></p>
<div align="center"><b>Fig 2. Isolation with Knights</b><sup>[\[3\]](http://the-charlie.com/ml/index.php/project/winning-at-isolation/)</sup></div>
