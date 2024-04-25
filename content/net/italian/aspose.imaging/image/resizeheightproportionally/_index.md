---
title: ResizeHeightProportionally
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Ridimensiona proporzionalmente laltezza. Il predefinitoNearestNeighbourResample viene utilizzato.
type: docs
weight: 210
url: /it/aspose.imaging/image/resizeheightproportionally/
---
## ResizeHeightProportionally(int) {#resizeheightproportionally}

Ridimensiona proporzionalmente l'altezza. Il predefinitoNearestNeighbourResample viene utilizzato.

```csharp
public void ResizeHeightProportionally(int newHeight)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| newHeight | Int32 | La nuova altezza. |

### Guarda anche

* class [Image](../../image)
* spazio dei nomi [Aspose.Imaging](../../image)
* assemblea [Aspose.Imaging](../../../)

---

## ResizeHeightProportionally(int, ResizeType) {#resizeheightproportionally_2}

Ridimensiona proporzionalmente l'altezza.

```csharp
public virtual void ResizeHeightProportionally(int newHeight, ResizeType resizeType)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| newHeight | Int32 | La nuova altezza. |
| resizeType | ResizeType | Tipo di ridimensionamento. |

### Esempi

Questo esempio carica un'immagine e la ridimensiona proporzionalmente utilizzando vari metodi di ridimensionamento. Viene specificata solo l'altezza, la larghezza viene calcolata automaticamente.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    // Aumenta di 2 volte utilizzando il ricampionamento Nearest Neighbor.
    image.ResizeHeightProportionally(image.Height* 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);
    image.Save(dir + "upsample.nearestneighbour.gif");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    // Ridimensiona di 2 volte usando il ricampionamento Nearest Neighbor.
    image.ResizeHeightProportionally(image.Height / 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);
    image.Save(dir + "upsample.nearestneighbour.gif");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    // Aumenta di 2 volte utilizzando il ricampionamento bilineare.
    image.ResizeHeightProportionally(image.Height* 2, Aspose.Imaging.ResizeType.BilinearResample);
    image.Save(dir + "upsample.bilinear.gif");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    // Ridimensiona di 2 volte usando il ricampionamento bilineare.
    image.ResizeHeightProportionally(image.Height / 2, Aspose.Imaging.ResizeType.BilinearResample);
    image.Save(dir + "downsample.bilinear.gif");
}
```

Utilizzo di una maschera di segmento per accelerare il processo di segmentazione

```csharp
[C#]

// Opzioni di esportazione mascheratura
Aspose.Imaging.ImageOptions.PngOptions exportOptions = new Aspose.Imaging.ImageOptions.PngOptions();
exportOptions.ColorType = Aspose.Imaging.FileFormats.Png.PngColorType.TruecolorWithAlpha;
exportOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream());

Aspose.Imaging.Masking.Options.MaskingOptions maskingOptions = new Aspose.Imaging.Masking.Options.MaskingOptions();
    
// Usa il clustering di GraphCut.
maskingOptions.Method = Masking.Options.SegmentationMethod.GraphCut;
maskingOptions.Decompose = false;
maskingOptions.Args = new Aspose.Imaging.Masking.Options.AutoMaskingArgs();

// Il colore dello sfondo sarà trasparente.
maskingOptions.BackgroundReplacementColor = Aspose.Imaging.Color.Transparent;
maskingOptions.ExportOptions = exportOptions;

string dir = "c:\\temp\\";
using (Aspose.Imaging.RasterImage image = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Load(dir + "BigImage.jpg"))
{
    Aspose.Imaging.Size imageSize = image.Size;

    // Ridurre le dimensioni dell'immagine per accelerare il processo di segmentazione
    image.ResizeHeightProportionally(600, Aspose.Imaging.ResizeType.HighQualityResample);

    // Crea un'istanza della classe ImageMasking.
    Aspose.Imaging.Masking.ImageMasking masking = new Aspose.Imaging.Masking.ImageMasking(image);

    // Dividi l'immagine di origine in diversi cluster (segmenti).
    using (Aspose.Imaging.Masking.Result.MaskingResult maskingResult = masking.Decompose(maskingOptions))
    {
        // Ottenere la maschera in primo piano
        using (Aspose.Imaging.RasterImage foregroundMask = maskingResult[1].GetMask()) 
        {
            // Aumenta le dimensioni della maschera alle dimensioni dell'immagine originale
            foregroundMask.Resize(imageSize.Width, imageSize.Height, Aspose.Imaging.ResizeType.NearestNeighbourResample);

            // Applicazione della maschera all'immagine originale per ottenere un segmento in primo piano
            using (Aspose.Imaging.RasterImage originImage = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Load(dir + "BigImage.jpg"))
            {
                Aspose.Imaging.Masking.ImageMasking.ApplyMask(originImage, foregroundMask, maskingOptions);
                originImage.Save(dir + "BigImage_foreground.png", exportOptions);
            }
        }
    }
}
```

### Guarda anche

* enum [ResizeType](../../resizetype)
* class [Image](../../image)
* spazio dei nomi [Aspose.Imaging](../../image)
* assemblea [Aspose.Imaging](../../../)

---

## ResizeHeightProportionally(int, ImageResizeSettings) {#resizeheightproportionally_1}

Ridimensiona proporzionalmente l'altezza.

```csharp
public virtual void ResizeHeightProportionally(int newHeight, ImageResizeSettings settings)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| newHeight | Int32 | La nuova altezza. |
| settings | ImageResizeSettings | Le impostazioni di ridimensionamento dell'immagine. |

### Guarda anche

* class [ImageResizeSettings](../../imageresizesettings)
* class [Image](../../image)
* spazio dei nomi [Aspose.Imaging](../../image)
* assemblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
