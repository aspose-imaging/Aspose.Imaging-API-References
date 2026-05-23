---
title: "Classe Figure"
type: docs
weight: 4770
url: /it/python-net/aspose.imaging/figure/
---

**Summary:** The figure. A container for shapes.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.Figure

**Inheritance:** ObjectWithBounds

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [Figure()](#Figure__1) | Inizializza una nuova istanza di [Figure](/imaging/python-net/aspose.imaging/figure/).<br/>            Un costruttore richiesto per la deserializzazione JSON. |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r | Ottiene o imposta i limiti dell'oggetto. |
| is_closed | bool | r/w | Ottiene o imposta un valore che indica se questa figura è chiusa. Una figura chiusa farà differenza solo nel caso in cui<br/>            le forme della prima e dell'ultima figura siano forme continue. In tal caso il primo punto della prima forma sarà<br/>            collegato da una linea retta all'ultimo punto dell'ultima forma. |
| segments | [ShapeSegment[]](/imaging/python-net/aspose.imaging/shapesegment/) | r | Ottiene tutti i segmenti della figura. |
| shapes | [Shape[]](/imaging/python-net/aspose.imaging/shape/) | r | Ottiene le forme. |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [add_shape(shape)](#add_shape_shape_1) | Aggiunge una forma alla figura. |
| [add_shapes(shapes)](#add_shapes_shapes_2) | Aggiunge un intervallo di forme alla figura. |
| [get_bounds(matrix)](#get_bounds_matrix_3) | Ottiene i limiti dell'oggetto. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_4) | Ottiene i limiti dell'oggetto. |
| [remove_shape(shape)](#remove_shape_shape_5) | Rimuove una forma dalla figura. |
| [remove_shapes(shapes)](#remove_shapes_shapes_6) | Rimuove un intervallo di forme dalla figura. |
| reverse() | Inverte l'ordine delle forme di questa figura e l'ordine dei punti delle forme. |
| [transform(transform)](#transform_transform_7) | Applica la trasformazione specificata alla forma. |


### Constructor: Figure() {#Figure__1}


```
 Figure() 
```

Inizializza una nuova istanza di [Figure](/imaging/python-net/aspose.imaging/figure/).<br/>            Un costruttore richiesto per la deserializzazione JSON.

### Method: add_shape(shape) {#add_shape_shape_1}


```
 add_shape(shape) 
```

Aggiunge una forma alla figura.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| shape | [Shape](/imaging/python-net/aspose.imaging/shape/) | La forma da aggiungere. |


**See also:**

**[Example # 1](#example_13)**: This examples make use of GraphicsPath and Graphics classes to create and man...

**[Example # 2](#example_16)**: This example creates a new Image and draws a variety of shapes using figures ...


### Method: add_shapes(shapes) {#add_shapes_shapes_2}


```
 add_shapes(shapes) 
```

Aggiunge un intervallo di forme alla figura.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| shapes | [Shape[]](/imaging/python-net/aspose.imaging/shape/) | Le forme da aggiungere. |

### Method: get_bounds(matrix) {#get_bounds_matrix_3}


```
 get_bounds(matrix) 
```

Ottiene i limiti dell'oggetto.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | La matrice da applicare prima che i limiti vengano calcolati. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | I limiti stimati dell'oggetto. |


### Method: get_bounds(matrix, pen) {#get_bounds_matrix_pen_4}


```
 get_bounds(matrix, pen) 
```

Ottiene i limiti dell'oggetto.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | La matrice da applicare prima che i limiti vengano calcolati. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | La penna da usare per l'oggetto. Questo può influenzare la dimensione dei limiti dell'oggetto. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | I limiti stimati dell'oggetto. |


### Method: remove_shape(shape) {#remove_shape_shape_5}


```
 remove_shape(shape) 
```

Rimuove una forma dalla figura.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| shape | [Shape](/imaging/python-net/aspose.imaging/shape/) | La forma da rimuovere. |

### Method: remove_shapes(shapes) {#remove_shapes_shapes_6}


```
 remove_shapes(shapes) 
```

Rimuove un intervallo di forme dalla figura.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| shapes | [Shape[]](/imaging/python-net/aspose.imaging/shape/) | L'intervallo di forme da rimuovere. |

### Method: transform(transform) {#transform_transform_7}


```
 transform(transform) 
```

Applica la trasformazione specificata alla forma.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| transform | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | La trasformazione da applicare. |

## **Examples**
### This examples make use of GraphicsPath and Graphics classes to create and manipulate figures on an Image surface. Example creates a new Image (of type Tiff), clears the surface and draws paths with the help of GraphicsPath class. At the end `draw_path` method exposed by Graphics class is called to render the paths on surface. {#example_13}
``` python

from aspose.imaging import Image, Graphics, Color, GraphicsPath, Figure, RectangleF, PointF, SizeF
from aspose.imaging import Pen
from aspose.imaging.sources import StreamSource
from aspose.imaging.imageoptions import TiffOptions
from aspose.imaging.fileformats.tiff.enums import TiffExpectedFormat
from aspose.imaging.shapes import RectangleShape, EllipseShape, PieShape


# Crea un'istanza di un flusso di file
with open(r"C:\temp\output.tiff", "w+b") as stream:
	# Crea un'istanza di TiffOptions e imposta le sue varie proprietà
	tiffOptions = TiffOptions(TiffExpectedFormat.DEFAULT)
	# Imposta la sorgente per l'istanza di ImageOptions
	tiffOptions.source = StreamSource(stream)
	# Crea un'istanza di Image
	with Image.create(tiffOptions, 500, 500) as image:
		# Crea e inizializza un'istanza della classe Graphics
		graphics = Graphics(image)
		# Cancella la superficie Graphics
		graphics.clear(Color.wheat);
		# Crea un'istanza della classe GraphicsPath
		graphics_path = GraphicsPath()
		# Crea un'istanza della classe Figure
		figure = Figure()
		# Aggiungi forme all'oggetto Figure
		figure.add_shape(RectangleShape(RectangleF(10.0, 10.0, 300.0, 300.0)))
		figure.add_shape(EllipseShape(RectangleF(50.0, 50.0, 300.0, 300.0)))
		figure.add_shape(PieShape(RectangleF(PointF(250.0, 250.0), SizeF(200.0, 200.0)), 0.0, 45.0))
		# Aggiungi l'oggetto Figure a GraphicsPath
		graphics_path.add_figure(figure)
		# Disegna il percorso con l'oggetto Pen di colore Nero
		graphics.draw_path(Pen(Color.black, 2.0), graphics_path)
		# salva tutte le modifiche.
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

#Crea un'istanza di BmpOptions e imposta le sue varie proprietà
with BmpOptions() as bmpOptions:
	bmpOptions.bits_per_pixel = 24
	#Crea un'istanza di FileCreateSource e assegnala come sorgente per l'istanza di BmpOptions
	#Il secondo parametro Booleano determina se il file da creare è temporaneo o meno
	bmpOptions.source = FileCreateSource(r"c:\temp\output.bmp", False)
	#Crea un'istanza di Image 
	with Image.create(bmpOptions, 500, 500) as image:
		# Crea e inizializza un'istanza della classe Graphics
		graphics = Graphics(image)
		# Cancella la superficie Graphics
		graphics.clear(Color.wheat)
		# Crea un'istanza della classe GraphicsPath
		graphicspath = GraphicsPath()
		#Crea un'istanza della classe Figure
		figure1 = Figure()
		# Aggiungi forma all'oggetto Figure
		figure1.add_shape(EllipseShape(RectangleF(50, 50, 300, 300)))
		figure1.add_shape(PieShape(Rectangle(Point(110, 110), Size(200, 200)), 0, 90))
		# Crea un'istanza della classe Figure
		figure2 = Figure()
		# Aggiungi forma all'oggetto Figure
		figure2.add_shape(ArcShape(RectangleF(10, 10, 300, 300), 0, 45))
		figure2.add_shape(
			PolygonShape([PointF(150, 10), PointF(150, 200), PointF(250, 300), PointF(350, 400)], True))
		figure2.add_shape(RectangleShape(RectangleF(Point(250, 250), Size(200, 200))))
		# Aggiungi l'oggetto Figure a GraphicsPath
		graphicspath.add_figures([figure1, figure2])
		# Disegna il percorso con l'oggetto Pen di colore Nero
		graphics.draw_path(Pen(Color.black, 2.0), graphicspath)
		# salva tutte le modifiche.
		image.save()


```

