---
title: Grayscale
second_title: Aspose.Imaging för .NET API-referens
description: Transformation av en bild till dess gråskalerepresentation
type: docs
weight: 110
url: /sv/net/aspose.imaging/rastercachedimage/grayscale/
---
## RasterCachedImage.Grayscale method

Transformation av en bild till dess gråskalerepresentation

```csharp
public override void Grayscale()
```

### Exempel

Följande exempel omvandlar en färgad rastercachebild till dess gråskalerepresentation. Gråskalebilder består uteslutande av gråtoner och innehåller endast intensitetsinformation.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterCachedImage rasterImage = (Aspose.Imaging.RasterCachedImage)image;

    rasterImage.Grayscale();
    rasterImage.Save(dir + "sample.Grayscale.png");
}
```

### Se även

* class [RasterCachedImage](../../rastercachedimage)
* namnutrymme [Aspose.Imaging](../../rastercachedimage)
* hopsättning [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->