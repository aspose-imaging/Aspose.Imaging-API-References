---
title: "RectangleMask"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Dikdörtgen maskeyi tanımlar."
type: docs
weight: 17
url: /tr/java/com.aspose.imaging.magicwand.imagemasks/rectanglemask/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.magicwand.imagemasks.ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask)
```
public class RectangleMask extends ImageMask
```

Dikdörtgen maskeyi tanımlar.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [RectangleMask(int x, int y, int width, int height)](#RectangleMask-int-int-int-int-) | Belirtilen sol-üst nokta, genişlik ve yükseklik ile [RectangleMask](../../com.aspose.imaging.magicwand.imagemasks/rectanglemask) sınıfının yeni bir örneğini başlatır. |
| [RectangleMask(Rectangle selectedArea)](#RectangleMask-com.aspose.imaging.Rectangle-) | Belirtilen dikdörtgen ile [RectangleMask](../../com.aspose.imaging.magicwand.imagemasks/rectanglemask) sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getSelectionBounds()](#getSelectionBounds--) | Maskenin seçilen kısmının piksel cinsinden sınırlarını alır. |
| [get_Item(int x, int y)](#get-Item-int-int-) | Belirtilen pikselin opaklığını alır. |
| [inflate(int size)](#inflate-int-) | Bu maskeyi belirtilen miktarda genişletir. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | Maskeyi belirtilen dikdörtgenle kırpar. |
| [deepClone()](#deepClone--) | Mevcut örneğin bir kopyası olan yeni bir nesne oluşturur. |

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

### RectangleMask(int x, int y, int width, int height) {#RectangleMask-int-int-int-int-}
```
public RectangleMask(int x, int y, int width, int height)
```


Belirtilen sol-üst nokta, genişlik ve yükseklik ile [RectangleMask](../../com.aspose.imaging.magicwand.imagemasks/rectanglemask) sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | int | Seçili alanın sol-üst noktasının x koordinatı. |
| y | int | Seçili alanın sol-üst noktasının y koordinatı. |
| genişlik | int | Seçili alanın genişliği. |
| yükseklik | int | Seçili alanın yüksekliği. |

### RectangleMask(Rectangle selectedArea) {#RectangleMask-com.aspose.imaging.Rectangle-}
```
public RectangleMask(Rectangle selectedArea)
```


Belirtilen dikdörtgen ile [RectangleMask](../../com.aspose.imaging.magicwand.imagemasks/rectanglemask) sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| selectedArea | [Rectangle](../../com.aspose.imaging/rectangle) | Dikdörtgen olarak belirtilen seçili alan. |

### getSelectionBounds() {#getSelectionBounds--}
```
public Rectangle getSelectionBounds()
```


Maskenin seçilen kısmının piksel cinsinden sınırlarını alır.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - the bounds of the selected part of the mask, in pixels.
### get_Item(int x, int y) {#get-Item-int-int-}
```
public boolean get_Item(int x, int y)
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
public ImageMask inflate(int size)
```


Bu maskeyi belirtilen miktarda genişletir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| boyut | int | Bu maskeyi şişirmek için miktar. |

**Returns:**
[ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) - An inflated RectangleMask as ImageMask.
### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public ImageMask crop(Rectangle rectangle)
```


Maskeyi belirtilen dikdörtgenle kırpar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Belirtilen dikdörtgen. |

**Returns:**
[ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) - A cropped RectangleMask as ImageMask.
### deepClone() {#deepClone--}
```
public Object deepClone()
```


Mevcut örneğin bir kopyası olan yeni bir nesne oluşturur.

**Returns:**
java.lang.Object - Bu örneğin bir kopyası olan yeni bir nesne.
