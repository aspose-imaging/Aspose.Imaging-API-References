---
title: "RectangleMask"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يصف قناعًا مستطيلًا."
type: docs
weight: 17
url: /ar/java/com.aspose.imaging.magicwand.imagemasks/rectanglemask/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.magicwand.imagemasks.ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask)
```
public class RectangleMask extends ImageMask
```

يصف قناعًا مستطيلًا.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [RectangleMask(int x, int y, int width, int height)](#RectangleMask-int-int-int-int-) | ينشئ مثيلاً جديداً من الفئة [RectangleMask](../../com.aspose.imaging.magicwand.imagemasks/rectanglemask) مع النقطة اليسرى العليا المحددة والعرض والارتفاع. |
| [RectangleMask(Rectangle selectedArea)](#RectangleMask-com.aspose.imaging.Rectangle-) | ينشئ مثيلاً جديداً من الفئة [RectangleMask](../../com.aspose.imaging.magicwand.imagemasks/rectanglemask) مع المستطيل المحدد. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getSelectionBounds()](#getSelectionBounds--) | يحصل على حدود الجزء المحدد من القناع، بوحدات البكسل. |
| [get_Item(int x, int y)](#get-Item-int-int-) | يحصل على شفافية البكسل المحدد. |
| [inflate(int size)](#inflate-int-) | يضخم هذه القناع بالمقدار المحدد. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | يقص القناع بالمستطيل المحدد. |
| [deepClone()](#deepClone--) | ينشئ كائنًا جديدًا يكون نسخة من المثيل الحالي. |

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

### RectangleMask(int x, int y, int width, int height) {#RectangleMask-int-int-int-int-}
```
public RectangleMask(int x, int y, int width, int height)
```


ينشئ مثيلاً جديداً من الفئة [RectangleMask](../../com.aspose.imaging.magicwand.imagemasks/rectanglemask) مع النقطة اليسرى العليا المحددة والعرض والارتفاع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| x | int | الإحداثي س للنقطة اليسرى العليا للمنطقة المحددة. |
| y | int | الإحداثي ص للنقطة اليسرى العليا للمنطقة المحددة. |
| width | int | عرض المنطقة المحددة. |
| height | int | ارتفاع المنطقة المحددة. |

### RectangleMask(Rectangle selectedArea) {#RectangleMask-com.aspose.imaging.Rectangle-}
```
public RectangleMask(Rectangle selectedArea)
```


ينشئ مثيلاً جديداً من الفئة [RectangleMask](../../com.aspose.imaging.magicwand.imagemasks/rectanglemask) مع المستطيل المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| selectedArea | [Rectangle](../../com.aspose.imaging/rectangle) | المنطقة المحددة مُحددة كمستطيل. |

### getSelectionBounds() {#getSelectionBounds--}
```
public Rectangle getSelectionBounds()
```


يحصل على حدود الجزء المحدد من القناع، بوحدات البكسل.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - the bounds of the selected part of the mask, in pixels.
### get_Item(int x, int y) {#get-Item-int-int-}
```
public boolean get_Item(int x, int y)
```


يحصل على شفافية البكسل المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| x | int | الإحداثي السيني للبكسل. |
| y | int | الإحداثي الصادي للبكسل. |

**Returns:**
boolean - true إذا كان البكسل المحدد غير شفاف؛ وإلا false.
### inflate(int size) {#inflate-int-}
```
public ImageMask inflate(int size)
```


يضخم هذه القناع بالمقدار المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| size | int | المقدار لتضخيم هذه القناع. |

**Returns:**
[ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) - An inflated RectangleMask as ImageMask.
### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public ImageMask crop(Rectangle rectangle)
```


يقص القناع بالمستطيل المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | المستطيل المحدد. |

**Returns:**
[ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) - A cropped RectangleMask as ImageMask.
### deepClone() {#deepClone--}
```
public Object deepClone()
```


ينشئ كائنًا جديدًا يكون نسخة من المثيل الحالي.

**Returns:**
java.lang.Object - كائن جديد يكون نسخة من هذا المثيل.
