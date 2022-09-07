---
title: TiffImage
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Limmagine tiff.
type: docs
weight: 7880
url: /it/net/aspose.imaging.fileformats.tiff/tiffimage/
---
## TiffImage class

L'immagine tiff.

```csharp
public sealed class TiffImage : RasterCachedMultipageImage, IMultipageImageExt
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [TiffImage](tiffimage#constructor)(TiffFrame) | Inizializza una nuova istanza di[`TiffImage`](../tiffimage) classe. |
| [TiffImage](tiffimage#constructor_1)(TiffFrame[]) | Inizializza una nuova istanza di[`TiffImage`](../tiffimage) classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [ActiveFrame](../../aspose.imaging.fileformats.tiff/tiffimage/activeframe) { get; set; } | Ottiene o imposta il frame attivo. |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette) { get; set; } | Ottiene o imposta un valore che indica se regolare automaticamente la tavolozza. |
| override [BackgroundColor](../../aspose.imaging/rastercachedmultipageimage/backgroundcolor) { get; set; } | Ottiene o imposta un valore per il colore di sfondo. |
| override [BitsPerPixel](../../aspose.imaging/rastercachedmultipageimage/bitsperpixel) { get; } | Ottiene il numero di bit dell'immagine per pixel. |
| [Bounds](../../aspose.imaging/image/bounds) { get; } | Ottiene i limiti dell'immagine. |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint) { get; set; } | Ottiene o imposta l'hint per la dimensione del buffer che è la dimensione massima consentita per tutti i buffer interni. |
| [ByteOrder](../../aspose.imaging.fileformats.tiff/tiffimage/byteorder) { get; set; } | Ottiene o imposta un valore che indica l'ordine dei byte tiff. |
| [Container](../../aspose.imaging/image/container) { get; } | Ottiene il[`Image`](../../aspose.imaging/image) contenitore. |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer) { get; } | Ottiene il flusso di dati dell'oggetto. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Ottiene un valore che indica se questa istanza è stata eliminata. |
| [ExifData](../../aspose.imaging.fileformats.tiff/tiffimage/exifdata) { get; set; } | Ottiene o imposta i dati EXIF per il frame attivo. |
| override [FileFormat](../../aspose.imaging.fileformats.tiff/tiffimage/fileformat) { get; } | Ottiene un valore di formato file |
| [Frames](../../aspose.imaging.fileformats.tiff/tiffimage/frames) { get; } | Ottiene l'array Frames dell'immagine. |
| override [HasAlpha](../../aspose.imaging.fileformats.tiff/tiffimage/hasalpha) { get; } | Ottiene il canale alfa Has. |
| virtual [HasBackgroundColor](../../aspose.imaging/image/hasbackgroundcolor) { get; set; } | Ottiene o imposta un valore che indica se l'immagine ha il colore di sfondo. |
| override [HasTransparentColor](../../aspose.imaging/rastercachedmultipageimage/hastransparentcolor) { get; } | Ottiene un valore che indica se l'immagine ha un colore trasparente. |
| override [Height](../../aspose.imaging/rastercachedmultipageimage/height) { get; } | Ottiene l'altezza dell'immagine. |
| override [HorizontalResolution](../../aspose.imaging.fileformats.tiff/tiffimage/horizontalresolution) { get; set; } | Ottiene la risoluzione orizzontale, in pixel per pollice, di questo[`Image`](../../aspose.imaging/image) . |
| override [ImageOpacity](../../aspose.imaging/rastercachedmultipageimage/imageopacity) { get; } | Ottiene l'opacità di questa immagine. |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor) { get; set; } | Ottiene o imposta il monitor di interruzione. |
| [IsCached](../../aspose.imaging/rastercachedmultipageimage/iscached) { get; } | Ottiene un valore che indica se i dati dell'immagine sono attualmente memorizzati nella cache. |
| [IsRawDataAvailable](../../aspose.imaging/rasterimage/israwdataavailable) { get; } | Ottiene un valore che indica se è disponibile il caricamento dei dati grezzi. |
| override [PageCount](../../aspose.imaging.fileformats.tiff/tiffimage/pagecount) { get; } | Ottiene il conteggio delle pagine. |
| virtual [PageExportingAction](../../aspose.imaging/rastercachedmultipageimage/pageexportingaction) { get; set; } | Ottiene o imposta l'azione di esportazione della pagina. Tieni presente che l'impostazione di questo metodo rilascerà automaticamente le risorse della pagina dopo l'esecuzione. Verrà eseguito appena prima del salvataggio di ogni pagina. |
| override [Pages](../../aspose.imaging.fileformats.tiff/tiffimage/pages) { get; } | Ottiene le pagine. |
| [Palette](../../aspose.imaging/image/palette) { get; set; } | Ottiene o imposta la tavolozza dei colori. La tavolozza dei colori non viene utilizzata quando i pixel sono rappresentati direttamente. |
| override [PremultiplyComponents](../../aspose.imaging.fileformats.tiff/tiffimage/premultiplycomponents) { get; set; } | Ottiene o imposta un valore che indica se i componenti devono essere premoltiplicati. |
| [RawCustomColorConverter](../../aspose.imaging/rasterimage/rawcustomcolorconverter) { get; set; } | Ottiene o imposta il convertitore colore personalizzato |
| virtual [RawDataFormat](../../aspose.imaging/rasterimage/rawdataformat) { get; } | Ottiene il formato dei dati grezzi. |
| [RawDataSettings](../../aspose.imaging/rasterimage/rawdatasettings) { get; } | Ottiene le impostazioni dei dati grezzi correnti. Nota quando si utilizzano queste impostazioni i dati vengono caricati senza conversione. |
| [RawFallbackIndex](../../aspose.imaging/rasterimage/rawfallbackindex) { get; set; } | Ottiene o imposta l'indice di fallback da utilizzare quando l'indice della tavolozza è fuori dai limiti |
| [RawIndexedColorConverter](../../aspose.imaging/rasterimage/rawindexedcolorconverter) { get; set; } | Ottiene o imposta il convertitore colore indicizzato |
| virtual [RawLineSize](../../aspose.imaging/rasterimage/rawlinesize) { get; } | Ottiene la dimensione della riga grezza in byte. |
| [Size](../../aspose.imaging/image/size) { get; } | Ottiene la dimensione dell'immagine. |
| virtual [TransparentColor](../../aspose.imaging/rasterimage/transparentcolor) { get; set; } | Ottiene il colore trasparente dell'immagine. |
| virtual [UpdateXmpData](../../aspose.imaging/rasterimage/updatexmpdata) { get; set; } | Ottiene o imposta un valore che indica se aggiornare i metadati XMP. |
| override [UsePalette](../../aspose.imaging/rasterimage/usepalette) { get; } | Ottiene un valore che indica se viene utilizzata la tavolozza dell'immagine. |
| virtual [UseRawData](../../aspose.imaging/rasterimage/userawdata) { get; set; } | Ottiene o imposta un valore che indica se utilizzare il caricamento dei dati grezzi quando è disponibile il caricamento dei dati grezzi. |
| override [VerticalResolution](../../aspose.imaging.fileformats.tiff/tiffimage/verticalresolution) { get; set; } | Ottiene la risoluzione verticale, in pixel per pollice, di questo[`Image`](../../aspose.imaging/image) . |
| override [Width](../../aspose.imaging/rastercachedmultipageimage/width) { get; } | Ottiene la larghezza dell'immagine. |
| override [XmpData](../../aspose.imaging/rastercachedmultipageimage/xmpdata) { get; set; } | Ottiene o imposta i dati XMP dal frame. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Add](../../aspose.imaging.fileformats.tiff/tiffimage/add)(TiffImage) | Aggiunge i fotogrammi dell'immagine specificata al fotogramma corrente. |
| [AddFrame](../../aspose.imaging.fileformats.tiff/tiffimage/addframe)(TiffFrame) | Aggiunge la cornice all'immagine |
| [AddFrames](../../aspose.imaging.fileformats.tiff/tiffimage/addframes)(TiffFrame[]) | Aggiunge l'array di fotogrammi a image |
| [AddPage](../../aspose.imaging.fileformats.tiff/tiffimage/addpage)(RasterImage) | Aggiunge la pagina all'immagine. |
| override [AdjustBrightness](../../aspose.imaging.fileformats.tiff/tiffimage/adjustbrightness)(int) | Regolazione di a*brightness* per immagine. |
| override [AdjustContrast](../../aspose.imaging.fileformats.tiff/tiffimage/adjustcontrast)(float) | [`Image`](../../aspose.imaging/image) contrasto |
| override [AdjustGamma](../../aspose.imaging.fileformats.tiff/tiffimage/adjustgamma#adjustgamma)(float) | Correzione gamma di un'immagine. |
| override [AdjustGamma](../../aspose.imaging.fileformats.tiff/tiffimage/adjustgamma#adjustgamma_1)(float, float, float) | Correzione gamma di un'immagine. |
| [AlignResolutions](../../aspose.imaging.fileformats.tiff/tiffimage/alignresolutions)() | Metodo di supporto per rendere uguali le risoluzioni orizzontali e verticali. |
| override [BinarizeBradley](../../aspose.imaging/rastercachedmultipageimage/binarizebradley)(double) | Binarizzazione di un'immagine utilizzando l'algoritmo di soglia adattivo di Bradley utilizzando la soglia di immagine integrale |
| override [BinarizeBradley](../../aspose.imaging.fileformats.tiff/tiffimage/binarizebradley#binarizebradley_1)(double, int) | Binarizzazione di un'immagine utilizzando l'algoritmo di soglia adattivo di Bradley utilizzando la soglia di immagine integrale |
| override [BinarizeFixed](../../aspose.imaging.fileformats.tiff/tiffimage/binarizefixed)(byte) | Binarizzazione di un'immagine con soglia predefinita |
| override [BinarizeOtsu](../../aspose.imaging.fileformats.tiff/tiffimage/binarizeotsu)() | Binarizzazione di un'immagine con soglia Otsu |
| override [CacheData](../../aspose.imaging/rastercachedmultipageimage/cachedata)() | Memorizza nella cache i dati privati. |
| [CanSave](../../aspose.imaging/image/cansave)(ImageOptionsBase) | Determina se l'immagine può essere salvata nel formato file specificato rappresentato dalle opzioni di salvataggio passate. |
| override [Crop](../../aspose.imaging.fileformats.tiff/tiffimage/crop#crop)(Rectangle) | Ritaglio dell'immagine. |
| override [Crop](../../aspose.imaging.fileformats.tiff/tiffimage/crop#crop_1)(int, int, int, int) | Ritaglia immagine con spostamenti. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Elimina l'istanza corrente. |
| [Dither](../../aspose.imaging/rasterimage/dither)(DitheringMethod, int) | Esegue il dithering sull'immagine corrente. |
| override [Dither](../../aspose.imaging.fileformats.tiff/tiffimage/dither#dither_1)(DitheringMethod, int, IColorPalette) | Esegue il dithering sull'immagine corrente. |
| override [Filter](../../aspose.imaging.fileformats.tiff/tiffimage/filter)(Rectangle, FilterOptionsBase) | Filtra il rettangolo specificato. |
| [GetArgb32Pixel](../../aspose.imaging/rasterimage/getargb32pixel)(int, int) | Ottiene un'immagine ARGB pixel a 32 bit. |
| [GetDefaultArgb32Pixels](../../aspose.imaging/rasterimage/getdefaultargb32pixels)(Rectangle) | Ottiene l'array di pixel ARGB a 32 bit predefinito. |
| virtual [GetDefaultOptions](../../aspose.imaging/image/getdefaultoptions)(object[]) | Ottiene le opzioni predefinite. |
| [GetDefaultPixels](../../aspose.imaging/rasterimage/getdefaultpixels)(Rectangle, IPartialArgb32PixelLoader) | Ottiene l'array di pixel predefinito utilizzando il caricatore di pixel parziale. |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata)(Rectangle, RawDataSettings) | Ottiene l'array di dati grezzi predefinito. |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata)(Rectangle, IPartialRawDataLoader, RawDataSettings) | Ottiene l'array di dati grezzi predefinito utilizzando il caricatore di pixel parziale. |
| virtual [GetModifyDate](../../aspose.imaging/rasterimage/getmodifydate)(bool) | Ottiene la data e l'ora dell'ultima modifica dell'immagine della risorsa. |
| override [GetOriginalOptions](../../aspose.imaging.fileformats.tiff/tiffimage/getoriginaloptions)() | Ottiene le opzioni in base alle impostazioni del file originale. Questo può essere utile per mantenere invariati la profondità di bit e altri parametri dell'immagine originale. Ad esempio, se carichiamo un'immagine PNG in bianco e nero con 1 bit per pixel e quindi salvalo usando il [`Save`](../../aspose.imaging/datastreamsupporter/save) metodo, verrà prodotta l'immagine PNG di output con 8 bit per pixel. Per evitarlo e salvare l'immagine PNG con 1 bit per pixel, utilizzare questo metodo per ottenere le opzioni di salvataggio corrispondenti e passarle al[`Save`](../../aspose.imaging/image/save) metodo come secondo parametro. |
| [GetPixel](../../aspose.imaging/rasterimage/getpixel)(int, int) | Ottiene un pixel dell'immagine. |
| [GetSkewAngle](../../aspose.imaging/rasterimage/getskewangle)() | Ottiene l'angolo di inclinazione. Questo metodo è applicabile ai documenti di testo scansionati, per determinare l'angolo di inclinazione durante la scansione. |
| override [Grayscale](../../aspose.imaging.fileformats.tiff/tiffimage/grayscale)() | Trasformazione di un'immagine nella sua rappresentazione in scala di grigi |
| [InsertFrame](../../aspose.imaging.fileformats.tiff/tiffimage/insertframe)(int, TiffFrame) | La cornice di inserimento. |
| [LoadArgb32Pixels](../../aspose.imaging/rasterimage/loadargb32pixels)(Rectangle) | Carica pixel ARGB a 32 bit. |
| [LoadArgb64Pixels](../../aspose.imaging/rasterimage/loadargb64pixels)(Rectangle) | Carica pixel ARGB a 64 bit. |
| [LoadCmyk32Pixels](../../aspose.imaging/rasterimage/loadcmyk32pixels)(Rectangle) | Carica i pixel in formato CMYK. |
| [LoadPartialArgb32Pixels](../../aspose.imaging/rasterimage/loadpartialargb32pixels)(Rectangle, IPartialArgb32PixelLoader) | Carica i pixel ARGB a 32 bit parzialmente per pacchetti. |
| [LoadPartialPixels](../../aspose.imaging/rasterimage/loadpartialpixels)(Rectangle, IPartialPixelLoader) | Carica i pixel parzialmente per pacchetti. |
| [LoadPixels](../../aspose.imaging/rasterimage/loadpixels)(Rectangle) | Carica pixel. |
| [LoadRawData](../../aspose.imaging/rasterimage/loadrawdata)(Rectangle, RawDataSettings, IPartialRawDataLoader) | Carica dati grezzi. |
| [LoadRawData](../../aspose.imaging/rasterimage/loadrawdata)(Rectangle, Rectangle, RawDataSettings, IPartialRawDataLoader) | Carica dati grezzi. |
| [NormalizeAngle](../../aspose.imaging/rasterimage/normalizeangle)() | Normalizza l'angolo. Questo metodo è applicabile ai documenti di testo scansionati per eliminare la scansione obliqua. Questo metodo utilizza[`GetSkewAngle`](../../aspose.imaging/rasterimage/getskewangle) e[`Rotate`](../../aspose.imaging/rasterimage/rotate) metodi. |
| override [NormalizeAngle](../../aspose.imaging.fileformats.tiff/tiffimage/normalizeangle#normalizeangle_1)(bool, Color) | Normalizza l'angolo. Questo metodo è applicabile ai documenti di testo scansionati per eliminare la scansione obliqua. Questo metodo utilizza[`GetSkewAngle`](../../aspose.imaging/rasterimage/getskewangle) e[`Rotate`](./rotate) metodi. |
| [ReadArgb32ScanLine](../../aspose.imaging/rasterimage/readargb32scanline)(int) | Legge l'intera linea di scansione in base all'indice della linea di scansione specificato. |
| [ReadScanLine](../../aspose.imaging/rasterimage/readscanline)(int) | Legge l'intera linea di scansione in base all'indice della linea di scansione specificato. |
| [RemoveFrame](../../aspose.imaging.fileformats.tiff/tiffimage/removeframe#removeframe)(int) | Rimuove la cornice in base al suo indice. |
| [RemoveFrame](../../aspose.imaging.fileformats.tiff/tiffimage/removeframe#removeframe_1)(TiffFrame) | Rimuove il frame specificato. |
| [ReplaceColor](../../aspose.imaging/rasterimage/replacecolor)(Color, byte, Color) | Sostituisce un colore con un altro con la differenza consentita e conserva il valore alfa originale per salvare i bordi smussati. |
| override [ReplaceColor](../../aspose.imaging/rastercachedmultipageimage/replacecolor)(int, byte, int) | Sostituisce un colore con un altro con la differenza consentita e conserva il valore alfa originale per salvare i bordi smussati. |
| [ReplaceFrame](../../aspose.imaging.fileformats.tiff/tiffimage/replaceframe)(int, TiffFrame) | Sostituisce la cornice nella posizione specificata. |
| [ReplaceNonTransparentColors](../../aspose.imaging/rasterimage/replacenontransparentcolors)(Color) | Sostituisce tutti i colori non trasparenti con un nuovo colore e conserva il valore alfa originale per salvare i bordi smussati. Nota: se lo usi su immagini senza trasparenza, tutti i colori verranno sostituiti con uno solo. |
| override [ReplaceNonTransparentColors](../../aspose.imaging/rastercachedmultipageimage/replacenontransparentcolors)(int) | Sostituisce tutti i colori non trasparenti con un nuovo colore e conserva il valore alfa originale per salvare i bordi smussati. Nota: se lo usi su immagini senza trasparenza, tutti i colori verranno sostituiti con uno solo. |
| [Resize](../../aspose.imaging/image/resize)(int, int) | Ridimensiona l'immagine. Il predefinitoNearestNeighbourResample viene utilizzato. |
| override [Resize](../../aspose.imaging.fileformats.tiff/tiffimage/resize#resize_1)(int, int, ImageResizeSettings) | Ridimensiona l'immagine. |
| override [Resize](../../aspose.imaging.fileformats.tiff/tiffimage/resize#resize_2)(int, int, ResizeType) | Ridimensiona l'immagine. |
| [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int) | Ridimensiona proporzionalmente l'altezza. Il predefinitoNearestNeighbourResample viene utilizzato. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int, ImageResizeSettings) | Ridimensiona proporzionalmente l'altezza. |
| override [ResizeHeightProportionally](../../aspose.imaging.fileformats.tiff/tiffimage/resizeheightproportionally#resizeheightproportionally_2)(int, ResizeType) | Ridimensiona proporzionalmente la larghezza. |
| [ResizeProportional](../../aspose.imaging.fileformats.tiff/tiffimage/resizeproportional)(int, int, ResizeType) | Esegue il ridimensionamento proporzionale sull'immagine. Il ridimensionamento proporzionale ridimensionerà ogni fotogramma in base al rapporto di*newWidth*/larghezza e*newHeight* /altezza. |
| [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int) | Ridimensiona proporzionalmente la larghezza. Il predefinitoNearestNeighbourResample viene utilizzato. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int, ImageResizeSettings) | Ridimensiona proporzionalmente la larghezza. |
| override [ResizeWidthProportionally](../../aspose.imaging.fileformats.tiff/tiffimage/resizewidthproportionally#resizewidthproportionally_2)(int, ResizeType) | Ridimensiona proporzionalmente la larghezza. |
| virtual [Rotate](../../aspose.imaging/rasterimage/rotate)(float) | Ruota l'immagine attorno al centro. |
| override [Rotate](../../aspose.imaging.fileformats.tiff/tiffimage/rotate#rotate_1)(float, bool, Color) | Ruota l'immagine attorno al centro. |
| override [RotateFlip](../../aspose.imaging.fileformats.tiff/tiffimage/rotateflip)(RotateFlipType) | Ruota, capovolge o ruota e capovolge solo il fotogramma attivo. |
| [Save](../../aspose.imaging/image/save)() | Salva i dati dell'immagine nel flusso sottostante. |
| [Save](../../aspose.imaging/datastreamsupporter/save)(Stream) | Salva i dati dell'oggetto nel flusso specificato. |
| override [Save](../../aspose.imaging/image/save)(string) | Salva l'immagine nella posizione del file specificata. |
| [Save](../../aspose.imaging/image/save)(Stream, ImageOptionsBase) | Salva i dati dell'immagine nel flusso specificato nel formato file specificato in base alle opzioni di salvataggio. |
| virtual [Save](../../aspose.imaging/datastreamsupporter/save)(string, bool) | Salva i dati dell'oggetto nella posizione del file specificata. |
| virtual [Save](../../aspose.imaging/image/save)(string, ImageOptionsBase) | Salva i dati dell'oggetto nel percorso file specificato nel formato file specificato in base alle opzioni di salvataggio. |
| override [Save](../../aspose.imaging/rasterimage/save)(Stream, ImageOptionsBase, Rectangle) | Salva i dati dell'immagine nel flusso specificato nel formato file specificato in base alle opzioni di salvataggio. |
| virtual [Save](../../aspose.imaging/image/save)(string, ImageOptionsBase, Rectangle) | Salva i dati dell'oggetto nel percorso file specificato nel formato file specificato in base alle opzioni di salvataggio. |
| [SaveArgb32Pixels](../../aspose.imaging/rasterimage/saveargb32pixels)(Rectangle, int[]) | Salva i pixel ARGB a 32 bit. |
| [SaveCmyk32Pixels](../../aspose.imaging/rasterimage/savecmyk32pixels)(Rectangle, int[]) | Salva i pixel. |
| [SavePixels](../../aspose.imaging/rasterimage/savepixels)(Rectangle, Color[]) | Salva i pixel. |
| [SaveRawData](../../aspose.imaging/rasterimage/saverawdata)(byte[], int, Rectangle, RawDataSettings) | Salva i dati grezzi. |
| [SetArgb32Pixel](../../aspose.imaging/rasterimage/setargb32pixel)(int, int, int) | Imposta un pixel ARGB a 32 bit dell'immagine per la posizione specificata. |
| override [SetPalette](../../aspose.imaging/rasterimage/setpalette)(IColorPalette, bool) | Imposta la tavolozza dell'immagine. |
| [SetPixel](../../aspose.imaging/rasterimage/setpixel)(int, int, Color) | Imposta un pixel dell'immagine per la posizione specificata. |
| override [SetResolution](../../aspose.imaging.fileformats.tiff/tiffimage/setresolution)(double, double) | Imposta la risoluzione per questo[`RasterImage`](../../aspose.imaging/rasterimage) . |
| virtual [ToBitmap](../../aspose.imaging/rasterimage/tobitmap)() | Converte l'immagine raster in bitmap. |
| [WriteArgb32ScanLine](../../aspose.imaging/rasterimage/writeargb32scanline)(int, int[]) | Scrive l'intera linea di scansione nell'indice della linea di scansione specificato. |
| [WriteScanLine](../../aspose.imaging/rasterimage/writescanline)(int, Color[]) | Scrive l'intera linea di scansione nell'indice della linea di scansione specificato. |

### Esempi

Crea percorso grafico dalle risorse del percorso nell'immagine TIFF.

```csharp
[C#]

using (var image = (TiffImage)Image.Load("Bottle.tif"))
{
    // Crea il GraphicsPath usando PathResources dall'immagine TIFF
    var graphicsPath = PathResourceConverter.ToGraphicsPath(image.ActiveFrame.PathResources.ToArray(), image.ActiveFrame.Size);
    var graphics = new Graphics(image);

    // Disegna una linea rossa e salva l'immagine
    graphics.DrawPath(new Pen(Color.Red, 10), graphicsPath);
    image.Save("BottleWithRedBorder.tif");
}
```

Crea risorse di percorso usando il percorso grafico.

```csharp
[C#]

static void Main(string[] args)
{
    using (var image = (TiffImage)Image.Load("Bottle.tif"))
    {
        // Crea una figura rettangolare per GraphicsPath
        var figure = new Figure();
        figure.AddShape(CreateBezierShape(100f, 100f, 500f, 100f, 500f, 1000f, 100f, 1000f));

        // Crea GraphicsPath usando la nostra figura
        var graphicsPath = new GraphicsPath();
        graphicsPath.AddFigure(figure);

        // Imposta PathResources usando GraphicsPath
        var pathResouze = PathResourceConverter.FromGraphicsPath(graphicsPath, image.Size);
        image.ActiveFrame.PathResources = new List<PathResource>(pathResouze);

        // Salva l'immagine
        image.Save("BottleWithRectanglePath.tif");
    }
}

private static BezierShape CreateBezierShape(params float[] coordinates)
{
    var bezierPoints = CoordinatesToBezierPoints(coordinates).ToArray();
    return new BezierShape(bezierPoints, true);
}

private static IEnumerable<PointF> CoordinatesToBezierPoints(float[] coordinates)
{
    for (var coordinateIndex = 0; coordinateIndex < coordinates.Length; coordinateIndex += 2)
        for (var index = 0; index < 3; index++)
            yield return new PointF(coordinates[coordinateIndex], coordinates[coordinateIndex + 1]);
}
```

### Guarda anche

* class [RasterCachedMultipageImage](../../aspose.imaging/rastercachedmultipageimage)
* interface [IMultipageImageExt](../../aspose.imaging/imultipageimageext)
* spazio dei nomi [Aspose.Imaging.FileFormats.Tiff](../../aspose.imaging.fileformats.tiff)
* assemblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
