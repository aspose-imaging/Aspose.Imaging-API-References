---
title: AuthorName
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Ottiene o imposta il nome dellautore. Questo campo contiene un totale di 40 caratteri ASCII per il nome. Se il campo è utilizzato deve contenere il nome della persona che ha creato limmagine autore.
type: docs
weight: 30
url: /it/net/aspose.imaging.fileformats.tga/tgaimage/authorname/
---
## TgaImage.AuthorName property

Ottiene o imposta il nome dell'autore. Questo campo contiene un totale di 40 caratteri ASCII per il nome. Se il campo è utilizzato, deve contenere il nome della persona che ha creato l'immagine (autore).

```csharp
public string AuthorName { get; set; }
```

### Esempi

Aggiornamento delle proprietà pubbliche dell'immagine TGA caricata.

```csharp
[C#]

using (TgaImage image = (TgaImage)Image.Load("test.tga"))
{
    image.DateTimeStamp = testTime;
    image.AuthorName = "John Smith";
    image.AuthorComments = "Comment";
    image.ImageId = "ImageId";
    image.JobNameOrId = "Important Job";
    image.JobTime = TimeSpan.FromDays(10);
    image.TransparentColor = Color.FromArgb(123);
    image.SoftwareId = "SoftwareId";
    image.SoftwareVersion = "abc1";
    image.SoftwareVersionLetter = 'a';
    image.SoftwareVersionNumber = 2;
    image.XOrigin = 1000;
    image.YOrigin = 1000;

    image.Save("test.tga")
}
```

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
