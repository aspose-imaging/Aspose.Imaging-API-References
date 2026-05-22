---
title: "RasterImage.LoadPixels"
second_title: "Aspose.Imaging for .NET API 参考"
description: "RasterImage 方法。加载像素"
type: docs
weight: 460
url: /zh/net/aspose.imaging/rasterimage/loadpixels/
---
## RasterImage.LoadPixels method

加载像素。

```csharp
public Color[] LoadPixels(Rectangle rectangle)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 矩形 | Rectangle | 用于加载像素的矩形。 |

### 返回值

已加载的像素数组。

## 示例

以下示例展示了如何加载和处理光栅图像的像素。例如，考虑统计图像中完全透明像素的问题。

```csharp
[C#]

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(@"c:\temp\alpha.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // 加载整幅图像的像素。图像的任意矩形区域都可以作为 Aspose.Imaging.RasterImage.LoadPixels 方法的参数指定。
    Color[] pixels = rasterImage.LoadPixels(rasterImage.Bounds);

    int count = 0;
    foreach (Color pixel in pixels)
    {
        if (pixel.A == 0)
        {
            count++;
        }
    }

    System.Console.WriteLine("The number of fully transparent pixels is {0}", count);
    System.Console.WriteLine("The total number of pixels is {0}", image.Width * image.Height);
}
```

本示例展示了如何将像素信息加载到 Color 类型的数组中，操作该数组并将其设置回图像。为执行这些操作，示例使用 MemoryStream 对象创建一个新的（GIF 格式）图像文件。

```csharp
[C#]

//创建 MemoryStream 的实例
using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
{
    //创建 GifOptions 的实例并设置其各种属性，包括 Source 属性
    Aspose.Imaging.ImageOptions.GifOptions gifOptions = new Aspose.Imaging.ImageOptions.GifOptions();
    gifOptions.Source = new Aspose.Imaging.Sources.StreamSource(stream);

    //创建 Image 的实例
    using (Aspose.Imaging.RasterImage image = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Create(gifOptions, 500, 500))
    {
        //通过将区域指定为图像边界来获取图像像素
        Aspose.Imaging.Color[] pixels = image.LoadPixels(image.Bounds);

        //遍历数组并设置交替索引像素的颜色
        for (int index = 0; index < pixels.Length; index++)
        {
            if (index % 2 == 0)
            {
                //将索引像素颜色设置为黄色
                pixels[index] = Aspose.Imaging.Color.Yellow;
            }
            else
            {
                //将索引像素颜色设置为蓝色
                pixels[index] = Aspose.Imaging.Color.Blue;
            }
        }

        //将像素更改应用到图像
        image.SavePixels(image.Bounds, pixels);

        // 保存所有更改。
        image.Save();
    }

    // 将 MemoryStream 写入文件
    using (System.IO.FileStream fileStream = new System.IO.FileStream(@"C:\temp\output.gif", System.IO.FileMode.Create))
    {
        stream.WriteTo(fileStream);
    }   
}
```

### 另请参见

* struct [Color](../../color/)
* struct [Rectangle](../../rectangle/)
* class [RasterImage](../)
* namespace [Aspose.Imaging](../../rasterimage/)
* assembly [Aspose.Imaging](../../../)


