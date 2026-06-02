---
title: "RasterImage.SavePixels"
second_title: "Aspose.Imaging for .NET API 参考"
description: "RasterImage 方法。保存像素"
type: docs
weight: 600
url: /zh/net/aspose.imaging/rasterimage/savepixels/
---
## RasterImage.SavePixels method

保存像素。

```csharp
public void SavePixels(Rectangle rectangle, Color[] pixels)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 矩形 | Rectangle | 用于保存像素的矩形区域。 |
| 像素 | Color[] | 像素数组。 |

## 示例

以下示例使用 Aspose.Imaging.RasterImage.SavePixels 方法将光栅图像的中心区域填充为黑色像素。

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // 黑色方块
    Color[] pixels = new Color[(rasterImage.Width / 2) * (rasterImage.Height / 2)];
    for (int i = 0; i < pixels.Length; i++)
    {
        pixels[i] = Color.Black;
    }

    // 在图像中心绘制黑色方块。
    Aspose.Imaging.Rectangle area = new Aspose.Imaging.Rectangle(rasterImage.Width / 4, rasterImage.Height / 4, rasterImage.Width / 2, rasterImage.Height / 2);
    rasterImage.SavePixels(area, pixels);

    rasterImage.Save(dir + "sample.SavePixels.png");
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

* struct [Rectangle](../../rectangle/)
* struct [Color](../../color/)
* class [RasterImage](../)
* namespace [Aspose.Imaging](../../rasterimage/)
* assembly [Aspose.Imaging](../../../)


