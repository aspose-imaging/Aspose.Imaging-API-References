---
title: Resize
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Ridimensiona limmagine.
type: docs
weight: 120
url: /it/net/aspose.imaging/rastercachedimage/resize/
---
## Resize(int, int, ResizeType) {#resize_2}

Ridimensiona l'immagine.

```csharp
public override void Resize(int newWidth, int newHeight, ResizeType resizeType)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| newWidth | Int32 | La nuova larghezza. |
| newHeight | Int32 | La nuova altezza. |
| resizeType | ResizeType | Il tipo di ridimensionamento. |

### Esempi

Questo esempio carica un'immagine raster memorizzata nella cache e la ridimensiona utilizzando vari metodi di ridimensionamento.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.RasterCachedImage image = (Aspose.Imaging.RasterCachedImage)Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    // Aumenta di 2 volte utilizzando il ricampionamento Nearest Neighbor.
    image.Resize(image.Width* 2, image.Height* 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);                

    // Salva in PNG con le opzioni predefinite.
    image.Save(dir + "upsample.nearestneighbour.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.RasterCachedImage image = (Aspose.Imaging.RasterCachedImage)Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    // Ridimensiona di 2 volte usando il ricampionamento Nearest Neighbor.
    image.Resize(image.Width / 2, image.Height / 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);
        
    // Salva in PNG con le opzioni predefinite.
    image.Save(dir + "downsample.nearestneighbour.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.RasterCachedImage image = (Aspose.Imaging.RasterCachedImage)Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    // Aumenta di 2 volte utilizzando il ricampionamento bilineare.
    image.Resize(image.Width* 2, image.Height* 2, Aspose.Imaging.ResizeType.BilinearResample);

    // Salva in PNG con le opzioni predefinite.
    image.Save(dir + "upsample.bilinear.png", new Aspose.Imaging.ImageOptions.PngOptions());
}

using (Aspose.Imaging.RasterCachedImage image = (Aspose.Imaging.RasterCachedImage)Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    // Ridimensiona di 2 volte usando il ricampionamento bilineare.
    image.Resize(image.Width / 2, image.Height / 2, Aspose.Imaging.ResizeType.BilinearResample);
        
    // Salva in PNG con le opzioni predefinite.
    image.Save(dir + "downsample.bilinear.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### Guarda anche

* enum [ResizeType](../../resizetype)
* class [RasterCachedImage](../../rastercachedimage)
* spazio dei nomi [Aspose.Imaging](../../rastercachedimage)
* assemblea [Aspose.Imaging](../../../)

---

## Resize(int, int, ImageResizeSettings) {#resize_1}

Ridimensiona l'immagine.

```csharp
public override void Resize(int newWidth, int newHeight, ImageResizeSettings settings)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| newWidth | Int32 | La nuova larghezza. |
| newHeight | Int32 | La nuova altezza. |
| settings | ImageResizeSettings | Le impostazioni di ridimensionamento. |

### Esempi

Questo esempio carica un'immagine raster memorizzata nella cache e la ridimensiona utilizzando varie impostazioni di ridimensionamento.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageResizeSettings resizeSettings = new Aspose.Imaging.ImageResizeSettings();

// L'algoritmo adattivo basato sulla funzione razionale pesata e mista e sull'interpolazione lanczos3.
resizeSettings.Mode = Aspose.Imaging.ResizeType.AdaptiveResample;

// Il piccolo filtro rettangolare
resizeSettings.FilterType = Aspose.Imaging.ImageFilterType.SmallRectangular;

// Il numero di colori nella tavolozza.
resizeSettings.EntriesCount = 256;

// La quantizzazione del colore non viene utilizzata
resizeSettings.ColorQuantizationMethod = ColorQuantizationMethod.None;

// Il metodo euclideo
resizeSettings.ColorCompareMethod = ColorCompareMethod.Euclidian;

using (Aspose.Imaging.RasterCachedImage image = (Aspose.Imaging.RasterCachedImage)Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    // Riduci di 2 volte utilizzando il ricampionamento adattivo.
    image.Resize(image.Width / 2, image.Height / 2, resizeSettings);
    image.Save(dir + "downsample.adaptive.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### Guarda anche

* class [ImageResizeSettings](../../imageresizesettings)
* class [RasterCachedImage](../../rastercachedimage)
* spazio dei nomi [Aspose.Imaging](../../rastercachedimage)
* assemblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
