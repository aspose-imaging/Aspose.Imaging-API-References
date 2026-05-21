---
title: "TgaImage.Height"
second_title: "Aspose.Imaging for .NET API Reference"
description: "خاصية TgaImage. الحصول على ارتفاع الصورة التي يغلفها هذا المثيل من TgaImage. تزود هذه الخاصية المطورين بتفاصيل حيوية حول الأبعاد العمودية للصورة، مما يتيح دمجًا سلسًا ومعالجة الصور ضمن حلولهم البرمجية."
type: docs
weight: 150
url: /ar/net/aspose.imaging.fileformats.tga/tgaimage/height/
---
## TgaImage.Height property

الحصول على ارتفاع الصورة التي يغلفها هذا [`TgaImage`](../) المثيل. تزود هذه الخاصية المطورين بتفاصيل حيوية حول الأبعاد العمودية للصورة، مما يتيح دمجًا سلسًا ومعالجة الصور ضمن حلولهم البرمجية.

```csharp
public override int Height { get; }
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


