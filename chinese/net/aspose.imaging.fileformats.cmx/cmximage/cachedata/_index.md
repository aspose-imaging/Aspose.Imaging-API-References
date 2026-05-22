---
title: "CmxImage.CacheData"
second_title: "Aspose.Imaging for .NET API 参考"
description: "CmxImage 方法。使用此便捷方法缓存数据，以防止从底层源 DataStreamContainer 进行额外加载。适用于希望通过预加载数据来优化性能、确保更快访问和更流畅运行的开发者。"
type: docs
weight: 110
url: /zh/net/aspose.imaging.fileformats.cmx/cmximage/cachedata/
---
## CmxImage.CacheData method

使用此便捷方法缓存数据，以防止从底层源[`DataStreamContainer`](../../../aspose.imaging/datastreamsupporter/datastreamcontainer/)进行额外加载。适用于希望通过预加载数据来优化性能、确保更快访问和更流畅运行的开发者。

```csharp
public override void CacheData()
```

## 示例

以下示例展示了如何缓存 CMX 图像的所有页面。

```csharp
[C#]

string dir = "c:\\temp\\";

// 从 CMX 文件加载图像。
using (Aspose.Imaging.FileFormats.Cmx.CmxImage image = (Aspose.Imaging.FileFormats.Cmx.CmxImage)Aspose.Imaging.Image.Load(dir + "sample.cmx"))
{
    // 此调用仅缓存默认页面。
    image.CacheData();

    // 缓存所有页面，以便不再从底层数据流执行额外的数据加载。
    foreach (Aspose.Imaging.FileFormats.Cmx.CmxImagePage page in image.Pages)
    {
        page.CacheData();
    }
}
```

### 另请参见

* class [CmxImage](../)
* namespace [Aspose.Imaging.FileFormats.Cmx](../../cmximage/)
* assembly [Aspose.Imaging](../../../)


