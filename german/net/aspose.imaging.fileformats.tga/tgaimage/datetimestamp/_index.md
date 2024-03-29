---
title: DateTimeStamp
second_title: Aspose.Imaging für .NET-API-Referenz
description: Ruft Datums-/Zeitstempel ab oder legt diesen fest. Dieses Feld definiert den Wert für das Datum und die Uhrzeit zu der das Bild gespeichert wurde. Obwohl Betriebssysteme Dateien normalerweise mit Zeit- und Datumsstempeln versehen wird diese Funktion bereitgestellt da das Betriebssystem den Zeit- und Datumsstempel ändern kann wenn die Datei kopiert wird. Durch die Verwendung dieses Bereichs wird Ihnen ein unveränderter Bereich für die Aufnahme von Datum und Uhrzeit garantiert.
type: docs
weight: 70
url: /de/net/aspose.imaging.fileformats.tga/tgaimage/datetimestamp/
---
## TgaImage.DateTimeStamp property

Ruft Datums-/Zeitstempel ab oder legt diesen fest. Dieses Feld definiert den Wert für das Datum und die Uhrzeit, zu der das Bild gespeichert wurde. Obwohl Betriebssysteme Dateien normalerweise mit Zeit- und Datumsstempeln versehen, wird diese Funktion bereitgestellt, da das Betriebssystem den Zeit- und Datumsstempel ändern kann, wenn die Datei kopiert wird. Durch die Verwendung dieses Bereichs wird Ihnen ein unveränderter Bereich für die Aufnahme von Datum und Uhrzeit garantiert.

```csharp
public DateTime? DateTimeStamp { get; set; }
```

### Beispiele

Aktualisieren öffentlicher Eigenschaften des geladenen TGA-Bildes.

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
