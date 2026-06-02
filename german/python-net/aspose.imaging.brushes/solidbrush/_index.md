---
title: "SolidBrush Klasse"
type: docs
weight: 80
url: /de/python-net/aspose.imaging.brushes/solidbrush/
---

**Summary:** Solid brush is intended for drawing continiously with specific color. This class cannot be inherited.

**Module:** [aspose.imaging.brushes](/imaging/python-net/aspose.imaging.brushes/)

**Full Name:** aspose.imaging.brushes.SolidBrush

**Inheritance:** Brush

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [SolidBrush()](#SolidBrush__1) | Initialisiert eine neue Instanz der [SolidBrush](/imaging/python-net/aspose.imaging.brushes/solidbrush/) Klasse. |
| [SolidBrush(color)](#SolidBrush_color_2) | Initialisiert eine neue Instanz der [SolidBrush](/imaging/python-net/aspose.imaging.brushes/solidbrush/) Klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| [color](#color1) | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Liest oder setzt die Pinselfarbe. |
| freigegeben | bool | r | Liest einen Wert, der angibt, ob diese Instanz freigegeben ist. |
| opacity | float | r/w | Ruft die Deckkraft des Pinsels ab oder legt sie fest. Der Wert sollte zwischen 0 und 1 liegen. Ein Wert von 0 bedeutet, dass der Pinsel vollständig sichtbar ist, ein Wert von 1 bedeutet, dass der Pinsel vollständig undurchsichtig ist. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [deep_clone()](#deep_clone__1) | Erstellt einen neuen Deep-Clone des aktuellen [Brush](/imaging/python-net/aspose.imaging/brush/). |


### Constructor: SolidBrush() {#SolidBrush__1}


```
 SolidBrush() 
```

Initialisiert eine neue Instanz der [SolidBrush](/imaging/python-net/aspose.imaging.brushes/solidbrush/) Klasse.


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Constructor: SolidBrush(color) {#SolidBrush_color_2}


```
 SolidBrush(color) 
```

Initialisiert eine neue Instanz der [SolidBrush](/imaging/python-net/aspose.imaging.brushes/solidbrush/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| color | [Color](/imaging/python-net/aspose.imaging/color/) | Die Farbe des SolidBrush. |

### Property: color {#color1}

Liest oder setzt die Pinselfarbe.

**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: deep_clone() {#deep_clone__1}


```
 deep_clone() 
```

Erstellt einen neuen Deep-Clone des aktuellen [Brush](/imaging/python-net/aspose.imaging/brush/).

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Brush](/imaging/python-net/aspose.imaging/brush/) | Ein neuer [Brush](/imaging/python-net/aspose.imaging/brush/), der der Deep-Clone dieser [Brush](/imaging/python-net/aspose.imaging/brush/) Instanz ist. |


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

#Erstellt eine Instanz eines Dateistreams.
with open(r"C:\temp\output.png", "w+b") as stream:
	#Erstelle eine Instanz von PngOptions und setze deren verschiedene Eigenschaften.
	pngOptions = PngOptions()
	#Setze die Quelle für PngOptions.
	pngOptions.source = StreamSource(stream)
	#Erstelle eine Instanz von Image.
	with Image.create(pngOptions, 500, 500) as image:
		#Erstelle und initialisiere eine Instanz der Graphics Klasse.
		graphics = Graphics(image)
		#Lösche die Graphics-Oberfläche.
		graphics.clear(Color.wheat);
		#Zeichne einen Bogen, indem du das Pen-Objekt mit schwarzer Farbe angibst, 
		#ein Rechteck, das den Bogen umgibt, Startwinkel und Sweep-Winkel.
		graphics.draw_arc(Pen(Color.black, 2.0), Rectangle(200, 200, 100, 200), 0, 300)
		#Zeichne eine Bézierkurve, indem du das Pen-Objekt mit blauer Farbe und Koordinatenpunkten angibst.
		graphics.draw_bezier(Pen(Color.blue, 2.0), Point(250, 100), Point(300, 30), Point(450, 100), Point(235, 25))
		#Zeichnen Sie eine Kurve, indem Sie das Pen-Objekt mit grüner Farbe und einem Array von Punkten angeben.
		graphics.draw_curve(Pen(Color.green, 2.0), [Point(100, 200), Point(100, 350), Point(200, 450)])
		#Zeichnen Sie eine Ellipse mit dem Pen-Objekt und einem umgebenden Rechteck.
		graphics.draw_ellipse(Pen(Color.yellow, 2.0), Rectangle(300, 300, 100, 100))
		#Zeichnen Sie eine Linie
		graphics.draw_line(Pen(Color.violet, 2.0), Point(100, 100), Point(200, 200))
		#Zeichnen Sie ein Kuchenstück.
		graphics.draw_pie(Pen(Color.silver, 2.0), Rectangle(Point(200, 20), Size(200, 200)), 0, 45);
		#Zeichnen Sie ein Polygon, indem Sie das Pen-Objekt mit roter Farbe und einem Array von Punkten angeben.
		graphics.draw_polygon(Pen(Color.red, 2.0), [Point(20, 100), Point(20, 200), Point(220, 20)])
		#Zeichnen Sie ein Rechteck.
		graphics.draw_rectangle(Pen(Color.orange, 2.0), Rectangle(Point(250, 250), Size(100, 100)))
		#Erstellen Sie ein SolidBrush-Objekt und setzen Sie dessen verschiedene Eigenschaften.
		brush = SolidBrush()
		brush.color = Color.purple
		#Zeichnen Sie einen String mit dem SolidBrush-Objekt und Font an einem bestimmten Punkt.
		graphics.draw_string("This image is created by Aspose.Imaging API", Font("Times New Roman", 16),
							 brush, PointF(50.0, 400.0))
		# Alle Änderungen speichern.
		image.save();

```

