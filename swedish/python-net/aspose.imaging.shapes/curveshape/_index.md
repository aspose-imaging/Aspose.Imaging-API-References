---
title: "CurveShape-klass"
type: docs
weight: 30
url: /sv/python-net/aspose.imaging.shapes/curveshape/
---

**Summary:** Represents a curved spline shape.

**Module:** [aspose.imaging.shapes](/imaging/python-net/aspose.imaging.shapes/)

**Full Name:** aspose.imaging.shapes.CurveShape

**Inheritance:** IOrderedShape, PolygonShape

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [CurveShape()](#CurveShape__1) | Initierar en ny instans av klassen [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/). |
| [CurveShape(points)](#CurveShape_points_2) | Initierar en ny instans av klassen [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/). Standardspänningen 0.5 används. |
| [CurveShape(points, is_closed)](#CurveShape_points_is_closed_3) | Initierar en ny instans av klassen [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/). Standardspänningen 0.5 används. |
| [CurveShape(points, tension)](#CurveShape_points_tension_4) | Initierar en ny instans av klassen [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/). |
| [CurveShape(points, tension, is_closed)](#CurveShape_points_tension_is_closed_5) | Initierar en ny instans av klassen [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/). |
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
| spänning | float | r/w | Hämtar eller anger kurvspänningen. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_with_point_fs_closed(points, is_closed)](#create_with_point_fs_closed_points_is_closed_1) | Initierar en ny instans av klassen [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/). Standardspänningen 0.5 används. |
| [create_with_point_fs_tension(points, tension)](#create_with_point_fs_tension_points_tension_2) | Initierar en ny instans av klassen [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/). |
| [get_bounds(matrix)](#get_bounds_matrix_3) | Hämtar objektets gränser. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_4) | Hämtar objektets gränser. |
| reverse() | Vänder på ordningen av punkter för denna form. |
| [transform(transform)](#transform_transform_5) | Tillämpar den angivna transformationen på formen. |


### Constructor: CurveShape() {#CurveShape__1}


```
 CurveShape() 
```

Initierar en ny instans av klassen [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/).

### Constructor: CurveShape(points) {#CurveShape_points_2}


```
 CurveShape(points) 
```

Initierar en ny instans av klassen [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/). Standardspänningen 0.5 används.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Punktarrayen. |

### Constructor: CurveShape(points, is_closed) {#CurveShape_points_is_closed_3}


```
 CurveShape(points, is_closed) 
```

Initierar en ny instans av klassen [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/). Standardspänningen 0.5 används.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Punktarrayen. |
| is_closed | bool | Om den är inställd på <c>true</c> är kurvan sluten. |

### Constructor: CurveShape(points, tension) {#CurveShape_points_tension_4}


```
 CurveShape(points, tension) 
```

Initierar en ny instans av klassen [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Punktarrayen. |
| spänning | float | Kurvspänningen. |

### Constructor: CurveShape(points, tension, is_closed) {#CurveShape_points_tension_is_closed_5}


```
 CurveShape(points, tension, is_closed) 
```

Initierar en ny instans av klassen [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Punktarrayen. |
| spänning | float | Kurvspänningen. |
| is_closed | bool | Om den är inställd på <c>true</c> är kurvan sluten. |

### Method: create_with_point_fs_closed(points, is_closed)  [static] {#create_with_point_fs_closed_points_is_closed_1}


```
 create_with_point_fs_closed(points, is_closed) 
```

Initierar en ny instans av klassen [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/). Standardspänningen 0.5 används.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Punktarrayen. |
| is_closed | bool | Om den är inställd på <c>true</c> är kurvan sluten. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/) |  |


### Method: create_with_point_fs_tension(points, tension)  [static] {#create_with_point_fs_tension_points_tension_2}


```
 create_with_point_fs_tension(points, tension) 
```

Initierar en ny instans av klassen [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | Punktarrayen. |
| spänning | float | Kurvspänningen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/) |  |


### Method: get_bounds(matrix) {#get_bounds_matrix_3}


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


### Method: get_bounds(matrix, pen) {#get_bounds_matrix_pen_4}


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


### Method: transform(transform) {#transform_transform_5}


```
 transform(transform) 
```

Tillämpar den angivna transformationen på formen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| transform | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Transformationen att tillämpa. |

