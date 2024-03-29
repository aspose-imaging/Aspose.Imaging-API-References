---
title: HasAlpha
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Ottiene un valore che indica se questoTgaImageaspose.imaging.fileformats.tga/tgaimage ha un canale alfa.
type: docs
weight: 110
url: /it/net/aspose.imaging.fileformats.tga/tgaimage/hasalpha/
---
## TgaImage.HasAlpha property

Ottiene un valore che indica se questo[`TgaImage`](../../tgaimage) ha un canale alfa.

```csharp
public override bool HasAlpha { get; }
```

### Esempi

Ottenere i valori delle proprietà pubbliche dell'immagine TGA caricata.

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

### Guarda anche

* class [TgaImage](../../tgaimage)
* spazio dei nomi [Aspose.Imaging.FileFormats.Tga](../../tgaimage)
* assemblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
