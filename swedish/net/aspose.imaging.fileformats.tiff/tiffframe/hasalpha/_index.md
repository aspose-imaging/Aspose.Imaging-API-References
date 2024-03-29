---
title: HasAlpha
second_title: Aspose.Imaging för .NET API-referens
description: Får ett värde som indikerar om denna instans har alpha.
type: docs
weight: 80
url: /sv/net/aspose.imaging.fileformats.tiff/tiffframe/hasalpha/
---
## TiffFrame.HasAlpha property

Får ett värde som indikerar om denna instans har alpha.

```csharp
public override bool HasAlpha { get; }
```

### Fastighetsvärde

`Sann` om denna instans har alfa; annat,`falsk` .

### Exempel

Följande exempel laddar en TIFF-bild och skriver ut information om rådataformat och alfakanal.

```csharp
[C#]

string dir = "c:\\temp\\";

string fileName = dir + "sample.tif";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(fileName))
{
    Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = (Aspose.Imaging.FileFormats.Tiff.TiffImage)image;

    // Om den aktiva TIFF-ramen har en alfakanal, anses hela TIFF-bilden ha en alfakanal.
    System.Console.WriteLine("ImageFile={0}, FileFormat={1}, HasAlpha={2}", fileName, tiffImage.RawDataFormat, tiffImage.HasAlpha);

    int i = 0;
    foreach (Aspose.Imaging.FileFormats.Tiff.TiffFrame frame in tiffImage.Frames)
    {
        System.Console.WriteLine("Frame={0}, FileFormat={1}, HasAlpha={2}", ++i, frame.RawDataFormat, frame.HasAlpha);
    }
}

// Utdata kan se ut så här:
// ImageFile=c:\temp\sample.tif, FileFormat=RgbIndexed1Bpp, använda kanaler: 1, HasAlpha=False
// Frame=1, FileFormat=RgbIndexed1Bpp, använda kanaler: 1, HasAlpha=False
// Frame=2, FileFormat=RgbIndexed1Bpp, använda kanaler: 1, HasAlpha=False
```

### Se även

* class [TiffFrame](../../tiffframe)
* namnutrymme [Aspose.Imaging.FileFormats.Tiff](../../tiffframe)
* hopsättning [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
