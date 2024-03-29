---
title: Grayscale
second_title: Aspose.Imaging för .NET API-referens
description: Transformation av en bild till dess gråskalerepresentation
type: docs
weight: 350
url: /sv/net/aspose.imaging/rasterimage/grayscale/
---
## RasterImage.Grayscale method

Transformation av en bild till dess gråskalerepresentation

```csharp
public virtual void Grayscale()
```

### Exempel

Följande exempel omvandlar en färgad rasterbild till dess gråskalerepresentation. Gråskalebilder består uteslutande av gråtoner och innehåller endast intensitetsinformation.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    rasterImage.Grayscale();
    rasterImage.Save(dir + "sample.Grayscale.png");
}
```

### Se även

* class [RasterImage](../../rasterimage)
* namnutrymme [Aspose.Imaging](../../rasterimage)
* hopsättning [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
