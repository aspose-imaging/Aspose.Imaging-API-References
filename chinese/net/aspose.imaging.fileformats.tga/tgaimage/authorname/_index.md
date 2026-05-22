---
title: "TgaImage.AuthorName"
second_title: "Aspose.Imaging for .NET API 参考"
description: "TgaImage 属性。检索或设置与图像关联的作者名称。此属性允许开发者访问或修改作者名称元数据，提供有关图像创建者的有价值信息。通过使用作者名称属性，用户可以轻松识别负责创建或贡献图像的个人，提升整体元数据并为观众提供有价值的上下文。此字段最多容纳 40 个 ASCII 字符用于存放名称。如果使用该字段，应填写创建该图像的作者姓名。"
type: docs
weight: 30
url: /zh/net/aspose.imaging.fileformats.tga/tgaimage/authorname/
---
## TgaImage.AuthorName property

检索或设置与图像关联的作者姓名。此属性允许开发者访问或修改作者姓名元数据，提供有关图像创建者的有价值信息。通过使用 Author Name 属性，用户可以轻松识别图像的创作者或贡献者，提升整体元数据并为观众提供有价值的上下文。该字段总计 40 个 ASCII 字符用于存放姓名。如果使用该字段，应包含创建图像的人的姓名（作者）。

```csharp
public string AuthorName { get; set; }
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


