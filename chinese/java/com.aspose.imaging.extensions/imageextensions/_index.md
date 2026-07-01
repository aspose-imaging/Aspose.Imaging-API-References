---
title: "ImageExtensions"
second_title: "Aspose.Imaging for Java API 参考"
description: "包含基于 System.Drawing.Image 和 Image 的转换扩展方法。"
type: docs
weight: 18
url: /zh/java/com.aspose.imaging.extensions/imageextensions/
---
**Inheritance:**
java.lang.Object
```
public final class ImageExtensions
```

包含基于 `System.Drawing.Image` 和 `Image` 的转换扩展方法。
## 方法

| 方法 | 描述 |
| --- | --- |
| [fromJava(BufferedImage image, Rectangle rect)](#fromJava-java.awt.image.BufferedImage-com.aspose.imaging.Rectangle-) | 将 `BufferedImage` 转换为 `PngImage`。 |
| [fromJava(BufferedImage image)](#fromJava-java.awt.image.BufferedImage-) | 将 `BufferedImage` 转换为 `PngImage`。 |
| [toJava(Image image)](#toJava-com.aspose.imaging.Image-) | 将 `Image` 转换为 `BufferedImage`，使用 TYPE\_INT\_ARGB。 |
| [toJava(Image image, int bufferedImageType)](#toJava-com.aspose.imaging.Image-int-) | 将 `Image` 转换为 `BufferedImage`，使用 bufferedImageType。 |
| [toJava(Image image, Rectangle subImageRect)](#toJava-com.aspose.imaging.Image-com.aspose.imaging.Rectangle-) | 从 `Image` 中获取子图像并转换为 `BufferedImage`，使用 BufferedImage.TYPE\_INT\_ARGB。 |
| [wrap(BufferedImage image)](#wrap-java.awt.image.BufferedImage-) | 创建一个 BufferedImage 的包装器，而不复制像素数据。 |
| [toJava(Image image, Rectangle subImageRect, int bufferedImageType)](#toJava-com.aspose.imaging.Image-com.aspose.imaging.Rectangle-int-) | 从 `Image` 中获取子图像并转换为 `BufferedImage`，使用 bufferedImageType。 |
| [toJava(Image image, Rectangle subImageRect, BufferedImage dstImage)](#toJava-com.aspose.imaging.Image-com.aspose.imaging.Rectangle-java.awt.image.BufferedImage-) | 从 `Image` 中获取子图像并转换为 `BufferedImage`，使用 bufferedImageType。 |
### fromJava(BufferedImage image, Rectangle rect) {#fromJava-java.awt.image.BufferedImage-com.aspose.imaging.Rectangle-}
```
public static RasterImage fromJava(BufferedImage image, Rectangle rect)
```


将 `BufferedImage` 转换为 `PngImage`。

警告，GDI 图像的边界可能小于 `image` 的边界。要获取图像的所有部分，请使用更安全的扩展方法 ToGdiImageFull。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 图像 | java.awt.image.BufferedImage | 要转换的 `BufferedImage`。 |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | 所需的矩形。 |

**Returns:**
[RasterImage](../../com.aspose.imaging/rasterimage) - The converted `PngImage`.
### fromJava(BufferedImage image) {#fromJava-java.awt.image.BufferedImage-}
```
public static RasterImage fromJava(BufferedImage image)
```


将 `BufferedImage` 转换为 `PngImage`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 图像 | java.awt.image.BufferedImage | 要转换的 `BufferedImage`。 |

**Returns:**
[RasterImage](../../com.aspose.imaging/rasterimage) - The converted `PngImage`.
### toJava(Image image) {#toJava-com.aspose.imaging.Image-}
```
public static BufferedImage toJava(Image image)
```


将 `Image` 转换为 `BufferedImage`，使用 TYPE\_INT\_ARGB。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | 要转换的 `Image`。 |

**Returns:**
java.awt.image.BufferedImage - 已转换的 `BufferedImage`。
### toJava(Image image, int bufferedImageType) {#toJava-com.aspose.imaging.Image-int-}
```
public static BufferedImage toJava(Image image, int bufferedImageType)
```


将 `Image` 转换为 `BufferedImage`，使用 bufferedImageType。请从 java.awt.image.BufferedImage\#TYPE\_\*\*\*\* 中选择 `bufferedImageType`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | 要转换的 `Image`。 |
| bufferedImageType | int |  |

**Returns:**
java.awt.image.BufferedImage - 已转换的 `BufferedImage`。
### toJava(Image image, Rectangle subImageRect) {#toJava-com.aspose.imaging.Image-com.aspose.imaging.Rectangle-}
```
public static BufferedImage toJava(Image image, Rectangle subImageRect)
```


从 `Image` 中获取子图像并转换为 `BufferedImage`，使用 BufferedImage.TYPE\_INT\_ARGB。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | 要转换的 `Image`。 |
| subImageRect | [Rectangle](../../com.aspose.imaging/rectangle) | 要转换的子图像矩形。 |

**Returns:**
java.awt.image.BufferedImage - 已转换的 `BufferedImage` 包含从 `Image` 获取的子图像。
### wrap(BufferedImage image) {#wrap-java.awt.image.BufferedImage-}
```
public static RasterImage wrap(BufferedImage image)
```


创建一个 BufferedImage 的包装器，而不复制像素数据。它在内部使用源 `image`，但允许像操作 [RasterImage](../../com.aspose.imaging/rasterimage) 那样对其进行操作。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 图像 | java.awt.image.BufferedImage | 源图像。 |

**Returns:**
[RasterImage](../../com.aspose.imaging/rasterimage) - The wrapper RasterImage.
### toJava(Image image, Rectangle subImageRect, int bufferedImageType) {#toJava-com.aspose.imaging.Image-com.aspose.imaging.Rectangle-int-}
```
public static BufferedImage toJava(Image image, Rectangle subImageRect, int bufferedImageType)
```


从 `Image` 中获取子图像并转换为 `BufferedImage`，使用 bufferedImageType。请从 java.awt.image.BufferedImage\#TYPE\_\*\*\*\* 中选择 `bufferedImageType`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | 要转换的 `Image`。 |
| subImageRect | [Rectangle](../../com.aspose.imaging/rectangle) | 要转换的子图像矩形。 |
| bufferedImageType | int |  |

**Returns:**
java.awt.image.BufferedImage - 已转换的 `BufferedImage` 包含从 `Image` 获取的子图像。
### toJava(Image image, Rectangle subImageRect, BufferedImage dstImage) {#toJava-com.aspose.imaging.Image-com.aspose.imaging.Rectangle-java.awt.image.BufferedImage-}
```
public static BufferedImage toJava(Image image, Rectangle subImageRect, BufferedImage dstImage)
```


从 `Image` 中获取子图像并转换为 `BufferedImage`，使用 bufferedImageType。请从 java.awt.image.BufferedImage\#TYPE\_\*\*\*\* 中选择 `bufferedImageType`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | 要转换的 `Image`。 |
| subImageRect | [Rectangle](../../com.aspose.imaging/rectangle) | 要转换的子图像矩形。如果 `subImageRect.isEmpty()`，将使用整幅图像。 |
| dstImage | java.awt.image.BufferedImage | 目标图像。 |

**Returns:**
java.awt.image.BufferedImage - 已转换的 `BufferedImage` 包含从 `Image` 获取的子图像。
