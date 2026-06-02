---
title: "TgaImage.Height"
second_title: "Aspose.Imaging for .NET API 参考"
description: "TgaImage 属性。获取此 TgaImage 实例所封装图像的高度。此属性为开发者提供有关图像垂直尺寸的关键细节，便于在软件解决方案中无缝集成和操作图像。"
type: docs
weight: 150
url: /zh/net/aspose.imaging.fileformats.tga/tgaimage/height/
---
## TgaImage.Height property

获取此 [`TgaImage`](../) 实例所封装图像的高度。此属性为开发者提供有关图像垂直尺寸的关键细节，便于在软件解决方案中无缝集成和操作图像。

```csharp
public override int Height { get; }
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


