---
title: BinarizeOtsu
second_title: Aspose.Imaging für .NET-API-Referenz
description: Binarisierung eines Bildes mit Otsu-Thresholding
type: docs
weight: 230
url: /de/net/aspose.imaging.fileformats.tiff/tiffimage/binarizeotsu/
---
## TiffImage.BinarizeOtsu method

Binarisierung eines Bildes mit Otsu-Thresholding

```csharp
public override void BinarizeOtsu()
```

### Beispiele

Im folgenden Beispiel wird ein TIFF-Bild mit Otsu-Schwellenwerten binarisiert. Binarisierte Bilder enthalten nur 2 Farben - Schwarz und Weiß.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.tif"))
{
    Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = (Aspose.Imaging.FileFormats.Tiff.TiffImage)image;

    // Das Bild mit Otsu-Schwellenwerten binarisieren.
    tiffImage.BinarizeOtsu();
    tiffImage.Save(dir + "sample.BinarizeOtsu.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### Siehe auch

* class [TiffImage](../../tiffimage)
* namensraum [Aspose.Imaging.FileFormats.Tiff](../../tiffimage)
* Montage [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
