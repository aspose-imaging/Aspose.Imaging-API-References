---
title: "CmxImage.Pages"
second_title: "Aspose.Imaging for .NET API 参考"
description: "CmxImage 属性。使用此直观属性无缝检索图像的页面。适用于希望访问和操作多页图像中各个页面、确保高效导航和处理的开发者。"
type: docs
weight: 90
url: /zh/net/aspose.imaging.fileformats.cmx/cmximage/pages/
---
## CmxImage.Pages property

无缝检索图像的页面，使用此直观属性。适用于希望访问和操作多页图像中各个页面的开发者，确保高效的导航和处理。

```csharp
public override Image[] Pages { get; }
```

### Property Value

这些页面。

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

* class [Image](../../../aspose.imaging/image/)
* class [CmxImage](../)
* namespace [Aspose.Imaging.FileFormats.Cmx](../../cmximage/)
* assembly [Aspose.Imaging](../../../)


