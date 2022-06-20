---
title: CacheData
second_title: Aspose.Imaging for .NET API 参考
description: 缓存数据私有
type: docs
weight: 190
url: /zh/net/aspose.imaging.fileformats.dicom/dicomimage/cachedata/
---
## DicomImage.CacheData method

缓存数据私有。

```csharp
public override void CacheData()
```

### 例子

以下示例显示如何缓存 DICOM 图像的所有页面。

```csharp
[C#]

string dir = "c:\\temp\\";

    // 从 DICOM 文件加载图像。
using (Aspose.Imaging.FileFormats.Dicom.DicomImage image = (Aspose.Imaging.FileFormats.Dicom.DicomImage)Aspose.Imaging.Image.Load(dir + "sample.dicom"))
{
        // 此调用缓存所有页面，因此不会从底层数据流执行额外的数据加载。
    image.CacheData();

        // 或者你可以单独缓存页面。
    foreach (Aspose.Imaging.FileFormats.Dicom.DicomPage page in image.DicomPages)
    {
        page.CacheData();
    }
}
```

### 也可以看看

* class [DicomImage](../../dicomimage)
* 命名空间 [Aspose.Imaging.FileFormats.Dicom](../../dicomimage)
* 部件 [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->