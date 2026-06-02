---
title: "PolygonShape Klasse"
type: docs
weight: 60
url: /de/python-net/aspose.imaging.shapes/polygonshape/
---

**Summary:** Represents a polygon shape.

**Module:** [aspose.imaging.shapes](/imaging/python-net/aspose.imaging.shapes/)

**Full Name:** aspose.imaging.shapes.PolygonShape

**Inheritance:** IOrderedShape, Shape

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [PolygonShape()](#PolygonShape__1) | Initialisiert eine neue Instanz der [PolygonShape](/imaging/python-net/aspose.imaging.shapes/polygonshape/) Klasse. |
| [PolygonShape(points)](#PolygonShape_points_2) | Initialisiert eine neue Instanz der [PolygonShape](/imaging/python-net/aspose.imaging.shapes/polygonshape/) Klasse. |
| [PolygonShape(points, is_closed)](#PolygonShape_points_is_closed_3) | Initialisiert eine neue Instanz der [PolygonShape](/imaging/python-net/aspose.imaging.shapes/polygonshape/) Klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r | Liest die Begrenzungen des Objekts. |
| center | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Gibt das Zentrum der Form zurück. |
| end_point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Gibt den Endpunkt der Form zurück. |
| has_segments | bool | r | Gibt einen Wert zurück, der angibt, ob die Form Segmente hat. |
| is_closed | bool | r/w | Liest oder setzt einen Wert, der angibt, ob die Form geschlossen ist. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | r/w | Liest oder setzt die Kurvenpunkte. |
| segments | [ShapeSegment[]](/imaging/python-net/aspose.imaging/shapesegment/) | r | Gibt die Formsegmente zurück. |
| start_point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Gibt den Startpunkt der Form zurück. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [get_bounds(matrix)](#get_bounds_matrix_1) | Liest die Begrenzungen des Objekts. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_2) | Liest die Begrenzungen des Objekts. |
| reverse() | Kehrt die Reihenfolge der Punkte für diese Form um. |
| [transform(transform)](#transform_transform_3) | Wendet die angegebene Transformation auf die Form an. |


### Constructor: PolygonShape() {#PolygonShape__1}


```
 PolygonShape() 
```

Initialisiert eine neue Instanz der [PolygonShape](/imaging/python-net/aspose.imaging.shapes/polygonshape/) Klasse.

### Constructor: PolygonShape(points) {#PolygonShape_points_2}


```
 PolygonShape(points) 
```

Initialisiert eine neue Instanz der [PolygonShape](/imaging/python-net/aspose.imaging.shapes/polygonshape/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Das Punkte-Array. |

### Constructor: PolygonShape(points, is_closed) {#PolygonShape_points_is_closed_3}


```
 PolygonShape(points, is_closed) 
```

Initialisiert eine neue Instanz der [PolygonShape](/imaging/python-net/aspose.imaging.shapes/polygonshape/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Das Punkte-Array. |
| is_closed | bool | Wenn auf <c>true</c> gesetzt, ist das Polygon geschlossen. |

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

