---
title: ArcShape Class
type: docs
weight: 10
url: /python-net/aspose.imaging.shapes/arcshape/
---

**Summary:** Represents an arc shape.

**Module:** [aspose.imaging.shapes](/imaging/python-net/aspose.imaging.shapes/)

**Full Name:** aspose.imaging.shapes.ArcShape

**Inheritance:** IOrderedShape, PieShape

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [ArcShape()](#ArcShape__1) | Initializes a new instance of the [ArcShape](/imaging/python-net/aspose.imaging.shapes/arcshape/) class. |
| [ArcShape(rectangle, start_angle, sweep_angle)](#ArcShape_rectangle_start_angle_sweep_angle_2) | Initializes a new instance of the [ArcShape](/imaging/python-net/aspose.imaging.shapes/arcshape/) class. |
| [ArcShape(rectangle, start_angle, sweep_angle, is_closed)](#ArcShape_rectangle_start_angle_sweep_angle_is_closed_3) | Initializes a new instance of the [ArcShape](/imaging/python-net/aspose.imaging.shapes/arcshape/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r | Gets the object's bounds. |
| center | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Gets the shape's center. |
| end_point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Gets the ending shape point. |
| has_segments | bool | r | Gets a value indicating whether shape has segments. |
| is_closed | bool | r/w | Gets or sets a value indicating whether ordered shape is closed. When processing closed ordered shape the starting and ending points have no meaning. |
| left_bottom | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Gets the left bottom rectangle point. |
| left_top | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Gets the left top rectangle point. |
| rectangle_height | float | r | Gets the rectangle height. |
| rectangle_width | float | r | Gets the rectangle width. |
| right_bottom | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Gets the right bottom rectangle point. |
| right_top | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Gets the right top rectangle point. |
| segments | [ShapeSegment[]](/imaging/python-net/aspose.imaging/shapesegment/) | r | Gets the shape segments. |
| start_angle | float | r/w | Gets or sets the start angle. |
| start_point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Gets the starting shape point. |
| sweep_angle | float | r/w | Gets or sets the sweep angle. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_bounds(matrix)](#get_bounds_matrix_1) | Gets the object's bounds. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_2) | Gets the object's bounds. |
| reverse() | Reverses the order of points for this shape. |
| [transform(transform)](#transform_transform_3) | Applies the specified transformation to the shape. |


### Constructor: ArcShape() {#ArcShape__1}


```
 ArcShape() 
```

Initializes a new instance of the [ArcShape](/imaging/python-net/aspose.imaging.shapes/arcshape/) class.

### Constructor: ArcShape(rectangle, start_angle, sweep_angle) {#ArcShape_rectangle_start_angle_sweep_angle_2}


```
 ArcShape(rectangle, start_angle, sweep_angle) 
```

Initializes a new instance of the [ArcShape](/imaging/python-net/aspose.imaging.shapes/arcshape/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | The rectangle. |
| start_angle | float | The start angle. |
| sweep_angle | float | The sweep angle. |


**See also:**

**[Example # 1](#example_16)**: This example creates a new Image and draws a variety of shapes using figures ...


### Constructor: ArcShape(rectangle, start_angle, sweep_angle, is_closed) {#ArcShape_rectangle_start_angle_sweep_angle_is_closed_3}


```
 ArcShape(rectangle, start_angle, sweep_angle, is_closed) 
```

Initializes a new instance of the [ArcShape](/imaging/python-net/aspose.imaging.shapes/arcshape/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | The rectangle. |
| start_angle | float | The start angle. |
| sweep_angle | float | The sweep angle. |
| is_closed | bool | If set to <c>true</c> the arc is closed. The closed arc is actually degenereates to an ellipse. |

### Method: get_bounds(matrix) {#get_bounds_matrix_1}


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


### Method: get_bounds(matrix, pen) {#get_bounds_matrix_pen_2}


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


### Method: transform(transform) {#transform_transform_3}


```
 transform(transform) 
```

Applies the specified transformation to the shape.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| transform | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | The transformation to apply. |

## **Examples**
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

