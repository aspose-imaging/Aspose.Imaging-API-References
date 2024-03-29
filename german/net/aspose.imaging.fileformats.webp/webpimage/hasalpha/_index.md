---
title: HasAlpha
second_title: Aspose.Imaging für .NET-API-Referenz
description: Ruft den Has-Alphakanal ab.
type: docs
weight: 30
url: /de/net/aspose.imaging.fileformats.webp/webpimage/hasalpha/
---
## WebPImage.HasAlpha property

Ruft den Has-Alphakanal ab.

```csharp
public override bool HasAlpha { get; }
```

### Eigentumswert

Der hat Alphakanal.

### Beispiele

Das folgende Beispiel lädt ein WEBP-Bild und druckt Informationen über das Rohdatenformat und den Alphakanal.

```csharp
[C#]

string dir = "c:\\temp\\";

string fileName = dir + "sample.webp";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(fileName))
{
    Aspose.Imaging.FileFormats.Webp.WebPImage webpImage = (Aspose.Imaging.FileFormats.Webp.WebPImage)image;

    // Wenn der aktive TIFF-Frame einen Alphakanal hat, wird das gesamte TIFF-Bild als Alphakanal betrachtet.
    System.Console.WriteLine("ImageFile={0}, FileFormat={1}, HasAlpha={2}", fileName, webpImage.RawDataFormat, webpImage.HasAlpha);

    int i = 0;
    foreach (Aspose.Imaging.FileFormats.Webp.IFrame frame in webpImage.Blocks)
    {
        Aspose.Imaging.FileFormats.Webp.WebPFrameBlock frameBlock = frame as Aspose.Imaging.FileFormats.Webp.WebPFrameBlock;
        if (frameBlock != null)
        {
            System.Console.WriteLine("Frame={0}, FileFormat={1}, HasAlpha={2}", i++, frameBlock.RawDataFormat, frameBlock.HasAlpha);
        }
    }
}

// Die Ausgabe könnte so aussehen:
// ImageFile=c:\temp\sample.webp, FileFormat=RgbIndexed1Bpp, verwendete Kanäle: 1, HasAlpha=False
// Frame=0, FileFormat=RgbIndexed1Bpp, verwendete Kanäle: 1, HasAlpha=False
```

### Siehe auch

* class [WebPImage](../../webpimage)
* namensraum [Aspose.Imaging.FileFormats.Webp](../../webpimage)
* Montage [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
