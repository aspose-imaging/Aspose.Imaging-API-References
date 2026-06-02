---
title: "SolidBrush"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "الفرشاة الصلبة مخصصة للرسم باستمرار بلون محدد."
type: docs
weight: 17
url: /ar/java/com.aspose.imaging.brushes/solidbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.Brush](../../com.aspose.imaging/brush)
```
public final class SolidBrush extends Brush
```

الفرشاة الصلبة مخصصة للرسم باستمرار بلون محدد. لا يمكن توريث هذه الفئة.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [SolidBrush()](#SolidBrush--) | يُنشئ مثيلاً جديداً من الفئة `SolidBrush`. |
| [SolidBrush(Color color)](#SolidBrush-com.aspose.imaging.Color-) | يُنشئ مثيلاً جديداً من الفئة `SolidBrush`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getColor()](#getColor--) | يحصل على لون الفرشاة أو يضبطه. |
| [setColor(Color value)](#setColor-com.aspose.imaging.Color-) | يحصل على لون الفرشاة أو يضبطه. |
| [hashCode()](#hashCode--) |  |
| [equals(Object object)](#equals-java.lang.Object-) |  |

## Example: This example uses Graphics class to create primitive shapes on the Image surface.
يستخدم هذا المثال فئة Graphics لإنشاء أشكال بدائية على سطح Image. لتوضيح العملية، ينشئ المثال صورة جديدة بصيغة PNG ويرسم أشكالاً بدائية على سطح Image باستخدام طرق Draw التي توفرها فئة Graphics.
``` java
// ينشئ مثيلاً من FileStream
com.aspose.imaging.system.io.FileStream stream = new com.aspose.imaging.system.io.FileStream("C:\\temp\\output.png", com.aspose.imaging.system.io.FileMode.Create);
try {
    // أنشئ مثيلاً من PngOptions واضبط خصائصه المتنوعة
    com.aspose.imaging.imageoptions.PngOptions pngOptions = new com.aspose.imaging.imageoptions.PngOptions();

    // اضبط المصدر لـ PngOptions
    pngOptions.setSource(new com.aspose.imaging.sources.StreamSource(stream));

    // إنشاء نسخة من Image
    com.aspose.imaging.Image image = com.aspose.imaging.Image.create(pngOptions, 500, 500);
    try {
        // إنشاء وتهيئة نسخة من فئة Graphics
        com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);

        // مسح سطح Graphics
        graphics.clear(com.aspose.imaging.Color.getWheat());

        // ارسم قوساً بتحديد كائن Pen الذي يملك اللون Black com.aspose.imaging.Color،
        // مستطيل يحيط بالقوس، زاوية البداية وزاوية المسح
        graphics.drawArc(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlack(), 2),
                new com.aspose.imaging.Rectangle(200, 200, 100, 200),
                0,
                300);

        // ارسم منحنى بيزير بتحديد كائن Pen الذي يملك اللون Blue com.aspose.imaging.Color ونقاط الإحداثيات.
        graphics.drawBezier(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlue(), 2),
                new com.aspose.imaging.Point(250, 100),
                new com.aspose.imaging.Point(300, 30),
                new com.aspose.imaging.Point(450, 100),
                new com.aspose.imaging.Point(235, 25));

        // ارسم منحنى بتحديد كائن Pen الذي يملك اللون Green com.aspose.imaging.Color ومصفوفة من النقاط
        graphics.drawCurve(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getGreen(), 2),
                new com.aspose.imaging.Point[]
                        {
                                new com.aspose.imaging.Point(100, 200),
                                new com.aspose.imaging.Point(100, 350),
                                new com.aspose.imaging.Point(200, 450)
                        });

        // ارسم إهليلجاً باستخدام كائن Pen ومستطيل يحيط به
        graphics.drawEllipse(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getYellow(), 2),
                new com.aspose.imaging.Rectangle(300, 300, 100, 100));

        // ارسم خطاً
        graphics.drawLine(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getViolet(), 2),
                new com.aspose.imaging.Point(100, 100),
                new com.aspose.imaging.Point(200, 200));

        // ارسم قطعة فطيرة
        graphics.drawPie(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getSilver(), 2),
                new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(200, 20), new com.aspose.imaging.Size(200, 200)),
                0,
                45);

        // ارسم مضلعاً بتحديد كائن Pen الذي يملك اللون Red com.aspose.imaging.Color ومصفوفة من النقاط
        graphics.drawPolygon(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getRed(), 2),
                new com.aspose.imaging.Point[]
                        {
                                new com.aspose.imaging.Point(20, 100),
                                new com.aspose.imaging.Point(20, 200),
                                new com.aspose.imaging.Point(220, 20)
                        });

        // ارسم مستطيلًا
        graphics.drawRectangle(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getOrange(), 2),
                new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(250, 250), new com.aspose.imaging.Size(100, 100)));

        // أنشئ كائن SolidBrush واضبط خصائصه المتنوعة
        com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush();
        brush.setColor(com.aspose.imaging.Color.getPurple());

        // ارسم نصاً باستخدام كائن SolidBrush والخط، عند نقطة محددة
        graphics.drawString(
                "This image is created by Aspose.Imaging API",
                new com.aspose.imaging.Font("Times New Roman", 16),
                brush,
                new com.aspose.imaging.PointF(50, 400));

        // حفظ جميع التغييرات.
        image.save();
    } finally {
        image.dispose();
    }
} finally {
    stream.dispose();
}
```

### SolidBrush() {#SolidBrush--}
```
public SolidBrush()
```


يُنشئ مثيلاً جديداً من الفئة `SolidBrush`.

### SolidBrush(Color color) {#SolidBrush-com.aspose.imaging.Color-}
```
public SolidBrush(Color color)
```


يُنشئ مثيلاً جديداً من الفئة `SolidBrush`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| color | [Color](../../com.aspose.imaging/color) | لون الفرشاة الصلبة. |

### getColor() {#getColor--}
```
public Color getColor()
```


يحصل على لون الفرشاة أو يضبطه.

القيمة: لون الفرشاة.

**Returns:**
[Color](../../com.aspose.imaging/color)

**Example: This example uses Graphics class to create primitive shapes on the Image surface.**
يستخدم هذا المثال فئة Graphics لإنشاء أشكال بدائية على سطح Image. لتوضيح العملية، ينشئ المثال صورة جديدة بصيغة PNG ويرسم أشكالاً بدائية على سطح Image باستخدام طرق Draw التي توفرها فئة Graphics.
``` java
// ينشئ مثيلاً من FileStream
com.aspose.imaging.system.io.FileStream stream = new com.aspose.imaging.system.io.FileStream("C:\\temp\\output.png", com.aspose.imaging.system.io.FileMode.Create);
try {
    // أنشئ مثيلاً من PngOptions واضبط خصائصه المتنوعة
    com.aspose.imaging.imageoptions.PngOptions pngOptions = new com.aspose.imaging.imageoptions.PngOptions();

    // اضبط المصدر لـ PngOptions
    pngOptions.setSource(new com.aspose.imaging.sources.StreamSource(stream));

    // إنشاء نسخة من Image
    com.aspose.imaging.Image image = com.aspose.imaging.Image.create(pngOptions, 500, 500);
    try {
        // إنشاء وتهيئة نسخة من فئة Graphics
        com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);

        // مسح سطح Graphics
        graphics.clear(com.aspose.imaging.Color.getWheat());

        // ارسم قوساً بتحديد كائن Pen الذي يملك اللون Black com.aspose.imaging.Color،
        // مستطيل يحيط بالقوس، زاوية البداية وزاوية المسح
        graphics.drawArc(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlack(), 2),
                new com.aspose.imaging.Rectangle(200, 200, 100, 200),
                0,
                300);

        // ارسم منحنى بيزير بتحديد كائن Pen الذي يملك اللون Blue com.aspose.imaging.Color ونقاط الإحداثيات.
        graphics.drawBezier(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlue(), 2),
                new com.aspose.imaging.Point(250, 100),
                new com.aspose.imaging.Point(300, 30),
                new com.aspose.imaging.Point(450, 100),
                new com.aspose.imaging.Point(235, 25));

        // ارسم منحنى بتحديد كائن Pen الذي يملك اللون Green com.aspose.imaging.Color ومصفوفة من النقاط
        graphics.drawCurve(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getGreen(), 2),
                new com.aspose.imaging.Point[]
                        {
                                new com.aspose.imaging.Point(100, 200),
                                new com.aspose.imaging.Point(100, 350),
                                new com.aspose.imaging.Point(200, 450)
                        });

        // ارسم إهليلجاً باستخدام كائن Pen ومستطيل يحيط به
        graphics.drawEllipse(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getYellow(), 2),
                new com.aspose.imaging.Rectangle(300, 300, 100, 100));

        // ارسم خطاً
        graphics.drawLine(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getViolet(), 2),
                new com.aspose.imaging.Point(100, 100),
                new com.aspose.imaging.Point(200, 200));

        // ارسم قطعة فطيرة
        graphics.drawPie(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getSilver(), 2),
                new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(200, 20), new com.aspose.imaging.Size(200, 200)),
                0,
                45);

        // ارسم مضلعاً بتحديد كائن Pen الذي يملك اللون Red com.aspose.imaging.Color ومصفوفة من النقاط
        graphics.drawPolygon(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getRed(), 2),
                new com.aspose.imaging.Point[]
                        {
                                new com.aspose.imaging.Point(20, 100),
                                new com.aspose.imaging.Point(20, 200),
                                new com.aspose.imaging.Point(220, 20)
                        });

        // ارسم مستطيلًا
        graphics.drawRectangle(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getOrange(), 2),
                new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(250, 250), new com.aspose.imaging.Size(100, 100)));

        // أنشئ كائن SolidBrush واضبط خصائصه المتنوعة
        com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush();
        brush.setColor(com.aspose.imaging.Color.getPurple());

        // ارسم نصاً باستخدام كائن SolidBrush والخط، عند نقطة محددة
        graphics.drawString(
                "This image is created by Aspose.Imaging API",
                new com.aspose.imaging.Font("Times New Roman", 16),
                brush,
                new com.aspose.imaging.PointF(50, 400));

        // حفظ جميع التغييرات.
        image.save();
    } finally {
        image.dispose();
    }
} finally {
    stream.dispose();
}
```

### setColor(Color value) {#setColor-com.aspose.imaging.Color-}
```
public void setColor(Color value)
```


يحصل على لون الفرشاة أو يضبطه.

القيمة: لون الفرشاة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) |  |

### hashCode() {#hashCode--}
```
public int hashCode()
```


احصل على رمز التجزئة للكائن الحالي.

**Returns:**
int
### equals(Object object) {#equals-java.lang.Object-}
```
public boolean equals(Object object)
```


تحقق مما إذا كانت الكائنات متساوية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| كائن | java.lang.Object |  |

**Returns:**
boolean
