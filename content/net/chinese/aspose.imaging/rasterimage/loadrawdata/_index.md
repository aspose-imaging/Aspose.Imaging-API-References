---
title: LoadRawData
second_title: Aspose.Imaging for .NET API 参考
description: 加载原始数据
type: docs
weight: 420
url: /zh/aspose.imaging/rasterimage/loadrawdata/
---
## LoadRawData(Rectangle, RawDataSettings, IPartialRawDataLoader) {#loadrawdata}

加载原始数据。

```csharp
public void LoadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, 
    IPartialRawDataLoader rawDataLoader)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| rectangle | Rectangle | 要从中加载原始数据的矩形。 |
| rawDataSettings | RawDataSettings | 用于加载数据的原始数据设置。请注意，如果数据不是指定的格式，则将执行数据转换。 |
| rawDataLoader | IPartialRawDataLoader | 原始数据加载器。 |

### 例子

以下示例显示如何使用 RawDataSettings 从原始图像数据中提取像素。例如，考虑计算图像的完全透明像素的问题。

```csharp
[C#]

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(@"c:\temp\GrayscaleWithAlpha.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;
    Aspose.Imaging.RawDataSettings settings = rasterImage.RawDataSettings;

    TransparentPixelRawDataCounter rawDataLoader = new TransparentPixelRawDataCounter(settings);

    // 加载整个图像的像素。图像的任何矩形部分都可以指定为 Aspose.Imaging.RasterImage.LoadRawData 方法的参数。
    rasterImage.LoadRawData(rasterImage.Bounds, settings, rawDataLoader);

    System.Console.WriteLine("The number of fully transparent pixels is {0}", rawDataLoader.Count);
    System.Console.WriteLine("The total number of pixels is {0}", image.Width * image.Height);
}

// 如果是原始数据，计数器可能如下所示：
/// <summary>
/// 计算 alpha 通道值为 0 的完全透明像素的数量。
/// </summary>
private class TransparentPixelRawDataCounter : IPartialRawDataLoader
{
    /// <summary>
    /// 完全透明像素的数量。
    /// </summary>
    private int count;

    /// <summary>
    /// 加载图像的原始数据设置。
    /// </summary>
    private Aspose.Imaging.RawDataSettings rawDataSettings;

    /// <summary>
    /// 获取完全透明像素的数量。
    /// </summary>
    public int Count
    {
        get { return this.count; }
    }

    /// <summary>
    /// 初始化 <see TransparentPixelRawDataCounter /> 的新实例班级。
    /// </summary>
    /// <param name="settings">原始数据设置允许从原始数据中提取颜色成分。</param>
    public TransparentPixelRawDataCounter(Aspose.Imaging.RawDataSettings settings)
    {
        this.rawDataSettings = settings;
        this.count = 0;
    }

    /// <summary>
    /// 处理加载的原始数据。每次加载新的原始数据部分时都会回调此方法。
    /// </summary>
    /// <param name="dataRectangle">原始数据矩形。</param>
    /// <param name="data">原始数据。</param>
    /// <param name="start">起始数据点。</param>
    /// <param name="end">结束数据点。</param>
    public void Process(Aspose.Imaging.Rectangle dataRectangle, byte[] data, Aspose.Imaging.Point start, Aspose.Imaging.Point end)
    {
        int[] channelBits = this.rawDataSettings.PixelDataFormat.ChannelBits;

        // 这里只考虑简单的格式来简化代码。
        // 让我们只考虑每个样本 8 位的图像。
        for (int i = 0; i < channelBits.Length; i++)
        {
            if (channelBits[i] != 8)
            {
                throw new System.NotSupportedException();
            }
        }

        switch (this.rawDataSettings.PixelDataFormat.PixelFormat)
        {
            case PixelFormat.Rgb:
            case PixelFormat.Bgr:
                {
                    if (channelBits.Length == 4)
                    {
                        // ARGB
                        for (int i = 0; i < data.Length; i += 4)
                        {
                            // Alpha 通道最后存储，在颜色分量之后。
                            if (data[i + 3] == 0)
                            {
                                this.count++;
                            }
                        }
                    }
                }
                break;

            case PixelFormat.Grayscale:
                {
                    if (channelBits.Length == 2)
                    {
                        //灰度阿尔法
                        for (int i = 0; i < data.Length; i += 2)
                        {
                            // Alpha 通道最后存储，在颜色分量之后。
                            if (data[i + 1] == 0)
                            {
                                this.count++;
                            }
                        }
                    }
                }
                break;

            default:
                throw new System.ArgumentOutOfRangeException("PixelFormat");
        }
    }

    /// <summary>
    /// 处理加载的原始数据。每次加载新的原始数据部分时都会回调此方法。
    /// </summary>
    /// <param name="dataRectangle">原始数据矩形。</param>
    /// <param name="data">原始数据。</param>
    /// <param name="start">起始数据点。</param>
    /// <param name="end">结束数据点。</param>
    /// <param name="loadOptions">加载选项。</param>
    public void Process(Aspose.Imaging.Rectangle dataRectangle, byte[] data, Aspose.Imaging.Point start, Aspose.Imaging.Point end, Aspose.Imaging.LoadOptions loadOptions)
    {
        this.Process(dataRectangle, data, start, end);
    }
}
```

### 也可以看看

* struct [Rectangle](../../rectangle)
* class [RawDataSettings](../../rawdatasettings)
* interface [IPartialRawDataLoader](../../ipartialrawdataloader)
* class [RasterImage](../../rasterimage)
* 命名空间 [Aspose.Imaging](../../rasterimage)
* 部件 [Aspose.Imaging](../../../)

---

## LoadRawData(Rectangle, Rectangle, RawDataSettings, IPartialRawDataLoader) {#loadrawdata_1}

加载原始数据。

```csharp
public void LoadRawData(Rectangle rectangle, Rectangle destImageBounds, 
    RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| rectangle | Rectangle | 要从中加载原始数据的矩形。 |
| destImageBounds | Rectangle | dest 图像边界。 |
| rawDataSettings | RawDataSettings | 用于加载数据的原始数据设置。请注意，如果数据不是指定的格式，则将执行数据转换。 |
| rawDataLoader | IPartialRawDataLoader | 原始数据加载器。 |

### 也可以看看

* struct [Rectangle](../../rectangle)
* class [RawDataSettings](../../rawdatasettings)
* interface [IPartialRawDataLoader](../../ipartialrawdataloader)
* class [RasterImage](../../rasterimage)
* 命名空间 [Aspose.Imaging](../../rasterimage)
* 部件 [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
