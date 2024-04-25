---
title: Jpeg2000Options
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Le opzioni del formato del file JPEG2000.
type: docs
weight: 10020
url: /it/aspose.imaging.imageoptions/jpeg2000options/
---
## Jpeg2000Options class

Le opzioni del formato del file JPEG2000.

```csharp
public class Jpeg2000Options : ImageOptionsBase
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [Jpeg2000Options](jpeg2000options#constructor)() | Inizializza una nuova istanza di[`Jpeg2000Options`](../jpeg2000options) classe. |
| [Jpeg2000Options](jpeg2000options#constructor_1)(Jpeg2000Options) | Inizializza una nuova istanza di[`Jpeg2000Options`](../jpeg2000options) classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [BufferSizeHint](../../aspose.imaging/imageoptionsbase/buffersizehint) { get; set; } | Ottiene o imposta l'hint per la dimensione del buffer che è la dimensione massima consentita per tutti i buffer interni. |
| [Codec](../../aspose.imaging.imageoptions/jpeg2000options/codec) { get; set; } | Ottiene o imposta il codec JPEG2000 |
| [Comments](../../aspose.imaging.imageoptions/jpeg2000options/comments) { get; set; } | Ottiene o imposta i marcatori di commento JPEG. |
| [CompressionRatios](../../aspose.imaging.imageoptions/jpeg2000options/compressionratios) { get; set; } | Ottiene o imposta il rapporto di compressione dell'array. Rapporti di compressione diversi per livelli successivi. Il tasso specificato per ciascun livello di qualità è il fattore di compressione desiderato . Rapporti decrescenti richiesti. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Ottiene un valore che indica se questa istanza è stata eliminata. |
| [FullFrame](../../aspose.imaging/imageoptionsbase/fullframe) { get; set; } | Ottiene o imposta un valore che indica se [fotogramma intero]. |
| [Irreversible](../../aspose.imaging.imageoptions/jpeg2000options/irreversible) { get; set; } | Ottiene o imposta un valore che indica se utilizzare la compressione DWT 9-7 irreversibile (true) o utilizzare la compressione DWT 5-3 senza perdita di dati (predefinita). |
| [MultiPageOptions](../../aspose.imaging/imageoptionsbase/multipageoptions) { get; set; } | Le opzioni multipagina |
| virtual [Palette](../../aspose.imaging/imageoptionsbase/palette) { get; set; } | Ottiene o imposta la tavolozza dei colori. |
| [ProgressEventHandler](../../aspose.imaging/imageoptionsbase/progresseventhandler) { get; set; } | Ottiene o imposta il gestore dell'evento di avanzamento. |
| virtual [ResolutionSettings](../../aspose.imaging/imageoptionsbase/resolutionsettings) { get; set; } | Ottiene o imposta le impostazioni di risoluzione. |
| [Source](../../aspose.imaging/imageoptionsbase/source) { get; set; } | Ottiene o imposta l'origine in cui creare l'immagine. |
| [VectorRasterizationOptions](../../aspose.imaging/imageoptionsbase/vectorrasterizationoptions) { get; set; } | Ottiene o imposta le opzioni di rasterizzazione del vettore. |
| override [XmpData](../../aspose.imaging.imageoptions/jpeg2000options/xmpdata) { get; set; } | Ottiene o imposta il contenitore di metadati XMP. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| virtual [Clone](../../aspose.imaging/imageoptionsbase/clone)() | Clona questa istanza. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Elimina l'istanza corrente. |

### Esempi

L'esempio seguente mostra come convertire un'immagine vettoriale multipagina in formato JPEG 2000 in generale senza fare riferimento a un particolare tipo di immagine.

```csharp
[C#]

string dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
string inputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr");
string outputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr.j2k");

Aspose.Imaging.ImageOptionsBase exportOptions = new Aspose.Imaging.ImageOptions.Jpeg2000Options();

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFilePath))
{
    exportOptions.MultiPageOptions = null;

    // Esporta solo le prime due pagine. In effetti, solo una pagina verrà rasterizzata perché JPEG 2000 non è un formato multipagina.
    Aspose.Imaging.IMultipageImage multipageImage = image as Aspose.Imaging.IMultipageImage;
    if (multipageImage != null && (multipageImage.Pages != null && multipageImage.PageCount > 2))
    {
        exportOptions.MultiPageOptions = new Aspose.Imaging.ImageOptions.MultiPageOptions(new Aspose.Imaging.IntRange(0, 2));
    }

    if (image is Aspose.Imaging.VectorImage)
    {
        exportOptions.VectorRasterizationOptions = (Aspose.Imaging.ImageOptions.VectorRasterizationOptions)image.GetDefaultOptions(new object[] { Aspose.Imaging.Color.White, image.Width, image.Height });
        exportOptions.VectorRasterizationOptions.TextRenderingHint = Aspose.Imaging.TextRenderingHint.SingleBitPerPixel;
        exportOptions.VectorRasterizationOptions.SmoothingMode = Aspose.Imaging.SmoothingMode.None;
    }

    image.Save(outputFilePath, exportOptions);
}
```

### Guarda anche

* class [ImageOptionsBase](../../aspose.imaging/imageoptionsbase)
* spazio dei nomi [Aspose.Imaging.ImageOptions](../../aspose.imaging.imageoptions)
* assemblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
