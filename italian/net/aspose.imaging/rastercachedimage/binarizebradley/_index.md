---
title: BinarizeBradley
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Binarizzazione di unimmagine utilizzando lalgoritmo di soglia adattivo di Bradley utilizzando la soglia di immagine integrale
type: docs
weight: 50
url: /it/net/aspose.imaging/rastercachedimage/binarizebradley/
---
## BinarizeBradley(double, int) {#binarizebradley_1}

Binarizzazione di un'immagine utilizzando l'algoritmo di soglia adattivo di Bradley utilizzando la soglia di immagine integrale

```csharp
public override void BinarizeBradley(double brightnessDifference, int windowSize)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| brightnessDifference | Double | La differenza di luminosità tra pixel e la media di una finestra sxs di pixel centrata attorno a questo pixel. |
| windowSize | Int32 | La dimensione della finestra sxs di pixel centrata attorno a questo pixel |

### Esempi

L'esempio seguente esegue il binarismo di un'immagine raster memorizzata nella cache con l'algoritmo di soglia adattivo di Bradley con la dimensione della finestra specificata. Le immagini binarie contengono solo 2 colori: bianco e nero.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterCachedImage rasterImage = (Aspose.Imaging.RasterCachedImage)image;

    // Binarizza l'immagine con una differenza di luminosità di 5.
    // La luminosità è una differenza tra un pixel e la media di una finestra di 10 x 10 pixel centrata attorno a questo pixel.
    rasterImage.BinarizeBradley(5, 10);
    rasterImage.Save(dir + "sample.BinarizeBradley5_10x10.png");
}
```

### Guarda anche

* class [RasterCachedImage](../../rastercachedimage)
* spazio dei nomi [Aspose.Imaging](../../rastercachedimage)
* assemblea [Aspose.Imaging](../../../)

---

## BinarizeBradley(double) {#binarizebradley}

Binarizzazione di un'immagine utilizzando l'algoritmo di soglia adattivo di Bradley utilizzando la soglia di immagine integrale

```csharp
public override void BinarizeBradley(double brightnessDifference)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| brightnessDifference | Double | La differenza di luminosità tra pixel e la media di una finestra sxs di pixel centrata attorno a questo pixel. |

### Esempi

L'esempio seguente esegue il binarismo di un'immagine raster memorizzata nella cache con l'algoritmo di soglia adattivo di Bradley. Le immagini binarie contengono solo 2 colori: bianco e nero.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterCachedImage rasterImage = (Aspose.Imaging.RasterCachedImage)image;

    // Binarizza l'immagine con una differenza di luminosità di 5. 
    // La luminosità è una differenza tra un pixel e la media di una finestra sxs di pixel centrata attorno a questo pixel.
    // La dimensione della finestra verrà calibrata automaticamente.
    rasterImage.BinarizeBradley(5);
    rasterImage.Save(dir + "sample.BinarizeBradley5.png");
}
```

### Guarda anche

* class [RasterCachedImage](../../rastercachedimage)
* spazio dei nomi [Aspose.Imaging](../../rastercachedimage)
* assemblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->