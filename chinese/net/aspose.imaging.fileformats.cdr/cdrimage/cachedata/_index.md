---
title: "CdrImage.CacheData"
second_title: "Aspose.Imaging for .NET API 参考"
description: "CdrImage 方法。使用此用户友好方法轻松缓存数据，以防止从底层源额外加载。适用于希望通过预加载数据来优化性能，确保在其应用程序中更快访问和更平稳运行的开发者。DataStreamContainer"
type: docs
weight: 100
url: /zh/net/aspose.imaging.fileformats.cdr/cdrimage/cachedata/
---
## CdrImage.CacheData method

使用此用户友好方法轻松缓存数据，以防止从底层源额外加载。适用于希望通过预加载数据来优化性能，确保在其应用程序中更快访问和更平稳运行的开发者。[`DataStreamContainer`](../../../aspose.imaging/datastreamsupporter/datastreamcontainer/)。

```csharp
public override void CacheData()
```

## 示例

以下示例展示了如何缓存 CDR 图像的所有页面。

```csharp
[C#]

string dir = "c:\\temp\\";

// 从 CDR 文件加载图像。
using (Aspose.Imaging.FileFormats.Cdr.CdrImage image = (Aspose.Imaging.FileFormats.Cdr.CdrImage)Aspose.Imaging.Image.Load(dir + "sample.cdr"))
{
    // 此调用仅缓存默认页面。
    image.CacheData();

    // 缓存所有页面，以便不再从底层数据流执行额外的数据加载。
    foreach (Aspose.Imaging.FileFormats.Cdr.CdrImagePage page in image.Pages)
    {
        page.CacheData();
    }
}
```

### 另请参见

* class [CdrImage](../)
* namespace [Aspose.Imaging.FileFormats.Cdr](../../cdrimage/)
* assembly [Aspose.Imaging](../../../)


