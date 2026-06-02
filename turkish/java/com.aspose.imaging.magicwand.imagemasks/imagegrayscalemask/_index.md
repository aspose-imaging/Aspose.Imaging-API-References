---
title: "ImageGrayscaleMask"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Gri tonlamalı görüntü maskesini tanımlar."
type: docs
weight: 15
url: /tr/java/com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.magicwand.imagemasks.IImageMask](../../com.aspose.imaging.magicwand.imagemasks/iimagemask)
```
public class ImageGrayscaleMask implements IImageMask
```

Gri tonlamalı görüntü maskesini tanımlar.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [ImageGrayscaleMask(int width, int height)](#ImageGrayscaleMask-int-int-) | Belirtilen genişlik ve yükseklik ile [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) sınıfının yeni bir örneğini başlatır. |
| [ImageGrayscaleMask(RasterImage image)](#ImageGrayscaleMask-com.aspose.imaging.RasterImage-) | Belirtilen mevcut [RasterImage](../../com.aspose.imaging/rasterimage) boyutu ile [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getSource()](#getSource--) | Bu maskeyi oluşturmak için kullanılan kaynak görüntüyü, varsa alır. |
| [getWidth()](#getWidth--) | Bu maskenin piksel cinsinden genişliğini alır. |
| [getHeight()](#getHeight--) | Bu maskenin piksel cinsinden yüksekliğini alır. |
| [getBounds()](#getBounds--) | Bu maskenin piksel cinsinden sınırlarını alır. |
| [getSelectionBounds()](#getSelectionBounds--) | Maskenin seçilen kısmının piksel cinsinden sınırlarını alır. |
| [get_Item(int x, int y)](#get-Item-int-int-) | Belirtilen pikselin opaklığını alır. |
| [set_Item(int x, int y, byte value)](#set-Item-int-int-byte-) | Belirtilen pikselin opaklığını ayarlar. |
| [isOpaque(int x, int y)](#isOpaque-int-int-) | Belirtilen pikselin opak olup olmadığını kontrol eder. |
| [isTransparent(int x, int y)](#isTransparent-int-int-) | Belirtilen pikselin şeffaf olup olmadığını denetler. |
| [getByteOpacity(int x, int y)](#getByteOpacity-int-int-) | Belirtilen pikselin opaklığını bayt hassasiyetiyle alır. |
| [deepClone()](#deepClone--) | Mevcut örneğin bir kopyası olan yeni bir nesne oluşturur. |
| [apply()](#apply--) | Mevcut maskeyi, mevcutsa, [RasterImage](../../com.aspose.imaging/rasterimage) kaynağına uygular. |
| [applyTo(RasterImage image)](#applyTo-com.aspose.imaging.RasterImage-) | Mevcut maskeyi belirtilen [RasterImage](../../com.aspose.imaging/rasterimage) üzerine uygular. |
| [crop(Size size)](#crop-com.aspose.imaging.Size-) | Maskeyi belirtilen boyutta kırpar. |
| [crop(int width, int height)](#crop-int-int-) | Maskeyi belirtilen genişlik ve yükseklikte kırpar. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | Maskeyi belirtilen dikdörtgenle kırpar. |
| [invert()](#invert--) | Mevcut maskenin tersini alır. |
| [union(ImageGrayscaleMask mask)](#union-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-) | İki maskenin birleşimi. |
| [subtract(ImageGrayscaleMask mask)](#subtract-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-) | Sağlanan maskeyi mevcut maskeden çıkarır. |
| [intersect(ImageGrayscaleMask mask)](#intersect-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-) | Mevcut maskeyi sağlananla kesiştirir. |
| [exclusiveDisjunction(ImageGrayscaleMask mask)](#exclusiveDisjunction-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-) | Mevcut maskenin sağlanan ile özel ayrık birleşimini alır. |
| [op_LogicalNot(ImageGrayscaleMask a)](#op-LogicalNot-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-) | Maskeyi tersine çevirir. |
| [op_Addition(ImageGrayscaleMask a, ImageGrayscaleMask b)](#op-Addition-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-) | İki maskenin birleşimi. |
| [op_Subtraction(ImageGrayscaleMask a, ImageGrayscaleMask b)](#op-Subtraction-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-) | İkinci maskeyi birinciden çıkar. |
| [op_Multiply(ImageGrayscaleMask a, ImageGrayscaleMask b)](#op-Multiply-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-) | İki maskenin kesişimi. |
| [op_ExclusiveOr(ImageGrayscaleMask a, ImageGrayscaleMask b)](#op-ExclusiveOr-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-) | İki maskenin özel ayrık birleşimi. |

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

### ImageGrayscaleMask(int width, int height) {#ImageGrayscaleMask-int-int-}
```
public ImageGrayscaleMask(int width, int height)
```


Belirtilen genişlik ve yükseklik ile [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| genişlik | int | Maskenin genişliği. |
| yükseklik | int | Maskenin yüksekliği. |

### ImageGrayscaleMask(RasterImage image) {#ImageGrayscaleMask-com.aspose.imaging.RasterImage-}
```
public ImageGrayscaleMask(RasterImage image)
```


Belirtilen mevcut [RasterImage](../../com.aspose.imaging/rasterimage) boyutu ile [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) sınıfının yeni bir örneğini başlatır. Belirtilen [RasterImage](../../com.aspose.imaging/rasterimage) kaynak görüntü olarak saklanacaktır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Kaynak görüntü. |

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
### getSelectionBounds() {#getSelectionBounds--}
```
public final Rectangle getSelectionBounds()
```


Maskenin seçilen kısmının piksel cinsinden sınırlarını alır.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - the bounds of the selected part of the mask, in pixels.
### get_Item(int x, int y) {#get-Item-int-int-}
```
public final byte get_Item(int x, int y)
```


Belirtilen pikselin opaklığını alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | int | Pikselin x koordinatı. |
| y | int | Pikselin y koordinatı. Değer: Bayt değeri; şeffaf ise 0; opak ise 255. |

**Returns:**
byte
### set_Item(int x, int y, byte value) {#set-Item-int-int-byte-}
```
public final void set_Item(int x, int y, byte value)
```


Belirtilen pikselin opaklığını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | int | Pikselin x koordinatı. |
| y | int | Pikselin y koordinatı. Değer: Bayt değeri; şeffaf ise 0; opak ise 255. |
| değer | byte | belirtilen pikselin opaklığı. |

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
### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Mevcut örneğin bir kopyası olan yeni bir nesne oluşturur.

**Returns:**
java.lang.Object - Bu örneğin bir kopyası olan yeni bir nesne.
### apply() {#apply--}
```
public final void apply()
```


Mevcut maskeyi, mevcutsa, [RasterImage](../../com.aspose.imaging/rasterimage) kaynağına uygular.

### applyTo(RasterImage image) {#applyTo-com.aspose.imaging.RasterImage-}
```
public final void applyTo(RasterImage image)
```


Mevcut maskeyi belirtilen [RasterImage](../../com.aspose.imaging/rasterimage) üzerine uygular.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Maskenin uygulanacağı görüntü. |

### crop(Size size) {#crop-com.aspose.imaging.Size-}
```
public final ImageGrayscaleMask crop(Size size)
```


Maskeyi belirtilen boyutta kırpar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| size | [Size](../../com.aspose.imaging/size) | Belirtilen boyut. |

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - A cropped [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask).
### crop(int width, int height) {#crop-int-int-}
```
public final ImageGrayscaleMask crop(int width, int height)
```


Maskeyi belirtilen genişlik ve yükseklikte kırpar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| genişlik | int | Belirtilen genişlik. |
| yükseklik | int | Belirtilen yükseklik. |

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - A cropped [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask).
### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public final ImageGrayscaleMask crop(Rectangle rectangle)
```


Maskeyi belirtilen dikdörtgenle kırpar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Belirtilen dikdörtgen. |

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - A cropped [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask).
### invert() {#invert--}
```
public final ImageGrayscaleMask invert()
```


Mevcut maskenin tersini alır.

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - New [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask).
### union(ImageGrayscaleMask mask) {#union-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-}
```
public final ImageGrayscaleMask union(ImageGrayscaleMask mask)
```


İki maskenin birleşimi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mask | [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) | Sağlanan maske |

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - New [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask).
### subtract(ImageGrayscaleMask mask) {#subtract-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-}
```
public final ImageGrayscaleMask subtract(ImageGrayscaleMask mask)
```


Sağlanan maskeyi mevcut maskeden çıkarır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mask | [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) | Sağlanan maske |

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - New [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask).
### intersect(ImageGrayscaleMask mask) {#intersect-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-}
```
public final ImageGrayscaleMask intersect(ImageGrayscaleMask mask)
```


Mevcut maskeyi sağlananla kesiştirir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mask | [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) | Sağlanan maske |

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - New [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask).
### exclusiveDisjunction(ImageGrayscaleMask mask) {#exclusiveDisjunction-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-}
```
public final ImageGrayscaleMask exclusiveDisjunction(ImageGrayscaleMask mask)
```


Mevcut maskenin sağlanan ile özel ayrık birleşimini alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mask | [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) | Sağlanan maske |

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - New [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask).
### op_LogicalNot(ImageGrayscaleMask a) {#op-LogicalNot-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-}
```
public static ImageGrayscaleMask op_LogicalNot(ImageGrayscaleMask a)
```


Maskeyi tersine çevirir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| a | [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) | Tersine çevrilecek maske. |

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - New [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask).
### op_Addition(ImageGrayscaleMask a, ImageGrayscaleMask b) {#op-Addition-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-}
```
public static ImageGrayscaleMask op_Addition(ImageGrayscaleMask a, ImageGrayscaleMask b)
```


İki maskenin birleşimi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| a | [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) | İlk maske. |
| b | [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) | İkinci maske. |

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - New [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask).
### op_Subtraction(ImageGrayscaleMask a, ImageGrayscaleMask b) {#op-Subtraction-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-}
```
public static ImageGrayscaleMask op_Subtraction(ImageGrayscaleMask a, ImageGrayscaleMask b)
```


İkinci maskeyi birinciden çıkar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| a | [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) | İlk maske. |
| b | [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) | İkinci maske. |

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - New [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask).
### op_Multiply(ImageGrayscaleMask a, ImageGrayscaleMask b) {#op-Multiply-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-}
```
public static ImageGrayscaleMask op_Multiply(ImageGrayscaleMask a, ImageGrayscaleMask b)
```


İki maskenin kesişimi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| a | [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) | İlk maske. |
| b | [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) | İkinci maske. |

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - New [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask).
### op_ExclusiveOr(ImageGrayscaleMask a, ImageGrayscaleMask b) {#op-ExclusiveOr-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-}
```
public static ImageGrayscaleMask op_ExclusiveOr(ImageGrayscaleMask a, ImageGrayscaleMask b)
```


İki maskenin özel ayrık birleşimi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| a | [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) | İlk maske. |
| b | [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) | İkinci maske. |

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - New [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask).
