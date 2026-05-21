---
title: "CircleMask"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Bir daire maskesini tanımlar."
type: docs
weight: 10
url: /tr/java/com.aspose.imaging.magicwand.imagemasks/circlemask/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.magicwand.imagemasks.ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask)
```
public class CircleMask extends ImageMask
```

Bir daire maskesini tanımlar.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [CircleMask(int x, int y, int radius)](#CircleMask-int-int-int-) | Belirtilen merkez noktası ve yarıçap ile [CircleMask](../../com.aspose.imaging.magicwand.imagemasks/circlemask) sınıfının yeni bir örneğini başlatır. |
| [CircleMask(Point center, int radius)](#CircleMask-com.aspose.imaging.Point-int-) | Belirtilen merkez noktası ve yarıçap ile [CircleMask](../../com.aspose.imaging.magicwand.imagemasks/circlemask) sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getSelectionBounds()](#getSelectionBounds--) | Bu maskenin piksel cinsinden sınırlarını alır. |
| [get_Item(int x, int y)](#get-Item-int-int-) | Belirtilen pikselin opaklığını alır. |
| [inflate(int size)](#inflate-int-) | Bu maskeyi belirtilen miktarda genişletir. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | Maskeyi belirtilen dikdörtgenle kırpar. |
| [deepClone()](#deepClone--) | Mevcut örneğin bir kopyası olan yeni bir nesne oluşturur. |
### CircleMask(int x, int y, int radius) {#CircleMask-int-int-int-}
```
public CircleMask(int x, int y, int radius)
```


Belirtilen merkez noktası ve yarıçap ile [CircleMask](../../com.aspose.imaging.magicwand.imagemasks/circlemask) sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | int | Seçilen alanın merkez noktasının x koordinatı. |
| y | int | Seçilen alanın merkez noktasının y koordinatı. |
| radius | int | Seçilen alanın yarıçapı. |

### CircleMask(Point center, int radius) {#CircleMask-com.aspose.imaging.Point-int-}
```
public CircleMask(Point center, int radius)
```


Belirtilen merkez noktası ve yarıçap ile [CircleMask](../../com.aspose.imaging.magicwand.imagemasks/circlemask) sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| center | [Point](../../com.aspose.imaging/point) | Seçilen alanın merkez noktası. |
| radius | int | Seçilen alanın yarıçapı. |

### getSelectionBounds() {#getSelectionBounds--}
```
public Rectangle getSelectionBounds()
```


Bu maskenin piksel cinsinden sınırlarını alır.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - the bounds, in pixels, of this mask.
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
[ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) - An inflated CircleMask as ImageMask.
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
[ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) - A cropped CircleMask or ImageBitMask as ImageMask. As ImageBitMask may be returned, fluent call is recommended.
### deepClone() {#deepClone--}
```
public Object deepClone()
```


Mevcut örneğin bir kopyası olan yeni bir nesne oluşturur.

**Returns:**
java.lang.Object - Bu örneğin bir kopyası olan yeni bir nesne.
