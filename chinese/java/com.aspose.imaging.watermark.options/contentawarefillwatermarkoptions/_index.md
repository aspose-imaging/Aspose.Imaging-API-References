---
title: "ContentAwareFillWatermarkOptions"
second_title: "Aspose.Imaging for Java API 参考"
description: "通用 Content Aware Fill 算法选项。"
type: docs
weight: 10
url: /zh/java/com.aspose.imaging.watermark.options/contentawarefillwatermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.watermark.options.WatermarkOptions](../../com.aspose.imaging.watermark.options/watermarkoptions)
```
public class ContentAwareFillWatermarkOptions extends WatermarkOptions
```

通用 Content Aware Fill 算法选项。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ContentAwareFillWatermarkOptions(Point[] mask)](#ContentAwareFillWatermarkOptions-com.aspose.imaging.Point---) | 初始化一个新的 [ContentAwareFillWatermarkOptions](../../com.aspose.imaging.watermark.options/contentawarefillwatermarkoptions) 类实例。 |
| [ContentAwareFillWatermarkOptions(GraphicsPath mask)](#ContentAwareFillWatermarkOptions-com.aspose.imaging.GraphicsPath-) | 初始化一个新的 [ContentAwareFillWatermarkOptions](../../com.aspose.imaging.watermark.options/contentawarefillwatermarkoptions) 类实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getPatchSize()](#getPatchSize--) | 获取补丁大小（应为奇数）。 |
| [setPatchSize(byte value)](#setPatchSize-byte-) | 设置补丁大小（应为奇数）。 |
| [getMaxPaintingAttempts()](#getMaxPaintingAttempts--) | 获取最大绘画尝试次数。 |
| [setMaxPaintingAttempts(int value)](#setMaxPaintingAttempts-int-) | 设置最大绘画尝试次数。 |
| [getInterestArea()](#getInterestArea--) | 获取用于获取补丁的区域。 |
| [setInterestArea(Rectangle value)](#setInterestArea-com.aspose.imaging.Rectangle-) | 设置用于获取补丁的区域。 |

## Example: The example shows how to remove any object from the image using Graphics Path with Content Aware fill algorithm.

``` java
String imageFilePath = "ball.png"; 
try (Image image = Image.load(imageFilePath))
{
    PngImage pngImage = (PngImage)image;

    GraphicsPath mask = new GraphicsPath();
    Figure firstFigure = new Figure();
    firstFigure.addShape(new EllipseShape(new RectangleF(350, 170, 570 - 350, 400 - 170)));
    mask.addFigure(firstFigure);

    ContentAwareFillWatermarkOptions options = new ContentAwareFillWatermarkOptions(mask);
    options.setMaxPaintingAttempts(4);
    try (Image result = WatermarkRemover.paintOver(pngImage, options))
    {
        result.Save(outputPath);
    }
}
```

### ContentAwareFillWatermarkOptions(Point[] mask) {#ContentAwareFillWatermarkOptions-com.aspose.imaging.Point---}
```
public ContentAwareFillWatermarkOptions(Point[] mask)
```


初始化一个新的 [ContentAwareFillWatermarkOptions](../../com.aspose.imaging.watermark.options/contentawarefillwatermarkoptions) 类实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| mask | [Point\[\]](../../com.aspose.imaging/point) | 未知区域的掩码。 |

### ContentAwareFillWatermarkOptions(GraphicsPath mask) {#ContentAwareFillWatermarkOptions-com.aspose.imaging.GraphicsPath-}
```
public ContentAwareFillWatermarkOptions(GraphicsPath mask)
```


初始化一个新的 [ContentAwareFillWatermarkOptions](../../com.aspose.imaging.watermark.options/contentawarefillwatermarkoptions) 类实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| mask | [GraphicsPath](../../com.aspose.imaging/graphicspath) | 未知区域的掩码。 |

### getPatchSize() {#getPatchSize--}
```
public final byte getPatchSize()
```


获取补丁大小（应为奇数）。

值：补丁的大小。

**Returns:**
byte - 补丁大小（应为奇数）。
### setPatchSize(byte value) {#setPatchSize-byte-}
```
public final void setPatchSize(byte value)
```


设置补丁大小（应为奇数）。

值：补丁的大小。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | byte | 补丁大小（应为奇数）。 |

### getMaxPaintingAttempts() {#getMaxPaintingAttempts--}
```
public final int getMaxPaintingAttempts()
```


获取最大绘画尝试次数。算法将选择最佳变体。

值：最大绘画尝试次数。

**Returns:**
int - 最大绘画尝试次数。

**Example: The example shows how to remove any object from the image using Graphics Path with Content Aware fill algorithm.**

``` java
String imageFilePath = "ball.png"; 
try (Image image = Image.load(imageFilePath))
{
    PngImage pngImage = (PngImage)image;

    GraphicsPath mask = new GraphicsPath();
    Figure firstFigure = new Figure();
    firstFigure.addShape(new EllipseShape(new RectangleF(350, 170, 570 - 350, 400 - 170)));
    mask.addFigure(firstFigure);

    ContentAwareFillWatermarkOptions options = new ContentAwareFillWatermarkOptions(mask);
    options.setMaxPaintingAttempts(4);
    try (Image result = WatermarkRemover.paintOver(pngImage, options))
    {
        result.Save(outputPath);
    }
}
```

### setMaxPaintingAttempts(int value) {#setMaxPaintingAttempts-int-}
```
public final void setMaxPaintingAttempts(int value)
```


设置最大绘画尝试次数。算法将选择最佳变体。

值：最大绘画尝试次数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int | 最大绘画尝试次数。 |


**Example: The example shows how to remove any object from the image using Graphics Path with Content Aware fill algorithm.**

``` java
String imageFilePath = "ball.png"; 
try (Image image = Image.load(imageFilePath))
{
    PngImage pngImage = (PngImage)image;

    GraphicsPath mask = new GraphicsPath();
    Figure firstFigure = new Figure();
    firstFigure.addShape(new EllipseShape(new RectangleF(350, 170, 570 - 350, 400 - 170)));
    mask.addFigure(firstFigure);

    ContentAwareFillWatermarkOptions options = new ContentAwareFillWatermarkOptions(mask);
    options.setMaxPaintingAttempts(4);
    try (Image result = WatermarkRemover.paintOver(pngImage, options))
    {
        result.Save(outputPath);
    }
}
```

### getInterestArea() {#getInterestArea--}
```
public final Rectangle getInterestArea()
```


获取用于获取补丁的区域。

值：用于获取补丁的感兴趣区域。

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - the area to take patches.
### setInterestArea(Rectangle value) {#setInterestArea-com.aspose.imaging.Rectangle-}
```
public final void setInterestArea(Rectangle value)
```


设置用于获取补丁的区域。

值：用于获取补丁的感兴趣区域。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) | 用于获取补丁的区域。 |

