---
title: "Clase RectangleProjectedShape"
type: docs
weight: 70
url: /es/python-net/aspose.imaging.shapes/rectangleprojectedshape/
---

**Summary:** Represents a shape which is projected over rectangle turned to a particular orientation.<br/>            Specified by four points which can be rotated in space maintaining the same edges length and 90 degrees between adjacent edges.

**Module:** [aspose.imaging.shapes](/imaging/python-net/aspose.imaging.shapes/)

**Full Name:** aspose.imaging.shapes.RectangleProjectedShape

**Inheritance:** Shape

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
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [get_bounds(matrix)](#get_bounds_matrix_1) | Obtiene los límites del objeto. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_2) | Obtiene los límites del objeto. |
| [transform(transform)](#transform_transform_3) | Aplica la transformación especificada a la forma. |


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

