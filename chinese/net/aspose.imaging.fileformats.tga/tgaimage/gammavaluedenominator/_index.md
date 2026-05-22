---
title: "TgaImage.GammaValueDenominator"
second_title: "Aspose.Imaging for .NET API 参考"
description: "TgaImage 属性。检索伽马值的分母部分，这是决定图像颜色表示的关键因素。对于缺少伽马校正的图像，此值应为 1.0，以确保准确的颜色渲染。理解并利用此参数对于保持颜色保真度和实现精确的图像可视化至关重要。"
type: docs
weight: 90
url: /zh/net/aspose.imaging.fileformats.tga/tgaimage/gammavaluedenominator/
---
## TgaImage.GammaValueDenominator property

检索伽马值的分母部分，这是决定图像颜色表现的关键因素。对于缺少伽马校正的图像，该值应为 1.0，以确保准确的颜色渲染。理解并利用此参数对于保持色彩保真度和实现精确的图像可视化至关重要。

```csharp
public ushort GammaValueDenominator { get; }
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


