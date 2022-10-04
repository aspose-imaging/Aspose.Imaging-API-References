---
title: ResizeWidthProportionally
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Ridimensiona proporzionalmente la larghezza.
type: docs
weight: 280
url: /it/net/aspose.imaging.fileformats.djvu/djvuimage/resizewidthproportionally/
---
## DjvuImage.ResizeWidthProportionally method

Ridimensiona proporzionalmente la larghezza.

```csharp
public override void ResizeWidthProportionally(int newWidth, ResizeType resizeType)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| newWidth | Int32 | La nuova larghezza. |
| resizeType | ResizeType | Tipo di ridimensionamento. |

### Esempi

Questo esempio carica un'immagine DJVU e la ridimensiona proporzionalmente utilizzando vari metodi di ridimensionamento. Viene specificata solo la larghezza, l'altezza viene calcolata automaticamente.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.FileFormats.Djvu.DjvuImage image = (Aspose.Imaging.FileFormats.Djvu.DjvuImage)Aspose.Imaging.Image.Load(dir + "sample.djvu"))
{
    // Aumenta di 2 volte utilizzando il ricampionamento Nearest Neighbor.
    image.ResizeWidthProportionally(image.Width* 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);

    // Salva in PNG con le opzioni predefinite.
    image.Save(dir + "upsample.nearestneighbour.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.FileFormats.Djvu.DjvuImage image = (Aspose.Imaging.FileFormats.Djvu.DjvuImage)Aspose.Imaging.Image.Load(dir + "sample.djvu"))
{
    // Ridimensiona di 2 volte usando il ricampionamento Nearest Neighbor.
    image.ResizeWidthProportionally(image.Width / 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);

    // Salva in PNG con le opzioni predefinite.
    image.Save(dir + "downsample.nearestneighbour.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.FileFormats.Djvu.DjvuImage image = (Aspose.Imaging.FileFormats.Djvu.DjvuImage)Aspose.Imaging.Image.Load(dir + "sample.djvu"))
{
    // Aumenta di 2 volte utilizzando il ricampionamento bilineare.
    image.ResizeWidthProportionally(image.Width* 2, Aspose.Imaging.ResizeType.BilinearResample);

    // Salva in PNG con le opzioni predefinite.
    image.Save(dir + "upsample.bilinear.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.FileFormats.Djvu.DjvuImage image = (Aspose.Imaging.FileFormats.Djvu.DjvuImage)Aspose.Imaging.Image.Load(dir + "sample.djvu"))
{
    // Ridimensiona di 2 volte usando il ricampionamento bilineare.
    image.ResizeWidthProportionally(image.Width / 2, Aspose.Imaging.ResizeType.BilinearResample);

    // Salva in PNG con le opzioni predefinite.
    image.Save(dir + "downsample.bilinear.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### Guarda anche

* enum [ResizeType](../../../aspose.imaging/resizetype)
* class [DjvuImage](../../djvuimage)
* spazio dei nomi [Aspose.Imaging.FileFormats.Djvu](../../djvuimage)
* assemblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->