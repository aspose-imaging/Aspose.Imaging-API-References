---
title: GammaValueNumerator
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Gets Gamma Value Numerator part. Une image non corrigée une image sans gamma doit avoir la valeur 1.0 comme résultat.
type: docs
weight: 100
url: /fr/net/aspose.imaging.fileformats.tga/tgaimage/gammavaluenumerator/
---
## TgaImage.GammaValueNumerator property

Gets Gamma Value Numerator part. Une image non corrigée (une image sans gamma) doit avoir la valeur 1.0 comme résultat.

```csharp
public ushort GammaValueNumerator { get; }
```

### Exemples

Obtention des valeurs des propriétés publiques de l'image TGA chargée.

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

### Voir également

* class [TgaImage](../../tgaimage)
* espace de noms [Aspose.Imaging.FileFormats.Tga](../../tgaimage)
* Assemblée [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->