---
title: "Clase ArcShape"
type: docs
weight: 10
url: /es/python-net/aspose.imaging.shapes/arcshape/
---

**Summary:** Represents an arc shape.

**Module:** [aspose.imaging.shapes](/imaging/python-net/aspose.imaging.shapes/)

**Full Name:** aspose.imaging.shapes.ArcShape

**Inheritance:** IOrderedShape, PieShape

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [ArcShape()](#ArcShape__1) | Inicializa una nueva instancia de la clase [ArcShape](/imaging/python-net/aspose.imaging.shapes/arcshape/). |
| [ArcShape(rectangle, start_angle, sweep_angle)](#ArcShape_rectangle_start_angle_sweep_angle_2) | Inicializa una nueva instancia de la clase [ArcShape](/imaging/python-net/aspose.imaging.shapes/arcshape/). |
| [ArcShape(rectangle, start_angle, sweep_angle, is_closed)](#ArcShape_rectangle_start_angle_sweep_angle_is_closed_3) | Inicializa una nueva instancia de la clase [ArcShape](/imaging/python-net/aspose.imaging.shapes/arcshape/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r | Obtiene los límites del objeto. |
| center | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Obtiene el centro de la forma. |
| end_point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Obtiene el punto final de la forma. |
| has_segments | bool | r | Obtiene un valor que indica si la forma tiene segmentos. |
| is_closed | bool | r/w | Obtiene o establece un valor que indica si la forma ordenada está cerrada. Al procesar una forma ordenada cerrada, los puntos de inicio y fin no tienen significado. |
| left_bottom | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Obtiene el punto inferior izquierdo del rectángulo. |
| left_top | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Obtiene el punto superior izquierdo del rectángulo. |
| rectangle_height | float | r | Obtiene la altura del rectángulo. |
| rectangle_width | float | r | Obtiene el ancho del rectángulo. |
| right_bottom | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Obtiene el punto inferior derecho del rectángulo. |
| right_top | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Obtiene el punto superior derecho del rectángulo. |
| segments | [ShapeSegment[]](/imaging/python-net/aspose.imaging/shapesegment/) | r | Obtiene los segmentos de la forma. |
| start_angle | float | r/w | Obtiene o establece el ángulo de inicio. |
| start_point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Obtiene el punto inicial de la forma. |
| sweep_angle | float | r/w | Obtiene o establece el ángulo de barrido. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [get_bounds(matrix)](#get_bounds_matrix_1) | Obtiene los límites del objeto. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_2) | Obtiene los límites del objeto. |
| reverse() | Invierte el orden de los puntos de esta forma. |
| [transform(transform)](#transform_transform_3) | Aplica la transformación especificada a la forma. |


### Constructor: ArcShape() {#ArcShape__1}


```
 ArcShape() 
```

Inicializa una nueva instancia de la clase [ArcShape](/imaging/python-net/aspose.imaging.shapes/arcshape/).

### Constructor: ArcShape(rectangle, start_angle, sweep_angle) {#ArcShape_rectangle_start_angle_sweep_angle_2}


```
 ArcShape(rectangle, start_angle, sweep_angle) 
```

Inicializa una nueva instancia de la clase [ArcShape](/imaging/python-net/aspose.imaging.shapes/arcshape/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | El rectángulo. |
| start_angle | float | El ángulo de inicio. |
| sweep_angle | float | El ángulo de barrido. |


**See also:**

**[Example # 1](#example_16)**: This example creates a new Image and draws a variety of shapes using figures ...


### Constructor: ArcShape(rectangle, start_angle, sweep_angle, is_closed) {#ArcShape_rectangle_start_angle_sweep_angle_is_closed_3}


```
 ArcShape(rectangle, start_angle, sweep_angle, is_closed) 
```

Inicializa una nueva instancia de la clase [ArcShape](/imaging/python-net/aspose.imaging.shapes/arcshape/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | El rectángulo. |
| start_angle | float | El ángulo de inicio. |
| sweep_angle | float | El ángulo de barrido. |
| is_closed | bool | Si se establece en <c>true</c> el arco está cerrado. El arco cerrado en realidad se degenera en una elipse. |

### Method: get_bounds(matrix) {#get_bounds_matrix_1}


```
 get_bounds(matrix) 
```

Obtiene los límites del objeto.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | La matriz a aplicar antes de que se calculen los límites. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Los límites estimados del objeto. |


### Method: get_bounds(matrix, pen) {#get_bounds_matrix_pen_2}


```
 get_bounds(matrix, pen) 
```

Obtiene los límites del objeto.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | La matriz a aplicar antes de que se calculen los límites. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | El lápiz a usar para el objeto. Esto puede influir en el tamaño de los límites del objeto. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Los límites estimados del objeto. |


### Method: transform(transform) {#transform_transform_3}


```
 transform(transform) 
```

Aplica la transformación especificada a la forma.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| transform | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | La transformación a aplicar. |

## **Examples**
### This example creates a new Image and draws a variety of shapes using figures and `GraphicsPath` on the `Image` surface {#example_16}
``` python

from aspose.imaging import Image, Graphics, Color, GraphicsPath, Figure, RectangleF, Rectangle, Size
from aspose.imaging import Point, PointF, Pen
from aspose.imaging.imageoptions import BmpOptions
from aspose.imaging.sources import FileCreateSource
from aspose.imaging.shapes import EllipseShape, PieShape, ArcShape, PolygonShape, RectangleShape
from os.path import join as path_join

#Crea una instancia de BmpOptions y establezca sus diversas propiedades            
with BmpOptions() as bmpOptions:
	bmpOptions.bits_per_pixel = 24
	#Cree una instancia de FileCreateSource y asígnela como Source para la instancia de BmpOptions
	#El segundo parámetro Boolean determina si el archivo a crear es IsTemporal o no
	bmpOptions.source = FileCreateSource(r"c:\temp\output.bmp", False)
	#Crea una instancia de Image
	with Image.create(bmpOptions, 500, 500) as image:
		# Crea e inicializa una instancia de la clase Graphics
		graphics = Graphics(image)
		# Limpia la superficie Graphics
		graphics.clear(Color.wheat)
		# Cree una instancia de la clase GraphicsPath
		graphicspath = GraphicsPath()
		#Cree una instancia de la clase Figure
		figure1 = Figure()
		# Agregue Shape al objeto Figure
		figure1.add_shape(EllipseShape(RectangleF(50, 50, 300, 300)))
		figure1.add_shape(PieShape(Rectangle(Point(110, 110), Size(200, 200)), 0, 90))
		# Cree una instancia de la clase Figure
		figure2 = Figure()
		# Agregue Shape al objeto Figure
		figure2.add_shape(ArcShape(RectangleF(10, 10, 300, 300), 0, 45))
		figure2.add_shape(
			PolygonShape([PointF(150, 10), PointF(150, 200), PointF(250, 300), PointF(350, 400)], True))
		figure2.add_shape(RectangleShape(RectangleF(Point(250, 250), Size(200, 200))))
		# Agregue el objeto Figure a GraphicsPath
		graphicspath.add_figures([figure1, figure2])
		# Dibuje la ruta con el objeto Pen de color Black
		graphics.draw_path(Pen(Color.black, 2.0), graphicspath)
		# guarde todos los cambios.
		image.save()


```

