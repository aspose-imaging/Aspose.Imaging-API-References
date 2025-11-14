---
title: Figure Class
type: docs
weight: 4770
url: /python-net/aspose.imaging/figure/
---

**Summary:** The figure. A container for shapes.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.Figure

**Inheritance:** ObjectWithBounds

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Figure()](#Figure__1) | Initializes a new [Figure](/imaging/python-net/aspose.imaging/figure/) instance.<br/>            A constructor required for a JSON deserialization. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r | Gets or sets the object's bounds. |
| is_closed | bool | r/w | Gets or sets a value indicating whether this figure is closed. A closed figure will make a difference only in case where<br/>            the first and the last figure's shapes are continuous shapes. In such case the first point of the first shape will be<br/>            connected by a straight line from the last point of the last shape. |
| segments | [ShapeSegment[]](/imaging/python-net/aspose.imaging/shapesegment/) | r | Gets the whole figure segments. |
| shapes | [Shape[]](/imaging/python-net/aspose.imaging/shape/) | r | Gets the shapes. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_shape(shape)](#add_shape_shape_1) | Adds a shape to the figure. |
| [add_shapes(shapes)](#add_shapes_shapes_2) | Adds a range of shapes to the figure. |
| [get_bounds(matrix)](#get_bounds_matrix_3) | Gets the object's bounds. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_4) | Gets the object's bounds. |
| [remove_shape(shape)](#remove_shape_shape_5) | Removes a shape from the figure. |
| [remove_shapes(shapes)](#remove_shapes_shapes_6) | Removes a range of shapes from the figure. |
| reverse() | Reverses this figure shapes order and shapes point order. |
| [transform(transform)](#transform_transform_7) | Applies the specified transformation to the shape. |


### Constructor: Figure() {#Figure__1}


```
 Figure() 
```

Initializes a new [Figure](/imaging/python-net/aspose.imaging/figure/) instance.<br/>            A constructor required for a JSON deserialization.

### Method: add_shape(shape) {#add_shape_shape_1}


```
 add_shape(shape) 
```

Adds a shape to the figure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| shape | [Shape](/imaging/python-net/aspose.imaging/shape/) | The shape to add. |


**See also:**

**[Example # 1](#example_13)**: This examples make use of GraphicsPath and Graphics classes to create and man...

**[Example # 2](#example_16)**: This example creates a new Image and draws a variety of shapes using figures ...


### Method: add_shapes(shapes) {#add_shapes_shapes_2}


```
 add_shapes(shapes) 
```

Adds a range of shapes to the figure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| shapes | [Shape[]](/imaging/python-net/aspose.imaging/shape/) | The shapes to add. |

### Method: get_bounds(matrix) {#get_bounds_matrix_3}


```
 get_bounds(matrix) 
```

Gets the object's bounds.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | The matrix to apply before bounds will be calculated. |

**Returns**

| Type | Description |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | The estimated object's bounds. |


### Method: get_bounds(matrix, pen) {#get_bounds_matrix_pen_4}


```
 get_bounds(matrix, pen) 
```

Gets the object's bounds.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | The matrix to apply before bounds will be calculated. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | The pen to use for object. This can influence the object's bounds size. |

**Returns**

| Type | Description |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | The estimated object's bounds. |


### Method: remove_shape(shape) {#remove_shape_shape_5}


```
 remove_shape(shape) 
```

Removes a shape from the figure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| shape | [Shape](/imaging/python-net/aspose.imaging/shape/) | The shape to remove. |

### Method: remove_shapes(shapes) {#remove_shapes_shapes_6}


```
 remove_shapes(shapes) 
```

Removes a range of shapes from the figure.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| shapes | [Shape[]](/imaging/python-net/aspose.imaging/shape/) | The shapes range to remove. |

### Method: transform(transform) {#transform_transform_7}


```
 transform(transform) 
```

Applies the specified transformation to the shape.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| transform | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | The transformation to apply. |

## **Examples**
### This examples make use of GraphicsPath and Graphics classes to create and manipulate figures on an Image surface. Example creates a new Image (of type Tiff), clears the surface and draws paths with the help of GraphicsPath class. At the end `draw_path` method exposed by Graphics class is called to render the paths on surface. {#example_13}
``` python

from aspose.imaging import Image, Graphics, Color, GraphicsPath, Figure, RectangleF, PointF, SizeF
from aspose.imaging import Pen
from aspose.imaging.sources import StreamSource
from aspose.imaging.imageoptions import TiffOptions
from aspose.imaging.fileformats.tiff.enums import TiffExpectedFormat
from aspose.imaging.shapes import RectangleShape, EllipseShape, PieShape


# Create an instance of a file stream
with open(r"C:\temp\output.tiff", "w+b") as stream:
	# Create an instance of TiffOptions and set its various properties
	tiffOptions = TiffOptions(TiffExpectedFormat.DEFAULT)
	# Set the source for the instance of ImageOptions
	tiffOptions.source = StreamSource(stream)
	# Create an instance of Image
	with Image.create(tiffOptions, 500, 500) as image:
		# Create and initialize an instance of Graphics class
		graphics = Graphics(image)
		# Clear Graphics surface
		graphics.clear(Color.wheat);
		# Create an instance of GraphicsPath class
		graphics_path = GraphicsPath()
		# Create an instance of Figure class
		figure = Figure()
		# Add Shapes to Figure object
		figure.add_shape(RectangleShape(RectangleF(10.0, 10.0, 300.0, 300.0)))
		figure.add_shape(EllipseShape(RectangleF(50.0, 50.0, 300.0, 300.0)))
		figure.add_shape(PieShape(RectangleF(PointF(250.0, 250.0), SizeF(200.0, 200.0)), 0.0, 45.0))
		# Add Figure object to GraphicsPath
		graphics_path.add_figure(figure)
		# Draw path with Pen object of color Black
		graphics.draw_path(Pen(Color.black, 2.0), graphics_path)
		# save all changes.
		image.save()


```

### This example creates a new Image and draws a variety of shapes using figures and `GraphicsPath` on the `Image` surface {#example_16}
``` python

from aspose.imaging import Image, Graphics, Color, GraphicsPath, Figure, RectangleF, Rectangle, Size
from aspose.imaging import Point, PointF, Pen
from aspose.imaging.imageoptions import BmpOptions
from aspose.imaging.sources import FileCreateSource
from aspose.imaging.shapes import EllipseShape, PieShape, ArcShape, PolygonShape, RectangleShape
from os.path import join as path_join

#Creates an instance of BmpOptions and set its various properties            
with BmpOptions() as bmpOptions:
	bmpOptions.bits_per_pixel = 24
	#Create an instance of FileCreateSource and assign it as Source for the instance of BmpOptions
	#Second Boolean parameter determines if the file to be created IsTemporal or not
	bmpOptions.source = FileCreateSource(r"c:\temp\output.bmp", False)
	#Create an instance of Image 
	with Image.create(bmpOptions, 500, 500) as image:
		# Create and initialize an instance of Graphics class
		graphics = Graphics(image)
		# Clear Graphics surface
		graphics.clear(Color.wheat)
		# Create an instance of GraphicsPath class
		graphicspath = GraphicsPath()
		#Create an instance of Figure class
		figure1 = Figure()
		# Add Shape to Figure object
		figure1.add_shape(EllipseShape(RectangleF(50, 50, 300, 300)))
		figure1.add_shape(PieShape(Rectangle(Point(110, 110), Size(200, 200)), 0, 90))
		# Create an instance of Figure class
		figure2 = Figure()
		# Add Shape to Figure object
		figure2.add_shape(ArcShape(RectangleF(10, 10, 300, 300), 0, 45))
		figure2.add_shape(
			PolygonShape([PointF(150, 10), PointF(150, 200), PointF(250, 300), PointF(350, 400)], True))
		figure2.add_shape(RectangleShape(RectangleF(Point(250, 250), Size(200, 200))))
		# Add Figure object to GraphicsPath
		graphicspath.add_figures([figure1, figure2])
		# Draw path with Pen object of color Black
		graphics.draw_path(Pen(Color.black, 2.0), graphicspath)
		# save all changes.
		image.save()


```

