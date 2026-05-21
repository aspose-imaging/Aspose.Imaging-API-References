---
title: "ImageExtensions"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يحتوي على طرق توسيع للتحويلات المستندة إلى System.Drawing.Image و Image."
type: docs
weight: 18
url: /ar/java/com.aspose.imaging.extensions/imageextensions/
---
**Inheritance:**
java.lang.Object
```
public final class ImageExtensions
```

يحتوي على أساليب امتداد للتحويلات بناءً على `System.Drawing.Image` و `Image`.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [fromJava(BufferedImage image, Rectangle rect)](#fromJava-java.awt.image.BufferedImage-com.aspose.imaging.Rectangle-) | يقوم بتحويل `BufferedImage` إلى `PngImage`. |
| [fromJava(BufferedImage image)](#fromJava-java.awt.image.BufferedImage-) | يقوم بتحويل `BufferedImage` إلى `PngImage`. |
| [toJava(Image image)](#toJava-com.aspose.imaging.Image-) | يقوم بتحويل `Image` إلى `BufferedImage` باستخدام TYPE\_INT\_ARGB. |
| [toJava(Image image, int bufferedImageType)](#toJava-com.aspose.imaging.Image-int-) | يقوم بتحويل `Image` إلى `BufferedImage` باستخدام bufferedImageType. |
| [toJava(Image image, Rectangle subImageRect)](#toJava-com.aspose.imaging.Image-com.aspose.imaging.Rectangle-) | يأخذ الصورة الفرعية من `Image` ويحولها إلى `BufferedImage` باستخدام BufferedImage.TYPE\_INT\_ARGB. |
| [wrap(BufferedImage image)](#wrap-java.awt.image.BufferedImage-) | إنشاء غلاف حول BufferedImage دون نسخ بيانات البكسلات. |
| [toJava(Image image, Rectangle subImageRect, int bufferedImageType)](#toJava-com.aspose.imaging.Image-com.aspose.imaging.Rectangle-int-) | يأخذ الصورة الفرعية من `Image` ويحولها إلى `BufferedImage` باستخدام bufferedImageType. |
| [toJava(Image image, Rectangle subImageRect, BufferedImage dstImage)](#toJava-com.aspose.imaging.Image-com.aspose.imaging.Rectangle-java.awt.image.BufferedImage-) | يأخذ الصورة الفرعية من `Image` ويحولها إلى `BufferedImage` باستخدام bufferedImageType. |
### fromJava(BufferedImage image, Rectangle rect) {#fromJava-java.awt.image.BufferedImage-com.aspose.imaging.Rectangle-}
```
public static RasterImage fromJava(BufferedImage image, Rectangle rect)
```


يقوم بتحويل `BufferedImage` إلى `PngImage`.

تحذير، قد يحصل صورة GDI على حدود أقل مما تملكه `image`. للحصول على جميع أجزاء الصورة استخدم طريقة التوسيع الأكثر أمانًا ToGdiImageFull.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| image | java.awt.image.BufferedImage | الـ `BufferedImage` للتحويل. |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | المستطيل المطلوب. |

**Returns:**
[RasterImage](../../com.aspose.imaging/rasterimage) - The converted `PngImage`.
### fromJava(BufferedImage image) {#fromJava-java.awt.image.BufferedImage-}
```
public static RasterImage fromJava(BufferedImage image)
```


يقوم بتحويل `BufferedImage` إلى `PngImage`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| image | java.awt.image.BufferedImage | الـ `BufferedImage` للتحويل. |

**Returns:**
[RasterImage](../../com.aspose.imaging/rasterimage) - The converted `PngImage`.
### toJava(Image image) {#toJava-com.aspose.imaging.Image-}
```
public static BufferedImage toJava(Image image)
```


يقوم بتحويل `Image` إلى `BufferedImage` باستخدام TYPE\_INT\_ARGB.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | الـ `Image` للتحويل. |

**Returns:**
java.awt.image.BufferedImage - الـ `BufferedImage` المحوّل.
### toJava(Image image, int bufferedImageType) {#toJava-com.aspose.imaging.Image-int-}
```
public static BufferedImage toJava(Image image, int bufferedImageType)
```


يقوم بتحويل الـ `Image` إلى الـ `BufferedImage` باستخدام bufferedImageType. يرجى اختيار `bufferedImageType` من java.awt.image.BufferedImage\#TYPE\_\*\*\*\*

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | الـ `Image` للتحويل. |
| bufferedImageType | int |  |

**Returns:**
java.awt.image.BufferedImage - الـ `BufferedImage` المحوّل.
### toJava(Image image, Rectangle subImageRect) {#toJava-com.aspose.imaging.Image-com.aspose.imaging.Rectangle-}
```
public static BufferedImage toJava(Image image, Rectangle subImageRect)
```


يأخذ الصورة الفرعية من `Image` ويحولها إلى `BufferedImage` باستخدام BufferedImage.TYPE\_INT\_ARGB.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | الـ `Image` للتحويل. |
| subImageRect | [Rectangle](../../com.aspose.imaging/rectangle) | المستطيل الخاص بالصورة الفرعية للتحويل. |

**Returns:**
java.awt.image.BufferedImage - الـ `BufferedImage` المحوّل يحتوي على الصورة الفرعية المأخوذة من `Image`.
### wrap(BufferedImage image) {#wrap-java.awt.image.BufferedImage-}
```
public static RasterImage wrap(BufferedImage image)
```


أنشئ غلافًا حول الـ BufferedImage دون نسخ بيانات البكسلات. يستخدم الـ `image` المصدر في الخلفية لكنه يسمح بالتعامل معه كما هو الحال مع [RasterImage](../../com.aspose.imaging/rasterimage).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| image | java.awt.image.BufferedImage | الصورة المصدر. |

**Returns:**
[RasterImage](../../com.aspose.imaging/rasterimage) - The wrapper RasterImage.
### toJava(Image image, Rectangle subImageRect, int bufferedImageType) {#toJava-com.aspose.imaging.Image-com.aspose.imaging.Rectangle-int-}
```
public static BufferedImage toJava(Image image, Rectangle subImageRect, int bufferedImageType)
```


يأخذ الصورة الفرعية من `Image` ويحولها إلى `BufferedImage` باستخدام bufferedImageType. يرجى اختيار `bufferedImageType` من java.awt.image.BufferedImage\#TYPE\_\*\*\*\*

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | الـ `Image` للتحويل. |
| subImageRect | [Rectangle](../../com.aspose.imaging/rectangle) | المستطيل الخاص بالصورة الفرعية للتحويل. |
| bufferedImageType | int |  |

**Returns:**
java.awt.image.BufferedImage - الـ `BufferedImage` المحوّل يحتوي على الصورة الفرعية المأخوذة من `Image`.
### toJava(Image image, Rectangle subImageRect, BufferedImage dstImage) {#toJava-com.aspose.imaging.Image-com.aspose.imaging.Rectangle-java.awt.image.BufferedImage-}
```
public static BufferedImage toJava(Image image, Rectangle subImageRect, BufferedImage dstImage)
```


يأخذ الصورة الفرعية من `Image` ويحولها إلى `BufferedImage` باستخدام bufferedImageType. يرجى اختيار `bufferedImageType` من java.awt.image.BufferedImage\#TYPE\_\*\*\*\*

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | الـ `Image` للتحويل. |
| subImageRect | [Rectangle](../../com.aspose.imaging/rectangle) | المستطيل الخاص بالصورة الفرعية للتحويل. إذا كان `subImageRect.isEmpty()` سيتم أخذ الصورة كاملة. |
| dstImage | java.awt.image.BufferedImage | الصورة الوجهة. |

**Returns:**
java.awt.image.BufferedImage - الـ `BufferedImage` المحوّل يحتوي على الصورة الفرعية المأخوذة من `Image`.
