---
title: "IImageMask"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Bir maskeyi tanımlar."
type: docs
weight: 18
url: /tr/java/com.aspose.imaging.magicwand.imagemasks/iimagemask/
---
**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable
```
public interface IImageMask extends System.ICloneable
```

Bir maskeyi tanımlar.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getSource()](#getSource--) | Bu maskeyi oluşturmak için kullanılan kaynak görüntüyü, varsa alır. |
| [getWidth()](#getWidth--) | Bu maskenin piksel cinsinden genişliğini alır. |
| [getHeight()](#getHeight--) | Bu maskenin piksel cinsinden yüksekliğini alır. |
| [getBounds()](#getBounds--) | Bu maskenin piksel cinsinden sınırlarını alır. |
| [getSelectionBounds()](#getSelectionBounds--) | Maskenin seçilen kısmının piksel cinsinden sınırlarını alır. |
| [isOpaque(int x, int y)](#isOpaque-int-int-) | Belirtilen pikselin opak olup olmadığını kontrol eder. |
| [isTransparent(int x, int y)](#isTransparent-int-int-) | Belirtilen pikselin şeffaf olup olmadığını denetler. |
| [getByteOpacity(int x, int y)](#getByteOpacity-int-int-) | Belirtilen pikselin opaklığını bayt hassasiyetiyle alır. |
### getSource() {#getSource--}
```
public abstract RasterImage getSource()
```


Bu maskeyi oluşturmak için kullanılan kaynak görüntüyü, varsa alır.

**Returns:**
[RasterImage](../../com.aspose.imaging/rasterimage) - the source image used to create this mask, if exists.
### getWidth() {#getWidth--}
```
public abstract int getWidth()
```


Bu maskenin piksel cinsinden genişliğini alır.

**Returns:**
int - bu maskenin piksel cinsinden genişliği.
### getHeight() {#getHeight--}
```
public abstract int getHeight()
```


Bu maskenin piksel cinsinden yüksekliğini alır.

**Returns:**
int - bu maskenin piksel cinsinden yüksekliği.
### getBounds() {#getBounds--}
```
public abstract Rectangle getBounds()
```


Bu maskenin piksel cinsinden sınırlarını alır.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - the bounds, in pixels, of this mask.
### getSelectionBounds() {#getSelectionBounds--}
```
public abstract Rectangle getSelectionBounds()
```


Maskenin seçilen kısmının piksel cinsinden sınırlarını alır.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - the bounds of the selected part of the mask, in pixels.
### isOpaque(int x, int y) {#isOpaque-int-int-}
```
public abstract boolean isOpaque(int x, int y)
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
public abstract boolean isTransparent(int x, int y)
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
public abstract byte getByteOpacity(int x, int y)
```


Belirtilen pikselin opaklığını bayt hassasiyetiyle alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | int | Pikselin x koordinatı. |
| y | int | Pikselin y koordinatı. |

**Returns:**
byte - Belirtilen pikselin opaklığını temsil eden bayt değeri.
