---
title: "فئة TextShape"
type: docs
weight: 90
url: /ar/python-net/aspose.imaging.shapes/textshape/
---

**Summary:** Represents a text shape.

**Module:** [aspose.imaging.shapes](/imaging/python-net/aspose.imaging.shapes/)

**Full Name:** aspose.imaging.shapes.TextShape

**Inheritance:** RectangleProjectedShape

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [TextShape()](#TextShape__1) | ينشئ مثيلاً جديدًا من الفئة [TextShape](/imaging/python-net/aspose.imaging.shapes/textshape/). |
| [TextShape(text, rectangle, font, string_format)](#TextShape_text_rectangle_font_string_format_2) | ينشئ مثيلاً جديدًا من الفئة [TextShape](/imaging/python-net/aspose.imaging.shapes/textshape/). |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r | يحصل على حدود الكائن. |
| center | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | يحصل على مركز الشكل. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | r/w | يحصل أو يعيّن الخط المستخدم لرسم النص. |
| has_segments | bool | r | يحصل على قيمة تشير إلى ما إذا كان الشكل يحتوي على مقاطع. |
| left_bottom | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | يحصل على نقطة المستطيل اليسرى السفلية. |
| left_top | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | يحصل على نقطة المستطيل اليسرى العليا. |
| rectangle_height | float | r | يحصل على ارتفاع المستطيل. |
| rectangle_width | float | r | يحصل على عرض المستطيل. |
| right_bottom | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | يحصل على نقطة المستطيل اليمنى السفلية. |
| right_top | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r | يحصل على نقطة المستطيل اليمنى العليا. |
| segments | [ShapeSegment[]](/imaging/python-net/aspose.imaging/shapesegment/) | r | يحصل على مقاطع الشكل. |
| text | string | r/w | يحصل أو يعيّن النص المرسوم. |
| text_format | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | r/w | يحصل أو يعيّن تنسيق النص. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [get_bounds(matrix)](#get_bounds_matrix_1) | يحصل على حدود الكائن. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_2) | يحصل على حدود الكائن. |
| [transform(transform)](#transform_transform_3) | يطبق التحويل المحدد على الشكل. |


### Constructor: TextShape() {#TextShape__1}


```
 TextShape() 
```

ينشئ مثيلاً جديدًا من الفئة [TextShape](/imaging/python-net/aspose.imaging.shapes/textshape/).

### Constructor: TextShape(text, rectangle, font, string_format) {#TextShape_text_rectangle_font_string_format_2}


```
 TextShape(text, rectangle, font, string_format) 
```

ينشئ مثيلاً جديدًا من الفئة [TextShape](/imaging/python-net/aspose.imaging.shapes/textshape/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| text | string | النص المراد رسمه. |
| rectangle | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | مستطيل النص. |
| font | [Font](/imaging/python-net/aspose.imaging/font/) | الخط المراد استخدامه. |
| string_format | [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | تنسيق السلسلة. |

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

