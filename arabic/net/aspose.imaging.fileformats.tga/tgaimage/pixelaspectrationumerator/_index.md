---
title: "TgaImage.PixelAspectRatioNumerator"
second_title: "Aspose.Imaging for .NET API Reference"
description: "TgaImage property. تسترجع العنصر البسط من نسبة أبعاد البكسل التي تؤثر على الشكل البصري للبكسلات داخل الصورة. فهم وتعديل هذه القيمة أمر أساسي لتحقيق تمثيل دقيق للبكسل ونسب الأبعاد في عرض ومعالجة الصورة."
type: docs
weight: 210
url: /ar/net/aspose.imaging.fileformats.tga/tgaimage/pixelaspectrationumerator/
---
## TgaImage.PixelAspectRatioNumerator property

يسترجع الجزء البسط من نسبة أبعاد البكسل، الذي يؤثر على الشكل البصري للبكسلات داخل الصورة. فهم وتعديل هذه القيمة أمر أساسي لتحقيق تمثيل دقيق للبكسل ونسب الأبعاد في عرض ومعالجة الصور.

```csharp
public ushort PixelAspectRatioNumerator { get; }
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


