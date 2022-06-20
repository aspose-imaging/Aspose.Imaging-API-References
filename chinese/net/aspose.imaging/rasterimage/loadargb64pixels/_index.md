---
title: LoadArgb64Pixels
second_title: Aspose.Imaging for .NET API 参考
description: 加载 64 位 ARGB 像素
type: docs
weight: 370
url: /zh/net/aspose.imaging/rasterimage/loadargb64pixels/
---
## RasterImage.LoadArgb64Pixels method

加载 64 位 ARGB 像素。

```csharp
public long[] LoadArgb64Pixels(Rectangle rectangle)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| rectangle | Rectangle | 要从中加载像素的矩形。 |

### 返回值

加载的 64 位 ARGB 像素数组。

### 例子

以下示例显示如何加载和处理光栅图像的像素。像素表示为 64 位整数值。例如，考虑计算图像的完全透明像素的问题。

```csharp
[C#]

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(@"c:\temp\16rgba.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

        // 加载整个图像的像素。图像的任何矩形部分都可以指定为 Aspose.Imaging.RasterImage.LoadArgb64Pixels 方法的参数。
        // 注意图像本身每个样本必须有 16 位，因为 Aspose.Imaging.RasterImage.LoadArgb64Pixels 不适用于每个样本 8 位。
        // 为了使用每个样本 8 位，请使用旧的 Aspose.Imaging.RasterImage.LoadArgb32Pixels 方法。
    long[] pixels = rasterImage.LoadArgb64Pixels(rasterImage.Bounds);

    int count = 0;
    foreach (int pixel in pixels)
    {
            // 注意，包括 alpha 在内的所有颜色分量都用 16 位值表示，因此它们的允许值在 [0, 63535].
 范围内
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

### 也可以看看

* struct [Rectangle](../../rectangle)
* class [RasterImage](../../rasterimage)
* 命名空间 [Aspose.Imaging](../../rasterimage)
* 部件 [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->