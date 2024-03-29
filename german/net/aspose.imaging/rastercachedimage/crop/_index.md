---
title: Crop
second_title: Aspose.Imaging für .NET-API-Referenz
description: Bild zuschneiden.
type: docs
weight: 90
url: /de/net/aspose.imaging/rastercachedimage/crop/
---
## RasterCachedImage.Crop method

Bild zuschneiden.

```csharp
public override void Crop(Rectangle rectangle)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rectangle | Rectangle | Das Rechteck. |

### Beispiele

Das folgende Beispiel beschneidet ein zwischengespeichertes Rasterbild. Der Zuschneidebereich wird über Aspose.Imaging.Rectangle angegeben.

```csharp
[C#]

string dir = @"c:\temp\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterCachedImage rasterImage = (Aspose.Imaging.RasterCachedImage)image;

    // Bild zuschneiden. Der Zuschneidebereich ist der rechteckige zentrale Bereich des Bildes.
    Aspose.Imaging.Rectangle area = new Aspose.Imaging.Rectangle(rasterImage.Width / 4, rasterImage.Height / 4, rasterImage.Width / 2, rasterImage.Height / 2);
    rasterImage.Crop(area);

    // Speichern Sie das zugeschnittene Bild in PNG
    rasterImage.Save(dir + "sample.Crop.png");
}
```

### Siehe auch

* struct [Rectangle](../../rectangle)
* class [RasterCachedImage](../../rastercachedimage)
* namensraum [Aspose.Imaging](../../rastercachedimage)
* Montage [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
