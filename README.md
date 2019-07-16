# SW-Data-Analysis
Using web APIs for surface water and weather station data analysis.

My employer recently purchased a very expensive database platform to manage our water quality data. Very few people have access, 
and even fewer understand the user interface well enough to leverage the huge diversity of data stored there. I wanted to leverage
my skills in python and data science to make this data a bit more accessible to decision makers and the community. In this notebook,
I use pandas and matplotlib to generate a simple graphic depicting fecal coliform sample results alongside historic rainfall over a
period of 3 years. It's a commonly requested graphic by partners in our 4 different shellfish community interest groups, but it 
typically takes a good 30 minutes to update, sync, and chart the data manually in Excel. Multiply that by 4 graphics, and you've wasted
your morning.

The really great thing about our new database platform is the REST web API that allows anyone to query the data via some simple html.
By setting up a few parameters as variables in the notebook, I can use this web API to automatically generate updated graphics in seconds.
More importantly though, this means that we now have a way of making better use of our investment by making data more accessible and 
comprehensible to our customers.
