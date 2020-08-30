# SuperPuzzleSliderTurbo
This is a web-based version of a classic sliding puzzle game

First public commit of my MSSA project, .

The concept is a variation on the old 15-puzzle sliding piece game, where a square image is split into pieces and rearranged.  One piece is removed and then the player has to slide the pieces, one at a time, until they all find their original place on the board.


## <div align="center">Table of Contents</div>
#### <div align="center">(Some contents forthcoming)</div>

1) [Why I chose this](#why)
2) [Concept](#idea)
3) [Wire-Frame Desktop (forthcoming)]
4) [Wire-Frame Mobile (forthcoming)]
5) [Entity Relationship Diagram (ERD) (forthcoming)]
6) [User Stories/Req/UML (forthcoming)]
7) [Testing (forthcoming)]
8) [Prototype](#prototype)

## <div align="center">WHY</div>
[(Table of contents)](#table-of-contents)

I used to play a lot of board games with my siblings when we were younger.  Sometimes, though, I wanted to play my own game.  Before I got a game boy, that meant something like a Puzzle 15 would have to suffice.  I have fond memories of playing them, and I thought it would be a lot of fun to build the game using C# for a web application.

## <div align="center">IDEA</div>
[(Table of contents)](#table-of-contents)

The idea of a Puzzle 15 is that a square image is split into a 4 X 4 grid of sixteen squares.  One of the squares is missing, so you have fifteen puzzle pieces, hence Puzzle 15.  You have to slide the pieces one at a time into the one empty grid space, back and forth and around the board, until you have shuffled them all into the correct spaces.  You will know they're the correct spaces because they will form a complete image.  For my web application, I will give players the opportunity to show or hide the image in the upper left corner to give them a guide for solving.  I also wanted to provide a chance to decrease or increase difficulty from a 2 X 2 to 3 X 3 to 4 X 4 grid.  Then alternately, they could toggle between color, black and white, or line drawing versions of the image which would also affect difficulty to a degree.  If they are having too much trouble, they can bail out and let the computer solve the puzzle by hitting the "Give Up" button.  Oh, and they can change the image as well if they don't like the one the system chose for them by cycling through the images in the top right.

## <div align="center">PROTOTYPE</div>
[(Table of contents)](#prototype)
![PROTOTYPE](https://github.com/jayhawk84/SuperPuzzleSliderTurbo/blob/master/PuzzleMedia/Prototype.PNG)
#### <div align="center"><a href="https://ojbh74.axshare.com/#id=ithaj4&p=page_1" targe="_blank">Interactive Axure Prototype (link)</a></div>
