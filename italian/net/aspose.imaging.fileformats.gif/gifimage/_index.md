---
title: GifImage
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Unimmagine gif.
type: docs
weight: 6700
url: /it/net/aspose.imaging.fileformats.gif/gifimage/
---
## GifImage class

Un'immagine gif.

```csharp
public sealed class GifImage : RasterCachedMultipageImage, IMultipageImageExt
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [GifImage](gifimage#constructor)(GifFrameBlock) | Inizializza una nuova istanza di[`GifImage`](../gifimage) classe. |
| [GifImage](gifimage#constructor_1)(GifFrameBlock, IColorPalette) | Inizializza una nuova istanza di[`GifImage`](../gifimage) classe. |
| [GifImage](gifimage#constructor_2)(GifFrameBlock, IColorPalette, bool, byte, byte, byte, bool) | Inizializza una nuova istanza di[`GifImage`](../gifimage) classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [ActiveFrame](../../aspose.imaging.fileformats.gif/gifimage/activeframe) { get; set; } | Ottiene o imposta il frame attivo. |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette) { get; set; } | Ottiene o imposta un valore che indica se regolare automaticamente la tavolozza. |
| override [BackgroundColor](../../aspose.imaging.fileformats.gif/gifimage/backgroundcolor) { get; set; } | Ottiene o imposta il colore di sfondo. |
| [BackgroundColorIndex](../../aspose.imaging.fileformats.gif/gifimage/backgroundcolorindex) { get; set; } | Ottiene o imposta l'indice del colore di sfondo. |
| override [BitsPerPixel](../../aspose.imaging/rastercachedmultipageimage/bitsperpixel) { get; } | Ottiene il numero di bit dell'immagine per pixel. |
| [Blocks](../../aspose.imaging.fileformats.gif/gifimage/blocks) { get; } | Ottiene i blocchi GIF. |
| [Bounds](../../aspose.imaging/image/bounds) { get; } | Ottiene i limiti dell'immagine. |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint) { get; set; } | Ottiene o imposta l'hint per la dimensione del buffer che è la dimensione massima consentita per tutti i buffer interni. |
| [Container](../../aspose.imaging/image/container) { get; } | Ottiene il[`Image`](../../aspose.imaging/image) contenitore. |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer) { get; } | Ottiene il flusso di dati dell'oggetto. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Ottiene un valore che indica se questa istanza è stata eliminata. |
| override [FileFormat](../../aspose.imaging.fileformats.gif/gifimage/fileformat) { get; } | Ottiene un valore di formato file |
| override [HasAlpha](../../aspose.imaging/rastercachedmultipageimage/hasalpha) { get; } | Ottiene un valore che indica se questa istanza ha alpha. |
| override [HasBackgroundColor](../../aspose.imaging.fileformats.gif/gifimage/hasbackgroundcolor) { get; } | Ottiene un valore che indica se l'immagine ha il colore di sfondo. |
| [HasTrailer](../../aspose.imaging.fileformats.gif/gifimage/hastrailer) { get; set; } | Ottiene o imposta un valore che indica se GIF ha trailer. |
| override [HasTransparentColor](../../aspose.imaging.fileformats.gif/gifimage/hastransparentcolor) { get; set; } | Ottiene un valore che indica se la cornice attiva ha un colore trasparente. |
| override [Height](../../aspose.imaging/rastercachedmultipageimage/height) { get; } | Ottiene l'altezza dell'immagine. |
| virtual [HorizontalResolution](../../aspose.imaging/rasterimage/horizontalresolution) { get; set; } | Ottiene o imposta la risoluzione orizzontale, in pixel per pollice, di questo[`RasterImage`](../../aspose.imaging/rasterimage) . |
| override [ImageOpacity](../../aspose.imaging.fileformats.gif/gifimage/imageopacity) { get; } | Ottiene l'opacità di questa immagine (frame attivo). |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor) { get; set; } | Ottiene o imposta il monitor di interruzione. |
| [IsCached](../../aspose.imaging/rastercachedmultipageimage/iscached) { get; } | Ottiene un valore che indica se i dati dell'immagine sono attualmente memorizzati nella cache. |
| [IsInterlaced](../../aspose.imaging.fileformats.gif/gifimage/isinterlaced) { get; } | Ottiene un valore che indica se questa istanza dell'immagine è interlacciata. |
| [IsPaletteSorted](../../aspose.imaging.fileformats.gif/gifimage/ispalettesorted) { get; set; } | Ottiene o imposta un valore che indica se la tavolozza è ordinata. |
| [IsRawDataAvailable](../../aspose.imaging/rasterimage/israwdataavailable) { get; } | Ottiene un valore che indica se è disponibile il caricamento dei dati grezzi. |
| [LoopsCount](../../aspose.imaging.fileformats.gif/gifimage/loopscount) { get; set; } | Ottiene il conteggio dei loop (se l'immagine gif contiene informazioni sui loop) |
| override [PageCount](../../aspose.imaging.fileformats.gif/gifimage/pagecount) { get; } | Ottiene il conteggio delle pagine. |
| override [PageExportingAction](../../aspose.imaging.fileformats.gif/gifimage/pageexportingaction) { get; set; } | Ottiene o imposta l'azione di esportazione della pagina. Tieni presente che l'impostazione di questo metodo rilascerà automaticamente le risorse della pagina dopo l'esecuzione. Verrà eseguito appena prima del salvataggio di ogni pagina. |
| override [Pages](../../aspose.imaging.fileformats.gif/gifimage/pages) { get; } | Ottiene le pagine. |
| [Palette](../../aspose.imaging/image/palette) { get; set; } | Ottiene o imposta la tavolozza dei colori. La tavolozza dei colori non viene utilizzata quando i pixel sono rappresentati direttamente. |
| [PaletteColorResolutionBits](../../aspose.imaging.fileformats.gif/gifimage/palettecolorresolutionbits) { get; set; } | Ottiene o imposta i bit di risoluzione del colore della tavolozza. |
| [PixelAspectRatio](../../aspose.imaging.fileformats.gif/gifimage/pixelaspectratio) { get; set; } | Ottiene o imposta le proporzioni dei pixel. |
| virtual [PremultiplyComponents](../../aspose.imaging/rasterimage/premultiplycomponents) { get; set; } | Ottiene o imposta un valore che indica se i componenti dell'immagine devono essere premoltiplicati. |
| [RawCustomColorConverter](../../aspose.imaging/rasterimage/rawcustomcolorconverter) { get; set; } | Ottiene o imposta il convertitore colore personalizzato |
| virtual [RawDataFormat](../../aspose.imaging/rasterimage/rawdataformat) { get; } | Ottiene il formato dei dati grezzi. |
| [RawDataSettings](../../aspose.imaging/rasterimage/rawdatasettings) { get; } | Ottiene le impostazioni dei dati grezzi correnti. Nota quando si utilizzano queste impostazioni i dati vengono caricati senza conversione. |
| [RawFallbackIndex](../../aspose.imaging/rasterimage/rawfallbackindex) { get; set; } | Ottiene o imposta l'indice di fallback da utilizzare quando l'indice della tavolozza è fuori dai limiti |
| [RawIndexedColorConverter](../../aspose.imaging/rasterimage/rawindexedcolorconverter) { get; set; } | Ottiene o imposta il convertitore colore indicizzato |
| virtual [RawLineSize](../../aspose.imaging/rasterimage/rawlinesize) { get; } | Ottiene la dimensione della riga grezza in byte. |
| [Size](../../aspose.imaging/image/size) { get; } | Ottiene la dimensione dell'immagine. |
| override [TransparentColor](../../aspose.imaging.fileformats.gif/gifimage/transparentcolor) { get; } | Ottiene il colore trasparente della cornice attiva. |
| virtual [UpdateXmpData](../../aspose.imaging/rasterimage/updatexmpdata) { get; set; } | Ottiene o imposta un valore che indica se aggiornare i metadati XMP. |
| override [UsePalette](../../aspose.imaging/rasterimage/usepalette) { get; } | Ottiene un valore che indica se viene utilizzata la tavolozza dell'immagine. |
| virtual [UseRawData](../../aspose.imaging/rasterimage/userawdata) { get; set; } | Ottiene o imposta un valore che indica se utilizzare il caricamento dei dati grezzi quando è disponibile il caricamento dei dati grezzi. |
| virtual [VerticalResolution](../../aspose.imaging/rasterimage/verticalresolution) { get; set; } | Ottiene o imposta la risoluzione verticale, in pixel per pollice, di questo[`RasterImage`](../../aspose.imaging/rasterimage) . |
| override [Width](../../aspose.imaging/rastercachedmultipageimage/width) { get; } | Ottiene la larghezza dell'immagine. |
| override [XmpData](../../aspose.imaging.fileformats.gif/gifimage/xmpdata) { get; set; } | Ottiene o imposta i metadati XMP. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AddBlock](../../aspose.imaging.fileformats.gif/gifimage/addblock)(IGifBlock) | Aggiunge un nuovo blocco GIF. |
| [AddPage](../../aspose.imaging.fileformats.gif/gifimage/addpage)(RasterImage) | Aggiunge la pagina all'immagine. |
| override [AdjustBrightness](../../aspose.imaging.fileformats.gif/gifimage/adjustbrightness)(int) | Regolazione di a*brightness* per immagine. |
| override [AdjustContrast](../../aspose.imaging.fileformats.gif/gifimage/adjustcontrast)(float) | Regola il contrasto. |
| override [AdjustGamma](../../aspose.imaging.fileformats.gif/gifimage/adjustgamma#adjustgamma)(float) | Correzione gamma di un'immagine. |
| override [AdjustGamma](../../aspose.imaging.fileformats.gif/gifimage/adjustgamma#adjustgamma_1)(float, float, float) | Correzione gamma di un'immagine. |
| override [BinarizeBradley](../../aspose.imaging.fileformats.gif/gifimage/binarizebradley#binarizebradley)(double) | Binarizzazione di un'immagine utilizzando l'algoritmo di soglia adattivo di Bradley utilizzando la soglia di immagine integrale |
| override [BinarizeBradley](../../aspose.imaging/rastercachedmultipageimage/binarizebradley)(double, int) | Binarizzazione di un'immagine utilizzando l'algoritmo di soglia adattivo di Bradley utilizzando la soglia di immagine integrale |
| override [BinarizeFixed](../../aspose.imaging.fileformats.gif/gifimage/binarizefixed)(byte) | Binarizzazione di un'immagine con soglia predefinita |
| override [BinarizeOtsu](../../aspose.imaging.fileformats.gif/gifimage/binarizeotsu)() | Binarizzazione di un'immagine con soglia Otsu |
| override [CacheData](../../aspose.imaging/rastercachedmultipageimage/cachedata)() | Memorizza nella cache i dati privati. |
| [CanSave](../../aspose.imaging/image/cansave)(ImageOptionsBase) | Determina se l'immagine può essere salvata nel formato file specificato rappresentato dalle opzioni di salvataggio passate. |
| [ClearBlocks](../../aspose.imaging.fileformats.gif/gifimage/clearblocks)() | Cancella tutti i blocchi GIF. |
| override [Crop](../../aspose.imaging.fileformats.gif/gifimage/crop#crop)(Rectangle) | Ritaglio dell'immagine. |
| override [Crop](../../aspose.imaging/rastercachedmultipageimage/crop)(int, int, int, int) | Ritaglia immagine con spostamenti. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Elimina l'istanza corrente. |
| [Dither](../../aspose.imaging/rasterimage/dither)(DitheringMethod, int) | Esegue il dithering sull'immagine corrente. |
| override [Dither](../../aspose.imaging.fileformats.gif/gifimage/dither#dither_1)(DitheringMethod, int, IColorPalette) | Esegue il dithering sull'immagine corrente. |
| override [Filter](../../aspose.imaging.fileformats.gif/gifimage/filter)(Rectangle, FilterOptionsBase) | Filtra il rettangolo specificato. |
| [GetArgb32Pixel](../../aspose.imaging/rasterimage/getargb32pixel)(int, int) | Ottiene un'immagine ARGB pixel a 32 bit. |
| [GetDefaultArgb32Pixels](../../aspose.imaging/rasterimage/getdefaultargb32pixels)(Rectangle) | Ottiene l'array di pixel ARGB a 32 bit predefinito. |
| virtual [GetDefaultOptions](../../aspose.imaging/image/getdefaultoptions)(object[]) | Ottiene le opzioni predefinite. |
| [GetDefaultPixels](../../aspose.imaging/rasterimage/getdefaultpixels)(Rectangle, IPartialArgb32PixelLoader) | Ottiene l'array di pixel predefinito utilizzando il caricatore di pixel parziale. |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata)(Rectangle, RawDataSettings) | Ottiene l'array di dati grezzi predefinito. |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata)(Rectangle, IPartialRawDataLoader, RawDataSettings) | Ottiene l'array di dati grezzi predefinito utilizzando il caricatore di pixel parziale. |
| virtual [GetModifyDate](../../aspose.imaging/rasterimage/getmodifydate)(bool) | Ottiene la data e l'ora dell'ultima modifica dell'immagine della risorsa. |
| override [GetOriginalOptions](../../aspose.imaging.fileformats.gif/gifimage/getoriginaloptions)() | Ottiene le opzioni in base alle impostazioni del file originale. Questo può essere utile per mantenere invariati la profondità di bit e altri parametri dell'immagine originale. Ad esempio, se carichiamo un'immagine PNG in bianco e nero con 1 bit per pixel e quindi salvalo usando il [`Save`](../../aspose.imaging/datastreamsupporter/save) metodo, verrà prodotta l'immagine PNG di output con 8 bit per pixel. Per evitarlo e salvare l'immagine PNG con 1 bit per pixel, utilizzare questo metodo per ottenere le opzioni di salvataggio corrispondenti e passarle al[`Save`](../../aspose.imaging/image/save) metodo come secondo parametro. |
| [GetPixel](../../aspose.imaging/rasterimage/getpixel)(int, int) | Ottiene un pixel dell'immagine. |
| [GetSkewAngle](../../aspose.imaging/rasterimage/getskewangle)() | Ottiene l'angolo di inclinazione. Questo metodo è applicabile ai documenti di testo scansionati, per determinare l'angolo di inclinazione durante la scansione. |
| override [Grayscale](../../aspose.imaging.fileformats.gif/gifimage/grayscale)() | Trasformazione di un'immagine nella sua rappresentazione in scala di grigi |
| [InsertBlock](../../aspose.imaging.fileformats.gif/gifimage/insertblock)(int, IGifBlock) | Aggiunge un nuovo blocco GIF. |
| [LoadArgb32Pixels](../../aspose.imaging/rasterimage/loadargb32pixels)(Rectangle) | Carica pixel ARGB a 32 bit. |
| [LoadArgb64Pixels](../../aspose.imaging/rasterimage/loadargb64pixels)(Rectangle) | Carica pixel ARGB a 64 bit. |
| [LoadCmyk32Pixels](../../aspose.imaging/rasterimage/loadcmyk32pixels)(Rectangle) | Carica i pixel in formato CMYK. |
| [LoadPartialArgb32Pixels](../../aspose.imaging/rasterimage/loadpartialargb32pixels)(Rectangle, IPartialArgb32PixelLoader) | Carica i pixel ARGB a 32 bit parzialmente per pacchetti. |
| [LoadPartialPixels](../../aspose.imaging/rasterimage/loadpartialpixels)(Rectangle, IPartialPixelLoader) | Carica i pixel parzialmente per pacchetti. |
| [LoadPixels](../../aspose.imaging/rasterimage/loadpixels)(Rectangle) | Carica pixel. |
| [LoadRawData](../../aspose.imaging/rasterimage/loadrawdata)(Rectangle, RawDataSettings, IPartialRawDataLoader) | Carica dati grezzi. |
| [LoadRawData](../../aspose.imaging/rasterimage/loadrawdata)(Rectangle, Rectangle, RawDataSettings, IPartialRawDataLoader) | Carica dati grezzi. |
| [NormalizeAngle](../../aspose.imaging/rasterimage/normalizeangle)() | Normalizza l'angolo. Questo metodo è applicabile ai documenti di testo scansionati per eliminare la scansione obliqua. Questo metodo utilizza[`GetSkewAngle`](../../aspose.imaging/rasterimage/getskewangle) e[`Rotate`](../../aspose.imaging/rasterimage/rotate) metodi. |
| override [NormalizeAngle](../../aspose.imaging/rastercachedmultipageimage/normalizeangle)(bool, Color) | Normalizza l'angolo. Questo metodo è applicabile ai documenti di testo scansionati per eliminare la scansione obliqua. Questo metodo utilizza!:GetSkewAngle e[`Rotate`](../../aspose.imaging/rastercachedmultipageimage/rotate) metodi. |
| [OrderBlocks](../../aspose.imaging.fileformats.gif/gifimage/orderblocks)() | Ordina i blocchi GIF in base alla specifica GIF. Alcuni[`GifGraphicsControlBlock`](../../aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock) può essere rimosso per un layout GIF corretto. |
| [ReadArgb32ScanLine](../../aspose.imaging/rasterimage/readargb32scanline)(int) | Legge l'intera linea di scansione in base all'indice della linea di scansione specificato. |
| [ReadScanLine](../../aspose.imaging/rasterimage/readscanline)(int) | Legge l'intera linea di scansione in base all'indice della linea di scansione specificato. |
| [RemoveBlock](../../aspose.imaging.fileformats.gif/gifimage/removeblock)(IGifBlock) | Rimuove il blocco GIF. |
| [ReplaceColor](../../aspose.imaging/rasterimage/replacecolor)(Color, byte, Color) | Sostituisce un colore con un altro con la differenza consentita e conserva il valore alfa originale per salvare i bordi smussati. |
| override [ReplaceColor](../../aspose.imaging/rastercachedmultipageimage/replacecolor)(int, byte, int) | Sostituisce un colore con un altro con la differenza consentita e conserva il valore alfa originale per salvare i bordi smussati. |
| [ReplaceNonTransparentColors](../../aspose.imaging/rasterimage/replacenontransparentcolors)(Color) | Sostituisce tutti i colori non trasparenti con un nuovo colore e conserva il valore alfa originale per salvare i bordi smussati. Nota: se lo usi su immagini senza trasparenza, tutti i colori verranno sostituiti con uno solo. |
| override [ReplaceNonTransparentColors](../../aspose.imaging/rastercachedmultipageimage/replacenontransparentcolors)(int) | Sostituisce tutti i colori non trasparenti con un nuovo colore e conserva il valore alfa originale per salvare i bordi smussati. Nota: se lo usi su immagini senza trasparenza, tutti i colori verranno sostituiti con uno solo. |
| [Resize](../../aspose.imaging/image/resize)(int, int) | Ridimensiona l'immagine. Il predefinitoNearestNeighbourResample viene utilizzato. |
| override [Resize](../../aspose.imaging.fileformats.gif/gifimage/resize#resize_1)(int, int, ImageResizeSettings) | Ridimensiona l'immagine. |
| override [Resize](../../aspose.imaging.fileformats.gif/gifimage/resize#resize_2)(int, int, ResizeType) | Ridimensiona l'immagine. |
| [ResizeFullFrame](../../aspose.imaging.fileformats.gif/gifimage/resizefullframe)(int, int, ResizeType) | Ridimensiona l'immagine utilizzando fotogrammi interi per ogni pagina GIF. Necessario per evitare la comparsa di possibili artefatti. |
| [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int) | Ridimensiona proporzionalmente l'altezza. Il predefinitoNearestNeighbourResample viene utilizzato. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int, ImageResizeSettings) | Ridimensiona proporzionalmente l'altezza. |
| override [ResizeHeightProportionally](../../aspose.imaging/rastercachedmultipageimage/resizeheightproportionally)(int, ResizeType) | Ridimensiona proporzionalmente la larghezza. |
| [ResizeProportional](../../aspose.imaging.fileformats.gif/gifimage/resizeproportional)(int, int, ResizeType) | Esegue il ridimensionamento proporzionale sull'immagine. Il ridimensionamento proporzionale ridimensionerà ogni fotogramma in base al rapporto di*newWidth*/larghezza e*newHeight* /altezza. |
| [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int) | Ridimensiona proporzionalmente la larghezza. Il predefinitoNearestNeighbourResample viene utilizzato. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int, ImageResizeSettings) | Ridimensiona proporzionalmente la larghezza. |
| override [ResizeWidthProportionally](../../aspose.imaging/rastercachedmultipageimage/resizewidthproportionally)(int, ResizeType) | Ridimensiona proporzionalmente la larghezza. |
| virtual [Rotate](../../aspose.imaging/rasterimage/rotate)(float) | Ruota l'immagine attorno al centro. |
| override [Rotate](../../aspose.imaging.fileformats.gif/gifimage/rotate#rotate_1)(float, bool, Color) | !:RasterCahcedMultipageImage.Rotate immagine intorno al centro. |
| override [RotateFlip](../../aspose.imaging.fileformats.gif/gifimage/rotateflip)(RotateFlipType) | Ruota, capovolge o ruota e capovolge solo il fotogramma attivo. |
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
| [SetFrameTime](../../aspose.imaging.fileformats.gif/gifimage/setframetime)(ushort) | Imposta la durata di tutti i frame in millisecondi. La modifica di questo valore azzererà il ritardo per tutti i frame. |
| override [SetPalette](../../aspose.imaging/rasterimage/setpalette)(IColorPalette, bool) | Imposta la tavolozza dell'immagine. |
| [SetPixel](../../aspose.imaging/rasterimage/setpixel)(int, int, Color) | Imposta un pixel dell'immagine per la posizione specificata. |
| virtual [SetResolution](../../aspose.imaging/rasterimage/setresolution)(double, double) | Imposta la risoluzione per questo[`RasterImage`](../../aspose.imaging/rasterimage) . |
| virtual [ToBitmap](../../aspose.imaging/rasterimage/tobitmap)() | Converte l'immagine raster in bitmap. |
| [WriteArgb32ScanLine](../../aspose.imaging/rasterimage/writeargb32scanline)(int, int[]) | Scrive l'intera linea di scansione nell'indice della linea di scansione specificato. |
| [WriteScanLine](../../aspose.imaging/rasterimage/writescanline)(int, Color[]) | Scrive l'intera linea di scansione nell'indice della linea di scansione specificato. |

### Esempi

Esportazione di parte dell'animazione dall'immagine GIF in base all'intervallo di tempo.

```csharp
[C#]

using (var image = Image.Load("Animation.gif"))
{
    var options = new GifOptions
    {
        FullFrame = true,
        MultiPageOptions = new MultiPageOptions
        {
            Mode = MultiPageMode.TimeInterval,
            TimeInterval = new TimeInterval(0, 400)
        }
    };

    image.Save("PartOfAnimation.gif", options);
}
```

Questo esempio mostra come creare un'immagine GIF e salvarla in un file.

```csharp
[C#]

string dir = "c:\\temp\\";

// Crea un blocco GIF Frame di 100x100 px.
using (Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock firstBlock = new Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock(100, 100))
{
    // Riempi di rosso l'intero blocco.
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(firstBlock);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    gr.FillRectangle(brush, firstBlock.Bounds);

    using (Aspose.Imaging.FileFormats.Gif.GifImage gifImage = new Aspose.Imaging.FileFormats.Gif.GifImage(firstBlock))
    {
        gifImage.Save(dir + "output.gif");
    }
}
```

Crea immagini GIF multipagina utilizzando immagini raster a pagina singola.

```csharp
[C#]

static void Main(string[] args)
{
    // Carica fotogrammi
    var frames = LoadFrames("Animation frames").ToArray();

    // Crea un'immagine GIF usando il primo fotogramma
    using (var image = new GifImage(new GifFrameBlock(frames[0])))
    {
        // Aggiungi cornici all'immagine GIF usando il metodo AddPage
        for (var index = 1; index < frames.Length; index++)
        {
            image.AddPage(frames[index]);
        }

        // Salva l'immagine GIF
        image.Save("Multipage.gif");
    }
}

private static IEnumerable<RasterImage> LoadFrames(string directory)
{
    foreach (var filePath in Directory.GetFiles(directory))
    {
        yield return (RasterImage)Image.Load(filePath);
    }
}
```

### Guarda anche

* class [RasterCachedMultipageImage](../../aspose.imaging/rastercachedmultipageimage)
* interface [IMultipageImageExt](../../aspose.imaging/imultipageimageext)
* spazio dei nomi [Aspose.Imaging.FileFormats.Gif](../../aspose.imaging.fileformats.gif)
* assemblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
