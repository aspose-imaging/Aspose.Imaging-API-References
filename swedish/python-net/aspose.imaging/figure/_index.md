---
title: "Figurklass"
type: docs
weight: 4770
url: /sv/python-net/aspose.imaging/figure/
---

**Summary:** The figure. A container for shapes.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.Figure

**Inheritance:** ObjectWithBounds

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Figure()](#Figure__1) | Initierar en ny [Figure](/imaging/python-net/aspose.imaging/figure/) instans.<br/>            En konstruktor som krävs för en JSON-deserialisering. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r | Hämtar eller anger objektets gränser. |
| is_closed | bool | r/w | Hämtar eller anger ett värde som indikerar om denna figur är sluten. En sluten figur gör bara skillnad i fall där<br/>            den första och den sista figurens former är kontinuerliga former. I sådant fall kommer den första punkten i den första formen att vara<br/>            ansluten med en rak linje från den sista punkten i den sista formen. |
| segments | [ShapeSegment[]](/imaging/python-net/aspose.imaging/shapesegment/) | r | Hämtar hela figursegmenten. |
| shapes | [Shape[]](/imaging/python-net/aspose.imaging/shape/) | r | Hämtar formerna. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_shape(shape)](#add_shape_shape_1) | Lägger till en form till figuren. |
| [add_shapes(shapes)](#add_shapes_shapes_2) | Lägger till ett intervall av former till figuren. |
| [get_bounds(matrix)](#get_bounds_matrix_3) | Hämtar objektets gränser. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_4) | Hämtar objektets gränser. |
| [remove_shape(shape)](#remove_shape_shape_5) | Tar bort en form från figuren. |
| [remove_shapes(shapes)](#remove_shapes_shapes_6) | Tar bort ett intervall av former från figuren. |
| reverse() | Vänder ordningen på denna figurens former och på formernas punktordning. |
| [transform(transform)](#transform_transform_7) | Tillämpar den angivna transformationen på formen. |


### Constructor: Figure() {#Figure__1}


```
 Figure() 
```

Initierar en ny [Figure](/imaging/python-net/aspose.imaging/figure/) instans.<br/>            En konstruktor som krävs för en JSON-deserialisering.

### Method: add_shape(shape) {#add_shape_shape_1}


```
 add_shape(shape) 
```

Lägger till en form till figuren.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| shape | [Shape](/imaging/python-net/aspose.imaging/shape/) | Formen att lägga till. |


**See also:**

**[Example # 1](#example_13)**: This examples make use of GraphicsPath and Graphics classes to create and man...

**[Example # 2](#example_16)**: This example creates a new Image and draws a variety of shapes using figures ...


### Method: add_shapes(shapes) {#add_shapes_shapes_2}


```
 add_shapes(shapes) 
```

Lägger till ett intervall av former till figuren.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| shapes | [Shape[]](/imaging/python-net/aspose.imaging/shape/) | Formerna att lägga till. |

### Method: get_bounds(matrix) {#get_bounds_matrix_3}


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


### Method: get_bounds(matrix, pen) {#get_bounds_matrix_pen_4}


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


### Method: remove_shape(shape) {#remove_shape_shape_5}


```
 remove_shape(shape) 
```

Tar bort en form från figuren.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| shape | [Shape](/imaging/python-net/aspose.imaging/shape/) | Formen att ta bort. |

### Method: remove_shapes(shapes) {#remove_shapes_shapes_6}


```
 remove_shapes(shapes) 
```

Tar bort ett intervall av former från figuren.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| shapes | [Shape[]](/imaging/python-net/aspose.imaging/shape/) | Intervall av former att ta bort. |

### Method: transform(transform) {#transform_transform_7}


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

