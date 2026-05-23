---
title: "Brush Classe"
type: docs
weight: 340
url: /it/python-net/aspose.imaging/brush/
---

**Summary:** The base brush class.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.Brush

**Inheritance:** DisposableObject

## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| eliminato | bool | r | Ottiene un valore che indica se questa istanza è stata eliminata. |
| [opacity](#opacity1) | float | r/w | Ottiene o imposta l'opacità del pennello. Il valore deve essere compreso tra 0 e 1. Un valore di 0 indica che il pennello è completamente visibile, un valore di 1 indica che il pennello è completamente opaco. |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [deep_clone()](#deep_clone__1) | Crea una nuova copia profonda dell'attuale [Brush](/imaging/python-net/aspose.imaging/brush/). |


### Property: opacity {#opacity1}

Ottiene o imposta l'opacità del pennello. Il valore deve essere compreso tra 0 e 1. Un valore di 0 indica che il pennello è completamente visibile, un valore di 1 indica che il pennello è completamente opaco.

**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: deep_clone() {#deep_clone__1}


```
 deep_clone() 
```

Crea una nuova copia profonda dell'attuale [Brush](/imaging/python-net/aspose.imaging/brush/).

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Brush](/imaging/python-net/aspose.imaging/brush/) | Un nuovo [Brush](/imaging/python-net/aspose.imaging/brush/) che è la copia profonda di questa istanza [Brush](/imaging/python-net/aspose.imaging/brush/). |


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

#Crea un'istanza di flusso file
with open(r"C:\temp\output.png", "w+b") as stream:
	#Crea un'istanza di PngOptions e imposta le sue varie proprietà
	pngOptions = PngOptions()
	#Imposta la sorgente per PngOptions
	pngOptions.source = StreamSource(stream)
	#Crea un'istanza di Image 
	with Image.create(pngOptions, 500, 500) as image:
		#Crea e inizializza un'istanza della classe Graphics
		graphics = Graphics(image)
		#Cancella la superficie Graphics
		graphics.clear(Color.wheat);
		#Disegna un arco specificando l'oggetto Pen con colore Nero, 
		#un rettangolo che circonda l'arco, angolo di partenza e angolo di sweep
		graphics.draw_arc(Pen(Color.black, 2.0), Rectangle(200, 200, 100, 200), 0, 300)
		#Disegna un Bezier specificando l'oggetto Pen con colore Blu e i punti di coordinate.
		graphics.draw_bezier(Pen(Color.blue, 2.0), Point(250, 100), Point(300, 30), Point(450, 100), Point(235, 25))
		#Disegna una curva specificando l'oggetto Pen con colore Verde e un array di Points
		graphics.draw_curve(Pen(Color.green, 2.0), [Point(100, 200), Point(100, 350), Point(200, 450)])
		#Disegna un'ellisse usando l'oggetto Pen e un Rectangle circostante
		graphics.draw_ellipse(Pen(Color.yellow, 2.0), Rectangle(300, 300, 100, 100))
		#Disegna una linea
		graphics.draw_line(Pen(Color.violet, 2.0), Point(100, 100), Point(200, 200))
		#Disegna un segmento di torta
		graphics.draw_pie(Pen(Color.silver, 2.0), Rectangle(Point(200, 20), Size(200, 200)), 0, 45);
		#Disegna un poligono specificando l'oggetto Pen con colore Rosso e un array di Points
		graphics.draw_polygon(Pen(Color.red, 2.0), [Point(20, 100), Point(20, 200), Point(220, 20)])
		#Disegna un Rectangle
		graphics.draw_rectangle(Pen(Color.orange, 2.0), Rectangle(Point(250, 250), Size(100, 100)))
		#Crea un oggetto SolidBrush e imposta le sue varie proprietà
		brush = SolidBrush()
		brush.color = Color.purple
		#Disegna una String usando l'oggetto SolidBrush e Font, in un Point specifico
		graphics.draw_string("This image is created by Aspose.Imaging API", Font("Times New Roman", 16),
							 brush, PointF(50.0, 400.0))
		# salva tutte le modifiche.
		image.save();

```

