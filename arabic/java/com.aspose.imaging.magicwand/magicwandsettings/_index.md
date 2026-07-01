---
title: "MagicWandSettings"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "فئة إعدادات اختيار Magic Wand."
type: docs
weight: 13
url: /ar/java/com.aspose.imaging.magicwand/magicwandsettings/
---
**Inheritance:**
java.lang.Object
```
public class MagicWandSettings
```

فئة إعدادات اختيار Magic Wand.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [MagicWandSettings(Point point)](#MagicWandSettings-com.aspose.imaging.Point-) | يقوم بإنشاء نسخة جديدة من الفئة [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) class. |
| [MagicWandSettings(int x, int y)](#MagicWandSettings-int-int-) | يقوم بإنشاء نسخة جديدة من الفئة [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) class. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getAreaOfInterest()](#getAreaOfInterest--) | يحصل على حدود المنطقة لعمل الخوارزمية. |
| [setAreaOfInterest(Rectangle value)](#setAreaOfInterest-com.aspose.imaging.Rectangle-) | يضبط حدود المنطقة لعمل الخوارزمية. |
| [getPoint()](#getPoint--) | يحصل على نقطة المرجع لعمل الخوارزمية. |
| [getThreshold()](#getThreshold--) | يحصل على مستوى التحمل لمقارنة ألوان البكسلات. |
| [setThreshold(int value)](#setThreshold-int-) | يضبط مستوى التحمل لمقارنة ألوان البكسلات. |
| [getContiguousMode()](#getContiguousMode--) | يحصل على قيمة تشير إلى ما إذا كانت أداة السحر ستحدد البكسلات المتجاورة فقط. |
| [setContiguousMode(boolean value)](#setContiguousMode-boolean-) | يضبط قيمة تشير إلى ما إذا كانت أداة السحر ستحدد البكسلات المتجاورة فقط. |
| [getDirectionalMode()](#getDirectionalMode--) | يحصل على وضع خوارزمية البحث بالملء المتسلسل: بحث بأربع أو ثمان اتجاهات. |
| [setDirectionalMode(int value)](#setDirectionalMode-int-) | يضبط وضع خوارزمية البحث بالملء المتسلسل: بحث بأربع أو ثمان اتجاهات. |
| [getColorCompareMode()](#getColorCompareMode--) | يحصل على الخوارزمية التي تُقارن بها الألوان. |
| [setColorCompareMode(int value)](#setColorCompareMode-int-) | يضبط الخوارزمية التي تُقارن بها الألوان. |
| [getColorComparisonDelegate()](#getColorComparisonDelegate--) | يحصل على خوارزمية مقارنة الألوان المخصصة إذا تم تعيين `ColorCompareMode`(\#getColorCompareMode.getColorCompareMode/\#setColorCompareMode(int).setColorCompareMode(int)) إلى [ColorComparisonMode.Custom](../../com.aspose.imaging.magicwand/colorcomparisonmode\#Custom). |
| [setColorComparisonDelegate(MagicWandSettings.ColorComparison value)](#setColorComparisonDelegate-com.aspose.imaging.magicwand.MagicWandSettings.ColorComparison-) | يضبط خوارزمية مقارنة الألوان المخصصة إذا تم تعيين `ColorCompareMode`(\#getColorCompareMode.getColorCompareMode/\#setColorCompareMode(int).setColorCompareMode(int)) إلى [ColorComparisonMode.Custom](../../com.aspose.imaging.magicwand/colorcomparisonmode\#Custom). |

## Example: The example shows how to select a simple area of an image based on tone and color of any pixel using Magic Wand tool.

``` java
String imageFilePath = "input.png";
String outputFilePath = "masked.png";
try (RasterImage image = (RasterImage)Image.load(imageFilePath))
{
    // أنشئ قناعًا جديدًا باستخدام أداة العصا السحرية بناءً على درجة اللون ولون البكسل (120, 100) مع عتبة مخصصة مساوية لـ 150
    MagicWandTool
            .select(image, new MagicWandSettings(120, 100) {{ setThreshold(150); }})
            // تطبيق القناع على الصورة
            .apply();

    // احفظ الصورة مع خيار فرض نوع لون الشفافية
    image.save(outputFilePath, new PngOptions()
    {{
        setColorType(PngColorType.TruecolorWithAlpha);
    }});
}

```


## Example: The example shows how to select a complicated area of an image using Magic Wand tool and the ability to interact with masks (invert, union, subtract).

``` java
String imageFilePath = "input.png";
String outputFilePath = "masked-complex.png";
try (RasterImage image = (RasterImage)Image.load(imageFilePath))
{
    // أنشئ قناعًا جديدًا باستخدام أداة العصا السحرية بناءً على درجة اللون ولون البكسل (845, 128)
    MagicWandTool.select(image, new MagicWandSettings(845, 128))
            // ادمج القناع الحالي مع القناع المحدد الذي تم إنشاؤه بواسطة أداة العصا السحرية
            .union(new MagicWandSettings(416, 387))
            // عكس القناع الحالي
            .invert()
            // اطرح القناع المحدد الذي تم إنشاؤه بأداة العصا السحرية مع العتبة المحددة من القناع الحالي
            .subtract(new MagicWandSettings(1482, 346) {{ setThreshold(69); }})
            // اطرح أربعة أقنعة مستطيلة محددة من القناع الحالي واحدًا تلو الآخر
            .subtract(new RectangleMask(0, 0, 800, 150))
            .subtract(new RectangleMask(0, 380, 600, 220))
            .subtract(new RectangleMask(930, 520, 110, 40))
            .subtract(new RectangleMask(1370, 400, 120, 200))
            // تنعيم القناع بالإعدادات المحددة
            .getFeathered(new FeatheringSettings() {{ setSize(3); }})
            // تطبيق القناع على الصورة
            .apply();

    // حفظ الصورة
    image.save(outputFilePath);
}

```

### MagicWandSettings(Point point) {#MagicWandSettings-com.aspose.imaging.Point-}
```
public MagicWandSettings(Point point)
```


يقوم بإنشاء نسخة جديدة من الفئة [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) class.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | نقطة المرجع. |

### MagicWandSettings(int x, int y) {#MagicWandSettings-int-int-}
```
public MagicWandSettings(int x, int y)
```


يقوم بإنشاء نسخة جديدة من الفئة [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) class.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| x | int | الإحداثي السيني لنقطة المرجع. |
| y | int | الإحداثي الصادي لنقطة المرجع. |

### getAreaOfInterest() {#getAreaOfInterest--}
```
public final Rectangle getAreaOfInterest()
```


يحصل على حدود المنطقة لعمل الخوارزمية.

القيمة: المستطيل الذي يمثل حدود منطقة الاهتمام.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - the bounds of the area for algorithm work.
### setAreaOfInterest(Rectangle value) {#setAreaOfInterest-com.aspose.imaging.Rectangle-}
```
public final void setAreaOfInterest(Rectangle value)
```


يضبط حدود المنطقة لعمل الخوارزمية.

القيمة: المستطيل الذي يمثل حدود منطقة الاهتمام.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) | حدود المنطقة لعمل الخوارزمية. |

### getPoint() {#getPoint--}
```
public final Point getPoint()
```


يحصل على نقطة المرجع لعمل الخوارزمية.

القيمة: قيمة `Point`.

**Returns:**
[Point](../../com.aspose.imaging/point) - the reference point for algorithm work.
### getThreshold() {#getThreshold--}
```
public final int getThreshold()
```


يحصل على مستوى التحمل لمقارنة ألوان البكسلات.

القيمة: العتبة لمقارنة الألوان.

**Returns:**
int - مستوى التحمل لمقارنة ألوان البكسلات.
### setThreshold(int value) {#setThreshold-int-}
```
public final void setThreshold(int value)
```


يضبط مستوى التحمل لمقارنة ألوان البكسلات.

القيمة: العتبة لمقارنة الألوان.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int | مستوى التحمل لمقارنة ألوان البكسلات. |

### getContiguousMode() {#getContiguousMode--}
```
public final boolean getContiguousMode()
```


يحصل على قيمة تشير إلى ما إذا كانت أداة السحر ستحدد البكسلات المتجاورة فقط.

القيمة: `true` إذا كان العنصر مفعلاً؛ وإلا `false`. القيمة الافتراضية هي `true`.

**Returns:**
boolean - قيمة تشير إلى ما إذا كانت أداة السحر ستحدد فقط البكسلات المتجاورة.
### setContiguousMode(boolean value) {#setContiguousMode-boolean-}
```
public final void setContiguousMode(boolean value)
```


يضبط قيمة تشير إلى ما إذا كانت أداة السحر ستحدد البكسلات المتجاورة فقط.

القيمة: `true` إذا كان العنصر مفعلاً؛ وإلا `false`. القيمة الافتراضية هي `true`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | boolean | قيمة تشير إلى ما إذا كانت أداة السحر ستحدد فقط البكسلات المتجاورة. |

### getDirectionalMode() {#getDirectionalMode--}
```
public final int getDirectionalMode()
```


يحصل على وضع خوارزمية البحث بالملء المتسلسل: بحث بأربع أو ثمان اتجاهات.

القيمة: وضع خوارزمية البحث بالملء المتسلسل.

**Returns:**
int - وضع خوارزمية البحث بالملء المتسلسل: بحث بأربع أو ثمان اتجاهات.
### setDirectionalMode(int value) {#setDirectionalMode-int-}
```
public final void setDirectionalMode(int value)
```


يضبط وضع خوارزمية البحث بالملء المتسلسل: بحث بأربع أو ثمان اتجاهات.

القيمة: وضع خوارزمية البحث بالملء المتسلسل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int | وضع خوارزمية البحث بالملء المتسلسل: بحث بأربع أو ثمان اتجاهات. |

### getColorCompareMode() {#getColorCompareMode--}
```
public final int getColorCompareMode()
```


يحصل على الخوارزمية التي تُقارن بها الألوان.

القيمة: وضع مقارنة الألوان.

**Returns:**
int - الخوارزمية التي تُقارن بها الألوان.
### setColorCompareMode(int value) {#setColorCompareMode-int-}
```
public final void setColorCompareMode(int value)
```


يضبط الخوارزمية التي تُقارن بها الألوان.

القيمة: وضع مقارنة الألوان.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int | الخوارزمية التي تُقارن بها الألوان. |

### getColorComparisonDelegate() {#getColorComparisonDelegate--}
```
public final MagicWandSettings.ColorComparison getColorComparisonDelegate()
```


يحصل على خوارزمية مقارنة الألوان المخصصة إذا تم تعيين `ColorCompareMode`(\#getColorCompareMode.getColorCompareMode/\#setColorCompareMode(int).setColorCompareMode(int)) إلى [ColorComparisonMode.Custom](../../com.aspose.imaging.magicwand/colorcomparisonmode\#Custom).

القيمة: المندوب لمقارنة الألوان.

**Returns:**
[ColorComparison](../../com.aspose.imaging.magicwand/colorcomparison) - the custom color comparison algorithm if `ColorCompareMode`(\#getColorCompareMode.getColorCompareMode/\#setColorCompareMode(int).setColorCompareMode(int)) is set to [ColorComparisonMode.Custom](../../com.aspose.imaging.magicwand/colorcomparisonmode\#Custom).
### setColorComparisonDelegate(MagicWandSettings.ColorComparison value) {#setColorComparisonDelegate-com.aspose.imaging.magicwand.MagicWandSettings.ColorComparison-}
```
public final void setColorComparisonDelegate(MagicWandSettings.ColorComparison value)
```


يضبط خوارزمية مقارنة الألوان المخصصة إذا تم تعيين `ColorCompareMode`(\#getColorCompareMode.getColorCompareMode/\#setColorCompareMode(int).setColorCompareMode(int)) إلى [ColorComparisonMode.Custom](../../com.aspose.imaging.magicwand/colorcomparisonmode\#Custom).

القيمة: المندوب لمقارنة الألوان.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [ColorComparison](../../com.aspose.imaging.magicwand/colorcomparison) | خوارزمية مقارنة الألوان المخصصة إذا تم تعيين `ColorCompareMode`(\#getColorCompareMode.getColorCompareMode/\#setColorCompareMode(int).setColorCompareMode(int)) إلى [ColorComparisonMode.Custom](../../com.aspose.imaging.magicwand/colorcomparisonmode\#Custom). |

