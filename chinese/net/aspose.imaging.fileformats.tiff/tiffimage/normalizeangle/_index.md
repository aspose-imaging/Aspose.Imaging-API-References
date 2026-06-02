---
title: "TiffImage.NormalizeAngle"
second_title: "Aspose.Imaging for .NET API 参考"
description: "TiffImage 方法。利用专为扫描文本文件设计的 NormalizeAngle 方法校正倾斜的扫描件，确保准确对齐。将此功能无缝集成到您的文本处理工作流中，以提升文档可读性和质量，提高文本识别与分析任务的整体效率。此方法使用 GetSkewAngle 和 Rotate 方法。"
type: docs
weight: 290
url: /zh/net/aspose.imaging.fileformats.tiff/tiffimage/normalizeangle/
---
## TiffImage.NormalizeAngle method

利用专为扫描文本文件设计的 NormalizeAngle 方法校正倾斜的扫描件，确保准确对齐。将此功能无缝集成到您的文本处理工作流中，以提升文档可读性和质量，提高文本识别与分析任务的整体效率。此方法使用 [`GetSkewAngle`](../../../aspose.imaging/rasterimage/getskewangle/) 和 [`Rotate`](../rotate/) 方法。

```csharp
public override void NormalizeAngle(bool resizeProportionally, Color backgroundColor)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| resizeProportionally | Boolean | 如果设置为 `true`，图像尺寸将根据旋转矩形（角点）投影进行更改；否则保持尺寸不变，仅旋转内部图像内容。 |
| backgroundColor | 颜色 | 背景颜色。 |

### 另请参见

* struct [Color](../../../aspose.imaging/color/)
* class [TiffImage](../)
* namespace [Aspose.Imaging.FileFormats.Tiff](../../tiffimage/)
* assembly [Aspose.Imaging](../../../)


