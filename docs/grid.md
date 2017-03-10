# The Kaioken CSS Grid

The Kaioken CSS grid system is much like the Bootstrap one in the sense that it consists of
12 different columns. The grid system is made with flexbox however, after reaching the 450px
breakpoint it turns into a single column webpage as the columns become to small and look
pretty bad.

## Containers

Containers do what they sound like, they contain your content(pun intended XD).
Use the `container`
class for a 75% wide wide container and use the `container-full` class for a 100% wide container.

## The grid

As stated before, the grid consists of 12 columns. First you have to use the
`grid` class to create a container for your grid. Then use the `col-1`
for a single column sized column or `col-2` for a double........
My point is adding numbers to the `col`
class makes it bigger (make sure to keep it under 12).
Then there are the other things like grid-center, grid-middle
etc. These are self explanatory but just for the sake of documentation, here
are those:
* grid-between: put an equal amount of space between the columns
* grid-around: put an equal amount of space around the columns
* grid-top: put everything at the top
* grid-bottom: put everything at the bottom
* grid-middle: vertically center your columns
* grid-first: align stuff to the left
* grid-last: align stuff to the right
* grid-start: put your columns first
* grid-center: horizontally center your columns
* grid-end: align everything at the end
* grid-vertical: make the grid vertical
