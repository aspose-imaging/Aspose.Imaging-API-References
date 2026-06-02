---
title: "Clase SolidBrush"
type: docs
weight: 80
url: /es/python-net/aspose.imaging.brushes/solidbrush/
---

**Summary:** Solid brush is intended for drawing continiously with specific color. This class cannot be inherited.

**Module:** [aspose.imaging.brushes](/imaging/python-net/aspose.imaging.brushes/)

**Full Name:** aspose.imaging.brushes.SolidBrush

**Inheritance:** Brush

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [SolidBrush()](#SolidBrush__1) | Inicializa una nueva instancia de la clase [SolidBrush](/imaging/python-net/aspose.imaging.brushes/solidbrush/). |
| [SolidBrush(color)](#SolidBrush_color_2) | Inicializa una nueva instancia de la clase [SolidBrush](/imaging/python-net/aspose.imaging.brushes/solidbrush/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| [color](#color1) | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Obtiene o establece el color del pincel. |
| disposed | bool | r | Obtiene un valor que indica si esta instancia está disposed. |
| opacity | float | r/w | Obtiene o establece la opacidad del pincel. El valor debe estar entre 0 y 1. Un valor de 0 significa que el pincel es totalmente visible, un valor de 1 significa que el pincel es totalmente opaco. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [deep_clone()](#deep_clone__1) | Crea una nueva clonación profunda del [Brush](/imaging/python-net/aspose.imaging/brush/) actual. |


### Constructor: SolidBrush() {#SolidBrush__1}


```
 SolidBrush() 
```

Inicializa una nueva instancia de la clase [SolidBrush](/imaging/python-net/aspose.imaging.brushes/solidbrush/).


**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Constructor: SolidBrush(color) {#SolidBrush_color_2}


```
 SolidBrush(color) 
```

Inicializa una nueva instancia de la clase [SolidBrush](/imaging/python-net/aspose.imaging.brushes/solidbrush/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| color | [Color](/imaging/python-net/aspose.imaging/color/) | El color del pincel sólido. |

### Property: color {#color1}

Obtiene o establece el color del pincel.

**See also:**

**[Example # 1](#example_12)**: This example uses Graphics class to create primitive shapes on the Image surf...


### Method: deep_clone() {#deep_clone__1}


```
 deep_clone() 
```

Crea una nueva clonación profunda del [Brush](/imaging/python-net/aspose.imaging/brush/) actual.

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Brush](/imaging/python-net/aspose.imaging/brush/) | Un nuevo [Brush](/imaging/python-net/aspose.imaging/brush/) que es la clonación profunda de esta instancia de [Brush](/imaging/python-net/aspose.imaging/brush/). |


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

#Crea una instancia de flujo de archivo
with open(r"C:\temp\output.png", "w+b") as stream:
	#Crea una instancia de PngOptions y establece sus diversas propiedades
	pngOptions = PngOptions()
	#Establece la fuente para PngOptions
	pngOptions.source = StreamSource(stream)
	#Crea una instancia de Image
	with Image.create(pngOptions, 500, 500) as image:
		#Crea e inicializa una instancia de la clase Graphics
		graphics = Graphics(image)
		#Limpia la superficie Graphics
		graphics.clear(Color.wheat);
		#Dibuja un arco especificando el objeto Pen que tiene color negro, 
		#un rectángulo que rodea el arco, ángulo de inicio y ángulo de barrido
		graphics.draw_arc(Pen(Color.black, 2.0), Rectangle(200, 200, 100, 200), 0, 300)
		#Dibuja una curva Bézier especificando el objeto Pen que tiene color azul y puntos de coordenadas.
		graphics.draw_bezier(Pen(Color.blue, 2.0), Point(250, 100), Point(300, 30), Point(450, 100), Point(235, 25))
		#Dibuje una curva especificando el objeto Pen con color Verde y una matriz de Points
		graphics.draw_curve(Pen(Color.green, 2.0), [Point(100, 200), Point(100, 350), Point(200, 450)])
		#Dibuje una elipse usando el objeto Pen y un Rectangle circundante
		graphics.draw_ellipse(Pen(Color.yellow, 2.0), Rectangle(300, 300, 100, 100))
		#Dibuje una línea
		graphics.draw_line(Pen(Color.violet, 2.0), Point(100, 100), Point(200, 200))
		#Dibuje un segmento de Pie
		graphics.draw_pie(Pen(Color.silver, 2.0), Rectangle(Point(200, 20), Size(200, 200)), 0, 45);
		#Dibuje un polígono especificando el objeto Pen con color Rojo y una matriz de Points
		graphics.draw_polygon(Pen(Color.red, 2.0), [Point(20, 100), Point(20, 200), Point(220, 20)])
		#Dibuje un Rectangle
		graphics.draw_rectangle(Pen(Color.orange, 2.0), Rectangle(Point(250, 250), Size(100, 100)))
		#Cree un objeto SolidBrush y establezca sus diversas propiedades
		brush = SolidBrush()
		brush.color = Color.purple
		#Dibuje un String usando el objeto SolidBrush y Font, en un Point específico
		graphics.draw_string("This image is created by Aspose.Imaging API", Font("Times New Roman", 16),
							 brush, PointF(50.0, 400.0))
		# guarde todos los cambios.
		image.save();

```

