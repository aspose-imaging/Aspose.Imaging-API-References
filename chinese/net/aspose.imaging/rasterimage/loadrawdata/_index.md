---
title: "RasterImage.LoadRawData"
second_title: "Aspose.Imaging for .NET API 参考"
description: "RasterImage 方法。加载原始数据"
type: docs
weight: 470
url: /zh/net/aspose.imaging/rasterimage/loadrawdata/
---
## LoadRawData(Rectangle, RawDataSettings, IPartialRawDataLoader) {#loadrawdata}

加载原始数据。

```csharp
public void LoadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, 
    IPartialRawDataLoader rawDataLoader)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 矩形 | Rectangle | 用于加载原始数据的矩形。 |
| rawDataSettings | RawDataSettings | 用于已加载数据的原始数据设置。注意，如果数据不是指定的格式，则会执行数据转换。 |
| rawDataLoader | IPartialRawDataLoader | 原始数据加载器。 |

## 示例

下面的示例展示了如何使用 RawDataSettings 从原始图像数据中提取像素。例如，考虑统计图像中完全透明像素的情况。

```csharp
[C#]

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(@"c:\temp\GrayscaleWithAlpha.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;
    Aspose.Imaging.RawDataSettings settings = rasterImage.RawDataSettings;

    TransparentPixelRawDataCounter rawDataLoader = new TransparentPixelRawDataCounter(settings);

    // 加载整幅图像的像素。图像的任意矩形区域都可以作为 Aspose.Imaging.RasterImage.LoadRawData 方法的参数指定。
    rasterImage.LoadRawData(rasterImage.Bounds, settings, rawDataLoader);

    System.Console.WriteLine("The number of fully transparent pixels is {0}", rawDataLoader.Count);
    System.Console.WriteLine("The total number of pixels is {0}", image.Width * image.Height);
}

// 对于原始数据，计数器可能如下所示：
/// <summary>
/// 统计 alpha 通道值为 0 的完全透明像素数量。
/// </summary>
private class TransparentPixelRawDataCounter : IPartialRawDataLoader
{
    /// <summary>
    /// 完全透明像素的数量。
    /// </summary>
    private int count;

    /// <summary>
    /// 已加载图像的原始数据设置。
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
    /// 初始化 <see TransparentPixelRawDataCounter /> 类的新实例。
    /// </summary>
    /// <param name=\"settings\">原始数据设置允许从原始数据中提取颜色分量。</param>
    public TransparentPixelRawDataCounter(Aspose.Imaging.RawDataSettings settings)
    {
        this.rawDataSettings = settings;
        this.count = 0;
    }

    /// <summary>
    /// 处理已加载的原始数据。每当加载新的原始数据块时，都会回调此方法。
    /// </summary>
    /// <param name=\"dataRectangle\">原始数据矩形。</param>
    /// <param name=\"data\">原始数据。</param>
    /// <param name=\"start\">起始数据点。</param>
    /// <param name=\"end\">结束数据点。</param>
    public void Process(Aspose.Imaging.Rectangle dataRectangle, byte[] data, Aspose.Imaging.Point start, Aspose.Imaging.Point end)
    {
        int[] channelBits = this.rawDataSettings.PixelDataFormat.ChannelBits;

        // 此处仅考虑简单格式，以简化代码。
        // 我们仅考虑每个样本 8 位的图像。
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
                            // Alpha 通道存储在最后，位于颜色分量之后。
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
                        // 灰度 Alpha
                        for (int i = 0; i < data.Length; i += 2)
                        {
                            // Alpha 通道存储在最后，位于颜色分量之后。
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
    /// 处理已加载的原始数据。每当加载新的原始数据块时，都会回调此方法。
    /// </summary>
    /// <param name=\"dataRectangle\">原始数据矩形。</param>
    /// <param name=\"data\">原始数据。</param>
    /// <param name=\"start\">起始数据点。</param>
    /// <param name=\"end\">结束数据点。</param>
    /// <param name="loadOptions">加载选项。</param>
    public void Process(Aspose.Imaging.Rectangle dataRectangle, byte[] data, Aspose.Imaging.Point start, Aspose.Imaging.Point end, Aspose.Imaging.LoadOptions loadOptions)
    {
        this.Process(dataRectangle, data, start, end);
    }
}
```

### 另请参见

* struct [Rectangle](../../rectangle/)
* class [RawDataSettings](../../rawdatasettings/)
* interface [IPartialRawDataLoader](../../ipartialrawdataloader/)
* class [RasterImage](../)
* namespace [Aspose.Imaging](../../rasterimage/)
* assembly [Aspose.Imaging](../../../)

---

## LoadRawData(Rectangle, Rectangle, RawDataSettings, IPartialRawDataLoader) {#loadrawdata_1}

加载原始数据。

```csharp
public void LoadRawData(Rectangle rectangle, Rectangle destImageBounds, 
    RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 矩形 | Rectangle | 用于加载原始数据的矩形。 |
| destImageBounds | Rectangle | 目标图像边界。 |
| rawDataSettings | RawDataSettings | 用于已加载数据的原始数据设置。注意，如果数据不是指定的格式，则会执行数据转换。 |
| rawDataLoader | IPartialRawDataLoader | 原始数据加载器。 |

### 另请参见

* struct [Rectangle](../../rectangle/)
* class [RawDataSettings](../../rawdatasettings/)
* interface [IPartialRawDataLoader](../../ipartialrawdataloader/)
* class [RasterImage](../)
* namespace [Aspose.Imaging](../../rasterimage/)
* assembly [Aspose.Imaging](../../../)


