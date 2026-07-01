---
title: "TextShape"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يمثل شكل نص."
type: docs
weight: 18
url: /ar/java/com.aspose.imaging.shapes/textshape/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.ObjectWithBounds](../../com.aspose.imaging/objectwithbounds), [com.aspose.imaging.Shape](../../com.aspose.imaging/shape), [com.aspose.imaging.shapes.RectangleProjectedShape](../../com.aspose.imaging.shapes/rectangleprojectedshape)
```
public final class TextShape extends RectangleProjectedShape
```

يمثل شكل نص.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [TextShape()](#TextShape--) | يقوم بإنشاء نسخة جديدة من الفئة `TextShape` class. |
| [TextShape(String text, RectangleF rectangle, Font font, StringFormat stringFormat)](#TextShape-java.lang.String-com.aspose.imaging.RectangleF-com.aspose.imaging.Font-com.aspose.imaging.StringFormat-) | يقوم بإنشاء نسخة جديدة من الفئة `TextShape` class. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getText()](#getText--) | يحصل أو يعيّن النص المرسوم. |
| [setText(String value)](#setText-java.lang.String-) | يحصل أو يعيّن النص المرسوم. |
| [getFont()](#getFont--) | يحصل أو يعيّن الخط المستخدم لرسم النص. |
| [setFont(Font value)](#setFont-com.aspose.imaging.Font-) | يحصل أو يعيّن الخط المستخدم لرسم النص. |
| [getTextFormat()](#getTextFormat--) | يحصل أو يعيّن تنسيق النص. |
| [setTextFormat(StringFormat value)](#setTextFormat-com.aspose.imaging.StringFormat-) | يحصل أو يعيّن تنسيق النص. |
| [getCenter()](#getCenter--) | يحصل على مركز الشكل. |
| [getBounds()](#getBounds--) | يحصل على حدود الكائن. |
| [getSegments()](#getSegments--) | يحصل على مقاطع الشكل. |
| [hasSegments()](#hasSegments--) | يحصل على قيمة تشير إلى ما إذا كان الشكل يحتوي على مقاطع. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.imaging.Matrix-) | يحصل على حدود الكائن. |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.imaging.Matrix-com.aspose.imaging.Pen-) | يحصل على حدود الكائن. |
| [transform(Matrix transform)](#transform-com.aspose.imaging.Matrix-) | يطبق التحويل المحدد على الشكل. |
| [equals(Object o)](#equals-java.lang.Object-) | تحقق مما إذا كانت الكائنات متساوية. |
| [hashCode()](#hashCode--) | احصل على رمز التجزئة للكائن الحالي. |
### TextShape() {#TextShape--}
```
public TextShape()
```


يقوم بإنشاء نسخة جديدة من الفئة `TextShape` class.

### TextShape(String text, RectangleF rectangle, Font font, StringFormat stringFormat) {#TextShape-java.lang.String-com.aspose.imaging.RectangleF-com.aspose.imaging.Font-com.aspose.imaging.StringFormat-}
```
public TextShape(String text, RectangleF rectangle, Font font, StringFormat stringFormat)
```


يقوم بإنشاء نسخة جديدة من الفئة `TextShape` class.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| text | java.lang.String | النص المراد رسمه. |
| rectangle | [RectangleF](../../com.aspose.imaging/rectanglef) | مستطيل النص. |
| font | [Font](../../com.aspose.imaging/font) | الخط المراد استخدامه. |
| stringFormat | [StringFormat](../../com.aspose.imaging/stringformat) | تنسيق السلسلة. |

### getText() {#getText--}
```
public String getText()
```


يحصل أو يعيّن النص المرسوم.

القيمة: النص المرسوم.

**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


يحصل أو يعيّن النص المرسوم.

القيمة: النص المرسوم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getFont() {#getFont--}
```
public Font getFont()
```


يحصل أو يعيّن الخط المستخدم لرسم النص.

القيمة: الخط المستخدم لرسم النص.

**Returns:**
[Font](../../com.aspose.imaging/font)
### setFont(Font value) {#setFont-com.aspose.imaging.Font-}
```
public void setFont(Font value)
```


يحصل أو يعيّن الخط المستخدم لرسم النص.

القيمة: الخط المستخدم لرسم النص.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Font](../../com.aspose.imaging/font) |  |

### getTextFormat() {#getTextFormat--}
```
public StringFormat getTextFormat()
```


يحصل أو يعيّن تنسيق النص.

القيمة: تنسيق النص.

**Returns:**
[StringFormat](../../com.aspose.imaging/stringformat)
### setTextFormat(StringFormat value) {#setTextFormat-com.aspose.imaging.StringFormat-}
```
public void setTextFormat(StringFormat value)
```


يحصل أو يعيّن تنسيق النص.

القيمة: تنسيق النص.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [StringFormat](../../com.aspose.imaging/stringformat) |  |

### getCenter() {#getCenter--}
```
public PointF getCenter()
```


يحصل على مركز الشكل.

القيمة: مركز الشكل.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### getBounds() {#getBounds--}
```
public RectangleF getBounds()
```


يحصل على حدود الكائن.

القيمة: حدود الكائن.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### getSegments() {#getSegments--}
```
public ShapeSegment[] getSegments()
```


يحصل على مقاطع الشكل.

القيمة: مقاطع الشكل.

**Returns:**
com.aspose.imaging.ShapeSegment[]
### hasSegments() {#hasSegments--}
```
public boolean hasSegments()
```


يحصل على قيمة تشير إلى ما إذا كان الشكل يحتوي على مقاطع.

القيمة: `True` إذا كان الشكل يحتوي على مقاطع؛ وإلا، `false`.

**Returns:**
boolean
### getBounds(Matrix matrix) {#getBounds-com.aspose.imaging.Matrix-}
```
public RectangleF getBounds(Matrix matrix)
```


يحصل على حدود الكائن.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | سيتم حساب المصفوفة التي سيتم تطبيقها قبل الحدود. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The estimated object's bounds.
### getBounds(Matrix matrix, Pen pen) {#getBounds-com.aspose.imaging.Matrix-com.aspose.imaging.Pen-}
```
public RectangleF getBounds(Matrix matrix, Pen pen)
```


يحصل على حدود الكائن.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | سيتم حساب المصفوفة التي سيتم تطبيقها قبل الحدود. |
| pen | [Pen](../../com.aspose.imaging/pen) | القلم المستخدم للكائن. يمكن أن يؤثر هذا على حجم حدود الكائن. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The estimated object's bounds.
### transform(Matrix transform) {#transform-com.aspose.imaging.Matrix-}
```
public void transform(Matrix transform)
```


يطبق التحويل المحدد على الشكل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| transform | [Matrix](../../com.aspose.imaging/matrix) | التحويل الذي سيتم تطبيقه. |

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


تحقق مما إذا كانت الكائنات متساوية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| o | java.lang.Object | الكائن الآخر. |

**Returns:**
boolean - نتيجة مقارنة المساواة.
### hashCode() {#hashCode--}
```
public int hashCode()
```


احصل على رمز التجزئة للكائن الحالي.

**Returns:**
int - رمز التجزئة.
