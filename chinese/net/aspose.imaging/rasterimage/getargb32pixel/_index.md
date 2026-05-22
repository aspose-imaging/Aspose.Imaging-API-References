---
title: "RasterImage.GetArgb32Pixel"
second_title: "Aspose.Imaging for .NET API 参考"
description: "RasterImage 方法。获取图像的 32 位 ARGB 像素"
type: docs
weight: 310
url: /zh/net/aspose.imaging/rasterimage/getargb32pixel/
---
## RasterImage.GetArgb32Pixel method

获取图像的 32 位 ARGB 像素。

```csharp
public int GetArgb32Pixel(int x, int y)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | Int32 | 像素的 x 坐标。 |
| y | Int32 | 像素的 y 坐标。 |

### 返回值

指定位置的 32 位 ARGB 像素。

## 示例

以下示例加载栅格图像并获取表示为 32 位整数值的任意像素的颜色。

```csharp
[C#]

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(@"c:\temp\sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // 获取图像左上像素颜色的整数表示。
    int color = rasterImage.GetArgb32Pixel(0, 0);

    // 要获取各个颜色分量的值，需要将颜色值按相应的位数进行移位。
    int alpha = (color >> 24) & 0xff;
    int red = (color >> 16) & 0xff;
    int green = (color >> 8) & 0xff;
    int blue = (color >> 0) & 0xff;

    System.Console.WriteLine("The color of the pixel(0,0) is A={0},R={1},G={2},B={3}", alpha, red, green, blue);
}
```

以下示例展示了图像缓存如何影响性能。一般情况下，读取缓存数据的速度快于读取未缓存的数据。

```csharp
[C#]

string dir = "c:\\temp\\";

// 从 PNG 文件加载图像。
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    // 缓存所有像素数据，以便不再从底层数据流加载额外数据
    image.CacheData();

    System.Diagnostics.Stopwatch stopwatch = new System.Diagnostics.Stopwatch();
    stopwatch.Start();

    // 读取所有像素相当快。
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;
    for (int y = 0; y < image.Height; y++)
    {
        for (int x = 0; x < image.Width; x++)
        {
            int color = rasterImage.GetArgb32Pixel(x, y);
        }
    }

    stopwatch.Stop();
    System.Console.WriteLine("Reading all cached pixels took {0} ms.", stopwatch.ElapsedMilliseconds);
}

// 从 PNG 文件加载图像
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    System.Diagnostics.Stopwatch stopwatch = new System.Diagnostics.Stopwatch();
    stopwatch.Start();

    // 读取所有像素的速度不如缓存时快
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;
    for (int y = 0; y < image.Height; y++)
    {
        for (int x = 0; x < image.Width; x++)
        {
            int color = rasterImage.GetArgb32Pixel(x, y);
        }
    }

    stopwatch.Stop();
    System.Console.WriteLine("Reading all pixels without preliminary caching took {0} ms.", stopwatch.ElapsedMilliseconds);
}

// 输出可能如下所示：
// 读取所有已缓存像素耗时 1500 毫秒。
// 在未进行预缓存的情况下读取所有像素耗时 150000 毫秒。
```

### 另请参见

* class [RasterImage](../)
* namespace [Aspose.Imaging](../../rasterimage/)
* assembly [Aspose.Imaging](../../../)


