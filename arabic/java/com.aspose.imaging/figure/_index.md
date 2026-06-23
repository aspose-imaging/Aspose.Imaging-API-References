---
title: "Figure"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "الشكل."
type: docs
weight: 44
url: /ar/java/com.aspose.imaging/figure/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.ObjectWithBounds](../../com.aspose.imaging/objectwithbounds)
```
public class Figure extends ObjectWithBounds
```

الشكل. حاوية للأشكال.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [Figure()](#Figure--) | ينشئ مثيلًا جديدًا من [Figure](../../com.aspose.imaging/figure). |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getShapes()](#getShapes--) | يسترجع أشكال الشكل. |
| [getBounds()](#getBounds--) | يحصل أو يضبط حدود الكائن. |
| [isClosed()](#isClosed--) | يحصل على قيمة تشير إلى ما إذا كان هذا الشكل مغلقًا. |
| [setClosed(boolean value)](#setClosed-boolean-) | يضبط قيمة تشير إلى ما إذا كان هذا الشكل مغلقًا. |
| [getSegments()](#getSegments--) | يحصل على جميع مقاطع الشكل. |
| [addShape(Shape shape)](#addShape-com.aspose.imaging.Shape-) | يضيف شكلاً إلى الشكل. |
| [addShapes(Shape[] shapes)](#addShapes-com.aspose.imaging.Shape---) | يضيف مجموعة من الأشكال إلى الشكل. |
| [removeShape(Shape shape)](#removeShape-com.aspose.imaging.Shape-) | يزيل شكلاً من الشكل. |
| [removeShapes(Shape[] shapes)](#removeShapes-com.aspose.imaging.Shape---) | يزيل مجموعة من الأشكال من الشكل. |
| [reverse()](#reverse--) | يعكس ترتيب أشكال هذا الشكل وترتيب نقاط الأشكال. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.imaging.Matrix-) | يحصل على حدود الكائن. |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.imaging.Matrix-com.aspose.imaging.Pen-) | يحصل على حدود الكائن. |
| [transform(Matrix transform)](#transform-com.aspose.imaging.Matrix-) | يطبق التحويل المحدد على الشكل. |
| [equals(Object obj)](#equals-java.lang.Object-) | يحدد ما إذا كان الكائن المحدد مساويًا للكائن الحالي. |
| [hashCode()](#hashCode--) | يعمل كدالة التجزئة الافتراضية. |

## Example: This examples make use of GraphicsPath and Graphics class to create and manipulate Figures on an Image surface.
تستخدم هذه الأمثلة فئة GraphicsPath وفئة Graphics لإنشاء وتعديل الأشكال على سطح صورة. ينشئ المثال صورة جديدة (من نوع Tiff) ويرسم المسارات بمساعدة فئة GraphicsPath. في النهاية يتم استدعاء طريقة DrawPath التي توفرها فئة Graphics لعرض المسارات على السطح.
``` java
// إنشاء نسخة من FileStream
com.aspose.imaging.system.io.FileStream stream = new com.aspose.imaging.system.io.FileStream("C:\\temp\\output.tif", com.aspose.imaging.system.io.FileMode.Create);
try {
    // إنشاء نسخة من TiffOptions وتعيين خصائصه المتنوعة
    com.aspose.imaging.imageoptions.TiffOptions tiffOptions = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);

    // تعيين المصدر لنسخة ImageOptions
    tiffOptions.setSource(new com.aspose.imaging.sources.StreamSource(stream));

    // إنشاء نسخة من Image
    com.aspose.imaging.Image image = com.aspose.imaging.Image.create(tiffOptions, 500, 500);
    try {
        // إنشاء وتهيئة نسخة من فئة Graphics
        com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);

        // مسح سطح Graphics
        graphics.clear(com.aspose.imaging.Color.getWheat());

        // إنشاء نسخة من فئة GraphicsPath
        com.aspose.imaging.GraphicsPath graphicspath = new com.aspose.imaging.GraphicsPath();

        // إنشاء نسخة من فئة Figure
        com.aspose.imaging.Figure figure = new com.aspose.imaging.Figure();

        // إضافة أشكال إلى كائن Figure
        figure.addShape(new com.aspose.imaging.shapes.RectangleShape(new com.aspose.imaging.RectangleF(10, 10, 300, 300)));
        figure.addShape(new com.aspose.imaging.shapes.EllipseShape(new com.aspose.imaging.RectangleF(50, 50, 300, 300)));
        figure.addShape(
                new com.aspose.imaging.shapes.PieShape(new com.aspose.imaging.RectangleF(
                        new com.aspose.imaging.PointF(250, 250),
                        new com.aspose.imaging.SizeF(200, 200)),
                        0, 45));

        // إضافة كائن Figure إلى GraphicsPath
        graphicspath.addFigure(figure);

        // رسم مسار باستخدام كائن Pen باللون الأسود
        graphics.drawPath(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlack(), 2), graphicspath);

        // حفظ جميع التغييرات.
        image.save();
    } finally {
        image.dispose();
    }
} finally {
    stream.dispose();
}
```

### Figure() {#Figure--}
```
public Figure()
```


يُهيئ نسخة جديدة من [Figure](../../com.aspose.imaging/figure). مُنشئ مطلوب لتسلسل JSON.

### getShapes() {#getShapes--}
```
public Shape[] getShapes()
```


يسترجع أشكال الشكل.

**Returns:**
com.aspose.imaging.Shape[] - أشكال الشكل.
### getBounds() {#getBounds--}
```
public RectangleF getBounds()
```


يحصل أو يضبط حدود الكائن.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The object's bounds.
### isClosed() {#isClosed--}
```
public boolean isClosed()
```


يحصل على قيمة تشير إلى ما إذا كان هذا الشكل مغلقًا. سيُحدث الشكل المغلق فرقًا فقط في الحالة التي تكون فيها الأشكال الأولى والأخيرة للشكل متصلة. في هذه الحالة سيتم ربط النقطة الأولى للشكل الأول بخط مستقيم من النقطة الأخيرة للشكل الأخير.

**Returns:**
منطقي - `True` إذا كان هذا الشكل مغلقًا؛ وإلا `false`.
### setClosed(boolean value) {#setClosed-boolean-}
```
public void setClosed(boolean value)
```


يضبط قيمة تشير إلى ما إذا كان هذا الشكل مغلقًا. سيُحدث الشكل المغلق فرقًا فقط في الحالة التي تكون فيها الأشكال الأولى والأخيرة للشكل متصلة. في هذه الحالة سيتم ربط النقطة الأولى للشكل الأول بخط مستقيم من النقطة الأخيرة للشكل الأخير.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | boolean | `True` إذا كان هذا الشكل مغلقًا؛ وإلا `false`. |

### getSegments() {#getSegments--}
```
public ShapeSegment[] getSegments()
```


يحصل على جميع مقاطع الشكل.

**Returns:**
com.aspose.imaging.ShapeSegment[] - مقاطع الشكل.
### addShape(Shape shape) {#addShape-com.aspose.imaging.Shape-}
```
public void addShape(Shape shape)
```


يضيف شكلاً إلى الشكل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.imaging/shape) | الشكل للإضافة. |


**Example: This examples make use of GraphicsPath and Graphics class to create and manipulate Figures on an Image surface.**
تستخدم هذه الأمثلة فئة GraphicsPath وفئة Graphics لإنشاء وتعديل الأشكال على سطح صورة. ينشئ المثال صورة جديدة (من نوع Tiff) ويرسم المسارات بمساعدة فئة GraphicsPath. في النهاية يتم استدعاء طريقة DrawPath التي توفرها فئة Graphics لعرض المسارات على السطح.
``` java
// إنشاء نسخة من FileStream
com.aspose.imaging.system.io.FileStream stream = new com.aspose.imaging.system.io.FileStream("C:\\temp\\output.tif", com.aspose.imaging.system.io.FileMode.Create);
try {
    // إنشاء نسخة من TiffOptions وتعيين خصائصه المتنوعة
    com.aspose.imaging.imageoptions.TiffOptions tiffOptions = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);

    // تعيين المصدر لنسخة ImageOptions
    tiffOptions.setSource(new com.aspose.imaging.sources.StreamSource(stream));

    // إنشاء نسخة من Image
    com.aspose.imaging.Image image = com.aspose.imaging.Image.create(tiffOptions, 500, 500);
    try {
        // إنشاء وتهيئة نسخة من فئة Graphics
        com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);

        // مسح سطح Graphics
        graphics.clear(com.aspose.imaging.Color.getWheat());

        // إنشاء نسخة من فئة GraphicsPath
        com.aspose.imaging.GraphicsPath graphicspath = new com.aspose.imaging.GraphicsPath();

        // إنشاء نسخة من فئة Figure
        com.aspose.imaging.Figure figure = new com.aspose.imaging.Figure();

        // إضافة أشكال إلى كائن Figure
        figure.addShape(new com.aspose.imaging.shapes.RectangleShape(new com.aspose.imaging.RectangleF(10, 10, 300, 300)));
        figure.addShape(new com.aspose.imaging.shapes.EllipseShape(new com.aspose.imaging.RectangleF(50, 50, 300, 300)));
        figure.addShape(
                new com.aspose.imaging.shapes.PieShape(new com.aspose.imaging.RectangleF(
                        new com.aspose.imaging.PointF(250, 250),
                        new com.aspose.imaging.SizeF(200, 200)),
                        0, 45));

        // إضافة كائن Figure إلى GraphicsPath
        graphicspath.addFigure(figure);

        // رسم مسار باستخدام كائن Pen باللون الأسود
        graphics.drawPath(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlack(), 2), graphicspath);

        // حفظ جميع التغييرات.
        image.save();
    } finally {
        image.dispose();
    }
} finally {
    stream.dispose();
}
```

### addShapes(Shape[] shapes) {#addShapes-com.aspose.imaging.Shape---}
```
public void addShapes(Shape[] shapes)
```


يضيف مجموعة من الأشكال إلى الشكل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| shapes | [Shape\[\]](../../com.aspose.imaging/shape) | الأشكال للإضافة. |

### removeShape(Shape shape) {#removeShape-com.aspose.imaging.Shape-}
```
public void removeShape(Shape shape)
```


يزيل شكلاً من الشكل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.imaging/shape) | الشكل للإزالة. |

### removeShapes(Shape[] shapes) {#removeShapes-com.aspose.imaging.Shape---}
```
public void removeShapes(Shape[] shapes)
```


يزيل مجموعة من الأشكال من الشكل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| shapes | [Shape\[\]](../../com.aspose.imaging/shape) | نطاق الأشكال للإزالة. |

### reverse() {#reverse--}
```
public void reverse()
```


يعكس ترتيب أشكال هذا الشكل وترتيب نقاط الأشكال.

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

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


يحدد ما إذا كان الكائن المحدد مساويًا للكائن الحالي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| obj | java.lang.Object | الكائن المقارن. |

**Returns:**
منطقي - نتيجة equals
### hashCode() {#hashCode--}
```
public int hashCode()
```


يعمل كدالة التجزئة الافتراضية.

**Returns:**
عدد صحيح - رمز تجزئة للكائن الحالي.
