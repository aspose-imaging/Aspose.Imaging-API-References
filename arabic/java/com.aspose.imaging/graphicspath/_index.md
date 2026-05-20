---
title: "GraphicsPath"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يمثل سلسلة من الخطوط والمنحنيات المتصلة."
type: docs
weight: 52
url: /ar/java/com.aspose.imaging/graphicspath/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.ObjectWithBounds](../../com.aspose.imaging/objectwithbounds)
```
public final class GraphicsPath extends ObjectWithBounds
```

يمثل سلسلة من الخطوط والمنحنيات المتصلة. لا يمكن وراثة هذه الفئة.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [GraphicsPath()](#GraphicsPath--) | ينشئ مثيلاً جديداً من الفئة `GraphicsPath`. |
| [GraphicsPath(Figure[] figures)](#GraphicsPath-com.aspose.imaging.Figure---) | ينشئ مثيلاً جديداً من الفئة `GraphicsPath`. |
| [GraphicsPath(Figure[] figures, int fillMode)](#GraphicsPath-com.aspose.imaging.Figure---int-) | ينشئ مثيلاً جديداً من الفئة `GraphicsPath`. |
| [GraphicsPath(int fillMode)](#GraphicsPath-int-) | ينشئ مثيلاً جديداً من الفئة `GraphicsPath`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getFillMode()](#getFillMode--) | يحصل على تعداد `com.aspose.imaging.FillMode` الذي يحدد كيفية ملء داخل الأشكال في هذا `com.aspose.imaging.GraphicsPath`. |
| [setFillMode(int value)](#setFillMode-int-) | يضبط تعداد `com.aspose.imaging.FillMode` الذي يحدد كيفية تعبئة داخل الأشكال في هذا `com.aspose.imaging.GraphicsPath`. |
| [getFigures()](#getFigures--) | يسترجع أشكال المسار. |
| [getBounds()](#getBounds--) | يحصل أو يعيّن حدود الكائن. |
| [reset()](#reset--) | يفرغ مسار الرسومات ويضبط `com.aspose.imaging.FillMode` إلى `F:com.aspose.imaging.fillMode.alternate`. |
| [reverse()](#reverse--) | يعكس ترتيب الأشكال، والرسومات، والنقاط في كل شكل من هذا `com.aspose.imaging.graphicsPath`. |
| [isVisible(float x, float y)](#isVisible-float-float-) | يشير إلى ما إذا كانت النقطة المحددة موجودة داخل هذا `com.aspose.imaging.graphicsPath`. |
| [isVisible(PointF point)](#isVisible-com.aspose.imaging.PointF-) | يشير إلى ما إذا كانت النقطة المحددة موجودة داخل هذا `com.aspose.imaging.graphicsPath`. |
| [isVisible(int x, int y)](#isVisible-int-int-) | يشير إلى ما إذا كانت النقطة المحددة موجودة داخل هذا `com.aspose.imaging.graphicsPath`. |
| [isVisible(Point point)](#isVisible-com.aspose.imaging.Point-) | يشير إلى ما إذا كانت النقطة المحددة موجودة داخل هذا `com.aspose.imaging.graphicsPath`. |
| [isVisible(float x, float y, Graphics graphics)](#isVisible-float-float-com.aspose.imaging.Graphics-) | يشير إلى ما إذا كانت النقطة المحددة موجودة داخل هذا `com.aspose.imaging.GraphicsPath` في منطقة القص المرئية للـ `com.aspose.imaging.graphics` المحدد. |
| [isVisible(PointF pt, Graphics graphics)](#isVisible-com.aspose.imaging.PointF-com.aspose.imaging.Graphics-) | يشير إلى ما إذا كانت النقطة المحددة موجودة داخل هذا `com.aspose.imaging.graphicsPath`. |
| [isVisible(int x, int y, Graphics graphics)](#isVisible-int-int-com.aspose.imaging.Graphics-) | يشير إلى ما إذا كانت النقطة المحددة موجودة داخل هذا `com.aspose.imaging.GraphicsPath` باستخدام الـ `com.aspose.imaging.graphics` المحدد. |
| [isVisible(Point pt, Graphics graphics)](#isVisible-com.aspose.imaging.Point-com.aspose.imaging.Graphics-) | يشير إلى ما إذا كانت النقطة المحددة موجودة داخل هذا `com.aspose.imaging.graphicsPath`. |
| [isOutlineVisible(float x, float y, Pen pen)](#isOutlineVisible-float-float-com.aspose.imaging.Pen-) | يشير إلى ما إذا كانت النقطة المحددة موجودة داخل (تحت) حدود هذا `com.aspose.imaging.GraphicsPath` عند رسمه بالـ `com.aspose.imaging.pen` المحدد. |
| [isOutlineVisible(PointF point, Pen pen)](#isOutlineVisible-com.aspose.imaging.PointF-com.aspose.imaging.Pen-) | يشير إلى ما إذا كانت النقطة المحددة موجودة داخل (تحت) حدود هذا `com.aspose.imaging.GraphicsPath` عند رسمه بالـ `com.aspose.imaging.pen` المحدد. |
| [isOutlineVisible(float x, float y, Pen pen, Graphics graphics)](#isOutlineVisible-float-float-com.aspose.imaging.Pen-com.aspose.imaging.Graphics-) | يشير إلى ما إذا كانت النقطة المحددة موجودة داخل (تحت) حدود هذا `com.aspose.imaging.GraphicsPath` عند رسمه بالـ `com.aspose.imaging.Pen` المحدد وباستخدام الـ `com.aspose.imaging.graphics` المحدد. |
| [isOutlineVisible(PointF pt, Pen pen, Graphics graphics)](#isOutlineVisible-com.aspose.imaging.PointF-com.aspose.imaging.Pen-com.aspose.imaging.Graphics-) | يشير إلى ما إذا كانت النقطة المحددة موجودة داخل (تحت) حدود هذا `com.aspose.imaging.GraphicsPath` عند رسمه بالـ `com.aspose.imaging.Pen` المحدد وباستخدام الـ `com.aspose.imaging.graphics` المحدد. |
| [isOutlineVisible(int x, int y, Pen pen)](#isOutlineVisible-int-int-com.aspose.imaging.Pen-) | يشير إلى ما إذا كانت النقطة المحددة موجودة داخل (تحت) حدود هذا `com.aspose.imaging.GraphicsPath` عند رسمه بالـ `com.aspose.imaging.pen` المحدد. |
| [isOutlineVisible(Point point, Pen pen)](#isOutlineVisible-com.aspose.imaging.Point-com.aspose.imaging.Pen-) | يشير إلى ما إذا كانت النقطة المحددة موجودة داخل (تحت) حدود هذا `com.aspose.imaging.GraphicsPath` عند رسمه بالـ `com.aspose.imaging.pen` المحدد. |
| [isOutlineVisible(int x, int y, Pen pen, Graphics graphics)](#isOutlineVisible-int-int-com.aspose.imaging.Pen-com.aspose.imaging.Graphics-) | يشير إلى ما إذا كانت النقطة المحددة موجودة داخل (تحت) حدود هذا `com.aspose.imaging.GraphicsPath` عند رسمه بالـ `com.aspose.imaging.Pen` المحدد وباستخدام الـ `com.aspose.imaging.graphics` المحدد. |
| [isOutlineVisible(Point pt, Pen pen, Graphics graphics)](#isOutlineVisible-com.aspose.imaging.Point-com.aspose.imaging.Pen-com.aspose.imaging.Graphics-) | يشير إلى ما إذا كانت النقطة المحددة موجودة داخل (تحت) حدود هذا `com.aspose.imaging.GraphicsPath` عند رسمه بالـ `com.aspose.imaging.Pen` المحدد وباستخدام الـ `com.aspose.imaging.graphics` المحدد. |
| [flatten()](#flatten--) | يحوّل كل منحنى في هذا المسار إلى سلسلة من القطع الخطية المتصلة. |
| [flatten(Matrix matrix)](#flatten-com.aspose.imaging.Matrix-) | يطبق التحويل المحدد ثم يحوّل كل منحنى في هذا `com.aspose.imaging.GraphicsPath` إلى سلسلة من القطع الخطية المتصلة. |
| [flatten(Matrix matrix, float flatness)](#flatten-com.aspose.imaging.Matrix-float-) | يحوّل كل منحنى في هذا `com.aspose.imaging.GraphicsPath` إلى سلسلة من القطع الخطية المتصلة. |
| [widen(Pen pen)](#widen-com.aspose.imaging.Pen-) | يضيف حدودًا إضافية إلى المسار. |
| [widen(Pen pen, Matrix matrix)](#widen-com.aspose.imaging.Pen-com.aspose.imaging.Matrix-) | يضيف حدودًا إضافية إلى `com.aspose.imaging.graphicsPath`. |
| [widen(Pen pen, Matrix matrix, float flatness)](#widen-com.aspose.imaging.Pen-com.aspose.imaging.Matrix-float-) | يستبدل هذا `com.aspose.imaging.GraphicsPath` بمنحنيات تحيط بالمنطقة التي تُملأ عندما يُرسم هذا المسار بالقلم المحدد. |
| [warp(PointF[] destPoints, RectangleF srcRect)](#warp-com.aspose.imaging.PointF---com.aspose.imaging.RectangleF-) | يطبق تحويل تشويه، يُعرّف بواسطة مستطيل ومتوازي أضلاع، على هذا `com.aspose.imaging.graphicsPath`. |
| [warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix)](#warp-com.aspose.imaging.PointF---com.aspose.imaging.RectangleF-com.aspose.imaging.Matrix-) | يطبق تحويل تشويه، يُعرّف بواسطة مستطيل ومتوازي أضلاع، على هذا `com.aspose.imaging.graphicsPath`. |
| [warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode)](#warp-com.aspose.imaging.PointF---com.aspose.imaging.RectangleF-com.aspose.imaging.Matrix-int-) | يطبق تحويل تشويه، يُعرّف بواسطة مستطيل ومتوازي أضلاع، على هذا `com.aspose.imaging.graphicsPath`. |
| [warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode, float flatness)](#warp-com.aspose.imaging.PointF---com.aspose.imaging.RectangleF-com.aspose.imaging.Matrix-int-float-) | يطبق تحويل تشويه، يُعرّف بواسطة مستطيل ومتوازي أضلاع، على هذا `com.aspose.imaging.graphicsPath`. |
| [addFigure(Figure figure)](#addFigure-com.aspose.imaging.Figure-) | يضيف شكلًا جديدًا. |
| [addFigures(Figure[] figures)](#addFigures-com.aspose.imaging.Figure---) | يضيف أشكالًا جديدة. |
| [removeFigure(Figure figure)](#removeFigure-com.aspose.imaging.Figure-) | يزيل شكلًا. |
| [removeFigures(Figure[] figures)](#removeFigures-com.aspose.imaging.Figure---) | يزيل أشكالًا. |
| [addPath(GraphicsPath addingPath)](#addPath-com.aspose.imaging.GraphicsPath-) | يضيف الـ `com.aspose.imaging.GraphicsPath` المحدد إلى هذا المسار. |
| [addPath(GraphicsPath addingPath, boolean connect)](#addPath-com.aspose.imaging.GraphicsPath-boolean-) | يضيف الـ `com.aspose.imaging.GraphicsPath` المحدد إلى هذا المسار. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.imaging.Matrix-) | يحصل على حدود الكائن. |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.imaging.Matrix-com.aspose.imaging.Pen-) | يحصل على حدود الكائن. |
| [deepClone()](#deepClone--) | ينفّذ استنساخًا عميقًا لهذا مسار الرسومات. |
| [transform(Matrix transform)](#transform-com.aspose.imaging.Matrix-) | يطبق التحويل المحدد على الشكل. |
| [equals(Object o)](#equals-java.lang.Object-) | تحقق مما إذا كانت الكائنات متساوية. |
| [hashCode()](#hashCode--) | احصل على رمز التجزئة للكائن الحالي. |

## Example: This examples make use of GraphicsPath and Graphics class to create and manipulate Figures on an Image surface.
تستخدم هذه الأمثلة فئة GraphicsPath وفئة Graphics لإنشاء وتعديل الأشكال على سطح صورة. ينشئ المثال صورة جديدة (من نوع Tiff) ويرسم المسارات بمساعدة فئة GraphicsPath. في النهاية يتم استدعاء طريقة DrawPath التي توفرها فئة Graphics لعرض المسارات على السطح.
``` java
// إنشاء نسخة من FileStream
com.aspose.imaging.system.io.FileStream stream = new com.aspose.imaging.system.io.FileStream("C:\\temp\\output.tif", com.aspose.imaging.system.io.FileMode.Create);
try {
    // إنشاء نسخة من TiffOptions وتعيين خصائصه المتنوعة
    com.aspose.imaging.imageoptions.TiffOptions tiffOptions = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);

    // تعيين المصدر لنسخة من ImageOptions
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

### GraphicsPath() {#GraphicsPath--}
```
public GraphicsPath()
```


ينشئ مثيلاً جديداً من الفئة `GraphicsPath`.

### GraphicsPath(Figure[] figures) {#GraphicsPath-com.aspose.imaging.Figure---}
```
public GraphicsPath(Figure[] figures)
```


ينشئ مثيلاً جديداً من الفئة `GraphicsPath`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| figures | [Figure\[\]](../../com.aspose.imaging/figure) | الأشكال التي سيتم التهيئة منها. |

### GraphicsPath(Figure[] figures, int fillMode) {#GraphicsPath-com.aspose.imaging.Figure---int-}
```
public GraphicsPath(Figure[] figures, int fillMode)
```


ينشئ مثيلاً جديداً من الفئة `GraphicsPath`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| figures | [Figure\[\]](../../com.aspose.imaging/figure) | الأشكال التي سيتم التهيئة منها. |
| fillMode | int | وضع التعبئة. |

### GraphicsPath(int fillMode) {#GraphicsPath-int-}
```
public GraphicsPath(int fillMode)
```


ينشئ مثيلاً جديداً من الفئة `GraphicsPath`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fillMode | int | وضع التعبئة. |

### getFillMode() {#getFillMode--}
```
public int getFillMode()
```


يحصل على تعداد `com.aspose.imaging.FillMode` الذي يحدد كيفية ملء داخل الأشكال في هذا `com.aspose.imaging.GraphicsPath`.

**Returns:**
int - وضع التعبئة. تعداد `com.aspose.imaging.FillMode` يحدد كيفية ملء داخل الأشكال في هذا `com.aspose.imaging.GraphicsPath`.
### setFillMode(int value) {#setFillMode-int-}
```
public void setFillMode(int value)
```


يضبط تعداد `com.aspose.imaging.FillMode` الذي يحدد كيفية تعبئة داخل الأشكال في هذا `com.aspose.imaging.GraphicsPath`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | وضع التعبئة. |

### getFigures() {#getFigures--}
```
public Figure[] getFigures()
```


يسترجع أشكال المسار.

**Returns:**
com.aspose.imaging.Figure[] - أشكال المسار.
### getBounds() {#getBounds--}
```
public RectangleF getBounds()
```


يحصل أو يعيّن حدود الكائن.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The object's bounds.
### reset() {#reset--}
```
public void reset()
```


يفرغ مسار الرسومات ويضبط `com.aspose.imaging.FillMode` إلى `F:com.aspose.imaging.fillMode.alternate`.

### reverse() {#reverse--}
```
public void reverse()
```


يعكس ترتيب الأشكال، والرسومات، والنقاط في كل شكل من هذا `com.aspose.imaging.graphicsPath`.

### isVisible(float x, float y) {#isVisible-float-float-}
```
public boolean isVisible(float x, float y)
```


يشير إلى ما إذا كانت النقطة المحددة موجودة داخل هذا `com.aspose.imaging.graphicsPath`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| س | float | إحداثي x للنقطة المراد اختبارها. |
| ص | float | إحداثي y للنقطة المراد اختبارها. |

**Returns:**
boolean - تُعيد هذه الطريقة true إذا كانت النقطة المحددة موجودة داخل هذا `com.aspose.imaging.GraphicsPath`؛ وإلا false.
### isVisible(PointF point) {#isVisible-com.aspose.imaging.PointF-}
```
public boolean isVisible(PointF point)
```


يشير إلى ما إذا كانت النقطة المحددة موجودة داخل هذا `com.aspose.imaging.graphicsPath`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | `com.aspose.imaging.PointF` الذي يمثل النقطة التي سيتم اختبارها. |

**Returns:**
boolean - تُعيد هذه الطريقة true إذا كانت النقطة المحددة موجودة داخل هذا `com.aspose.imaging.GraphicsPath`؛ وإلا false.
### isVisible(int x, int y) {#isVisible-int-int-}
```
public boolean isVisible(int x, int y)
```


يشير إلى ما إذا كانت النقطة المحددة موجودة داخل هذا `com.aspose.imaging.graphicsPath`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| س | int | إحداثي x للنقطة المراد اختبارها. |
| ص | int | إحداثي y للنقطة المراد اختبارها. |

**Returns:**
boolean - تُعيد هذه الطريقة true إذا كانت النقطة المحددة موجودة داخل هذا `com.aspose.imaging.GraphicsPath`؛ وإلا false.
### isVisible(Point point) {#isVisible-com.aspose.imaging.Point-}
```
public boolean isVisible(Point point)
```


يشير إلى ما إذا كانت النقطة المحددة موجودة داخل هذا `com.aspose.imaging.graphicsPath`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | `com.aspose.imaging.Point` الذي يمثل النقطة التي سيتم اختبارها. |

**Returns:**
boolean - تُعيد هذه الطريقة true إذا كانت النقطة المحددة موجودة داخل هذا `com.aspose.imaging.GraphicsPath`؛ وإلا false.
### isVisible(float x, float y, Graphics graphics) {#isVisible-float-float-com.aspose.imaging.Graphics-}
```
public boolean isVisible(float x, float y, Graphics graphics)
```


يشير إلى ما إذا كانت النقطة المحددة موجودة داخل هذا `com.aspose.imaging.GraphicsPath` في منطقة القص المرئية للـ `com.aspose.imaging.graphics` المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| س | float | إحداثي x للنقطة المراد اختبارها. |
| ص | float | إحداثي y للنقطة المراد اختبارها. |
| graphics | [Graphics](../../com.aspose.imaging/graphics) | `com.aspose.imaging.Graphics` لاختبار الرؤية. |

**Returns:**
boolean - تُعيد هذه الطريقة true إذا كانت النقطة المحددة موجودة داخل هذا `com.aspose.imaging.GraphicsPath`؛ وإلا false.
### isVisible(PointF pt, Graphics graphics) {#isVisible-com.aspose.imaging.PointF-com.aspose.imaging.Graphics-}
```
public boolean isVisible(PointF pt, Graphics graphics)
```


يشير إلى ما إذا كانت النقطة المحددة موجودة داخل هذا `com.aspose.imaging.graphicsPath`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pt | [PointF](../../com.aspose.imaging/pointf) | `com.aspose.imaging.PointF` الذي يمثل النقطة التي سيتم اختبارها. |
| graphics | [Graphics](../../com.aspose.imaging/graphics) | `com.aspose.imaging.Graphics` لاختبار الرؤية. |

**Returns:**
boolean - تُعيد هذه الطريقة true إذا كانت النقطة المحددة موجودة داخل هذا؛ وإلا false.
### isVisible(int x, int y, Graphics graphics) {#isVisible-int-int-com.aspose.imaging.Graphics-}
```
public boolean isVisible(int x, int y, Graphics graphics)
```


يشير إلى ما إذا كانت النقطة المحددة موجودة داخل هذا `com.aspose.imaging.GraphicsPath` باستخدام الـ `com.aspose.imaging.graphics` المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| س | int | إحداثي x للنقطة المراد اختبارها. |
| ص | int | إحداثي y للنقطة المراد اختبارها. |
| graphics | [Graphics](../../com.aspose.imaging/graphics) | `com.aspose.imaging.Graphics` لاختبار الرؤية. |

**Returns:**
boolean - تُعيد هذه الطريقة true إذا كانت النقطة المحددة موجودة داخل هذا `com.aspose.imaging.GraphicsPath`؛ وإلا false.
### isVisible(Point pt, Graphics graphics) {#isVisible-com.aspose.imaging.Point-com.aspose.imaging.Graphics-}
```
public boolean isVisible(Point pt, Graphics graphics)
```


يشير إلى ما إذا كانت النقطة المحددة موجودة داخل هذا `com.aspose.imaging.graphicsPath`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pt | [Point](../../com.aspose.imaging/point) | `com.aspose.imaging.Point` الذي يمثل النقطة التي سيتم اختبارها. |
| graphics | [Graphics](../../com.aspose.imaging/graphics) | `com.aspose.imaging.Graphics` لاختبار الرؤية. |

**Returns:**
boolean - تُعيد هذه الطريقة true إذا كانت النقطة المحددة موجودة داخل هذا `com.aspose.imaging.GraphicsPath`؛ وإلا false.
### isOutlineVisible(float x, float y, Pen pen) {#isOutlineVisible-float-float-com.aspose.imaging.Pen-}
```
public boolean isOutlineVisible(float x, float y, Pen pen)
```


يشير إلى ما إذا كانت النقطة المحددة موجودة داخل (تحت) حدود هذا `com.aspose.imaging.GraphicsPath` عند رسمه بالـ `com.aspose.imaging.pen` المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| س | float | إحداثي x للنقطة المراد اختبارها. |
| ص | float | إحداثي y للنقطة المراد اختبارها. |
| pen | [Pen](../../com.aspose.imaging/pen) | `com.aspose.imaging.Pen` للاختبار. |

**Returns:**
boolean - تُعيد هذه الطريقة true إذا كانت النقطة المحددة موجودة داخل حدود هذا `com.aspose.imaging.GraphicsPath` عند رسمه باستخدام `com.aspose.imaging.Pen` المحدد؛ وإلا false.
### isOutlineVisible(PointF point, Pen pen) {#isOutlineVisible-com.aspose.imaging.PointF-com.aspose.imaging.Pen-}
```
public boolean isOutlineVisible(PointF point, Pen pen)
```


يشير إلى ما إذا كانت النقطة المحددة موجودة داخل (تحت) حدود هذا `com.aspose.imaging.GraphicsPath` عند رسمه بالـ `com.aspose.imaging.pen` المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | `com.aspose.imaging.PointF` الذي يحدد الموقع للاختبار. |
| pen | [Pen](../../com.aspose.imaging/pen) | `com.aspose.imaging.Pen` للاختبار. |

**Returns:**
boolean - تُعيد هذه الطريقة true إذا كانت النقطة المحددة موجودة داخل حدود هذا `com.aspose.imaging.GraphicsPath` عند رسمه باستخدام `com.aspose.imaging.Pen` المحدد؛ وإلا false.
### isOutlineVisible(float x, float y, Pen pen, Graphics graphics) {#isOutlineVisible-float-float-com.aspose.imaging.Pen-com.aspose.imaging.Graphics-}
```
public boolean isOutlineVisible(float x, float y, Pen pen, Graphics graphics)
```


يشير إلى ما إذا كانت النقطة المحددة موجودة داخل (تحت) حدود هذا `com.aspose.imaging.GraphicsPath` عند رسمه بالـ `com.aspose.imaging.Pen` المحدد وباستخدام الـ `com.aspose.imaging.graphics` المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| س | float | إحداثي x للنقطة المراد اختبارها. |
| ص | float | إحداثي y للنقطة المراد اختبارها. |
| pen | [Pen](../../com.aspose.imaging/pen) | `com.aspose.imaging.Pen` للاختبار. |
| graphics | [Graphics](../../com.aspose.imaging/graphics) | `com.aspose.imaging.Graphics` لاختبار الرؤية. |

**Returns:**
boolean - تُعيد هذه الطريقة true إذا كانت النقطة المحددة موجودة داخل (تحت) حدود هذا `com.aspose.imaging.GraphicsPath` كما يُرسم باستخدام `com.aspose.imaging.Pen` المحدد؛ وإلا false.
### isOutlineVisible(PointF pt, Pen pen, Graphics graphics) {#isOutlineVisible-com.aspose.imaging.PointF-com.aspose.imaging.Pen-com.aspose.imaging.Graphics-}
```
public boolean isOutlineVisible(PointF pt, Pen pen, Graphics graphics)
```


يشير إلى ما إذا كانت النقطة المحددة موجودة داخل (تحت) حدود هذا `com.aspose.imaging.GraphicsPath` عند رسمه بالـ `com.aspose.imaging.Pen` المحدد وباستخدام الـ `com.aspose.imaging.graphics` المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pt | [PointF](../../com.aspose.imaging/pointf) | `com.aspose.imaging.PointF` الذي يحدد الموقع للاختبار. |
| pen | [Pen](../../com.aspose.imaging/pen) | `com.aspose.imaging.Pen` للاختبار. |
| graphics | [Graphics](../../com.aspose.imaging/graphics) | `com.aspose.imaging.Graphics` لاختبار الرؤية. |

**Returns:**
boolean - تُعيد هذه الطريقة true إذا كانت النقطة المحددة موجودة داخل (تحت) حدود هذا `com.aspose.imaging.GraphicsPath` كما يُرسم باستخدام `com.aspose.imaging.Pen` المحدد؛ وإلا false.
### isOutlineVisible(int x, int y, Pen pen) {#isOutlineVisible-int-int-com.aspose.imaging.Pen-}
```
public boolean isOutlineVisible(int x, int y, Pen pen)
```


يشير إلى ما إذا كانت النقطة المحددة موجودة داخل (تحت) حدود هذا `com.aspose.imaging.GraphicsPath` عند رسمه بالـ `com.aspose.imaging.pen` المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| س | int | إحداثي x للنقطة المراد اختبارها. |
| ص | int | إحداثي y للنقطة المراد اختبارها. |
| pen | [Pen](../../com.aspose.imaging/pen) | `com.aspose.imaging.Pen` للاختبار. |

**Returns:**
boolean - تُعيد هذه الطريقة true إذا كانت النقطة المحددة موجودة داخل حدود هذا `com.aspose.imaging.GraphicsPath` عند رسمه باستخدام `com.aspose.imaging.Pen` المحدد؛ وإلا false.
### isOutlineVisible(Point point, Pen pen) {#isOutlineVisible-com.aspose.imaging.Point-com.aspose.imaging.Pen-}
```
public boolean isOutlineVisible(Point point, Pen pen)
```


يشير إلى ما إذا كانت النقطة المحددة موجودة داخل (تحت) حدود هذا `com.aspose.imaging.GraphicsPath` عند رسمه بالـ `com.aspose.imaging.pen` المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | `com.aspose.imaging.Point` الذي يحدد الموقع للاختبار. |
| pen | [Pen](../../com.aspose.imaging/pen) | `com.aspose.imaging.Pen` للاختبار. |

**Returns:**
boolean - تُعيد هذه الطريقة true إذا كانت النقطة المحددة موجودة داخل حدود هذا `com.aspose.imaging.GraphicsPath` عند رسمه باستخدام `com.aspose.imaging.Pen` المحدد؛ وإلا false.
### isOutlineVisible(int x, int y, Pen pen, Graphics graphics) {#isOutlineVisible-int-int-com.aspose.imaging.Pen-com.aspose.imaging.Graphics-}
```
public boolean isOutlineVisible(int x, int y, Pen pen, Graphics graphics)
```


يشير إلى ما إذا كانت النقطة المحددة موجودة داخل (تحت) حدود هذا `com.aspose.imaging.GraphicsPath` عند رسمه بالـ `com.aspose.imaging.Pen` المحدد وباستخدام الـ `com.aspose.imaging.graphics` المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| س | int | إحداثي x للنقطة المراد اختبارها. |
| ص | int | إحداثي y للنقطة المراد اختبارها. |
| pen | [Pen](../../com.aspose.imaging/pen) | `com.aspose.imaging.Pen` للاختبار. |
| graphics | [Graphics](../../com.aspose.imaging/graphics) | `com.aspose.imaging.Graphics` لاختبار الرؤية. |

**Returns:**
boolean - تُعيد هذه الطريقة true إذا كانت النقطة المحددة موجودة داخل حدود هذا `com.aspose.imaging.GraphicsPath` كما يُرسم باستخدام `com.aspose.imaging.Pen` المحدد؛ وإلا false.
### isOutlineVisible(Point pt, Pen pen, Graphics graphics) {#isOutlineVisible-com.aspose.imaging.Point-com.aspose.imaging.Pen-com.aspose.imaging.Graphics-}
```
public boolean isOutlineVisible(Point pt, Pen pen, Graphics graphics)
```


يشير إلى ما إذا كانت النقطة المحددة موجودة داخل (تحت) حدود هذا `com.aspose.imaging.GraphicsPath` عند رسمه بالـ `com.aspose.imaging.Pen` المحدد وباستخدام الـ `com.aspose.imaging.graphics` المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pt | [Point](../../com.aspose.imaging/point) | `com.aspose.imaging.Point` الذي يحدد الموقع للاختبار. |
| pen | [Pen](../../com.aspose.imaging/pen) | `com.aspose.imaging.Pen` للاختبار. |
| graphics | [Graphics](../../com.aspose.imaging/graphics) | `com.aspose.imaging.Graphics` لاختبار الرؤية. |

**Returns:**
boolean - تُعيد هذه الطريقة true إذا كانت النقطة المحددة موجودة داخل حدود هذا `com.aspose.imaging.GraphicsPath` كما يُرسم باستخدام `com.aspose.imaging.Pen` المحدد؛ وإلا false.
### flatten() {#flatten--}
```
public void flatten()
```


يحوّل كل منحنى في هذا المسار إلى سلسلة من القطع الخطية المتصلة.

### flatten(Matrix matrix) {#flatten-com.aspose.imaging.Matrix-}
```
public void flatten(Matrix matrix)
```


يطبق التحويل المحدد ثم يحوّل كل منحنى في هذا `com.aspose.imaging.GraphicsPath` إلى سلسلة من القطع الخطية المتصلة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | `com.aspose.imaging.Matrix` الذي يُستخدم لتحويل هذا `com.aspose.imaging.GraphicsPath` قبل التسوية. |

### flatten(Matrix matrix, float flatness) {#flatten-com.aspose.imaging.Matrix-float-}
```
public void flatten(Matrix matrix, float flatness)
```


يحوّل كل منحنى في هذا `com.aspose.imaging.GraphicsPath` إلى سلسلة من القطع الخطية المتصلة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | `com.aspose.imaging.Matrix` الذي يُستخدم لتحويل هذا `com.aspose.imaging.GraphicsPath` قبل التسوية. |
| السطحية | float | يحدد الحد الأقصى للخطأ المسموح بين المنحنى وتقريبه المسطح. القيمة الافتراضية هي 0.25. تقليل قيمة السطحية سيزيد عدد مقاطع الخط في التقريب. |

### widen(Pen pen) {#widen-com.aspose.imaging.Pen-}
```
public void widen(Pen pen)
```


يضيف حدودًا إضافية إلى المسار.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | `com.aspose.imaging.Pen` الذي يحدد العرض بين الحدود الأصلية للمسار والحدود الجديدة التي تُنشئها هذه الطريقة. |

### widen(Pen pen, Matrix matrix) {#widen-com.aspose.imaging.Pen-com.aspose.imaging.Matrix-}
```
public void widen(Pen pen, Matrix matrix)
```


يضيف حدودًا إضافية إلى `com.aspose.imaging.graphicsPath`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | `com.aspose.imaging.Pen` الذي يحدد العرض بين الحدود الأصلية للمسار والحدود الجديدة التي تُنشئها هذه الطريقة. |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | `com.aspose.imaging.Matrix` الذي يحدد التحويل لتطبيقه على المسار قبل توسيعه. |

### widen(Pen pen, Matrix matrix, float flatness) {#widen-com.aspose.imaging.Pen-com.aspose.imaging.Matrix-float-}
```
public void widen(Pen pen, Matrix matrix, float flatness)
```


يستبدل هذا `com.aspose.imaging.GraphicsPath` بمنحنيات تحيط بالمنطقة التي تُملأ عندما يُرسم هذا المسار بالقلم المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | `com.aspose.imaging.Pen` الذي يحدد العرض بين الحدود الأصلية للمسار والحدود الجديدة التي تُنشئها هذه الطريقة. |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | `com.aspose.imaging.Matrix` الذي يحدد التحويل لتطبيقه على المسار قبل توسيعه. |
| السطحية | float | قيمة تحدد السطحية للمنحنيات. |

### warp(PointF[] destPoints, RectangleF srcRect) {#warp-com.aspose.imaging.PointF---com.aspose.imaging.RectangleF-}
```
public void warp(PointF[] destPoints, RectangleF srcRect)
```


يطبق تحويل تشويه، يُعرّف بواسطة مستطيل ومتوازي أضلاع، على هذا `com.aspose.imaging.graphicsPath`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| destPoints | [PointF\[\]](../../com.aspose.imaging/pointf) | مصفوفة من هياكل `com.aspose.imaging.PointF` التي تُعرّف متوازي أضلاع يتم تحويل المستطيل المحدد بـ `srcRect` إليه. يمكن أن تحتوي المصفوفة على ثلاثة أو أربعة عناصر. إذا احتوت المصفوفة على ثلاثة عناصر، فإن الزاوية السفلية اليمنى للمتوازي أضلاع تُستنتج من النقاط الثلاث الأولى. |
| srcRect | [RectangleF](../../com.aspose.imaging/rectanglef) | `com.aspose.imaging.RectangleF` الذي يمثل المستطيل الذي يُحول إلى المتوازي أضلاع المحدد بـ `destPoints`. |

### warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix) {#warp-com.aspose.imaging.PointF---com.aspose.imaging.RectangleF-com.aspose.imaging.Matrix-}
```
public void warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix)
```


يطبق تحويل تشويه، يُعرّف بواسطة مستطيل ومتوازي أضلاع، على هذا `com.aspose.imaging.graphicsPath`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| destPoints | [PointF\[\]](../../com.aspose.imaging/pointf) | مصفوفة من هياكل `com.aspose.imaging.PointF` التي تُعرّف متوازي أضلاع يتم تحويل المستطيل المحدد بـ `srcRect` إليه. يمكن أن تحتوي المصفوفة على ثلاثة أو أربعة عناصر. إذا احتوت المصفوفة على ثلاثة عناصر، فإن الزاوية السفلية اليمنى للمتوازي أضلاع تُستنتج من النقاط الثلاث الأولى. |
| srcRect | [RectangleF](../../com.aspose.imaging/rectanglef) | `com.aspose.imaging.RectangleF` الذي يمثل المستطيل الذي يُحول إلى المتوازي أضلاع المحدد بـ `destPoints`. |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | `com.aspose.imaging.Matrix` الذي يحدد تحويلًا هندسيًا لتطبيقه على المسار. |

### warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode) {#warp-com.aspose.imaging.PointF---com.aspose.imaging.RectangleF-com.aspose.imaging.Matrix-int-}
```
public void warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode)
```


يطبق تحويل تشويه، يُعرّف بواسطة مستطيل ومتوازي أضلاع، على هذا `com.aspose.imaging.graphicsPath`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| destPoints | [PointF\[\]](../../com.aspose.imaging/pointf) | مصفوفة من هياكل `com.aspose.imaging.PointF` التي تُعرّف متوازي أضلاع يتم تحويل المستطيل المحدد بـ `srcRect` إليه. يمكن أن تحتوي المصفوفة على ثلاثة أو أربعة عناصر. إذا احتوت المصفوفة على ثلاثة عناصر، فإن الزاوية السفلية اليمنى للمتوازي أضلاع تُستنتج من النقاط الثلاث الأولى. |
| srcRect | [RectangleF](../../com.aspose.imaging/rectanglef) | `com.aspose.imaging.RectangleF` الذي يمثل المستطيل الذي يُحول إلى المتوازي أضلاع المحدد بـ `destPoints`. |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | `com.aspose.imaging.Matrix` الذي يحدد تحويلًا هندسيًا لتطبيقه على المسار. |
| وضع الالتواء | int | تعداد `com.aspose.imaging.WarpMode` يحدد ما إذا كانت عملية الالتواء هذه تستخدم وضع المنظور أو الوضع الثنائي الخطية. |

### warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode, float flatness) {#warp-com.aspose.imaging.PointF---com.aspose.imaging.RectangleF-com.aspose.imaging.Matrix-int-float-}
```
public void warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode, float flatness)
```


يطبق تحويل تشويه، يُعرّف بواسطة مستطيل ومتوازي أضلاع، على هذا `com.aspose.imaging.graphicsPath`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| destPoints | [PointF\[\]](../../com.aspose.imaging/pointf) | مصفوفة من هياكل `com.aspose.imaging.PointF` التي تُعرّف متوازي أضلاع يتم تحويل المستطيل المحدد بـ `srcRect` إليه. يمكن أن تحتوي المصفوفة على ثلاثة أو أربعة عناصر. إذا احتوت المصفوفة على ثلاثة عناصر، فإن الزاوية السفلية اليمنى للمتوازي أضلاع تُستنتج من النقاط الثلاث الأولى. |
| srcRect | [RectangleF](../../com.aspose.imaging/rectanglef) | `com.aspose.imaging.RectangleF` الذي يمثل المستطيل الذي يُحول إلى المتوازي أضلاع المحدد بـ `destPoints`. |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | `com.aspose.imaging.Matrix` الذي يحدد تحويلًا هندسيًا لتطبيقه على المسار. |
| وضع الالتواء | int | تعداد `com.aspose.imaging.WarpMode` يحدد ما إذا كانت عملية الالتواء هذه تستخدم وضع المنظور أو الوضع الثنائي الخطية. |
| السطحية | float | قيمة تتراوح بين 0 و 1 تحدد مدى تسطيح المسار الناتج. لمزيد من المعلومات، راجع طرق `com.aspose.imaging.GraphicsPath.flatten`. |

### addFigure(Figure figure) {#addFigure-com.aspose.imaging.Figure-}
```
public void addFigure(Figure figure)
```


يضيف شكلًا جديدًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| figure | [Figure](../../com.aspose.imaging/figure) | الشكل المراد إضافته. |


**Example: This examples make use of GraphicsPath and Graphics class to create and manipulate Figures on an Image surface.**
تستخدم هذه الأمثلة فئة GraphicsPath وفئة Graphics لإنشاء وتعديل الأشكال على سطح صورة. ينشئ المثال صورة جديدة (من نوع Tiff) ويرسم المسارات بمساعدة فئة GraphicsPath. في النهاية يتم استدعاء طريقة DrawPath التي توفرها فئة Graphics لعرض المسارات على السطح.
``` java
// إنشاء نسخة من FileStream
com.aspose.imaging.system.io.FileStream stream = new com.aspose.imaging.system.io.FileStream("C:\\temp\\output.tif", com.aspose.imaging.system.io.FileMode.Create);
try {
    // إنشاء نسخة من TiffOptions وتعيين خصائصه المتنوعة
    com.aspose.imaging.imageoptions.TiffOptions tiffOptions = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);

    // تعيين المصدر لنسخة من ImageOptions
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

### addFigures(Figure[] figures) {#addFigures-com.aspose.imaging.Figure---}
```
public void addFigures(Figure[] figures)
```


يضيف أشكالًا جديدة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| figures | [Figure\[\]](../../com.aspose.imaging/figure) | الأشكال المراد إضافتها. |


**Example: This example creates a new Image and draws a variety of shapes using Figures and GraphicsPath o...**
هذا المثال ينشئ صورة جديدة ويرسم مجموعة متنوعة من الأشكال باستخدام Figures و GraphicsPath على سطح الصورة.
``` java
//ينشئ مثيلاً من BmpOptions ويضبط خصائصه المتنوعة.
com.aspose.imaging.imageoptions.BmpOptions bmpOptions = new com.aspose.imaging.imageoptions.BmpOptions();
bmpOptions.setBitsPerPixel(24);

//إنشاء مثيل من FileCreateSource وتعيينه كقيمة Source لمثيل BmpOptions.
//المعامل البولياني الثاني يحدد ما إذا كان الملف الذي سيتم إنشاؤه مؤقتًا أم لا.
bmpOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("c:\\temp\\output.bmp", false));

//إنشاء نسخة من Image
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(bmpOptions, 500, 500);
try {
    //إنشاء وتهيئة نسخة من فئة Graphics
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);

    //مسح سطح Graphics
    graphics.clear(com.aspose.imaging.Color.getWheat());

    //إنشاء نسخة من فئة GraphicsPath
    com.aspose.imaging.GraphicsPath graphicspath = new com.aspose.imaging.GraphicsPath();

    //إنشاء نسخة من فئة Figure
    com.aspose.imaging.Figure figure1 = new com.aspose.imaging.Figure();

    //إضافة شكل إلى كائن Figure.
    figure1.addShape(new com.aspose.imaging.shapes.EllipseShape(new com.aspose.imaging.RectangleF(50, 50, 300, 300)));
    figure1.addShape(new com.aspose.imaging.shapes.PieShape(
            new com.aspose.imaging.RectangleF(
                    new com.aspose.imaging.PointF(110, 110),
                    new com.aspose.imaging.SizeF(200, 200)), 0, 90));

    //إنشاء نسخة من فئة Figure
    com.aspose.imaging.Figure figure2 = new com.aspose.imaging.Figure();

    //إضافة شكل إلى كائن Figure.
    figure2.addShape(new com.aspose.imaging.shapes.ArcShape(new com.aspose.imaging.RectangleF(10, 10, 300, 300), 0, 45));
    figure2.addShape(new com.aspose.imaging.shapes.PolygonShape(
            new com.aspose.imaging.PointF[]
                    {
                            new com.aspose.imaging.PointF(150, 10),
                            new com.aspose.imaging.PointF(150, 200),
                            new com.aspose.imaging.PointF(250, 300),
                            new com.aspose.imaging.PointF(350, 400)}, true));
    figure2.addShape(new com.aspose.imaging.shapes.RectangleShape(
            new com.aspose.imaging.RectangleF(
                    new com.aspose.imaging.PointF(250, 250),
                    new com.aspose.imaging.SizeF(200, 200))));

    //إضافة كائن Figure إلى GraphicsPath
    graphicspath.addFigures(new com.aspose.imaging.Figure[]{figure1, figure2});

    //رسم مسار باستخدام كائن Pen باللون الأسود
    graphics.drawPath(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlack(), 2), graphicspath);

    // احفظ جميع التغييرات.
    image.save();
} finally {
    image.dispose();
}
```

### removeFigure(Figure figure) {#removeFigure-com.aspose.imaging.Figure-}
```
public void removeFigure(Figure figure)
```


يزيل شكلًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| figure | [Figure](../../com.aspose.imaging/figure) | الشكل المراد إزالته. |

### removeFigures(Figure[] figures) {#removeFigures-com.aspose.imaging.Figure---}
```
public void removeFigures(Figure[] figures)
```


يزيل أشكالًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| figures | [Figure\[\]](../../com.aspose.imaging/figure) | الأشكال المراد إزالتها. |

### addPath(GraphicsPath addingPath) {#addPath-com.aspose.imaging.GraphicsPath-}
```
public void addPath(GraphicsPath addingPath)
```


يضيف الـ `com.aspose.imaging.GraphicsPath` المحدد إلى هذا المسار.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| addingPath | [GraphicsPath](../../com.aspose.imaging/graphicspath) | الـ `com.aspose.imaging.GraphicsPath` المراد إضافته. |

### addPath(GraphicsPath addingPath, boolean connect) {#addPath-com.aspose.imaging.GraphicsPath-boolean-}
```
public void addPath(GraphicsPath addingPath, boolean connect)
```


يضيف الـ `com.aspose.imaging.GraphicsPath` المحدد إلى هذا المسار.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| addingPath | [GraphicsPath](../../com.aspose.imaging/graphicspath) | الـ `com.aspose.imaging.GraphicsPath` المراد إضافته. |
| اتصال | boolean | قيمة منطقية تحدد ما إذا كان الشكل الأول في المسار المضاف جزءًا من الشكل الأخير في هذا المسار. القيمة true تعني أن الشكل الأول في المسار المضاف جزء من الشكل الأخير في هذا المسار. القيمة false تعني أن الشكل الأول في المسار المضاف منفصل عن الشكل الأخير في هذا المسار. |

### getBounds(Matrix matrix) {#getBounds-com.aspose.imaging.Matrix-}
```
public RectangleF getBounds(Matrix matrix)
```


يحصل على حدود الكائن.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | المصفوفة التي سيتم تطبيقها قبل حساب الحدود. |

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
| matrix | [Matrix](../../com.aspose.imaging/matrix) | المصفوفة التي سيتم تطبيقها قبل حساب الحدود. |
| pen | [Pen](../../com.aspose.imaging/pen) | القلم المستخدم للكائن. يمكن أن يؤثر ذلك على حجم حدود الكائن. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The estimated object's bounds.
### deepClone() {#deepClone--}
```
public GraphicsPath deepClone()
```


ينفّذ استنساخًا عميقًا لهذا مسار الرسومات.

**Returns:**
[GraphicsPath](../../com.aspose.imaging/graphicspath) - A deep clone of the graphics path.
### transform(Matrix transform) {#transform-com.aspose.imaging.Matrix-}
```
public void transform(Matrix transform)
```


يطبق التحويل المحدد على الشكل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| transform | [Matrix](../../com.aspose.imaging/matrix) | التحويل المراد تطبيقه. |

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
