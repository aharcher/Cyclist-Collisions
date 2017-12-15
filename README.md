### December 14, 2017
### Andrea Archer
### SIG-6170 Metrics and Data Visualization I
### Final Project

# The Road to Safe Cycling in NYC

## DESCRIPTION
Thanks to major initiatives like Vision Zero and Citi Bike, the number of bike lines in New York City has more than doubled in the past decade. But even today, nine in ten cyclists killed are killed while riding outside of bike lanes. There's still plenty of work to do.

My interactive maps the location of all NYC motor vehicle collisions since July 2012 that resulted in at least one cyclist injury (red dots) or cyclist fatality (white dots). Each point, when clicked, contains additional information about the specific date, time, and reason for collision.

The purpose of this project is not to encourage all current and potential cyclists to opt for the subway, but to remind the entire cycling community that we must continue to advocate for safer roads at the grassroots level, while remembering the individuals to whom we owe our increasingly safer city.

## DEMO LINK

[The Road to Safe Cycling in NYC](https://aharcher.github.io/Cyclist-Collisions/)

## PROJECT PROCEDURE
_Describe your data processing, visualization selection, and analyses post-visualization_

For my final project, I initially set out to learn more about the patterns and circumstances present around traffic accidents in NYC involving cyclists (as an NYC bike commuter, this is a topic I think about a lot). I started with a dataset from NYC OpenData that has variables for all motor vehicle collisions in NYC since July 2012, including an interesting column describing factors that contributed to the collisions. Since it was an enormous dataset, Sandy helped me parse through the data and create new tables that only included those collisions involving a cyclist who was injured or killed.

[image excel]

From the outset, I had hoped to visualize the data on a map of NYC—after all, bikes are a form of transportation and grant us geographic freedom within this City. I used Carto for this. I had also hoped to specifically vizualize the factors contributing to the collisions, expecting that there would be some actionable take away like "all left turns are super confusing and dangerous!" Unfortunately, there wasn't a lot to work with here. The vast majority of collisions had "unspecified" factors or factors that were entirely uncontrollable, like "Other vehicle." So, I opted to keep the vizualization more flexible and discoverable. Lastly, I decided to manually link up information from the Street Memorial Project (based on collision location and date) for all the cyclists killed since 2012 (or as many as possible). Including names and photos (some of which I took, some from the MSP) of the deceased crash victims helps the map retain a human element—important since it's easy to forget that the thousands of dots on the map represent actual human lives.

[image carto]

In the end, constraints in the data itself and in my technical abilities limited the quality of insights a little. But I have a few takeaways:
- 
