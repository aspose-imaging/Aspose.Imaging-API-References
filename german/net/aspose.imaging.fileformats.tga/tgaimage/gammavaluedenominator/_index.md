---
title: GammaValueDenominator
second_title: Aspose.Imaging für .NET-API-Referenz
description: Ruft den Teil des Gamma-Wert-Nenners ab. Ein unkorrigiertes Bild ein Bild ohne Gamma sollte als Ergebnis den Wert 10 haben.
type: docs
weight: 90
url: /de/net/aspose.imaging.fileformats.tga/tgaimage/gammavaluedenominator/
---
## TgaImage.GammaValueDenominator property

Ruft den Teil des Gamma-Wert-Nenners ab. Ein unkorrigiertes Bild (ein Bild ohne Gamma) sollte als Ergebnis den Wert 1,0 haben.

```csharp
public ushort GammaValueDenominator { get; }
```

### Beispiele

Abrufen von Werten der öffentlichen Eigenschaften des geladenen TGA-Bildes.

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

### Siehe auch

* class [TgaImage](../../tgaimage)
* namensraum [Aspose.Imaging.FileFormats.Tga](../../tgaimage)
* Montage [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->