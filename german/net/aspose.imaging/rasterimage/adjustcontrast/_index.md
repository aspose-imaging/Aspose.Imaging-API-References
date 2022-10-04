---
title: AdjustContrast
second_title: Aspose.Imaging für .NET-API-Referenz
description: Bildkontrast
type: docs
weight: 200
url: /de/net/aspose.imaging/rasterimage/adjustcontrast/
---
## RasterImage.AdjustContrast method

Bildkontrast

```csharp
public virtual void AdjustContrast(float contrast)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| contrast | Single | Kontrastwert (im Bereich [-100; 100]) |

### Beispiele

Das folgende Beispiel führt eine Kontrastkorrektur eines Bildes durch.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // Setzen Sie den Kontrastwert. Die akzeptierten Kontrastwerte liegen im Bereich [-100f, 100f].
    rasterImage.AdjustContrast(50);
    rasterImage.Save(dir + "sample.AdjustContrast.png");
}
```

### Siehe auch

* class [RasterImage](../../rasterimage)
* namensraum [Aspose.Imaging](../../rasterimage)
* Montage [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->