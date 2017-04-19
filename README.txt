Assignment 2

The link to the webpage is : https://aripalli.github.io

The repository contains:
Visualization1data.ipynb: Contains the code that creates the dataset used for Assignment 2A (One scatter plot and two datasets).

Vis1.csv: Data file containing data for the first visualization generated with Visualization1data.ipynb.

K-meansdata.ipynb: Contains the code that creates the dataset used for Assignment 2B (Visualizing geodata).

kmeansdata.json: Data file containing data for the second visualization generated with K-meansdata.ipynb.

README: This file

d3: Files that make the visualizations possible.

sfpddistricts.geojson: Data file that contains information and coordinates for the San Fransisco districts.

index.html: The main file that contains all the code that makes the visualizations and generates the webpage.

main.css: Information about text style.


Question answers (Also present on the webpage):

Assignment 2A: One scatter plot and two datasets

Explain in your own words why you think I want the axes to be the same for both years? 
(Even though you know how to make axes adapt to the data values.)

If the axes change durng the transisition it can be really hard to compare the changes.
The main idea with the plot is to show how the crime has changed over the years.
If the axes changes then you would have to look at the numbers on the axis to understand this point, instead of just looking at how the points move.


Assignment 2B: Visualizing geodata

Think carefully about how you can minimize the size of the file containing the data. 
My file is around 700KB. Why is the size of the file important?

The file is loaded by the webpage. It is therefore important that it is not too large.
Large files take longer time to load and would make the webpage laggy and slow. Our data file is 872 KB which is close to the 700KB Sune has.
Even with a data file this small, it can still make the page lag. The data affects the scatter plot transisition, which is a bit laggy.
Removing the K-means data from the webpage will make the transisition smooth.