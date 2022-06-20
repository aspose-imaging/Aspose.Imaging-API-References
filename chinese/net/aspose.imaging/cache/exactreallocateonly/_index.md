---
title: ExactReallocateOnly
second_title: Aspose.Imaging for .NET API 参考
description: 获取或设置一个值该值指示重新分配是否应该准确如果重新分配不准确则性能应该更高
type: docs
weight: 50
url: /zh/net/aspose.imaging/cache/exactreallocateonly/
---
## Cache.ExactReallocateOnly property

获取或设置一个值，该值指示重新分配是否应该准确。如果重新分配不准确，则性能应该更高。

```csharp
public static bool ExactReallocateOnly { get; set; }
```

### 适当的价值

` true` 如果重新分配是准确的；否则，` false` 。

### 评论

精确的重新分配将执行额外内存的重新分配，直到达到指定的上限。 在重新分配期间超过内存上限时，缓存数据将尽可能复制到磁盘。 在重新分配期间超过磁盘内存上限时，将引发相应的异常。 如果关闭此选项，性能应该会更高，因为如果可能不会执行额外的复制， 但是这也可能导致超过为内存或磁盘指定的上限。

### 例子

这个例子演示了 Aspose.Imaging.Cache

```csharp
[C#]

    // 默认情况下，缓存文件夹设置为用户的本地临时目录。
    // 您还可以指定另一个缓存文件夹而不是默认值，如下所示：
    // Cache.CacheFolder = @"D:\\MyTemp";

    // 自动模式灵活高效
Aspose.Imaging.Cache.CacheType = Aspose.Imaging.CacheType.Auto;

    // 默认值为0，表示没有上限
Aspose.Imaging.Cache.MaxDiskSpaceForCache = 1073741824;        // 1 GB
Aspose.Imaging.Cache.MaxMemoryForCache = 1073741824;        // 1 GB

    // 不建议更改以下属性，因为它可能会极大地影响性能
Aspose.Imaging.Cache.ExactReallocateOnly = false;

    // 您可以随时检查当前分配给内存或磁盘的字节数
    // 通过检查以下属性进行缓存
long l1 = Aspose.Imaging.Cache.AllocatedDiskBytesCount;
long l2 = Aspose.Imaging.Cache.AllocatedMemoryBytesCount;

    // 像下面做一些图像处理
Aspose.Imaging.ImageOptions.GifOptions options = new Aspose.Imaging.ImageOptions.GifOptions();
options.Palette = new ColorPalette(new Aspose.Imaging.Color[] { Aspose.Imaging.Color.Red, Aspose.Imaging.Color.Blue, Aspose.Imaging.Color.Black, Aspose.Imaging.Color.White });
options.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream(), true);
using (Aspose.Imaging.RasterImage image = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Create(options, 100, 100))
{
    Aspose.Imaging.Color[] pixels = new Aspose.Imaging.Color[10000];
    for (int i = 0; i < pixels.Length; i++)
    {
        pixels[i] = Aspose.Imaging.Color.White;
    }

    image.SavePixels(image.Bounds, pixels);

    // 执行上述代码后，内存中将分配 40000 字节。
    long diskBytes = Aspose.Imaging.Cache.AllocatedDiskBytesCount;
    long memoryBytes = Aspose.Imaging.Cache.AllocatedMemoryBytesCount;
}

    // 分配属性可用于检查是否所有 Aspose.Imaging 对象都被正确处理。
    // 如果您忘记对某些对象调用 dispose，缓存值将不同于 0。
l1 = Aspose.Imaging.Cache.AllocatedDiskBytesCount;
l2 = Aspose.Imaging.Cache.AllocatedMemoryBytesCount;
```

### 也可以看看

* class [Cache](../../cache)
* 命名空间 [Aspose.Imaging](../../cache)
* 部件 [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->