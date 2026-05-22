---
title: "TiffFrame.GetOriginalOptions"
second_title: "Aspose.Imaging for .NET API 参考"
description: "TiffFrame 方法。获取基于原始文件设置的选项。这有助于保持原始图像的位深度和其他参数不变。例如，如果我们加载一张每像素 1 位的黑白 PNG 图像，然后使用 Save 方法保存，它将生成每像素 8 位的 PNG 图像。为避免这种情况并以每像素 1 位保存 PNG 图像，请使用此方法获取相应的保存选项，并将其作为第二个参数传递给 Save 方法。"
type: docs
weight: 150
url: /zh/net/aspose.imaging.fileformats.tiff/tiffframe/getoriginaloptions/
---
## TiffFrame.GetOriginalOptions method

获取基于原始文件设置的选项。这有助于保持原始图像的位深度和其他参数不变。例如，如果我们加载一张每像素 1 位的黑白 PNG 图像，然后使用 [`Save`](../../../aspose.imaging/datastreamsupporter/save/) 方法保存，输出的 PNG 图像将是每像素 8 位。为避免这种情况并以每像素 1 位保存 PNG 图像，请使用此方法获取相应的保存选项，并将其作为第二个参数传递给 [`Save`](../../../aspose.imaging/image/save/) 方法。

```csharp
public override ImageOptionsBase GetOriginalOptions()
```

### 返回值

基于原始文件设置的选项。

### 另请参见

* class [ImageOptionsBase](../../../aspose.imaging/imageoptionsbase/)
* class [TiffFrame](../)
* namespace [Aspose.Imaging.FileFormats.Tiff](../../tiffframe/)
* assembly [Aspose.Imaging](../../../)


