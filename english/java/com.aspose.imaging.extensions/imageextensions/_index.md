---
title: ImageExtensions
second_title: Aspose.Imaging for Java API Reference
description: Contains extension methods for conversions based on System.Drawing.Image and Image.
type: docs
weight: 18
url: /java/com.aspose.imaging.extensions/imageextensions/
---
**Inheritance:**
java.lang.Object
```
public final class ImageExtensions
```

Contains extension methods for conversions based on `System.Drawing.Image` and `Image`.
## Methods

| Method | Description |
| --- | --- |
| [fromJava(BufferedImage image, Rectangle rect)](#fromJava-java.awt.image.BufferedImage-com.aspose.imaging.Rectangle-) | Converts the `BufferedImage` to the `PngImage`. |
| [fromJava(BufferedImage image)](#fromJava-java.awt.image.BufferedImage-) | Converts the `BufferedImage` to the `PngImage`. |
| [toJava(Image image)](#toJava-com.aspose.imaging.Image-) | Converts the `Image` to the `BufferedImage` with TYPE\_INT\_ARGB. |
| [toJava(Image image, int bufferedImageType)](#toJava-com.aspose.imaging.Image-int-) | Converts the `Image` to the `BufferedImage` with bufferedImageType. |
| [toJava(Image image, Rectangle subImageRect)](#toJava-com.aspose.imaging.Image-com.aspose.imaging.Rectangle-) | Takes the subimage from `Image` and converts to the `BufferedImage` with BufferedImage.TYPE\_INT\_ARGB. |
| [toJava(Image image, Rectangle subImageRect, int bufferedImageType)](#toJava-com.aspose.imaging.Image-com.aspose.imaging.Rectangle-int-) | Takes the subimage from `Image` and converts to the `BufferedImage` with bufferedImageType. |
### fromJava(BufferedImage image, Rectangle rect) {#fromJava-java.awt.image.BufferedImage-com.aspose.imaging.Rectangle-}
```
public static RasterImage fromJava(BufferedImage image, Rectangle rect)
```


Converts the `BufferedImage` to the `PngImage`.

Warning, the GDI image may get lower bounds than `image` has. To get all parts of the image use more safe extension method ToGdiImageFull.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| image | java.awt.image.BufferedImage | The `BufferedImage` to convert. |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | The required rectangle. |

**Returns:**
[RasterImage](../../com.aspose.imaging/rasterimage) - The converted `PngImage`.
### fromJava(BufferedImage image) {#fromJava-java.awt.image.BufferedImage-}
```
public static RasterImage fromJava(BufferedImage image)
```


Converts the `BufferedImage` to the `PngImage`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| image | java.awt.image.BufferedImage | The `BufferedImage` to convert. |

**Returns:**
[RasterImage](../../com.aspose.imaging/rasterimage) - The converted `PngImage`.
### toJava(Image image) {#toJava-com.aspose.imaging.Image-}
```
public static BufferedImage toJava(Image image)
```


Converts the `Image` to the `BufferedImage` with TYPE\_INT\_ARGB.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | The `Image` to convert. |

**Returns:**
java.awt.image.BufferedImage - The converted `BufferedImage`.
### toJava(Image image, int bufferedImageType) {#toJava-com.aspose.imaging.Image-int-}
```
public static BufferedImage toJava(Image image, int bufferedImageType)
```


Converts the `Image` to the `BufferedImage` with bufferedImageType. Please choose `bufferedImageType` from java.awt.image.BufferedImage\#TYPE\_\*\*\*\*

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | The `Image` to convert. |
| bufferedImageType | int |  |

**Returns:**
java.awt.image.BufferedImage - The converted `BufferedImage`.
### toJava(Image image, Rectangle subImageRect) {#toJava-com.aspose.imaging.Image-com.aspose.imaging.Rectangle-}
```
public static BufferedImage toJava(Image image, Rectangle subImageRect)
```


Takes the subimage from `Image` and converts to the `BufferedImage` with BufferedImage.TYPE\_INT\_ARGB.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | The `Image` to convert. |
| subImageRect | [Rectangle](../../com.aspose.imaging/rectangle) | The rectangle of subimage to convert. |

**Returns:**
java.awt.image.BufferedImage - The converted `BufferedImage` contains subimage taken from `Image`.
### toJava(Image image, Rectangle subImageRect, int bufferedImageType) {#toJava-com.aspose.imaging.Image-com.aspose.imaging.Rectangle-int-}
```
public static BufferedImage toJava(Image image, Rectangle subImageRect, int bufferedImageType)
```


Takes the subimage from `Image` and converts to the `BufferedImage` with bufferedImageType. Please choose `bufferedImageType` from java.awt.image.BufferedImage\#TYPE\_\*\*\*\*

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | The `Image` to convert. |
| subImageRect | [Rectangle](../../com.aspose.imaging/rectangle) | The rectangle of subimage to convert. |
| bufferedImageType | int |  |

**Returns:**
java.awt.image.BufferedImage - The converted `BufferedImage` contains subimage taken from `Image`.
