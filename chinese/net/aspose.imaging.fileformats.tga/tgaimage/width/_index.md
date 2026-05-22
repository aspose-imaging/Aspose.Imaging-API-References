---
title: "TgaImage.Width"
second_title: "Aspose.Imaging for .NET API 参考"
description: "TgaImage 属性。检索此 TgaImage 实例所表示图像的宽度。此属性为开发者提供关于图像尺寸的关键信息，促进在其软件应用中进行各种图像操作和处理任务。"
type: docs
weight: 270
url: /zh/net/aspose.imaging.fileformats.tga/tgaimage/width/
---
## TgaImage.Width property

检索此 [`TgaImage`](../) 实例所表示图像的宽度。此属性为开发者提供关于图像尺寸的关键信息，促进在其软件应用中进行各种图像操作和处理任务。

```csharp
public override int Width { get; }
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


