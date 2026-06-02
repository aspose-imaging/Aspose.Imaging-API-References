---
title: "TgaImage.TransparentColor"
second_title: "Aspose.Imaging for .NET API 参考"
description: "TgaImage 属性。检索或设置与图像关联的关键颜色。此属性允许您访问或修改指定为关键颜色的颜色，以用于特定的图像处理任务或效果。使用关键颜色属性可让用户执行基于颜色的操作，如色度键控或颜色替换，提升图像操作能力和创意可能性。"
type: docs
weight: 260
url: /zh/net/aspose.imaging.fileformats.tga/tgaimage/transparentcolor/
---
## TgaImage.TransparentColor property

获取或设置与图像关联的关键颜色。此属性允许您访问或修改指定为特定图像处理任务或效果的关键颜色。使用关键颜色属性可让用户执行基于颜色的操作，如色度键控或颜色替换，增强图像操作能力和创意可能性。

关键颜色可以视为‘背景色’或‘透明色’。它是屏幕上‘非图像’区域的颜色，也是应用程序擦除时屏幕将被清除到的相同颜色。

```csharp
public override Color TransparentColor { get; set; }
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

* struct [Color](../../../aspose.imaging/color/)
* class [TgaImage](../)
* namespace [Aspose.Imaging.FileFormats.Tga](../../tgaimage/)
* assembly [Aspose.Imaging](../../../)


