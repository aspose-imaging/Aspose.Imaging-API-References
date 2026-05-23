---
title: "Clase Pen"
type: docs
weight: 6890
url: /es/python-net/aspose.imaging/pen/
---

**Summary:** Defines an object used to draw lines, curves and figures.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.Pen

**Inheritance:** TransparencySupporter

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [Pen(brush)](#Pen_brush_1) | Inicializa una nueva instancia de la clase [Pen](/imaging/python-net/aspose.imaging/pen/) con el [Pen.brush](/imaging/python-net/aspose.imaging/pen/) especificado. |
| [Pen(brush, width)](#Pen_brush_width_2) | Inicializa una nueva instancia de la clase [Pen](/imaging/python-net/aspose.imaging/pen/) con el [Pen.brush](/imaging/python-net/aspose.imaging/pen/) y el [Pen.width](/imaging/python-net/aspose.imaging/pen/) especificados. |
| [Pen(color)](#Pen_color_3) | Inicializa una nueva instancia de la clase [Pen](/imaging/python-net/aspose.imaging/pen/) con el color especificado. |
| [Pen(color, width)](#Pen_color_width_4) | Inicializa una nueva instancia de la clase [Pen](/imaging/python-net/aspose.imaging/pen/) con las propiedades [Pen.color](/imaging/python-net/aspose.imaging/pen/) y [Pen.width](/imaging/python-net/aspose.imaging/pen/) especificadas. |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| alignment | [PenAlignment](/imaging/python-net/aspose.imaging/penalignment/) | r/w | Obtiene o establece la alineación de este [Pen](/imaging/python-net/aspose.imaging/pen/). |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | r/w | Obtiene o establece el [Pen.brush](/imaging/python-net/aspose.imaging/pen/) que determina los atributos de este [Pen](/imaging/python-net/aspose.imaging/pen/). |
| color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Obtiene o establece el color de este [Pen](/imaging/python-net/aspose.imaging/pen/). |
| compound_array | float[] | r/w | Obtiene o establece una matriz de valores que especifica un bolígrafo compuesto. Un bolígrafo compuesto dibuja una línea compuesta formada por líneas paralelas y espacios. |
| custom_end_cap | [CustomLineCap](/imaging/python-net/aspose.imaging/customlinecap/) | r/w | Obtiene o establece una tapa personalizada para usar al final de las líneas dibujadas con este [Pen](/imaging/python-net/aspose.imaging/pen/). |
| custom_start_cap | [CustomLineCap](/imaging/python-net/aspose.imaging/customlinecap/) | r/w | Obtiene o establece una tapa personalizada para usar al comienzo de las líneas dibujadas con este [Pen](/imaging/python-net/aspose.imaging/pen/). |
| dash_cap | [DashCap](/imaging/python-net/aspose.imaging/dashcap/) | r/w | Obtiene o establece el estilo de tapa usado al final de los guiones que forman líneas discontinuas dibujadas con este [Pen](/imaging/python-net/aspose.imaging/pen/). |
| dash_offset | float | r/w | Obtiene o establece la distancia desde el inicio de una línea hasta el comienzo de un patrón de guiones. |
| dash_pattern | float[] | r/w | Obtiene o establece una matriz de guiones y espacios personalizados. |
| dash_style | [DashStyle](/imaging/python-net/aspose.imaging/dashstyle/) | r/w | Obtiene o establece el estilo utilizado para líneas discontinuas dibujadas con este [Pen](/imaging/python-net/aspose.imaging/pen/). |
| end_cap | [LineCap](/imaging/python-net/aspose.imaging/linecap/) | r/w | Obtiene o establece el estilo de extremo utilizado al final de las líneas dibujadas con este [Pen](/imaging/python-net/aspose.imaging/pen/). |
| line_join | [LineJoin](/imaging/python-net/aspose.imaging/linejoin/) | r/w | Obtiene o establece el estilo de unión para los extremos de dos líneas consecutivas dibujadas con este [Pen](/imaging/python-net/aspose.imaging/pen/). |
| miter_limit | float | r/w | Obtiene o establece el límite del grosor de la unión en una esquina en ángulo. |
| opacity | float | r/w | Obtiene o establece la opacidad del objeto. El valor debe estar entre 0 y 1. Un valor de 0 significa que el objeto es totalmente visible, un valor de 1 significa que el objeto es totalmente opaco. |
| pen_type | [PenType](/imaging/python-net/aspose.imaging/pentype/) | r | Obtiene el estilo de las líneas dibujadas con este [Pen](/imaging/python-net/aspose.imaging/pen/). |
| start_cap | [LineCap](/imaging/python-net/aspose.imaging/linecap/) | r/w | Obtiene o establece el estilo de extremo utilizado al inicio de las líneas dibujadas con este [Pen](/imaging/python-net/aspose.imaging/pen/). |
| transform | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | Obtiene o establece una copia de la transformación geométrica para este [Pen](/imaging/python-net/aspose.imaging/pen/). |
| width | float | r/w | Obtiene o establece el ancho de este [Pen](/imaging/python-net/aspose.imaging/pen/), en unidades del objeto Graphics utilizado para dibujar. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [create_with_brush(brush)](#create_with_brush_brush_1) | Inicializa una nueva instancia de la clase [Pen](/imaging/python-net/aspose.imaging/pen/) con el [Pen.brush](/imaging/python-net/aspose.imaging/pen/) especificado. |
| [create_with_brush_width(brush, width)](#create_with_brush_width_brush_width_2) | Inicializa una nueva instancia de la clase [Pen](/imaging/python-net/aspose.imaging/pen/) con el [Pen.brush](/imaging/python-net/aspose.imaging/pen/) y el [Pen.width](/imaging/python-net/aspose.imaging/pen/) especificados. |
| [create_with_color(color)](#create_with_color_color_3) | Inicializa una nueva instancia de la clase [Pen](/imaging/python-net/aspose.imaging/pen/) con el color especificado. |
| [create_with_color_width(color, width)](#create_with_color_width_color_width_4) | Inicializa una nueva instancia de la clase [Pen](/imaging/python-net/aspose.imaging/pen/) con las propiedades [Pen.color](/imaging/python-net/aspose.imaging/pen/) y [Pen.width](/imaging/python-net/aspose.imaging/pen/) especificadas. |
| [multiply_transform(matrix)](#multiply_transform_matrix_5) | Multiplica la matriz de transformación de este [Pen](/imaging/python-net/aspose.imaging/pen/) por la [Matrix](/imaging/python-net/aspose.imaging/matrix/) especificada. |
| [multiply_transform(matrix, order)](#multiply_transform_matrix_order_6) | Multiplica la matriz de transformación de este [Pen](/imaging/python-net/aspose.imaging/pen/) por la [Matrix](/imaging/python-net/aspose.imaging/matrix/) especificada en el orden indicado. |
| reset_transform() | Restablece la matriz de transformación geométrica de este [Pen](/imaging/python-net/aspose.imaging/pen/) a la identidad. |
| [rotate_transform(angle)](#rotate_transform_angle_7) | Rota la transformación geométrica local por el ángulo especificado. Este método antepone la rotación a la transformación. |
| [rotate_transform(angle, order)](#rotate_transform_angle_order_8) | Rota la transformación geométrica local por el ángulo especificado en el orden indicado. |
| [scale_transform(sx, sy)](#scale_transform_sx_sy_9) | Escala la transformación geométrica local por los factores especificados. Este método antepone la matriz de escala a la transformación. |
| [scale_transform(sx, sy, order)](#scale_transform_sx_sy_order_10) | Escala la transformación geométrica local por los factores especificados en el orden indicado. |
| [set_line_cap(start_cap, end_cap, dash_cap)](#set_line_cap_start_cap_end_cap_dash_cap_11) | Establece los valores que determinan el estilo de extremo utilizado para terminar las líneas dibujadas por este [Pen](/imaging/python-net/aspose.imaging/pen/). |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_12) | Traslada la transformación geométrica local por las dimensiones especificadas. Este método antepone la traslación a la transformación. |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_13) | Traslada la transformación geométrica local por las dimensiones especificadas en el orden indicado. |


### Constructor: Pen(brush) {#Pen_brush_1}


```
 Pen(brush) 
```

Inicializa una nueva instancia de la clase [Pen](/imaging/python-net/aspose.imaging/pen/) con el [Pen.brush](/imaging/python-net/aspose.imaging/pen/) especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | Un [Pen.brush](/imaging/python-net/aspose.imaging/pen/) que determina las propiedades de relleno de este [Pen](/imaging/python-net/aspose.imaging/pen/). |

### Constructor: Pen(brush, width) {#Pen_brush_width_2}


```
 Pen(brush, width) 
```

Inicializa una nueva instancia de la clase [Pen](/imaging/python-net/aspose.imaging/pen/) con el [Pen.brush](/imaging/python-net/aspose.imaging/pen/) y el [Pen.width](/imaging/python-net/aspose.imaging/pen/) especificados.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | Un [Pen.brush](/imaging/python-net/aspose.imaging/pen/) que determina las características de este [Pen](/imaging/python-net/aspose.imaging/pen/). |
| width | float | El ancho del nuevo [Pen](/imaging/python-net/aspose.imaging/pen/). |

### Constructor: Pen(color) {#Pen_color_3}


```
 Pen(color) 
```

Inicializa una nueva instancia de la clase [Pen](/imaging/python-net/aspose.imaging/pen/) con el color especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| color | [Color](/imaging/python-net/aspose.imaging/color/) | Una estructura [Pen.color](/imaging/python-net/aspose.imaging/pen/) que indica el color de este [Pen](/imaging/python-net/aspose.imaging/pen/). |

### Constructor: Pen(color, width) {#Pen_color_width_4}


```
 Pen(color, width) 
```

Inicializa una nueva instancia de la clase [Pen](/imaging/python-net/aspose.imaging/pen/) con las propiedades [Pen.color](/imaging/python-net/aspose.imaging/pen/) y [Pen.width](/imaging/python-net/aspose.imaging/pen/) especificadas.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| color | [Color](/imaging/python-net/aspose.imaging/color/) | Una estructura [Pen.color](/imaging/python-net/aspose.imaging/pen/) que indica el color de este [Pen](/imaging/python-net/aspose.imaging/pen/). |
| width | float | Un valor que indica el ancho de este [Pen](/imaging/python-net/aspose.imaging/pen/). |


**See also:**

**[Example # 1](#example_14)**: This example shows the creation and usage Pen objects. The example creates a ...


### Method: create_with_brush(brush)  [static] {#create_with_brush_brush_1}


```
 create_with_brush(brush) 
```

Inicializa una nueva instancia de la clase [Pen](/imaging/python-net/aspose.imaging/pen/) con el [Pen.brush](/imaging/python-net/aspose.imaging/pen/) especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | Un [Pen.brush](/imaging/python-net/aspose.imaging/pen/) que determina las propiedades de relleno de este [Pen](/imaging/python-net/aspose.imaging/pen/). |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Pen](/imaging/python-net/aspose.imaging/pen/) |  |


### Method: create_with_brush_width(brush, width)  [static] {#create_with_brush_width_brush_width_2}


```
 create_with_brush_width(brush, width) 
```

Inicializa una nueva instancia de la clase [Pen](/imaging/python-net/aspose.imaging/pen/) con el [Pen.brush](/imaging/python-net/aspose.imaging/pen/) y el [Pen.width](/imaging/python-net/aspose.imaging/pen/) especificados.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| brush | [Brush](/imaging/python-net/aspose.imaging/brush/) | Un [Pen.brush](/imaging/python-net/aspose.imaging/pen/) que determina las características de este [Pen](/imaging/python-net/aspose.imaging/pen/). |
| width | float | El ancho del nuevo [Pen](/imaging/python-net/aspose.imaging/pen/). |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Pen](/imaging/python-net/aspose.imaging/pen/) |  |


### Method: create_with_color(color)  [static] {#create_with_color_color_3}


```
 create_with_color(color) 
```

Inicializa una nueva instancia de la clase [Pen](/imaging/python-net/aspose.imaging/pen/) con el color especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| color | [Color](/imaging/python-net/aspose.imaging/color/) | Una estructura [Pen.color](/imaging/python-net/aspose.imaging/pen/) que indica el color de este [Pen](/imaging/python-net/aspose.imaging/pen/). |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Pen](/imaging/python-net/aspose.imaging/pen/) |  |


### Method: create_with_color_width(color, width)  [static] {#create_with_color_width_color_width_4}


```
 create_with_color_width(color, width) 
```

Inicializa una nueva instancia de la clase [Pen](/imaging/python-net/aspose.imaging/pen/) con las propiedades [Pen.color](/imaging/python-net/aspose.imaging/pen/) y [Pen.width](/imaging/python-net/aspose.imaging/pen/) especificadas.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| color | [Color](/imaging/python-net/aspose.imaging/color/) | Una estructura [Pen.color](/imaging/python-net/aspose.imaging/pen/) que indica el color de este [Pen](/imaging/python-net/aspose.imaging/pen/). |
| width | float | Un valor que indica el ancho de este [Pen](/imaging/python-net/aspose.imaging/pen/). |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Pen](/imaging/python-net/aspose.imaging/pen/) |  |


### Method: multiply_transform(matrix) {#multiply_transform_matrix_5}


```
 multiply_transform(matrix) 
```

Multiplica la matriz de transformación de este [Pen](/imaging/python-net/aspose.imaging/pen/) por la [Matrix](/imaging/python-net/aspose.imaging/matrix/) especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | El objeto [Matrix](/imaging/python-net/aspose.imaging/matrix/) por el cual multiplicar la matriz de transformación. |

### Method: multiply_transform(matrix, order) {#multiply_transform_matrix_order_6}


```
 multiply_transform(matrix, order) 
```

Multiplica la matriz de transformación de este [Pen](/imaging/python-net/aspose.imaging/pen/) por la [Matrix](/imaging/python-net/aspose.imaging/matrix/) especificada en el orden indicado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | El [Matrix](/imaging/python-net/aspose.imaging/matrix/) por el cual multiplicar la matriz de transformación. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | El orden en el que realizar la operación de multiplicación. |

### Method: rotate_transform(angle) {#rotate_transform_angle_7}


```
 rotate_transform(angle) 
```

Rota la transformación geométrica local por el ángulo especificado. Este método antepone la rotación a la transformación.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| angle | float | El ángulo de rotación. |

### Method: rotate_transform(angle, order) {#rotate_transform_angle_order_8}


```
 rotate_transform(angle, order) 
```

Rota la transformación geométrica local por el ángulo especificado en el orden indicado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| angle | float | El ángulo de rotación. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Un [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) que especifica si se debe añadir al final o al principio la matriz de rotación. |

### Method: scale_transform(sx, sy) {#scale_transform_sx_sy_9}


```
 scale_transform(sx, sy) 
```

Escala la transformación geométrica local por los factores especificados. Este método antepone la matriz de escala a la transformación.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| sx | float | El factor por el cual escalar la transformación en la dirección del eje x. |
| sy | float | El factor por el cual escalar la transformación en la dirección del eje y. |

### Method: scale_transform(sx, sy, order) {#scale_transform_sx_sy_order_10}


```
 scale_transform(sx, sy, order) 
```

Escala la transformación geométrica local por los factores especificados en el orden indicado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| sx | float | El factor por el cual escalar la transformación en la dirección del eje x. |
| sy | float | El factor por el cual escalar la transformación en la dirección del eje y. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Un [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) que especifica si se debe agregar o anteponer la matriz de escala. |

### Method: set_line_cap(start_cap, end_cap, dash_cap) {#set_line_cap_start_cap_end_cap_dash_cap_11}


```
 set_line_cap(start_cap, end_cap, dash_cap) 
```

Establece los valores que determinan el estilo de extremo utilizado para terminar las líneas dibujadas por este [Pen](/imaging/python-net/aspose.imaging/pen/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| start_cap | [LineCap](/imaging/python-net/aspose.imaging/linecap/) | Un [LineCap](/imaging/python-net/aspose.imaging/linecap/) que representa el estilo de extremo a usar al inicio de las líneas dibujadas con este [Pen](/imaging/python-net/aspose.imaging/pen/). |
| end_cap | [LineCap](/imaging/python-net/aspose.imaging/linecap/) | Un [LineCap](/imaging/python-net/aspose.imaging/linecap/) que representa el estilo de extremo a usar al final de las líneas dibujadas con este [Pen](/imaging/python-net/aspose.imaging/pen/). |
| dash_cap | [DashCap](/imaging/python-net/aspose.imaging/dashcap/) | Un [LineCap](/imaging/python-net/aspose.imaging/linecap/) que representa el estilo de extremo a usar al inicio o al final de líneas discontinuas dibujadas con este [Pen](/imaging/python-net/aspose.imaging/pen/). |

### Method: translate_transform(dx, dy) {#translate_transform_dx_dy_12}


```
 translate_transform(dx, dy) 
```

Traslada la transformación geométrica local por las dimensiones especificadas. Este método antepone la traslación a la transformación.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| dx | float | El valor de la traslación en x. |
| dy | float | El valor de la traslación en y. |

### Method: translate_transform(dx, dy, order) {#translate_transform_dx_dy_order_13}


```
 translate_transform(dx, dy, order) 
```

Traslada la transformación geométrica local por las dimensiones especificadas en el orden indicado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| dx | float | El valor de la traslación en x. |
| dy | float | El valor de la traslación en y. |
| order | [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | El orden (anteponer o agregar) en el que se aplica la traslación. |

## **Examples**
### This example shows the creation and usage Pen objects. The example creates a new Image and draw rectangles on the Image surface. {#example_14}
``` python

from aspose.imaging import Image, Graphics, Color, Pen, Rectangle, Point, Size
from aspose.imaging.brushes import HatchBrush
from aspose.imaging.imageoptions import BmpOptions
from aspose.imaging.sources import FileCreateSource

# Crea una instancia de BmpOptions y establece sus diversas propiedades
bmpOptions = BmpOptions()
bmpOptions.bits_per_pixel = 24
# Cree una instancia de FileCreateSource y asígnela como Source para la instancia de BmpOptions
# El segundo parámetro Boolean determina si el archivo a crear es IsTemporal o no
bmpOptions.source = FileCreateSource(r"C:\temp\sample.bmp", False)
# Crea una instancia de Image en la ruta especificada
with Image.create(bmpOptions, 500, 500) as image:
	# Crea una instancia de Graphics e inicialízala con un objeto Image
	graphics = Graphics(image)
	# Limpia la superficie de Graphics con color blanco
	graphics.clear(Color.white)
	#Crea una instancia de Pen con color rojo y ancho 5
	pen = Pen(Color.red, 5.0);
	# Crea una instancia de HatchBrush y establece sus propiedades
	brush = HatchBrush()
	brush.background_color = Color.wheat;
	brush.foreground_color = Color.red;
	# Crea una instancia de Pen
	# inicialícelo con el objeto HatchBrush y el ancho
	brusedpen = Pen(brush, 5.0)
	# Dibuje rectángulos especificando el objeto Pen
	graphics.draw_rectangles(pen, [
		Rectangle(Point(210, 210), Size(100, 100)),
		Rectangle(Point(110, 110), Size(100, 100)),
		Rectangle(Point(310, 310), Size(100, 100)) ])

	# Dibuje rectángulos especificando el objeto Pen
	graphics.draw_rectangles(brusedpen, [
		Rectangle(Point(310, 110), Size(100, 100)),
		Rectangle(Point(110, 310), Size(100, 100)) ])

	# guarde todos los cambios.
	image.save()


```

