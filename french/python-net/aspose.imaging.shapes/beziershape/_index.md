---
title: "Classe BezierShape"
type: docs
weight: 20
url: /fr/python-net/aspose.imaging.shapes/beziershape/
---

**Summary:** Represents a bezier spline.

**Module:** [aspose.imaging.shapes](/imaging/python-net/aspose.imaging.shapes/)

**Full Name:** aspose.imaging.shapes.BezierShape

**Inheritance:** IOrderedShape, PolygonShape

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [BezierShape()](#BezierShape__1) | Initialise une nouvelle instance de la classe [BezierShape](/imaging/python-net/aspose.imaging.shapes/beziershape/). |
| [BezierShape(points)](#BezierShape_points_2) | Initialise une nouvelle instance de la classe [BezierShape](/imaging/python-net/aspose.imaging.shapes/beziershape/). |
| [BezierShape(points, is_closed)](#BezierShape_points_is_closed_3) | Initialise une nouvelle instance de la classe [BezierShape](/imaging/python-net/aspose.imaging.shapes/beziershape/). |
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
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_bounds(matrix)](#get_bounds_matrix_1) | Obtient les limites de l'objet. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_2) | Obtient les limites de l'objet. |
| reverse() | Inverse l'ordre des points pour cette forme. |
| [transform(transform)](#transform_transform_3) | Applique la transformation spécifiée à la forme. |


### Constructor: BezierShape() {#BezierShape__1}


```
 BezierShape() 
```

Initialise une nouvelle instance de la classe [BezierShape](/imaging/python-net/aspose.imaging.shapes/beziershape/).

### Constructor: BezierShape(points) {#BezierShape_points_2}


```
 BezierShape(points) 
```

Initialise une nouvelle instance de la classe [BezierShape](/imaging/python-net/aspose.imaging.shapes/beziershape/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Le tableau de points. |

### Constructor: BezierShape(points, is_closed) {#BezierShape_points_is_closed_3}


```
 BezierShape(points, is_closed) 
```

Initialise une nouvelle instance de la classe [BezierShape](/imaging/python-net/aspose.imaging.shapes/beziershape/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Le tableau de points. |
| is_closed | bool | Si réglé sur <c>true</c> la spline de Bézier est fermée. |

### Method: get_bounds(matrix) {#get_bounds_matrix_1}


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


### Method: get_bounds(matrix, pen) {#get_bounds_matrix_pen_2}


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


### Method: transform(transform) {#transform_transform_3}


```
 transform(transform) 
```

Applique la transformation spécifiée à la forme.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| transform | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | La transformation à appliquer. |

