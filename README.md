# 460_project
holds an instance of the database for the 460 project

# How to go from base_csv to modded csv:
1. download a copy of the base_csv
2. open up pgadmin 4 and create a database and shit
3. The default delimiter for when you're importing stuff is a comma-- just ask me(Daniel) if you want a detailed explanation for this step but basically you're going to find and replace all commas with nothing
4. make a base table with all the columns you want
6. right click on the table in pg admin and select import/export data
7. choose import, choose the right file, and go to columns and select the columns you want in the order of the relation
8. don't select any not-null columns because some of the rows have nothing in certain columns for some reason idk why
9. fuck i may have to redo the csv i just made i didn't do like two of these steps
10. uhhhhh i'll finish this by sunday probably.
