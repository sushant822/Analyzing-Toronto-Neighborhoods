# Analyzing-Toronto-Neighborhoods
### by Sushant Deshpande

In this project, we’ll analyze Toronto’s most multicultural neighbourhoods, East Toronto and West Toronto. By doing so, we’ll see
what types of venues are popular in each neighbourhoods. This will help a group of investors understand what type of restaurant
they would like to invest in. In order to achieve this, We’ll perform the following:

 - Get the postal codes from Wikipedia using web scraping method in python.
 - Clean up the data and merge it with the geopositional data provided to us by Coursera.
 - Use FourSquare to get the venues in our desired neighbourhood.
 - Use python to find to 10 most popular venues and display it graphically.


## STEP 1 - Importing the data

We begin with grabbing the postal codes from Wikipedia’s webpage using python’s web scraping method.
Downloaded data looks like this:

`	Postal Code	Community	Neighbourhood
0	M1A	Not assigned	Not assigned
1	M2A	Not assigned	Not assigned
2	M3A	North York	Parkwoods
3	M4A	North York	Victoria Village
4	M5A	Downtown Toronto	Regent Park, Harbourfront
`