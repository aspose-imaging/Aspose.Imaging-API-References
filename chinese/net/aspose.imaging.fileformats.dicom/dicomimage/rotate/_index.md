---
title: "DicomImage.Rotate"
second_title: "Aspose.Imaging for .NET API 参考"
description: "DicomImage 方法。使用此便捷方法围绕图像中心旋转图像。非常适合希望动态调整图像方向，以确保在应用程序中实现最佳展示和对齐的开发者。"
type: docs
weight: 280
url: /zh/net/aspose.imaging.fileformats.dicom/dicomimage/rotate/
---
## DicomImage.Rotate method

使用此便捷方法围绕中心旋转图像。适用于希望动态调整图像方向的开发者，确保在应用程序中实现最佳展示和对齐。

```csharp
public override void Rotate(float angle, bool resizeProportionally, Color backgroundColor)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 角度 | 单精度 | 旋转角度（单位：度）。正值将顺时针旋转。 |
| resizeProportionally | Boolean | 如果设置为 `true`，图像尺寸将根据旋转矩形（角点）投影进行更改；否则保持尺寸不变，仅旋转 `internal` 图像内容。 |
| backgroundColor | 颜色 | 背景颜色。 |

## 示例

此示例展示如何旋转 DICOM 图像的所有页面并将它们全部保存为多帧 TIFF 图像。

```csharp
[C#]

string dir = "c:\\temp\\";

// 从文件流加载 DICOM 图像。
using (System.IO.Stream stream = System.IO.File.OpenRead(dir + "multiframe.dicom"))
{
    using (Aspose.Imaging.FileFormats.Dicom.DicomImage dicomImage = new Aspose.Imaging.FileFormats.Dicom.DicomImage(stream))
    {
        // 将图像围绕中心顺时针旋转 60 度。
        // 使用灰色作为背景颜色。
        dicomImage.Rotate(60, true, Aspose.Imaging.Color.Gray);

        Aspose.Imaging.ImageOptions.TiffOptions createOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);
        createOptions.Compression = Aspose.Imaging.FileFormats.Tiff.Enums.TiffCompressions.Deflate;

        // 请注意，如果图像是彩色的，它将根据以下选项自动转换为灰度格式。
        createOptions.Photometric = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.MinIsBlack;
        createOptions.BitsPerSample = new ushort[] { 8 };

        // 创建 TIFF 帧数组。
        // 帧的数量等于 DJVU 页面数量。
        Aspose.Imaging.FileFormats.Tiff.TiffFrame[] tiffFrames = new Aspose.Imaging.FileFormats.Tiff.TiffFrame[dicomImage.DicomPages.Length];

        // 将每个页面保存为单独的 TIFF 帧。
        foreach (Aspose.Imaging.FileFormats.Dicom.DicomPage dicomPage in dicomImage.DicomPages)
        {
            // 基于 DICOM 页面创建 TIFF 帧。
            tiffFrames[dicomPage.Index] = new Aspose.Imaging.FileFormats.Tiff.TiffFrame(dicomPage, createOptions);
        }

        // 从帧合成 TIFF 图像。
        using (Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = new Aspose.Imaging.FileFormats.Tiff.TiffImage(tiffFrames))
        {
            // 保存到文件。
            tiffImage.Save(dir + "multiframe.tif");
        }
    }
}
```

### 另请参见

* struct [Color](../../../aspose.imaging/color/)
* class [DicomImage](../)
* namespace [Aspose.Imaging.FileFormats.Dicom](../../dicomimage/)
* assembly [Aspose.Imaging](../../../)


