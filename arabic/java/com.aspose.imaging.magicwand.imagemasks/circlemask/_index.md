---
title: "CircleMask"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يصف قناعًا دائريًا."
type: docs
weight: 10
url: /ar/java/com.aspose.imaging.magicwand.imagemasks/circlemask/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.magicwand.imagemasks.ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask)
```
public class CircleMask extends ImageMask
```

يصف قناعًا دائريًا.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [CircleMask(int x, int y, int radius)](#CircleMask-int-int-int-) | ينشئ نسخة جديدة من الفئة [CircleMask](../../com.aspose.imaging.magicwand.imagemasks/circlemask) مع نقطة المركز المحددة والنصف قطر. |
| [CircleMask(Point center, int radius)](#CircleMask-com.aspose.imaging.Point-int-) | ينشئ نسخة جديدة من الفئة [CircleMask](../../com.aspose.imaging.magicwand.imagemasks/circlemask) مع نقطة المركز المحددة والنصف قطر. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getSelectionBounds()](#getSelectionBounds--) | يحصل على الحدود، بوحدات البكسل، لهذه القناع. |
| [get_Item(int x, int y)](#get-Item-int-int-) | يحصل على شفافية البكسل المحدد. |
| [inflate(int size)](#inflate-int-) | يضخم هذه القناع بالمقدار المحدد. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | يقص القناع بالمستطيل المحدد. |
| [deepClone()](#deepClone--) | ينشئ كائنًا جديدًا يكون نسخة من المثيل الحالي. |
### CircleMask(int x, int y, int radius) {#CircleMask-int-int-int-}
```
public CircleMask(int x, int y, int radius)
```


ينشئ نسخة جديدة من الفئة [CircleMask](../../com.aspose.imaging.magicwand.imagemasks/circlemask) مع نقطة المركز المحددة والنصف قطر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| x | int | الإحداثي السيني لنقطة المركز للمنطقة المحددة. |
| y | int | الإحداثي الصادي لنقطة المركز للمنطقة المحددة. |
| نصف القطر | int | نصف قطر المنطقة المحددة. |

### CircleMask(Point center, int radius) {#CircleMask-com.aspose.imaging.Point-int-}
```
public CircleMask(Point center, int radius)
```


ينشئ نسخة جديدة من الفئة [CircleMask](../../com.aspose.imaging.magicwand.imagemasks/circlemask) مع نقطة المركز المحددة والنصف قطر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| center | [Point](../../com.aspose.imaging/point) | نقطة المركز للمنطقة المحددة. |
| نصف القطر | int | نصف قطر المنطقة المحددة. |

### getSelectionBounds() {#getSelectionBounds--}
```
public Rectangle getSelectionBounds()
```


يحصل على الحدود، بوحدات البكسل، لهذه القناع.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - the bounds, in pixels, of this mask.
### get_Item(int x, int y) {#get-Item-int-int-}
```
public boolean get_Item(int x, int y)
```


يحصل على شفافية البكسل المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| x | int | الإحداثي السيني للبكسل. |
| y | int | الإحداثي الصادي للبكسل. |

**Returns:**
boolean - true إذا كان البكسل المحدد غير شفاف؛ وإلا false.
### inflate(int size) {#inflate-int-}
```
public ImageMask inflate(int size)
```


يضخم هذه القناع بالمقدار المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| size | int | المقدار لتضخيم هذه القناع. |

**Returns:**
[ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) - An inflated CircleMask as ImageMask.
### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public ImageMask crop(Rectangle rectangle)
```


يقص القناع بالمستطيل المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | المستطيل المحدد. |

**Returns:**
[ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) - A cropped CircleMask or ImageBitMask as ImageMask. As ImageBitMask may be returned, fluent call is recommended.
### deepClone() {#deepClone--}
```
public Object deepClone()
```


ينشئ كائنًا جديدًا يكون نسخة من المثيل الحالي.

**Returns:**
java.lang.Object - كائن جديد يكون نسخة من هذا المثيل.
