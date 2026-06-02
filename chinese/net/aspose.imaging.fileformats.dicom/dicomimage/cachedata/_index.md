---
title: "DicomImage.CacheData"
second_title: "Aspose.Imaging for .NET API 参考"
description: "DicomImage 方法。此方法高效缓存数据，优化性能并在需要时确保快速访问。对于希望通过智能管理数据资源来提升应用程序速度和效率的开发者而言，是理想的选择。"
type: docs
weight: 170
url: /zh/net/aspose.imaging.fileformats.dicom/dicomimage/cachedata/
---
## DicomImage.CacheData method

此方法高效缓存数据，优化性能并在需要时确保快速访问。适用于希望通过智能管理数据资源来提升应用程序速度和效率的开发者。

```csharp
public override void CacheData()
```

## 示例

以下示例展示了如何缓存 DICOM 图像的所有页面。

```csharp
[C#]

string dir = "c:\\temp\\";

// 从 DICOM 文件加载图像。
using (Aspose.Imaging.FileFormats.Dicom.DicomImage image = (Aspose.Imaging.FileFormats.Dicom.DicomImage)Aspose.Imaging.Image.Load(dir + "sample.dicom"))
{
    // 此调用会缓存所有页面，从而不会再从底层数据流加载额外数据。
    image.CacheData();

    // 或者您可以单独缓存各页面。
    foreach (Aspose.Imaging.FileFormats.Dicom.DicomPage page in image.DicomPages)
    {
        page.CacheData();
    }
}
```

### 另请参见

* class [DicomImage](../)
* namespace [Aspose.Imaging.FileFormats.Dicom](../../dicomimage/)
* assembly [Aspose.Imaging](../../../)


