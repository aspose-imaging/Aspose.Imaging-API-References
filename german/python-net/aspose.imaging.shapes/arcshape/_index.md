---
title: "ArcShape Klasse"
type: docs
weight: 10
url: /de/python-net/aspose.imaging.shapes/arcshape/
---

**Summary:** Represents an arc shape.

**Module:** [aspose.imaging.shapes](/imaging/python-net/aspose.imaging.shapes/)

**Full Name:** aspose.imaging.shapes.ArcShape

**Inheritance:** IOrderedShape, PieShape

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [ArcShape()](#ArcShape__1) | Initialisiert eine neue Instanz der [ArcShape](/imaging/python-net/aspose.imaging.shapes/arcshape/) Klasse. |
| [ArcShape(rectangle, start_angle, sweep_angle)](#ArcShape_rectangle_start_angle_sweep_angle_2) | Initialisiert eine neue Instanz der [ArcShape](/imaging/python-net/aspose.imaging.shapes/arcshape/) Klasse. |
| [ArcShape(rectangle, start_angle, sweep_angle, is_closed)](#ArcShape_rectangle_start_angle_sweep_angle_is_closed_3) | Initialisiert eine neue Instanz der [ArcShape](/imaging/python-net/aspose.imaging.shapes/arcshape/) Klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r | Liest die Begrenzungen des Objekts. |
| center | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Gibt das Zentrum der Form zurück. |
| end_point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Gibt den Endpunkt der Form zurück. |
| has_segments | bool | r | Gibt einen Wert zurück, der angibt, ob die Form Segmente hat. |
| is_closed | bool | r/w | Liest oder setzt einen Wert, der angibt, ob die geordnete Form geschlossen ist. Beim Verarbeiten einer geschlossenen geordneten Form haben der Start- und Endpunkt keine Bedeutung. |
| left_bottom | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Liefert den linken unteren Rechteckpunkt. |
| left_top | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Liefert den linken oberen Rechteckpunkt. |
| rectangle_height | float | r | Liefert die Rechteckhöhe. |
| rectangle_width | float | r | Liefert die Rechteckbreite. |
| right_bottom | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Liefert den rechten unteren Rechteckpunkt. |
| right_top | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Liefert den rechten oberen Rechteckpunkt. |
| segments | [ShapeSegment[]](/imaging/python-net/aspose.imaging/shapesegment/) | r | Gibt die Formsegmente zurück. |
| start_angle | float | r/w | Liest oder setzt den Startwinkel. |
| start_point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Gibt den Startpunkt der Form zurück. |
| sweep_angle | float | r/w | Liest oder setzt den Sweep-Winkel. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [get_bounds(matrix)](#get_bounds_matrix_1) | Liest die Begrenzungen des Objekts. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_2) | Liest die Begrenzungen des Objekts. |
| reverse() | Kehrt die Reihenfolge der Punkte für diese Form um. |
| [transform(transform)](#transform_transform_3) | Wendet die angegebene Transformation auf die Form an. |


### Constructor: ArcShape() {#ArcShape__1}


```
 ArcShape() 
```

Initialisiert eine neue Instanz der [ArcShape](/imaging/python-net/aspose.imaging.shapes/arcshape/) Klasse.

### Constructor: ArcShape(rectangle, start_angle, sweep_angle) {#ArcShape_rectangle_start_angle_sweep_angle_2}


```
 ArcShape(rectangle, start_angle, sweep_angle) 
```

Initialisiert eine neue Instanz der [ArcShape](/imaging/python-net/aspose.imaging.shapes/arcshape/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Das Rechteck. |
| start_angle | float | Der Startwinkel. |
| sweep_angle | float | Der Sweep-Winkel. |


**See also:**

**[Example # 1](#example_16)**: This example creates a new Image and draws a variety of shapes using figures ...


### Constructor: ArcShape(rectangle, start_angle, sweep_angle, is_closed) {#ArcShape_rectangle_start_angle_sweep_angle_is_closed_3}


```
 ArcShape(rectangle, start_angle, sweep_angle, is_closed) 
```

Initialisiert eine neue Instanz der [ArcShape](/imaging/python-net/aspose.imaging.shapes/arcshape/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Das Rechteck. |
| start_angle | float | Der Startwinkel. |
| sweep_angle | float | Der Sweep-Winkel. |
| is_closed | bool | Wenn auf <c>true</c> gesetzt, ist der Bogen geschlossen. Der geschlossene Bogen degeneriert tatsächlich zu einer Ellipse. |

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

