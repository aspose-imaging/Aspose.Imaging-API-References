---
title: "CdrImagePage.CacheData"
second_title: "Aspose.Imaging for .NET API 参考"
description: "CdrImagePage 方法。缓存数据并确保不会从底层 DataStreamContainer 加载额外数据"
type: docs
weight: 70
url: /zh/net/aspose.imaging.fileformats.cdr/cdrimagepage/cachedata/
---
## CdrImagePage.CacheData method

缓存数据并确保不会从底层 [`DataStreamContainer`](../../../aspose.imaging/datastreamsupporter/datastreamcontainer/) 加载额外的数据。

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

* class [CdrImagePage](../)
* namespace [Aspose.Imaging.FileFormats.Cdr](../../cdrimagepage/)
* assembly [Aspose.Imaging](../../../)


