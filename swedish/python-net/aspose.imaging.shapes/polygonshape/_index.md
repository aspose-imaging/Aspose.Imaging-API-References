---
title: "PolygonShape‑klass"
type: docs
weight: 60
url: /sv/python-net/aspose.imaging.shapes/polygonshape/
---

**Summary:** Represents a polygon shape.

**Module:** [aspose.imaging.shapes](/imaging/python-net/aspose.imaging.shapes/)

**Full Name:** aspose.imaging.shapes.PolygonShape

**Inheritance:** IOrderedShape, Shape

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [PolygonShape()](#PolygonShape__1) | Initierar en ny instans av klassen [PolygonShape](/imaging/python-net/aspose.imaging.shapes/polygonshape/). |
| [PolygonShape(points)](#PolygonShape_points_2) | Initierar en ny instans av klassen [PolygonShape](/imaging/python-net/aspose.imaging.shapes/polygonshape/). |
| [PolygonShape(points, is_closed)](#PolygonShape_points_is_closed_3) | Initierar en ny instans av klassen [PolygonShape](/imaging/python-net/aspose.imaging.shapes/polygonshape/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r | Hämtar objektets gränser. |
| center | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Hämtar figurens centrum. |
| end_point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Hämtar den avslutande formpunkten. |
| has_segments | bool | r | Hämtar ett värde som indikerar om figuren har segment. |
| is_closed | bool | r/w | Hämtar eller anger ett värde som indikerar om formen är sluten. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | r/w | Hämtar eller anger kurvpunkterna. |
| segments | [ShapeSegment[]](/imaging/python-net/aspose.imaging/shapesegment/) | r | Hämtar figurens segment. |
| start_point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Hämtar startpunkten för formen. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_bounds(matrix)](#get_bounds_matrix_1) | Hämtar objektets gränser. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_2) | Hämtar objektets gränser. |
| reverse() | Vänder på ordningen av punkter för denna form. |
| [transform(transform)](#transform_transform_3) | Tillämpar den angivna transformationen på formen. |


### Constructor: PolygonShape() {#PolygonShape__1}


```
 PolygonShape() 
```

Initierar en ny instans av klassen [PolygonShape](/imaging/python-net/aspose.imaging.shapes/polygonshape/).

### Constructor: PolygonShape(points) {#PolygonShape_points_2}


```
 PolygonShape(points) 
```

Initierar en ny instans av klassen [PolygonShape](/imaging/python-net/aspose.imaging.shapes/polygonshape/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Punktarrayen. |

### Constructor: PolygonShape(points, is_closed) {#PolygonShape_points_is_closed_3}


```
 PolygonShape(points, is_closed) 
```

Initierar en ny instans av klassen [PolygonShape](/imaging/python-net/aspose.imaging.shapes/polygonshape/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Punktarrayen. |
| is_closed | bool | Om den är inställd på <c>true</c> är polygonen sluten. |

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

