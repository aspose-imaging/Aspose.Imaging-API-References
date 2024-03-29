---
title: LoadArgb32Pixels
second_title: Aspose.Imaging for .NET API 参考
description: 加载 32 位 ARGB 像素
type: docs
weight: 360
url: /zh/net/aspose.imaging/rasterimage/loadargb32pixels/
---
## RasterImage.LoadArgb32Pixels method

加载 32 位 ARGB 像素。

```csharp
public int[] LoadArgb32Pixels(Rectangle rectangle)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| rectangle | Rectangle | 要从中加载像素的矩形。 |

### 返回值

加载的 32 位 ARGB 像素数组。

### 例子

以下示例显示了如何加载和处理光栅图像的像素。像素表示为 32 位整数值。例如，考虑计算图像的完全透明像素的问题。

```csharp
[C#]

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(@"c:\temp\alpha.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // 加载整个图像的像素。图像的任何矩形部分都可以指定为 Aspose.Imaging.RasterImage.LoadArgb32Pixels 方法的参数。
    int[] pixels = rasterImage.LoadArgb32Pixels(rasterImage.Bounds);

    int count = 0;
    foreach (int pixel in pixels)
    {
        int alpha = (pixel >> 24) & 0xff;
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
