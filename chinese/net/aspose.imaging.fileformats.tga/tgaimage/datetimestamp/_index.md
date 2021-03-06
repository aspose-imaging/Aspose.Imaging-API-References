---
title: DateTimeStamp
second_title: Aspose.Imaging for .NET API 参考
description: 获取或设置日期/时间戳 此字段定义图像保存的日期和时间值 尽管操作系统通常是时间戳和日期戳文件但提供此功能是 因为如果文件是47操作系统可能会更改时间和日期戳复制通过使用此区域您可以保证在日期和时间 记录中使用未修改的区域
type: docs
weight: 70
url: /zh/net/aspose.imaging.fileformats.tga/tgaimage/datetimestamp/
---
## TgaImage.DateTimeStamp property

获取或设置日期/时间戳。 此字段定义图像保存的日期和时间值。 尽管操作系统通常是时间戳和日期戳文件，但提供此功能是 因为如果文件是:::47，操作系统可能会更改时间和日期戳:::复制。通过使用此区域，您可以保证在日期和时间 记录中使用未修改的区域。

```csharp
public DateTime? DateTimeStamp { get; set; }
```

### 例子

更新加载的 TGA 图像的公共属性。

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

获取已加载 TGA 图像的公共属性值。

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
