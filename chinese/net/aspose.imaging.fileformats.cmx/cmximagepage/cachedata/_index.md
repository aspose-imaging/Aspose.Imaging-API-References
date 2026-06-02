---
title: "CmxImagePage.CacheData"
second_title: "Aspose.Imaging for .NET API 参考"
description: "CmxImagePage 方法。缓存不可用"
type: docs
weight: 100
url: /zh/net/aspose.imaging.fileformats.cmx/cmximagepage/cachedata/
---
## CmxImagePage.CacheData method

缓存不可用。

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

* class [CmxImagePage](../)
* namespace [Aspose.Imaging.FileFormats.Cmx](../../cmximagepage/)
* assembly [Aspose.Imaging](../../../)


