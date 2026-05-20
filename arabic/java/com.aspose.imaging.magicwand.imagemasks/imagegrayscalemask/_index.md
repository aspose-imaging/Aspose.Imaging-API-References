---
title: "ImageGrayscaleMask"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يصف قناع صورة بتدرج الرمادي."
type: docs
weight: 15
url: /ar/java/com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.magicwand.imagemasks.IImageMask](../../com.aspose.imaging.magicwand.imagemasks/iimagemask)
```
public class ImageGrayscaleMask implements IImageMask
```

يصف قناع صورة بتدرج الرمادي.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [ImageGrayscaleMask(int width, int height)](#ImageGrayscaleMask-int-int-) | يُنشئ مثيلاً جديدًا للفئة [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) مع العرض والارتفاع المحددين. |
| [ImageGrayscaleMask(RasterImage image)](#ImageGrayscaleMask-com.aspose.imaging.RasterImage-) | يُنشئ مثيلاً جديدًا للفئة [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) بحجم [RasterImage](../../com.aspose.imaging/rasterimage) الموجود المحدد. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getSource()](#getSource--) | يحصل على صورة المصدر المستخدمة لإنشاء هذا القناع، إذا كانت موجودة. |
| [getWidth()](#getWidth--) | يحصل على عرض هذا القناع، بوحدة البكسل. |
| [getHeight()](#getHeight--) | يحصل على ارتفاع هذا القناع، بوحدة البكسل. |
| [getBounds()](#getBounds--) | يحصل على حدود هذا القناع، بوحدة البكسل. |
| [getSelectionBounds()](#getSelectionBounds--) | يحصل على حدود الجزء المحدد من القناع، بوحدة البكسل. |
| [get_Item(int x, int y)](#get-Item-int-int-) | يحصل على شفافية البكسل المحدد. |
| [set_Item(int x, int y, byte value)](#set-Item-int-int-byte-) | يضبط شفافية البكسل المحدد. |
| [isOpaque(int x, int y)](#isOpaque-int-int-) | يتحقق مما إذا كان البكسل المحدد غير شفاف. |
| [isTransparent(int x, int y)](#isTransparent-int-int-) | يتحقق مما إذا كانت البكسل المحدد شفافة. |
| [getByteOpacity(int x, int y)](#getByteOpacity-int-int-) | يحصل على شفافية البكسل المحدد بدقة البايت. |
| [deepClone()](#deepClone--) | ينشئ كائنًا جديدًا يكون نسخة من المثيل الحالي. |
| [apply()](#apply--) | يطبق القناع الحالي على مصدر [RasterImage](../../com.aspose.imaging/rasterimage) إذا كان موجودًا. |
| [applyTo(RasterImage image)](#applyTo-com.aspose.imaging.RasterImage-) | يطبق القناع الحالي على [RasterImage](../../com.aspose.imaging/rasterimage) المحدد. |
| [crop(Size size)](#crop-com.aspose.imaging.Size-) | يقص القناع بالحجم المحدد. |
| [crop(int width, int height)](#crop-int-int-) | يقص القناع بالعرض والارتفاع المحددين. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | يقص القناع بالمستطيل المحدد. |
| [invert()](#invert--) | يحصل على عكس القناع الحالي. |
| [union(ImageGrayscaleMask mask)](#union-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-) | اتحاد قناعين. |
| [subtract(ImageGrayscaleMask mask)](#subtract-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-) | يحصل على طرح القناع المقدم من القناع الحالي. |
| [intersect(ImageGrayscaleMask mask)](#intersect-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-) | يحصل على تقاطع القناع الحالي مع القناع المقدم. |
| [exclusiveDisjunction(ImageGrayscaleMask mask)](#exclusiveDisjunction-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-) | يحصل على التفريق الحصري للقناع الحالي مع القناع المقدم. |
| [op_LogicalNot(ImageGrayscaleMask a)](#op-LogicalNot-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-) | يعكس القناع. |
| [op_Addition(ImageGrayscaleMask a, ImageGrayscaleMask b)](#op-Addition-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-) | اتحاد قناعين. |
| [op_Subtraction(ImageGrayscaleMask a, ImageGrayscaleMask b)](#op-Subtraction-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-) | طرح القناع الثاني من الأول. |
| [op_Multiply(ImageGrayscaleMask a, ImageGrayscaleMask b)](#op-Multiply-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-) | تقاطع قناعين. |
| [op_ExclusiveOr(ImageGrayscaleMask a, ImageGrayscaleMask b)](#op-ExclusiveOr-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-) | الاختلاف الحصري لقناعين. |

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

### ImageGrayscaleMask(int width, int height) {#ImageGrayscaleMask-int-int-}
```
public ImageGrayscaleMask(int width, int height)
```


يُنشئ مثيلاً جديدًا للفئة [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) مع العرض والارتفاع المحددين.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| العرض | int | عرض القناع. |
| الارتفاع | int | ارتفاع القناع. |

### ImageGrayscaleMask(RasterImage image) {#ImageGrayscaleMask-com.aspose.imaging.RasterImage-}
```
public ImageGrayscaleMask(RasterImage image)
```


يُنشئ مثيلاً جديدًا للفئة [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) بحجم [RasterImage](../../com.aspose.imaging/rasterimage) الموجود المحدد. سيتم تخزين [RasterImage](../../com.aspose.imaging/rasterimage) المحدد كصورة مصدر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | صورة المصدر. |

### getSource() {#getSource--}
```
public final RasterImage getSource()
```


يحصل على صورة المصدر المستخدمة لإنشاء هذا القناع، إذا كانت موجودة.

**Returns:**
[RasterImage](../../com.aspose.imaging/rasterimage) - the source image used to create this mask, if exists.
### getWidth() {#getWidth--}
```
public final int getWidth()
```


يحصل على عرض هذا القناع، بوحدة البكسل.

**Returns:**
int - العرض، بوحدات البكسل، لهذا القناع.
### getHeight() {#getHeight--}
```
public final int getHeight()
```


يحصل على ارتفاع هذا القناع، بوحدة البكسل.

**Returns:**
int - الارتفاع، بوحدات البكسل، لهذا القناع.
### getBounds() {#getBounds--}
```
public final Rectangle getBounds()
```


يحصل على حدود هذا القناع، بوحدة البكسل.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - the bounds, in pixels, of this mask.
### getSelectionBounds() {#getSelectionBounds--}
```
public final Rectangle getSelectionBounds()
```


يحصل على حدود الجزء المحدد من القناع، بوحدة البكسل.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - the bounds of the selected part of the mask, in pixels.
### get_Item(int x, int y) {#get-Item-int-int-}
```
public final byte get_Item(int x, int y)
```


يحصل على شفافية البكسل المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| س | int | الإحداثي السيني للبكسل. |
| ص | int | الإحداثي y للبكسل. القيمة: قيمة بايت؛ 0 إذا كان شفافًا؛ 255 إذا كان غير شفاف. |

**Returns:**
byte
### set_Item(int x, int y, byte value) {#set-Item-int-int-byte-}
```
public final void set_Item(int x, int y, byte value)
```


يضبط شفافية البكسل المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| س | int | الإحداثي السيني للبكسل. |
| ص | int | الإحداثي y للبكسل. القيمة: قيمة بايت؛ 0 إذا كان شفافًا؛ 255 إذا كان غير شفاف. |
| القيمة | byte | شفافية البكسل المحدد. |

### isOpaque(int x, int y) {#isOpaque-int-int-}
```
public final boolean isOpaque(int x, int y)
```


يتحقق مما إذا كان البكسل المحدد غير شفاف.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| س | int | الإحداثي السيني للبكسل. |
| ص | int | الإحداثي الصادي للبكسل. |

**Returns:**
boolean - true إذا كان البكسل المحدد غير شفاف؛ وإلا false.
### isTransparent(int x, int y) {#isTransparent-int-int-}
```
public final boolean isTransparent(int x, int y)
```


يتحقق مما إذا كانت البكسل المحدد شفافة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| س | int | الإحداثي السيني للبكسل. |
| ص | int | الإحداثي الصادي للبكسل. |

**Returns:**
boolean - true إذا كان البكسل المحدد شفافًا؛ وإلا false.
### getByteOpacity(int x, int y) {#getByteOpacity-int-int-}
```
public final byte getByteOpacity(int x, int y)
```


يحصل على شفافية البكسل المحدد بدقة البايت.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| س | int | الإحداثي السيني للبكسل. |
| ص | int | الإحداثي الصادي للبكسل. |

**Returns:**
byte - قيمة بايت، تمثل شفافية البكسل المحدد.
### deepClone() {#deepClone--}
```
public final Object deepClone()
```


ينشئ كائنًا جديدًا يكون نسخة من المثيل الحالي.

**Returns:**
java.lang.Object - كائن جديد هو نسخة من هذه المثيل.
### apply() {#apply--}
```
public final void apply()
```


يطبق القناع الحالي على مصدر [RasterImage](../../com.aspose.imaging/rasterimage) إذا كان موجودًا.

### applyTo(RasterImage image) {#applyTo-com.aspose.imaging.RasterImage-}
```
public final void applyTo(RasterImage image)
```


يطبق القناع الحالي على [RasterImage](../../com.aspose.imaging/rasterimage) المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | الصورة التي سيُطبق عليها القناع. |

### crop(Size size) {#crop-com.aspose.imaging.Size-}
```
public final ImageGrayscaleMask crop(Size size)
```


يقص القناع بالحجم المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| size | [Size](../../com.aspose.imaging/size) | الحجم المحدد. |

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - A cropped [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask).
### crop(int width, int height) {#crop-int-int-}
```
public final ImageGrayscaleMask crop(int width, int height)
```


يقص القناع بالعرض والارتفاع المحددين.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| العرض | int | العرض المحدد. |
| الارتفاع | int | الارتفاع المحدد. |

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - A cropped [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask).
### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public final ImageGrayscaleMask crop(Rectangle rectangle)
```


يقص القناع بالمستطيل المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | المستطيل المحدد. |

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - A cropped [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask).
### invert() {#invert--}
```
public final ImageGrayscaleMask invert()
```


يحصل على عكس القناع الحالي.

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - New [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask).
### union(ImageGrayscaleMask mask) {#union-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-}
```
public final ImageGrayscaleMask union(ImageGrayscaleMask mask)
```


اتحاد قناعين.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| mask | [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) | القناع المقدم |

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - New [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask).
### subtract(ImageGrayscaleMask mask) {#subtract-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-}
```
public final ImageGrayscaleMask subtract(ImageGrayscaleMask mask)
```


يحصل على طرح القناع المقدم من القناع الحالي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| mask | [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) | القناع المقدم |

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - New [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask).
### intersect(ImageGrayscaleMask mask) {#intersect-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-}
```
public final ImageGrayscaleMask intersect(ImageGrayscaleMask mask)
```


يحصل على تقاطع القناع الحالي مع القناع المقدم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| mask | [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) | القناع المقدم |

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - New [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask).
### exclusiveDisjunction(ImageGrayscaleMask mask) {#exclusiveDisjunction-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-}
```
public final ImageGrayscaleMask exclusiveDisjunction(ImageGrayscaleMask mask)
```


يحصل على التفريق الحصري للقناع الحالي مع القناع المقدم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| mask | [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) | القناع المقدم |

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - New [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask).
### op_LogicalNot(ImageGrayscaleMask a) {#op-LogicalNot-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-}
```
public static ImageGrayscaleMask op_LogicalNot(ImageGrayscaleMask a)
```


يعكس القناع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| a | [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) | القناع الذي سيتم عكسه. |

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - New [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask).
### op_Addition(ImageGrayscaleMask a, ImageGrayscaleMask b) {#op-Addition-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-}
```
public static ImageGrayscaleMask op_Addition(ImageGrayscaleMask a, ImageGrayscaleMask b)
```


اتحاد قناعين.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| a | [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) | القناع الأول. |
| b | [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) | القناع الثاني. |

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - New [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask).
### op_Subtraction(ImageGrayscaleMask a, ImageGrayscaleMask b) {#op-Subtraction-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-}
```
public static ImageGrayscaleMask op_Subtraction(ImageGrayscaleMask a, ImageGrayscaleMask b)
```


طرح القناع الثاني من الأول.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| a | [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) | القناع الأول. |
| b | [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) | القناع الثاني. |

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - New [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask).
### op_Multiply(ImageGrayscaleMask a, ImageGrayscaleMask b) {#op-Multiply-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-}
```
public static ImageGrayscaleMask op_Multiply(ImageGrayscaleMask a, ImageGrayscaleMask b)
```


تقاطع قناعين.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| a | [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) | القناع الأول. |
| b | [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) | القناع الثاني. |

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - New [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask).
### op_ExclusiveOr(ImageGrayscaleMask a, ImageGrayscaleMask b) {#op-ExclusiveOr-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-}
```
public static ImageGrayscaleMask op_ExclusiveOr(ImageGrayscaleMask a, ImageGrayscaleMask b)
```


الاختلاف الحصري لقناعين.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| a | [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) | القناع الأول. |
| b | [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) | القناع الثاني. |

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - New [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask).
