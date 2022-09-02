---
title: MaskingResult
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Classe astratta di base che può fornire limmagine del risultato dal sistema di mascheramento delle immagini.
type: docs
weight: 10540
url: /it/net/aspose.imaging.masking.result/maskingresult/
---
## MaskingResult class

Classe astratta di base che può fornire l'immagine del risultato dal sistema di mascheramento delle immagini.

```csharp
public abstract class MaskingResult : DisposableObject, IEnumerable<IMaskingLayer>
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Ottiene un valore che indica se questa istanza è stata eliminata. |
| [Item](../../aspose.imaging.masking.result/maskingresult/item) { get; } | Ottiene il[`IMaskingLayer`](../imaskinglayer) all'indice specificato. |
| abstract [Layers](../../aspose.imaging.masking.result/maskingresult/layers) { get; } | Ottiene i livelli. |
| [Length](../../aspose.imaging.masking.result/maskingresult/length) { get; } | Ottiene la lunghezza. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Elimina l'istanza corrente. |
| [GetEnumerator](../../aspose.imaging.masking.result/maskingresult/getenumerator)() | Ottiene l'enumeratore. |

## Campi

| Nome | Descrizione |
| --- | --- |
| readonly [MaskingOptions](../../aspose.imaging.masking.result/maskingresult/maskingoptions) | Le opzioni di mascheramento |

### Esempi

Questo esempio mostra come scomporre un'immagine raster in più immagini utilizzando il mascheramento dell'immagine e l'algoritmo di segmentazione K-means. Il mascheramento dell'immagine è una tecnica di elaborazione delle immagini che viene utilizzata per dividere lo sfondo dagli oggetti dell'immagine in primo piano.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.RasterImage image = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Load(dir + "Blue hills.png"))
{
    Aspose.Imaging.Masking.Options.AutoMaskingArgs args = new Aspose.Imaging.Masking.Options.AutoMaskingArgs();

    // Imposta il numero di cluster (oggetti separati). Il valore predefinito è 2, l'oggetto in primo piano e lo sfondo.
    args.NumberOfObjects = 3;

    // Imposta il numero massimo di iterazioni.
    args.MaxIterationNumber = 50;

    // Imposta la precisione del metodo di segmentazione (opzionale)
    args.Precision = 1;
        
    // Ogni cluster (segmento) verrà archiviato in un file PNG separato.
    Aspose.Imaging.ImageOptions.PngOptions exportOptions = new Aspose.Imaging.ImageOptions.PngOptions();
    exportOptions.ColorType = Aspose.Imaging.FileFormats.Png.PngColorType.TruecolorWithAlpha;
    exportOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream());

    Aspose.Imaging.Masking.Options.MaskingOptions maskingOptions = new Aspose.Imaging.Masking.Options.MaskingOptions();

    // Usa il clustering K-means.
    // Il clustering K-means consente di dividere l'immagine in diversi cluster (segmenti) indipendenti.
    maskingOptions.Method = Masking.Options.SegmentationMethod.KMeans;
    maskingOptions.Decompose = true;
    maskingOptions.Args = args;
        
    // Il colore dello sfondo sarà arancione.
    maskingOptions.BackgroundReplacementColor = Aspose.Imaging.Color.Orange;
    maskingOptions.ExportOptions = exportOptions;

    // Crea un'istanza della classe ImageMasking.
    Aspose.Imaging.Masking.ImageMasking masking = new Aspose.Imaging.Masking.ImageMasking(image);

    // Dividi l'immagine di origine in diversi cluster (segmenti).
    using (Aspose.Imaging.Masking.Result.MaskingResult maskingResult = masking.Decompose(maskingOptions))
    {
        // Ottieni immagini dal risultato della mascheratura e salvale in PNG.
        for (int i = 0; i < maskingResult.Length; i++)
        {
            string outputFileName = string.Format("Blue hills.Segment{0}.png", maskingResult[i].ObjectNumber);
            using (Aspose.Imaging.Image resultImage = maskingResult[i].GetImage())
            {
                resultImage.Save(dir + outputFileName);
            }
        }
    }
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

Questo esempio mostra come scomporre un'immagine raster in più immagini utilizzando la mascheratura dell'immagine e una maschera manuale. Il mascheramento dell'immagine è una tecnica di elaborazione delle immagini che viene utilizzata per dividere lo sfondo dagli oggetti dell'immagine in primo piano.

```csharp
[C#]

string dir = "c:\\temp\\";

// Definisci una maschera manuale.
Aspose.Imaging.GraphicsPath manualMask = new Aspose.Imaging.GraphicsPath();
Aspose.Imaging.Figure figure = new Aspose.Imaging.Figure();
figure.AddShape(new Aspose.Imaging.Shapes.EllipseShape(new RectangleF(50, 50, 40, 40)));
figure.AddShape(new Aspose.Imaging.Shapes.RectangleShape(new RectangleF(10, 20, 50, 30)));
manualMask.AddFigure(figure);

// Ogni cluster (segmento) verrà archiviato in un file PNG separato.
Aspose.Imaging.ImageOptions.PngOptions exportOptions = new Aspose.Imaging.ImageOptions.PngOptions();
exportOptions.ColorType = Aspose.Imaging.FileFormats.Png.PngColorType.TruecolorWithAlpha;
exportOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream());

