---
title: "MaskingResult"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "能够从图像遮罩系统提供结果图像的基抽象类。"
type: docs
weight: 10
url: /zh/java/com.aspose.imaging.masking.result/maskingresult/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject)

**All Implemented Interfaces:**
java.lang.Iterable
```
public abstract class MaskingResult extends DisposableObject implements Iterable<IMaskingLayer>
```

能够从图像遮罩系统提供结果图像的基抽象类。
## 字段

| 字段 | 描述 |
| --- | --- |
| [MaskingOptions](#MaskingOptions) | 掩码选项 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getLayers()](#getLayers--) | 获取层。 |
| [getLength()](#getLength--) | 获取长度。 |
| [get_Item(int index)](#get-Item-int-) | 获取指定索引处的 [IMaskingLayer](../../com.aspose.imaging.masking.result/imaskinglayer)。 |
| [iterator()](#iterator--) | 获取枚举器。 |

## Example: This example shows how to decompose a raster image into multiple images using image masking and the K-means segmentation algorithm.
此示例展示如何使用图像掩码和 K-means 分割算法将光栅图像分解为多个图像。图像掩码是一种用于将背景与前景图像对象分离的图像处理技术。
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.RasterImage image = (com.aspose.imaging.RasterImage) com.aspose.imaging.Image.load(dir + "Blue hills.png");
try {
    com.aspose.imaging.masking.options.AutoMaskingArgs args = new com.aspose.imaging.masking.options.AutoMaskingArgs();

    // 设置簇的数量（分离的对象）。默认值为 2，即前景对象和背景。
    args.setNumberOfObjects(3);

    // 设置最大迭代次数。
    args.setMaxIterationNumber(50);

    // 设置分割方法的精度（可选）。
    args.setPrecision(1);

    // 每个簇（段）将存储为单独的 PNG 文件。
    com.aspose.imaging.imageoptions.PngOptions exportOptions = new com.aspose.imaging.imageoptions.PngOptions();
    exportOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);
    exportOptions.setSource(new com.aspose.imaging.sources.StreamSource(new java.io.ByteArrayInputStream(new byte[0])));

    com.aspose.imaging.masking.options.MaskingOptions maskingOptions = new com.aspose.imaging.masking.options.MaskingOptions();

    // 使用 K-means 聚类。
    // K-means 聚类可以将图像拆分为多个独立的簇（段）。
    maskingOptions.setMethod(com.aspose.imaging.masking.options.SegmentationMethod.KMeans);
    maskingOptions.setDecompose(true);
    maskingOptions.setArgs(args);

    // 背景颜色将为橙色。
    maskingOptions.setBackgroundReplacementColor(com.aspose.imaging.Color.getOrange());
    maskingOptions.setExportOptions(exportOptions);

    // 创建 ImageMasking 类的实例。
    com.aspose.imaging.masking.ImageMasking masking = new com.aspose.imaging.masking.ImageMasking(image);

    // 将源图像划分为多个簇（段）。
    com.aspose.imaging.masking.result.MaskingResult maskingResults = masking.decompose(maskingOptions);
    try
    {
        // 从掩码结果获取图像并保存为 PNG。
        for (int i = 0; i < maskingResults.getLength(); i++) {
            final IMaskingLayer resultsItem = maskingResults.get_Item(i);
            String outputFileName = String.format("Blue hills.Segment%s.png", resultsItem.getObjectNumber());
            Image resultImage = resultsItem.getImage();
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


## Example: This example shows how to specify suggestions for image masking algorithm to improve precision of segmentation (clustering) method.
此示例展示如何为图像掩码算法指定建议，以提高分割（聚类）方法的精度。图像掩码是一种用于将背景与前景图像对象分离的图像处理技术。
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.RasterImage image = (com.aspose.imaging.RasterImage) com.aspose.imaging.Image.load(dir + "Gorilla.bmp");
try {
    com.aspose.imaging.masking.options.AutoMaskingArgs args = new com.aspose.imaging.masking.options.AutoMaskingArgs();

    // 建议 #1。
    // 对图像进行目视分析并设置感兴趣区域。分割结果将仅包含完全位于该区域内的对象。
    args.setObjectsRectangles(new com.aspose.imaging.Rectangle[]
            {
                    new com.aspose.imaging.Rectangle(86, 6, 270, 364),
            });

    // 建议 #2。
    // 对图像进行视觉分析并设置属于分离对象的点。
    args.setObjectsPoints(new com.aspose.imaging.Point[][]
            {
                    new com.aspose.imaging.Point[]{new com.aspose.imaging.Point(103, 326)},
                    new com.aspose.imaging.Point[]{new com.aspose.imaging.Point(280, 43)},
                    new com.aspose.imaging.Point[]{new com.aspose.imaging.Point(319, 86)},
            });

    // 每个簇（段）将存储为单独的 PNG 文件。
    com.aspose.imaging.imageoptions.PngOptions exportOptions = new com.aspose.imaging.imageoptions.PngOptions();
    exportOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);
    exportOptions.setSource(new com.aspose.imaging.sources.StreamSource());

    com.aspose.imaging.masking.options.MaskingOptions maskingOptions = new com.aspose.imaging.masking.options.MaskingOptions();

    // 使用 GraphCut 聚类。
    maskingOptions.setMethod(com.aspose.imaging.masking.options.SegmentationMethod.GraphCut);
    maskingOptions.setDecompose(false);
    maskingOptions.setArgs(args);

    // 背景颜色将为橙色。
    maskingOptions.setBackgroundReplacementColor(com.aspose.imaging.Color.getOrange());
    maskingOptions.setExportOptions(exportOptions);

    // 创建 ImageMasking 类的实例。
    com.aspose.imaging.masking.ImageMasking masking = new com.aspose.imaging.masking.ImageMasking(image);

    // 将源图像划分为多个簇（段）。
    com.aspose.imaging.masking.result.MaskingResult maskingResults = masking.decompose(maskingOptions);

    try
    {
        // 从掩码结果获取图像并保存为 PNG。
        for (int i = 0; i < maskingResults.getLength(); i++) {
            String outputFileName = String.format("Gorilla.Segment%s.png", maskingResults.get_Item(i).getObjectNumber());
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


## Example: Using a segment mask to speed up the segmentation process

``` java
// 遮罩导出选项
com.aspose.imaging.imageoptions.PngOptions exportOptions = new com.aspose.imaging.imageoptions.PngOptions();
exportOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);
exportOptions.setSource(new com.aspose.imaging.sources.StreamSource());

com.aspose.imaging.masking.options.MaskingOptions maskingOptions = new com.aspose.imaging.masking.options.MaskingOptions();

// 使用 GraphCut 聚类。
maskingOptions.setMethod(com.aspose.imaging.masking.options.SegmentationMethod.GraphCut);
maskingOptions.setDecompose(false);
maskingOptions.setArgs(new com.aspose.imaging.masking.options.AutoMaskingArgs());

// 背景颜色将是透明的。
maskingOptions.setBackgroundReplacementColor(com.aspose.imaging.Color.getTransparent());
maskingOptions.setExportOptions(exportOptions);

String dir = "c:\\temp\\";
com.aspose.imaging.RasterImage image = (com.aspose.imaging.RasterImage)com.aspose.imaging.Image.load(dir + "BigImage.jpg");
try
{
    com.aspose.imaging.Size imageSize = image.getSize();

    // 减小图像尺寸以加快分割过程
    image.resizeHeightProportionally(600, com.aspose.imaging.ResizeType.HighQualityResample);

    // 创建 ImageMasking 类的实例。
    com.aspose.imaging.masking.ImageMasking masking = new com.aspose.imaging.masking.ImageMasking(image);

    // 将源图像划分为多个簇（段）。
    com.aspose.imaging.masking.result.MaskingResult maskingResult = masking.decompose(maskingOptions);
    try
    {
        // 获取前景掩码
        com.aspose.imaging.RasterImage foregroundMask = maskingResult.get_Item(1).getMask();
        try
        {
            // 将掩码的大小增加到原始图像的尺寸
            foregroundMask.resize(imageSize.getWidth(), imageSize.getHeight(), com.aspose.imaging.ResizeType.NearestNeighbourResample);

            // 将掩码应用于原始图像以获得前景段
            com.aspose.imaging.RasterImage originImage = (com.aspose.imaging.RasterImage)com.aspose.imaging.Image.load(dir + "BigImage.jpg");
            try
            {
                com.aspose.imaging.masking.ImageMasking.applyMask(originImage, foregroundMask, maskingOptions);
                originImage.save(dir + "BigImage_foreground.png", exportOptions);
            }
            finally
            {
                originImage.close();
            }
        }
        finally
        {
            foregroundMask.close();
        }
    }
    finally
    {
        maskingResult.close();
    }
}
finally
{
    image.close();
}
```


## Example: Saving the masking session to a file for long sessions, as well as for the possibility of resuming the session in another environment.

``` java
String dir = "c:\\temp\\";
String sessionBackupFile = dir + "session.bak";

// 遮罩导出选项
com.aspose.imaging.imageoptions.PngOptions exportOptions = new com.aspose.imaging.imageoptions.PngOptions();
exportOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);
exportOptions.setSource(new com.aspose.imaging.sources.StreamSource());

com.aspose.imaging.masking.options.MaskingOptions maskingOptions = new com.aspose.imaging.masking.options.MaskingOptions();

// 使用 GraphCut 聚类。
maskingOptions.setMethod(com.aspose.imaging.masking.options.SegmentationMethod.GraphCut);
maskingOptions.setDecompose(false);
maskingOptions.setArgs(new com.aspose.imaging.masking.options.AutoMaskingArgs());

// 背景颜色将为橙色。
maskingOptions.setBackgroundReplacementColor(com.aspose.imaging.Color.getOrange());
maskingOptions.setExportOptions(exportOptions);

// 首次启动会话并保存到文件
com.aspose.imaging.RasterImage image = (com.aspose.imaging.RasterImage)com.aspose.imaging.Image.load(dir + "Gorilla.bmp");
try
{
    // 创建 ImageMasking 类的实例。
    com.aspose.imaging.masking.ImageMasking masking = new com.aspose.imaging.masking.ImageMasking(image);

    com.aspose.imaging.masking.IMaskingSession session = masking.createSession(maskingOptions);
    try
    {
        com.aspose.imaging.masking.result.MaskingResult maskingResult = session.decompose();
        try
        {
            com.aspose.imaging.RasterImage segmentImage = maskingResult.get_Item(1).getImage();
            try
            {
                segmentImage.save(dir + "step1.png");
            }
            finally
            {
                segmentImage.close();
            }
        }
        finally
        {
            maskingResult.close();
        }

        session.save(sessionBackupFile);
    }
    finally
    {
        session.dispose();
    }
}
finally
{
    image.close();
}

// 从文件恢复掩码会话
com.aspose.imaging.RasterImage image2 = (com.aspose.imaging.RasterImage)com.aspose.imaging.Image.load(dir + "Gorilla.bmp");
try
{
    // 创建 ImageMasking 类的实例。
    com.aspose.imaging.masking.ImageMasking masking = new com.aspose.imaging.masking.ImageMasking(image2);

    com.aspose.imaging.masking.IMaskingSession session = masking.loadSession(sessionBackupFile);
    try
    {
        com.aspose.imaging.masking.options.AutoMaskingArgs args = new com.aspose.imaging.masking.options.AutoMaskingArgs();

        // 对图像进行视觉分析并设置属于分离对象的点。
        args.setObjectsPoints(new Point[][]
                {
                        new Point[]
                                {
                                        new Point(0, 0), new Point(0, 1), new Point(1, 0),
                                        new Point(1, 1), new Point(2, 0), new Point(2, 1),
                                        new Point(3, 0), new Point(3, 1)
                                },
                });
        com.aspose.imaging.masking.result.MaskingResult maskingResult = session.improveDecomposition(args);
        try
        {
            // 显式传递导出选项，因为它不可序列化
            maskingResult.MaskingOptions.setExportOptions(exportOptions);

            com.aspose.imaging.RasterImage segmentImage = maskingResult.get_Item(1).getImage();
            try
            {
                segmentImage.save(dir + "step2.png");
            }
            finally
            {
                segmentImage.close();
            }
        }
        finally
        {
            maskingResult.close();
        }
    }
    finally
    {
        session.dispose();
    }
}
finally
{
    image2.close();
}
```

### MaskingOptions {#MaskingOptions}
```
public final MaskingOptions MaskingOptions
```


掩码选项

### getLayers() {#getLayers--}
```
public abstract IMaskingLayer[] getLayers()
```


获取层。

值：层。

**Returns:**
com.aspose.imaging.masking.result.IMaskingLayer[] - 层。
### getLength() {#getLength--}
```
public final int getLength()
```


获取长度。

值：长度。

**Returns:**
int - 长度。

**Example: This example shows how to specify suggestions for image masking algorithm to improve precision of segmentation (clustering) method.**
此示例展示如何为图像掩码算法指定建议，以提高分割（聚类）方法的精度。图像掩码是一种用于将背景与前景图像对象分离的图像处理技术。
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.RasterImage image = (com.aspose.imaging.RasterImage) com.aspose.imaging.Image.load(dir + "Gorilla.bmp");
try {
    com.aspose.imaging.masking.options.AutoMaskingArgs args = new com.aspose.imaging.masking.options.AutoMaskingArgs();

    // 建议 #1。
    // 对图像进行目视分析并设置感兴趣区域。分割结果将仅包含完全位于该区域内的对象。
    args.setObjectsRectangles(new com.aspose.imaging.Rectangle[]
            {
                    new com.aspose.imaging.Rectangle(86, 6, 270, 364),
            });

    // 建议 #2。
    // 对图像进行视觉分析并设置属于分离对象的点。
    args.setObjectsPoints(new com.aspose.imaging.Point[][]
            {
                    new com.aspose.imaging.Point[]{new com.aspose.imaging.Point(103, 326)},
                    new com.aspose.imaging.Point[]{new com.aspose.imaging.Point(280, 43)},
                    new com.aspose.imaging.Point[]{new com.aspose.imaging.Point(319, 86)},
            });

    // 每个簇（段）将存储为单独的 PNG 文件。
    com.aspose.imaging.imageoptions.PngOptions exportOptions = new com.aspose.imaging.imageoptions.PngOptions();
    exportOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);
    exportOptions.setSource(new com.aspose.imaging.sources.StreamSource());

    com.aspose.imaging.masking.options.MaskingOptions maskingOptions = new com.aspose.imaging.masking.options.MaskingOptions();

    // 使用 GraphCut 聚类。
    maskingOptions.setMethod(com.aspose.imaging.masking.options.SegmentationMethod.GraphCut);
    maskingOptions.setDecompose(false);
    maskingOptions.setArgs(args);

    // 背景颜色将为橙色。
    maskingOptions.setBackgroundReplacementColor(com.aspose.imaging.Color.getOrange());
    maskingOptions.setExportOptions(exportOptions);

    // 创建 ImageMasking 类的实例。
    com.aspose.imaging.masking.ImageMasking masking = new com.aspose.imaging.masking.ImageMasking(image);

    // 将源图像划分为多个簇（段）。
    com.aspose.imaging.masking.result.MaskingResult maskingResults = masking.decompose(maskingOptions);

    try
    {
        // 从掩码结果获取图像并保存为 PNG。
        for (int i = 0; i < maskingResults.getLength(); i++) {
            String outputFileName = String.format("Gorilla.Segment%s.png", maskingResults.get_Item(i).getObjectNumber());
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

### get_Item(int index) {#get-Item-int-}
```
public final IMaskingLayer get_Item(int index)
```


获取指定索引处的 [IMaskingLayer](../../com.aspose.imaging.masking.result/imaskinglayer)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 索引。值： [IMaskingLayer](../../com.aspose.imaging.masking.result/imatchinglayer)。 |

**Returns:**
[IMaskingLayer](../../com.aspose.imaging.masking.result/imaskinglayer) - The masking layer.
### iterator() {#iterator--}
```
public final Iterator<IMaskingLayer> iterator()
```


获取枚举器。

**Returns:**
java.util.Iterator<com.aspose.imaging.masking.result.IMaskingLayer> - 枚举器。
