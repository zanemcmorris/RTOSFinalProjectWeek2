# RTOSFinalProjectWeek2

CHANGES:

Imported working Lab 7
Deleted all Lab 7-specific data including structs, enum, and tasks

Added task definitions and created most of the tasks I foresee needing
Created graphicsFunctions .c and .h files which will store my graphics macros for drawing
Created the drawSlug() function that draws a small circle at a desried point and will be the basis for the railgun slugs moving foward.
Started on making a functional bouncing ball that bounces off the "floor" and off of the walls with a constant magnitude x-velocity

Found and issue where ball was losing energy over time even though collisions were implemented to be elastic.
I think this is caused by floating point rounding or some similar quirk. It occured even before I added code to reset position if it exceeded bounds of screen.

PROJECT COMPLETION: 7.5 hrs / 36.75 = 20.4% finished.

ANALYSIS OF TIME ESTIMATES VS LOGS
Environment Variables: Estimated time - 2 hrs | Real time - 3 hrs | 1.5x time estimate
Slug based on pos: Estimated time - .5 hrs | Real time - 2 hrs | 4.0x time estimate
Starting on physics: Estimated time - 2 hrs | Real time - 2 hrs | 1.0x time estimate
Weekly upkeep: estimated time - 3.5hrs / 5 weeks = .70 hrs/week | Real time - .25 hrs | 0.35x time estimate
            

STATUS: I am a little nervous about moving forward from here because I have been thinking a lot about the stuff that I have implemented and I need to change my focus to what is ahead of me. I feel my time estimates are certainly lower than the real time by roughly a factor of 2-3x. This week I spent a lot more time than expected dealing with a simple issue with GLIB not drawing what I wanted it to and the physics clock period being much longer than I expected. The general kinematics were faster to implement than I expected and currently one of the most daunting tasks feels like the capsense specifics and platform velocity. As I continue to work however I hope that it starts to come together faster than I currently expect, but I will be putting in significantly more time next week. 

