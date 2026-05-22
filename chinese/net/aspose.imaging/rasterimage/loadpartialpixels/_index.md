---
title: "RasterImage.LoadPartialPixels"
second_title: "Aspose.Imaging for .NET API 参考"
description: "RasterImage 方法。按包部分加载像素"
type: docs
weight: 450
url: /zh/net/aspose.imaging/rasterimage/loadpartialpixels/
---
## RasterImage.LoadPartialPixels method

按包部分加载像素。

```csharp
public void LoadPartialPixels(Rectangle desiredRectangle, IPartialPixelLoader pixelLoader)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| desiredRectangle | Rectangle | 所需的矩形。 |
| pixelLoader | IPartialPixelLoader | 像素加载器。 |

## 示例

以下示例展示了如何使用自定义的部分处理器加载和处理光栅图像的像素。例如，考虑统计图像中完全透明像素的问题。为了使用部分加载机制统计透明像素，引入了实现 Aspose.Imaging.IPartialPixelLoader 的单独类 TransparentPixelCounter。

```csharp
[C#]

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(@"c:\temp\alpha.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // 创建 Aspose.Imaging.IPartialPixelLoader 的实例并将其传递给 Aspose.Imaging.RasterImage.LoadPartialPixels
    TransparentPixelCounter counter = new TransparentPixelCounter();

    // 加载整幅图像的像素。图像的任意矩形部分都可以作为 Aspose.Imaging.RasterImage.LoadPartialPixels 方法的第一个参数指定。
    rasterImage.LoadPartialPixels(rasterImage.Bounds, counter);

    System.Console.WriteLine("The number of fully transparent pixels is {0}", counter.Count);
    System.Console.WriteLine("The total number of pixels is {0}", image.Width * image.Height);
}

// 计数器可能如下所示：
/// <summary>
/// 统计 alpha 通道值为 0 的完全透明像素数量。
/// </summary>
private class TransparentPixelCounter : IPartialPixelLoader
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
    public void Process(Aspose.Imaging.Rectangle pixelsRectangle, Aspose.Imaging.Color[] pixels, Aspose.Imaging.Point start, Aspose.Imaging.Point end)
    {
        foreach (Color pixel in pixels)
        {
            if (pixel.A == 0)
            {
                this.count++;
            }
        }
    }
}
```

### 另请参见

* struct [Rectangle](../../rectangle/)
* interface [IPartialPixelLoader](../../ipartialpixelloader/)
* class [RasterImage](../)
* namespace [Aspose.Imaging](../../rasterimage/)
* assembly [Aspose.Imaging](../../../)