// Imposta la maschera manuale.
Aspose.Imaging.Masking.Options.ManualMaskingArgs args = new Aspose.Imaging.Masking.Options.ManualMaskingArgs();
args.Mask = manualMask;

using (RasterImage image = (RasterImage)Image.Load(dir + "Blue hills.png"))
{
    Aspose.Imaging.Masking.Options.MaskingOptions maskingOptions = new Aspose.Imaging.Masking.Options.MaskingOptions();

    // Usa l'algoritmo di clustering manuale.
    maskingOptions.Method = Masking.Options.SegmentationMethod.Manual;

    // Tutte le forme che compongono una maschera verranno combinate in una sola. 
    maskingOptions.Decompose = false;
    maskingOptions.Args = args;

    // Il colore dello sfondo sarà arancione.
    maskingOptions.BackgroundReplacementColor = Aspose.Imaging.Color.Orange;
    maskingOptions.ExportOptions = exportOptions;

    // L'area dell'immagine sorgente a cui verrà applicata la mascheratura.
    maskingOptions.MaskingArea = new Rectangle(50, 50, 120, 120);

    // Crea un'istanza della classe ImageMasking.
    Aspose.Imaging.Masking.ImageMasking masking = new Aspose.Imaging.Masking.ImageMasking(image);

    // Dividi l'immagine di origine in diversi cluster (segmenti).
    using (Aspose.Imaging.Masking.Result.MaskingResult maskingResult = masking.Decompose(maskingOptions))
    {
        // Ottieni immagini dal risultato della mascheratura e salvale in PNG.
        for (int i = 0; i < maskingResult.Length; i++)
        {
            string outputFileName = string.Format("Blue hills.Segment{0}.png", maskingResult[i].ObjectNumber);
            using (Aspose.Imaging.Image resultImage = maskingResult[i].GetImage())
            {
                resultImage.Save(dir + outputFileName);
            }
        }
    }
}
```

Questo esempio mostra come specificare suggerimenti per l'algoritmo di mascheramento delle immagini per migliorare la precisione del metodo di segmentazione (clustering). Il mascheramento dell'immagine è una tecnica di elaborazione delle immagini che viene utilizzata per dividere lo sfondo dagli oggetti dell'immagine in primo piano.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.RasterImage image = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Load(dir + "Gorilla.bmp"))
{
    Aspose.Imaging.Masking.Options.AutoMaskingArgs args = new Aspose.Imaging.Masking.Options.AutoMaskingArgs();

    // Suggerimento n. 1.
    // Analizza visivamente l'immagine e imposta l'area di interesse. Il risultato della segmentazione includerà solo gli oggetti che saranno completamente posizionati all'interno di quest'area.
    args.ObjectsRectangles = new Rectangle[]
    {
        new Rectangle(86, 6, 270, 364),
    };

    // Suggerimento n. 2.
    // Analizza visivamente l'immagine e imposta i punti che appartengono a oggetti separati.
    args.ObjectsPoints = new Point[][]
    {
        new Point[] { new Point(103, 326) },
        new Point[] { new Point(280, 43) },
        new Point[] { new Point(319, 86) },
    };

    // Ogni cluster (segmento) verrà archiviato in un file PNG separato.
    Aspose.Imaging.ImageOptions.PngOptions exportOptions = new Aspose.Imaging.ImageOptions.PngOptions();
    exportOptions.ColorType = Aspose.Imaging.FileFormats.Png.PngColorType.TruecolorWithAlpha;
    exportOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream());

    Aspose.Imaging.Masking.Options.MaskingOptions maskingOptions = new Aspose.Imaging.Masking.Options.MaskingOptions();
        
    // Usa il clustering di GraphCut.
    maskingOptions.Method = Masking.Options.SegmentationMethod.GraphCut;
    maskingOptions.Decompose = false;
    maskingOptions.Args = args;

    // Il colore dello sfondo sarà arancione.
    maskingOptions.BackgroundReplacementColor = Aspose.Imaging.Color.Orange;
    maskingOptions.ExportOptions = exportOptions;

    // Crea un'istanza della classe ImageMasking.
    Aspose.Imaging.Masking.ImageMasking masking = new Aspose.Imaging.Masking.ImageMasking(image);

    // Dividi l'immagine di origine in diversi cluster (segmenti).
    using (Aspose.Imaging.Masking.Result.MaskingResult maskingResult = masking.Decompose(maskingOptions))
    {
        // Ottieni immagini dal risultato della mascheratura e salvale in PNG.
        for (int i = 0; i < maskingResult.Length; i++)
        {
            string outputFileName = string.Format("Gorilla.Segment{0}.png", maskingResult[i].ObjectNumber);
            using (Aspose.Imaging.Image resultImage = maskingResult[i].GetImage())
            {
                resultImage.Save(dir + outputFileName);
            }
        }
    }
}
```

