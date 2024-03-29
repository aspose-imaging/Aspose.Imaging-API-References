---
title: AdjustBrightness
second_title: Aspose.Imaging för .NET API-referens
description: Justera en ljusstyrka för bilden.
type: docs
weight: 190
url: /sv/net/aspose.imaging/rasterimage/adjustbrightness/
---
## RasterImage.AdjustBrightness method

Justera en ljusstyrka för bilden.

```csharp
public virtual void AdjustBrightness(int brightness)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| brightness | Int32 | Ljusstyrka värde. |

### Exempel

Följande exempel utför ljusstyrkekorrigering av en bild.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // Ställ in ljusstyrka. De accepterade värdena för ljusstyrka ligger inom området [-255, 255].
    rasterImage.AdjustBrightness(50);
    rasterImage.Save(dir + "sample.AdjustBrightness.png");
}
```

### Se även

* class [RasterImage](../../rasterimage)
* namnutrymme [Aspose.Imaging](../../rasterimage)
* hopsättning [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
