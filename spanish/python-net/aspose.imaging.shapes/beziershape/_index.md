---
title: "Clase BezierShape"
type: docs
weight: 20
url: /es/python-net/aspose.imaging.shapes/beziershape/
---

**Summary:** Represents a bezier spline.

**Module:** [aspose.imaging.shapes](/imaging/python-net/aspose.imaging.shapes/)

**Full Name:** aspose.imaging.shapes.BezierShape

**Inheritance:** IOrderedShape, PolygonShape

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [BezierShape()](#BezierShape__1) | Inicializa una nueva instancia de la clase [BezierShape](/imaging/python-net/aspose.imaging.shapes/beziershape/). |
| [BezierShape(points)](#BezierShape_points_2) | Inicializa una nueva instancia de la clase [BezierShape](/imaging/python-net/aspose.imaging.shapes/beziershape/). |
| [BezierShape(points, is_closed)](#BezierShape_points_is_closed_3) | Inicializa una nueva instancia de la clase [BezierShape](/imaging/python-net/aspose.imaging.shapes/beziershape/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r | Obtiene los límites del objeto. |
| center | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Obtiene el centro de la forma. |
| end_point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Obtiene el punto final de la forma. |
| has_segments | bool | r | Obtiene un valor que indica si la forma tiene segmentos. |
| is_closed | bool | r/w | Obtiene o establece un valor que indica si la forma está cerrada. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | r/w | Obtiene o establece los puntos de la curva. |
| segments | [ShapeSegment[]](/imaging/python-net/aspose.imaging/shapesegment/) | r | Obtiene los segmentos de la forma. |
| start_point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Obtiene el punto inicial de la forma. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [get_bounds(matrix)](#get_bounds_matrix_1) | Obtiene los límites del objeto. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_2) | Obtiene los límites del objeto. |
| reverse() | Invierte el orden de los puntos de esta forma. |
| [transform(transform)](#transform_transform_3) | Aplica la transformación especificada a la forma. |


### Constructor: BezierShape() {#BezierShape__1}


```
 BezierShape() 
```

Inicializa una nueva instancia de la clase [BezierShape](/imaging/python-net/aspose.imaging.shapes/beziershape/).

### Constructor: BezierShape(points) {#BezierShape_points_2}


```
 BezierShape(points) 
```

Inicializa una nueva instancia de la clase [BezierShape](/imaging/python-net/aspose.imaging.shapes/beziershape/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | La matriz de puntos. |

### Constructor: BezierShape(points, is_closed) {#BezierShape_points_is_closed_3}


```
 BezierShape(points, is_closed) 
```

Inicializa una nueva instancia de la clase [BezierShape](/imaging/python-net/aspose.imaging.shapes/beziershape/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | La matriz de puntos. |
| is_closed | bool | Si se establece en <c>true</c> la spline bezier está cerrada. |

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

