---
title: "DjvuImage.CacheData"
second_title: "Aspose.Imaging for .NET API 参考"
description: "DjvuImage 方法。私有缓存数据以优化性能，减少对外部资源的重复检索需求。此方法还能在数据访问频繁或资源受限的场景下帮助节约资源。"
type: docs
weight: 210
url: /zh/net/aspose.imaging.fileformats.djvu/djvuimage/cachedata/
---
## DjvuImage.CacheData method

私有缓存数据以优化性能，减少对外部来源的重复数据检索。此方法还能帮助节约资源，尤其在数据访问频繁或资源受限的场景中。

```csharp
public override void CacheData()
```

## 示例

以下示例展示如何缓存 DJVU 图像的所有页面。

```csharp
[C#]

string dir = "c:\\temp\\";

// 从 DJVU 文件加载图像。
using (Aspose.Imaging.FileFormats.Djvu.DjvuImage image = (Aspose.Imaging.FileFormats.Djvu.DjvuImage)Aspose.Imaging.Image.Load(dir + "sample.djvu"))
{
    // 此调用会缓存所有页面，从而不会再从底层数据流加载额外数据。
    image.CacheData();

    // 或者您可以单独缓存各页面。
    foreach (Aspose.Imaging.FileFormats.Djvu.DjvuPage page in image.Pages)
    {
        page.CacheData();
    }
}
```

### 另请参见

* class [DjvuImage](../)
* namespace [Aspose.Imaging.FileFormats.Djvu](../../djvuimage/)
* assembly [Aspose.Imaging](../../../)


