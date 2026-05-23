---
title: "EllipseShape Klasse"
type: docs
weight: 40
url: /de/python-net/aspose.imaging.shapes/ellipseshape/
---

**Summary:** Represents an ellipse shape.

**Module:** [aspose.imaging.shapes](/imaging/python-net/aspose.imaging.shapes/)

**Full Name:** aspose.imaging.shapes.EllipseShape

**Inheritance:** RectangleShape

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [EllipseShape()](#EllipseShape__1) | Initialisiert eine neue Instanz der Klasse [EllipseShape](/imaging/python-net/aspose.imaging.shapes/ellipseshape/). |
| [EllipseShape(rectangle)](#EllipseShape_rectangle_2) | Initialisiert eine neue Instanz der Klasse [EllipseShape](/imaging/python-net/aspose.imaging.shapes/ellipseshape/). |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r | Liest die Begrenzungen des Objekts. |
| center | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Gibt das Zentrum der Form zurück. |
| has_segments | bool | r | Gibt einen Wert zurück, der angibt, ob die Form Segmente hat. |
| left_bottom | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Liefert den linken unteren Rechteckpunkt. |
| left_top | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Liefert den linken oberen Rechteckpunkt. |
| rectangle_height | float | r | Liefert die Rechteckhöhe. |
| rectangle_width | float | r | Liefert die Rechteckbreite. |
| right_bottom | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Liefert den rechten unteren Rechteckpunkt. |
| right_top | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Liefert den rechten oberen Rechteckpunkt. |
| segments | [ShapeSegment[]](/imaging/python-net/aspose.imaging/shapesegment/) | r | Gibt die Formsegmente zurück. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [get_bounds(matrix)](#get_bounds_matrix_1) | Liest die Begrenzungen des Objekts. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_2) | Liest die Begrenzungen des Objekts. |
| [transform(transform)](#transform_transform_3) | Wendet die angegebene Transformation auf die Form an. |


### Constructor: EllipseShape() {#EllipseShape__1}


```
 EllipseShape() 
```

Initialisiert eine neue Instanz der Klasse [EllipseShape](/imaging/python-net/aspose.imaging.shapes/ellipseshape/).

### Constructor: EllipseShape(rectangle) {#EllipseShape_rectangle_2}


```
 EllipseShape(rectangle) 
```

Initialisiert eine neue Instanz der Klasse [EllipseShape](/imaging/python-net/aspose.imaging.shapes/ellipseshape/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Das Rechteck. |


**See also:**

**[Example # 1](#example_13)**: This examples make use of GraphicsPath and Graphics classes to create and man...


### Method: get_bounds(matrix) {#get_bounds_matrix_1}


```
 get_bounds(matrix) 
```

Liest die Begrenzungen des Objekts.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Die Matrix, die angewendet wird, bevor die Begrenzungen berechnet werden. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Die geschätzten Begrenzungen des Objekts. |


### Method: get_bounds(matrix, pen) {#get_bounds_matrix_pen_2}


```
 get_bounds(matrix, pen) 
```

Liest die Begrenzungen des Objekts.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Die Matrix, die angewendet wird, bevor die Begrenzungen berechnet werden. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Der Stift, der für das Objekt verwendet wird. Dies kann die Größe der Begrenzungen des Objekts beeinflussen. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Die geschätzten Begrenzungen des Objekts. |


### Method: transform(transform) {#transform_transform_3}


```
 transform(transform) 
```

Wendet die angegebene Transformation auf die Form an.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| transform | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Die anzuwendende Transformation. |

## **Examples**
### This examples make use of GraphicsPath and Graphics classes to create and manipulate figures on an Image surface. Example creates a new Image (of type Tiff), clears the surface and draws paths with the help of GraphicsPath class. At the end `draw_path` method exposed by Graphics class is called to render the paths on surface. {#example_13}
``` python

from aspose.imaging import Image, Graphics, Color, GraphicsPath, Figure, RectangleF, PointF, SizeF
from aspose.imaging import Pen
from aspose.imaging.sources import StreamSource
from aspose.imaging.imageoptions import TiffOptions
from aspose.imaging.fileformats.tiff.enums import TiffExpectedFormat
from aspose.imaging.shapes import RectangleShape, EllipseShape, PieShape


# Erstelle eine Instanz eines Dateistreams
with open(r"C:\temp\output.tiff", "w+b") as stream:
	# Erstellen Sie eine Instanz von TiffOptions und setzen Sie deren verschiedene Eigenschaften
	tiffOptions = TiffOptions(TiffExpectedFormat.DEFAULT)
	# Legen Sie die Quelle für die Instanz von ImageOptions fest
	tiffOptions.source = StreamSource(stream)
	# Erstellen Sie eine Instanz von Image
	with Image.create(tiffOptions, 500, 500) as image:
		# Erstelle und initialisiere eine Instanz der Graphics Klasse.
		graphics = Graphics(image)
		# Lösche die Graphics-Oberfläche.
		graphics.clear(Color.wheat);
		# Erstellen Sie eine Instanz der Klasse GraphicsPath
		graphics_path = GraphicsPath()
		# Erstellen Sie eine Instanz der Klasse Figure
		figure = Figure()
		# Fügen Sie dem Figure-Objekt Formen hinzu
		figure.add_shape(RectangleShape(RectangleF(10.0, 10.0, 300.0, 300.0)))
		figure.add_shape(EllipseShape(RectangleF(50.0, 50.0, 300.0, 300.0)))
		figure.add_shape(PieShape(RectangleF(PointF(250.0, 250.0), SizeF(200.0, 200.0)), 0.0, 45.0))
		# Fügen Sie das Figure-Objekt zu GraphicsPath hinzu
		graphics_path.add_figure(figure)
		# Zeichnen Sie den Pfad mit dem Pen-Objekt in der Farbe Schwarz
		graphics.draw_path(Pen(Color.black, 2.0), graphics_path)
		# Alle Änderungen speichern.
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

#Erstellt eine Instanz von BmpOptions und setzt deren verschiedene Eigenschaften
with BmpOptions() as bmpOptions:
	bmpOptions.bits_per_pixel = 24
	#Erstellen Sie eine Instanz von FileCreateSource und weisen Sie sie als Quelle für die Instanz von BmpOptions zu
	#Der zweite boolesche Parameter bestimmt, ob die zu erstellende Datei temporär ist oder nicht
	bmpOptions.source = FileCreateSource(r"c:\temp\output.bmp", False)
	#Erstelle eine Instanz von Image.
	with Image.create(bmpOptions, 500, 500) as image:
		# Erstelle und initialisiere eine Instanz der Graphics Klasse.
		graphics = Graphics(image)
		# Lösche die Graphics-Oberfläche.
		graphics.clear(Color.wheat)
		# Erstellen Sie eine Instanz der Klasse GraphicsPath
		graphicspath = GraphicsPath()
		#Erstellen Sie eine Instanz der Klasse Figure
		figure1 = Figure()
		# Fügen Sie dem Figure-Objekt eine Form hinzu
		figure1.add_shape(EllipseShape(RectangleF(50, 50, 300, 300)))
		figure1.add_shape(PieShape(Rectangle(Point(110, 110), Size(200, 200)), 0, 90))
		# Erstellen Sie eine Instanz der Klasse Figure
		figure2 = Figure()
		# Fügen Sie dem Figure-Objekt eine Form hinzu
		figure2.add_shape(ArcShape(RectangleF(10, 10, 300, 300), 0, 45))
		figure2.add_shape(
			PolygonShape([PointF(150, 10), PointF(150, 200), PointF(250, 300), PointF(350, 400)], True))
		figure2.add_shape(RectangleShape(RectangleF(Point(250, 250), Size(200, 200))))
		# Fügen Sie das Figure-Objekt zu GraphicsPath hinzu
		graphicspath.add_figures([figure1, figure2])
		# Zeichnen Sie den Pfad mit dem Pen-Objekt in der Farbe Schwarz
		graphics.draw_path(Pen(Color.black, 2.0), graphicspath)
		# Alle Änderungen speichern.
		image.save()


```

