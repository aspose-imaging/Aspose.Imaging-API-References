---
title: JpegOptions
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Il formato del file jpeg crea opzioni.
type: docs
weight: 10030
url: /it/aspose.imaging.imageoptions/jpegoptions/
---
## JpegOptions class

Il formato del file jpeg crea opzioni.

```csharp
public class JpegOptions : ImageOptionsBase
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [JpegOptions](jpegoptions#constructor)() | Inizializza una nuova istanza di[`JpegOptions`](../jpegoptions) classe. |
| [JpegOptions](jpegoptions#constructor_1)(JpegOptions) | Inizializza una nuova istanza di[`JpegOptions`](../jpegoptions) classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [BitsPerChannel](../../aspose.imaging.imageoptions/jpegoptions/bitsperchannel) { get; set; } | Ottiene o imposta i bit per canale per l'immagine JPEG senza perdita di dati. Ora supportiamo da 2 a 8 bit per canale. |
| [BufferSizeHint](../../aspose.imaging/imageoptionsbase/buffersizehint) { get; set; } | Ottiene o imposta l'hint per la dimensione del buffer che è la dimensione massima consentita per tutti i buffer interni. |
| [CmykColorProfile](../../aspose.imaging.imageoptions/jpegoptions/cmykcolorprofile) { get; set; } | Il profilo colore CMYK di destinazione per le immagini jpeg CMYK. Utilizzare per salvare le immagini. Deve essere abbinato a RGBColorProfile per una corretta conversione del colore. |
| [ColorType](../../aspose.imaging.imageoptions/jpegoptions/colortype) { get; set; } | Ottiene o imposta il tipo di colore per l'immagine jpeg. |
| [Comment](../../aspose.imaging.imageoptions/jpegoptions/comment) { get; set; } | Ottiene o imposta il commento del file jpeg. |
| [CompressionType](../../aspose.imaging.imageoptions/jpegoptions/compressiontype) { get; set; } | Ottiene o imposta il tipo di compressione. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Ottiene un valore che indica se questa istanza è stata eliminata. |
| [ExifData](../../aspose.imaging.imageoptions/jpegoptions/exifdata) { get; set; } | Ottieni o imposta il contenitore dati exif |
| [FullFrame](../../aspose.imaging/imageoptionsbase/fullframe) { get; set; } | Ottiene o imposta un valore che indica se [fotogramma intero]. |
| [HorizontalSampling](../../aspose.imaging.imageoptions/jpegoptions/horizontalsampling) { get; set; } | Ottiene o imposta i sottocampionamenti orizzontali per ogni componente. |
| [Jfif](../../aspose.imaging.imageoptions/jpegoptions/jfif) { get; set; } | Ottiene o imposta jfif. |
| [JpegLsAllowedLossyError](../../aspose.imaging.imageoptions/jpegoptions/jpeglsallowedlossyerror) { get; set; } | Ottiene o imposta la differenza JPEG-LS associata alla codifica quasi senza perdita di dati (parametro NEAR dalla specifica JPEG-LS). |
| [JpegLsInterleaveMode](../../aspose.imaging.imageoptions/jpegoptions/jpeglsinterleavemode) { get; set; } | Ottiene o imposta la modalità interleave JPEG-LS. |
| [JpegLsPreset](../../aspose.imaging.imageoptions/jpegoptions/jpeglspreset) { get; set; } | Ottiene o imposta i parametri predefiniti JPEG-LS. |
| [MultiPageOptions](../../aspose.imaging/imageoptionsbase/multipageoptions) { get; set; } | Le opzioni multipagina |
| virtual [Palette](../../aspose.imaging/imageoptionsbase/palette) { get; set; } | Ottiene o imposta la tavolozza dei colori. |
| [PreblendAlphaIfPresent](../../aspose.imaging.imageoptions/jpegoptions/preblendalphaifpresent) { get; set; } | Ottiene o imposta un valore che indica se i componenti rosso, verde e blu devono essere mischiati con un colore di sfondo, se è presente il canale alfa. |
| [ProgressEventHandler](../../aspose.imaging/imageoptionsbase/progresseventhandler) { get; set; } | Ottiene o imposta il gestore dell'evento di avanzamento. |
| [Quality](../../aspose.imaging.imageoptions/jpegoptions/quality) { get; set; } | Ottiene o imposta la qualità dell'immagine. |
| [RdOptSettings](../../aspose.imaging.imageoptions/jpegoptions/rdoptsettings) { get; set; } | Ottiene o imposta le impostazioni dell'ottimizzatore RD. |
| virtual [ResolutionSettings](../../aspose.imaging/imageoptionsbase/resolutionsettings) { get; set; } | Ottiene o imposta le impostazioni di risoluzione. |
| [ResolutionUnit](../../aspose.imaging.imageoptions/jpegoptions/resolutionunit) { get; set; } | Ottiene o imposta l'unità di risoluzione. |
| [RgbColorProfile](../../aspose.imaging.imageoptions/jpegoptions/rgbcolorprofile) { get; set; } | Il profilo colore RGB di destinazione per le immagini jpeg CMYK. Utilizzare per salvare le immagini. Deve essere abbinato a CMYKColorProfile per una corretta conversione del colore. |
| [SampleRoundingMode](../../aspose.imaging.imageoptions/jpegoptions/sampleroundingmode) { get; set; } | Ottiene o imposta la modalità di arrotondamento del campione per adattare un valore a 8 bit a un valore a n bit.BitsPerChannel |
| [ScaledQuality](../../aspose.imaging.imageoptions/jpegoptions/scaledquality) { get; } | La qualità in scala. |
| [Source](../../aspose.imaging/imageoptionsbase/source) { get; set; } | Ottiene o imposta l'origine in cui creare l'immagine. |
| [VectorRasterizationOptions](../../aspose.imaging/imageoptionsbase/vectorrasterizationoptions) { get; set; } | Ottiene o imposta le opzioni di rasterizzazione del vettore. |
| [VerticalSampling](../../aspose.imaging.imageoptions/jpegoptions/verticalsampling) { get; set; } | Ottiene o imposta i sottocampionamenti verticali per ogni componente. |
| override [XmpData](../../aspose.imaging.imageoptions/jpegoptions/xmpdata) { get; set; } | Ottiene o imposta il contenitore di metadati XMP. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| virtual [Clone](../../aspose.imaging/imageoptionsbase/clone)() | Clona questa istanza. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Elimina l'istanza corrente. |

### Esempi

Questo esempio mostra l'uso di System.IO.Stream per creare un nuovo file immagine (un tipo JPEG)

```csharp
[C#]

//Crea un'istanza di JpegOptions e ne imposta le varie proprietà
Aspose.Imaging.ImageOptions.JpegOptions jpegOptions = new Aspose.Imaging.ImageOptions.JpegOptions();

//Crea un'istanza di System.IO.Stream
System.IO.Stream stream = new System.IO.FileStream(@"C:\temp\sample.jpeg", System.IO.FileMode.Create);

//Definisce la proprietà di origine per l'istanza di JpegOptions
//Il secondo parametro booleano determina se lo Stream viene eliminato una volta uscito dall'ambito
jpegOptions.Source = new Aspose.Imaging.Sources.StreamSource(stream, true);

//Crea un'istanza di Image e chiama il metodo Create con JpegOptions come parametro per inizializzare l'oggetto Image   
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(jpegOptions, 500, 500))
{
    //eseguo un po' di elaborazione delle immagini
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

L'esempio seguente mostra come convertire un'immagine vettoriale multipagina in formato JPEG in modo generale senza fare riferimento a un particolare tipo di immagine.

```csharp
[C#]

string dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
string inputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr");
string outputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr.jpeg");

Aspose.Imaging.ImageOptionsBase exportOptions = new Aspose.Imaging.ImageOptions.JpegOptions();

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFilePath))
{
    exportOptions.MultiPageOptions = null;

    // Esporta solo le prime due pagine. In effetti, verrà rasterizzata solo una pagina perché JPEG non è un formato multipagina.
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
