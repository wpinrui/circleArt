# RoundArt
RoundArt is a static website in which users can use 3 sliders to create Mathematical art in a circle. It can be found [here](https://roundart.netlify.app).

## The drawing process
The algorithm for creating the 2D image goes as follows:
1. Draw a circle.
2. Choose some number of points to draw on the circumference of the circle, such that these points are spaced evenly. 
3. Number the points on the circle starting from 1.
4. Choose a multiplier that is not equal to 1.
5. For each point, multiply its number by the multiplier and take its result modulo the number of points if necessary. The result will be the number of the point to be connected to the first point using a line.

## The results
The resulting artpiece depends on the number of points and multiplier selected by the user. Some possible outputs are as follows:
(WIP)
