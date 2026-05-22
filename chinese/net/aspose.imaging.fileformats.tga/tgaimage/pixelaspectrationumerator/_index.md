---
title: "TgaImage.PixelAspectRatioNumerator"
second_title: "Aspose.Imaging for .NET API 参考"
description: "TgaImage 属性。检索像素纵横比的分子部分，该比例影响图像中像素的视觉外观。理解并操作此值对于在图像渲染和处理时实现精确的像素表示和纵横比至关重要。"
type: docs
weight: 210
url: /zh/net/aspose.imaging.fileformats.tga/tgaimage/pixelaspectrationumerator/
---
## TgaImage.PixelAspectRatioNumerator property

检索像素纵横比的分子部分，它影响图像中像素的视觉比例。理解并操作此值对于在图像渲染和处理过程中实现准确的像素表示和纵横比至关重要。

```csharp
public ushort PixelAspectRatioNumerator { get; }
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


