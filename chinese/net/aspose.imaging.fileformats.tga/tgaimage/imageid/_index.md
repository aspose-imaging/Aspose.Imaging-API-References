---
title: "TgaImage.ImageId"
second_title: "Aspose.Imaging for .NET API 参考"
description: "TgaImage 属性。获取或设置与图像关联的唯一标识符。此 ID 作为在系统或应用程序中识别和区分图像的参考点。通过设置或检索图像 ID，您可以有效管理和跟踪图像，促进有序的图像管理和检索过程。"
type: docs
weight: 160
url: /zh/net/aspose.imaging.fileformats.tga/tgaimage/imageid/
---
## TgaImage.ImageId property

获取或设置与图像关联的唯一标识符。此 ID 用作在系统或应用程序中识别和区分图像的参考点。通过设置或检索 Image ID，您可以有效管理和跟踪图像，促进有序的图像管理和检索过程。

此可选字段包含图像的识别信息。该字段的最大长度为 255 字节。

```csharp
public string ImageId { get; set; }
```

## 示例

更新已加载 TGA 图像的公共属性。

```csharp
[C#]

using (TgaImage image = (TgaImage)Image.Load("test.tga"))
{
    image.DateTimeStamp = testTime;
    image.AuthorName = "John Smith";
    image.AuthorComments = "Comment";
    image.ImageId = "ImageId";
    image.JobNameOrId = "Important Job";
    image.JobTime = TimeSpan.FromDays(10);
    image.TransparentColor = Color.FromArgb(123);
    image.SoftwareId = "SoftwareId";
    image.SoftwareVersion = "abc1";
    image.SoftwareVersionLetter = 'a';
    image.SoftwareVersionNumber = 2;
    image.XOrigin = 1000;
    image.YOrigin = 1000;

    image.Save("test.tga")
}
```

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


