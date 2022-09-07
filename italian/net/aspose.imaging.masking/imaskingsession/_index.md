---
title: IMaskingSession
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: La sessione di mascheramento
type: docs
weight: 10420
url: /it/net/aspose.imaging.masking/imaskingsession/
---
## IMaskingSession interface

La sessione di mascheramento

```csharp
public interface IMaskingSession : IDisposable
```

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Decompose](../../aspose.imaging.masking/imaskingsession/decompose)() | Esegue la prima operazione di scomposizione approssimativa |
| [DecomposeAsync](../../aspose.imaging.masking/imaskingsession/decomposeasync)() | Crea l'attività asincrona che può eseguire la prima operazione di scomposizione approssimativa |
| [ImproveDecomposition](../../aspose.imaging.masking/imaskingsession/improvedecomposition)(IMaskingArgs) | Esegue la riqualificazione dell'operazione di scomposizione |
| [ImproveDecompositionAsync](../../aspose.imaging.masking/imaskingsession/improvedecompositionasync)(IMaskingArgs) | Crea l'attività asincrona che può eseguire l'operazione di scomposizione della riqualificazione |
| [Save](../../aspose.imaging.masking/imaskingsession/save#save)(Stream) | Salva lo stato della sessione nel flusso specificato. |
| [Save](../../aspose.imaging.masking/imaskingsession/save#save_1)(string) | Salva lo stato della sessione nel file specificato. |

### Esempi

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
