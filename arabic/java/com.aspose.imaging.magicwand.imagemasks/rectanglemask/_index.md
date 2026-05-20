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
| [RectangleMask(int x, int y, int width, int height)](#RectangleMask-int-int-int-int-) | يُنشئ مثيلاً جديدًا للفئة [RectangleMask](../../com.aspose.imaging.magicwand.imagemasks/rectanglemask) مع النقطة اليسرى العليا المحددة، والعرض والارتفاع. |
| [RectangleMask(Rectangle selectedArea)](#RectangleMask-com.aspose.imaging.Rectangle-) | يُنشئ مثيلاً جديدًا للفئة [RectangleMask](../../com.aspose.imaging.magicwand.imagemasks/rectanglemask) مع المستطيل المحدد. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getSelectionBounds()](#getSelectionBounds--) | يحصل على حدود الجزء المحدد من القناع، بوحدة البكسل. |
| [get_Item(int x, int y)](#get-Item-int-int-) | يحصل على شفافية البكسل المحدد. |
| [inflate(int size)](#inflate-int-) | يوسع هذا القناع بالمقدار المحدد. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | يقص القناع بالمستطيل المحدد. |
| [deepClone()](#deepClone--) | ينشئ كائنًا جديدًا يكون نسخة من المثيل الحالي. |

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

### RectangleMask(int x, int y, int width, int height) {#RectangleMask-int-int-int-int-}
```
public RectangleMask(int x, int y, int width, int height)
```


يُنشئ مثيلاً جديدًا للفئة [RectangleMask](../../com.aspose.imaging.magicwand.imagemasks/rectanglemask) مع النقطة اليسرى العليا المحددة، والعرض والارتفاع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| س | int | الإحداثي x للنقطة اليسرى العليا للمنطقة المحددة. |
| ص | int | الإحداثي y للنقطة اليسرى العليا للمنطقة المحددة. |
| العرض | int | عرض المنطقة المحددة. |
| الارتفاع | int | ارتفاع المنطقة المحددة. |

### RectangleMask(Rectangle selectedArea) {#RectangleMask-com.aspose.imaging.Rectangle-}
```
public RectangleMask(Rectangle selectedArea)
```


يُنشئ مثيلاً جديدًا للفئة [RectangleMask](../../com.aspose.imaging.magicwand.imagemasks/rectanglemask) مع المستطيل المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| selectedArea | [Rectangle](../../com.aspose.imaging/rectangle) | المنطقة المحددة موصوفة كمستطيل. |

### getSelectionBounds() {#getSelectionBounds--}
```
public Rectangle getSelectionBounds()
```


يحصل على حدود الجزء المحدد من القناع، بوحدة البكسل.

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
| س | int | الإحداثي السيني للبكسل. |
| ص | int | الإحداثي الصادي للبكسل. |

**Returns:**
boolean - true إذا كان البكسل المحدد غير شفاف؛ وإلا false.
### inflate(int size) {#inflate-int-}
```
public ImageMask inflate(int size)
```


يوسع هذا القناع بالمقدار المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الحجم | int | المقدار لتوسيع هذه القناع. |

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
java.lang.Object - كائن جديد هو نسخة من هذه المثيل.
