---
title: "ImageMask"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يصف قناع صورة ثنائي."
type: docs
weight: 16
url: /ar/java/com.aspose.imaging.magicwand.imagemasks/imagemask/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.magicwand.imagemasks.IImageMask](../../com.aspose.imaging.magicwand.imagemasks/iimagemask)
```
public abstract class ImageMask implements IImageMask
```

يصف قناع صورة ثنائي.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [to_ImageGrayscaleMask(ImageMask mask)](#to-ImageGrayscaleMask-com.aspose.imaging.magicwand.imagemasks.ImageMask-) | تحويل `mask` إلى [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask). |
| [op_LogicalNot(ImageMask a)](#op-LogicalNot-com.aspose.imaging.magicwand.imagemasks.ImageMask-) | يعكس القناع. |
| [op_Addition(ImageMask a, ImageMask b)](#op-Addition-com.aspose.imaging.magicwand.imagemasks.ImageMask-com.aspose.imaging.magicwand.imagemasks.ImageMask-) | اتحاد قناعين. |
| [op_Subtraction(ImageMask a, ImageMask b)](#op-Subtraction-com.aspose.imaging.magicwand.imagemasks.ImageMask-com.aspose.imaging.magicwand.imagemasks.ImageMask-) | طرح القناع الثاني من الأول. |
| [op_Multiply(ImageMask a, ImageMask b)](#op-Multiply-com.aspose.imaging.magicwand.imagemasks.ImageMask-com.aspose.imaging.magicwand.imagemasks.ImageMask-) | تقاطع قناعين. |
| [op_ExclusiveOr(ImageMask a, ImageMask b)](#op-ExclusiveOr-com.aspose.imaging.magicwand.imagemasks.ImageMask-com.aspose.imaging.magicwand.imagemasks.ImageMask-) | الاختلاف الحصري لقناعين. |
| [getSource()](#getSource--) | يحصل على صورة المصدر المستخدمة لإنشاء هذا القناع، إذا كانت موجودة. |
| [getWidth()](#getWidth--) | يحصل على عرض هذا القناع، بوحدة البكسل. |
| [getHeight()](#getHeight--) | يحصل على ارتفاع هذا القناع، بوحدة البكسل. |
| [getBounds()](#getBounds--) | يحصل على حدود هذا القناع، بوحدة البكسل. |
| [get_Item(int x, int y)](#get-Item-int-int-) | يحصل على شفافية البكسل المحدد. |
| [inflate(int size)](#inflate-int-) | يوسع هذا القناع بالمقدار المحدد. |
| [crop(Size size)](#crop-com.aspose.imaging.Size-) | يقص القناع بالحجم المحدد. |
| [crop(int width, int height)](#crop-int-int-) | يقص القناع بالعرض والارتفاع المحددين. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | يقص القناع بالمستطيل المحدد. |
| [isOpaque(int x, int y)](#isOpaque-int-int-) | يتحقق مما إذا كان البكسل المحدد غير شفاف. |
| [isTransparent(int x, int y)](#isTransparent-int-int-) | يتحقق مما إذا كانت البكسل المحدد شفافة. |
| [getByteOpacity(int x, int y)](#getByteOpacity-int-int-) | يحصل على شفافية البكسل المحدد بدقة البايت. |
| [getFeathered()](#getFeathered--) | يحصل على قناع رمادي مع حد مموه باستخدام الإعدادات الافتراضية. |
| [getFeathered(FeatheringSettings settings)](#getFeathered-com.aspose.imaging.magicwand.imagemasks.FeatheringSettings-) | يحصل على قناع رمادي مع حد مموه باستخدام الإعدادات المحددة. |
| [apply()](#apply--) | يطبق القناع الحالي على مصدر [RasterImage](../../com.aspose.imaging/rasterimage) إذا كان موجودًا. |
| [applyTo(RasterImage image)](#applyTo-com.aspose.imaging.RasterImage-) | يطبق القناع الحالي على [RasterImage](../../com.aspose.imaging/rasterimage) المحدد. |
| [invert()](#invert--) | يحصل على عكس القناع الحالي. |
| [union(ImageMask mask)](#union-com.aspose.imaging.magicwand.imagemasks.ImageMask-) | يحصل على اتحاد القناع الحالي مع القناع المقدم. |
| [union()](#union--) | يحصل على اتحاد القناع الحالي مع نتيجة اختيار العصا السحرية المطبقة على مصدر القناع. |
| [union(MagicWandSettings settings)](#union-com.aspose.imaging.magicwand.MagicWandSettings-) | يحصل على اتحاد القناع الحالي مع نتيجة اختيار العصا السحرية المطبقة على مصدر القناع. |
| [union(RasterImage image)](#union-com.aspose.imaging.RasterImage-) | يحصل على اتحاد القناع الحالي مع نتيجة اختيار العصا السحرية المطبقة على الصورة المقدمة. |
| [union(RasterImage image, MagicWandSettings settings)](#union-com.aspose.imaging.RasterImage-com.aspose.imaging.magicwand.MagicWandSettings-) | يحصل على اتحاد القناع الحالي مع نتيجة اختيار العصا السحرية المطبقة على الصورة المقدمة. |
| [subtract(ImageMask mask)](#subtract-com.aspose.imaging.magicwand.imagemasks.ImageMask-) | يحصل على طرح القناع المقدم من القناع الحالي. |
| [subtract()](#subtract--) | يحصل على نتيجة اختيار العصا السحرية المطبقة على مصدر القناع الحالي مطروحًا من القناع. |
| [subtract(MagicWandSettings settings)](#subtract-com.aspose.imaging.magicwand.MagicWandSettings-) | يحصل على نتيجة اختيار العصا السحرية المطبقة على مصدر القناع الحالي مطروحًا من القناع. |
| [subtract(RasterImage image)](#subtract-com.aspose.imaging.RasterImage-) | يحصل على نتيجة اختيار العصا السحرية المطبقة على الصورة المقدمة مطروحًا من القناع الحالي. |
| [subtract(RasterImage image, MagicWandSettings settings)](#subtract-com.aspose.imaging.RasterImage-com.aspose.imaging.magicwand.MagicWandSettings-) | يحصل على نتيجة اختيار العصا السحرية المطبقة على الصورة المقدمة مطروحًا من القناع الحالي. |
| [intersect(ImageMask mask)](#intersect-com.aspose.imaging.magicwand.imagemasks.ImageMask-) | يحصل على تقاطع القناع الحالي مع القناع المقدم. |
| [intersect()](#intersect--) | يحصل على تقاطع القناع الحالي مع نتيجة اختيار العصا السحرية المطبقة على مصدر القناع. |
| [intersect(MagicWandSettings settings)](#intersect-com.aspose.imaging.magicwand.MagicWandSettings-) | يحصل على تقاطع القناع الحالي مع نتيجة اختيار العصا السحرية المطبقة على مصدر القناع. |
| [intersect(RasterImage image)](#intersect-com.aspose.imaging.RasterImage-) | يحصل على تقاطع القناع الحالي مع نتيجة تحديد العصا السحرية المطبقة على الصورة المقدمة. |
| [intersect(RasterImage image, MagicWandSettings settings)](#intersect-com.aspose.imaging.RasterImage-com.aspose.imaging.magicwand.MagicWandSettings-) | يحصل على تقاطع القناع الحالي مع نتيجة تحديد العصا السحرية المطبقة على الصورة المقدمة. |
| [exclusiveDisjunction(ImageMask mask)](#exclusiveDisjunction-com.aspose.imaging.magicwand.imagemasks.ImageMask-) | يحصل على التفريق الحصري للقناع الحالي مع القناع المقدم. |
| [exclusiveDisjunction()](#exclusiveDisjunction--) | يحصل على التفريق الحصري للقناع الحالي مع نتيجة تحديد العصا السحرية المطبقة على مصدر القناع. |
| [exclusiveDisjunction(MagicWandSettings settings)](#exclusiveDisjunction-com.aspose.imaging.magicwand.MagicWandSettings-) | يحصل على التفريق الحصري للقناع الحالي مع نتيجة تحديد العصا السحرية المطبقة على مصدر القناع. |
| [exclusiveDisjunction(RasterImage image)](#exclusiveDisjunction-com.aspose.imaging.RasterImage-) | يحصل على التفريق الحصري للقناع الحالي مع نتيجة تحديد العصا السحرية المطبقة على الصورة المقدمة. |
| [exclusiveDisjunction(RasterImage image, MagicWandSettings settings)](#exclusiveDisjunction-com.aspose.imaging.RasterImage-com.aspose.imaging.magicwand.MagicWandSettings-) | يحصل على التفريق الحصري للقناع الحالي مع نتيجة تحديد العصا السحرية المطبقة على الصورة المقدمة. |

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

### to_ImageGrayscaleMask(ImageMask mask) {#to-ImageGrayscaleMask-com.aspose.imaging.magicwand.imagemasks.ImageMask-}
```
public static ImageGrayscaleMask to_ImageGrayscaleMask(ImageMask mask)
```


تحويل `mask` إلى [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| mask | [ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) | قيمة القناع. |

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - The new [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) base on `mask`.
### op_LogicalNot(ImageMask a) {#op-LogicalNot-com.aspose.imaging.magicwand.imagemasks.ImageMask-}
```
public static ImageBitMask op_LogicalNot(ImageMask a)
```


يعكس القناع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| a | [ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) | القناع الذي سيتم عكسه. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### op_Addition(ImageMask a, ImageMask b) {#op-Addition-com.aspose.imaging.magicwand.imagemasks.ImageMask-com.aspose.imaging.magicwand.imagemasks.ImageMask-}
```
public static ImageBitMask op_Addition(ImageMask a, ImageMask b)
```


اتحاد قناعين.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| a | [ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) | القناع الأول. |
| b | [ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) | القناع الثاني. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### op_Subtraction(ImageMask a, ImageMask b) {#op-Subtraction-com.aspose.imaging.magicwand.imagemasks.ImageMask-com.aspose.imaging.magicwand.imagemasks.ImageMask-}
```
public static ImageBitMask op_Subtraction(ImageMask a, ImageMask b)
```


طرح القناع الثاني من الأول.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| a | [ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) | القناع الأول. |
| b | [ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) | القناع الثاني. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### op_Multiply(ImageMask a, ImageMask b) {#op-Multiply-com.aspose.imaging.magicwand.imagemasks.ImageMask-com.aspose.imaging.magicwand.imagemasks.ImageMask-}
```
public static ImageBitMask op_Multiply(ImageMask a, ImageMask b)
```


تقاطع قناعين.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| a | [ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) | القناع الأول. |
| b | [ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) | القناع الثاني. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### op_ExclusiveOr(ImageMask a, ImageMask b) {#op-ExclusiveOr-com.aspose.imaging.magicwand.imagemasks.ImageMask-com.aspose.imaging.magicwand.imagemasks.ImageMask-}
```
public static ImageBitMask op_ExclusiveOr(ImageMask a, ImageMask b)
```


الاختلاف الحصري لقناعين.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| a | [ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) | القناع الأول. |
| b | [ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) | القناع الثاني. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
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
### get_Item(int x, int y) {#get-Item-int-int-}
```
public abstract boolean get_Item(int x, int y)
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
public abstract ImageMask inflate(int size)
```


يوسع هذا القناع بالمقدار المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الحجم | int | المقدار لتوسيع هذه القناع. |

**Returns:**
[ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) - An ImageMask.
### crop(Size size) {#crop-com.aspose.imaging.Size-}
```
public final ImageMask crop(Size size)
```


يقص القناع بالحجم المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| size | [Size](../../com.aspose.imaging/size) | الحجم المحدد. |

**Returns:**
[ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) - An ImageMask.
### crop(int width, int height) {#crop-int-int-}
```
public final ImageMask crop(int width, int height)
```


يقص القناع بالعرض والارتفاع المحددين.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| العرض | int | العرض المحدد. |
| الارتفاع | int | الارتفاع المحدد. |

**Returns:**
[ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) - An ImageMask.
### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public abstract ImageMask crop(Rectangle rectangle)
```


يقص القناع بالمستطيل المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | المستطيل المحدد. |

**Returns:**
[ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) - An ImageMask.
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
### getFeathered() {#getFeathered--}
```
public final ImageGrayscaleMask getFeathered()
```


يحصل على قناع رمادي مع حد مموه باستخدام الإعدادات الافتراضية.

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - \#to\_ImageGrayscaleMask(ImageMask).to\_ImageGrayscaleMask(ImageMask)\} with feathered border.
### getFeathered(FeatheringSettings settings) {#getFeathered-com.aspose.imaging.magicwand.imagemasks.FeatheringSettings-}
```
public final ImageGrayscaleMask getFeathered(FeatheringSettings settings)
```


يحصل على قناع رمادي مع حد مموه باستخدام الإعدادات المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| settings | [FeatheringSettings](../../com.aspose.imaging.magicwand.imagemasks/featheringsettings) | إعدادات التنعيم. |

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - \#to\_ImageGrayscaleMask(ImageMask).to\_ImageGrayscaleMask(ImageMask)\} with feathered border.
### apply() {#apply--}
```
public final void apply()
```


يطبق القناع الحالي على مصدر [RasterImage](../../com.aspose.imaging/rasterimage) إذا كان موجودًا.


**Example: The example shows how to select a simple area of an image based on tone and color of any pixel using Magic Wand tool.**

``` java
String imageFilePath = "input.png";
String outputFilePath = "masked.png";
try (RasterImage image = (RasterImage)Image.load(imageFilePath))
{
    // أنشئ قناعًا جديدًا باستخدام أداة العصا السحرية بناءً على نغمة ولون البكسل (120, 100) مع عتبة مخصصة تساوي 150
    MagicWandTool
            .select(image, new MagicWandSettings(120, 100) {{ setThreshold(150); }})
            // طبق القناع على الصورة
            .apply();

    // احفظ الصورة مع خيار نوع لون الشفافية القسري
    image.save(outputFilePath, new PngOptions()
    {{
        setColorType(PngColorType.TruecolorWithAlpha);
    }});
}

```

### applyTo(RasterImage image) {#applyTo-com.aspose.imaging.RasterImage-}
```
public final void applyTo(RasterImage image)
```


يطبق القناع الحالي على [RasterImage](../../com.aspose.imaging/rasterimage) المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | الصورة التي سيُطبق عليها القناع. |

### invert() {#invert--}
```
public final ImageBitMask invert()
```


يحصل على عكس القناع الحالي.

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).

**Example: The example shows how to select a complicated area of an image using Magic Wand tool and the ability to interact with masks (invert, union, subtract).**

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

### union(ImageMask mask) {#union-com.aspose.imaging.magicwand.imagemasks.ImageMask-}
```
public final ImageBitMask union(ImageMask mask)
```


يحصل على اتحاد القناع الحالي مع القناع المقدم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| mask | [ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) | القناع المقدم |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### union() {#union--}
```
public final ImageBitMask union()
```


يحصل على اتحاد القناع الحالي مع نتيجة اختيار العصا السحرية المطبقة على مصدر القناع.

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### union(MagicWandSettings settings) {#union-com.aspose.imaging.magicwand.MagicWandSettings-}
```
public final ImageBitMask union(MagicWandSettings settings)
```


يحصل على اتحاد القناع الحالي مع نتيجة اختيار العصا السحرية المطبقة على مصدر القناع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| settings | [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) | إعدادات العصا السحرية. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### union(RasterImage image) {#union-com.aspose.imaging.RasterImage-}
```
public final ImageBitMask union(RasterImage image)
```


يحصل على اتحاد القناع الحالي مع نتيجة اختيار العصا السحرية المطبقة على الصورة المقدمة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | الصورة لاستخدام العصا السحرية. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### union(RasterImage image, MagicWandSettings settings) {#union-com.aspose.imaging.RasterImage-com.aspose.imaging.magicwand.MagicWandSettings-}
```
public final ImageBitMask union(RasterImage image, MagicWandSettings settings)
```


يحصل على اتحاد القناع الحالي مع نتيجة اختيار العصا السحرية المطبقة على الصورة المقدمة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | الصورة لاستخدام العصا السحرية. |
| settings | [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) | إعدادات العصا السحرية. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### subtract(ImageMask mask) {#subtract-com.aspose.imaging.magicwand.imagemasks.ImageMask-}
```
public final ImageBitMask subtract(ImageMask mask)
```


يحصل على طرح القناع المقدم من القناع الحالي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| mask | [ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) | القناع المقدم |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### subtract() {#subtract--}
```
public final ImageBitMask subtract()
```


يحصل على نتيجة اختيار العصا السحرية المطبقة على مصدر القناع الحالي مطروحًا من القناع.

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### subtract(MagicWandSettings settings) {#subtract-com.aspose.imaging.magicwand.MagicWandSettings-}
```
public final ImageBitMask subtract(MagicWandSettings settings)
```


يحصل على نتيجة اختيار العصا السحرية المطبقة على مصدر القناع الحالي مطروحًا من القناع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| settings | [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) | إعدادات العصا السحرية. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### subtract(RasterImage image) {#subtract-com.aspose.imaging.RasterImage-}
```
public final ImageBitMask subtract(RasterImage image)
```


يحصل على نتيجة اختيار العصا السحرية المطبقة على الصورة المقدمة مطروحًا من القناع الحالي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | الصورة لاستخدام العصا السحرية. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### subtract(RasterImage image, MagicWandSettings settings) {#subtract-com.aspose.imaging.RasterImage-com.aspose.imaging.magicwand.MagicWandSettings-}
```
public final ImageBitMask subtract(RasterImage image, MagicWandSettings settings)
```


يحصل على نتيجة اختيار العصا السحرية المطبقة على الصورة المقدمة مطروحًا من القناع الحالي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | الصورة لاستخدام العصا السحرية. |
| settings | [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) | إعدادات العصا السحرية. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### intersect(ImageMask mask) {#intersect-com.aspose.imaging.magicwand.imagemasks.ImageMask-}
```
public final ImageBitMask intersect(ImageMask mask)
```


يحصل على تقاطع القناع الحالي مع القناع المقدم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| mask | [ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) | القناع المقدم |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### intersect() {#intersect--}
```
public final ImageBitMask intersect()
```


يحصل على تقاطع القناع الحالي مع نتيجة اختيار العصا السحرية المطبقة على مصدر القناع.

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### intersect(MagicWandSettings settings) {#intersect-com.aspose.imaging.magicwand.MagicWandSettings-}
```
public final ImageBitMask intersect(MagicWandSettings settings)
```


يحصل على تقاطع القناع الحالي مع نتيجة اختيار العصا السحرية المطبقة على مصدر القناع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| settings | [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) | إعدادات العصا السحرية. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### intersect(RasterImage image) {#intersect-com.aspose.imaging.RasterImage-}
```
public final ImageBitMask intersect(RasterImage image)
```


يحصل على تقاطع القناع الحالي مع نتيجة تحديد العصا السحرية المطبقة على الصورة المقدمة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | الصورة لاستخدام العصا السحرية. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### intersect(RasterImage image, MagicWandSettings settings) {#intersect-com.aspose.imaging.RasterImage-com.aspose.imaging.magicwand.MagicWandSettings-}
```
public final ImageBitMask intersect(RasterImage image, MagicWandSettings settings)
```


يحصل على تقاطع القناع الحالي مع نتيجة تحديد العصا السحرية المطبقة على الصورة المقدمة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | الصورة لاستخدام العصا السحرية. |
| settings | [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) | إعدادات العصا السحرية. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### exclusiveDisjunction(ImageMask mask) {#exclusiveDisjunction-com.aspose.imaging.magicwand.imagemasks.ImageMask-}
```
public final ImageBitMask exclusiveDisjunction(ImageMask mask)
```


يحصل على التفريق الحصري للقناع الحالي مع القناع المقدم.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| mask | [ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) | القناع المقدم |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### exclusiveDisjunction() {#exclusiveDisjunction--}
```
public final ImageBitMask exclusiveDisjunction()
```


يحصل على التفريق الحصري للقناع الحالي مع نتيجة تحديد العصا السحرية المطبقة على مصدر القناع.

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### exclusiveDisjunction(MagicWandSettings settings) {#exclusiveDisjunction-com.aspose.imaging.magicwand.MagicWandSettings-}
```
public final ImageBitMask exclusiveDisjunction(MagicWandSettings settings)
```


يحصل على التفريق الحصري للقناع الحالي مع نتيجة تحديد العصا السحرية المطبقة على مصدر القناع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| settings | [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) | إعدادات العصا السحرية. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### exclusiveDisjunction(RasterImage image) {#exclusiveDisjunction-com.aspose.imaging.RasterImage-}
```
public final ImageBitMask exclusiveDisjunction(RasterImage image)
```


يحصل على التفريق الحصري للقناع الحالي مع نتيجة تحديد العصا السحرية المطبقة على الصورة المقدمة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | الصورة لاستخدام العصا السحرية. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### exclusiveDisjunction(RasterImage image, MagicWandSettings settings) {#exclusiveDisjunction-com.aspose.imaging.RasterImage-com.aspose.imaging.magicwand.MagicWandSettings-}
```
public final ImageBitMask exclusiveDisjunction(RasterImage image, MagicWandSettings settings)
```


يحصل على التفريق الحصري للقناع الحالي مع نتيجة تحديد العصا السحرية المطبقة على الصورة المقدمة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | الصورة لاستخدام العصا السحرية. |
| settings | [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) | إعدادات العصا السحرية. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
