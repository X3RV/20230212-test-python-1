# Test-20230212-1
Test repo illustrating some interesting test programs and/or concepts.  Primarily Python Colaboratory.

Started: 2023/02/12

Update:  2023/02/18 
Under development.  Added clarification to the top level comment and breif initial documantation for 20230218 13-1.ipyynb - X

Last Update:  2023/02/22 
Added the file example gist.
The basics of 20230218 13-1.ipyynb are complete.  Though it's super rough still.  


***********************
Relating to files inside python:

Although it's not a specific program here is a useful gist:

# Including the encoding turns out to be rather important
# infile = open(filename, 'r', encoding = 'utf-8-sig')

Many coding examples ommit the encoding which has caused me a few pains.  
The encoding used ubove is the most common one I've seen and is the one used by Excel CVS files.
Though you can universally change it, it seems prudent to simply include the proper encoding.

***********************
# 20230218 13-1.ipyynb 
This will be a program that is a match game featuring a grid 8 x 8 using the letters Q, R, S, T, U.  
They will be randomly placed in the grid.  The user can swap letters that are next to one another.  
A minimum match of 3 causes the letters to match, award points, move the existing letters down, and 
replace the empty slots with new random letters.
This continues until a score goal is reached.

* This is illistrating several differant concepts that are important (as well as being a nice begining program of slightly higher than average begining complexity)
- use of the import function (in the syntax of from)
- use of functions (and the definition program)
- example of top-down design (with loop cycle main area)
- calling functions

*************************


