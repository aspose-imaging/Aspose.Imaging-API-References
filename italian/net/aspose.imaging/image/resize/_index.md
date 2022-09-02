---
title: Resize
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Ridimensiona limmagine.
type: docs
weight: 200
url: /it/net/aspose.imaging/image/resize/
---
## Resize(int, int, ImageResizeSettings) {#resize_1}

Ridimensiona l'immagine.

```csharp
public abstract void Resize(int newWidth, int newHeight, ImageResizeSettings settings)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| newWidth | Int32 | La nuova larghezza. |
| newHeight | Int32 | La nuova altezza. |
| settings | ImageResizeSettings | Le impostazioni di ridimensionamento. |

### Esempi

Ridimensiona l'immagine utilizzando un tipo di ridimensionamento specifico.

```csharp
[C#]

using (var image = Image.Load("Photo.jpg"))
{
    image.Resize(640, 480, ResizeType.CatmullRom);
    image.Save("ResizedPhoto.jpg");

    image.Resize(1024, 768, ResizeType.CubicConvolution);
    image.Save("ResizedPhoto2.jpg");

    var resizeSettings = new ImageResizeSettings
    {
        Mode = ResizeType.CubicBSpline,
        FilterType = ImageFilterType.SmallRectangular
    };

    image.Resize(800, 800, resizeSettings);
    image.Save("ResizedPhoto3.jpg");
}
```

Questo esempio carica un'immagine e la ridimensiona utilizzando varie impostazioni di ridimensionamento.

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

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    // Riduci di 2 volte utilizzando il ricampionamento adattivo.
    image.Resize(image.Width / 2, image.Height / 2, resizeSettings);
    image.Save(dir + "downsample.adaptive.gif");
}
```

### Guarda anche

* class [ImageResizeSettings](../../imageresizesettings)
* class [Image](../../image)
* spazio dei nomi [Aspose.Imaging](../../image)
* assemblea [Aspose.Imaging](../../../)

---

## Resize(int, int, ResizeType) {#resize_2}

Ridimensiona l'immagine.

```csharp
public abstract void Resize(int newWidth, int newHeight, ResizeType resizeType)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| newWidth | Int32 | La nuova larghezza. |
| newHeight | Int32 | La nuova altezza. |
| resizeType | ResizeType | Il tipo di ridimensionamento. |

### Esempi

Ridimensiona l'immagine utilizzando un tipo di ridimensionamento specifico.

```csharp
[C#]

using (var image = Image.Load("Photo.jpg"))
{
    image.Resize(640, 480, ResizeType.CatmullRom);
    image.Save("ResizedPhoto.jpg");

    image.Resize(1024, 768, ResizeType.CubicConvolution);
    image.Save("ResizedPhoto2.jpg");

    var resizeSettings = new ImageResizeSettings
    {
        Mode = ResizeType.CubicBSpline,
        FilterType = ImageFilterType.SmallRectangular
    };

    image.Resize(800, 800, resizeSettings);
    image.Save("ResizedPhoto3.jpg");
}
```

Questo esempio carica un'immagine e la ridimensiona utilizzando vari metodi di ridimensionamento.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    // Aumenta di 2 volte utilizzando il ricampionamento Nearest Neighbor.
    image.Resize(image.Width* 2, image.Height* 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);
    image.Save(dir + "upsample.nearestneighbour.gif");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    // Ridimensiona di 2 volte usando il ricampionamento Nearest Neighbor.
    image.Resize(image.Width / 2, image.Height / 2, Aspose.Imaging.ResizeType.NearestNeighbourResample);
    image.Save(dir + "downsample.nearestneighbour.gif");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    // Aumenta di 2 volte utilizzando il ricampionamento bilineare.
    image.Resize(image.Width* 2, image.Height* 2, Aspose.Imaging.ResizeType.BilinearResample);
    image.Save(dir + "upsample.bilinear.gif");
}

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    // Ridimensiona di 2 volte usando il ricampionamento bilineare.
    image.Resize(image.Width / 2, image.Height / 2, Aspose.Imaging.ResizeType.BilinearResample);
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

## Resize(int, int) {#resize}

Ridimensiona l'immagine. Il predefinitoNearestNeighbourResample viene utilizzato.

```csharp
public void Resize(int newWidth, int newHeight)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| newWidth | Int32 | La nuova larghezza. |
| newHeight | Int32 | La nuova altezza. |

### Esempi

L'esempio seguente mostra come ridimensionare un metafile (WMF ed EMF).

```csharp
[C#]

string dir = "c:\\aspose.imaging\\issues\\net\\3280\\";
string[] fileNames = new[] { "image3.emf", "image4.wmf" };
foreach (string fileName in fileNames)
{
    string inputFilePath = dir + fileName;
    string outputFilePath = dir + "Downscale_" + fileName;

    using (Aspose.Imaging.FileFormats.Emf.MetaImage image = (Aspose.Imaging.FileFormats.Emf.MetaImage)Aspose.Imaging.Image.Load(inputFilePath))
    {
        image.Resize(image.Width / 4, image.Height / 4);
        image.Save(outputFilePath);
    }
}
```

L'esempio seguente mostra come ridimensionare l'immagine SVG e salvarla in PNG.

```csharp
[C#]

string dir = "c:\\aspose.imaging\\net\\issues\\3549";
string[] fileNames = new string[]
{
    "Logotype.svg",
    "sample_car.svg",
    "rg1024_green_grapes.svg",
    "MidMarkerFigure.svg",
    "embeddedFonts.svg"
};

Aspose.Imaging.PointF[] scales = new Aspose.Imaging.PointF[]
{
    new Aspose.Imaging.PointF(0.5f, 0.5f),
    new Aspose.Imaging.PointF(1f, 1f),
    new Aspose.Imaging.PointF(2f, 2f),
    new Aspose.Imaging.PointF(3.5f, 9.2f),
};

foreach (string inputFile in fileNames)
{
    foreach (Aspose.Imaging.PointF scale in scales)
    {
        string outputFile = string.Format("{0}_{1}_{2}.png", inputFile, scale.X.ToString(System.Globalization.CultureInfo.InvariantCulture), scale.Y.ToString(System.Globalization.CultureInfo.InvariantCulture));
        using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(System.IO.Path.Combine(dir, inputFile)))
        {
            image.Resize((int)(image.Width * scale.X), (int)(image.Height * scale.Y));
            image.Save(System.IO.Path.Combine(dir, outputFile), new Aspose.Imaging.ImageOptions.PngOptions());
        }
    }
}
```

### Guarda anche

* class [Image](../../image)
* spazio dei nomi [Aspose.Imaging](../../image)
* assemblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
