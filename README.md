## Data Visualization using dimple.js

### Summary
The objective of this project is to create an explanatory data visualization from a baseball dataset. The baseball dataset contains data of 1,157 baseball players including their handedness (right or left handed), height (in inches), weight (in pounds), batting average, and home runs. The visualization shows differences among the performance of the baseball players based on their handedness and height.

The dataset is available at : https://www.google.com/url?q=https://s3.amazonaws.com/udacity-hosted-downloads/ud507/baseball_data.csv&sa=D&ust=1480456909435000&usg=AFQjCNFXpi0HryO5CdPbjRUlekc074P8Mg


### Design
In this project, I provide a visualization that shows the comparison of batsman's performance based on their handedness and height. 

  Design1:
I chose a line chart to plot the batsman's batting average vs height. 

Design2:
Based on the first few feedbacks I received, I modified the code to include both the performance metrics - Batting average and home runs in the plot. The user now has the option to choose the performance metric between 'Batting Average' and 'Home run Average' by clicking the buttons.

Design3:
Based on the feedback from Udacity reviewer, I have changed the design to make the plot more explanatory. I have 2 key findings from the data - how 'handedness' affects performance and how 'height' affects performance, that I would like my visualization to focus on. The user has the option to choose between the two parameters 'handedness' and 'height' by clicking the button.

For handedness, I have used a bar chart to plot between handedness and homerun average and a line chart to plot between handedness and batting average. I tried using other charts like two line charts, two bar charts etc. for this plot. But I think using a bar chart and a line chart here was visually more appealing and clearly highlighted that left handed batsmen have better batting/homerun averages.


For height, I used a line chart between height and batting average. I did not plot height and homerun average since there was no clear trend.

Feedback

Feedback 1
Add a title for the chart

Feedback2
Replace legends "L, R, B" by "Left Handed, Right Handed, Both Handed" (replaced in csv file) for more clarity on the legend

Feedback3
Currently the plot only shows batting average vs height. Try adding 'home runs' as well in the plot.

Feedback4 - from udacity reviewer
Visualization as a whole is more exploratory rather than explanatory

Observations and Findings
Based on the exploratory analysis I did on the data, here are my findings:
1. Left handed players have higher batting average/homerun average combination  than  right/both handed players.
2. Shorter players have higher batting averages than taller players
3. There is no specific trend between homerun averages and players height

I made changes to my original plot as per the feedback I received.

Resources:
http://dimplejs.org/
https://github.com/PMSI-AlignAlytics/dimple/wiki/dimple.chart
http://dimplejs.org/examples_index.html
