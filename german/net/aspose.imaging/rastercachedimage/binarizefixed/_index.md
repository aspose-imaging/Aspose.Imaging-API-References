---
title: BinarizeFixed
second_title: Aspose.Imaging für .NET-API-Referenz
description: Binarisierung eines Bildes mit vordefiniertem Schwellwert
type: docs
weight: 60
url: /de/net/aspose.imaging/rastercachedimage/binarizefixed/
---
## RasterCachedImage.BinarizeFixed method

Binarisierung eines Bildes mit vordefiniertem Schwellwert

```csharp
public override void BinarizeFixed(byte threshold)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| threshold | Byte | Schwellwert. Wenn der entsprechende Grauwert eines Pixels größer als der Schwellenwert ist, wird ihm ein Wert von 255 zugewiesen, andernfalls 0. |

### Beispiele

Im folgenden Beispiel wird ein zwischengespeichertes Rasterbild mit dem vordefinierten Schwellenwert binarisiert. Binarisierte Bilder enthalten nur 2 Farben - Schwarz und Weiß.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterCachedImage rasterImage = (Aspose.Imaging.RasterCachedImage)image;

    // Binarisiere das Bild mit einem Schwellenwert von 127.
    // Wenn ein entsprechender Grauwert eines Pixels größer als 127 ist, wird ihm ein Wert von 255 zugewiesen, sonst 0.
    rasterImage.BinarizeFixed(127);
    rasterImage.Save(dir + "sample.BinarizeFixed.png");
}
```

### Siehe auch

* class [RasterCachedImage](../../rastercachedimage)
* namensraum [Aspose.Imaging](../../rastercachedimage)
* Montage [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->