# DataVizProject
Data Visualization Project P6 for Udacity.com  Data Analyst Nanodegree - Heather Capell


SUMMARY

Using the Baseball dataset, I wanted to demonstrate how the Baseball Player attributes of Height, Weight and Handedness impact Player Home Run Averages. I grouped Players into three nins per attribute, based on whether a Player is Lighter/Medium Weight/Heavier (for Weight attribute) or Shorter/Medium Height/Taller (for Height attribute) relative to other Players within the Baseball dataset, and into Left/Right/Both buckets for the Handedness attribute, and then calculated the Home Run Average to display for each bin.


DESIGN

I chose to use a bar chart, since this is a very clear way to highlight any differences between categorical variables.  I displayed the bins for each attribute along the x-axis, and the Home Run Average for all Players for each bin along the measurement/y-axis.  For the bin with the greatest Home Run Average, I displayed the bar in a prominent color (green) to make it stand out from the other bars which are a more subdued color (steelblue).


FEEDBACK

(1) From Myles Callahan, coach (5/22/16):
One suggestion, which is down to personal preference, would be to fix the y-axis (so that, when you switch between visualization, the scale is comparable), i.e.
            y.domain([0, 60]);
for all charts.

(2) From Meidy Rotinsulu, colleague (5/23/16):
Is there a way to compare the graphs together or combine two of the graphs so that you can more easily compare them in one view?  Or, can you add captions or text or color to summarize what you are seeing so that it is easier to see what is on each chart?

(3) From Suzanne Barbas, colleague (5/23/16):
The bars would look better if they were a little more narrow.  The fonts especially on the axis labels would be better if bigger and easier to read.   

(4) From Trent Shemwell, colleague (5/26/16):
Lefties have more home runs because the Left outfield wall is shorter; include that factor in the explanation section.

(5) From Jane Pullaro, colleague (5/26/16):  
Pitchers have less experience pitching to Shorter and Taller Players, and therefore have a tendency to not pitch within the strike zone for Shorter or Taller Players, resulting in more walks for them; include that factor in the explanation section.

RESOURCES

"Manipulating data like a boss with d3":  http://www.jeromecukier.net/blog/2012/05/28/manipulating-data-like-a-boss-with-d3/

"Towards Resuable Charts":  https://bost.ocks.org/mike/chart/

"Functions":  https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Functions

