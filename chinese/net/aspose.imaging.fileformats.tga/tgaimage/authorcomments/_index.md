---
title: "TgaImage.AuthorComments"
second_title: "Aspose.Imaging for .NET API 参考"
description: "TgaImage 属性。检索或设置图像作者提供的注释。这些注释通常包含有价值的信息，如描述、注释或关于图像的其他上下文。通过访问或修改 Author Comments 属性，开发者可以增强与图像关联的元数据，为用户提供有关其内容或创建的有价值的见解和上下文。该字段为 ASCII，长度为 324 字节，组织为四行每行 80 个字符，随后是空字符终止符。"
type: docs
weight: 20
url: /zh/net/aspose.imaging.fileformats.tga/tgaimage/authorcomments/
---
## TgaImage.AuthorComments property

检索或设置图像作者提供的注释。这些注释通常包含有价值的信息，如描述、标注或关于图像的其他上下文。通过访问或修改 Author Comments 属性，开发者可以增强图像的元数据，为用户提供有关内容或创作的有价值的洞察和背景。该字段为 ASCII，长度为 324 字节，组织为四行每行 80 个字符，随后跟随一个空字符终止符。

```csharp
public string AuthorComments { get; set; }
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


