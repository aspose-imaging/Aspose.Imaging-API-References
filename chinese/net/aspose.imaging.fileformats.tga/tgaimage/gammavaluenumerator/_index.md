---
title: GammaValueNumerator
second_title: Aspose.Imaging for .NET API 参考
description: 获取 Gamma 值分子部分 未校正的图像没有 gamma 的图像应具有值 1.0 作为结果
type: docs
weight: 100
url: /zh/net/aspose.imaging.fileformats.tga/tgaimage/gammavaluenumerator/
---
## TgaImage.GammaValueNumerator property

获取 Gamma 值分子部分。 未校正的图像（没有 gamma 的图像）应具有值 1.0 作为结果。

```csharp
public ushort GammaValueNumerator { get; }
```

### 例子

获取加载的 TGA 图像的公共属性的值。

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

### 也可以看看

* class [TgaImage](../../tgaimage)
* 命名空间 [Aspose.Imaging.FileFormats.Tga](../../tgaimage)
* 部件 [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
