---
title: "Classe CurveShape"
type: docs
weight: 30
url: /fr/python-net/aspose.imaging.shapes/curveshape/
---

**Summary:** Represents a curved spline shape.

**Module:** [aspose.imaging.shapes](/imaging/python-net/aspose.imaging.shapes/)

**Full Name:** aspose.imaging.shapes.CurveShape

**Inheritance:** IOrderedShape, PolygonShape

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [CurveShape()](#CurveShape__1) | Initialise une nouvelle instance de la classe [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/). |
| [CurveShape(points)](#CurveShape_points_2) | Initialise une nouvelle instance de la classe [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/). La tension par défaut de 0,5 est utilisée. |
| [CurveShape(points, is_closed)](#CurveShape_points_is_closed_3) | Initialise une nouvelle instance de la classe [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/). La tension par défaut de 0,5 est utilisée. |
| [CurveShape(points, tension)](#CurveShape_points_tension_4) | Initialise une nouvelle instance de la classe [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/). |
| [CurveShape(points, tension, is_closed)](#CurveShape_points_tension_is_closed_5) | Initialise une nouvelle instance de la classe [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r | Obtient les limites de l'objet. |
| center | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Obtient le centre de la forme. |
| end_point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Obtient le point final de la forme. |
| has_segments | bool | r | Obtient une valeur indiquant si la forme possède des segments. |
| is_closed | bool | r/w | Obtient ou définit une valeur indiquant si la forme est fermée. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | r/w | Obtient ou définit les points de la courbe. |
| segments | [ShapeSegment[]](/imaging/python-net/aspose.imaging/shapesegment/) | r | Obtient les segments de la forme. |
| start_point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Obtient le point de départ de la forme. |
| tension | float | r/w | Obtient ou définit la tension de la courbe. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_with_point_fs_closed(points, is_closed)](#create_with_point_fs_closed_points_is_closed_1) | Initialise une nouvelle instance de la classe [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/). La tension par défaut de 0,5 est utilisée. |
| [create_with_point_fs_tension(points, tension)](#create_with_point_fs_tension_points_tension_2) | Initialise une nouvelle instance de la classe [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/). |
| [get_bounds(matrix)](#get_bounds_matrix_3) | Obtient les limites de l'objet. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_4) | Obtient les limites de l'objet. |
| reverse() | Inverse l'ordre des points pour cette forme. |
| [transform(transform)](#transform_transform_5) | Applique la transformation spécifiée à la forme. |


### Constructor: CurveShape() {#CurveShape__1}


```
 CurveShape() 
```

Initialise une nouvelle instance de la classe [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/).

### Constructor: CurveShape(points) {#CurveShape_points_2}


```
 CurveShape(points) 
```

Initialise une nouvelle instance de la classe [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/). La tension par défaut de 0,5 est utilisée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Le tableau de points. |

### Constructor: CurveShape(points, is_closed) {#CurveShape_points_is_closed_3}


```
 CurveShape(points, is_closed) 
```

Initialise une nouvelle instance de la classe [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/). La tension par défaut de 0,5 est utilisée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Le tableau de points. |
| is_closed | bool | si défini sur <c>true</c> la courbe est fermée. |

### Constructor: CurveShape(points, tension) {#CurveShape_points_tension_4}


```
 CurveShape(points, tension) 
```

Initialise une nouvelle instance de la classe [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Le tableau de points. |
| tension | float | La tension de la courbe. |

### Constructor: CurveShape(points, tension, is_closed) {#CurveShape_points_tension_is_closed_5}


```
 CurveShape(points, tension, is_closed) 
```

Initialise une nouvelle instance de la classe [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Le tableau de points. |
| tension | float | La tension de la courbe. |
| is_closed | bool | si défini sur <c>true</c> la courbe est fermée. |

### Method: create_with_point_fs_closed(points, is_closed)  [static] {#create_with_point_fs_closed_points_is_closed_1}


```
 create_with_point_fs_closed(points, is_closed) 
```

Initialise une nouvelle instance de la classe [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/). La tension par défaut de 0,5 est utilisée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Le tableau de points. |
| is_closed | bool | si défini sur <c>true</c> la courbe est fermée. |

**Returns**

| Type | Description |
| :- | :- |
| [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/) |  |


### Method: create_with_point_fs_tension(points, tension)  [static] {#create_with_point_fs_tension_points_tension_2}


```
 create_with_point_fs_tension(points, tension) 
```

Initialise une nouvelle instance de la classe [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Le tableau de points. |
| tension | float | La tension de la courbe. |

**Returns**

| Type | Description |
| :- | :- |
| [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/) |  |


### Method: get_bounds(matrix) {#get_bounds_matrix_3}


```
 get_bounds(matrix) 
```

Obtient les limites de l'objet.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | La matrice à appliquer avant que les limites ne soient calculées. |

**Returns**

| Type | Description |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Les limites estimées de l'objet. |


### Method: get_bounds(matrix, pen) {#get_bounds_matrix_pen_4}


```
 get_bounds(matrix, pen) 
```

Obtient les limites de l'objet.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | La matrice à appliquer avant que les limites ne soient calculées. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Le stylo à utiliser pour l'objet. Cela peut influencer la taille des limites de l'objet. |

**Returns**

| Type | Description |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Les limites estimées de l'objet. |


### Method: transform(transform) {#transform_transform_5}


```
 transform(transform) 
```

Applique la transformation spécifiée à la forme.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| transform | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | La transformation à appliquer. |

