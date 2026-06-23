---
title: "IMaskingSession"
second_title: "Aspose.Imaging for Java API 参考"
description: "遮罩会话"
type: docs
weight: 12
url: /zh/java/com.aspose.imaging.masking/imaskingsession/
---
**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public interface IMaskingSession extends System.IDisposable
```

遮罩会话
## 方法

| 方法 | 描述 |
| --- | --- |
| [decompose()](#decompose--) | 执行首次粗略分解操作 |
| [decomposeAsync()](#decomposeAsync--) | 创建可执行首次粗略分解操作的异步任务 |
| [improveDecomposition(IMaskingArgs maskingArguments)](#improveDecomposition-com.aspose.imaging.masking.options.IMaskingArgs-) | 执行重新训练分解操作 |
| [improveDecompositionAsync(IMaskingArgs maskingArguments)](#improveDecompositionAsync-com.aspose.imaging.masking.options.IMaskingArgs-) | 创建可执行重新训练分解操作的异步任务 |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | 将会话状态保存到指定的流中。 |
| [save(System.IO.Stream stream)](#save-com.aspose.ms.System.IO.Stream-) | 将会话状态保存到指定的流中。 |
| [save(String filePath)](#save-java.lang.String-) | 将会话状态保存到指定的文件中。 |

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

// 首次启动会话并保存到文件中。
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

// 从文件恢复掩码会话。
com.aspose.imaging.RasterImage image2 = (com.aspose.imaging.RasterImage)com.aspose.imaging.Image.load(dir + "Gorilla.bmp");
try
{
    // 创建 ImageMasking 类的实例。
    com.aspose.imaging.masking.ImageMasking masking = new com.aspose.imaging.masking.ImageMasking(image2);

    com.aspose.imaging.masking.IMaskingSession session = masking.loadSession(sessionBackupFile);
    try
    {
        com.aspose.imaging.masking.options.AutoMaskingArgs args = new com.aspose.imaging.masking.options.AutoMaskingArgs();

        // 对图像进行可视化分析并设置属于分离对象的点。
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
            // 显式传输导出选项，因为它不可序列化。
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

### decompose() {#decompose--}
```
public abstract MaskingResult decompose()
```


执行首次粗略分解操作

**Returns:**
[MaskingResult](../../com.aspose.imaging.masking.result/maskingresult) - Result of masking operation as array of segment image providers.

**Example: Saving the masking session to a file for long sessions, as well as for the possibility of resuming the session in another environment.**

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

// 首次启动会话并保存到文件中。
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

// 从文件恢复掩码会话。
com.aspose.imaging.RasterImage image2 = (com.aspose.imaging.RasterImage)com.aspose.imaging.Image.load(dir + "Gorilla.bmp");
try
{
    // 创建 ImageMasking 类的实例。
    com.aspose.imaging.masking.ImageMasking masking = new com.aspose.imaging.masking.ImageMasking(image2);

    com.aspose.imaging.masking.IMaskingSession session = masking.loadSession(sessionBackupFile);
    try
    {
        com.aspose.imaging.masking.options.AutoMaskingArgs args = new com.aspose.imaging.masking.options.AutoMaskingArgs();

        // 对图像进行可视化分析并设置属于分离对象的点。
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
            // 显式传输导出选项，因为它不可序列化。
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

### decomposeAsync() {#decomposeAsync--}
```
public abstract IMaskingAsyncTask decomposeAsync()
```


创建可执行首次粗略分解操作的异步任务

**Returns:**
[IMaskingAsyncTask](../../com.aspose.imaging.masking/imaskingasynctask) - The asynchronous decompose task
### improveDecomposition(IMaskingArgs maskingArguments) {#improveDecomposition-com.aspose.imaging.masking.options.IMaskingArgs-}
```
public abstract MaskingResult improveDecomposition(IMaskingArgs maskingArguments)
```


执行重新训练分解操作

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| maskingArguments | [IMaskingArgs](../../com.aspose.imaging.masking.options/imaskingargs) | 掩码参数。 |

**Returns:**
[MaskingResult](../../com.aspose.imaging.masking.result/maskingresult) - Result of masking operation as array of segment image providers.

**Example: Saving the masking session to a file for long sessions, as well as for the possibility of resuming the session in another environment.**

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

// 首次启动会话并保存到文件中。
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

// 从文件恢复掩码会话。
com.aspose.imaging.RasterImage image2 = (com.aspose.imaging.RasterImage)com.aspose.imaging.Image.load(dir + "Gorilla.bmp");
try
{
    // 创建 ImageMasking 类的实例。
    com.aspose.imaging.masking.ImageMasking masking = new com.aspose.imaging.masking.ImageMasking(image2);

    com.aspose.imaging.masking.IMaskingSession session = masking.loadSession(sessionBackupFile);
    try
    {
        com.aspose.imaging.masking.options.AutoMaskingArgs args = new com.aspose.imaging.masking.options.AutoMaskingArgs();

        // 对图像进行可视化分析并设置属于分离对象的点。
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
            // 显式传输导出选项，因为它不可序列化。
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

### improveDecompositionAsync(IMaskingArgs maskingArguments) {#improveDecompositionAsync-com.aspose.imaging.masking.options.IMaskingArgs-}
```
public abstract IMaskingAsyncTask improveDecompositionAsync(IMaskingArgs maskingArguments)
```


创建可执行重新训练分解操作的异步任务

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| maskingArguments | [IMaskingArgs](../../com.aspose.imaging.masking.options/imaskingargs) | 掩码参数。 |

**Returns:**
[IMaskingAsyncTask](../../com.aspose.imaging.masking/imaskingasynctask) - The asynchronous decompose task
### save(OutputStream stream) {#save-java.io.OutputStream-}
```
public abstract void save(OutputStream stream)
```


将会话状态保存到指定的流中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | java.io.OutputStream | 流。 |

### save(System.IO.Stream stream) {#save-com.aspose.ms.System.IO.Stream-}
```
public abstract void save(System.IO.Stream stream)
```


将会话状态保存到指定的流中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | com.aspose.ms.System.IO.Stream | 流。 |

### save(String filePath) {#save-java.lang.String-}
```
public abstract void save(String filePath)
```


将会话状态保存到指定的文件中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePath | java.lang.String | 文件路径。 |

