---
title: "TiffImage.Rotate"
second_title: "Aspose.Imaging for .NET API 参考"
description: "TiffImage 方法。围绕图像中心点按指定角度旋转图像，实现精确的方向调整。将此功能整合到您的图像处理管道中，以促进准确的变换，确保视觉内容在应用程序中的最佳对齐和呈现。"
type: docs
weight: 370
url: /zh/net/aspose.imaging.fileformats.tiff/tiffimage/rotate/
---
## TiffImage.Rotate method

围绕中心点按指定角度旋转图像，实现精确的方向调整。将此功能纳入图像处理流水线，以便进行准确的变换，确保应用程序中视觉内容的最佳对齐和呈现。

```csharp
public override void Rotate(float angle, bool resizeProportionally, Color backgroundColor)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 角度 | 单精度 | 旋转角度（单位：度）。正值将顺时针旋转。 |
| resizeProportionally | Boolean | 如果设置为 `true`，图像尺寸将根据旋转矩形（角点）投影进行更改；否则保持尺寸不变，仅旋转内部图像内容。 |
| backgroundColor | 颜色 | 背景颜色。 |

## 示例

以下示例展示如何将 TIFF 图像围绕中心顺时针旋转 45 度。

```csharp
[C#]

string dir = "c:\\temp\\";
Aspose.Imaging.ImageOptions.TiffOptions createTiffOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Aspose.Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);
    
// 创建永久的，而非临时的文件源。
createTiffOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(dir + "rotated.tif", false);
createTiffOptions.Photometric = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.Rgb;
createTiffOptions.BitsPerSample = new ushort[] { 8, 8, 8 };

using (Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = (Aspose.Imaging.FileFormats.Tiff.TiffImage)Image.Create(createTiffOptions, 100, 100))
{
    // 图像左上角到右下角的线性渐变。
    Aspose.Imaging.Brushes.LinearGradientBrush brush =
        new Aspose.Imaging.Brushes.LinearGradientBrush(
            new Aspose.Imaging.Point(0, 0),
            new Aspose.Imaging.Point(tiffImage.Width, tiffImage.Height),
            Aspose.Imaging.Color.Red,
            Aspose.Imaging.Color.Green);

    // 使用线性渐变画笔填充活动帧。
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(tiffImage);
    gr.FillRectangle(brush, tiffImage.Bounds);

    // 围绕中心顺时针旋转图像 45 度。
    // 图像尺寸根据旋转后的矩形（角点）而变化。
    tiffImage.Rotate(45f, true, Aspose.Imaging.Color.Black);
    tiffImage.Save();

    // 围绕中心顺时针旋转图像 45 度。
    // 保持图像尺寸不变，仅旋转内部图像内容。
    tiffImage.Rotate(45f, false, Aspose.Imaging.Color.Gray);
    tiffImage.Save(dir + "rotated.preservesize.tif");
}
```

### 另请参见

* struct [Color](../../../aspose.imaging/color/)
* class [TiffImage](../)
* namespace [Aspose.Imaging.FileFormats.Tiff](../../tiffimage/)
* assembly [Aspose.Imaging](../../../)


