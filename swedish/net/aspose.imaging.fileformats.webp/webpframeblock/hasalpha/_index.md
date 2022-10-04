---
title: HasAlpha
second_title: Aspose.Imaging för .NET API-referens
description: Får ett värde som indikerar om denna instans har alpha.
type: docs
weight: 80
url: /sv/net/aspose.imaging.fileformats.webp/webpframeblock/hasalpha/
---
## WebPFrameBlock.HasAlpha property

Får ett värde som indikerar om denna instans har alpha.

```csharp
public override bool HasAlpha { get; }
```

### Fastighetsvärde

`Sann` om denna instans har alfa; annat,`falsk` .

### Exempel

Följande exempel laddar en WEBP-bild och skriver ut information om rådataformat och alfakanal.

```csharp
[C#]

string dir = "c:\\temp\\";

string fileName = dir + "sample.webp";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(fileName))
{
    Aspose.Imaging.FileFormats.Webp.WebPImage webpImage = (Aspose.Imaging.FileFormats.Webp.WebPImage)image;

    // Om den aktiva TIFF-ramen har en alfakanal, anses hela TIFF-bilden ha en alfakanal.
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

// Utdata kan se ut så här:
// ImageFile=c:\temp\sample.webp, FileFormat=RgbIndexed1Bpp, använda kanaler: 1, HasAlpha=False
// Frame=0, FileFormat=RgbIndexed1Bpp, använda kanaler: 1, HasAlpha=False
```

### Se även

* class [WebPFrameBlock](../../webpframeblock)
* namnutrymme [Aspose.Imaging.FileFormats.Webp](../../webpframeblock)
* hopsättning [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->