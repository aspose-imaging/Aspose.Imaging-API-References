---
title: AdjustBrightness
second_title: Aspose.Imaging för .NET API-referens
description: Justering av enbrightness för bild.
type: docs
weight: 170
url: /sv/net/aspose.imaging.fileformats.tiff/tiffimage/adjustbrightness/
---
## TiffImage.AdjustBrightness method

Justering av en*brightness* för bild.

```csharp
public override void AdjustBrightness(int brightness)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| brightness | Int32 | Ljusstyrka värde. |

### Exempel

Följande exempel utför ljusstyrkekorrigering av en TIFF-bild.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.tif"))
{
    Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = (Aspose.Imaging.FileFormats.Tiff.TiffImage)image;

    // Ställ in ljusstyrka. De accepterade värdena för ljusstyrka ligger inom området [-255, 255].
    tiffImage.AdjustBrightness(50);
    tiffImage.Save(dir + "sample.AdjustBrightness.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### Se även

* class [TiffImage](../../tiffimage)
* namnutrymme [Aspose.Imaging.FileFormats.Tiff](../../tiffimage)
* hopsättning [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->