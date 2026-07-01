---
title: "ManualMaskingArgs"
second_title: "Aspose.Imaging for Java API 参考"
description: "表示为手动遮罩方法指定的参数"
type: docs
weight: 15
url: /zh/java/com.aspose.imaging.masking.options/manualmaskingargs/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.masking.options.IMaskingArgs](../../com.aspose.imaging.masking.options/imaskingargs)
```
public class ManualMaskingArgs implements IMaskingArgs
```

表示为手动遮罩方法指定的参数
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ManualMaskingArgs()](#ManualMaskingArgs--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getMask()](#getMask--) | 获取构成遮罩的图形形状集合。 |
| [setMask(GraphicsPath value)](#setMask-com.aspose.imaging.GraphicsPath-) | 设置构成遮罩的图形形状集合。 |

## Example: This example shows how to decompose a raster image into multiple images using image masking and a manual mask.
此示例展示了如何使用图像遮罩和手动遮罩将栅格图像分解为多个图像。图像遮罩是一种用于将背景与前景图像对象分离的图像处理技术。
``` java
String dir = "c:\\temp\\";

// 定义手动遮罩。
com.aspose.imaging.GraphicsPath manualMask = new com.aspose.imaging.GraphicsPath();
com.aspose.imaging.Figure figure = new com.aspose.imaging.Figure();
figure.addShape(new com.aspose.imaging.shapes.EllipseShape(new com.aspose.imaging.RectangleF(50, 50, 40, 40)));
figure.addShape(new com.aspose.imaging.shapes.RectangleShape(new com.aspose.imaging.RectangleF(10, 20, 50, 30)));
manualMask.addFigure(figure);

// 设置手动遮罩。
com.aspose.imaging.masking.options.ManualMaskingArgs args = new com.aspose.imaging.masking.options.ManualMaskingArgs();
args.setMask(manualMask);

com.aspose.imaging.RasterImage image = (com.aspose.imaging.RasterImage) com.aspose.imaging.Image.load(dir + "Blue hills.png");
try {
    com.aspose.imaging.masking.options.MaskingOptions maskingOptions = new com.aspose.imaging.masking.options.MaskingOptions();

    // 使用手动聚类算法。
    maskingOptions.setMethod(com.aspose.imaging.masking.options.SegmentationMethod.Manual);

    // 构成遮罩的所有形状将合并为一个。
    maskingOptions.setDecompose(false);
    maskingOptions.setArgs(args);

    // TrueColor 带 Alpha 的 PNG 图像的最大预期尺寸。
    int estimatedMaxImageSize = image.getWidth() * image.getHeight() * 4;

    // 每个簇（段）将存储为单独的 PNG 文件。
    com.aspose.imaging.imageoptions.PngOptions exportOptions = new com.aspose.imaging.imageoptions.PngOptions();
    exportOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);
    exportOptions.setSource(new com.aspose.imaging.sources.StreamSource(new java.io.ByteArrayInputStream(new byte[estimatedMaxImageSize])));

    // 背景颜色将为橙色。
    maskingOptions.setBackgroundReplacementColor(com.aspose.imaging.Color.getOrange());
    maskingOptions.setExportOptions(exportOptions);

    // 将对源图像的该区域应用遮罩。
    maskingOptions.setMaskingArea(new com.aspose.imaging.Rectangle(50, 50, 120, 120));

    // 创建 ImageMasking 类的实例。
    com.aspose.imaging.masking.ImageMasking masking = new com.aspose.imaging.masking.ImageMasking(image);

    // 将源图像划分为多个簇（段）。
    com.aspose.imaging.masking.result.MaskingResult maskingResults = masking.decompose(maskingOptions);

    try
    {
        // 从掩码结果获取图像并保存为 PNG。
        for (int i = 0; i < maskingResults.getLength(); i++) {
            String outputFileName = String.format("Blue hills.Segment%s.png", maskingResults.get_Item(i).getObjectNumber());
            Image resultImage = maskingResults.get_Item(i).getImage();
            try {
                resultImage.save(dir + outputFileName);
            } finally {
                resultImage.close();
            }
        }
    }
    finally
    {
        maskingResults.close();
    }
} finally {
    image.close();
}
```

### ManualMaskingArgs() {#ManualMaskingArgs--}
```
public ManualMaskingArgs()
```


### getMask() {#getMask--}
```
public final GraphicsPath getMask()
```


获取构成遮罩的图形形状集合。

值：遮罩。

**Returns:**
[GraphicsPath](../../com.aspose.imaging/graphicspath) - the set of graphic shapes that form mask.
### setMask(GraphicsPath value) {#setMask-com.aspose.imaging.GraphicsPath-}
```
public final void setMask(GraphicsPath value)
```


设置构成遮罩的图形形状集合。

值：遮罩。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [GraphicsPath](../../com.aspose.imaging/graphicspath) | 构成遮罩的图形形状集合。 |

