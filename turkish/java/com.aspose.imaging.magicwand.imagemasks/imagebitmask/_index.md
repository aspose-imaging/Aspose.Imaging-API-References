---
title: "ImageBitMask"
second_title: "Aspose.Imaging for Java API Referansı"
description: "İkili görüntü maskesini tanımlar."
type: docs
weight: 14
url: /tr/java/com.aspose.imaging.magicwand.imagemasks/imagebitmask/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.magicwand.imagemasks.ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask)
```
public class ImageBitMask extends ImageMask
```

İkili görüntü maskesini tanımlar.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [ImageBitMask(int width, int height)](#ImageBitMask-int-int-) | Belirtilen genişlik ve yükseklik ile [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) sınıfının yeni bir örneğini başlatır. |
| [ImageBitMask(RasterImage image)](#ImageBitMask-com.aspose.imaging.RasterImage-) | Belirtilen mevcut [RasterImage](../../com.aspose.imaging/rasterimage) boyutu ile [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getSelectionBounds()](#getSelectionBounds--) | Maskenin seçilen kısmının piksel cinsinden sınırlarını alır. |
| [get_Item(int x, int y)](#get-Item-int-int-) | Belirtilen pikselin opaklığını alır. |
| [inflate(int size)](#inflate-int-) | Bu maskeyi belirtilen miktarda genişletir. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | Maskeyi belirtilen dikdörtgenle kırpar. |
| [deepClone()](#deepClone--) | Mevcut örneğin bir kopyası olan yeni bir nesne oluşturur. |
| [setMaskPixel(int x, int y, boolean value)](#setMaskPixel-int-int-boolean-) | Belirtilen pikselin opaklığını ayarlar. |
| [op_LogicalNot(ImageBitMask a)](#op-LogicalNot-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-) | Maskeyi tersine çevirir. |
| [op_Addition(ImageBitMask a, ImageBitMask b)](#op-Addition-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-) | İki maskenin birleşimi. |
| [op_Subtraction(ImageBitMask a, ImageBitMask b)](#op-Subtraction-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-) | İkinci maskeyi birinciden çıkar. |
| [op_Multiply(ImageBitMask a, ImageBitMask b)](#op-Multiply-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-) | İki maskenin kesişimi. |
| [op_ExclusiveOr(ImageBitMask a, ImageBitMask b)](#op-ExclusiveOr-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-) | İki maskenin özel ayrık birleşimi. |
### ImageBitMask(int width, int height) {#ImageBitMask-int-int-}
```
public ImageBitMask(int width, int height)
```


Belirtilen genişlik ve yükseklik ile [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| genişlik | int | Maskenin genişliği. |
| yükseklik | int | Maskenin yüksekliği. |

### ImageBitMask(RasterImage image) {#ImageBitMask-com.aspose.imaging.RasterImage-}
```
public ImageBitMask(RasterImage image)
```


Belirtilen mevcut [RasterImage](../../com.aspose.imaging/rasterimage) boyutunda yeni bir [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) sınıfının bir örneğini başlatır. Belirtilen [RasterImage](../../com.aspose.imaging/rasterimage) kaynak görüntü olarak depolanacaktır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Kaynak görüntü. |

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
| y | int | Pikselin y-koordinatı. Değer: belirtilen piksel opak ise true; aksi takdirde false. |

**Returns:**
boolean
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
[ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) - An inflated [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) as [ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask).
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
[ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) - A cropped [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) as [ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask).
### deepClone() {#deepClone--}
```
public Object deepClone()
```


Mevcut örneğin bir kopyası olan yeni bir nesne oluşturur.

**Returns:**
java.lang.Object - Bu örneğin bir kopyası olan yeni bir nesne.
### setMaskPixel(int x, int y, boolean value) {#setMaskPixel-int-int-boolean-}
```
public final void setMaskPixel(int x, int y, boolean value)
```


Belirtilen pikselin opaklığını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | int | Pikselin x koordinatı. |
| y | int | Pikselin y koordinatı. |
| değer | boolean | Belirtilen piksel opak ise true; aksi takdirde false. |

### op_LogicalNot(ImageBitMask a) {#op-LogicalNot-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-}
```
public static ImageBitMask op_LogicalNot(ImageBitMask a)
```


Maskeyi tersine çevirir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| a | [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) | Tersine çevrilecek maske. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### op_Addition(ImageBitMask a, ImageBitMask b) {#op-Addition-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-}
```
public static ImageBitMask op_Addition(ImageBitMask a, ImageBitMask b)
```


İki maskenin birleşimi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| a | [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) | İlk maske. |
| b | [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) | İkinci maske. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### op_Subtraction(ImageBitMask a, ImageBitMask b) {#op-Subtraction-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-}
```
public static ImageBitMask op_Subtraction(ImageBitMask a, ImageBitMask b)
```


İkinci maskeyi birinciden çıkar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| a | [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) | İlk maske. |
| b | [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) | İkinci maske. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### op_Multiply(ImageBitMask a, ImageBitMask b) {#op-Multiply-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-}
```
public static ImageBitMask op_Multiply(ImageBitMask a, ImageBitMask b)
```


İki maskenin kesişimi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| a | [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) | İlk maske. |
| b | [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) | İkinci maske. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### op_ExclusiveOr(ImageBitMask a, ImageBitMask b) {#op-ExclusiveOr-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-}
```
public static ImageBitMask op_ExclusiveOr(ImageBitMask a, ImageBitMask b)
```


İki maskenin özel ayrık birleşimi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| a | [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) | İlk maske. |
| b | [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) | İkinci maske. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
