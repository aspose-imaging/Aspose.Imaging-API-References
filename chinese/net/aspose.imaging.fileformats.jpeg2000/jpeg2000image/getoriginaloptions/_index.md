---
title: "Jpeg2000Image.GetOriginalOptions"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Jpeg2000Image 方法。根据原始文件设置检索图像选项。此方法有助于保持原始图像的位深度和其他参数，确保一致性并保留图像数据的完整性。访问这些选项可实现对图像的无缝处理和操作，同时保留其原始特性。例如，如果我们加载一张每像素 1 位的黑白 PNG 图像，然后使用 Save 方法保存，输出的 PNG 图像将是每像素 8 位。为避免这种情况并以每像素 1 位保存 PNG 图像，请使用此方法获取相应的保存选项，并将其作为第二个参数传递给 Save 方法。"
type: docs
weight: 120
url: /zh/net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/getoriginaloptions/
---
## Jpeg2000Image.GetOriginalOptions method

根据原始文件设置检索图像选项。此方法有助于保持原始图像的位深度和其他参数，确保一致性并保留图像数据的完整性。访问这些选项可实现对图像的无缝处理和操作，同时保留其原始特性。例如，如果我们加载一张每像素 1 位的黑白 PNG 图像，然后使用 [`Save`](../../../aspose.imaging/datastreamsupporter/save/) 方法保存，输出的 PNG 图像将是每像素 8 位。为避免这种情况并以每像素 1 位保存 PNG 图像，请使用此方法获取相应的保存选项，并将其作为第二个参数传递给 [`Save`](../../../aspose.imaging/image/save/) 方法。

```csharp
public override ImageOptionsBase GetOriginalOptions()
```

### 返回值

基于原始文件设置的选项。

### 另请参见

* class [ImageOptionsBase](../../../aspose.imaging/imageoptionsbase/)
* class [Jpeg2000Image](../)
* namespace [Aspose.Imaging.FileFormats.Jpeg2000](../../jpeg2000image/)
* assembly [Aspose.Imaging](../../../)


