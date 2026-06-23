---
title: "ImageBitMask"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يصف قناع صورة ثنائي."
type: docs
weight: 14
url: /ar/java/com.aspose.imaging.magicwand.imagemasks/imagebitmask/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.magicwand.imagemasks.ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask)
```
public class ImageBitMask extends ImageMask
```

يصف قناع صورة ثنائي.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [ImageBitMask(int width, int height)](#ImageBitMask-int-int-) | يُنشئ مثيلًا جديدًا من الفئة [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) بالعرض والارتفاع المحددين. |
| [ImageBitMask(RasterImage image)](#ImageBitMask-com.aspose.imaging.RasterImage-) | يُنشئ مثيلًا جديدًا من الفئة [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) بحجم صورة [RasterImage](../../com.aspose.imaging/rasterimage) المحددة الموجودة. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getSelectionBounds()](#getSelectionBounds--) | يحصل على حدود الجزء المحدد من القناع، بوحدات البكسل. |
| [get_Item(int x, int y)](#get-Item-int-int-) | يحصل على شفافية البكسل المحدد. |
| [inflate(int size)](#inflate-int-) | يضخم هذه القناع بالمقدار المحدد. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | يقص القناع بالمستطيل المحدد. |
| [deepClone()](#deepClone--) | ينشئ كائنًا جديدًا يكون نسخة من المثيل الحالي. |
| [setMaskPixel(int x, int y, boolean value)](#setMaskPixel-int-int-boolean-) | يضبط الشفافية للبيكسل المحدد. |
| [op_LogicalNot(ImageBitMask a)](#op-LogicalNot-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-) | يعكس القناع. |
| [op_Addition(ImageBitMask a, ImageBitMask b)](#op-Addition-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-) | اتحاد قناعين. |
| [op_Subtraction(ImageBitMask a, ImageBitMask b)](#op-Subtraction-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-) | اطرح القناع الثاني من الأول. |
| [op_Multiply(ImageBitMask a, ImageBitMask b)](#op-Multiply-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-) | تقاطع قناعين. |
| [op_ExclusiveOr(ImageBitMask a, ImageBitMask b)](#op-ExclusiveOr-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-) | اختلاف حصري بين قناعين. |
### ImageBitMask(int width, int height) {#ImageBitMask-int-int-}
```
public ImageBitMask(int width, int height)
```


يُنشئ مثيلًا جديدًا من الفئة [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) بالعرض والارتفاع المحددين.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| width | int | عرض القناع. |
| height | int | ارتفاع القناع. |

### ImageBitMask(RasterImage image) {#ImageBitMask-com.aspose.imaging.RasterImage-}
```
public ImageBitMask(RasterImage image)
```


يُنشئ مثيلًا جديدًا من الفئة [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) بحجم صورة [RasterImage](../../com.aspose.imaging/rasterimage) المحددة الموجودة. سيتم تخزين صورة [RasterImage](../../com.aspose.imaging/rasterimage) المحددة كصورة المصدر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | صورة المصدر. |

### getSelectionBounds() {#getSelectionBounds--}
```
public Rectangle getSelectionBounds()
```


يحصل على حدود الجزء المحدد من القناع، بوحدات البكسل.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - the bounds of the selected part of the mask, in pixels.
### get_Item(int x, int y) {#get-Item-int-int-}
```
public boolean get_Item(int x, int y)
```


يحصل على شفافية البكسل المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| x | int | الإحداثي السيني للبكسل. |
| y | int | الإحداثي ص للبيكسل. القيمة: true إذا كان البيكسل المحدد غير شفاف؛ وإلا false. |

**Returns:**
boolean
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
[ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) - An inflated [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) as [ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask).
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
[ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) - A cropped [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) as [ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask).
### deepClone() {#deepClone--}
```
public Object deepClone()
```


ينشئ كائنًا جديدًا يكون نسخة من المثيل الحالي.

**Returns:**
java.lang.Object - كائن جديد يكون نسخة من هذا المثيل.
### setMaskPixel(int x, int y, boolean value) {#setMaskPixel-int-int-boolean-}
```
public final void setMaskPixel(int x, int y, boolean value)
```


يضبط الشفافية للبيكسل المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| x | int | الإحداثي السيني للبكسل. |
| y | int | الإحداثي الصادي للبكسل. |
| value | boolean | true إذا كان البيكسل المحدد غير شفاف؛ وإلا false. |

### op_LogicalNot(ImageBitMask a) {#op-LogicalNot-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-}
```
public static ImageBitMask op_LogicalNot(ImageBitMask a)
```


يعكس القناع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| a | [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) | القناع الذي سيُعكس. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### op_Addition(ImageBitMask a, ImageBitMask b) {#op-Addition-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-}
```
public static ImageBitMask op_Addition(ImageBitMask a, ImageBitMask b)
```


اتحاد قناعين.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| a | [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) | القناع الأول. |
| b | [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) | القناع الثاني. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### op_Subtraction(ImageBitMask a, ImageBitMask b) {#op-Subtraction-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-}
```
public static ImageBitMask op_Subtraction(ImageBitMask a, ImageBitMask b)
```


اطرح القناع الثاني من الأول.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| a | [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) | القناع الأول. |
| b | [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) | القناع الثاني. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### op_Multiply(ImageBitMask a, ImageBitMask b) {#op-Multiply-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-}
```
public static ImageBitMask op_Multiply(ImageBitMask a, ImageBitMask b)
```


تقاطع قناعين.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| a | [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) | القناع الأول. |
| b | [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) | القناع الثاني. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### op_ExclusiveOr(ImageBitMask a, ImageBitMask b) {#op-ExclusiveOr-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-}
```
public static ImageBitMask op_ExclusiveOr(ImageBitMask a, ImageBitMask b)
```


اختلاف حصري بين قناعين.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| a | [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) | القناع الأول. |
| b | [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) | القناع الثاني. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
