Marouen Helali

September 9th 2018

code developed on: Mac

approach:

I made a layout of the graphical user interface in HTML and decorated it with 
some css to make it more visually acceptable. Then I decided to add
functionality through JavaScript and jQuery. 
I created two arrays. One to hold the candidates names and another to hold the
number of votes the candidate gets. I used the indexes of the arrays to 
know which votes belong to which candidates. 
I made a table to hold the candidates and I would add a table row (tr - td)
every time the add button is clicked.
I gave every table row a unique id so I can loop through them later when I 
am trying to pick out which one I clicked on and decide which candidate to
"vote" for (which candidate td got clicked). 
I made the deletion of a candidate not delete them from the arrays, but I 
deleted them from the view and ignored/set back to 0 their values so I can
keep the votes up to date with the deletion of a candidate.
I used one color to denote how full the row of the candidate is, which 
indicates how many votes that candidate got in a user friendly manner.


additional comments:
In some places, I used: () => {}
instead of: function() {}
when doing a callback. it is just an abbreviation.

I didn't put semi-colon in the end of every line since I realized it 
compiles and works fine even without it.

 <strong>Screenshot:</strong>
 <br>
![Screenshot](./pic.png)