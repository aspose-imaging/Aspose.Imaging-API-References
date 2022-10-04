---
title: BinarizeOtsu
second_title: Aspose.Imaging für .NET-API-Referenz
description: Binarisierung eines Bildes mit Otsu-Thresholding
type: docs
weight: 280
url: /de/net/aspose.imaging.fileformats.gif/gifimage/binarizeotsu/
---
## GifImage.BinarizeOtsu method

Binarisierung eines Bildes mit Otsu-Thresholding

```csharp
public override void BinarizeOtsu()
```

### Beispiele

Im folgenden Beispiel wird ein GIF-Bild mit Otsu-Schwellenwerten binarisiert. Binarisierte Bilder enthalten nur 2 Farben - Schwarz und Weiß.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    Aspose.Imaging.FileFormats.Gif.GifImage gifImage = (Aspose.Imaging.FileFormats.Gif.GifImage)image;

    // Das Bild mit Otsu-Schwellenwerten binarisieren.
    gifImage.BinarizeOtsu();
    gifImage.Save(dir + "sample.BinarizeOtsu.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### Siehe auch

* class [GifImage](../../gifimage)
* namensraum [Aspose.Imaging.FileFormats.Gif](../../gifimage)
* Montage [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->