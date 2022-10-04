---
title: AdjustBrightness
second_title: Aspose.Imaging för .NET API-referens
description: Justering av enbrightness för bild.
type: docs
weight: 230
url: /sv/net/aspose.imaging.fileformats.gif/gifimage/adjustbrightness/
---
## GifImage.AdjustBrightness method

Justering av en*brightness* för bild.

```csharp
public override void AdjustBrightness(int brightness)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| brightness | Int32 | Ljusstyrka värde. |

### Exempel

Följande exempel utför ljusstyrkekorrigering av en GIF-bild.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    Aspose.Imaging.FileFormats.Gif.GifImage gifImage = (Aspose.Imaging.FileFormats.Gif.GifImage)image;

    // Ställ in ljusstyrka. De accepterade värdena för ljusstyrka ligger inom området [-255, 255].
    gifImage.AdjustBrightness(50);
    gifImage.Save(dir + "sample.AdjustBrightness.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### Se även

* class [GifImage](../../gifimage)
* namnutrymme [Aspose.Imaging.FileFormats.Gif](../../gifimage)
* hopsättning [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->