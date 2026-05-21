---
title: "TgaImage.GammaValueDenominator"
second_title: "Aspose.Imaging for .NET API Reference"
description: "خاصية TgaImage. تسترجع الجزء المقام من قيمة غاما، وهو عامل أساسي في تحديد تمثيل الألوان داخل الصور. بالنسبة للصور التي تفتقر إلى تصحيح غاما يجب أن تكون هذه القيمة 1.0 لضمان تمثيل دقيق للألوان. فهم واستخدام هذه المعلمة أساسي للحفاظ على دقة الألوان وتحقيق تصور صورة دقيق."
type: docs
weight: 90
url: /ar/net/aspose.imaging.fileformats.tga/tgaimage/gammavaluedenominator/
---
## TgaImage.GammaValueDenominator property

يسترجع الجزء المقام من قيمة غاما، وهو عامل أساسي في تحديد تمثيل الألوان داخل الصور. بالنسبة للصور التي لا تحتوي على تصحيح غاما، يجب أن تكون القيمة 1.0، لضمان عرض ألوان دقيق. إن فهم واستخدام هذه المعلمة أساسي للحفاظ على دقة الألوان وتحقيق تصور صورة دقيق.

```csharp
public ushort GammaValueDenominator { get; }
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


