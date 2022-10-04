---
title: AdjustContrast
second_title: Aspose.Imaging för .NET API-referens
description: Bild kontrasterande
type: docs
weight: 30
url: /sv/net/aspose.imaging/rastercachedimage/adjustcontrast/
---
## RasterCachedImage.AdjustContrast method

Bild kontrasterande

```csharp
public override void AdjustContrast(float contrast)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| contrast | Single | Kontrastvärde (inom området [-100; 100]) |

### Exempel

Följande exempel utför kontrastkorrigering av en rastercachad bild.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterCachedImage rasterImage = (Aspose.Imaging.RasterCachedImage)image;

    // Ställ in kontrastvärdet. De accepterade kontrastvärdena ligger inom området [-100f, 100f].
    rasterImage.AdjustContrast(50);
    rasterImage.Save(dir + "sample.AdjustContrast.png");
}
```

### Se även

* class [RasterCachedImage](../../rastercachedimage)
* namnutrymme [Aspose.Imaging](../../rastercachedimage)
* hopsättning [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->