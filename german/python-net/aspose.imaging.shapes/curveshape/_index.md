---
title: "CurveShape Klasse"
type: docs
weight: 30
url: /de/python-net/aspose.imaging.shapes/curveshape/
---

**Summary:** Represents a curved spline shape.

**Module:** [aspose.imaging.shapes](/imaging/python-net/aspose.imaging.shapes/)

**Full Name:** aspose.imaging.shapes.CurveShape

**Inheritance:** IOrderedShape, PolygonShape

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [CurveShape()](#CurveShape__1) | Initialisiert eine neue Instanz der Klasse [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/). |
| [CurveShape(points)](#CurveShape_points_2) | Initialisiert eine neue Instanz der Klasse [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/). Die Standardspannung von 0,5 wird verwendet. |
| [CurveShape(points, is_closed)](#CurveShape_points_is_closed_3) | Initialisiert eine neue Instanz der Klasse [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/). Die Standardspannung von 0,5 wird verwendet. |
| [CurveShape(points, tension)](#CurveShape_points_tension_4) | Initialisiert eine neue Instanz der Klasse [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/). |
| [CurveShape(points, tension, is_closed)](#CurveShape_points_tension_is_closed_5) | Initialisiert eine neue Instanz der Klasse [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/). |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r | Liest die Begrenzungen des Objekts. |
| center | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Gibt das Zentrum der Form zurück. |
| end_point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Gibt den Endpunkt der Form zurück. |
| has_segments | bool | r | Gibt einen Wert zurück, der angibt, ob die Form Segmente hat. |
| is_closed | bool | r/w | Liest oder setzt einen Wert, der angibt, ob die Form geschlossen ist. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | r/w | Liest oder setzt die Kurvenpunkte. |
| segments | [ShapeSegment[]](/imaging/python-net/aspose.imaging/shapesegment/) | r | Gibt die Formsegmente zurück. |
| start_point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Gibt den Startpunkt der Form zurück. |
| Spannung | float | r/w | Liest oder setzt die Kurvenspannung. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [create_with_point_fs_closed(points, is_closed)](#create_with_point_fs_closed_points_is_closed_1) | Initialisiert eine neue Instanz der Klasse [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/). Die Standardspannung von 0,5 wird verwendet. |
| [create_with_point_fs_tension(points, tension)](#create_with_point_fs_tension_points_tension_2) | Initialisiert eine neue Instanz der Klasse [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/). |
| [get_bounds(matrix)](#get_bounds_matrix_3) | Liest die Begrenzungen des Objekts. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_4) | Liest die Begrenzungen des Objekts. |
| reverse() | Kehrt die Reihenfolge der Punkte für diese Form um. |
| [transform(transform)](#transform_transform_5) | Wendet die angegebene Transformation auf die Form an. |


### Constructor: CurveShape() {#CurveShape__1}


```
 CurveShape() 
```

Initialisiert eine neue Instanz der Klasse [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/).

### Constructor: CurveShape(points) {#CurveShape_points_2}


```
 CurveShape(points) 
```

Initialisiert eine neue Instanz der Klasse [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/). Die Standardspannung von 0,5 wird verwendet.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Das Punkte-Array. |

### Constructor: CurveShape(points, is_closed) {#CurveShape_points_is_closed_3}


```
 CurveShape(points, is_closed) 
```

Initialisiert eine neue Instanz der Klasse [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/). Die Standardspannung von 0,5 wird verwendet.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Das Punkte-Array. |
| is_closed | bool | Wenn auf <c>true</c> gesetzt, ist die Kurve geschlossen. |

### Constructor: CurveShape(points, tension) {#CurveShape_points_tension_4}


```
 CurveShape(points, tension) 
```

Initialisiert eine neue Instanz der Klasse [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Das Punkte-Array. |
| Spannung | float | Die Kurvenspannung. |

### Constructor: CurveShape(points, tension, is_closed) {#CurveShape_points_tension_is_closed_5}


```
 CurveShape(points, tension, is_closed) 
```

Initialisiert eine neue Instanz der Klasse [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Das Punkte-Array. |
| Spannung | float | Die Kurvenspannung. |
| is_closed | bool | Wenn auf <c>true</c> gesetzt, ist die Kurve geschlossen. |

### Method: create_with_point_fs_closed(points, is_closed)  [static] {#create_with_point_fs_closed_points_is_closed_1}


```
 create_with_point_fs_closed(points, is_closed) 
```

Initialisiert eine neue Instanz der Klasse [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/). Die Standardspannung von 0,5 wird verwendet.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Das Punkte-Array. |
| is_closed | bool | Wenn auf <c>true</c> gesetzt, ist die Kurve geschlossen. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/) |  |


### Method: create_with_point_fs_tension(points, tension)  [static] {#create_with_point_fs_tension_points_tension_2}


```
 create_with_point_fs_tension(points, tension) 
```

Initialisiert eine neue Instanz der Klasse [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Das Punkte-Array. |
| Spannung | float | Die Kurvenspannung. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/) |  |


### Method: get_bounds(matrix) {#get_bounds_matrix_3}


```
 get_bounds(matrix) 
```

Liest die Begrenzungen des Objekts.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Die Matrix, die angewendet wird, bevor die Begrenzungen berechnet werden. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Die geschätzten Begrenzungen des Objekts. |


### Method: get_bounds(matrix, pen) {#get_bounds_matrix_pen_4}


```
 get_bounds(matrix, pen) 
```

Liest die Begrenzungen des Objekts.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Die Matrix, die angewendet wird, bevor die Begrenzungen berechnet werden. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Der Stift, der für das Objekt verwendet wird. Dies kann die Größe der Begrenzungen des Objekts beeinflussen. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Die geschätzten Begrenzungen des Objekts. |


### Method: transform(transform) {#transform_transform_5}


```
 transform(transform) 
```

Wendet die angegebene Transformation auf die Form an.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| transform | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Die anzuwendende Transformation. |

