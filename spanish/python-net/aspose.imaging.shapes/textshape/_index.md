---
title: "Clase TextShape"
type: docs
weight: 90
url: /es/python-net/aspose.imaging.shapes/textshape/
---

**Summary:** Represents a text shape.

**Module:** [aspose.imaging.shapes](/imaging/python-net/aspose.imaging.shapes/)

**Full Name:** aspose.imaging.shapes.TextShape

**Inheritance:** RectangleProjectedShape

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [TextShape()](#TextShape__1) | Inicializa una nueva instancia de la clase [TextShape](/imaging/python-net/aspose.imaging.shapes/textshape/). |
| [TextShape(text, rectangle, font, string_format)](#TextShape_text_rectangle_font_string_format_2) | Inicializa una nueva instancia de la clase [TextShape](/imaging/python-net/aspose.imaging.shapes/textshape/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r | Obtiene los límites del objeto. |
| center | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Obtiene el centro de la forma. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | r/w | Obtiene o establece la fuente utilizada para dibujar el texto. |
| has_segments | bool | r | Obtiene un valor que indica si la forma tiene segmentos. |
| left_bottom | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Obtiene el punto inferior izquierdo del rectángulo. |
| left_top | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Obtiene el punto superior izquierdo del rectángulo. |
| rectangle_height | float | r | Obtiene la altura del rectángulo. |
| rectangle_width | float | r | Obtiene el ancho del rectángulo. |
| right_bottom | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Obtiene el punto inferior derecho del rectángulo. |
| right_top | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Obtiene el punto superior derecho del rectángulo. |
| segments | [ShapeSegment[]](/imaging/python-net/aspose.imaging/shapesegment/) | r | Obtiene los segmentos de la forma. |
| text | string | r/w | Obtiene o establece el texto dibujado. |
| text_format | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | r/w | Obtiene o establece el formato del texto. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [get_bounds(matrix)](#get_bounds_matrix_1) | Obtiene los límites del objeto. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_2) | Obtiene los límites del objeto. |
| [transform(transform)](#transform_transform_3) | Aplica la transformación especificada a la forma. |


### Constructor: TextShape() {#TextShape__1}


```
 TextShape() 
```

Inicializa una nueva instancia de la clase [TextShape](/imaging/python-net/aspose.imaging.shapes/textshape/).

### Constructor: TextShape(text, rectangle, font, string_format) {#TextShape_text_rectangle_font_string_format_2}


```
 TextShape(text, rectangle, font, string_format) 
```

Inicializa una nueva instancia de la clase [TextShape](/imaging/python-net/aspose.imaging.shapes/textshape/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| text | string | El texto a dibujar. |
| rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | El rectángulo de texto. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | La fuente a usar. |
| string_format | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | El formato de cadena. |

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

