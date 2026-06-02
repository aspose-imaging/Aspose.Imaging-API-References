---
title: "فئة CurveShape"
type: docs
weight: 30
url: /ar/python-net/aspose.imaging.shapes/curveshape/
---

**Summary:** Represents a curved spline shape.

**Module:** [aspose.imaging.shapes](/imaging/python-net/aspose.imaging.shapes/)

**Full Name:** aspose.imaging.shapes.CurveShape

**Inheritance:** IOrderedShape, PolygonShape

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [CurveShape()](#CurveShape__1) | ينشئ مثيلاً جديدًا من الفئة [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/). |
| [CurveShape(points)](#CurveShape_points_2) | ينشئ مثيلاً جديدًا من الفئة [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/). يتم استخدام الشد الافتراضي بقيمة 0.5. |
| [CurveShape(points, is_closed)](#CurveShape_points_is_closed_3) | ينشئ مثيلاً جديدًا من الفئة [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/). يتم استخدام الشد الافتراضي بقيمة 0.5. |
| [CurveShape(points, tension)](#CurveShape_points_tension_4) | ينشئ مثيلاً جديدًا من الفئة [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/). |
| [CurveShape(points, tension, is_closed)](#CurveShape_points_tension_is_closed_5) | ينشئ مثيلاً جديدًا من الفئة [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/). |
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
| التوتر | float | r/w | يحصل أو يعيّن شد المنحنى. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [create_with_point_fs_closed(points, is_closed)](#create_with_point_fs_closed_points_is_closed_1) | ينشئ مثيلاً جديدًا من الفئة [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/). يتم استخدام الشد الافتراضي بقيمة 0.5. |
| [create_with_point_fs_tension(points, tension)](#create_with_point_fs_tension_points_tension_2) | ينشئ مثيلاً جديدًا من الفئة [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/). |
| [get_bounds(matrix)](#get_bounds_matrix_3) | يحصل على حدود الكائن. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_4) | يحصل على حدود الكائن. |
| reverse() | يعكس ترتيب النقاط لهذا الشكل. |
| [transform(transform)](#transform_transform_5) | يطبق التحويل المحدد على الشكل. |


### Constructor: CurveShape() {#CurveShape__1}


```
 CurveShape() 
```

ينشئ مثيلاً جديدًا من الفئة [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/).

### Constructor: CurveShape(points) {#CurveShape_points_2}


```
 CurveShape(points) 
```

ينشئ مثيلاً جديدًا من الفئة [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/). يتم استخدام الشد الافتراضي بقيمة 0.5.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | مصفوفة النقاط. |

### Constructor: CurveShape(points, is_closed) {#CurveShape_points_is_closed_3}


```
 CurveShape(points, is_closed) 
```

ينشئ مثيلاً جديدًا من الفئة [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/). يتم استخدام الشد الافتراضي بقيمة 0.5.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | مصفوفة النقاط. |
| is_closed | bool | إذا تم تعيينه إلى <c>true</c> فإن المنحنى مغلق. |

### Constructor: CurveShape(points, tension) {#CurveShape_points_tension_4}


```
 CurveShape(points, tension) 
```

ينشئ مثيلاً جديدًا من الفئة [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | مصفوفة النقاط. |
| التوتر | float | شد المنحنى. |

### Constructor: CurveShape(points, tension, is_closed) {#CurveShape_points_tension_is_closed_5}


```
 CurveShape(points, tension, is_closed) 
```

ينشئ مثيلاً جديدًا من الفئة [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | مصفوفة النقاط. |
| التوتر | float | شد المنحنى. |
| is_closed | bool | إذا تم تعيينه إلى <c>true</c> فإن المنحنى مغلق. |

### Method: create_with_point_fs_closed(points, is_closed)  [static] {#create_with_point_fs_closed_points_is_closed_1}


```
 create_with_point_fs_closed(points, is_closed) 
```

ينشئ مثيلاً جديدًا من الفئة [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/). يتم استخدام الشد الافتراضي بقيمة 0.5.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | مصفوفة النقاط. |
| is_closed | bool | إذا تم تعيينه إلى <c>true</c> فإن المنحنى مغلق. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/) |  |


### Method: create_with_point_fs_tension(points, tension)  [static] {#create_with_point_fs_tension_points_tension_2}


```
 create_with_point_fs_tension(points, tension) 
```

ينشئ مثيلاً جديدًا من الفئة [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| points | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | مصفوفة النقاط. |
| التوتر | float | شد المنحنى. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [CurveShape](/imaging/python-net/aspose.imaging.shapes/curveshape/) |  |


### Method: get_bounds(matrix) {#get_bounds_matrix_3}


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


### Method: get_bounds(matrix, pen) {#get_bounds_matrix_pen_4}


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


### Method: transform(transform) {#transform_transform_5}


```
 transform(transform) 
```

يطبق التحويل المحدد على الشكل.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| transform | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | التحويل المراد تطبيقه. |

