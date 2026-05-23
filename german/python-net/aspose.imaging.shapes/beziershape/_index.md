---
title: "BezierShape Klasse"
type: docs
weight: 20
url: /de/python-net/aspose.imaging.shapes/beziershape/
---

**Summary:** Represents a bezier spline.

**Module:** [aspose.imaging.shapes](/imaging/python-net/aspose.imaging.shapes/)

**Full Name:** aspose.imaging.shapes.BezierShape

**Inheritance:** IOrderedShape, PolygonShape

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [BezierShape()](#BezierShape__1) | Initialisiert eine neue Instanz der [BezierShape](/imaging/python-net/aspose.imaging.shapes/beziershape/) Klasse. |
| [BezierShape(points)](#BezierShape_points_2) | Initialisiert eine neue Instanz der [BezierShape](/imaging/python-net/aspose.imaging.shapes/beziershape/) Klasse. |
| [BezierShape(points, is_closed)](#BezierShape_points_is_closed_3) | Initialisiert eine neue Instanz der [BezierShape](/imaging/python-net/aspose.imaging.shapes/beziershape/) Klasse. |
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
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [get_bounds(matrix)](#get_bounds_matrix_1) | Liest die Begrenzungen des Objekts. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_2) | Liest die Begrenzungen des Objekts. |
| reverse() | Kehrt die Reihenfolge der Punkte für diese Form um. |
| [transform(transform)](#transform_transform_3) | Wendet die angegebene Transformation auf die Form an. |


### Constructor: BezierShape() {#BezierShape__1}


```
 BezierShape() 
```

Initialisiert eine neue Instanz der [BezierShape](/imaging/python-net/aspose.imaging.shapes/beziershape/) Klasse.

### Constructor: BezierShape(points) {#BezierShape_points_2}


```
 BezierShape(points) 
```

Initialisiert eine neue Instanz der [BezierShape](/imaging/python-net/aspose.imaging.shapes/beziershape/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Das Punkte-Array. |

### Constructor: BezierShape(points, is_closed) {#BezierShape_points_is_closed_3}


```
 BezierShape(points, is_closed) 
```

Initialisiert eine neue Instanz der [BezierShape](/imaging/python-net/aspose.imaging.shapes/beziershape/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Das Punkte-Array. |
| is_closed | bool | Wenn auf <c>true</c> gesetzt, ist die Bezier‑Spline geschlossen. |

### Method: get_bounds(matrix) {#get_bounds_matrix_1}


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


### Method: get_bounds(matrix, pen) {#get_bounds_matrix_pen_2}


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


### Method: transform(transform) {#transform_transform_3}


```
 transform(transform) 
```

Wendet die angegebene Transformation auf die Form an.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| transform | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Die anzuwendende Transformation. |

