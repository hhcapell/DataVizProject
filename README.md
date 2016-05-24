# DataVizProject
Data Visualization Project P6 for Udacity.com  Data Analyst Nanodegree - Heather Capell

SUMMARY

Using the Baseball dataset, I wanted to find out how the Player attributes of Height, Weight and Handedness are related to Home Runs.   My initial guess that I wanted to test is that greater Height, Lower Weight, and Right Handedness each contributed to mmore Home Runs on average.  

To determine the actual relationship between Height, Weight or Handedness and Home Runs, I divided the Height and Weight data ranges into three assigned categories representing Low/Average/High Height or Weight, and calculated the Home Run average for all Players in each category.  I also calculated the Home Run average for each of the Handedness categories.


DESIGN

I chose to use a bar chart, since this is a very clear way to highlight any differences between categorical variables.  I displayed the categories for each attribute along the x-axis, and the Home Run average for all Players for each category along the measurement/y-axis.


FEEDBACK

(1) From Myles Callahan, coach (5/22/16):
One suggestion, which is down to personal preference, would be to fix the y-axis (so that, when you switch between visualization, the scale is comparable), i.e.
            y.domain([0, 60]);
for all charts.

(2) From Meidy Rotinsulu, colleague (5/23/16):
Is there a way to compare the graphs together or combine two of the graphs so that you can more easily compare them in one view?  Or, can you add caption or text to summarize what you are seeing so that it is easier to remember what is on each chart?


(3) From Suzanne Barbas, colleague (5/23/16):
The bars would look better if they were a little more narrow.  The fonts especially on the axis labels would be better if bigger and easier to read.   


RESOURCES

"Manipulating data like a boss with d3":  http://www.jeromecukier.net/blog/2012/05/28/manipulating-data-like-a-boss-with-d3/
