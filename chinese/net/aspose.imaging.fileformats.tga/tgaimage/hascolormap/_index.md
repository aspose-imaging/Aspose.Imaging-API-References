---
title: "TgaImage.HasColorMap"
second_title: "Aspose.Imaging for .NET API 参考"
description: "TgaImage 属性。检索此 TgaImage 实例是否包含颜色映射表。了解颜色映射表的存在对于准确解释和操作图像的颜色数据至关重要。"
type: docs
weight: 130
url: /zh/net/aspose.imaging.fileformats.tga/tgaimage/hascolormap/
---
## TgaImage.HasColorMap property

检索此 [`TgaImage`](../) 实例是否包含颜色映射表。了解颜色映射表的存在对于准确解释和操作图像的颜色数据至关重要。

```csharp
public bool HasColorMap { get; }
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


