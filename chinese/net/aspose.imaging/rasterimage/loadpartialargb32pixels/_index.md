---
title: "RasterImage.LoadPartialArgb32Pixels"
second_title: "Aspose.Imaging for .NET API 参考"
description: "RasterImage 方法。按批次部分加载 32 位 ARGB 像素。"
type: docs
weight: 430
url: /zh/net/aspose.imaging/rasterimage/loadpartialargb32pixels/
---
## RasterImage.LoadPartialArgb32Pixels method

按包部分加载 32 位 ARGB 像素。

```csharp
public void LoadPartialArgb32Pixels(Rectangle rectangle, 
    IPartialArgb32PixelLoader partialPixelLoader)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 矩形 | Rectangle | 所需的矩形。 |
| partialPixelLoader | IPartialArgb32PixelLoader | 32 位 ARGB 像素加载器。 |

## 示例

以下示例展示如何使用您自己的部分处理器加载和处理光栅图像的像素。例如，考虑统计图像中完全透明像素的问题。为了使用部分加载机制统计透明像素，引入了实现 Aspose.Imaging.IPartialArgb32PixelLoader 的单独类 TransparentArgb32PixelCounter。

```csharp
[C#]

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(@"c:\temp\alpha.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // 创建 Aspose.Imaging.IPartialArgb32PixelLoader 的实例并将其传递给 Aspose.Imaging.RasterImage.LoadPartialArgb32Pixels。
    TransparentArgb32PixelCounter counter = new TransparentArgb32PixelCounter();

    // 加载整幅图像的像素。图像的任意矩形部分都可以作为 Aspose.Imaging.RasterImage.LoadPartialArgb32Pixels 方法的第一个参数指定。
    rasterImage.LoadPartialArgb32Pixels(rasterImage.Bounds, counter);

    System.Console.WriteLine("The number of fully transparent pixels is {0}", counter.Count);
    System.Console.WriteLine("The total number of pixels is {0}", image.Width * image.Height);
}

// 计数器可能如下所示：
/// <summary>
/// 统计 alpha 通道值为 0 的完全透明像素数量。
/// </summary>
private class TransparentArgb32PixelCounter : IPartialArgb32PixelLoader
{
    /// <summary>
    /// 完全透明像素的数量。
    /// </summary>
    private int count;

    /// <summary>
    /// 获取完全透明像素的数量。
    /// </summary>
    public int Count
    {
        get { return this.count; }
    }

    /// <summary>
    /// 处理已加载的像素。每当加载新的一部分像素时，都会回调此方法。
    /// </summary>
    /// <param name="pixelsRectangle">像素矩形。</param>
    /// <param name="pixels">32 位 ARGB 像素。</param>
    /// <param name="start">起始像素点。</param>
    /// <param name="end">结束像素点。</param>
    public void Process(Aspose.Imaging.Rectangle pixelsRectangle, int[] pixels, Aspose.Imaging.Point start, Aspose.Imaging.Point end)
    {
        foreach (int pixel in pixels)
        {
            int alpha = (pixel >> 24) & 0xff;
            if (alpha == 0)
            {
                this.count++;
            }
        }
    }
}
```

### 另请参见

* struct [Rectangle](../../rectangle/)
* interface [IPartialArgb32PixelLoader](../../ipartialargb32pixelloader/)
* class [RasterImage](../)
* namespace [Aspose.Imaging](../../rasterimage/)
* assembly [Aspose.Imaging](../../../)


