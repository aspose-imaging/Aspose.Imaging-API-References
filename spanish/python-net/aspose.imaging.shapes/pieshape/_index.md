---
title: "Clase PieShape"
type: docs
weight: 50
url: /es/python-net/aspose.imaging.shapes/pieshape/
---

**Summary:** Represents a pie shape.

**Module:** [aspose.imaging.shapes](/imaging/python-net/aspose.imaging.shapes/)

**Full Name:** aspose.imaging.shapes.PieShape

**Inheritance:** EllipseShape

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [PieShape()](#PieShape__1) | Inicializa una nueva instancia de la clase [PieShape](/imaging/python-net/aspose.imaging.shapes/pieshape/). |
| [PieShape(rectangle, start_angle, sweep_angle)](#PieShape_rectangle_start_angle_sweep_angle_2) | Inicializa una nueva instancia de la clase [PieShape](/imaging/python-net/aspose.imaging.shapes/pieshape/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r | Obtiene los límites del objeto. |
| center | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Obtiene el centro de la forma. |
| has_segments | bool | r | Obtiene un valor que indica si la forma tiene segmentos. |
| left_bottom | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Obtiene el punto inferior izquierdo del rectángulo. |
| left_top | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Obtiene el punto superior izquierdo del rectángulo. |
| rectangle_height | float | r | Obtiene la altura del rectángulo. |
| rectangle_width | float | r | Obtiene el ancho del rectángulo. |
| right_bottom | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Obtiene el punto inferior derecho del rectángulo. |
| right_top | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Obtiene el punto superior derecho del rectángulo. |
| segments | [ShapeSegment[]](/imaging/python-net/aspose.imaging/shapesegment/) | r | Obtiene los segmentos de la forma. |
| start_angle | float | r/w | Obtiene o establece el ángulo de inicio. |
| sweep_angle | float | r/w | Obtiene o establece el ángulo de barrido. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [get_bounds(matrix)](#get_bounds_matrix_1) | Obtiene los límites del objeto. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_2) | Obtiene los límites del objeto. |
| [transform(transform)](#transform_transform_3) | Aplica la transformación especificada a la forma. |


### Constructor: PieShape() {#PieShape__1}


```
 PieShape() 
```

Inicializa una nueva instancia de la clase [PieShape](/imaging/python-net/aspose.imaging.shapes/pieshape/).

### Constructor: PieShape(rectangle, start_angle, sweep_angle) {#PieShape_rectangle_start_angle_sweep_angle_2}


```
 PieShape(rectangle, start_angle, sweep_angle) 
```

Inicializa una nueva instancia de la clase [PieShape](/imaging/python-net/aspose.imaging.shapes/pieshape/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | El rectángulo. |
| start_angle | float | El ángulo de inicio. |
| sweep_angle | float | El ángulo de barrido. |


**See also:**

**[Example # 1](#example_13)**: This examples make use of GraphicsPath and Graphics classes to create and man...


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
### This examples make use of GraphicsPath and Graphics classes to create and manipulate figures on an Image surface. Example creates a new Image (of type Tiff), clears the surface and draws paths with the help of GraphicsPath class. At the end `draw_path` method exposed by Graphics class is called to render the paths on surface. {#example_13}
``` python

from aspose.imaging import Image, Graphics, Color, GraphicsPath, Figure, RectangleF, PointF, SizeF
from aspose.imaging import Pen
from aspose.imaging.sources import StreamSource
from aspose.imaging.imageoptions import TiffOptions
from aspose.imaging.fileformats.tiff.enums import TiffExpectedFormat
from aspose.imaging.shapes import RectangleShape, EllipseShape, PieShape


# Crea una instancia de un flujo de archivo
with open(r"C:\temp\output.tiff", "w+b") as stream:
	# Cree una instancia de TiffOptions y establezca sus diversas propiedades
	tiffOptions = TiffOptions(TiffExpectedFormat.DEFAULT)
	# Establezca la fuente para la instancia de ImageOptions
	tiffOptions.source = StreamSource(stream)
	# Cree una instancia de Image
	with Image.create(tiffOptions, 500, 500) as image:
		# Crea e inicializa una instancia de la clase Graphics
		graphics = Graphics(image)
		# Limpia la superficie Graphics
		graphics.clear(Color.wheat);
		# Cree una instancia de la clase GraphicsPath
		graphics_path = GraphicsPath()
		# Cree una instancia de la clase Figure
		figure = Figure()
		# Agregue Shapes al objeto Figure
		figure.add_shape(RectangleShape(RectangleF(10.0, 10.0, 300.0, 300.0)))
		figure.add_shape(EllipseShape(RectangleF(50.0, 50.0, 300.0, 300.0)))
		figure.add_shape(PieShape(RectangleF(PointF(250.0, 250.0), SizeF(200.0, 200.0)), 0.0, 45.0))
		# Agregue el objeto Figure a GraphicsPath
		graphics_path.add_figure(figure)
		# Dibuje la ruta con el objeto Pen de color Black
		graphics.draw_path(Pen(Color.black, 2.0), graphics_path)
		# guarde todos los cambios.
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

