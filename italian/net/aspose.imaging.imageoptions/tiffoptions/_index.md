---
title: TiffOptions
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Le opzioni del formato del file tiff. Si noti che i tag di larghezza e altezza verranno sovrascritti durante la creazione dellimmagine dai parametri di larghezza e altezza quindi non è necessario specificarli direttamente. Si noti che molte opzioni restituiscono un valore predefinito ma ciò non significa che questa opzione è impostata esplicitamente come valore di tag. Per verificare la presenza del tag utilizzare la proprietà Tags o il metodo IsTagPresent corrispondente.
type: docs
weight: 10220
url: /it/net/aspose.imaging.imageoptions/tiffoptions/
---
## TiffOptions class

Le opzioni del formato del file tiff. Si noti che i tag di larghezza e altezza verranno sovrascritti durante la creazione dell'immagine dai parametri di larghezza e altezza, quindi non è necessario specificarli direttamente. Si noti che molte opzioni restituiscono un valore predefinito, ma ciò non significa che questa opzione è impostata esplicitamente come valore di tag. Per verificare la presenza del tag utilizzare la proprietà Tags o il metodo IsTagPresent corrispondente.

```csharp
public class TiffOptions : ImageOptionsBase
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [TiffOptions](tiffoptions#constructor_2)(TiffDataType[]) | Inizializza una nuova istanza di[`TiffOptions`](../tiffoptions) classe. |
| [TiffOptions](tiffoptions#constructor)(TiffExpectedFormat) | Inizializza una nuova istanza di[`TiffOptions`](../tiffoptions)classe. Per impostazione predefinita viene utilizzata la convenzione little endian. |
| [TiffOptions](tiffoptions#constructor_3)(TiffOptions) | Inizializza una nuova istanza di[`TiffOptions`](../tiffoptions) classe. |
| [TiffOptions](tiffoptions#constructor_1)(TiffExpectedFormat, TiffByteOrder) | Inizializza una nuova istanza di[`TiffOptions`](../tiffoptions) classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AlphaStorage](../../aspose.imaging.imageoptions/tiffoptions/alphastorage) { get; set; } | Ottiene o imposta l'opzione di archiviazione alfa. Opzioni diverse daUnspecified vengono utilizzati quando ce ne sono più di 3[`SamplesPerPixel`](./samplesperpixel) definito. |
| [Artist](../../aspose.imaging.imageoptions/tiffoptions/artist) { get; set; } | Ottiene o imposta l'artista. |
| [BitsPerPixel](../../aspose.imaging.imageoptions/tiffoptions/bitsperpixel) { get; } | Ottiene i bit per pixel. |
| [BitsPerSample](../../aspose.imaging.imageoptions/tiffoptions/bitspersample) { get; set; } | Ottiene o imposta i bit per campione. |
| [BufferSizeHint](../../aspose.imaging/imageoptionsbase/buffersizehint) { get; set; } | Ottiene o imposta l'hint per la dimensione del buffer che è la dimensione massima consentita per tutti i buffer interni. |
| [ByteOrder](../../aspose.imaging.imageoptions/tiffoptions/byteorder) { get; set; } | Ottiene o imposta un valore che indica l'ordine dei byte tiff. |
| [ColorMap](../../aspose.imaging.imageoptions/tiffoptions/colormap) { get; set; } | Ottiene o imposta la mappa dei colori. |
| [CompressedQuality](../../aspose.imaging.imageoptions/tiffoptions/compressedquality) { get; set; } | Ottiene o imposta la qualità dell'immagine compressa. Usato con la compressione Jpeg. |
| [Compression](../../aspose.imaging.imageoptions/tiffoptions/compression) { get; set; } | Ottiene o imposta la compressione. |
| [Copyright](../../aspose.imaging.imageoptions/tiffoptions/copyright) { get; set; } | Ottiene o imposta il copyright. |
| [DateTime](../../aspose.imaging.imageoptions/tiffoptions/datetime) { get; set; } | Ottiene o imposta la data e l'ora. |
| [DisableIccExport](../../aspose.imaging.imageoptions/tiffoptions/disableiccexport) { get; set; } | Ottiene o imposta un valore che indica se l'esportazione del profilo ICC è disabilitata (il profilo ICC viene applicato in anticipo ai pixel di origine). |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Ottiene un valore che indica se questa istanza è stata eliminata. |
| [DocumentName](../../aspose.imaging.imageoptions/tiffoptions/documentname) { get; set; } | Ottiene o imposta il nome del documento. |
| [ExifIfd](../../aspose.imaging.imageoptions/tiffoptions/exififd) { get; } | Ottiene o imposta il puntatore su EXIF IFD. |
| [ExtraSamples](../../aspose.imaging.imageoptions/tiffoptions/extrasamples) { get; } | Ottiene i valori dei campioni extra. |
| [FaxT4Options](../../aspose.imaging.imageoptions/tiffoptions/faxt4options) { get; set; } | Ottiene o imposta le opzioni fax t4. |
| [FileStandard](../../aspose.imaging.imageoptions/tiffoptions/filestandard) { get; set; } | Ottiene o imposta lo standard del file TIFF. |
| [FillOrder](../../aspose.imaging.imageoptions/tiffoptions/fillorder) { get; set; } | Ottiene o imposta l'ordine di riempimento dei bit di byte. |
| [FullFrame](../../aspose.imaging/imageoptionsbase/fullframe) { get; set; } | Ottiene o imposta un valore che indica se [fotogramma intero]. |
| [HalfToneHints](../../aspose.imaging.imageoptions/tiffoptions/halftonehints) { get; set; } | Ottiene o imposta i suggerimenti per i mezzitoni. |
| [IccProfile](../../aspose.imaging.imageoptions/tiffoptions/iccprofile) { get; set; } | Ottiene o imposta il flusso del profilo Icc. |
| [ImageDescription](../../aspose.imaging.imageoptions/tiffoptions/imagedescription) { get; set; } | Ottiene o imposta la descrizione dell'immagine. |
| [ImageLength](../../aspose.imaging.imageoptions/tiffoptions/imagelength) { get; set; } | Ottiene o imposta la lunghezza dell'immagine. |
| [ImageWidth](../../aspose.imaging.imageoptions/tiffoptions/imagewidth) { get; set; } | Ottiene o imposta la larghezza dell'immagine. |
| [InkNames](../../aspose.imaging.imageoptions/tiffoptions/inknames) { get; set; } | Ottiene o imposta i nomi degli inchiostri. |
| [IsExtraSamplesPresent](../../aspose.imaging.imageoptions/tiffoptions/isextrasamplespresent) { get; } | Ottiene un valore che indica se i campioni aggiuntivi sono presenti. |
| [IsTiled](../../aspose.imaging.imageoptions/tiffoptions/istiled) { get; } | Ottiene un valore che indica se l'immagine è affiancata. |
| [IsValid](../../aspose.imaging.imageoptions/tiffoptions/isvalid) { get; } | Ottiene un valore che indica se il[`TiffOptions`](../tiffoptions) sono stati configurati correttamente. Utilizzare il metodo Convalida per trovare il motivo dell'errore. |
| [MaxSampleValue](../../aspose.imaging.imageoptions/tiffoptions/maxsamplevalue) { get; set; } | Ottiene o imposta il valore di campionamento massimo. |
| [MinSampleValue](../../aspose.imaging.imageoptions/tiffoptions/minsamplevalue) { get; set; } | Ottiene o imposta il valore di campionamento minimo. |
| [MultiPageOptions](../../aspose.imaging/imageoptionsbase/multipageoptions) { get; set; } | Le opzioni multipagina |
| [Orientation](../../aspose.imaging.imageoptions/tiffoptions/orientation) { get; set; } | Ottiene o imposta l'orientamento. |
| [PageName](../../aspose.imaging.imageoptions/tiffoptions/pagename) { get; set; } | Ottiene o imposta il nome della pagina. |
| [PageNumber](../../aspose.imaging.imageoptions/tiffoptions/pagenumber) { get; set; } | Ottiene o imposta il tag del numero di pagina. |
| override [Palette](../../aspose.imaging.imageoptions/tiffoptions/palette) { get; set; } | Ottiene o imposta la tavolozza dei colori. |
| [Photometric](../../aspose.imaging.imageoptions/tiffoptions/photometric) { get; set; } | Ottiene o imposta la fotometrica. |
| [PlanarConfiguration](../../aspose.imaging.imageoptions/tiffoptions/planarconfiguration) { get; set; } | Ottiene o imposta la configurazione planare. |
| [Predictor](../../aspose.imaging.imageoptions/tiffoptions/predictor) { get; set; } | Ottiene o imposta il predittore per la compressione LZW. |
| [PremultiplyComponents](../../aspose.imaging.imageoptions/tiffoptions/premultiplycomponents) { get; set; } | Ottiene o imposta un valore che indica se i componenti devono essere premoltiplicati. |
| [ProgressEventHandler](../../aspose.imaging/imageoptionsbase/progresseventhandler) { get; set; } | Ottiene o imposta il gestore dell'evento di avanzamento. |
| override [ResolutionSettings](../../aspose.imaging.imageoptions/tiffoptions/resolutionsettings) { get; set; } | Ottiene o imposta le impostazioni di risoluzione. |
| [ResolutionUnit](../../aspose.imaging.imageoptions/tiffoptions/resolutionunit) { get; set; } | Ottiene o imposta l'unità di risoluzione. |
| [RowsPerStrip](../../aspose.imaging.imageoptions/tiffoptions/rowsperstrip) { get; set; } | Ottiene o imposta le righe per striscia. |
| [SampleFormat](../../aspose.imaging.imageoptions/tiffoptions/sampleformat) { get; set; } | Ottiene o imposta il formato di esempio. |
| [SamplesPerPixel](../../aspose.imaging.imageoptions/tiffoptions/samplesperpixel) { get; } | Ottiene i campioni per pixel. Per modificare questo valore di proprietà, utilizzare il[`BitsPerSample`](./bitspersample) setter proprietà. |
| [ScannerManufacturer](../../aspose.imaging.imageoptions/tiffoptions/scannermanufacturer) { get; set; } | Ottiene o imposta il produttore dello scanner. |
| [ScannerModel](../../aspose.imaging.imageoptions/tiffoptions/scannermodel) { get; set; } | Ottiene o imposta il modello dello scanner. |
| [SmaxSampleValue](../../aspose.imaging.imageoptions/tiffoptions/smaxsamplevalue) { get; set; } | Ottiene o imposta il valore di campionamento massimo. Il valore ha un tipo di campo che corrisponde meglio ai dati di esempio (tipo Byte, Short o Long). |
| [SminSampleValue](../../aspose.imaging.imageoptions/tiffoptions/sminsamplevalue) { get; set; } | Ottiene o imposta il valore di campionamento minimo. Il valore ha un tipo di campo che corrisponde meglio ai dati di esempio (tipo Byte, Short o Long). |
| [SoftwareType](../../aspose.imaging.imageoptions/tiffoptions/softwaretype) { get; set; } | Ottiene o imposta il tipo di software. |
| [Source](../../aspose.imaging/imageoptionsbase/source) { get; set; } | Ottiene o imposta l'origine in cui creare l'immagine. |
| [StripByteCounts](../../aspose.imaging.imageoptions/tiffoptions/stripbytecounts) { get; set; } | Ottiene o imposta i conteggi di strip byte. |
| [StripOffsets](../../aspose.imaging.imageoptions/tiffoptions/stripoffsets) { get; set; } | Ottiene o imposta gli offset delle strisce. |
| [SubFileType](../../aspose.imaging.imageoptions/tiffoptions/subfiletype) { get; set; } | Ottiene o imposta un'indicazione generale del tipo di dati contenuti in questo file secondario. |
| [Tags](../../aspose.imaging.imageoptions/tiffoptions/tags) { get; set; } | Ottiene o imposta i tag. |
| [TargetPrinter](../../aspose.imaging.imageoptions/tiffoptions/targetprinter) { get; set; } | Ottiene o imposta la stampante di destinazione. |
| [Threshholding](../../aspose.imaging.imageoptions/tiffoptions/threshholding) { get; set; } | Ottiene o imposta la soglia. |
| [TileByteCounts](../../aspose.imaging.imageoptions/tiffoptions/tilebytecounts) { get; set; } | Ottiene o imposta i conteggi di byte del riquadro. |
| [TileLength](../../aspose.imaging.imageoptions/tiffoptions/tilelength) { get; set; } | Ottiene o imposta la lunghezza del riquadro. |
| [TileOffsets](../../aspose.imaging.imageoptions/tiffoptions/tileoffsets) { get; set; } | Ottiene o imposta gli offset delle tessere. |
| [TileWidth](../../aspose.imaging.imageoptions/tiffoptions/tilewidth) { get; set; } | Ottiene o imposta la larghezza della piastrella. |
| [TotalPages](../../aspose.imaging.imageoptions/tiffoptions/totalpages) { get; } | Ottiene le pagine totali. |
| [ValidTagCount](../../aspose.imaging.imageoptions/tiffoptions/validtagcount) { get; } | Ottiene il conteggio dei tag validi. Questo non è il conteggio totale dei tag ma il numero di tag che possono essere conservati. |
| [VectorRasterizationOptions](../../aspose.imaging/imageoptionsbase/vectorrasterizationoptions) { get; set; } | Ottiene o imposta le opzioni di rasterizzazione del vettore. |
| override [XmpData](../../aspose.imaging.imageoptions/tiffoptions/xmpdata) { get; set; } | Ottiene o imposta il contenitore di metadati XMP. |
| [XPAuthor](../../aspose.imaging.imageoptions/tiffoptions/xpauthor) { get; set; } | Ottiene o imposta l'autore dell'immagine, utilizzato da Esplora risorse. |
| [XPComment](../../aspose.imaging.imageoptions/tiffoptions/xpcomment) { get; set; } | Ottiene o imposta il commento sull'immagine, utilizzato da Esplora risorse. |
| [XPKeywords](../../aspose.imaging.imageoptions/tiffoptions/xpkeywords) { get; set; } | Ottiene o imposta l'immagine del soggetto, utilizzata da Esplora risorse. |
| [Xposition](../../aspose.imaging.imageoptions/tiffoptions/xposition) { get; set; } | Ottiene o imposta la posizione x. |
| [XPSubject](../../aspose.imaging.imageoptions/tiffoptions/xpsubject) { get; set; } | Ottiene o imposta informazioni sull'immagine, utilizzate da Esplora risorse. |
| [XPTitle](../../aspose.imaging.imageoptions/tiffoptions/xptitle) { get; set; } | Ottiene o imposta informazioni sull'immagine, utilizzate da Esplora risorse. |
| [Xresolution](../../aspose.imaging.imageoptions/tiffoptions/xresolution) { get; set; } | Ottiene o imposta la risoluzione x. |
| [YCbCrCoefficients](../../aspose.imaging.imageoptions/tiffoptions/ycbcrcoefficients) { get; set; } | Ottiene o imposta YCbCrCoefficients. |
| [YCbCrSubsampling](../../aspose.imaging.imageoptions/tiffoptions/ycbcrsubsampling) { get; set; } | Ottiene o imposta i fattori di sottocampionamento per il fotometrico YCbCr. |
| [Yposition](../../aspose.imaging.imageoptions/tiffoptions/yposition) { get; set; } | Ottiene o imposta la posizione y. |
| [Yresolution](../../aspose.imaging.imageoptions/tiffoptions/yresolution) { get; set; } | Ottiene o imposta la risoluzione y. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AddTag](../../aspose.imaging.imageoptions/tiffoptions/addtag)(TiffDataType) | Aggiunge un nuovo tag. |
| [AddTags](../../aspose.imaging.imageoptions/tiffoptions/addtags)(TiffDataType[]) | Aggiunge i tag. |
| virtual [Clone](../../aspose.imaging/imageoptionsbase/clone)() | Clona questa istanza. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Elimina l'istanza corrente. |
| [GetTagByType](../../aspose.imaging.imageoptions/tiffoptions/gettagbytype)(TiffTags) | Ottiene l'istanza del tag per tipo. |
| [IsTagPresent](../../aspose.imaging.imageoptions/tiffoptions/istagpresent)(TiffTags) | Determina se il tag è presente nelle opzioni o meno. |
| [RemoveTag](../../aspose.imaging.imageoptions/tiffoptions/removetag)(TiffTags) | Rimuove il tag. |
| [Validate](../../aspose.imaging.imageoptions/tiffoptions/validate)() | Convalida se le opzioni hanno una combinazione valida di tag |
| static [GetValidTagsCount](../../aspose.imaging.imageoptions/tiffoptions/getvalidtagscount)(TiffDataType[]) | Ottiene il conteggio dei tag validi. |

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

L'esempio seguente mostra come convertire un'immagine vettoriale multipagina in formato TIFF in modo generale senza fare riferimento a un particolare tipo di immagine.

```csharp
[C#]

string dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
string inputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr");
string outputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr.tiff");

Aspose.Imaging.ImageOptionsBase exportOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Aspose.Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFilePath))
{
    exportOptions.MultiPageOptions = null;

    // Esporta solo le prime due pagine. Queste pagine verranno presentate come frame nel TIFF di output.
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

Questi esempi utilizzano la classe GraphicsPath e Graphics per creare e manipolare figure su un'area Image. Esempio crea una nuova immagine (di tipo Tiff), cancella la superficie e disegna percorsi con l'aiuto della classe GraphicsPath. Alla fine viene chiamato il metodo DrawPath esposto dalla classe Graphics per eseguire il rendering dei tracciati sulla superficie.

```csharp
[C#]

//Crea un'istanza di FileStream
using (System.IO.FileStream stream = new System.IO.FileStream(@"C:\temp\output.tiff", System.IO.FileMode.Create))
{
    //Crea un'istanza di TiffOptions e imposta le sue varie proprietà
    Aspose.Imaging.ImageOptions.TiffOptions tiffOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

    //Imposta l'origine per l'istanza di ImageOptions
    tiffOptions.Source = new Aspose.Imaging.Sources.StreamSource(stream);

    //Crea un'istanza di Image 
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(tiffOptions, 500, 500))
    {
        //Crea e inizializza un'istanza della classe Graphics
        Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);

        //Cancella superficie grafica
        graphics.Clear(Color.Wheat);

        //Crea un'istanza della classe GraphicsPath
        Aspose.Imaging.GraphicsPath graphicspath = new Aspose.Imaging.GraphicsPath();

        //Crea un'istanza della classe Figure
        Aspose.Imaging.Figure figure = new Aspose.Imaging.Figure();

        //Aggiungi forme all'oggetto Figura
        figure.AddShape(new Aspose.Imaging.Shapes.RectangleShape(new Aspose.Imaging.RectangleF(10f, 10f, 300f, 300f)));
        figure.AddShape(new Aspose.Imaging.Shapes.EllipseShape(new Aspose.Imaging.RectangleF(50f, 50f, 300f, 300f)));
        figure.AddShape(new Aspose.Imaging.Shapes.PieShape(new Aspose.Imaging.RectangleF(new Aspose.Imaging.PointF(250f, 250f), new Aspose.Imaging.SizeF(200f, 200f)), 0f, 45f));

        //Aggiungi l'oggetto Figure a GraphicsPath
        graphicspath.AddFigure(figure);

        //Disegna il percorso con l'oggetto Penna di colore Nero
        graphics.DrawPath(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Black, 2), graphicspath);

        // salva tutte le modifiche.
        image.Save();
    }
}
```

### Guarda anche

* class [ImageOptionsBase](../../aspose.imaging/imageoptionsbase)
* spazio dei nomi [Aspose.Imaging.ImageOptions](../../aspose.imaging.imageoptions)
* assemblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
