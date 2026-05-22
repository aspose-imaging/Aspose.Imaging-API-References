---
title: "ImageMask"
second_title: "Aspose.Imaging for Java API Referansı"
description: "İkili görüntü maskesini tanımlar."
type: docs
weight: 16
url: /tr/java/com.aspose.imaging.magicwand.imagemasks/imagemask/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.magicwand.imagemasks.IImageMask](../../com.aspose.imaging.magicwand.imagemasks/iimagemask)
```
public abstract class ImageMask implements IImageMask
```

İkili görüntü maskesini tanımlar.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [to_ImageGrayscaleMask(ImageMask mask)](#to-ImageGrayscaleMask-com.aspose.imaging.magicwand.imagemasks.ImageMask-) | `mask` değişkenini bir [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) tipine dönüştürme. |
| [op_LogicalNot(ImageMask a)](#op-LogicalNot-com.aspose.imaging.magicwand.imagemasks.ImageMask-) | Maskeyi tersine çevirir. |
| [op_Addition(ImageMask a, ImageMask b)](#op-Addition-com.aspose.imaging.magicwand.imagemasks.ImageMask-com.aspose.imaging.magicwand.imagemasks.ImageMask-) | İki maskenin birleşimi. |
| [op_Subtraction(ImageMask a, ImageMask b)](#op-Subtraction-com.aspose.imaging.magicwand.imagemasks.ImageMask-com.aspose.imaging.magicwand.imagemasks.ImageMask-) | İkinci maskeyi birinciden çıkar. |
| [op_Multiply(ImageMask a, ImageMask b)](#op-Multiply-com.aspose.imaging.magicwand.imagemasks.ImageMask-com.aspose.imaging.magicwand.imagemasks.ImageMask-) | İki maskenin kesişimi. |
| [op_ExclusiveOr(ImageMask a, ImageMask b)](#op-ExclusiveOr-com.aspose.imaging.magicwand.imagemasks.ImageMask-com.aspose.imaging.magicwand.imagemasks.ImageMask-) | İki maskenin özel ayrık birleşimi. |
| [getSource()](#getSource--) | Bu maskeyi oluşturmak için kullanılan kaynak görüntüyü, varsa alır. |
| [getWidth()](#getWidth--) | Bu maskenin piksel cinsinden genişliğini alır. |
| [getHeight()](#getHeight--) | Bu maskenin piksel cinsinden yüksekliğini alır. |
| [getBounds()](#getBounds--) | Bu maskenin piksel cinsinden sınırlarını alır. |
| [get_Item(int x, int y)](#get-Item-int-int-) | Belirtilen pikselin opaklığını alır. |
| [inflate(int size)](#inflate-int-) | Bu maskeyi belirtilen miktarda genişletir. |
| [crop(Size size)](#crop-com.aspose.imaging.Size-) | Maskeyi belirtilen boyutta kırpar. |
| [crop(int width, int height)](#crop-int-int-) | Maskeyi belirtilen genişlik ve yükseklikte kırpar. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | Maskeyi belirtilen dikdörtgenle kırpar. |
| [isOpaque(int x, int y)](#isOpaque-int-int-) | Belirtilen pikselin opak olup olmadığını kontrol eder. |
| [isTransparent(int x, int y)](#isTransparent-int-int-) | Belirtilen pikselin şeffaf olup olmadığını denetler. |
| [getByteOpacity(int x, int y)](#getByteOpacity-int-int-) | Belirtilen pikselin opaklığını bayt hassasiyetiyle alır. |
| [getFeathered()](#getFeathered--) | Kenarı varsayılan ayarlarla yumuşatılmış gri tonlamalı maskeyi alır. |
| [getFeathered(FeatheringSettings settings)](#getFeathered-com.aspose.imaging.magicwand.imagemasks.FeatheringSettings-) | Kenarı belirtilen ayarlarla yumuşatılmış gri tonlamalı maskeyi alır. |
| [apply()](#apply--) | Mevcut maskeyi, mevcutsa, [RasterImage](../../com.aspose.imaging/rasterimage) kaynağına uygular. |
| [applyTo(RasterImage image)](#applyTo-com.aspose.imaging.RasterImage-) | Mevcut maskeyi belirtilen [RasterImage](../../com.aspose.imaging/rasterimage) üzerine uygular. |
| [invert()](#invert--) | Mevcut maskenin tersini alır. |
| [union(ImageMask mask)](#union-com.aspose.imaging.magicwand.imagemasks.ImageMask-) | Mevcut maskeyi sağlananla birleştirir. |
| [union()](#union--) | Maskenin kaynağına uygulanan sihirli değnek seçiminin sonucu ile mevcut maskenin birleşimini alır. |
| [union(MagicWandSettings settings)](#union-com.aspose.imaging.magicwand.MagicWandSettings-) | Maskenin kaynağına uygulanan sihirli değnek seçiminin sonucu ile mevcut maskenin birleşimini alır. |
| [union(RasterImage image)](#union-com.aspose.imaging.RasterImage-) | Sağlanan görüntüye uygulanan sihirli değnek seçiminin sonucu ile mevcut maskenin birleşimini alır. |
| [union(RasterImage image, MagicWandSettings settings)](#union-com.aspose.imaging.RasterImage-com.aspose.imaging.magicwand.MagicWandSettings-) | Sağlanan görüntüye uygulanan sihirli değnek seçiminin sonucu ile mevcut maskenin birleşimini alır. |
| [subtract(ImageMask mask)](#subtract-com.aspose.imaging.magicwand.imagemasks.ImageMask-) | Sağlanan maskeyi mevcut maskeden çıkarır. |
| [subtract()](#subtract--) | Mevcut maskenin kaynağına uygulanan sihirli değnek seçiminin sonucunu maskeden çıkararak alır. |
| [subtract(MagicWandSettings settings)](#subtract-com.aspose.imaging.magicwand.MagicWandSettings-) | Mevcut maskenin kaynağına uygulanan sihirli değnek seçiminin sonucunu maskeden çıkararak alır. |
| [subtract(RasterImage image)](#subtract-com.aspose.imaging.RasterImage-) | Sağlanan görüntüye uygulanan sihirli değnek seçiminin sonucunu mevcut maskeden çıkararak alır. |
| [subtract(RasterImage image, MagicWandSettings settings)](#subtract-com.aspose.imaging.RasterImage-com.aspose.imaging.magicwand.MagicWandSettings-) | Sağlanan görüntüye uygulanan sihirli değnek seçiminin sonucunu mevcut maskeden çıkararak alır. |
| [intersect(ImageMask mask)](#intersect-com.aspose.imaging.magicwand.imagemasks.ImageMask-) | Mevcut maskeyi sağlananla kesiştirir. |
| [intersect()](#intersect--) | Maskenin kaynağına uygulanan sihirli değnek seçiminin sonucu ile mevcut maskenin kesişimini alır. |
| [intersect(MagicWandSettings settings)](#intersect-com.aspose.imaging.magicwand.MagicWandSettings-) | Maskenin kaynağına uygulanan sihirli değnek seçiminin sonucu ile mevcut maskenin kesişimini alır. |
| [intersect(RasterImage image)](#intersect-com.aspose.imaging.RasterImage-) | Sağlanan görüntüye uygulanan sihirli değnek seçiminin sonucuyla mevcut maskenin kesişimini alır. |
| [intersect(RasterImage image, MagicWandSettings settings)](#intersect-com.aspose.imaging.RasterImage-com.aspose.imaging.magicwand.MagicWandSettings-) | Sağlanan görüntüye uygulanan sihirli değnek seçiminin sonucuyla mevcut maskenin kesişimini alır. |
| [exclusiveDisjunction(ImageMask mask)](#exclusiveDisjunction-com.aspose.imaging.magicwand.imagemasks.ImageMask-) | Mevcut maskenin sağlanan ile özel ayrık birleşimini alır. |
| [exclusiveDisjunction()](#exclusiveDisjunction--) | Maskenin kaynağına uygulanan sihirli değnek seçiminin sonucuyla mevcut maskenin özel ayrık birleşimini alır. |
| [exclusiveDisjunction(MagicWandSettings settings)](#exclusiveDisjunction-com.aspose.imaging.magicwand.MagicWandSettings-) | Maskenin kaynağına uygulanan sihirli değnek seçiminin sonucuyla mevcut maskenin özel ayrık birleşimini alır. |
| [exclusiveDisjunction(RasterImage image)](#exclusiveDisjunction-com.aspose.imaging.RasterImage-) | Sağlanan görüntüye uygulanan sihirli değnek seçiminin sonucuyla mevcut maskenin özel ayrık birleşimini alır. |
| [exclusiveDisjunction(RasterImage image, MagicWandSettings settings)](#exclusiveDisjunction-com.aspose.imaging.RasterImage-com.aspose.imaging.magicwand.MagicWandSettings-) | Sağlanan görüntüye uygulanan sihirli değnek seçiminin sonucuyla mevcut maskenin özel ayrık birleşimini alır. |

## Example: The example shows how to select a complicated area of an image using Magic Wand tool and the ability to interact with masks (invert, union, subtract).

``` java
String imageFilePath = "input.png";
String outputFilePath = "masked-complex.png";
try (RasterImage image = (RasterImage)Image.load(imageFilePath))
{
    // (845, 128) pikselinin ton ve rengine dayanarak magic wand aracıyla yeni bir maske oluşturun.
    MagicWandTool.select(image, new MagicWandSettings(845, 128))
            // Mevcut maskeyi, magic wand aracıyla oluşturulan belirtilen maske ile birleştir
            .union(new MagicWandSettings(416, 387))
            // Mevcut maskeyi tersine çevir
            .invert()
            // Belirtilen eşik değeriyle magic wand aracıyla oluşturulan maskeyi mevcut maskeden çıkar
            .subtract(new MagicWandSettings(1482, 346) {{ setThreshold(69); }})
            // Belirtilen dört dikdörtgen maskeyi mevcut maskeden tek tek çıkar
            .subtract(new RectangleMask(0, 0, 800, 150))
            .subtract(new RectangleMask(0, 380, 600, 220))
            .subtract(new RectangleMask(930, 520, 110, 40))
            .subtract(new RectangleMask(1370, 400, 120, 200))
            // Maskeyi belirtilen ayarlarla yumuşat
            .getFeathered(new FeatheringSettings() {{ setSize(3); }})
            // Maskeyi görüntüye uygula
            .apply();

    // Görüntüyü kaydet
    image.save(outputFilePath);
}

```

### to_ImageGrayscaleMask(ImageMask mask) {#to-ImageGrayscaleMask-com.aspose.imaging.magicwand.imagemasks.ImageMask-}
```
public static ImageGrayscaleMask to_ImageGrayscaleMask(ImageMask mask)
```


`mask` değişkenini bir [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) tipine dönüştürme.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mask | [ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) | Maskenin değeri. |

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - The new [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) base on `mask`.
### op_LogicalNot(ImageMask a) {#op-LogicalNot-com.aspose.imaging.magicwand.imagemasks.ImageMask-}
```
public static ImageBitMask op_LogicalNot(ImageMask a)
```


Maskeyi tersine çevirir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| a | [ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) | Tersine çevrilecek maske. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### op_Addition(ImageMask a, ImageMask b) {#op-Addition-com.aspose.imaging.magicwand.imagemasks.ImageMask-com.aspose.imaging.magicwand.imagemasks.ImageMask-}
```
public static ImageBitMask op_Addition(ImageMask a, ImageMask b)
```


İki maskenin birleşimi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| a | [ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) | İlk maske. |
| b | [ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) | İkinci maske. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### op_Subtraction(ImageMask a, ImageMask b) {#op-Subtraction-com.aspose.imaging.magicwand.imagemasks.ImageMask-com.aspose.imaging.magicwand.imagemasks.ImageMask-}
```
public static ImageBitMask op_Subtraction(ImageMask a, ImageMask b)
```


İkinci maskeyi birinciden çıkar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| a | [ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) | İlk maske. |
| b | [ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) | İkinci maske. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### op_Multiply(ImageMask a, ImageMask b) {#op-Multiply-com.aspose.imaging.magicwand.imagemasks.ImageMask-com.aspose.imaging.magicwand.imagemasks.ImageMask-}
```
public static ImageBitMask op_Multiply(ImageMask a, ImageMask b)
```


İki maskenin kesişimi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| a | [ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) | İlk maske. |
| b | [ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) | İkinci maske. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### op_ExclusiveOr(ImageMask a, ImageMask b) {#op-ExclusiveOr-com.aspose.imaging.magicwand.imagemasks.ImageMask-com.aspose.imaging.magicwand.imagemasks.ImageMask-}
```
public static ImageBitMask op_ExclusiveOr(ImageMask a, ImageMask b)
```


İki maskenin özel ayrık birleşimi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| a | [ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) | İlk maske. |
| b | [ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) | İkinci maske. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### getSource() {#getSource--}
```
public final RasterImage getSource()
```


Bu maskeyi oluşturmak için kullanılan kaynak görüntüyü, varsa alır.

**Returns:**
[RasterImage](../../com.aspose.imaging/rasterimage) - the source image used to create this mask, if exists.
### getWidth() {#getWidth--}
```
public final int getWidth()
```


Bu maskenin piksel cinsinden genişliğini alır.

**Returns:**
int - bu maskenin piksel cinsinden genişliği.
### getHeight() {#getHeight--}
```
public final int getHeight()
```


Bu maskenin piksel cinsinden yüksekliğini alır.

**Returns:**
int - bu maskenin piksel cinsinden yüksekliği.
### getBounds() {#getBounds--}
```
public final Rectangle getBounds()
```


Bu maskenin piksel cinsinden sınırlarını alır.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - the bounds, in pixels, of this mask.
### get_Item(int x, int y) {#get-Item-int-int-}
```
public abstract boolean get_Item(int x, int y)
```


Belirtilen pikselin opaklığını alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | int | Pikselin x koordinatı. |
| y | int | Pikselin y koordinatı. |

**Returns:**
boolean - belirtilen piksel opak ise true; aksi takdirde false.
### inflate(int size) {#inflate-int-}
```
public abstract ImageMask inflate(int size)
```


Bu maskeyi belirtilen miktarda genişletir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| boyut | int | Bu maskeyi şişirmek için miktar. |

**Returns:**
[ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) - An ImageMask.
### crop(Size size) {#crop-com.aspose.imaging.Size-}
```
public final ImageMask crop(Size size)
```


Maskeyi belirtilen boyutta kırpar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| size | [Size](../../com.aspose.imaging/size) | Belirtilen boyut. |

**Returns:**
[ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) - An ImageMask.
### crop(int width, int height) {#crop-int-int-}
```
public final ImageMask crop(int width, int height)
```


Maskeyi belirtilen genişlik ve yükseklikte kırpar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| genişlik | int | Belirtilen genişlik. |
| yükseklik | int | Belirtilen yükseklik. |

**Returns:**
[ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) - An ImageMask.
### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public abstract ImageMask crop(Rectangle rectangle)
```


Maskeyi belirtilen dikdörtgenle kırpar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Belirtilen dikdörtgen. |

**Returns:**
[ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) - An ImageMask.
### isOpaque(int x, int y) {#isOpaque-int-int-}
```
public final boolean isOpaque(int x, int y)
```


Belirtilen pikselin opak olup olmadığını kontrol eder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | int | Pikselin x koordinatı. |
| y | int | Pikselin y koordinatı. |

**Returns:**
boolean - belirtilen piksel opak ise true; aksi takdirde false.
### isTransparent(int x, int y) {#isTransparent-int-int-}
```
public final boolean isTransparent(int x, int y)
```


Belirtilen pikselin şeffaf olup olmadığını denetler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | int | Pikselin x koordinatı. |
| y | int | Pikselin y koordinatı. |

**Returns:**
boolean - belirtilen piksel şeffaf ise true; aksi takdirinde false.
### getByteOpacity(int x, int y) {#getByteOpacity-int-int-}
```
public final byte getByteOpacity(int x, int y)
```


Belirtilen pikselin opaklığını bayt hassasiyetiyle alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | int | Pikselin x koordinatı. |
| y | int | Pikselin y koordinatı. |

**Returns:**
byte - Belirtilen pikselin opaklığını temsil eden bayt değeri.
### getFeathered() {#getFeathered--}
```
public final ImageGrayscaleMask getFeathered()
```


Kenarı varsayılan ayarlarla yumuşatılmış gri tonlamalı maskeyi alır.

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - \#to\_ImageGrayscaleMask(ImageMask).to\_ImageGrayscaleMask(ImageMask)\} with feathered border.
### getFeathered(FeatheringSettings settings) {#getFeathered-com.aspose.imaging.magicwand.imagemasks.FeatheringSettings-}
```
public final ImageGrayscaleMask getFeathered(FeatheringSettings settings)
```


Kenarı belirtilen ayarlarla yumuşatılmış gri tonlamalı maskeyi alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| settings | [FeatheringSettings](../../com.aspose.imaging.magicwand.imagemasks/featheringsettings) | Tüyleme ayarları. |

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - \#to\_ImageGrayscaleMask(ImageMask).to\_ImageGrayscaleMask(ImageMask)\} with feathered border.
### apply() {#apply--}
```
public final void apply()
```


Mevcut maskeyi, mevcutsa, [RasterImage](../../com.aspose.imaging/rasterimage) kaynağına uygular.


**Example: The example shows how to select a simple area of an image based on tone and color of any pixel using Magic Wand tool.**

``` java
String imageFilePath = "input.png";
String outputFilePath = "masked.png";
try (RasterImage image = (RasterImage)Image.load(imageFilePath))
{
    // Özel eşik değeri 150 olan, (120, 100) pikselinin ton ve rengine dayanarak magic wand aracıyla yeni bir maske oluşturun.
    MagicWandTool
            .select(image, new MagicWandSettings(120, 100) {{ setThreshold(150); }})
            // Maskeyi görüntüye uygula
            .apply();

    // Zorunlu şeffaflık renk tipi seçeneğiyle görüntüyü kaydet
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


Mevcut maskeyi belirtilen [RasterImage](../../com.aspose.imaging/rasterimage) üzerine uygular.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Maskenin uygulanacağı görüntü. |

### invert() {#invert--}
```
public final ImageBitMask invert()
```


Mevcut maskenin tersini alır.

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).

**Example: The example shows how to select a complicated area of an image using Magic Wand tool and the ability to interact with masks (invert, union, subtract).**

``` java
String imageFilePath = "input.png";
String outputFilePath = "masked-complex.png";
try (RasterImage image = (RasterImage)Image.load(imageFilePath))
{
    // (845, 128) pikselinin ton ve rengine dayanarak magic wand aracıyla yeni bir maske oluşturun.
    MagicWandTool.select(image, new MagicWandSettings(845, 128))
            // Mevcut maskeyi, magic wand aracıyla oluşturulan belirtilen maske ile birleştir
            .union(new MagicWandSettings(416, 387))
            // Mevcut maskeyi tersine çevir
            .invert()
            // Belirtilen eşik değeriyle magic wand aracıyla oluşturulan maskeyi mevcut maskeden çıkar
            .subtract(new MagicWandSettings(1482, 346) {{ setThreshold(69); }})
            // Belirtilen dört dikdörtgen maskeyi mevcut maskeden tek tek çıkar
            .subtract(new RectangleMask(0, 0, 800, 150))
            .subtract(new RectangleMask(0, 380, 600, 220))
            .subtract(new RectangleMask(930, 520, 110, 40))
            .subtract(new RectangleMask(1370, 400, 120, 200))
            // Maskeyi belirtilen ayarlarla yumuşat
            .getFeathered(new FeatheringSettings() {{ setSize(3); }})
            // Maskeyi görüntüye uygula
            .apply();

    // Görüntüyü kaydet
    image.save(outputFilePath);
}

```

### union(ImageMask mask) {#union-com.aspose.imaging.magicwand.imagemasks.ImageMask-}
```
public final ImageBitMask union(ImageMask mask)
```


Mevcut maskeyi sağlananla birleştirir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mask | [ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) | Sağlanan maske |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### union() {#union--}
```
public final ImageBitMask union()
```


Maskenin kaynağına uygulanan sihirli değnek seçiminin sonucu ile mevcut maskenin birleşimini alır.

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### union(MagicWandSettings settings) {#union-com.aspose.imaging.magicwand.MagicWandSettings-}
```
public final ImageBitMask union(MagicWandSettings settings)
```


Maskenin kaynağına uygulanan sihirli değnek seçiminin sonucu ile mevcut maskenin birleşimini alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| settings | [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) | Sihirli değnek ayarları. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### union(RasterImage image) {#union-com.aspose.imaging.RasterImage-}
```
public final ImageBitMask union(RasterImage image)
```


Sağlanan görüntüye uygulanan sihirli değnek seçiminin sonucu ile mevcut maskenin birleşimini alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Sihirli değnek için görüntü. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### union(RasterImage image, MagicWandSettings settings) {#union-com.aspose.imaging.RasterImage-com.aspose.imaging.magicwand.MagicWandSettings-}
```
public final ImageBitMask union(RasterImage image, MagicWandSettings settings)
```


Sağlanan görüntüye uygulanan sihirli değnek seçiminin sonucu ile mevcut maskenin birleşimini alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Sihirli değnek için görüntü. |
| settings | [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) | Sihirli değnek ayarları. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### subtract(ImageMask mask) {#subtract-com.aspose.imaging.magicwand.imagemasks.ImageMask-}
```
public final ImageBitMask subtract(ImageMask mask)
```


Sağlanan maskeyi mevcut maskeden çıkarır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mask | [ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) | Sağlanan maske |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### subtract() {#subtract--}
```
public final ImageBitMask subtract()
```


Mevcut maskenin kaynağına uygulanan sihirli değnek seçiminin sonucunu maskeden çıkararak alır.

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### subtract(MagicWandSettings settings) {#subtract-com.aspose.imaging.magicwand.MagicWandSettings-}
```
public final ImageBitMask subtract(MagicWandSettings settings)
```


Mevcut maskenin kaynağına uygulanan sihirli değnek seçiminin sonucunu maskeden çıkararak alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| settings | [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) | Sihirli değnek ayarları. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### subtract(RasterImage image) {#subtract-com.aspose.imaging.RasterImage-}
```
public final ImageBitMask subtract(RasterImage image)
```


Sağlanan görüntüye uygulanan sihirli değnek seçiminin sonucunu mevcut maskeden çıkararak alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Sihirli değnek için görüntü. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### subtract(RasterImage image, MagicWandSettings settings) {#subtract-com.aspose.imaging.RasterImage-com.aspose.imaging.magicwand.MagicWandSettings-}
```
public final ImageBitMask subtract(RasterImage image, MagicWandSettings settings)
```


Sağlanan görüntüye uygulanan sihirli değnek seçiminin sonucunu mevcut maskeden çıkararak alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Sihirli değnek için görüntü. |
| settings | [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) | Sihirli değnek ayarları. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### intersect(ImageMask mask) {#intersect-com.aspose.imaging.magicwand.imagemasks.ImageMask-}
```
public final ImageBitMask intersect(ImageMask mask)
```


Mevcut maskeyi sağlananla kesiştirir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mask | [ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) | Sağlanan maske |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### intersect() {#intersect--}
```
public final ImageBitMask intersect()
```


Maskenin kaynağına uygulanan sihirli değnek seçiminin sonucu ile mevcut maskenin kesişimini alır.

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### intersect(MagicWandSettings settings) {#intersect-com.aspose.imaging.magicwand.MagicWandSettings-}
```
public final ImageBitMask intersect(MagicWandSettings settings)
```


Maskenin kaynağına uygulanan sihirli değnek seçiminin sonucu ile mevcut maskenin kesişimini alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| settings | [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) | Sihirli değnek ayarları. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### intersect(RasterImage image) {#intersect-com.aspose.imaging.RasterImage-}
```
public final ImageBitMask intersect(RasterImage image)
```


Sağlanan görüntüye uygulanan sihirli değnek seçiminin sonucuyla mevcut maskenin kesişimini alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Sihirli değnek için görüntü. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### intersect(RasterImage image, MagicWandSettings settings) {#intersect-com.aspose.imaging.RasterImage-com.aspose.imaging.magicwand.MagicWandSettings-}
```
public final ImageBitMask intersect(RasterImage image, MagicWandSettings settings)
```


Sağlanan görüntüye uygulanan sihirli değnek seçiminin sonucuyla mevcut maskenin kesişimini alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Sihirli değnek için görüntü. |
| settings | [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) | Sihirli değnek ayarları. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### exclusiveDisjunction(ImageMask mask) {#exclusiveDisjunction-com.aspose.imaging.magicwand.imagemasks.ImageMask-}
```
public final ImageBitMask exclusiveDisjunction(ImageMask mask)
```


Mevcut maskenin sağlanan ile özel ayrık birleşimini alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mask | [ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) | Sağlanan maske |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### exclusiveDisjunction() {#exclusiveDisjunction--}
```
public final ImageBitMask exclusiveDisjunction()
```


Maskenin kaynağına uygulanan sihirli değnek seçiminin sonucuyla mevcut maskenin özel ayrık birleşimini alır.

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### exclusiveDisjunction(MagicWandSettings settings) {#exclusiveDisjunction-com.aspose.imaging.magicwand.MagicWandSettings-}
```
public final ImageBitMask exclusiveDisjunction(MagicWandSettings settings)
```


Maskenin kaynağına uygulanan sihirli değnek seçiminin sonucuyla mevcut maskenin özel ayrık birleşimini alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| settings | [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) | Sihirli değnek ayarları. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### exclusiveDisjunction(RasterImage image) {#exclusiveDisjunction-com.aspose.imaging.RasterImage-}
```
public final ImageBitMask exclusiveDisjunction(RasterImage image)
```


Sağlanan görüntüye uygulanan sihirli değnek seçiminin sonucuyla mevcut maskenin özel ayrık birleşimini alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Sihirli değnek için görüntü. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### exclusiveDisjunction(RasterImage image, MagicWandSettings settings) {#exclusiveDisjunction-com.aspose.imaging.RasterImage-com.aspose.imaging.magicwand.MagicWandSettings-}
```
public final ImageBitMask exclusiveDisjunction(RasterImage image, MagicWandSettings settings)
```


Sağlanan görüntüye uygulanan sihirli değnek seçiminin sonucuyla mevcut maskenin özel ayrık birleşimini alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Sihirli değnek için görüntü. |
| settings | [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) | Sihirli değnek ayarları. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
