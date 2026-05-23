---
title: "Classe ArcShape"
type: docs
weight: 10
url: /it/python-net/aspose.imaging.shapes/arcshape/
---

**Summary:** Represents an arc shape.

**Module:** [aspose.imaging.shapes](/imaging/python-net/aspose.imaging.shapes/)

**Full Name:** aspose.imaging.shapes.ArcShape

**Inheritance:** IOrderedShape, PieShape

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [ArcShape()](#ArcShape__1) | Inizializza una nuova istanza della classe [ArcShape](/imaging/python-net/aspose.imaging.shapes/arcshape/). |
| [ArcShape(rectangle, start_angle, sweep_angle)](#ArcShape_rectangle_start_angle_sweep_angle_2) | Inizializza una nuova istanza della classe [ArcShape](/imaging/python-net/aspose.imaging.shapes/arcshape/). |
| [ArcShape(rectangle, start_angle, sweep_angle, is_closed)](#ArcShape_rectangle_start_angle_sweep_angle_is_closed_3) | Inizializza una nuova istanza della classe [ArcShape](/imaging/python-net/aspose.imaging.shapes/arcshape/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r | Ottiene i limiti dell'oggetto. |
| center | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Restituisce il centro della forma. |
| end_point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Ottiene il punto finale della forma. |
| has_segments | bool | r | Restituisce un valore che indica se la forma ha segmenti. |
| is_closed | bool | r/w | Ottiene o imposta un valore che indica se la forma ordinata è chiusa. Durante l'elaborazione di una forma ordinata chiusa i punti di inizio e fine non hanno significato. |
| left_bottom | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Restituisce il punto in basso a sinistra del rettangolo. |
| left_top | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Restituisce il punto in alto a sinistra del rettangolo. |
| rectangle_height | float | r | Restituisce l'altezza del rettangolo. |
| rectangle_width | float | r | Restituisce la larghezza del rettangolo. |
| right_bottom | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Restituisce il punto in basso a destra del rettangolo. |
| right_top | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Restituisce il punto in alto a destra del rettangolo. |
| segments | [ShapeSegment[]](/imaging/python-net/aspose.imaging/shapesegment/) | r | Restituisce i segmenti della forma. |
| start_angle | float | r/w | Ottiene o imposta l'angolo di inizio. |
| start_point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Ottiene il punto iniziale della forma. |
| sweep_angle | float | r/w | Ottiene o imposta l'angolo di sweep. |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [get_bounds(matrix)](#get_bounds_matrix_1) | Ottiene i limiti dell'oggetto. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_2) | Ottiene i limiti dell'oggetto. |
| reverse() | Inverte l'ordine dei punti per questa forma. |
| [transform(transform)](#transform_transform_3) | Applica la trasformazione specificata alla forma. |


### Constructor: ArcShape() {#ArcShape__1}


```
 ArcShape() 
```

Inizializza una nuova istanza della classe [ArcShape](/imaging/python-net/aspose.imaging.shapes/arcshape/).

### Constructor: ArcShape(rectangle, start_angle, sweep_angle) {#ArcShape_rectangle_start_angle_sweep_angle_2}


```
 ArcShape(rectangle, start_angle, sweep_angle) 
```

Inizializza una nuova istanza della classe [ArcShape](/imaging/python-net/aspose.imaging.shapes/arcshape/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Il rettangolo. |
| start_angle | float | L'angolo di inizio. |
| sweep_angle | float | L'angolo di sweep. |


**See also:**

**[Example # 1](#example_16)**: This example creates a new Image and draws a variety of shapes using figures ...


### Constructor: ArcShape(rectangle, start_angle, sweep_angle, is_closed) {#ArcShape_rectangle_start_angle_sweep_angle_is_closed_3}


```
 ArcShape(rectangle, start_angle, sweep_angle, is_closed) 
```

Inizializza una nuova istanza della classe [ArcShape](/imaging/python-net/aspose.imaging.shapes/arcshape/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Il rettangolo. |
| start_angle | float | L'angolo di inizio. |
| sweep_angle | float | L'angolo di sweep. |
| is_closed | bool | Se impostato su <c>true</c> l'arco è chiuso. L'arco chiuso in realtà si degenere in un'ellisse. |

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

