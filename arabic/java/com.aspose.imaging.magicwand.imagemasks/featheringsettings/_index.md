---
title: "FeatheringSettings"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "فئة إعدادات التنعيم."
type: docs
weight: 13
url: /ar/java/com.aspose.imaging.magicwand.imagemasks/featheringsettings/
---
**Inheritance:**
java.lang.Object
```
public class FeatheringSettings
```

فئة إعدادات التنعيم.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [FeatheringSettings()](#FeatheringSettings--) | يُنشئ مثيلًا جديدًا للفئة [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings). |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getSize()](#getSize--) | يحصل على حجم التنعيم. |
| [setSize(int value)](#setSize-int-) | يضبط حجم التنعيم. |
| [getMode()](#getMode--) | يحصل على وضع خوارزمية التنعيم. |
| [setMode(int value)](#setMode-int-) | يضبط وضع خوارزمية التنعيم. |

## Example: The example shows how to select a complicated area of an image using Magic Wand tool and the ability to interact with masks (invert, union, subtract).

``` java
String imageFilePath = "input.png";
String outputFilePath = "masked-complex.png";
try (RasterImage image = (RasterImage)Image.load(imageFilePath))
{
    // أنشئ قناعًا جديدًا باستخدام أداة العصا السحرية بناءً على نغمة ولون البكسل (845, 128)
    MagicWandTool.select(image, new MagicWandSettings(845, 128))
            // ادمج القناع الحالي مع القناع المحدد الذي تم إنشاؤه بأداة العصا السحرية
            .union(new MagicWandSettings(416, 387))
            // اعكس القناع الحالي
            .invert()
            // اطرح القناع المحدد الذي تم إنشاؤه بأداة العصا السحرية مع العتبة المحددة من القناع الحالي
            .subtract(new MagicWandSettings(1482, 346) {{ setThreshold(69); }})
            // اطرح أربعة أقنعة مستطيلة محددة من القناع الحالي واحدًا تلو الآخر
            .subtract(new RectangleMask(0, 0, 800, 150))
            .subtract(new RectangleMask(0, 380, 600, 220))
            .subtract(new RectangleMask(930, 520, 110, 40))
            .subtract(new RectangleMask(1370, 400, 120, 200))
            // نقّح القناع باستخدام الإعدادات المحددة
            .getFeathered(new FeatheringSettings() {{ setSize(3); }})
            // طبق القناع على الصورة
            .apply();

    // احفظ الصورة
    image.save(outputFilePath);
}

```

### FeatheringSettings() {#FeatheringSettings--}
```
public FeatheringSettings()
```


يُنشئ مثيلًا جديدًا للفئة [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings).

### getSize() {#getSize--}
```
public final int getSize()
```


يحصل على حجم التنعيم.

القيمة: حجم فرشاة التنعيم بالبكسل.

**Returns:**
int - حجم التنعيم.
### setSize(int value) {#setSize-int-}
```
public final void setSize(int value)
```


يضبط حجم التنعيم.

القيمة: حجم فرشاة التنعيم بالبكسل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | حجم التنعيم. |

### getMode() {#getMode--}
```
public final int getMode()
```


يحصل على وضع خوارزمية التنعيم.

القيمة: وضع خوارزمية التنعيم.

**Returns:**
int - وضع خوارزمية التنعيم.
### setMode(int value) {#setMode-int-}
```
public final void setMode(int value)
```


يضبط وضع خوارزمية التنعيم.

القيمة: وضع خوارزمية التنعيم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int | وضع خوارزمية الريش. |

