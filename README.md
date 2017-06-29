# Make-Effective-Data-Visualization
Project - 07 , Udacity Data Analyst Nanodegree
### by RAHUL PATRA
29th June,2017

## Summary
In this project, I focus on visualization by using d3.js and dimple.js.

Here we present a visual analysis about some parameters that affects the performance of the baseball players. Data I used in this project is about the baseball players' performance which inclues 1157 players including their handedness (right or left handed), height (in inches), weight (in pounds), batting average, and home runs. So performance is measured as their batting average and the number of home runs; parameters are handedness, height and weight. Since height and weight are positively correlated (data not shown). Data is available [here](https://docs.google.com/document/d/1w7KhqotVi5eoKE3I_AZHbsxdr-NmcWsLTIiZrpxWx4w/pub?embedded=true)
I'm using Body Mass Index(BMI) to made my conclutions over Players' perfomance. And from the visualizations we get: 'High BMI players tend to have better batting performance.'


## Design
1157 players are so many that I selected only top 60 players in the first graph.
The second and third graph, I classified batters in terms of BMI(more than 24 or not) and Handedness.
I have choosen Bubble chart and Bar Chart for my visualizaton. Chart Junks are removed, Data-Ink ratio is reduced to make visualizations more improved. Legands are added to each visualisations which depicts players' performance. 

Modification made: (after Feedback)

1.I added some explanation of batting average for the uninitiated.

2.I modified typo and grammatical error. I arranged the layout of HTML.

3.I changed the order of ticks of bar charts so that they are consistent.

## Feedback

### Person 1:
For the uninitiated, could you explain what the batting average means and if higher or lower is better?

### Person 2:
There are some typos and grammar mistakes that should be fixed:
“Is it a gereral trend to have”
“ Overweight players tend to be better performance”
“players are better performance in batting”
Otherwise nice job!

### Person 3:
The graphs are easy to recognize.
The only one thing I find is that the ticks in the bar charts are not consistent.

## Resourse
1. [Udacity Data Visualization](https://classroom.udacity.com/courses/ud507-nd)
2. http://dimplejs.org/advanced_examples_viewer.html?id=advanced_interactive_legends
3. http://dimplejs.org/
