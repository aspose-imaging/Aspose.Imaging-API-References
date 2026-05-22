---
title: "TgaImage.HasAlpha"
second_title: "Aspose.Imaging for .NET API 参考"
description: "TgaImage 属性。检索一个布尔值，指示 TgaImage 是否包含用于实现透明效果的 alpha 通道。此属性为处理图像合成和渲染提供重要信息，帮助开发者实现多种视觉效果和合成操作。"
type: docs
weight: 110
url: /zh/net/aspose.imaging.fileformats.tga/tgaimage/hasalpha/
---
## TgaImage.HasAlpha property

检索一个布尔值，指示 [`TgaImage`](../) 是否包含 alpha 通道，以实现透明效果。此属性为处理图像合成和渲染提供重要信息，帮助开发者实现多种视觉效果和合成操作。

```csharp
public override bool HasAlpha { get; }
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