Salvataggio della sessione di mascheramento in un file per sessioni lunghe, nonché per la possibilità di riprendere la sessione in un altro ambiente.

```csharp
[C#]

string dir = "c:\\temp\\";
string sessionBackupFile = dir + "session.bak";

// Opzioni di esportazione mascheratura
Aspose.Imaging.ImageOptions.PngOptions exportOptions = new Aspose.Imaging.ImageOptions.PngOptions();
exportOptions.ColorType = Aspose.Imaging.FileFormats.Png.PngColorType.TruecolorWithAlpha;
exportOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream());

Aspose.Imaging.Masking.Options.MaskingOptions maskingOptions = new Aspose.Imaging.Masking.Options.MaskingOptions();
    
// Usa il clustering di GraphCut.
maskingOptions.Method = Masking.Options.SegmentationMethod.GraphCut;
maskingOptions.Decompose = false;
maskingOptions.Args = new Aspose.Imaging.Masking.Options.AutoMaskingArgs();

// Il colore dello sfondo sarà arancione.
maskingOptions.BackgroundReplacementColor = Aspose.Imaging.Color.Orange;
maskingOptions.ExportOptions = exportOptions;

// Avvio di una sessione per la prima volta e salvataggio in un file
using (Aspose.Imaging.RasterImage image = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Load(dir + "Gorilla.bmp"))
{
    // Crea un'istanza della classe ImageMasking.
    Aspose.Imaging.Masking.ImageMasking masking = new Aspose.Imaging.Masking.ImageMasking(image);

    using (Aspose.Imaging.Masking.IMaskingSession session = masking.CreateSession(maskingOptions))
    {
        using (Aspose.Imaging.Masking.Result.MaskingResult maskingResult = session.Decompose())
        {
            using (Aspose.Imaging.RasterImage segmentImage = maskingResult[1].GetImage())
            {
                segmentImage.Save(dir + "step1.png");
            }
        }

        session.Save(sessionBackupFile);
    }
}

// Riprendere una sessione di mascheramento da un file
using (Aspose.Imaging.RasterImage image = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Load(dir + "Gorilla.bmp"))
{
    // Crea un'istanza della classe ImageMasking.
    Aspose.Imaging.Masking.ImageMasking masking = new Aspose.Imaging.Masking.ImageMasking(image);

    using (Aspose.Imaging.Masking.IMaskingSession session = masking.LoadSession(sessionBackupFile))
    {
        Aspose.Imaging.Masking.Options.AutoMaskingArgs args = new Aspose.Imaging.Masking.Options.AutoMaskingArgs();

        // Analizza visivamente l'immagine e imposta i punti che appartengono a oggetti separati.
        args.ObjectsPoints = new Point[][]
                                     {
                                         new Point[]
                                             {
                                                 new Point(0, 0), new Point(0, 1), new Point(1, 0),
                                                 new Point(1, 1), new Point(2, 0), new Point(2, 1),
                                                 new Point(3, 0), new Point(3, 1)
                                             },
                                     };
        using (Aspose.Imaging.Masking.Result.MaskingResult maskingResult = session.ImproveDecomposition(args))
        {
            // Trasferimento esplicito delle opzioni di esportazione, poiché non è serializzabile
            maskingResult.MaskingOptions.ExportOptions = exportOptions;

            using (Aspose.Imaging.RasterImage segmentImage = maskingResult[1].GetImage())
            {
                segmentImage.Save(dir + "step2.png");
            }
        }
    }
}
```

### Guarda anche

* class [DisposableObject](../../aspose.imaging/disposableobject)
* interface [IMaskingLayer](../imaskinglayer)
* spazio dei nomi [Aspose.Imaging.Masking.Result](../../aspose.imaging.masking.result)
* assemblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
