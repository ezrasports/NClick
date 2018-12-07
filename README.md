# NClick
UiPath Library to click on an element a variable number of times

Library made in 2018.3.2

Takes the selector, click type, and number of clicks as arguments. 
The Maximum number of clicks is defined as 10, but could be edited in the source.
For click type:
"L" or "left" results in left-click.
"R" or "right" results in right-click.
"M" or "middle" results in middle-click.
This parameter is NOT case sensitive ("Right" and "RIGHT" will both work).

The activity returns a boolean that will be True if it succeeds and False if it hits any errors. It would also log the error it encountered at a Warning level.
