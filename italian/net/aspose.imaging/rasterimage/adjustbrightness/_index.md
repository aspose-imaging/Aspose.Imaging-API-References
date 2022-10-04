---
title: AdjustBrightness
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Regolazione di una luminosità per limmagine.
type: docs
weight: 190
url: /it/net/aspose.imaging/rasterimage/adjustbrightness/
---
## RasterImage.AdjustBrightness method

Regolazione di una luminosità per l'immagine.

```csharp
public virtual void AdjustBrightness(int brightness)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| brightness | Int32 | Valore di luminosità. |

### Esempi

L'esempio seguente esegue la correzione della luminosità di un'immagine.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // Imposta il valore di luminosità. I valori accettati di luminosità sono compresi nell'intervallo [-255, 255].
    rasterImage.AdjustBrightness(50);
    rasterImage.Save(dir + "sample.AdjustBrightness.png");
}
```

### Guarda anche

* class [RasterImage](../../rasterimage)
* spazio dei nomi [Aspose.Imaging](../../rasterimage)
* assemblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->