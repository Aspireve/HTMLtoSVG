# HTMLtoSVG
A simple repository showing how to create a SVG using the HTML tag.
Final goal is to replcate the YouTube's Homesreen.

## Description
This project aims to provide a comprehensive guide on creating custom Scalable Vector Graphics (SVG) from simple HTML code. By following the steps outlined in this guide, you will be able to design and create a simple Youtube Home Screen Clone and overall be able to customize SVG images for use in web applications.

## Table of Contents
- [Installation](#installation) 
- [Usage](#usage)
- [Examples](#examples)
- [License](#license)
- [Acknowledgements](#acknowledgements)


## Installation
To run this code you could just clone it or directly download the zip folder and extract it.
If the browser you are running is working correctly, then the code should work too.
Simply clone the repository to your local machine.
For changing the code open the project in your preferred text editor or IDE (eg. VSCode).


## Usage
Navigate to the project directory.
Review the provided HTML code examples ```index.html``` folder.
Follow the step-by-step instructions in the accompanying documentation to create custom SVGs from the HTML code.
Experiment with different HTML elements, attributes, and styles to achieve the desired SVG design.
Test your SVGs in a web browser or integrate them into your web applications.


## Examples
The examples/ folder contains a variety of HTML code samples demonstrating the conversion of HTML elements into SVGs. Each example is accompanied by comments explaining the process and providing additional insights.

### SVG Tag

| ![image](https://github.com/Aspireve/HTMLtoSVG/assets/93852415/0dfa916f-9701-45a0-ace0-14fd8e192426)  |
|:--:|
| The entire thing is in a SVG tag   |

The SVG tag is denoted by <svg> and is typically paired with a closing </svg> tag to encapsulate SVG content.
```HTML
<svg width="" height="" viewBox="" preserveAspectRatio-"" xmlns="">
 <other stuff />
</svg>
<!--
width: Specifies the width of the SVG viewport.
height: Specifies the height of the SVG viewport.
viewBox: It consists of four values: min-x, min-y, width, and height.
preserveAspectRatio: Controls how the SVG content scales and aligns within the viewport.
xmlns: Specifies the XML namespace for SVG. It should be set to "http://www.w3.org/2000/svg".
-->
```

### Group Tag
|![image](https://github.com/Aspireve/HTMLtoSVG/assets/93852415/04a73e5e-e546-4b0c-bc7e-af49dc01af83) |
|:--:|
| These are two groups since they have a similar structure |

The <g> tag in SVG stands for "group" and is used to group multiple SVG elements together. It allows you to treat a set of elements as a single unit, making it easier to manipulate and style them collectively. Here are the various attributes associated with the <g> tag

```HTML
<g id="" class="" transform="" opacity="" clip-path="" >
  <other elements />
</g>
<!-- 
id: Specifies a unique identifier for the group element.

class: Assigns one or more CSS classes to the group element.

transform: Applies a transformation to the group and its child elements.

opacity: Sets the opacity level for the group and its child elements.

style: Specifies inline CSS styles for the group element. 

clip-path: Defines a clipping path for the group and its child elements.

mask: Applies a mask to the group and its child elements.
-->
```

### Rectangle Tag
| ![image](https://github.com/Aspireve/HTMLtoSVG/assets/93852415/7ebfd90c-57bc-4cdd-96d8-eddf2357807f) |
 |:--:|
  | These are rounded rectangles |
  
The <rect> SVG tag is used to draw rectangles or rounded rectangles on an SVG canvas. It allows you to define the position, size, and appearance of the rectangle. Here, we will discuss the various attributes that can be used with the <rect> tag:
```HTML
<rect x="" y="" width="" height="" rx="" ry="" />
<!--
x: Specifies the x-coordinate of the rectangle's starting point (top-left corner).
y: Specifies the y-coordinate of the rectangle's starting point (top-left corner).
width: Defines the width of the rectangle.
height: Defines the height of the rectangle.
rx (optional): Specifies the horizontal radius of the rounded corners of the rectangle.
ry (optional): Specifies the vertical radius of the rounded corners of the rectangle.
fill (optional): Determines the fill color of the rectangle.
-->
```
  
### Polygon Tag
| ![image](https://github.com/Aspireve/HTMLtoSVG/assets/93852415/0fb41653-fb0e-4365-8410-151e9ac440f6) |
  |:--:|
  | We use the polygon tag to create a triangle in the YouTube logo since there isnt any premade triangle |
  
The <polygon> SVG tag is used to create a closed shape consisting of straight lines in an SVG image. It is a versatile element that allows you to define complex polygons by specifying the coordinates of its vertices. Here are the various attributes commonly used with the <polygon> tag:

```HTML
<polygon points="x1,y1 x2,y2" fill="" stroke="" stroke-width="" />
<!--
points: It accepts a list of x, y coordinate pairs separated by spaces or commas.

fill: This attribute determines the color or pattern used to fill the polygon.

stroke: This attribute defines the color of the outline stroke of the polygon.

stroke-width: This attribute sets the width of the outline stroke in pixels.
-->

```


## License
This project is licensed under the Apache License 2.0 - see the [LICENSE](LICENSE) file for details.

## Acknowledgements
This project was inspired by the need to create custom SVGs from simple HTML for web applications. Special thanks to the online SVG communities and tutorials that provided valuable resources for understanding SVG creation techniques.
