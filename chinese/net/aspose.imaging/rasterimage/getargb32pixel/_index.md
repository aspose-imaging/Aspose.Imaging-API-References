---
title: GetArgb32Pixel
second_title: Aspose.Imaging for .NET API 参考
description: 获取图像 32 位 ARGB 像素
type: docs
weight: 280
url: /zh/net/aspose.imaging/rasterimage/getargb32pixel/
---
## RasterImage.GetArgb32Pixel method

获取图像 32 位 ARGB 像素。

```csharp
public int GetArgb32Pixel(int x, int y)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| x | Int32 | 像素 x 位置。 |
| y | Int32 | 像素 y 位置。 |

### 返回值

指定位置的 32 位 ARGB 像素。

### 例子

以下示例加载光栅图像并获取表示为 32 位整数值的任意像素的颜色。

```csharp
[C#]

string dir = "c:\\temp\\";

    // 从 PNG 文件加载图像。
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
        // 缓存所有像素数据，这样就不会从底层数据流中执行额外的数据加载
    image.CacheData();

    System.Diagnostics.Stopwatch stopwatch = new System.Diagnostics.Stopwatch();
    stopwatch.Start();

        // 读取所有像素非常快。
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

    // 从 PNG 文件中加载图像
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    System.Diagnostics.Stopwatch stopwatch = new System.Diagnostics.Stopwatch();
    stopwatch.Start();

        // 读取所有像素没有缓存时快
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
    // 读取所有缓存的像素需要 1500 ms.
// 在没有初步缓存的情况下读取所有像素需要 150000 毫秒。
```

以下示例显示图像缓存如何影响性能。在一般情况下，读取缓存数据比读取非缓存数据执行得更快。

```csharp
[C#]

string dir = "c:\\temp\\";

    // 从 PNG 文件加载图像。
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
        // 缓存所有像素数据，这样就不会从底层数据流中执行额外的数据加载
    image.CacheData();

    System.Diagnostics.Stopwatch stopwatch = new System.Diagnostics.Stopwatch();
    stopwatch.Start();

        // 读取所有像素非常快。
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

    // 从 PNG 文件中加载图像
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    System.Diagnostics.Stopwatch stopwatch = new System.Diagnostics.Stopwatch();
    stopwatch.Start();

        // 读取所有像素没有缓存时快
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
    // 读取所有缓存的像素需要 1500 ms.
// 在没有初步缓存的情况下读取所有像素需要 150000 毫秒。
```

### 也可以看看

* class [RasterImage](../../rasterimage)
* 命名空间 [Aspose.Imaging](../../rasterimage)
* 部件 [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->