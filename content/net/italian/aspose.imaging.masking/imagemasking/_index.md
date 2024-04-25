---
title: ImageMasking
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Fornisce operazioni di mascheramento dellimmagine
type: docs
weight: 10430
url: /it/aspose.imaging.masking/imagemasking/
---
## ImageMasking class

Fornisce operazioni di mascheramento dell'immagine

```csharp
public class ImageMasking
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [ImageMasking](imagemasking)(RasterImage) | Inizializza una nuova istanza di[`ImageMasking`](../imagemasking) classe. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [CreateSession](../../aspose.imaging.masking/imagemasking/createsession)(MaskingOptions) | Crea la sessione di mascheratura che può eseguire operazioni di scomposizione di riaddestramento. |
| [Decompose](../../aspose.imaging.masking/imagemasking/decompose)(MaskingOptions) | Esegue l'operazione di scomposizione utilizzando le opzioni di mascheramento specificate |
| [DecomposeAsync](../../aspose.imaging.masking/imagemasking/decomposeasync)(MaskingOptions) | Crea l'attività di scomposizione asincrona utilizzando le opzioni di mascheramento specificate. |
| [LoadSession](../../aspose.imaging.masking/imagemasking/loadsession#loadsession)(Stream) | Carica la sessione dal flusso specificato. |
| [LoadSession](../../aspose.imaging.masking/imagemasking/loadsession#loadsession_1)(string) | Carica la sessione dal file specificato. |
| static [ApplyMask](../../aspose.imaging.masking/imagemasking/applymask)(RasterImage, RasterImage, MaskingOptions) | Applica la maschera all'immagine di origine specificata. |

### Esempi

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

* spazio dei nomi [Aspose.Imaging.Masking](../../aspose.imaging.masking)
* assemblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
