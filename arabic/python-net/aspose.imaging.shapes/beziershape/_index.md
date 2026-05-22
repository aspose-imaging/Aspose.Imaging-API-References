---
title: "فئة BezierShape"
type: docs
weight: 20
url: /ar/python-net/aspose.imaging.shapes/beziershape/
---

**Summary:** Represents a bezier spline.

**Module:** [aspose.imaging.shapes](/imaging/python-net/aspose.imaging.shapes/)

**Full Name:** aspose.imaging.shapes.BezierShape

**Inheritance:** IOrderedShape, PolygonShape

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [BezierShape()](#BezierShape__1) | ينشئ مثيلًا جديدًا من الفئة [BezierShape](/imaging/python-net/aspose.imaging.shapes/beziershape/). |
| [BezierShape(points)](#BezierShape_points_2) | ينشئ مثيلًا جديدًا من الفئة [BezierShape](/imaging/python-net/aspose.imaging.shapes/beziershape/). |
| [BezierShape(points, is_closed)](#BezierShape_points_is_closed_3) | ينشئ مثيلًا جديدًا من الفئة [BezierShape](/imaging/python-net/aspose.imaging.shapes/beziershape/). |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r | يحصل على حدود الكائن. |
| center | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | يحصل على مركز الشكل. |
| end_point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | يحصل على نقطة النهاية للشكل. |
| has_segments | bool | r | يحصل على قيمة تشير إلى ما إذا كان الشكل يحتوي على مقاطع. |
| is_closed | bool | r/w | يحصل أو يعيّن قيمة تشير إلى ما إذا كان الشكل مغلقًا. |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | r/w | يحصل أو يعيّن نقاط المنحنى. |
| segments | [ShapeSegment[]](/imaging/python-net/aspose.imaging/shapesegment/) | r | يحصل على مقاطع الشكل. |
| start_point | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | يحصل على نقطة بداية الشكل. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [get_bounds(matrix)](#get_bounds_matrix_1) | يحصل على حدود الكائن. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_2) | يحصل على حدود الكائن. |
| reverse() | يعكس ترتيب النقاط لهذا الشكل. |
| [transform(transform)](#transform_transform_3) | يطبق التحويل المحدد على الشكل. |


### Constructor: BezierShape() {#BezierShape__1}


```
 BezierShape() 
```

ينشئ مثيلًا جديدًا من الفئة [BezierShape](/imaging/python-net/aspose.imaging.shapes/beziershape/).

### Constructor: BezierShape(points) {#BezierShape_points_2}


```
 BezierShape(points) 
```

ينشئ مثيلًا جديدًا من الفئة [BezierShape](/imaging/python-net/aspose.imaging.shapes/beziershape/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | مصفوفة النقاط. |

### Constructor: BezierShape(points, is_closed) {#BezierShape_points_is_closed_3}


```
 BezierShape(points, is_closed) 
```

ينشئ مثيلًا جديدًا من الفئة [BezierShape](/imaging/python-net/aspose.imaging.shapes/beziershape/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | مصفوفة النقاط. |
| is_closed | bool | إذا تم تعيينه إلى <c>true</c> يصبح منحنى بيزيير مغلقًا. |

### Method: get_bounds(matrix) {#get_bounds_matrix_1}


```
 get_bounds(matrix) 
```

يحصل على حدود الكائن.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | المصفوفة التي سيتم تطبيقها قبل حساب الحدود. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | حدود الكائن المقدرة. |


### Method: get_bounds(matrix, pen) {#get_bounds_matrix_pen_2}


```
 get_bounds(matrix, pen) 
```

يحصل على حدود الكائن.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | المصفوفة التي سيتم تطبيقها قبل حساب الحدود. |
| pen | [Pen](/imaging/python-net/aspose.imaging/pen/) | القلم المستخدم للكائن. يمكن أن يؤثر ذلك على حجم حدود الكائن. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | حدود الكائن المقدرة. |


### Method: transform(transform) {#transform_transform_3}


```
 transform(transform) 
```

يطبق التحويل المحدد على الشكل.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| transform | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | التحويل المراد تطبيقه. |

