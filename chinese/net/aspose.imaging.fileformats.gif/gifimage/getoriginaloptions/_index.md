---
title: "GifImage.GetOriginalOptions"
second_title: "Aspose.Imaging for .NET API 参考"
description: "GifImage 方法。检索原始文件设置基于的选项，这对于在图像处理和操作中保持忠实度和一致性至关重要。此方法允许将文件特定参数无缝集成到后续操作中，确保准确呈现并遵循图像固有特性。这有助于保持原始图像的位深度和其他参数不变。例如，如果我们加载一张每像素 1 位的黑白 PNG 图像，然后使用 Save 方法保存，输出的 PNG 图像将是每像素 8 位。为避免这种情况并以每像素 1 位保存 PNG 图像，请使用此方法获取相应的保存选项，并将其作为第二个参数传递给 Save 方法。"
type: docs
weight: 310
url: /zh/net/aspose.imaging.fileformats.gif/gifimage/getoriginaloptions/
---
## GifImage.GetOriginalOptions method

检索原始文件设置基于的选项，这对于在图像处理和操作中保持忠实度和一致性至关重要。此方法允许将文件特定参数无缝集成到后续操作中，确保准确呈现并遵循图像固有特性。这有助于保持原始图像的位深度和其他参数不变。例如，如果我们加载一张每像素 1 位的黑白 PNG 图像，然后使用 [`Save`](../../../aspose.imaging/datastreamsupporter/save/) 方法保存，输出的 PNG 图像将是每像素 8 位。为避免这种情况并以每像素 1 位保存 PNG 图像，请使用此方法获取相应的保存选项，并将其作为第二个参数传递给 [`Save`](../../../aspose.imaging/image/save/) 方法。

```csharp
public override ImageOptionsBase GetOriginalOptions()
```

### 返回值

基于原始文件设置的选项。

### 另请参见

* class [ImageOptionsBase](../../../aspose.imaging/imageoptionsbase/)
* class [GifImage](../)
* namespace [Aspose.Imaging.FileFormats.Gif](../../gifimage/)
* assembly [Aspose.Imaging](../../../)


