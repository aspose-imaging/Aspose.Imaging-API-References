---
title: "HatchBrush"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يعرّف فرشاة مستطيلة ذات نمط تخطيط ولون أمامي ولون خلفية."
type: docs
weight: 10
url: /ar/java/com.aspose.imaging.brushes/hatchbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.Brush](../../com.aspose.imaging/brush)
```
public final class HatchBrush extends Brush
```

يعرّف فرشاة مستطيلة ذات نمط تخطيط، ولون أمامي، ولون خلفية. لا يمكن وراثة هذه الفئة.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [HatchBrush()](#HatchBrush--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getForegroundColor()](#getForegroundColor--) | يحصل على لون خطوط التخطيط. |
| [setForegroundColor(Color value)](#setForegroundColor-com.aspose.imaging.Color-) | يضبط لون خطوط التخطيط. |
| [getBackgroundColor()](#getBackgroundColor--) | يحصل على لون الفراغات بين خطوط التخطيط. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.imaging.Color-) | يضبط لون الفراغات بين خطوط التخطيط. |
| [getHatchStyle()](#getHatchStyle--) | يحصل على نمط التخطيط لهذه الفرشاة. |
| [setHatchStyle(int value)](#setHatchStyle-int-) | يضبط نمط التظليل لهذه الفرشاة. |

## Example: This example shows the creation and usage Pen objects.
يوضح هذا المثال إنشاء واستخدام كائنات Pen. ينشئ المثال صورة جديدة Image ويرسم مستطيلات على سطح الصورة.
``` java

// إنشاء مثيل من BmpOptions وتعيين خصائصه المتنوعة.
com.aspose.imaging.imageoptions.BmpOptions bmpOptions = new com.aspose.imaging.imageoptions.BmpOptions();
bmpOptions.setBitsPerPixel(24);

// إنشاء مثيل من FileCreateSource وتعيينه كقيمة Source لمثيل BmpOptions.
// المعامل البولياني الثاني يحدد ما إذا كان الملف الذي سيتم إنشاؤه مؤقتًا أم لا.
bmpOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("C:\\temp\\sample.bmp", false));

// إنشاء نسخة من Image في المسار المحدد.
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(bmpOptions, 500, 500);
try {
    // إنشاء نسخة من Graphics وتهيئتها باستخدام كائن Image.
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);

    // امسح سطح Graphics باستخدام White Color.
    graphics.clear(com.aspose.imaging.Color.getWhite());

    // إنشاء نسخة من Pen باللون الأحمر وعرض 5.
    com.aspose.imaging.Pen pen = new com.aspose.imaging.Pen(com.aspose.imaging.Color.getRed(), 5);

    // إنشاء نسخة من HatchBrush وتعيين خصائصه.
    com.aspose.imaging.brushes.HatchBrush brush = new com.aspose.imaging.brushes.HatchBrush();
    brush.setBackgroundColor(com.aspose.imaging.Color.getWheat());
    brush.setForegroundColor(com.aspose.imaging.Color.getRed());

    // إنشاء نسخة من Pen وتهيئتها باستخدام كائن HatchBrush والعرض.
    com.aspose.imaging.Pen brushedpen = new com.aspose.imaging.Pen(brush, 5);

    // ارسم مستطيلات بتحديد كائن Pen.
    graphics.drawRectangles(pen, new com.aspose.imaging.Rectangle[]
            {
                    new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(210, 210), new com.aspose.imaging.Size(100, 100)),
                    new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(110, 110), new com.aspose.imaging.Size(100, 100)),
                    new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(310, 310), new com.aspose.imaging.Size(100, 100))
            });

    // ارسم مستطيلات بتحديد كائن Pen.
    graphics.drawRectangles(
            brushedpen,
            new com.aspose.imaging.Rectangle[]
                    {
                            new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(310, 110), new com.aspose.imaging.Size(100, 100)),
                            new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(110, 310), new com.aspose.imaging.Size(100, 100))
                    });

    // حفظ جميع التغييرات.
    image.save();
} finally {
    image.dispose();
}
```

### HatchBrush() {#HatchBrush--}
```
public HatchBrush()
```


### getForegroundColor() {#getForegroundColor--}
```
public Color getForegroundColor()
```


يحصل على لون خطوط التخطيط.

**Returns:**
[Color](../../com.aspose.imaging/color) - The color of hatch lines.
### setForegroundColor(Color value) {#setForegroundColor-com.aspose.imaging.Color-}
```
public void setForegroundColor(Color value)
```


يضبط لون خطوط التخطيط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | لون خطوط التظليل. |


**Example: This example shows the creation and usage Pen objects.**
يوضح هذا المثال إنشاء واستخدام كائنات Pen. ينشئ المثال صورة جديدة Image ويرسم مستطيلات على سطح الصورة.
``` java

// إنشاء مثيل من BmpOptions وتعيين خصائصه المتنوعة.
com.aspose.imaging.imageoptions.BmpOptions bmpOptions = new com.aspose.imaging.imageoptions.BmpOptions();
bmpOptions.setBitsPerPixel(24);

// إنشاء مثيل من FileCreateSource وتعيينه كقيمة Source لمثيل BmpOptions.
// المعامل البولياني الثاني يحدد ما إذا كان الملف الذي سيتم إنشاؤه مؤقتًا أم لا.
bmpOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("C:\\temp\\sample.bmp", false));

// إنشاء نسخة من Image في المسار المحدد.
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(bmpOptions, 500, 500);
try {
    // إنشاء نسخة من Graphics وتهيئتها باستخدام كائن Image.
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);

    // امسح سطح Graphics باستخدام White Color.
    graphics.clear(com.aspose.imaging.Color.getWhite());

    // إنشاء نسخة من Pen باللون الأحمر وعرض 5.
    com.aspose.imaging.Pen pen = new com.aspose.imaging.Pen(com.aspose.imaging.Color.getRed(), 5);

    // إنشاء نسخة من HatchBrush وتعيين خصائصه.
    com.aspose.imaging.brushes.HatchBrush brush = new com.aspose.imaging.brushes.HatchBrush();
    brush.setBackgroundColor(com.aspose.imaging.Color.getWheat());
    brush.setForegroundColor(com.aspose.imaging.Color.getRed());

    // إنشاء نسخة من Pen وتهيئتها باستخدام كائن HatchBrush والعرض.
    com.aspose.imaging.Pen brushedpen = new com.aspose.imaging.Pen(brush, 5);

    // ارسم مستطيلات بتحديد كائن Pen.
    graphics.drawRectangles(pen, new com.aspose.imaging.Rectangle[]
            {
                    new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(210, 210), new com.aspose.imaging.Size(100, 100)),
                    new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(110, 110), new com.aspose.imaging.Size(100, 100)),
                    new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(310, 310), new com.aspose.imaging.Size(100, 100))
            });

    // ارسم مستطيلات بتحديد كائن Pen.
    graphics.drawRectangles(
            brushedpen,
            new com.aspose.imaging.Rectangle[]
                    {
                            new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(310, 110), new com.aspose.imaging.Size(100, 100)),
                            new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(110, 310), new com.aspose.imaging.Size(100, 100))
                    });

    // حفظ جميع التغييرات.
    image.save();
} finally {
    image.dispose();
}
```

### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


يحصل على لون الفراغات بين خطوط التخطيط.

**Returns:**
[Color](../../com.aspose.imaging/color) - The color of spaces between the hatch lines.
### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.imaging.Color-}
```
public void setBackgroundColor(Color value)
```


يضبط لون الفراغات بين خطوط التخطيط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | لون الفراغات بين خطوط التظليل. |


**Example: This example shows the creation and usage Pen objects.**
يوضح هذا المثال إنشاء واستخدام كائنات Pen. ينشئ المثال صورة جديدة Image ويرسم مستطيلات على سطح الصورة.
``` java

// إنشاء مثيل من BmpOptions وتعيين خصائصه المتنوعة.
com.aspose.imaging.imageoptions.BmpOptions bmpOptions = new com.aspose.imaging.imageoptions.BmpOptions();
bmpOptions.setBitsPerPixel(24);

// إنشاء مثيل من FileCreateSource وتعيينه كقيمة Source لمثيل BmpOptions.
// المعامل البولياني الثاني يحدد ما إذا كان الملف الذي سيتم إنشاؤه مؤقتًا أم لا.
bmpOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("C:\\temp\\sample.bmp", false));

// إنشاء نسخة من Image في المسار المحدد.
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(bmpOptions, 500, 500);
try {
    // إنشاء نسخة من Graphics وتهيئتها باستخدام كائن Image.
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);

    // امسح سطح Graphics باستخدام White Color.
    graphics.clear(com.aspose.imaging.Color.getWhite());

    // إنشاء نسخة من Pen باللون الأحمر وعرض 5.
    com.aspose.imaging.Pen pen = new com.aspose.imaging.Pen(com.aspose.imaging.Color.getRed(), 5);

    // إنشاء نسخة من HatchBrush وتعيين خصائصه.
    com.aspose.imaging.brushes.HatchBrush brush = new com.aspose.imaging.brushes.HatchBrush();
    brush.setBackgroundColor(com.aspose.imaging.Color.getWheat());
    brush.setForegroundColor(com.aspose.imaging.Color.getRed());

    // إنشاء نسخة من Pen وتهيئتها باستخدام كائن HatchBrush والعرض.
    com.aspose.imaging.Pen brushedpen = new com.aspose.imaging.Pen(brush, 5);

    // ارسم مستطيلات بتحديد كائن Pen.
    graphics.drawRectangles(pen, new com.aspose.imaging.Rectangle[]
            {
                    new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(210, 210), new com.aspose.imaging.Size(100, 100)),
                    new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(110, 110), new com.aspose.imaging.Size(100, 100)),
                    new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(310, 310), new com.aspose.imaging.Size(100, 100))
            });

    // ارسم مستطيلات بتحديد كائن Pen.
    graphics.drawRectangles(
            brushedpen,
            new com.aspose.imaging.Rectangle[]
                    {
                            new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(310, 110), new com.aspose.imaging.Size(100, 100)),
                            new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(110, 310), new com.aspose.imaging.Size(100, 100))
                    });

    // حفظ جميع التغييرات.
    image.save();
} finally {
    image.dispose();
}
```

### getHatchStyle() {#getHatchStyle--}
```
public int getHatchStyle()
```


يحصل على نمط التخطيط لهذه الفرشاة.

**Returns:**
int
### setHatchStyle(int value) {#setHatchStyle-int-}
```
public void setHatchStyle(int value)
```


يضبط نمط التظليل لهذه الفرشاة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

