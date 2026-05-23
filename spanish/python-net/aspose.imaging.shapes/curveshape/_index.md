---
title: "Clase CurveShape"
type: docs
weight: 30
url: /es/python-net/aspose.imaging.shapes/curveshape/
---

**Summary:** Represents a curved spline shape.

**Module:** [aspose.imaging.shapes](/imaging/python-net/aspose.imaging.shapes/)

**Full Name:** aspose.imaging.shapes.CurveShape

**Inheritance:** IOrderedShape, PolygonShape

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [CurveShape()](#CurveShape__1) | Inicializa una nueva instancia de la clase [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/). |
| [CurveShape(points)](#CurveShape_points_2) | Inicializa una nueva instancia de la clase [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/). Se utiliza la tensión predeterminada de 0.5. |
| [CurveShape(points, is_closed)](#CurveShape_points_is_closed_3) | Inicializa una nueva instancia de la clase [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/). Se utiliza la tensión predeterminada de 0.5. |
| [CurveShape(points, tension)](#CurveShape_points_tension_4) | Inicializa una nueva instancia de la clase [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/). |
| [CurveShape(points, tension, is_closed)](#CurveShape_points_tension_is_closed_5) | Inicializa una nueva instancia de la clase [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/). |
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
| tensión | float | r/w | Obtiene o establece la tensión de la curva. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [create_with_point_fs_closed(points, is_closed)](#create_with_point_fs_closed_points_is_closed_1) | Inicializa una nueva instancia de la clase [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/). Se utiliza la tensión predeterminada de 0.5. |
| [create_with_point_fs_tension(points, tension)](#create_with_point_fs_tension_points_tension_2) | Inicializa una nueva instancia de la clase [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/). |
| [get_bounds(matrix)](#get_bounds_matrix_3) | Obtiene los límites del objeto. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_4) | Obtiene los límites del objeto. |
| reverse() | Invierte el orden de los puntos de esta forma. |
| [transform(transform)](#transform_transform_5) | Aplica la transformación especificada a la forma. |


### Constructor: CurveShape() {#CurveShape__1}


```
 CurveShape() 
```

Inicializa una nueva instancia de la clase [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/).

### Constructor: CurveShape(points) {#CurveShape_points_2}


```
 CurveShape(points) 
```

Inicializa una nueva instancia de la clase [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/). Se utiliza la tensión predeterminada de 0.5.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | La matriz de puntos. |

### Constructor: CurveShape(points, is_closed) {#CurveShape_points_is_closed_3}


```
 CurveShape(points, is_closed) 
```

Inicializa una nueva instancia de la clase [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/). Se utiliza la tensión predeterminada de 0.5.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | La matriz de puntos. |
| is_closed | bool | Si se establece en <c>true</c> la curva está cerrada. |

### Constructor: CurveShape(points, tension) {#CurveShape_points_tension_4}


```
 CurveShape(points, tension) 
```

Inicializa una nueva instancia de la clase [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | La matriz de puntos. |
| tensión | float | La tensión de la curva. |

### Constructor: CurveShape(points, tension, is_closed) {#CurveShape_points_tension_is_closed_5}


```
 CurveShape(points, tension, is_closed) 
```

Inicializa una nueva instancia de la clase [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | La matriz de puntos. |
| tensión | float | La tensión de la curva. |
| is_closed | bool | Si se establece en <c>true</c> la curva está cerrada. |

### Method: create_with_point_fs_closed(points, is_closed)  [static] {#create_with_point_fs_closed_points_is_closed_1}


```
 create_with_point_fs_closed(points, is_closed) 
```

Inicializa una nueva instancia de la clase [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/). Se utiliza la tensión predeterminada de 0.5.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | La matriz de puntos. |
| is_closed | bool | Si se establece en <c>true</c> la curva está cerrada. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/) |  |


### Method: create_with_point_fs_tension(points, tension)  [static] {#create_with_point_fs_tension_points_tension_2}


```
 create_with_point_fs_tension(points, tension) 
```

Inicializa una nueva instancia de la clase [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | La matriz de puntos. |
| tensión | float | La tensión de la curva. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/) |  |


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


### Method: transform(transform) {#transform_transform_5}


```
 transform(transform) 
```

Aplica la transformación especificada a la forma.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| transform | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | La transformación a aplicar. |

