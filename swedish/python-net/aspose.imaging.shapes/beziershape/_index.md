---
title: "BezierShape-klass"
type: docs
weight: 20
url: /sv/python-net/aspose.imaging.shapes/beziershape/
---

**Summary:** Represents a bezier spline.

**Module:** [aspose.imaging.shapes](/imaging/python-net/aspose.imaging.shapes/)

**Full Name:** aspose.imaging.shapes.BezierShape

**Inheritance:** IOrderedShape, PolygonShape

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [BezierShape()](#BezierShape__1) | Initierar en ny instans av klassen [BezierShape](/imaging/python-net/aspose.imaging.shapes/beziershape/). |
| [BezierShape(points)](#BezierShape_points_2) | Initierar en ny instans av klassen [BezierShape](/imaging/python-net/aspose.imaging.shapes/beziershape/). |
| [BezierShape(points, is_closed)](#BezierShape_points_is_closed_3) | Initierar en ny instans av klassen [BezierShape](/imaging/python-net/aspose.imaging.shapes/beziershape/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r | Hämtar objektets gränser. |
| center | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Hämtar figurens centrum. |
| end_point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Hämtar den avslutande formpunkten. |
| has_segments | bool | r | Hämtar ett värde som indikerar om figuren har segment. |
| is_closed | bool | r/w | Hämtar eller anger ett värde som indikerar om formen är sluten. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | r/w | Hämtar eller anger kurvpunkterna. |
| segments | [ShapeSegment[]](/imaging/python-net/aspose.imaging/shapesegment/) | r | Hämtar figurens segment. |
| start_point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | Hämtar startpunkten för formen. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_bounds(matrix)](#get_bounds_matrix_1) | Hämtar objektets gränser. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_2) | Hämtar objektets gränser. |
| reverse() | Vänder på ordningen av punkter för denna form. |
| [transform(transform)](#transform_transform_3) | Tillämpar den angivna transformationen på formen. |


### Constructor: BezierShape() {#BezierShape__1}


```
 BezierShape() 
```

Initierar en ny instans av klassen [BezierShape](/imaging/python-net/aspose.imaging.shapes/beziershape/).

### Constructor: BezierShape(points) {#BezierShape_points_2}


```
 BezierShape(points) 
```

Initierar en ny instans av klassen [BezierShape](/imaging/python-net/aspose.imaging.shapes/beziershape/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Punktarrayen. |

### Constructor: BezierShape(points, is_closed) {#BezierShape_points_is_closed_3}


```
 BezierShape(points, is_closed) 
```

Initierar en ny instans av klassen [BezierShape](/imaging/python-net/aspose.imaging.shapes/beziershape/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Punktarrayen. |
| is_closed | bool | Om den är inställd på <c>true</c> är bezier-splinen sluten. |

### Method: get_bounds(matrix) {#get_bounds_matrix_1}


```
 get_bounds(matrix) 
```

Hämtar objektets gränser.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Matrisen att tillämpa innan gränserna beräknas. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Det uppskattade objektets gränser. |


### Method: get_bounds(matrix, pen) {#get_bounds_matrix_pen_2}


```
 get_bounds(matrix, pen) 
```

Hämtar objektets gränser.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Matrisen att tillämpa innan gränserna beräknas. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | Pennan att använda för objektet. Detta kan påverka objektets gränsstorlek. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Det uppskattade objektets gränser. |


### Method: transform(transform) {#transform_transform_3}


```
 transform(transform) 
```

Tillämpar den angivna transformationen på formen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| transform | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Transformationen att tillämpa. |

