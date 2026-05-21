---
title: "TgaImage.Width"
second_title: "Aspose.Imaging for .NET API Reference"
description: "TgaImage property. استرجاع عرض الصورة التي يمثلها هذا الكائن من نوع TgaImage. توفر هذه الخاصية للمطورين معلومات أساسية حول أبعاد الصورة مما يسهل مهام التلاعب والمعالجة المختلفة داخل تطبيقاتهم البرمجية."
type: docs
weight: 270
url: /ar/net/aspose.imaging.fileformats.tga/tgaimage/width/
---
## TgaImage.Width property

Retrieve the width of the image represented by this [`TgaImage`](../) instance. This property provides developers with essential information about the image dimensions, facilitating various image manipulation and processing tasks within their software applications.

```csharp
public override int Width { get; }
```

## أمثلة

Getting values of the public properties of the loaded TGA image.

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

### انظر أيضًا

* class [TgaImage](../)
* namespace [Aspose.Imaging.FileFormats.Tga](../../tgaimage/)
* assembly [Aspose.Imaging](../../../)


