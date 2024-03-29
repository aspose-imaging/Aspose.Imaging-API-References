---
title: AdjustBrightness
second_title: Aspose.Imaging för .NET API-referens
description: Justera en ljusstyrka för bilden.
type: docs
weight: 20
url: /sv/net/aspose.imaging/rastercachedimage/adjustbrightness/
---
## RasterCachedImage.AdjustBrightness method

Justera en ljusstyrka för bilden.

```csharp
public override void AdjustBrightness(int brightness)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| brightness | Int32 | Ljusstyrka värde. |

### Exempel

Följande exempel utför ljusstyrkekorrigering av en rastercachad bild.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterCachedImage rasterImage = (Aspose.Imaging.RasterCachedImage)image;

    // Ställ in ljusstyrka. De accepterade värdena för ljusstyrka ligger inom området [-255, 255].
    rasterImage.AdjustBrightness(50);
    rasterImage.Save(dir + "sample.AdjustBrightness.png");
}
```

### Se även

* class [RasterCachedImage](../../rastercachedimage)
* namnutrymme [Aspose.Imaging](../../rastercachedimage)
* hopsättning [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
