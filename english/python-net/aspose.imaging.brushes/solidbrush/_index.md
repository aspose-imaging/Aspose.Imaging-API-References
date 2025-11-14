---
title: SolidBrush Class
type: docs
weight: 80
url: /python-net/aspose.imaging.brushes/solidbrush/
---

**Summary:** Solid brush is intended for drawing continiously with specific color. This class cannot be inherited.

**Module:** [aspose.imaging.brushes](/imaging/python-net/aspose.imaging.brushes/)

**Full Name:** aspose.imaging.brushes.SolidBrush

**Inheritance:** Brush

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [SolidBrush()](#SolidBrush__1) | Initializes a new instance of the [SolidBrush](/imaging/python-net/aspose.imaging.brushes/solidbrush/) class. |
| [SolidBrush(color)](#SolidBrush_color_2) | Initializes a new instance of the [SolidBrush](/imaging/python-net/aspose.imaging.brushes/solidbrush/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| [color](#color1) | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Gets or sets the brush color. |
| disposed | bool | r | Gets a value indicating whether this instance is disposed. |
| opacity | float | r/w | Gets or sets the brush opacity. The value should be between 0 and 1. Value of 0 means that brush is fully visible, value of 1 means the brush is fully opaque. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [deep_clone()](#deep_clone__1) | Creates a new deep clone of the current [Brush](/imaging/python-net/aspose.imaging/brush/). |


### Constructor: SolidBrush() {#SolidBrush__1}


```
 SolidBrush() 
```

Initializes a new instance of the [SolidBrush](/imaging/python-net/aspose.imaging.brushes/solidbrush/) class.


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Constructor: SolidBrush(color) {#SolidBrush_color_2}


```
 SolidBrush(color) 
```

Initializes a new instance of the [SolidBrush](/imaging/python-net/aspose.imaging.brushes/solidbrush/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| color | [Color](/imaging/python-net/aspose.imaging/color/) | The solid brush color. |

### Property: color {#color1}

Gets or sets the brush color.

**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: deep_clone() {#deep_clone__1}


```
 deep_clone() 
```

Creates a new deep clone of the current [Brush](/imaging/python-net/aspose.imaging/brush/).

**Returns**

| Type | Description |
| :- | :- |
| [Brush](/imaging/python-net/aspose.imaging/brush/) | A new [Brush](/imaging/python-net/aspose.imaging/brush/) which is the deep clone of this [Brush](/imaging/python-net/aspose.imaging/brush/) instance. |


## **Examples**
### This example uses Graphics class to create primitive shapes on the Image surface. To demonstrate the operation, the example creates a new Image in PNG format and draw primitive shapes on Image surface using Draw methods exposed by Graphics class {#example_12}
``` python

from aspose.imaging import Image, RotateFlipType, Graphics, Color, Pen, Rectangle, Point, Size,\
	Font, PointF
from aspose.imaging.brushes import SolidBrush
from aspose.imaging.imageoptions import PngOptions
from aspose.imaging.fileformats.psd import CompressionMethod, ColorModes
from aspose.imaging.sources import StreamSource

from os.path import join as path_join

#Creates an instance of file stream
with open(r"C:\temp\output.png", "w+b") as stream:
	#Create an instance of PngOptions and set its various properties
	pngOptions = PngOptions()
	#Set the Source for PngOptions
	pngOptions.source = StreamSource(stream)
	#Create an instance of Image 
	with Image.create(pngOptions, 500, 500) as image:
		#Create and initialize an instance of Graphics class
		graphics = Graphics(image)
		#Clear Graphics surface
		graphics.clear(Color.wheat);
		#Draw an Arc by specifying the Pen object having Black color, 
		#a Rectangle surrounding the Arc, Start Angle and Sweep Angle
		graphics.draw_arc(Pen(Color.black, 2.0), Rectangle(200, 200, 100, 200), 0, 300)
		#Draw a Bezier by specifying the Pen object having Blue color and co-ordinate Points.
		graphics.draw_bezier(Pen(Color.blue, 2.0), Point(250, 100), Point(300, 30), Point(450, 100), Point(235, 25))
		#Draw a Curve by specifying the Pen object having Green color and an array of Points
		graphics.draw_curve(Pen(Color.green, 2.0), [Point(100, 200), Point(100, 350), Point(200, 450)])
		#Draw an Ellipse using the Pen object and a surrounding Rectangle
		graphics.draw_ellipse(Pen(Color.yellow, 2.0), Rectangle(300, 300, 100, 100))
		#Draw a Line 
		graphics.draw_line(Pen(Color.violet, 2.0), Point(100, 100), Point(200, 200))
		#Draw a Pie segment
		graphics.draw_pie(Pen(Color.silver, 2.0), Rectangle(Point(200, 20), Size(200, 200)), 0, 45);
		#Draw a Polygon by specifying the Pen object having Red color and an array of Points
		graphics.draw_polygon(Pen(Color.red, 2.0), [Point(20, 100), Point(20, 200), Point(220, 20)])
		#Draw a Rectangle
		graphics.draw_rectangle(Pen(Color.orange, 2.0), Rectangle(Point(250, 250), Size(100, 100)))
		#Create a SolidBrush object and set its various properties
		brush = SolidBrush()
		brush.color = Color.purple
		#Draw a String using the SolidBrush object and Font, at specific Point
		graphics.draw_string("This image is created by Aspose.Imaging API", Font("Times New Roman", 16),
							 brush, PointF(50.0, 400.0))
		# save all changes.
		image.save();

```

