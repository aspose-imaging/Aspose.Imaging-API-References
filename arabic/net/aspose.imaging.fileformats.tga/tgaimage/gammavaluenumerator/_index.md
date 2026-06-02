---
title: "TgaImage.GammaValueNumerator"
second_title: "Aspose.Imaging for .NET API Reference"
description: "TgaImage property. Gets the numerator part of the gamma value which is essential for accurate color representation in images. In images without gamma correction this value should be 1.0. Understanding and utilizing this value is crucial for maintaining color fidelity and ensuring accurate image rendering"
type: docs
weight: 100
url: /ar/net/aspose.imaging.fileformats.tga/tgaimage/gammavaluenumerator/
---
## TgaImage.GammaValueNumerator property

يحصل على الجزء البسط من قيمة غاما، وهو أساسي لتمثيل الألوان بدقة في الصور. في الصور بدون تصحيح غاما، يجب أن تكون هذه القيمة 1.0. فهم واستخدام هذه القيمة أمر حاسم للحفاظ على دقة الألوان وضمان عرض الصورة بدقة.

```csharp
public ushort GammaValueNumerator { get; }
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


