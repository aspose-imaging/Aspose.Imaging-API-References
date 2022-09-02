---
title: PsdOptions
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Il formato del file psd crea opzioni.
type: docs
weight: 10140
url: /it/net/aspose.imaging.imageoptions/psdoptions/
---
## PsdOptions class

Il formato del file psd crea opzioni.

```csharp
public class PsdOptions : ImageOptionsBase
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [PsdOptions](psdoptions#constructor)() | Inizializza una nuova istanza di[`PsdOptions`](../psdoptions) classe. |
| [PsdOptions](psdoptions#constructor_1)(PsdOptions) | Inizializza una nuova istanza di[`PsdOptions`](../psdoptions) classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [BufferSizeHint](../../aspose.imaging/imageoptionsbase/buffersizehint) { get; set; } | Ottiene o imposta l'hint per la dimensione del buffer che è la dimensione massima consentita per tutti i buffer interni. |
| [ChannelBitsCount](../../aspose.imaging.imageoptions/psdoptions/channelbitscount) { get; set; } | Ottiene o imposta il conteggio dei bit per canale colore. |
| [ChannelsCount](../../aspose.imaging.imageoptions/psdoptions/channelscount) { get; set; } | Ottiene o imposta il conteggio dei canali colore. |
| [ColorMode](../../aspose.imaging.imageoptions/psdoptions/colormode) { get; set; } | Ottiene o imposta la modalità colore psd. |
| [CompressionMethod](../../aspose.imaging.imageoptions/psdoptions/compressionmethod) { get; set; } | Ottiene o imposta il metodo di compressione psd. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Ottiene un valore che indica se questa istanza è stata eliminata. |
| [FullFrame](../../aspose.imaging/imageoptionsbase/fullframe) { get; set; } | Ottiene o imposta un valore che indica se [fotogramma intero]. |
| [MultiPageOptions](../../aspose.imaging/imageoptionsbase/multipageoptions) { get; set; } | Le opzioni multipagina |
| virtual [Palette](../../aspose.imaging/imageoptionsbase/palette) { get; set; } | Ottiene o imposta la tavolozza dei colori. |
| [ProgressEventHandler](../../aspose.imaging/imageoptionsbase/progresseventhandler) { get; set; } | Ottiene o imposta il gestore dell'evento di avanzamento. |
| [PsdVersion](../../aspose.imaging.imageoptions/psdoptions/psdversion) { get; set; } | Ottiene o imposta la versione del formato del file. Può essere PSD o PSB. |
| [RefreshImagePreviewData](../../aspose.imaging.imageoptions/psdoptions/refreshimagepreviewdata) { get; set; } | Ottiene o imposta un valore che indica se [aggiorna i dati di anteprima dell'immagine] - opzione utilizzata per massimizzare la compatibilità con altri visualizzatori di immagini PSD. Tieni presente che il disegno dei livelli di testo sul layout finale non è supportato per la piattaforma Compact Framework |
| [RemoveGlobalTextEngineResource](../../aspose.imaging.imageoptions/psdoptions/removeglobaltextengineresource) { get; set; } | Ottiene o imposta un valore che indica se - Rimuovi la risorsa del motore di testo globale - Utilizzato per alcuni file PSD con livelli di testo, nel solo caso in cui non possono essere aperti in Adobe Photoshop dopo l'elaborazione (principalmente per i livelli di testo dei caratteri assenti correlati). Dopo aver utilizzato questa opzione, l'utente deve aprire il prossimo file di Photoshop: Menu "Testo" -&gt; "Elabora caratteri assenti". Dopo quell'operazione tutto il testo apparirà di nuovo. Tieni presente che questa operazione potrebbe causare alcune modifiche finali al layout. |
| virtual [ResolutionSettings](../../aspose.imaging/imageoptionsbase/resolutionsettings) { get; set; } | Ottiene o imposta le impostazioni di risoluzione. |
| [Source](../../aspose.imaging/imageoptionsbase/source) { get; set; } | Ottiene o imposta l'origine in cui creare l'immagine. |
| [VectorizationOptions](../../aspose.imaging.imageoptions/psdoptions/vectorizationoptions) { get; set; } | Ottiene o imposta le opzioni di vettorizzazione PSD. |
| [VectorRasterizationOptions](../../aspose.imaging/imageoptionsbase/vectorrasterizationoptions) { get; set; } | Ottiene o imposta le opzioni di rasterizzazione del vettore. |
| [Version](../../aspose.imaging.imageoptions/psdoptions/version) { get; set; } | Ottiene o imposta la versione del file psd. |
| override [XmpData](../../aspose.imaging.imageoptions/psdoptions/xmpdata) { get; set; } | Ottieni o imposta il contenitore di dati XMP |

## Metodi

| Nome | Descrizione |
| --- | --- |
| virtual [Clone](../../aspose.imaging/imageoptionsbase/clone)() | Clona questa istanza. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Elimina l'istanza corrente. |

### Esempi

Questo esempio mostra l'uso di Aspsoe.Imaging per l'API .Net per convertire le immagini in formato PSD. Per raggiungere questo obiettivo, questo esempio carica un'immagine esistente e poi la salva di nuovo in formato PSD.

```csharp
[C#]

string dir = "c:\\temp\\";

//Crea un'istanza della classe image e la inizializza con un file esistente tramite il percorso del file
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    //Crea un'istanza della classe PsdOptions
    Aspose.Imaging.ImageOptions.PsdOptions psdOptions = new Aspose.Imaging.ImageOptions.PsdOptions();

    //Imposta CompressionMethod come RLE
    //Nota: un altro CompressionMethod supportato è CompressionMethod.RAW [Nessuna compressione]
    psdOptions.CompressionMethod = Aspose.Imaging.FileFormats.Psd.CompressionMethod.RLE;

    //Imposta ColorMode su Scala di grigi
    //Nota: altri ColorModes supportati sono ColorModes.Bitmap e ColorModes.RGB
    psdOptions.ColorMode = Aspose.Imaging.FileFormats.Psd.ColorModes.Grayscale;

    //Salva l'immagine nella posizione del disco con le impostazioni PsdOptions fornite
    image.Save(dir + "output.psd", psdOptions);
}
```

L'esempio seguente mostra come convertire un'immagine vettoriale multipagina in formato PSD in modo generale senza fare riferimento a un particolare tipo di immagine.

```csharp
[C#]

string dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
string inputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr");
string outputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr.psd");

Aspose.Imaging.ImageOptionsBase exportOptions = new Aspose.Imaging.ImageOptions.PsdOptions();

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFilePath))
{
    exportOptions.MultiPageOptions = null;

    // Esporta solo le prime due pagine. Queste pagine verranno presentate come livelli nel PSD di output.
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
