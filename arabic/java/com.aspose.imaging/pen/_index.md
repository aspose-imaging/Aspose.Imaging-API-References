---
title: "Pen"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يحدد كائنًا يُستخدم لرسم الخطوط والمنحنيات والأشكال."
type: docs
weight: 81
url: /ar/java/com.aspose.imaging/pen/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.TransparencySupporter](../../com.aspose.imaging/transparencysupporter)
```
public class Pen extends TransparencySupporter
```

يحدد كائنًا يُستخدم لرسم الخطوط والمنحنيات والأشكال.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [Pen(Color color)](#Pen-com.aspose.imaging.Color-) | ينشئ نسخة جديدة من فئة `Pen` باللون المحدد. |
| [Pen(Color color, float width)](#Pen-com.aspose.imaging.Color-float-) | ينشئ نسخة جديدة من فئة `Pen` بالخصائص المحددة `Color` و `Pen.Width`. |
| [Pen(Brush brush)](#Pen-com.aspose.imaging.Brush-) | ينشئ نسخة جديدة من فئة `Pen` بالـ `Brush` المحدد. |
| [Pen(Brush brush, float width)](#Pen-com.aspose.imaging.Brush-float-) | ينشئ نسخة جديدة من فئة `Pen` بالـ `Brush` و `Pen.Width` المحددين. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getWidth()](#getWidth--) | يحصل على عرض هذا `Pen` بوحدات كائن Graphics المستخدم في الرسم. |
| [setWidth(float value)](#setWidth-float-) | يضبط عرض هذا `Pen` بوحدات كائن Graphics المستخدم في الرسم. |
| [getStartCap()](#getStartCap--) | يحصل على نمط القمة المستخدم في بداية الخطوط المرسومة بهذا `Pen`. |
| [setStartCap(int value)](#setStartCap-int-) | يضبط نمط القمة المستخدم في بداية الخطوط المرسومة بهذا `Pen`. |
| [getEndCap()](#getEndCap--) | يحصل على نمط القمة المستخدم في نهاية الخطوط المرسومة بهذا `Pen`. |
| [setEndCap(int value)](#setEndCap-int-) | يضبط نمط القمة المستخدم في نهاية الخطوط المرسومة بهذا `Pen`. |
| [getDashCap()](#getDashCap--) | يحصل على نمط القمة المستخدم في نهاية الشرطات التي تشكل الخطوط المتقطعة المرسومة بهذا `Pen`. |
| [setDashCap(int value)](#setDashCap-int-) | يضبط نمط الغطاء المستخدم في نهاية الشرطات التي تشكل الخطوط المتقطعة المرسومة بهذا `Pen`. |
| [getLineJoin()](#getLineJoin--) | يحصل على نمط الوصل لنهايات خطين متتاليين مرسومين بهذا `Pen`. |
| [setLineJoin(int value)](#setLineJoin-int-) | يضبط نمط الوصل لنهايات خطين متتاليين مرسومين بهذا `Pen`. |
| [getCustomStartCap()](#getCustomStartCap--) | يحصل على غطاء مخصص لاستخدامه في بداية الخطوط المرسومة بهذا `Pen`. |
| [setCustomStartCap(CustomLineCap value)](#setCustomStartCap-com.aspose.imaging.CustomLineCap-) | يضبط غطاءً مخصصًا لاستخدامه في بداية الخطوط المرسومة بهذا `Pen`. |
| [getCustomEndCap()](#getCustomEndCap--) | يحصل على غطاء مخصص لاستخدامه في نهاية الخطوط المرسومة بهذا `Pen`. |
| [setCustomEndCap(CustomLineCap value)](#setCustomEndCap-com.aspose.imaging.CustomLineCap-) | يضبط غطاءً مخصصًا لاستخدامه في نهاية الخطوط المرسومة بهذا `Pen`. |
| [getMiterLimit()](#getMiterLimit--) | يحصل على حد سمك الوصل عند زاوية ميتريّة. |
| [setMiterLimit(float value)](#setMiterLimit-float-) | يضبط حد سمك الوصل عند زاوية ميتريّة. |
| [getAlignment()](#getAlignment--) | يحصل على المحاذاة لهذا `Pen`. |
| [setAlignment(int value)](#setAlignment-int-) | يضبط المحاذاة لهذا `Pen`. |
| [getTransform()](#getTransform--) | يحصل على نسخة من التحويل الهندسي لهذا `Pen`. |
| [setTransform(Matrix value)](#setTransform-com.aspose.imaging.Matrix-) | يضبط نسخة من التحويل الهندسي لهذا `Pen`. |
| [getPenType()](#getPenType--) | يحصل على نمط الخطوط المرسومة بهذا `Pen`. |
| [getColor()](#getColor--) | يحصل على لون هذا `Pen`. |
| [setColor(Color value)](#setColor-com.aspose.imaging.Color-) | يضبط لون هذا `Pen`. |
| [getBrush()](#getBrush--) | يحصل على الـ `Brush` الذي يحدد خصائص هذا `Pen`. |
| [setBrush(Brush value)](#setBrush-com.aspose.imaging.Brush-) | يضبط الـ `Brush` الذي يحدد خصائص هذا `Pen`. |
| [getDashStyle()](#getDashStyle--) | يحصل على النمط المستخدم للخطوط المتقطعة المرسومة بهذا `Pen`. |
| [setDashStyle(int value)](#setDashStyle-int-) | يضبط النمط المستخدم للخطوط المتقطعة المرسومة بهذا `Pen`. |
| [getDashOffset()](#getDashOffset--) | يحصل على المسافة من بداية الخط إلى بداية نمط الشرطات. |
| [setDashOffset(float value)](#setDashOffset-float-) | يضبط المسافة من بداية الخط إلى بداية نمط الشرطات. |
| [getDashPattern()](#getDashPattern--) | يحصل على مصفوفة من الشرطات والمسافات المخصصة. |
| [setDashPattern(float[] value)](#setDashPattern-float---) | يضبط مصفوفة من الشرطات والمسافات المخصصة. |
| [getCompoundArray()](#getCompoundArray--) | يحصل على مصفوفة من القيم التي تحدد قلمًا مركبًا. |
| [setCompoundArray(float[] value)](#setCompoundArray-float---) | يضبط مصفوفة من القيم التي تحدد قلمًا مركبًا. |
| [setLineCap(int startCap, int endCap, int dashCap)](#setLineCap-int-int-int-) | يضبط القيم التي تحدد نمط الغطاء المستخدم لإنهاء الخطوط المرسومة بواسطة هذا `Pen`. |
| [resetTransform()](#resetTransform--) | يعيد تعيين مصفوفة التحويل الهندسي لهذا `Pen` إلى الهوية. |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.imaging.Matrix-) | يضرب مصفوفة التحويل لهذا `Pen` بالمصفوفة المحددة `Matrix`. |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.imaging.Matrix-int-) | يضرب مصفوفة التحويل لهذا `Pen` بالمصفوفة المحددة `Matrix` بالترتيب المحدد. |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | ينقل التحويل الهندسي المحلي بالأبعاد المحددة. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | ينقل التحويل الهندسي المحلي بالأبعاد المحددة بالترتيب المحدد. |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | يقوم بتكبير التحويل الهندسي المحلي بالعوامل المحددة. |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | يقوم بتكبير التحويل الهندسي المحلي بالعوامل المحددة بالترتيب المحدد. |
| [rotateTransform(float angle)](#rotateTransform-float-) | يدور التحويل الهندسي المحلي بالزاوية المحددة. |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | يدور التحويل الهندسي المحلي بالزاوية المحددة بالترتيب المحدد. |
| [equals(Object o)](#equals-java.lang.Object-) | تحقق مما إذا كانت الكائنات متساوية. |
| [hashCode()](#hashCode--) |  |

## Example: This example shows the creation and usage Pen objects.
يوضح هذا المثال إنشاء واستخدام كائنات Pen. ينشئ المثال صورة جديدة ويرسم مستطيلات على سطح الصورة.
``` java

// أنشئ مثيلاً من BmpOptions واضبط خصائصه المتنوعة.
com.aspose.imaging.imageoptions.BmpOptions bmpOptions = new com.aspose.imaging.imageoptions.BmpOptions();
bmpOptions.setBitsPerPixel(24);

// أنشئ مثيلاً من FileCreateSource وعيّنه كخاصية Source لمثيل BmpOptions.
// المعامل البولياني الثاني يحدد ما إذا كان الملف الذي سيتم إنشاؤه مؤقتًا أم لا.
bmpOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("C:\\temp\\sample.bmp", false));

// إنشاء نسخة من Image في المسار المحدد
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(bmpOptions, 500, 500);
try {
    // إنشاء نسخة من Graphics وتهيئتها بكائن Image
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);

    // امسح سطح Graphics باللون الأبيض
    graphics.clear(com.aspose.imaging.Color.getWhite());

    // إنشاء نسخة من Pen باللون الأحمر وعرض 5
    com.aspose.imaging.Pen pen = new com.aspose.imaging.Pen(com.aspose.imaging.Color.getRed(), 5);

    // إنشاء نسخة من HatchBrush وتعيين خصائصه
    com.aspose.imaging.brushes.HatchBrush brush = new com.aspose.imaging.brushes.HatchBrush();
    brush.setBackgroundColor(com.aspose.imaging.Color.getWheat());
    brush.setForegroundColor(com.aspose.imaging.Color.getRed());

    // إنشاء نسخة من Pen وتهيئتها بكائن HatchBrush والعرض
    com.aspose.imaging.Pen brushedpen = new com.aspose.imaging.Pen(brush, 5);

    // ارسم مستطيلات بتحديد كائن Pen
    graphics.drawRectangles(pen, new com.aspose.imaging.Rectangle[]
            {
                    new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(210, 210), new com.aspose.imaging.Size(100, 100)),
                    new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(110, 110), new com.aspose.imaging.Size(100, 100)),
                    new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(310, 310), new com.aspose.imaging.Size(100, 100))
            });

    // ارسم مستطيلات بتحديد كائن Pen
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

### Pen(Color color) {#Pen-com.aspose.imaging.Color-}
```
public Pen(Color color)
```


ينشئ نسخة جديدة من فئة `Pen` باللون المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| color | [Color](../../com.aspose.imaging/color) | `Color` بنية تشير إلى لون هذا `Pen`. |

### Pen(Color color, float width) {#Pen-com.aspose.imaging.Color-float-}
```
public Pen(Color color, float width)
```


ينشئ نسخة جديدة من فئة `Pen` بالخصائص المحددة `Color` و `Pen.Width`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| color | [Color](../../com.aspose.imaging/color) | `Color` بنية تشير إلى لون هذا `Pen`. |
| width | float | قيمة تشير إلى عرض هذا `Pen`. |

### Pen(Brush brush) {#Pen-com.aspose.imaging.Brush-}
```
public Pen(Brush brush)
```


ينشئ نسخة جديدة من فئة `Pen` بالـ `Brush` المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.imaging/brush) | `Brush` يحدد خصائص التعبئة لهذا `Pen`. |

### Pen(Brush brush, float width) {#Pen-com.aspose.imaging.Brush-float-}
```
public Pen(Brush brush, float width)
```


ينشئ نسخة جديدة من فئة `Pen` بالـ `Brush` و `Pen.Width` المحددين.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.imaging/brush) | `Brush` يحدد خصائص هذا `Pen`. |
| width | float | عرض الـ `Pen` الجديد. |

### getWidth() {#getWidth--}
```
public float getWidth()
```


يحصل على عرض هذا `Pen` بوحدات كائن Graphics المستخدم في الرسم.

**Returns:**
float - عرض هذا `Pen`.
### setWidth(float value) {#setWidth-float-}
```
public void setWidth(float value)
```


يضبط عرض هذا `Pen` بوحدات كائن Graphics المستخدم في الرسم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | float | عرض هذا `Pen`. |

### getStartCap() {#getStartCap--}
```
public int getStartCap()
```


يحصل على نمط القمة المستخدم في بداية الخطوط المرسومة بهذا `Pen`.

**Returns:**
int - إحدى قيم `LineCap` التي تمثل نمط الغطاء المستخدم في بداية الخطوط المرسومة بهذا `Pen`.
### setStartCap(int value) {#setStartCap-int-}
```
public void setStartCap(int value)
```


يضبط نمط القمة المستخدم في بداية الخطوط المرسومة بهذا `Pen`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int | إحدى قيم `LineCap` التي تمثل نمط الغطاء المستخدم في بداية الخطوط المرسومة بهذا `Pen`. |

### getEndCap() {#getEndCap--}
```
public int getEndCap()
```


يحصل على نمط القمة المستخدم في نهاية الخطوط المرسومة بهذا `Pen`.

**Returns:**
int - إحدى قيم `LineCap` التي تمثل نمط الغطاء المستخدم في نهاية الخطوط المرسومة بهذا `Pen`.
### setEndCap(int value) {#setEndCap-int-}
```
public void setEndCap(int value)
```


يضبط نمط القمة المستخدم في نهاية الخطوط المرسومة بهذا `Pen`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int | إحدى قيم `LineCap` التي تمثل نمط الغطاء المستخدم في نهاية الخطوط المرسومة بهذا `Pen`. |

### getDashCap() {#getDashCap--}
```
public int getDashCap()
```


يحصل على نمط القمة المستخدم في نهاية الشرطات التي تشكل الخطوط المتقطعة المرسومة بهذا `Pen`.

**Returns:**
int - إحدى قيم `DashCap` التي تمثل نمط الغطاء المستخدم في بداية ونهاية الشرطات التي تشكل الخطوط المتقطعة المرسومة بهذا `Pen`.
### setDashCap(int value) {#setDashCap-int-}
```
public void setDashCap(int value)
```


يضبط نمط الغطاء المستخدم في نهاية الشرطات التي تشكل الخطوط المتقطعة المرسومة بهذا `Pen`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int | إحدى قيم `DashCap` التي تمثل نمط الغطاء المستخدم في بداية ونهاية الشرطات التي تشكل الخطوط المتقطعة المرسومة بهذا `Pen`. |

### getLineJoin() {#getLineJoin--}
```
public int getLineJoin()
```


يحصل على نمط الوصل لنهايات خطين متتاليين مرسومين بهذا `Pen`.

**Returns:**
int - `LineJoin` الذي يمثل نمط الوصل لنهايات خطين متتاليين مرسومين بهذا `Pen`.
### setLineJoin(int value) {#setLineJoin-int-}
```
public void setLineJoin(int value)
```


يضبط نمط الوصل لنهايات خطين متتاليين مرسومين بهذا `Pen`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int | `LineJoin` الذي يمثل نمط الوصل لنهايات خطين متتاليين مرسومين بهذا `Pen`. |

### getCustomStartCap() {#getCustomStartCap--}
```
public CustomLineCap getCustomStartCap()
```


يحصل على غطاء مخصص لاستخدامه في بداية الخطوط المرسومة بهذا `Pen`.

**Returns:**
[CustomLineCap](../../com.aspose.imaging/customlinecap) - A `CustomLineCap` that represents the cap used at the beginning of lines drawn with this `Pen`.
### setCustomStartCap(CustomLineCap value) {#setCustomStartCap-com.aspose.imaging.CustomLineCap-}
```
public void setCustomStartCap(CustomLineCap value)
```


يضبط غطاءً مخصصًا لاستخدامه في بداية الخطوط المرسومة بهذا `Pen`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [CustomLineCap](../../com.aspose.imaging/customlinecap) | `CustomLineCap` الذي يمثل الغطاء المستخدم في بداية الخطوط المرسومة بهذا `Pen`. |

### getCustomEndCap() {#getCustomEndCap--}
```
public CustomLineCap getCustomEndCap()
```


يحصل على غطاء مخصص لاستخدامه في نهاية الخطوط المرسومة بهذا `Pen`.

**Returns:**
[CustomLineCap](../../com.aspose.imaging/customlinecap) - A `CustomLineCap` that represents the cap used at the end of lines drawn with this `Pen`.
### setCustomEndCap(CustomLineCap value) {#setCustomEndCap-com.aspose.imaging.CustomLineCap-}
```
public void setCustomEndCap(CustomLineCap value)
```


يضبط غطاءً مخصصًا لاستخدامه في نهاية الخطوط المرسومة بهذا `Pen`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [CustomLineCap](../../com.aspose.imaging/customlinecap) | `CustomLineCap` الذي يمثل الغطاء المستخدم في نهاية الخطوط المرسومة بهذا `Pen`. |

### getMiterLimit() {#getMiterLimit--}
```
public float getMiterLimit()
```


يحصل على حد سمك الوصل عند زاوية ميتريّة.

**Returns:**
float - الحد الأقصى لسماكة الوصل عند زاوية ميتير.
### setMiterLimit(float value) {#setMiterLimit-float-}
```
public void setMiterLimit(float value)
```


يضبط حد سمك الوصل عند زاوية ميتريّة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | float | الحد الأقصى لسماكة الوصل عند زاوية ميتير. |

### getAlignment() {#getAlignment--}
```
public int getAlignment()
```


يحصل على المحاذاة لهذا `Pen`.

**Returns:**
int - `PenAlignment` الذي يمثل المحاذاة لهذا `Pen`.
### setAlignment(int value) {#setAlignment-int-}
```
public void setAlignment(int value)
```


يضبط المحاذاة لهذا `Pen`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int | `PenAlignment` الذي يمثل المحاذاة لهذا `Pen`. |

### getTransform() {#getTransform--}
```
public Matrix getTransform()
```


يحصل على نسخة من التحويل الهندسي لهذا `Pen`.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix) - A copy of the `Matrix` that represents the geometric transformation for this `Pen`.
### setTransform(Matrix value) {#setTransform-com.aspose.imaging.Matrix-}
```
public void setTransform(Matrix value)
```


يضبط نسخة من التحويل الهندسي لهذا `Pen`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) | نسخة من `Matrix` التي تمثل التحويل الهندسي لهذا `Pen`. |

### getPenType() {#getPenType--}
```
public int getPenType()
```


يحصل على نمط الخطوط المرسومة بهذا `Pen`.

**Returns:**
int - تعداد `PenType` الذي يحدد نمط الخطوط المرسومة بهذا `Pen`.
### getColor() {#getColor--}
```
public Color getColor()
```


يحصل على لون هذا `Pen`.

**Returns:**
[Color](../../com.aspose.imaging/color) - A `Color` structure that represents the color of this `Pen`.
### setColor(Color value) {#setColor-com.aspose.imaging.Color-}
```
public void setColor(Color value)
```


يضبط لون هذا `Pen`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | هيكل `Color` الذي يمثل لون هذا `Pen`. |

### getBrush() {#getBrush--}
```
public Brush getBrush()
```


يحصل على الـ `Brush` الذي يحدد خصائص هذا `Pen`.

**Returns:**
[Brush](../../com.aspose.imaging/brush) - A `Brush` that determines attributes of this `Pen`.
### setBrush(Brush value) {#setBrush-com.aspose.imaging.Brush-}
```
public void setBrush(Brush value)
```


يضبط الـ `Brush` الذي يحدد خصائص هذا `Pen`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Brush](../../com.aspose.imaging/brush) | `Brush` الذي يحدد خصائص هذا `Pen`. |

### getDashStyle() {#getDashStyle--}
```
public int getDashStyle()
```


يحصل على النمط المستخدم للخطوط المتقطعة المرسومة بهذا `Pen`.

**Returns:**
int - `DashStyle` الذي يمثل النمط المستخدم للخطوط المتقطعة المرسومة بهذا `Pen`.
### setDashStyle(int value) {#setDashStyle-int-}
```
public void setDashStyle(int value)
```


يضبط النمط المستخدم للخطوط المتقطعة المرسومة بهذا `Pen`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int | `DashStyle` الذي يمثل النمط المستخدم للخطوط المتقطعة المرسومة بهذا `Pen`. |

### getDashOffset() {#getDashOffset--}
```
public float getDashOffset()
```


يحصل على المسافة من بداية الخط إلى بداية نمط الشرطات.

**Returns:**
float - المسافة من بداية الخط إلى بداية نمط الشرطة.
### setDashOffset(float value) {#setDashOffset-float-}
```
public void setDashOffset(float value)
```


يضبط المسافة من بداية الخط إلى بداية نمط الشرطات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | float | المسافة من بداية الخط إلى بداية نمط الشرطة. |

### getDashPattern() {#getDashPattern--}
```
public float[] getDashPattern()
```


يحصل على مصفوفة من الشرطات والمسافات المخصصة.

**Returns:**
float[] - مصفوفة من الأعداد الحقيقية التي تحدد أطوال الشرطات والمسافات المتناوبة في الخطوط المتقطعة.
### setDashPattern(float[] value) {#setDashPattern-float---}
```
public void setDashPattern(float[] value)
```


يضبط مصفوفة من الشرطات والمسافات المخصصة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | float[] | مصفوفة من الأعداد الحقيقية التي تحدد أطوال الشرطات والمسافات المتناوبة في الخطوط المتقطعة. |

### getCompoundArray() {#getCompoundArray--}
```
public float[] getCompoundArray()
```


يحصل على مصفوفة من القيم التي تحدد قلم مركب. القلم المركب يرسم خطًا مركبًا مكوّنًا من خطوط متوازية وفراغات.

**Returns:**
float[] - مصفوفة من الأعداد الحقيقية التي تحدد مصفوفة المركب. يجب أن تكون عناصر المصفوفة بترتيب تصاعدي، لا تقل عن 0، ولا تزيد عن 1.
### setCompoundArray(float[] value) {#setCompoundArray-float---}
```
public void setCompoundArray(float[] value)
```


يضبط مصفوفة من القيم التي تحدد قلمًا مركبًا. القلم المركب يرسم خطًا مركبًا مكوّنًا من خطوط متوازية وفراغات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | float[] | مصفوفة من الأعداد الحقيقية التي تحدد مصفوفة المركب. يجب أن تكون عناصر المصفوفة بترتيب تصاعدي، لا تقل عن 0، ولا تزيد عن 1. |

### setLineCap(int startCap, int endCap, int dashCap) {#setLineCap-int-int-int-}
```
public void setLineCap(int startCap, int endCap, int dashCap)
```


يضبط القيم التي تحدد نمط الغطاء المستخدم لإنهاء الخطوط المرسومة بواسطة هذا `Pen`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| startCap | int | `LineCap` التي تمثل نمط القمة لاستخدامه في بداية الخطوط المرسومة بهذا `Pen`. |
| endCap | int | `LineCap` التي تمثل نمط القمة لاستخدامه في نهاية الخطوط المرسومة بهذا `Pen`. |
| dashCap | int | `LineCap` التي تمثل نمط القمة لاستخدامه في بداية أو نهاية الخطوط المتقطعة المرسومة بهذا `Pen`. |

### resetTransform() {#resetTransform--}
```
public void resetTransform()
```


يعيد تعيين مصفوفة التحويل الهندسي لهذا `Pen` إلى الهوية.

### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.imaging.Matrix-}
```
public void multiplyTransform(Matrix matrix)
```


يضرب مصفوفة التحويل لهذا `Pen` بالمصفوفة المحددة `Matrix`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | كائن `Matrix` الذي يُستخدم لضرب مصفوفة التحويل. |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.imaging.Matrix-int-}
```
public void multiplyTransform(Matrix matrix, int order)
```


يضرب مصفوفة التحويل لهذا `Pen` بالمصفوفة المحددة `Matrix` بالترتيب المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | `Matrix` الذي يُستخدم لضرب مصفوفة التحويل. |
| الترتيب | int | الترتيب الذي يتم فيه تنفيذ عملية الضرب. |

### translateTransform(float dx, float dy) {#translateTransform-float-float-}
```
public void translateTransform(float dx, float dy)
```


يُترجم التحويل الهندسي المحلي بالأبعاد المحددة. تُضيف هذه الطريقة الإزاحة إلى التحويل في البداية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| dx | float | قيمة الإزاحة في الاتجاه x. |
| dy | float | قيمة الإزاحة في الاتجاه y. |

### translateTransform(float dx, float dy, int order) {#translateTransform-float-float-int-}
```
public void translateTransform(float dx, float dy, int order)
```


ينقل التحويل الهندسي المحلي بالأبعاد المحددة بالترتيب المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| dx | float | قيمة الإزاحة في الاتجاه x. |
| dy | float | قيمة الإزاحة في الاتجاه y. |
| الترتيب | int | الترتيب (إضافة في البداية أو في النهاية) الذي يُطبق فيه الإزاحة. |

### scaleTransform(float sx, float sy) {#scaleTransform-float-float-}
```
public void scaleTransform(float sx, float sy)
```


يقوم بتكبير التحويل الهندسي المحلي بالعوامل المحددة. تُضيف هذه الطريقة مصفوفة التكبير إلى التحويل في البداية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| sx | float | العامل الذي يُستخدم لتكبير التحويل في اتجاه المحور x. |
| sy | float | العامل الذي يُستخدم لتكبير التحويل في اتجاه المحور y. |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public void scaleTransform(float sx, float sy, int order)
```


يقوم بتكبير التحويل الهندسي المحلي بالعوامل المحددة بالترتيب المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| sx | float | العامل الذي يُستخدم لتكبير التحويل في اتجاه المحور x. |
| sy | float | العامل الذي يُستخدم لتكبير التحويل في اتجاه المحور y. |
| الترتيب | int | `MatrixOrder` التي تحدد ما إذا كان سيتم إضافة مصفوفة التكبير في النهاية أو في البداية. |

### rotateTransform(float angle) {#rotateTransform-float-}
```
public void rotateTransform(float angle)
```


يدور التحويل الهندسي المحلي بالزاوية المحددة. تُضيف هذه الطريقة الدوران إلى التحويل في البداية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| angle | float | زاوية الدوران. |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public void rotateTransform(float angle, int order)
```


يدور التحويل الهندسي المحلي بالزاوية المحددة بالترتيب المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| angle | float | زاوية الدوران. |
| الترتيب | int | `MatrixOrder` التي تحدد ما إذا كان سيتم إضافة مصفوفة الدوران في النهاية أو في البداية. |

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
int
