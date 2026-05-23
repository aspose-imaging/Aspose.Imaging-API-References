---
title: "PieShape-klass"
type: docs
weight: 50
url: /sv/python-net/aspose.imaging.shapes/pieshape/
---

**Summary:** Represents a pie shape.

**Module:** [aspose.imaging.shapes](/imaging/python-net/aspose.imaging.shapes/)

**Full Name:** aspose.imaging.shapes.PieShape

**Inheritance:** EllipseShape

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [PieShape()](#PieShape__1) | Initierar en ny instans av klassen [PieShape](/imaging/python-net/aspose.imaging.shapes/pieshape/). |
| [PieShape(rectangle, start_angle, sweep_angle)](#PieShape_rectangle_start_angle_sweep_angle_2) | Initierar en ny instans av klassen [PieShape](/imaging/python-net/aspose.imaging.shapes/pieshape/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r | Hämtar objektets gränser. |
| center | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Hämtar figurens centrum. |
| has_segments | bool | r | Hämtar ett värde som indikerar om figuren har segment. |
| left_bottom | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Hämtar den vänstra nedre rektangelpunkten. |
| left_top | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Hämtar den vänstra övre rektangelpunkten. |
| rectangle_height | float | r | Hämtar rektangelns höjd. |
| rectangle_width | float | r | Hämtar rektangelns bredd. |
| right_bottom | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Hämtar den högra nedre rektangelpunkten. |
| right_top | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Hämtar den högra övre rektangelpunkten. |
| segments | [ShapeSegment[]](/imaging/python-net/aspose.imaging/shapesegment/) | r | Hämtar figurens segment. |
| start_angle | float | r/w | Hämtar eller anger startvinkeln. |
| sweep_angle | float | r/w | Hämtar eller anger svepvinkeln. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_bounds(matrix)](#get_bounds_matrix_1) | Hämtar objektets gränser. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_2) | Hämtar objektets gränser. |
| [transform(transform)](#transform_transform_3) | Tillämpar den angivna transformationen på formen. |


### Constructor: PieShape() {#PieShape__1}


```
 PieShape() 
```

Initierar en ny instans av klassen [PieShape](/imaging/python-net/aspose.imaging.shapes/pieshape/).

### Constructor: PieShape(rectangle, start_angle, sweep_angle) {#PieShape_rectangle_start_angle_sweep_angle_2}


```
 PieShape(rectangle, start_angle, sweep_angle) 
```

Initierar en ny instans av klassen [PieShape](/imaging/python-net/aspose.imaging.shapes/pieshape/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Rektangeln. |
| start_angle | float | Startvinkeln. |
| sweep_angle | float | Svepningsvinkeln. |


**See also:**

**[Example # 1](#example_13)**: This examples make use of GraphicsPath and Graphics classes to create and man...


### Method: get_bounds(matrix) {#get_bounds_matrix_1}


```
 get_bounds(matrix) 
```

Hämtar objektets gränser.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Matrisen att tillämpa innan gränserna beräknas. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Det uppskattade objektets gränser. |


### Method: get_bounds(matrix, pen) {#get_bounds_matrix_pen_2}


```
 get_bounds(matrix, pen) 
```

Hämtar objektets gränser.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Matrisen att tillämpa innan gränserna beräknas. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Pennan att använda för objektet. Detta kan påverka objektets gränsstorlek. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Det uppskattade objektets gränser. |


### Method: transform(transform) {#transform_transform_3}


```
 transform(transform) 
```

Tillämpar den angivna transformationen på formen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| transform | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Transformationen att tillämpa. |

## **Examples**
### This examples make use of GraphicsPath and Graphics classes to create and manipulate figures on an Image surface. Example creates a new Image (of type Tiff), clears the surface and draws paths with the help of GraphicsPath class. At the end `draw_path` method exposed by Graphics class is called to render the paths on surface. {#example_13}
``` python

from aspose.imaging import Image, Graphics, Color, GraphicsPath, Figure, RectangleF, PointF, SizeF
from aspose.imaging import Pen
from aspose.imaging.sources import StreamSource
from aspose.imaging.imageoptions import TiffOptions
from aspose.imaging.fileformats.tiff.enums import TiffExpectedFormat
from aspose.imaging.shapes import RectangleShape, EllipseShape, PieShape


# Skapa en instans av en filström
with open(r"C:\temp\output.tiff", "w+b") as stream:
	# Skapa en instans av TiffOptions och ställ in dess olika egenskaper
	tiffOptions = TiffOptions(TiffExpectedFormat.DEFAULT)
	# Ange källan för instansen av ImageOptions
	tiffOptions.source = StreamSource(stream)
	# Skapa en instans av Image
	with Image.create(tiffOptions, 500, 500) as image:
		# Skapa och initiera en instans av Graphics-klassen
		graphics = Graphics(image)
		# Rensa Graphics-ytan
		graphics.clear(Color.wheat);
		# Skapa en instans av klassen GraphicsPath
		graphics_path = GraphicsPath()
		# Skapa en instans av klassen Figure
		figure = Figure()
		# Lägg till former till Figure-objektet
		figure.add_shape(RectangleShape(RectangleF(10.0, 10.0, 300.0, 300.0)))
		figure.add_shape(EllipseShape(RectangleF(50.0, 50.0, 300.0, 300.0)))
		figure.add_shape(PieShape(RectangleF(PointF(250.0, 250.0), SizeF(200.0, 200.0)), 0.0, 45.0))
		# Lägg till Figure-objektet till GraphicsPath
		graphics_path.add_figure(figure)
		# Rita bana med Pen-objektet i färgen svart
		graphics.draw_path(Pen(Color.black, 2.0), graphics_path)
		# spara alla ändringar.
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

#Skapar en instans av BmpOptions och ställer in dess olika egenskaper            
with BmpOptions() as bmpOptions:
	bmpOptions.bits_per_pixel = 24
	#Skapa en instans av FileCreateSource och tilldela den som källa för instansen av BmpOptions
	#Den andra booleska parametern bestämmer om filen som ska skapas är temporär eller inte
	bmpOptions.source = FileCreateSource(r"c:\temp\output.bmp", False)
	#Skapa en instans av Image
	with Image.create(bmpOptions, 500, 500) as image:
		# Skapa och initiera en instans av Graphics-klassen
		graphics = Graphics(image)
		# Rensa Graphics-ytan
		graphics.clear(Color.wheat)
		# Skapa en instans av klassen GraphicsPath
		graphicspath = GraphicsPath()
		#Skapa en instans av klassen Figure
		figure1 = Figure()
		# Lägg till form till Figure-objektet
		figure1.add_shape(EllipseShape(RectangleF(50, 50, 300, 300)))
		figure1.add_shape(PieShape(Rectangle(Point(110, 110), Size(200, 200)), 0, 90))
		# Skapa en instans av klassen Figure
		figure2 = Figure()
		# Lägg till form till Figure-objektet
		figure2.add_shape(ArcShape(RectangleF(10, 10, 300, 300), 0, 45))
		figure2.add_shape(
			PolygonShape([PointF(150, 10), PointF(150, 200), PointF(250, 300), PointF(350, 400)], True))
		figure2.add_shape(RectangleShape(RectangleF(Point(250, 250), Size(200, 200))))
		# Lägg till Figure-objektet till GraphicsPath
		graphicspath.add_figures([figure1, figure2])
		# Rita bana med Pen-objektet i färgen svart
		graphics.draw_path(Pen(Color.black, 2.0), graphicspath)
		# spara alla ändringar.
		image.save()


```

