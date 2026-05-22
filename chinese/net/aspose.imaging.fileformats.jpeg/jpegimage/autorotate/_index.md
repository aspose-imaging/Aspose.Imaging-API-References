---
title: "JpegImage.AutoRotate"
second_title: "Aspose.Imaging for .NET API 参考"
description: "JpegImage 方法。根据从 Exif 元数据提取的方向数据自动旋转图像。此方法确保图像以正确的方向显示，提升用户体验并消除手动调整的需求。通过分析 Exif 信息，图像相应地被旋转，提供跨平台和设备的流畅观看体验。此自动旋转过程简化了图像处理，并在处理大量方向各异的图像时显著提升整体可用性。"
type: docs
weight: 190
url: /zh/net/aspose.imaging.fileformats.jpeg/jpegimage/autorotate/
---
## JpegImage.AutoRotate method

自动根据从 Exif 元数据提取的方向数据旋转图像。此方法确保图像以正确的方向显示，提升用户体验并消除手动调整的需求。通过分析 Exif 信息，图像相应地被旋转，提供跨平台和设备的无缝观看体验。此自动旋转过程简化了图像处理，并在处理大量方向各异的图像时提升整体可用性。

```csharp
public void AutoRotate()
```

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentOutOfRangeException | ‘JpegExifData’ 的 ‘Orientation’ 值超出允许范围 [1...8]，因此无法应用自动旋转。 |

### 另请参见

* class [JpegImage](../)
* namespace [Aspose.Imaging.FileFormats.Jpeg](../../jpegimage/)
* assembly [Aspose.Imaging](../../../)


