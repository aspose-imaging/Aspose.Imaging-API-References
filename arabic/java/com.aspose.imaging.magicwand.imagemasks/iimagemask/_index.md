---
title: "IImageMask"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يصف قناعًا."
type: docs
weight: 18
url: /ar/java/com.aspose.imaging.magicwand.imagemasks/iimagemask/
---
**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable
```
public interface IImageMask extends System.ICloneable
```

يصف قناعًا.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getSource()](#getSource--) | يحصل على الصورة المصدر المستخدمة لإنشاء هذه القناع، إذا وجدت. |
| [getWidth()](#getWidth--) | يحصل على العرض، بوحدات البكسل، لهذه القناع. |
| [getHeight()](#getHeight--) | يحصل على الارتفاع، بوحدات البكسل، لهذه القناع. |
| [getBounds()](#getBounds--) | يحصل على الحدود، بوحدات البكسل، لهذه القناع. |
| [getSelectionBounds()](#getSelectionBounds--) | يحصل على حدود الجزء المحدد من القناع، بوحدات البكسل. |
| [isOpaque(int x, int y)](#isOpaque-int-int-) | يتحقق مما إذا كان البكسل المحدد غير شفاف. |
| [isTransparent(int x, int y)](#isTransparent-int-int-) | يتحقق مما إذا كان البكسل المحدد شفافًا. |
| [getByteOpacity(int x, int y)](#getByteOpacity-int-int-) | يحصل على شفافية البكسل المحدد بدقة بايت. |
### getSource() {#getSource--}
```
public abstract RasterImage getSource()
```


يحصل على الصورة المصدر المستخدمة لإنشاء هذه القناع، إذا وجدت.

**Returns:**
[RasterImage](../../com.aspose.imaging/rasterimage) - the source image used to create this mask, if exists.
### getWidth() {#getWidth--}
```
public abstract int getWidth()
```


يحصل على العرض، بوحدات البكسل، لهذه القناع.

**Returns:**
int - العرض، بوحدات البكسل، لهذه القناع.
### getHeight() {#getHeight--}
```
public abstract int getHeight()
```


يحصل على الارتفاع، بوحدات البكسل، لهذه القناع.

**Returns:**
int - الارتفاع، بوحدات البكسل، لهذه القناع.
### getBounds() {#getBounds--}
```
public abstract Rectangle getBounds()
```


يحصل على الحدود، بوحدات البكسل، لهذه القناع.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - the bounds, in pixels, of this mask.
### getSelectionBounds() {#getSelectionBounds--}
```
public abstract Rectangle getSelectionBounds()
```


يحصل على حدود الجزء المحدد من القناع، بوحدات البكسل.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - the bounds of the selected part of the mask, in pixels.
### isOpaque(int x, int y) {#isOpaque-int-int-}
```
public abstract boolean isOpaque(int x, int y)
```


يتحقق مما إذا كان البكسل المحدد غير شفاف.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| x | int | الإحداثي السيني للبكسل. |
| y | int | الإحداثي الصادي للبكسل. |

**Returns:**
boolean - true إذا كان البكسل المحدد غير شفاف؛ وإلا false.
### isTransparent(int x, int y) {#isTransparent-int-int-}
```
public abstract boolean isTransparent(int x, int y)
```


يتحقق مما إذا كان البكسل المحدد شفافًا.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| x | int | الإحداثي السيني للبكسل. |
| y | int | الإحداثي الصادي للبكسل. |

**Returns:**
boolean - true إذا كان البكسل المحدد شفافًا؛ وإلا false.
### getByteOpacity(int x, int y) {#getByteOpacity-int-int-}
```
public abstract byte getByteOpacity(int x, int y)
```


يحصل على شفافية البكسل المحدد بدقة بايت.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| x | int | الإحداثي السيني للبكسل. |
| y | int | الإحداثي الصادي للبكسل. |

**Returns:**
byte - قيمة بايت، تمثل شفافية البكسل المحدد.
