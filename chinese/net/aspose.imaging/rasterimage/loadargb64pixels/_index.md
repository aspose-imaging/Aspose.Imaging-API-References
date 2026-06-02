---
title: "RasterImage.LoadArgb64Pixels"
second_title: "Aspose.Imaging for .NET API 参考"
description: "RasterImage 方法。加载 64 位 ARGB 像素。"
type: docs
weight: 410
url: /zh/net/aspose.imaging/rasterimage/loadargb64pixels/
---
## RasterImage.LoadArgb64Pixels method

加载 64 位 ARGB 像素。

```csharp
public long[] LoadArgb64Pixels(Rectangle rectangle)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 矩形 | Rectangle | 用于加载像素的矩形。 |

### 返回值

已加载的 64 位 ARGB 像素数组。

## 示例

以下示例展示了如何加载和处理光栅图像的像素。像素以 64 位整数值表示。例如，考虑统计图像中完全透明像素的问题。

```csharp
[C#]

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(@"c:\temp\16rgba.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // 加载整幅图像的像素。图像的任意矩形区域都可以作为 Aspose.Imaging.RasterImage.LoadArgb64Pixels 方法的参数指定。
    // 请注意，图像本身必须具有每样本 16 位，因为 Aspose.Imaging.RasterImage.LoadArgb64Pixels 不支持每样本 8 位。
    // 若要使用每样本 8 位，请使用老牌的 Aspose.Imaging.RasterImage.LoadArgb32Pixels 方法。
    long[] pixels = rasterImage.LoadArgb64Pixels(rasterImage.Bounds);

    int count = 0;
    foreach (int pixel in pixels)
    {
        // 请注意，所有颜色分量（包括 alpha）均以 16 位值表示，因此其允许的取值范围为 [0, 63535]。
        int alpha = (pixel >> 48) & 0xffff;
        if (alpha == 0)
        {
            count++;
        }
    }

    System.Console.WriteLine("The number of fully transparent pixels is {0}", count);
    System.Console.WriteLine("The total number of pixels is {0}", image.Width * image.Height);
}
```

### 另请参见

* struct [Rectangle](../../rectangle/)
* class [RasterImage](../)
* namespace [Aspose.Imaging](../../rasterimage/)
* assembly [Aspose.Imaging](../../../)


