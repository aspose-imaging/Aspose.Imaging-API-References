---
title: "Clase Shape"
type: docs
weight: 7250
url: /es/python-net/aspose.imaging/shape/
---

**Summary:** The shape. A continuous set of points connected using a specific rule.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.Shape

**Inheritance:** ObjectWithBounds

## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r | Obtiene los límites del objeto. |
| center | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Obtiene el centro de la forma. |
| has_segments | bool | r | Obtiene un valor que indica si la forma tiene segmentos. |
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

