---
title: "AutoMaskingArgs"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "表示为自动掩码方法指定的参数"
type: docs
weight: 11
url: /zh/java/com.aspose.imaging.masking.options/automaskingargs/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.masking.options.IMaskingArgs](../../com.aspose.imaging.masking.options/imaskingargs)
```
public class AutoMaskingArgs implements IMaskingArgs
```

表示为自动掩码方法指定的参数
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [AutoMaskingArgs()](#AutoMaskingArgs--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getNumberOfObjects()](#getNumberOfObjects--) | 获取要将初始图像分离成的对象数量（可选），默认值为 2（对象和背景）。 |
| [setNumberOfObjects(int value)](#setNumberOfObjects-int-) | 设置要将初始图像分离成的对象数量（可选），默认值为 2（对象和背景）。 |
| [getObjectsRectangles()](#getObjectsRectangles--) | 获取属于分离对象的对象矩形（可选）。 |
| [setObjectsRectangles(Rectangle[] value)](#setObjectsRectangles-com.aspose.imaging.Rectangle---) | 设置属于分离对象的对象矩形（可选）。 |
| [getObjectsPoints()](#getObjectsPoints--) | 获取属于分离对象的点（可选）NumberOfObjects 坐标属于初始图像的 NumberOfObjects 对象。 |
| [setObjectsPoints(Point[][] value)](#setObjectsPoints-com.aspose.imaging.Point-----) | 设置属于分离对象的点（可选）NumberOfObjects 坐标属于初始图像的 NumberOfObjects 对象。 |
| [getOrphanedPoints()](#getOrphanedPoints--) | 获取不再属于任何对象的点（可选）。 |
| [setOrphanedPoints(Point[] value)](#setOrphanedPoints-com.aspose.imaging.Point---) | 设置不再属于任何对象的点（可选）。 |
| [getPrecision()](#getPrecision--) | 获取分割方法的精度（可选）。 |
| [setPrecision(double value)](#setPrecision-double-) | 设置分割方法的精度（可选）。 |
| [getMaxIterationNumber()](#getMaxIterationNumber--) | 获取最大迭代次数。 |
| [setMaxIterationNumber(int value)](#setMaxIterationNumber-int-) | 设置最大迭代次数。 |

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

### AutoMaskingArgs() {#AutoMaskingArgs--}
```
public AutoMaskingArgs()
```


### getNumberOfObjects() {#getNumberOfObjects--}
```
public final int getNumberOfObjects()
```


获取要将初始图像分离成的对象数量（可选），默认值为 2（对象和背景）。

值：对象数量。

**Returns:**
int - 要将初始图像分离成的对象数量（可选），默认值为 2（对象和背景）。
### setNumberOfObjects(int value) {#setNumberOfObjects-int-}
```
public final void setNumberOfObjects(int value)
```


设置要将初始图像分离成的对象数量（可选），默认值为 2（对象和背景）。

值：对象数量。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 要将初始图像分离成的对象数量（可选），默认值为 2（对象和背景）。 |

### getObjectsRectangles() {#getObjectsRectangles--}
```
public final Rectangle[] getObjectsRectangles()
```


获取属于分离对象的对象矩形（可选）。此参数用于提高分割方法的精度。

值：对象矩形。

**Returns:**
com.aspose.imaging.Rectangle[] - 属于分离对象的对象矩形（可选）。
### setObjectsRectangles(Rectangle[] value) {#setObjectsRectangles-com.aspose.imaging.Rectangle---}
```
public final void setObjectsRectangles(Rectangle[] value)
```


设置属于分离对象的对象矩形（可选）。此参数用于提高分割方法的精度。

值：对象矩形。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Rectangle\[\]](../../com.aspose.imaging/rectangle) | 属于分离对象的对象矩形（可选）。 |

### getObjectsPoints() {#getObjectsPoints--}
```
public final Point[][] getObjectsPoints()
```


获取属于分离对象的点（可选）NumberOfObjects 坐标属于初始图像的 NumberOfObjects 对象。此参数用于提高分割方法的精度。

值：对象点。

**Returns:**
com.aspose.imaging.Point[][] - 属于分离对象的点（可选）NumberOfObjects 坐标属于初始图像的 NumberOfObjects 对象。
### setObjectsPoints(Point[][] value) {#setObjectsPoints-com.aspose.imaging.Point-----}
```
public final void setObjectsPoints(Point[][] value)
```


设置属于分离对象的点（可选）NumberOfObjects 坐标，这些坐标属于初始图像中的 NumberOfObjects 个对象。此参数用于提高分割方法的精度。

值：对象点。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.imaging/point) | 属于分离对象的点（可选）NumberOfObjects 坐标，这些坐标属于初始图像中的 NumberOfObjects 个对象。 |

### getOrphanedPoints() {#getOrphanedPoints--}
```
public final Point[] getOrphanedPoints()
```


获取不再属于任何对象的点（可选）。此参数仅在重新分割的情况下使用。

值：孤立点。

**Returns:**
com.aspose.imaging.Point[] - 不再属于任何对象的点（可选）。
### setOrphanedPoints(Point[] value) {#setOrphanedPoints-com.aspose.imaging.Point---}
```
public final void setOrphanedPoints(Point[] value)
```


设置不再属于任何对象的点（可选）。此参数仅在重新分割的情况下使用。

值：孤立点。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.imaging/point) | 不再属于任何对象的点（可选）。 |

### getPrecision() {#getPrecision--}
```
public final double getPrecision()
```


获取分割方法的精度（可选）。

值：分割方法的精度（可选）。

**Returns:**
double - 分割方法的精度（可选）。
### setPrecision(double value) {#setPrecision-double-}
```
public final void setPrecision(double value)
```


设置分割方法的精度（可选）。

值：分割方法的精度（可选）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 分割方法的精度（可选）。 |

### getMaxIterationNumber() {#getMaxIterationNumber--}
```
public final int getMaxIterationNumber()
```


获取最大迭代次数。

值：最大迭代次数。

**Returns:**
int - 最大迭代次数。
### setMaxIterationNumber(int value) {#setMaxIterationNumber-int-}
```
public final void setMaxIterationNumber(int value)
```


设置最大迭代次数。

值：最大迭代次数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 最大迭代次数。 |

