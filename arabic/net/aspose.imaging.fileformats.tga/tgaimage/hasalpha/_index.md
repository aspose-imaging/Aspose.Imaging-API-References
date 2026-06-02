---
title: "TgaImage.HasAlpha"
second_title: "Aspose.Imaging for .NET API Reference"
description: "خاصية TgaImage. استرجع قيمة منطقية تشير إلى ما إذا كان TgaImage يتضمن قناة ألفا تُسهل تأثيرات الشفافية. توفر هذه الخاصية معلومات أساسية لمعالجة تركيب الصور وعرضها، مما يساعد المطورين على تنفيذ تأثيرات بصرية متنوعة وعمليات تركيب."
type: docs
weight: 110
url: /ar/net/aspose.imaging.fileformats.tga/tgaimage/hasalpha/
---
## TgaImage.HasAlpha property

استرجع قيمة منطقية تشير إلى ما إذا كان [`TgaImage`](../) يتضمن قناة ألفا، تُسهل تأثيرات الشفافية. توفر هذه الخاصية معلومات أساسية لمعالجة تركيب الصور وعرضها، مما يساعد المطورين على تنفيذ تأثيرات بصرية متنوعة وعمليات تركيب.

```csharp
public override bool HasAlpha { get; }
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


