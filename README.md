## Gopher-Hunt
A game of gopher hunting as an Android app

# Turn Based Mode
<img src=http://g.recordit.co/zhPjMrVlde.gif width=200><br>

# Continuous Mode
<img src=http://g.recordit.co/uInEX9eMSA.gif width=200><br>

## Project Description
Imagine you are in a field occupied by a gopher. The gopher could be hiding in one of any number of holes in the field’s ground. The goal of the game is to find the hole that contains the gopher. (The game does not say what to do with the gopher, once it
is found.)
The game is played by two worker threads contained in your app, with the threads playing against each
other. There are exactly 100 holes in the field; the holes are arranged as a 10×10 matrix and equally spaced
with respect to each other. The threads take turns at guessing the hole containing the gopher; the first thread
to find gopher wins the game.
The app supports both a guess-by-guess game play as well as a continuous mode whereby the two threads
play without interruption until one thread wins the game. Either way, the app contains a display showing all
the guesses that the two threads have made so far. 
