---
title: "Clase Figure"
type: docs
weight: 4770
url: /es/python-net/aspose.imaging/figure/
---

**Summary:** The figure. A container for shapes.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.Figure

**Inheritance:** ObjectWithBounds

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [Figure()](#Figure__1) | Inicializa una nueva instancia de [Figure](/imaging/python-net/aspose.imaging/figure/).<br/>            Un constructor requerido para la deserialización de JSON. |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r | Obtiene o establece los límites del objeto. |
| is_closed | bool | r/w | Obtiene o establece un valor que indica si esta figura está cerrada. Una figura cerrada solo hará una diferencia en el caso en que<br/>            las formas de la primera y la última figura sean formas continuas. En tal caso, el primer punto de la primera forma será<br/>            conectado por una línea recta desde el último punto de la última forma. |
| segments | [ShapeSegment[]](/imaging/python-net/aspose.imaging/shapesegment/) | r | Obtiene todos los segmentos de la figura. |
| shapes | [Shape[]](/imaging/python-net/aspose.imaging/shape/) | r | Obtiene las formas. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [add_shape(shape)](#add_shape_shape_1) | Agrega una forma a la figura. |
| [add_shapes(shapes)](#add_shapes_shapes_2) | Agrega un rango de formas a la figura. |
| [get_bounds(matrix)](#get_bounds_matrix_3) | Obtiene los límites del objeto. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_4) | Obtiene los límites del objeto. |
| [remove_shape(shape)](#remove_shape_shape_5) | Elimina una forma de la figura. |
| [remove_shapes(shapes)](#remove_shapes_shapes_6) | Elimina un rango de formas de la figura. |
| reverse() | Invierte el orden de las formas de esta figura y el orden de los puntos de las formas. |
| [transform(transform)](#transform_transform_7) | Aplica la transformación especificada a la forma. |


### Constructor: Figure() {#Figure__1}


```
 Figure() 
```

Inicializa una nueva instancia de [Figure](/imaging/python-net/aspose.imaging/figure/).<br/>            Un constructor requerido para la deserialización de JSON.

### Method: add_shape(shape) {#add_shape_shape_1}


```
 add_shape(shape) 
```

Agrega una forma a la figura.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| shape | [Shape](/imaging/python-net/aspose.imaging/shape/) | La forma a agregar. |


**See also:**

**[Example # 1](#example_13)**: This examples make use of GraphicsPath and Graphics classes to create and man...

**[Example # 2](#example_16)**: This example creates a new Image and draws a variety of shapes using figures ...


### Method: add_shapes(shapes) {#add_shapes_shapes_2}


```
 add_shapes(shapes) 
```

Agrega un rango de formas a la figura.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| shapes | [Shape[]](/imaging/python-net/aspose.imaging/shape/) | Las formas a agregar. |

### Method: get_bounds(matrix) {#get_bounds_matrix_3}


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


### Method: get_bounds(matrix, pen) {#get_bounds_matrix_pen_4}


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


### Method: remove_shape(shape) {#remove_shape_shape_5}


```
 remove_shape(shape) 
```

Elimina una forma de la figura.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| shape | [Shape](/imaging/python-net/aspose.imaging/shape/) | La forma a eliminar. |

### Method: remove_shapes(shapes) {#remove_shapes_shapes_6}


```
 remove_shapes(shapes) 
```

Elimina un rango de formas de la figura.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| shapes | [Shape[]](/imaging/python-net/aspose.imaging/shape/) | El rango de formas a eliminar. |

### Method: transform(transform) {#transform_transform_7}


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

