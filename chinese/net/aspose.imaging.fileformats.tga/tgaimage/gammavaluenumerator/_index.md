---
title: "TgaImage.GammaValueNumerator"
second_title: "Aspose.Imaging for .NET API 参考"
description: "TgaImage 属性。获取伽马值的分子部分，这对于图像中的准确颜色表示至关重要。在未进行伽马校正的图像中，此值应为 1.0。理解并使用此值对于保持色彩保真度和确保图像渲染的准确性至关重要。"
type: docs
weight: 100
url: /zh/net/aspose.imaging.fileformats.tga/tgaimage/gammavaluenumerator/
---
## TgaImage.GammaValueNumerator property

获取 gamma 值的分子部分，这对于图像中的准确颜色表示至关重要。在未进行 gamma 校正的图像中，此值应为 1.0。理解并利用此值对于保持颜色保真度和确保图像渲染的准确性至关重要。

```csharp
public ushort GammaValueNumerator { get; }
```

## 示例

获取已加载 TGA 图像的公共属性的值。

```csharp
[C#]

using (TgaImage image = (TgaImage)Image.Load("test.tga"))
{
    dateTimeStamp = image.DateTimeStamp;
    authorName = image.AuthorName;
    authorComments = image.AuthorComments;
    imageId = image.ImageId;
    jobNameOrId = image.JobNameOrId;
    jobTime = image.JobTime;
    keyColor = image.TransparentColor;
    softwareId = image.SoftwareId;
    softwareVersion = image.SoftwareVersion;
    softwareVersionLetter = image.SoftwareVersionLetter;
    softwareVersionNumber = image.SoftwareVersionNumber;
    xOrigin = image.XOrigin;
    yOrigin = image.YOrigin;
    gammaValueDenominator = image.GammaValueDenominator;
    gammaValueNumerator = image.GammaValueNumerator;
    hasAlphaChannel = image.HasAlpha;
    hasColorMap = image.HasColorMap;
    height = image.Height;
    isGrayScale = image.IsGrayScale;
    pixelAspectRatioDenominator = image.PixelAspectRatioDenominator;
    pixelAspectRatioNumerator = image.PixelAspectRatioNumerator;
    size = image.Size;
    width = image.Width;
}
```

### 另请参见

* class [TgaImage](../)
* namespace [Aspose.Imaging.FileFormats.Tga](../../tgaimage/)
* assembly [Aspose.Imaging](../../../)


