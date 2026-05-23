---
title: "Classe PolygonShape"
type: docs
weight: 60
url: /it/python-net/aspose.imaging.shapes/polygonshape/
---

**Summary:** Represents a polygon shape.

**Module:** [aspose.imaging.shapes](/imaging/python-net/aspose.imaging.shapes/)

**Full Name:** aspose.imaging.shapes.PolygonShape

**Inheritance:** IOrderedShape, Shape

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [PolygonShape()](#PolygonShape__1) | Inizializza una nuova istanza della classe [PolygonShape](/imaging/python-net/aspose.imaging.shapes/polygonshape/). |
| [PolygonShape(points)](#PolygonShape_points_2) | Inizializza una nuova istanza della classe [PolygonShape](/imaging/python-net/aspose.imaging.shapes/polygonshape/). |
| [PolygonShape(points, is_closed)](#PolygonShape_points_is_closed_3) | Inizializza una nuova istanza della classe [PolygonShape](/imaging/python-net/aspose.imaging.shapes/polygonshape/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r | Ottiene i limiti dell'oggetto. |
| center | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Restituisce il centro della forma. |
| end_point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Ottiene il punto finale della forma. |
| has_segments | bool | r | Restituisce un valore che indica se la forma ha segmenti. |
| is_closed | bool | r/w | Ottiene o imposta un valore che indica se la forma è chiusa. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | r/w | Ottiene o imposta i punti della curva. |
| segments | [ShapeSegment[]](/imaging/python-net/aspose.imaging/shapesegment/) | r | Restituisce i segmenti della forma. |
| start_point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Ottiene il punto iniziale della forma. |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [get_bounds(matrix)](#get_bounds_matrix_1) | Ottiene i limiti dell'oggetto. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_2) | Ottiene i limiti dell'oggetto. |
| reverse() | Inverte l'ordine dei punti per questa forma. |
| [transform(transform)](#transform_transform_3) | Applica la trasformazione specificata alla forma. |


### Constructor: PolygonShape() {#PolygonShape__1}


```
 PolygonShape() 
```

Inizializza una nuova istanza della classe [PolygonShape](/imaging/python-net/aspose.imaging.shapes/polygonshape/).

### Constructor: PolygonShape(points) {#PolygonShape_points_2}


```
 PolygonShape(points) 
```

Inizializza una nuova istanza della classe [PolygonShape](/imaging/python-net/aspose.imaging.shapes/polygonshape/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | L'array dei punti. |

### Constructor: PolygonShape(points, is_closed) {#PolygonShape_points_is_closed_3}


```
 PolygonShape(points, is_closed) 
```

Inizializza una nuova istanza della classe [PolygonShape](/imaging/python-net/aspose.imaging.shapes/polygonshape/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | L'array dei punti. |
| is_closed | bool | Se impostato su <c>true</c> il poligono è chiuso. |

### Method: get_bounds(matrix) {#get_bounds_matrix_1}


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


### Method: get_bounds(matrix, pen) {#get_bounds_matrix_pen_2}


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


### Method: transform(transform) {#transform_transform_3}


```
 transform(transform) 
```

Applica la trasformazione specificata alla forma.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| transform | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | La trasformazione da applicare. |

## **Examples**
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

