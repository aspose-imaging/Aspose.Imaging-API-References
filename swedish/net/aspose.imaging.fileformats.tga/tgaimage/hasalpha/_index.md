---
title: HasAlpha
second_title: Aspose.Imaging för .NET API-referens
description: Får ett värde som indikerar om dettaTgaImageaspose.imaging.fileformats.tga/tgaimage har en alfakanal.
type: docs
weight: 110
url: /sv/net/aspose.imaging.fileformats.tga/tgaimage/hasalpha/
---
## TgaImage.HasAlpha property

Får ett värde som indikerar om detta[`TgaImage`](../../tgaimage) har en alfakanal.

```csharp
public override bool HasAlpha { get; }
```

### Exempel

Hämta värden för de offentliga egenskaperna för den inlästa TGA-bilden.

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

### Se även

* class [TgaImage](../../tgaimage)
* namnutrymme [Aspose.Imaging.FileFormats.Tga](../../tgaimage)
* hopsättning [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
