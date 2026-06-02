---
title: "TiffImage.GetOriginalOptions"
second_title: "Aspose.Imaging for .NET API 参考"
description: "TiffImage 方法。检索源文件设置派生的选项，以实现对关键参数（如位深度）及原始图像其他重要属性的无缝保留。使用此方法可在图像处理任务中保持忠实度和一致性，确保在不进行不必要更改的情况下获得最佳结果。例如，如果我们加载一张每像素 1 位的黑白 PNG 图像，然后使用 Save 方法保存，它将生成每像素 8 位的输出 PNG 图像。为避免这种情况并以每像素 1 位保存 PNG 图像，请使用此方法获取相应的保存选项，并将其作为第二个参数传递给 Save 方法。"
type: docs
weight: 260
url: /zh/net/aspose.imaging.fileformats.tiff/tiffimage/getoriginaloptions/
---
## TiffImage.GetOriginalOptions method

检索源文件设置派生的选项，以实现对关键参数（如位深度）及原始图像其他重要属性的无缝保留。使用此方法可在图像处理任务中保持忠实度和一致性，确保在不进行不必要更改的情况下获得最佳结果。例如，如果我们加载一张每像素 1 位的黑白 PNG 图像，然后使用 [`Save`](../../../aspose.imaging/datastreamsupporter/save/) 方法保存，将生成每像素 8 位的输出 PNG 图像。为避免这种情况并以每像素 1 位保存 PNG 图像，请使用此方法获取相应的保存选项，并将其作为第二个参数传递给 [`Save`](../../../aspose.imaging/image/save/) 方法。

```csharp
public override ImageOptionsBase GetOriginalOptions()
```

### 返回值

基于原始文件设置的选项。

### 异常

| 异常 | 条件 |
| --- | --- |
| [TiffImageException](../../../aspose.imaging.coreexceptions.imageformats/tiffimageexception/) | 无法从图像中提取原始选项。 |

### 另请参见

* class [ImageOptionsBase](../../../aspose.imaging/imageoptionsbase/)
* class [TiffImage](../)
* namespace [Aspose.Imaging.FileFormats.Tiff](../../tiffimage/)
* assembly [Aspose.Imaging](../../../)


