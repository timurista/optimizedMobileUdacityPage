## Website Performance Optimization portfolio project

1. To run the application, load into remote server or fork and download

# List of Optimization Changes
# In Views
1. reduced pizzeria size and meta information
2. modified sizing in js file for pizza.html so image width is changed as the pizza size is changed (not offset detials)
3. modified updatePosition to do heavy-mathematical lifting and lookup in a seperate location
4. In both files cached query searches into a variables for easier referencing and lookup.

# In Main, index.html
1. minifyed css and js
2. moved media query into seperate file
3. applied async to js and put it at the end so it didn't block crp.
4. changed type to "print" for print.css and minifyed it
5. removed unnecessary fonts, since browser was falling back on sans-serif
6. reduced portfolio picture size and meta information