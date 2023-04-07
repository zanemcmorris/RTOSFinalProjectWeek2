# RTOSFinalProjectWeek2

Changes:

Imported working Lab 7
Deleted all Lab 7-specific data including structs, enum, and tasks

Added task definitions and created most of the tasks I foresee needing
Created graphicsFunctions .c and .h files which will store my graphics macros for drawing
Created the drawSlug() function that draws a small circle at a desried point and will be the basis for the railgun slugs moving foward.
Started on making a functional bouncing ball that bounces off the "floor" and off of the walls with a constant magnitude x-velocity

Found and issue where ball was losing energy over time even though collisions were implemented to be elastic.
I think this is caused by floating point rounding or some similar quirk. It occured even before I added code to reset position if it exceeded bounds of screen.

