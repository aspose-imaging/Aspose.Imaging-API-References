---
title: "Cache.ExactReallocateOnly"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Cache 属性。获取或设置一个值，指示重新分配是否应精确。如果重新分配不精确，性能应更高"
type: docs
weight: 50
url: /zh/net/aspose.imaging/cache/exactreallocateonly/
---
## Cache.ExactReallocateOnly property

获取或设置一个值，指示重新分配是否应精确。如果重新分配不精确，性能应更高。

```csharp
public static bool ExactReallocateOnly { get; set; }
```

### Property Value

`true` 如果重新分配是精确的；否则为 `false`。

## 备注

精确的重新分配仅会在指定的上限范围内执行额外内存的重新分配。若在重新分配期间为内存传递上限，缓存数据将在可能的情况下复制到磁盘。若在重新分配期间为磁盘内存传递上限，将抛出相应的异常。如果关闭此选项，则不会进行额外的复制，性能应更高，但这也可能导致超出为内存或磁盘指定的上限。

## 示例

此示例演示了 Aspose.Imaging.Cache 的使用。

```csharp
[C#]

// 默认情况下，缓存文件夹设置为用户的本地临时目录。
// 您也可以指定除默认之外的其他缓存文件夹，如下所示：
// Cache.CacheFolder = @"D:\\MyTemp";

// 自动模式灵活且高效
Aspose.Imaging.Cache.CacheType = Aspose.Imaging.CacheType.Auto;

// 默认值为 0，这意味着没有上限
Aspose.Imaging.Cache.MaxDiskSpaceForCache = 1073741824; // 1 gigabyte
Aspose.Imaging.Cache.MaxMemoryForCache = 1073741824; // 1 gigabyte

// 不建议更改以下属性，因为它可能会极大影响性能
Aspose.Imaging.Cache.ExactReallocateOnly = false;

// 您可以随时检查当前为内存或磁盘分配了多少字节
// 通过检查以下属性来查看缓存
long l1 = Aspose.Imaging.Cache.AllocatedDiskBytesCount;
long l2 = Aspose.Imaging.Cache.AllocatedMemoryBytesCount;

// 如下进行一些图像处理
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

    // 执行上述代码后，将在内存中分配 40000 字节。
    long diskBytes = Aspose.Imaging.Cache.AllocatedDiskBytesCount;
    long memoryBytes = Aspose.Imaging.Cache.AllocatedMemoryBytesCount;
}

// 分配属性可用于检查所有 Aspose.Imaging 对象是否已正确释放。
// 如果您忘记对某些对象调用 dispose，缓存值将不为 0。
l1 = Aspose.Imaging.Cache.AllocatedDiskBytesCount;
l2 = Aspose.Imaging.Cache.AllocatedMemoryBytesCount;
```

### 另请参见

* class [Cache](../)
* namespace [Aspose.Imaging](../../cache/)
* assembly [Aspose.Imaging](../../../)


