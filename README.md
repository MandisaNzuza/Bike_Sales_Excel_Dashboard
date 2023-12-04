# Bike Sales Excel Dashboard

## Excel Projects Notes

1.	Create another worksheet to paste the data so we can have data we are working on and the one that is raw data.
2.	Work on the new worksheet “working sheet”.
3.	1st step – Clean the data – Remove all duplicates.
4.	The columns ‘Marital status’ and ‘Gender’ both have M, so to make this easy for the reader who doesn’t know what these stand for in our data, we can just replace the letters with actual words
5.	To do this we change column B, control H – brings out find and replace.
6.	Change the income table to currency by Numbers.
7.	We then check every column if there are no spelling errors, null values, etc.
8.	On the Age column we see that the ages are separate, they are not in a range form, and this could be tedious for us.
9.	We then have to condense these age values to make them easy to understand.
10.	We can create a new column ‘Age Brackets’
11.	We can use an IF statement to give it a range: =IF(L2>31; “Middle Age”; IF(L2<31; “Adolescent”; “Invalid”)
12.	Now we have cleaned our data, we go to pivot tables.
13.	Pivot tables help build our dashboards and our visualizations.
14.	Control A- highlight all your data.
15.	We can build different dashboards, the first one we want is a dashboard that looks at the average income of a person who either bought or did not buy a bike.
16.	We want to break it down by their gender.
17.	From the table we can see that Men make more money.
18.	We then do visualizations for the table we just created.
19.	All these need pivot tables to create visualizations.
20.	For the first table we’re looking at whether their income is a determinant of whether they bought a bike or didn’t buy one.  If they said yes, is it because they make more money?
21.	We create another table; this time we want to see the distance.
22.	Commute distance is a determining factor in whether customers buy bikes or not, the pivot table will help us determine who is buying. Are they living close or far away?
23.	Our table has 10+ miles following after 0 – 1 mile, meaning it is not in order. 
24.	This causes a dip in our graph; hence we need to go back to our working sheet to fix it.
25.	We changed it into +10 Miles, and it made sense.
26.	For the last table we are using the age brackets that we created, to see our target market.
27.	From our graph we see that not a lot of adolescents are buying bikes, however, middle-aged people from 31-54 are buying a ton of bikes.
28.	Now that we’ve done our pivot tables, we can create our dashboard.
29.	How do we make our dashboard nice?
30.	We can remove the gridlines, go to View, and remove them.
31.	Considering that there are other elements that people would love to see when looking at a dashboard, be able to filter by. But it is not on the visualizations we created.
32.	One field that could be very specific is to see which ones are buying bikes more, married people or single people.
33.	We’ll click on any of the tables, go to pivot chart analysis, insert a slice, and choose married or single. Since we selected only one pivot chart, the filter will only work on that table.
34.	To apply this filter to all of them we going to click on the filter, then slicer then report connections, we can then choose the pivot tables we want the filter to work on.
35.	We can then create more filters, Regions, and education.
36.	Nice Dashboard – You have key information to look at.
-	Nice visualizations
-	It’s colour-coordinated. 
-	Have slices on the side.
  
