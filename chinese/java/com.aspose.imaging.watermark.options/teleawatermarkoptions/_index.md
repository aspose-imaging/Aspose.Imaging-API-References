---
title: "TeleaWatermarkOptions"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "常见的 Telea 算法选项。"
type: docs
weight: 11
url: /zh/java/com.aspose.imaging.watermark.options/teleawatermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.watermark.options.WatermarkOptions](../../com.aspose.imaging.watermark.options/watermarkoptions)
```
public class TeleaWatermarkOptions extends WatermarkOptions
```

常见的 Telea 算法选项。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [TeleaWatermarkOptions(Point[] mask)](#TeleaWatermarkOptions-com.aspose.imaging.Point---) | 初始化一个新的 [TeleaWatermarkOptions](../../com.aspose.imaging.watermark.options/teleawatermarkoptions) 类实例。 |
| [TeleaWatermarkOptions(GraphicsPath mask)](#TeleaWatermarkOptions-com.aspose.imaging.GraphicsPath-) | 初始化一个新的 [TeleaWatermarkOptions](../../com.aspose.imaging.watermark.options/teleawatermarkoptions) 类实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getHalfPatchSize()](#getHalfPatchSize--) | 获取半补丁大小。 |
| [setHalfPatchSize(int value)](#setHalfPatchSize-int-) | 设置半补丁大小。 |

## Example: The example shows how to remove any object from the image using Graphics Path with Telea algorithm.

``` java
String imageFilePath = "ball.png";
String outputPath = "no-watermark.png";
try (Image image = Image.load(imageFilePath))
{
    PngImage pngImage = (PngImage) image;
    GraphicsPath mask = new GraphicsPath();
    Figure firstFigure = new Figure();
    firstFigure.addShape(new EllipseShape(new RectangleF(350, 170, 570 - 350, 400 - 170)));
    mask.addFigure(firstFigure);

    TeleaWatermarkOptions options = new TeleaWatermarkOptions(mask);

    try (RasterImage result = WatermarkRemover.paintOver(pngImage, options))
    {
        result.save(outputPath);
    }
}

```

### TeleaWatermarkOptions(Point[] mask) {#TeleaWatermarkOptions-com.aspose.imaging.Point---}
```
public TeleaWatermarkOptions(Point[] mask)
```


初始化一个新的 [TeleaWatermarkOptions](../../com.aspose.imaging.watermark.options/teleawatermarkoptions) 类实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| mask | [Point\[\]](../../com.aspose.imaging/point) | 未知区域的掩码。 |

### TeleaWatermarkOptions(GraphicsPath mask) {#TeleaWatermarkOptions-com.aspose.imaging.GraphicsPath-}
```
public TeleaWatermarkOptions(GraphicsPath mask)
```


初始化一个新的 [TeleaWatermarkOptions](../../com.aspose.imaging.watermark.options/teleawatermarkoptions) 类实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| mask | [GraphicsPath](../../com.aspose.imaging/graphicspath) | 未知区域的掩码。 |

### getHalfPatchSize() {#getHalfPatchSize--}
```
public final int getHalfPatchSize()
```


获取半补丁大小。

值：补丁大小。

**Returns:**
int - 半补丁大小。
### setHalfPatchSize(int value) {#setHalfPatchSize-int-}
```
public final void setHalfPatchSize(int value)
```


设置半补丁大小。

值：补丁大小。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 半补丁大小。 |

