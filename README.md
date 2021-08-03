# RoundArt
RoundArt is a static website in which users can use 3 sliders to create Mathematical art in a circle. It can be found at [https://roundart.netlify.app](https://roundart.netlify.app).

## Motivation
This project was created as a learning opportunity for working with 2D graphics libraries [(Two.js)](https://two.js.org/) as well as to appreciate the marriage between Mathematics and Art. In addition, RoundArt can be used to engage children to increase their appreciation for geometry, revise concepts like radius and circumference, introduce modular arithmetic and encourage pattern-finding.

## The drawing process
The algorithm for creating the 2D image goes as follows:
1. Draw a circle.
2. Choose some number of points to draw on the circumference of the circle, such that these points are spaced evenly. 
3. Number the points on the circle starting from 1.
4. Choose a multiplier that is not equal to 1.
5. For each point, multiply its number by the multiplier and take its result modulo the number of points if necessary. The result will be the number of the point to be connected to the first point using a line.

## The results
The resulting artpiece depends on the number of points and multiplier selected by the user. Some possible outputs are as follows:

<p float="left">
<img src="https://user-images.githubusercontent.com/77185900/128039102-6e84950c-2eac-4089-9b2b-25d9b7a914fc.png" alt="" width="200"/>
<img src="https://user-images.githubusercontent.com/77185900/128039116-db18a76a-bdb6-420a-9000-733dc9a870e1.png" alt="" width="200"/>
<img src="https://user-images.githubusercontent.com/77185900/128039125-8332e118-7568-4499-9f25-55ee24fbaf9a.png" alt="" width="200"/>
<img src="https://user-images.githubusercontent.com/77185900/128039133-602caeb4-13f1-4834-8580-097f130319bf.png" alt="" width="200"/>
<img src="https://user-images.githubusercontent.com/77185900/128040221-c3a7dc4f-1e94-4ace-96ba-49d9c73e3d79.png" alt="" width="200"/>
<img src="https://user-images.githubusercontent.com/77185900/128040229-0e0b004f-bf0b-44af-bbef-35b2a7f480b6.png" alt="" width="200"/>
<img src="https://user-images.githubusercontent.com/77185900/128040232-c7b77406-d027-4e69-83b4-2450b9107281.png" alt="" width="200"/>
<img src="https://user-images.githubusercontent.com/77185900/128040233-790454c1-2ba4-450a-8a7d-e66125ba52e4.png" alt="" width="200"/>
</p>

## Technologies

- HTML, CSS, JavaScript
- Two.js 
