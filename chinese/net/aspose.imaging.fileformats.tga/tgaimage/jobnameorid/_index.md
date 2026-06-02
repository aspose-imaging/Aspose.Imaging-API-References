---
title: "TgaImage.JobNameOrId"
second_title: "Aspose.Imaging for .NET API 参考"
description: "TgaImage 属性。检索或设置与图像关联的作业名称或 ID。此属性使您能够访问或修改与图像相关的特定作业或项目的元数据。通过使用作业名称/ID 属性，用户可以轻松识别图像所属的项目或任务，从而促进在更大工作流或项目中对图像资产的组织和管理。"
type: docs
weight: 180
url: /zh/net/aspose.imaging.fileformats.tga/tgaimage/jobnameorid/
---
## TgaImage.JobNameOrId property

获取或设置与图像关联的作业名称或 ID。此属性使您能够访问或修改与图像相关的特定作业或项目的元数据。通过使用作业名称/ID 属性，用户可以轻松识别图像所属的项目或任务，促进在更大工作流或项目中对图像资产的组织和管理。

```csharp
public string JobNameOrId { get; set; }
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


