---
title: BinarizeOtsu
second_title: Aspose.Imaging für .NET-API-Referenz
description: Binarisierung eines Bildes mit Otsu-Thresholding
type: docs
weight: 70
url: /de/net/aspose.imaging/rastercachedimage/binarizeotsu/
---
## RasterCachedImage.BinarizeOtsu method

Binarisierung eines Bildes mit Otsu-Thresholding

```csharp
public override void BinarizeOtsu()
```

### Beispiele

Im folgenden Beispiel wird ein zwischengespeichertes Rasterbild mit Otsu-Schwellenwerten binarisiert. Binarisierte Bilder enthalten nur 2 Farben - Schwarz und Weiß.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterCachedImage rasterImage = (Aspose.Imaging.RasterCachedImage)image;

    // Das Bild mit Otsu-Schwellenwerten binarisieren.
    rasterImage.BinarizeOtsu();
    rasterImage.Save(dir + "sample.BinarizeOtsu.png");
}
```

### Siehe auch

* class [RasterCachedImage](../../rastercachedimage)
* namensraum [Aspose.Imaging](../../rastercachedimage)
* Montage [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
