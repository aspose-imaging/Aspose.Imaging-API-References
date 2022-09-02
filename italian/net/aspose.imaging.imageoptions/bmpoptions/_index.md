---
title: BmpOptions
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Opzioni di creazione del formato file bmp.
type: docs
weight: 9910
url: /it/net/aspose.imaging.imageoptions/bmpoptions/
---
## BmpOptions class

Opzioni di creazione del formato file bmp.

```csharp
public class BmpOptions : ImageOptionsBase
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [BmpOptions](bmpoptions#constructor)() | Inizializza una nuova istanza di[`BmpOptions`](../bmpoptions) classe. |
| [BmpOptions](bmpoptions#constructor_1)(BmpOptions) | Inizializza una nuova istanza di[`BmpOptions`](../bmpoptions) classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [BitsPerPixel](../../aspose.imaging.imageoptions/bmpoptions/bitsperpixel) { get; set; } | Ottiene o imposta il conteggio dei bit dell'immagine per pixel. |
| [BufferSizeHint](../../aspose.imaging/imageoptionsbase/buffersizehint) { get; set; } | Ottiene o imposta l'hint per la dimensione del buffer che è la dimensione massima consentita per tutti i buffer interni. |
| [Compression](../../aspose.imaging.imageoptions/bmpoptions/compression) { get; set; } | Ottiene o imposta la compressione. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Ottiene un valore che indica se questa istanza è stata eliminata. |
| [FullFrame](../../aspose.imaging/imageoptionsbase/fullframe) { get; set; } | Ottiene o imposta un valore che indica se [fotogramma intero]. |
| [MultiPageOptions](../../aspose.imaging/imageoptionsbase/multipageoptions) { get; set; } | Le opzioni multipagina |
| virtual [Palette](../../aspose.imaging/imageoptionsbase/palette) { get; set; } | Ottiene o imposta la tavolozza dei colori. |
| [ProgressEventHandler](../../aspose.imaging/imageoptionsbase/progresseventhandler) { get; set; } | Ottiene o imposta il gestore dell'evento di avanzamento. |
| virtual [ResolutionSettings](../../aspose.imaging/imageoptionsbase/resolutionsettings) { get; set; } | Ottiene o imposta le impostazioni di risoluzione. |
| [Source](../../aspose.imaging/imageoptionsbase/source) { get; set; } | Ottiene o imposta l'origine in cui creare l'immagine. |
| [VectorRasterizationOptions](../../aspose.imaging/imageoptionsbase/vectorrasterizationoptions) { get; set; } | Ottiene o imposta le opzioni di rasterizzazione del vettore. |
| virtual [XmpData](../../aspose.imaging/imageoptionsbase/xmpdata) { get; set; } | Ottiene o imposta il contenitore di metadati XMP. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| virtual [Clone](../../aspose.imaging/imageoptionsbase/clone)() | Clona questa istanza. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Elimina l'istanza corrente. |

### Esempi

Questo esempio crea un nuovo file immagine in una posizione del disco come specificato dalla proprietà Source dell'istanza BmpOptions. Diverse proprietà per l'istanza BmpOptions vengono impostate prima di creare l'immagine effettiva. Soprattutto la proprietà Source, che in questo caso si riferisce alla posizione effettiva del disco.

```csharp
[C#]

//Crea un'istanza di BmpOptions e imposta le sue varie proprietà
Aspose.Imaging.ImageOptions.BmpOptions bmpOptions = new Aspose.Imaging.ImageOptions.BmpOptions();
bmpOptions.BitsPerPixel = 24;

//Crea un'istanza di FileCreateSource e assegnala come origine per l'istanza di BmpOptions
//Il secondo parametro booleano determina se il file da creare è Temporale o meno
bmpOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(@"C:\temp\output.bmp", false);

//Crea un'istanza di Image e inizializzala con un'istanza di BmpOptions chiamando il metodo Create
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(bmpOptions, 500, 500))
{
    //eseguo un po' di elaborazione delle immagini

    // salva tutte le modifiche
    image.Save();
}
```

Questo esempio mostra l'uso di classi diverse da SaveOptions Namespace per scopi di esportazione. Un'immagine di tipo Gif viene caricata in un'istanza di Image e quindi esportata in diversi formati.

```csharp
[C#]

string dir = "c:\\temp\\";

//Carica un'immagine esistente (di tipo Gif) in un'istanza della classe Image
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    //Esporta in formato file BMP utilizzando le opzioni predefinite
    image.Save(dir + "output.bmp", new Aspose.Imaging.ImageOptions.BmpOptions());

    //Esporta in formato file JPEG utilizzando le opzioni predefinite
    image.Save(dir + "output.jpg", new Aspose.Imaging.ImageOptions.JpegOptions());

    //Esporta in formato file PNG utilizzando le opzioni predefinite
    image.Save(dir + "output.png", new Aspose.Imaging.ImageOptions.PngOptions());

    //Esporta in formato file TIFF utilizzando le opzioni predefinite
    image.Save(dir + "output.tif", new Aspose.Imaging.ImageOptions.TiffOptions(Aspose.Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default));
}
```

L'esempio seguente mostra come convertire un'immagine vettoriale multipagina in formato BMP in modo generale senza fare riferimento a un particolare tipo di immagine.

```csharp
[C#]

string dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
string inputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr");
string outputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr.bmp");

Aspose.Imaging.ImageOptionsBase exportOptions = new Aspose.Imaging.ImageOptions.BmpOptions();

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFilePath))
{
    exportOptions.MultiPageOptions = null;

    // Esporta solo le prime due pagine. In effetti, verrà rasterizzata solo una pagina perché BMP non è un formato multipagina.
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
