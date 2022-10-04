---
title: BinarizeFixed
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Binarizzazione di unimmagine con soglia predefinita
type: docs
weight: 230
url: /it/net/aspose.imaging/rasterimage/binarizefixed/
---
## RasterImage.BinarizeFixed method

Binarizzazione di un'immagine con soglia predefinita

```csharp
public virtual void BinarizeFixed(byte threshold)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| threshold | Byte | Valore di soglia. Se il valore di grigio corrispondente di un pixel è maggiore della soglia, gli verrà assegnato un valore di 255, altrimenti 0. |

### Esempi

L'esempio seguente esegue il binarismo di un'immagine raster con la soglia predefinita. Le immagini binarie contengono solo 2 colori: bianco e nero.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // Binarizza l'immagine con un valore di soglia di 127.
    // Se un valore di grigio corrispondente di un pixel è maggiore di 127, gli verrà assegnato un valore di 255, altrimenti 0.
    rasterImage.BinarizeFixed(127);
    rasterImage.Save(dir + "sample.BinarizeFixed.png");
}
```

### Guarda anche

* class [RasterImage](../../rasterimage)
* spazio dei nomi [Aspose.Imaging](../../rasterimage)
* assemblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->