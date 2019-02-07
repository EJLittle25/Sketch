# This is my Blog Post
------

Variables
-- Move
    -- Shift (Instructs shapes how far vertically to move
    based on their Xposition. Should be further for things closer
    to the edges of the canvas.)

Class
--Basis
    -- Composed of color, size, xPos, yPos (possibly speed)

Set up
-- Canvas
-- Background(black)
-- Ensure that Javascript code reflects a black backdrop as well

Shift
-- Uses a for loop. Should be from 0 to half the width of the canvas.
    -- Steps through for loop to draw a circle
        -- Starts each circle at a tiered position.
        -- For each iteration, the circle's position should be moved up incrementally.
        -- For each iteration, the circle should travel a shorter distance to the top.
        -- For each iteration, the circles color should should be shifted closer towards white.


-- Uses a second, but not nested, for loop. Should be from half the width of the canvas to the end of the canvas.
    -- Steps through for loop to draw a circle
        -- Starts each circle at a tiered position.
        -- For each iteration, the circle's position should be moved down incrementally.
        -- For each iteration, the circle should travel a longer distance to the top.
        -- For each iteration, the circles color should should be shifted closer towards black.


Concept:

This should create an image that looks like two equilaterial triangle touching tips. It should be a gradient and appear as if the colors are rippling. 

![Sketch](Sketch.jpg?raw=true "Sketch")