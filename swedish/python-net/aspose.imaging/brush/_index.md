---
title: "Brush klass"
type: docs
weight: 340
url: /sv/python-net/aspose.imaging/brush/
---

**Summary:** The base brush class.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.Brush

**Inheritance:** DisposableObject

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| disposed | bool | r | Hämtar ett värde som indikerar om den här instansen är frigjord. |
| [opacity](#opacity1) | float | r/w | Hämtar eller anger penselns opacitet. Värdet bör vara mellan 0 och 1. Ett värde på 0 betyder att penseln är helt synlig, ett värde på 1 betyder att penseln är helt ogenomskinlig. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [deep_clone()](#deep_clone__1) | Skapar en ny djupklon av den aktuella [Brush](/imaging/python-net/aspose.imaging/brush/). |


### Property: opacity {#opacity1}

Hämtar eller anger penselns opacitet. Värdet bör vara mellan 0 och 1. Ett värde på 0 betyder att penseln är helt synlig, ett värde på 1 betyder att penseln är helt ogenomskinlig.

**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: deep_clone() {#deep_clone__1}


```
 deep_clone() 
```

Skapar en ny djupklon av den aktuella [Brush](/imaging/python-net/aspose.imaging/brush/).

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Brush](/imaging/python-net/aspose.imaging/brush/) | En ny [Brush](/imaging/python-net/aspose.imaging/brush/) som är den djupa klonen av detta [Brush](/imaging/python-net/aspose.imaging/brush/)-instans. |


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

#Skapar en instans av filström
with open(r"C:\temp\output.png", "w+b") as stream:
	#Skapa en instans av PngOptions och ange dess olika egenskaper
	pngOptions = PngOptions()
	#Ange källan för PngOptions
	pngOptions.source = StreamSource(stream)
	#Skapa en instans av Image
	with Image.create(pngOptions, 500, 500) as image:
		#Skapa och initiera en instans av Graphics-klassen
		graphics = Graphics(image)
		#Rensa Graphics-ytan
		graphics.clear(Color.wheat);
		#Rita en båge genom att ange Pen-objektet med svart färg, 
		#en rektangel som omger bågen, startvinkel och svepvinkel
		graphics.draw_arc(Pen(Color.black, 2.0), Rectangle(200, 200, 100, 200), 0, 300)
		#Rita en Bezier genom att ange Pen-objektet med blå färg och koordinatpunkter.
		graphics.draw_bezier(Pen(Color.blue, 2.0), Point(250, 100), Point(300, 30), Point(450, 100), Point(235, 25))
		#Rita en kurva genom att specificera Pen-objektet med grön färg och en array av punkter
		graphics.draw_curve(Pen(Color.green, 2.0), [Point(100, 200), Point(100, 350), Point(200, 450)])
		#Rita en ellips med Pen-objektet och en omgivande Rectangle
		graphics.draw_ellipse(Pen(Color.yellow, 2.0), Rectangle(300, 300, 100, 100))
		#Rita en linje
		graphics.draw_line(Pen(Color.violet, 2.0), Point(100, 100), Point(200, 200))
		#Rita ett pajsegment
		graphics.draw_pie(Pen(Color.silver, 2.0), Rectangle(Point(200, 20), Size(200, 200)), 0, 45);
		#Rita en polygon genom att specificera Pen-objektet med röd färg och en array av punkter
		graphics.draw_polygon(Pen(Color.red, 2.0), [Point(20, 100), Point(20, 200), Point(220, 20)])
		#Rita en Rectangle
		graphics.draw_rectangle(Pen(Color.orange, 2.0), Rectangle(Point(250, 250), Size(100, 100)))
		#Skapa ett SolidBrush-objekt och sätt dess olika egenskaper
		brush = SolidBrush()
		brush.color = Color.purple
		#Rita en String med SolidBrush-objektet och Font, vid en specifik Point
		graphics.draw_string("This image is created by Aspose.Imaging API", Font("Times New Roman", 16),
							 brush, PointF(50.0, 400.0))
		# spara alla ändringar.
		image.save();

```

