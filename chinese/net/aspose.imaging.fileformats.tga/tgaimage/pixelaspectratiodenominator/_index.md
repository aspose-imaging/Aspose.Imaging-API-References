---
title: "TgaImage.PixelAspectRatioDenominator"
second_title: "Aspose.Imaging for .NET API 参考"
description: "TgaImage 属性。检索像素纵横比的分母部分，这是决定图像中像素视觉外观的关键因素。此数值对于在各种图像渲染和处理操作中保持精确的像素表示和纵横比至关重要，确保高质量的视觉输出。"
type: docs
weight: 200
url: /zh/net/aspose.imaging.fileformats.tga/tgaimage/pixelaspectratiodenominator/
---
## TgaImage.PixelAspectRatioDenominator property

检索像素纵横比的分母部分，这是决定图像中像素视觉比例的关键因素。此值对于在各种图像渲染和处理操作中保持准确的像素表示和纵横比至关重要，确保高质量的视觉输出。

```csharp
public ushort PixelAspectRatioDenominator { get; }
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


