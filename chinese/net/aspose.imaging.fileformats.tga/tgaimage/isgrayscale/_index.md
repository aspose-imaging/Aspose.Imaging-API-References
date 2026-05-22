---
title: "TgaImage.IsGrayScale"
second_title: "Aspose.Imaging for .NET API 参考"
description: "TgaImage 属性。获取一个布尔值，指示 TgaImage 是否表示灰度图像。此属性对于区分彩色和灰度图像至关重要，帮助开发者根据图像的颜色特性采用适当的处理和渲染技术。"
type: docs
weight: 170
url: /zh/net/aspose.imaging.fileformats.tga/tgaimage/isgrayscale/
---
## TgaImage.IsGrayScale property

获取一个布尔值，指示 [`TgaImage`](../) 是否表示灰度图像。此属性对于区分彩色和灰度图像至关重要，帮助开发者根据图像的颜色特性采用适当的处理和渲染技术。

```csharp
public bool IsGrayScale { get; }
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


