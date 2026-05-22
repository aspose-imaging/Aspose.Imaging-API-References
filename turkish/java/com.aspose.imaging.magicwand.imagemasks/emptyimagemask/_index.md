---
title: "EmptyImageMask"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Boş, soyut olmayan bir maskeyi tanımlar."
type: docs
weight: 11
url: /tr/java/com.aspose.imaging.magicwand.imagemasks/emptyimagemask/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.magicwand.imagemasks.ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask)
```
public class EmptyImageMask extends ImageMask
```

Boş, soyut olmayan bir maskeyi tanımlar.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmptyImageMask(int width, int height)](#EmptyImageMask-int-int-) | Belirtilen genişlik ve yükseklik ile [EmptyImageMask](../../com.aspose.imaging.magicwand.imagemasks/emptyimagemask) sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getSelectionBounds()](#getSelectionBounds--) | Maskenin seçilen kısmının piksel cinsinden sınırlarını alır. |
| [get_Item(int x, int y)](#get-Item-int-int-) | Belirtilen pikselin opaklığını alır. |
| [inflate(int size)](#inflate-int-) | Bu maskeyi belirtilen miktarda genişletir. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | Maskeyi belirtilen dikdörtgenle kırpar. |
| [deepClone()](#deepClone--) | Mevcut örneğin bir kopyası olan yeni bir nesne oluşturur. |
### EmptyImageMask(int width, int height) {#EmptyImageMask-int-int-}
```
public EmptyImageMask(int width, int height)
```


Belirtilen genişlik ve yükseklik ile [EmptyImageMask](../../com.aspose.imaging.magicwand.imagemasks/emptyimagemask) sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| genişlik | int | Maskenin genişliği. |
| yükseklik | int | Maskenin yüksekliği. |

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
[ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) - An inflated EmptyImageMask as ImageMask.
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
[ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) - A cropped EmptyImageMask as ImageMask.
### deepClone() {#deepClone--}
```
public Object deepClone()
```


Mevcut örneğin bir kopyası olan yeni bir nesne oluşturur.

**Returns:**
java.lang.Object - Bu örneğin bir kopyası olan yeni bir nesne.
