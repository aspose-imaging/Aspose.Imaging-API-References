---
title: GifOptions
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Opzioni di creazione del formato file gif.
type: docs
weight: 10000
url: /it/aspose.imaging.imageoptions/gifoptions/
---
## GifOptions class

Opzioni di creazione del formato file gif.

```csharp
public class GifOptions : ImageOptionsBase
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [GifOptions](gifoptions#constructor)() | Inizializza una nuova istanza di[`GifOptions`](../gifoptions) classe. |
| [GifOptions](gifoptions#constructor_1)(GifOptions) | Inizializza una nuova istanza di[`GifOptions`](../gifoptions) classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [BackgroundColor](../../aspose.imaging.imageoptions/gifoptions/backgroundcolor) { get; set; } | Ottiene o imposta il colore di sfondo. |
| [BackgroundColorIndex](../../aspose.imaging.imageoptions/gifoptions/backgroundcolorindex) { get; set; } | Ottiene o imposta l'indice del colore di sfondo GIF. |
| [BufferSizeHint](../../aspose.imaging/imageoptionsbase/buffersizehint) { get; set; } | Ottiene o imposta l'hint per la dimensione del buffer che è la dimensione massima consentita per tutti i buffer interni. |
| [ColorResolution](../../aspose.imaging.imageoptions/gifoptions/colorresolution) { get; set; } | Ottiene o imposta la risoluzione del colore GIF. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Ottiene un valore che indica se questa istanza è stata eliminata. |
| [DoPaletteCorrection](../../aspose.imaging.imageoptions/gifoptions/dopalettecorrection) { get; set; } | Ottiene o imposta un valore che indica se è stata applicata la correzione della tavolozza. |
| [FullFrame](../../aspose.imaging/imageoptionsbase/fullframe) { get; set; } | Ottiene o imposta un valore che indica se [fotogramma intero]. |
| [HasTrailer](../../aspose.imaging.imageoptions/gifoptions/hastrailer) { get; set; } | Ottiene o imposta un valore che indica se GIF ha trailer. |
| [HasTransparentColor](../../aspose.imaging.imageoptions/gifoptions/hastransparentcolor) { get; set; } | Ottiene o imposta un valore che indica se l'immagine GIF ha un colore trasparente. |
| [Interlaced](../../aspose.imaging.imageoptions/gifoptions/interlaced) { get; set; } | Vero se l'immagine deve essere interlacciata. |
| [IsPaletteSorted](../../aspose.imaging.imageoptions/gifoptions/ispalettesorted) { get; set; } | Ottiene o imposta un valore che indica se le voci della tavolozza sono ordinate. |
| [LoopsCount](../../aspose.imaging.imageoptions/gifoptions/loopscount) { get; set; } | Ottiene o imposta il conteggio dei loop (predefinito 1 loop) |
| [MaxDiff](../../aspose.imaging.imageoptions/gifoptions/maxdiff) { get; set; } | Ottiene o imposta la differenza di pixel massima consentita. Se maggiore di zero, verrà utilizzata la compressione con perdita. Il valore consigliato per una compressione con perdita ottimale è 80. 30 è una compressione molto leggera, 200 è pesante. Funziona meglio quando viene introdotta solo una piccola perdita e a causa della limitazione dell'algoritmo di compressione livelli di perdita molto elevati non daranno molto guadagno. L'intervallo di valori consentiti è [0, 1000]. |
| [MultiPageOptions](../../aspose.imaging/imageoptionsbase/multipageoptions) { get; set; } | Le opzioni multipagina |
| virtual [Palette](../../aspose.imaging/imageoptionsbase/palette) { get; set; } | Ottiene o imposta la tavolozza dei colori. |
| [PixelAspectRatio](../../aspose.imaging.imageoptions/gifoptions/pixelaspectratio) { get; set; } | Ottiene o imposta le proporzioni dei pixel GIF. |
| [ProgressEventHandler](../../aspose.imaging/imageoptionsbase/progresseventhandler) { get; set; } | Ottiene o imposta il gestore dell'evento di avanzamento. |
| virtual [ResolutionSettings](../../aspose.imaging/imageoptionsbase/resolutionsettings) { get; set; } | Ottiene o imposta le impostazioni di risoluzione. |
| [Source](../../aspose.imaging/imageoptionsbase/source) { get; set; } | Ottiene o imposta l'origine in cui creare l'immagine. |
| [VectorRasterizationOptions](../../aspose.imaging/imageoptionsbase/vectorrasterizationoptions) { get; set; } | Ottiene o imposta le opzioni di rasterizzazione del vettore. |
| override [XmpData](../../aspose.imaging.imageoptions/gifoptions/xmpdata) { get; set; } | Ottiene o imposta il contenitore di metadati XMP. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| virtual [Clone](../../aspose.imaging/imageoptionsbase/clone)() | Clona questa istanza. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Elimina l'istanza corrente. |

### Esempi

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

L'esempio seguente mostra come convertire un'immagine vettoriale multipagina in formato GIF in generale senza fare riferimento a un particolare tipo di immagine.

```csharp
[C#]

string dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
string inputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr");
string outputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr.gif");

Aspose.Imaging.ImageOptionsBase exportOptions = new Aspose.Imaging.ImageOptions.GifOptions();

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFilePath))
{
    exportOptions.MultiPageOptions = null;

    // Esporta solo le prime due pagine. Queste pagine verranno presentate come frame animati nella GIF di output.
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

Questo esempio mostra come caricare le informazioni sui pixel in una matrice di tipo colore, manipolare la matrice e reimpostarla sull'immagine. Per eseguire queste operazioni, questo esempio crea un nuovo file immagine (in formato GIF) utilizzando l'oggetto MemoryStream.

```csharp
[C#]

//Crea un'istanza di MemoryStream
using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
{
    //Crea un'istanza di GifOptions e imposta le sue varie proprietà inclusa la proprietà Source
    Aspose.Imaging.ImageOptions.GifOptions gifOptions = new Aspose.Imaging.ImageOptions.GifOptions();
    gifOptions.Source = new Aspose.Imaging.Sources.StreamSource(stream);

    //Crea un'istanza di Image
    using (Aspose.Imaging.RasterImage image = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Create(gifOptions, 500, 500))
    {
        //Ottieni i pixel dell'immagine specificando l'area come limite dell'immagine
        Aspose.Imaging.Color[] pixels = image.LoadPixels(image.Bounds);

        //Cicla sull'array e imposta il colore del pixel indicizzato alternativo
        for (int index = 0; index < pixels.Length; index++)
        {
            if (index % 2 == 0)
            {
                //Imposta il colore del pixel indicizzato su giallo
                pixels[index] = Aspose.Imaging.Color.Yellow;
            }
            else
            {
                //Imposta il colore del pixel indicizzato su blu
                pixels[index] = Aspose.Imaging.Color.Blue;
            }
        }

        //Applica le modifiche ai pixel all'immagine
        image.SavePixels(image.Bounds, pixels);

        // salva tutte le modifiche.
        image.Save();
    }

    // Scrivi MemoryStream su file
    using (System.IO.FileStream fileStream = new System.IO.FileStream(@"C:\temp\output.gif", System.IO.FileMode.Create))
    {
        stream.WriteTo(fileStream);
    }   
}
```

### Guarda anche

* class [ImageOptionsBase](../../aspose.imaging/imageoptionsbase)
* spazio dei nomi [Aspose.Imaging.ImageOptions](../../aspose.imaging.imageoptions)
* assemblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
