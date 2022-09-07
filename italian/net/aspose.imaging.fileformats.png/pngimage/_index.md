---
title: PngImage
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: La nuova immagine png.
type: docs
weight: 7450
url: /it/net/aspose.imaging.fileformats.png/pngimage/
---
## PngImage class

La nuova immagine png.

```csharp
public class PngImage : RasterCachedImage
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [PngImage](pngimage#constructor_1)(RasterImage) | Inizializza una nuova istanza di[`PngImage`](../pngimage) classe. |
| [PngImage](pngimage#constructor_5)(Stream) | Inizializza una nuova istanza di[`PngImage`](../pngimage) classe. |
| [PngImage](pngimage#constructor_6)(string) | Inizializza una nuova istanza di[`PngImage`](../pngimage) classe. |
| [PngImage](pngimage#constructor_3)(int, int) | Inizializza una nuova istanza di[`PngImage`](../pngimage) classe. |
| [PngImage](pngimage#constructor_2)(RasterImage, PngColorType) | Inizializza una nuova istanza di[`PngImage`](../pngimage) classe. |
| [PngImage](pngimage#constructor_7)(string, PngColorType) | Inizializza una nuova istanza di[`PngImage`](../pngimage) classe. |
| [PngImage](pngimage#constructor_4)(int, int, PngColorType) | Inizializza una nuova istanza di[`PngImage`](../pngimage) classe. |
| [PngImage](pngimage#constructor)(PngOptions, int, int) | Inizializza una nuova istanza di[`PngImage`](../pngimage) classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette) { get; set; } | Ottiene o imposta un valore che indica se regolare automaticamente la tavolozza. |
| override [BackgroundColor](../../aspose.imaging.fileformats.png/pngimage/backgroundcolor) { get; set; } | Ottiene il colore di sfondo. |
| override [BitsPerPixel](../../aspose.imaging.fileformats.png/pngimage/bitsperpixel) { get; } | Ottiene i bit per pixel. |
| [Bounds](../../aspose.imaging/image/bounds) { get; } | Ottiene i limiti dell'immagine. |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint) { get; set; } | Ottiene o imposta l'hint per la dimensione del buffer che è la dimensione massima consentita per tutti i buffer interni. |
| [Container](../../aspose.imaging/image/container) { get; } | Ottiene il[`Image`](../../aspose.imaging/image) contenitore. |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer) { get; } | Ottiene il flusso di dati dell'oggetto. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Ottiene un valore che indica se questa istanza è stata eliminata. |
| override [FileFormat](../../aspose.imaging.fileformats.png/pngimage/fileformat) { get; } | Ottiene un valore di formato file |
| override [HasAlpha](../../aspose.imaging.fileformats.png/pngimage/hasalpha) { get; } | Ottieni un valore che indica se questa istanza ha alpha. |
| override [HasBackgroundColor](../../aspose.imaging.fileformats.png/pngimage/hasbackgroundcolor) { get; set; } | Ottiene un valore che indica se ha il colore di sfondo. |
| override [HasTransparentColor](../../aspose.imaging.fileformats.png/pngimage/hastransparentcolor) { get; set; } | Ottiene un valore che indica se l'immagine ha un colore trasparente. |
| override [Height](../../aspose.imaging.fileformats.png/pngimage/height) { get; } | Ottiene l'altezza. |
| override [HorizontalResolution](../../aspose.imaging.fileformats.png/pngimage/horizontalresolution) { get; set; } | Ottiene o imposta la risoluzione orizzontale. |
| virtual [ImageOpacity](../../aspose.imaging/rasterimage/imageopacity) { get; } | Ottiene l'opacità di questa immagine. |
| [Interlaced](../../aspose.imaging.fileformats.png/pngimage/interlaced) { get; } | Ottiene un valore che indica se questo[`PngImage`](../pngimage) è intrecciato. |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor) { get; set; } | Ottiene o imposta il monitor di interruzione. |
| override [IsCached](../../aspose.imaging/rastercachedimage/iscached) { get; } | Ottiene un valore che indica se i dati dell'immagine sono attualmente memorizzati nella cache. |
| [IsInterlaced](../../aspose.imaging.fileformats.png/pngimage/isinterlaced) { get; } | Ottiene un valore che indica se questa istanza dell'immagine è interlacciata. |
| [IsRawDataAvailable](../../aspose.imaging/rasterimage/israwdataavailable) { get; } | Ottiene un valore che indica se è disponibile il caricamento dei dati grezzi. |
| [Palette](../../aspose.imaging/image/palette) { get; set; } | Ottiene o imposta la tavolozza dei colori. La tavolozza dei colori non viene utilizzata quando i pixel sono rappresentati direttamente. |
| virtual [PremultiplyComponents](../../aspose.imaging/rasterimage/premultiplycomponents) { get; set; } | Ottiene o imposta un valore che indica se i componenti dell'immagine devono essere premoltiplicati. |
| [RawCustomColorConverter](../../aspose.imaging/rasterimage/rawcustomcolorconverter) { get; set; } | Ottiene o imposta il convertitore colore personalizzato |
| override [RawDataFormat](../../aspose.imaging.fileformats.png/pngimage/rawdataformat) { get; } | Ottiene il formato dei dati grezzi. |
| [RawDataSettings](../../aspose.imaging/rasterimage/rawdatasettings) { get; } | Ottiene le impostazioni dei dati grezzi correnti. Nota quando si utilizzano queste impostazioni i dati vengono caricati senza conversione. |
| [RawFallbackIndex](../../aspose.imaging/rasterimage/rawfallbackindex) { get; set; } | Ottiene o imposta l'indice di fallback da utilizzare quando l'indice della tavolozza è fuori dai limiti |
| [RawIndexedColorConverter](../../aspose.imaging/rasterimage/rawindexedcolorconverter) { get; set; } | Ottiene o imposta il convertitore colore indicizzato |
| virtual [RawLineSize](../../aspose.imaging/rasterimage/rawlinesize) { get; } | Ottiene la dimensione della riga grezza in byte. |
| [Size](../../aspose.imaging/image/size) { get; } | Ottiene la dimensione dell'immagine. |
| override [TransparentColor](../../aspose.imaging.fileformats.png/pngimage/transparentcolor) { get; set; } | Ottiene il colore trasparente. |
| virtual [UpdateXmpData](../../aspose.imaging/rasterimage/updatexmpdata) { get; set; } | Ottiene o imposta un valore che indica se aggiornare i metadati XMP. |
| override [UsePalette](../../aspose.imaging/rasterimage/usepalette) { get; } | Ottiene un valore che indica se viene utilizzata la tavolozza dell'immagine. |
| virtual [UseRawData](../../aspose.imaging/rasterimage/userawdata) { get; set; } | Ottiene o imposta un valore che indica se utilizzare il caricamento dei dati grezzi quando è disponibile il caricamento dei dati grezzi. |
| override [VerticalResolution](../../aspose.imaging.fileformats.png/pngimage/verticalresolution) { get; set; } | Ottiene o imposta la risoluzione verticale. |
| override [Width](../../aspose.imaging.fileformats.png/pngimage/width) { get; } | Ottiene la larghezza. |
| override [XmpData](../../aspose.imaging.fileformats.png/pngimage/xmpdata) { get; set; } | Ottiene o imposta i metadati XMP. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [AdjustBrightness](../../aspose.imaging/rastercachedimage/adjustbrightness)(int) | Regolazione di una luminosità per l'immagine. |
| override [AdjustContrast](../../aspose.imaging/rastercachedimage/adjustcontrast)(float) | Immagine in contrasto |
| override [AdjustGamma](../../aspose.imaging/rastercachedimage/adjustgamma)(float) | Correzione gamma di un'immagine. |
| override [AdjustGamma](../../aspose.imaging/rastercachedimage/adjustgamma)(float, float, float) | Correzione gamma di un'immagine. |
| override [BinarizeBradley](../../aspose.imaging/rastercachedimage/binarizebradley)(double) | Binarizzazione di un'immagine utilizzando l'algoritmo di soglia adattivo di Bradley utilizzando la soglia di immagine integrale |
| override [BinarizeBradley](../../aspose.imaging/rastercachedimage/binarizebradley)(double, int) | Binarizzazione di un'immagine utilizzando l'algoritmo di soglia adattivo di Bradley utilizzando la soglia di immagine integrale |
| override [BinarizeFixed](../../aspose.imaging/rastercachedimage/binarizefixed)(byte) | Binarizzazione di un'immagine con soglia predefinita |
| override [BinarizeOtsu](../../aspose.imaging/rastercachedimage/binarizeotsu)() | Binarizzazione di un'immagine con soglia Otsu |
| override [CacheData](../../aspose.imaging/rastercachedimage/cachedata)() | Memorizza i dati nella cache e garantisce che nessun ulteriore caricamento dei dati venga eseguito dal sottostante[`DataStreamContainer`](../../aspose.imaging/datastreamsupporter/datastreamcontainer) . |
| [CanSave](../../aspose.imaging/image/cansave)(ImageOptionsBase) | Determina se l'immagine può essere salvata nel formato file specificato rappresentato dalle opzioni di salvataggio passate. |
| override [Crop](../../aspose.imaging/rastercachedimage/crop)(Rectangle) | Ritaglio dell'immagine. |
| virtual [Crop](../../aspose.imaging/rasterimage/crop)(int, int, int, int) | Ritaglia immagine con spostamenti. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Elimina l'istanza corrente. |
| [Dither](../../aspose.imaging/rasterimage/dither)(DitheringMethod, int) | Esegue il dithering sull'immagine corrente. |
| override [Dither](../../aspose.imaging/rastercachedimage/dither)(DitheringMethod, int, IColorPalette) | Esegue il dithering sull'immagine corrente. |
| virtual [Filter](../../aspose.imaging/rasterimage/filter)(Rectangle, FilterOptionsBase) | Filtra il rettangolo specificato. |
| [GetArgb32Pixel](../../aspose.imaging/rasterimage/getargb32pixel)(int, int) | Ottiene un'immagine ARGB pixel a 32 bit. |
| [GetDefaultArgb32Pixels](../../aspose.imaging/rasterimage/getdefaultargb32pixels)(Rectangle) | Ottiene l'array di pixel ARGB a 32 bit predefinito. |
| override [GetDefaultOptions](../../aspose.imaging.fileformats.png/pngimage/getdefaultoptions)(object[]) | Ottiene le opzioni predefinite. |
| [GetDefaultPixels](../../aspose.imaging/rasterimage/getdefaultpixels)(Rectangle, IPartialArgb32PixelLoader) | Ottiene l'array di pixel predefinito utilizzando il caricatore di pixel parziale. |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata)(Rectangle, RawDataSettings) | Ottiene l'array di dati grezzi predefinito. |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata)(Rectangle, IPartialRawDataLoader, RawDataSettings) | Ottiene l'array di dati grezzi predefinito utilizzando il caricatore di pixel parziale. |
| override [GetModifyDate](../../aspose.imaging.fileformats.png/pngimage/getmodifydate)(bool) | Ottiene la data e l'ora dell'ultima modifica dell'immagine della risorsa. |
| override [GetOriginalOptions](../../aspose.imaging.fileformats.png/pngimage/getoriginaloptions)() | Ottiene le opzioni in base alle impostazioni del file originale. Questo può essere utile per mantenere invariati la profondità di bit e altri parametri dell'immagine originale. Ad esempio, se carichiamo un'immagine PNG in bianco e nero con 1 bit per pixel e quindi salvalo usando il [`Save`](../../aspose.imaging/datastreamsupporter/save) metodo, verrà prodotta l'immagine PNG di output con 8 bit per pixel. Per evitarlo e salvare l'immagine PNG con 1 bit per pixel, utilizzare questo metodo per ottenere le opzioni di salvataggio corrispondenti e passarle al[`Save`](../../aspose.imaging/image/save) metodo come secondo parametro. |
| [GetPixel](../../aspose.imaging/rasterimage/getpixel)(int, int) | Ottiene un pixel dell'immagine. |
| [GetSkewAngle](../../aspose.imaging/rasterimage/getskewangle)() | Ottiene l'angolo di inclinazione. Questo metodo è applicabile ai documenti di testo scansionati, per determinare l'angolo di inclinazione durante la scansione. |
| override [Grayscale](../../aspose.imaging/rastercachedimage/grayscale)() | Trasformazione di un'immagine nella sua rappresentazione in scala di grigi |
| [LoadArgb32Pixels](../../aspose.imaging/rasterimage/loadargb32pixels)(Rectangle) | Carica pixel ARGB a 32 bit. |
| [LoadArgb64Pixels](../../aspose.imaging/rasterimage/loadargb64pixels)(Rectangle) | Carica pixel ARGB a 64 bit. |
| [LoadCmyk32Pixels](../../aspose.imaging/rasterimage/loadcmyk32pixels)(Rectangle) | Carica i pixel in formato CMYK. |
| [LoadPartialArgb32Pixels](../../aspose.imaging/rasterimage/loadpartialargb32pixels)(Rectangle, IPartialArgb32PixelLoader) | Carica i pixel ARGB a 32 bit parzialmente per pacchetti. |
| [LoadPartialPixels](../../aspose.imaging/rasterimage/loadpartialpixels)(Rectangle, IPartialPixelLoader) | Carica i pixel parzialmente per pacchetti. |
| [LoadPixels](../../aspose.imaging/rasterimage/loadpixels)(Rectangle) | Carica pixel. |
| [LoadRawData](../../aspose.imaging/rasterimage/loadrawdata)(Rectangle, RawDataSettings, IPartialRawDataLoader) | Carica dati grezzi. |
| [LoadRawData](../../aspose.imaging/rasterimage/loadrawdata)(Rectangle, Rectangle, RawDataSettings, IPartialRawDataLoader) | Carica dati grezzi. |
| [NormalizeAngle](../../aspose.imaging/rasterimage/normalizeangle)() | Normalizza l'angolo. Questo metodo è applicabile ai documenti di testo scansionati per eliminare la scansione obliqua. Questo metodo utilizza[`GetSkewAngle`](../../aspose.imaging/rasterimage/getskewangle) e[`Rotate`](../../aspose.imaging/rasterimage/rotate) metodi. |
| virtual [NormalizeAngle](../../aspose.imaging/rasterimage/normalizeangle)(bool, Color) | Normalizza l'angolo. Questo metodo è applicabile ai documenti di testo scansionati per eliminare la scansione obliqua. Questo metodo utilizza[`GetSkewAngle`](../../aspose.imaging/rasterimage/getskewangle) e[`Rotate`](../../aspose.imaging/rasterimage/rotate) metodi. |
| [ReadArgb32ScanLine](../../aspose.imaging/rasterimage/readargb32scanline)(int) | Legge l'intera linea di scansione in base all'indice della linea di scansione specificato. |
| [ReadScanLine](../../aspose.imaging/rasterimage/readscanline)(int) | Legge l'intera linea di scansione in base all'indice della linea di scansione specificato. |
| [ReplaceColor](../../aspose.imaging/rasterimage/replacecolor)(Color, byte, Color) | Sostituisce un colore con un altro con la differenza consentita e conserva il valore alfa originale per salvare i bordi smussati. |
| virtual [ReplaceColor](../../aspose.imaging/rasterimage/replacecolor)(int, byte, int) | Sostituisce un colore con un altro con la differenza consentita e conserva il valore alfa originale per salvare i bordi smussati. |
| [ReplaceNonTransparentColors](../../aspose.imaging/rasterimage/replacenontransparentcolors)(Color) | Sostituisce tutti i colori non trasparenti con un nuovo colore e conserva il valore alfa originale per salvare i bordi smussati. Nota: se lo usi su immagini senza trasparenza, tutti i colori verranno sostituiti con uno solo. |
| virtual [ReplaceNonTransparentColors](../../aspose.imaging/rasterimage/replacenontransparentcolors)(int) | Sostituisce tutti i colori non trasparenti con un nuovo colore e conserva il valore alfa originale per salvare i bordi smussati. Nota: se lo usi su immagini senza trasparenza, tutti i colori verranno sostituiti con uno solo. |
| [Resize](../../aspose.imaging/image/resize)(int, int) | Ridimensiona l'immagine. Il predefinitoNearestNeighbourResample viene utilizzato. |
| override [Resize](../../aspose.imaging/rastercachedimage/resize)(int, int, ImageResizeSettings) | Ridimensiona l'immagine. |
| override [Resize](../../aspose.imaging/rastercachedimage/resize)(int, int, ResizeType) | Ridimensiona l'immagine. |
| [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int) | Ridimensiona proporzionalmente l'altezza. Il predefinitoNearestNeighbourResample viene utilizzato. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int, ImageResizeSettings) | Ridimensiona proporzionalmente l'altezza. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int, ResizeType) | Ridimensiona proporzionalmente l'altezza. |
| [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int) | Ridimensiona proporzionalmente la larghezza. Il predefinitoNearestNeighbourResample viene utilizzato. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int, ImageResizeSettings) | Ridimensiona proporzionalmente la larghezza. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int, ResizeType) | Ridimensiona proporzionalmente la larghezza. |
| virtual [Rotate](../../aspose.imaging/rasterimage/rotate)(float) | Ruota l'immagine attorno al centro. |
| override [Rotate](../../aspose.imaging/rastercachedimage/rotate)(float, bool, Color) | Ruota l'immagine attorno al centro. |
| override [RotateFlip](../../aspose.imaging/rastercachedimage/rotateflip)(RotateFlipType) | Ruota, capovolge o ruota e capovolge l'immagine. |
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
| virtual [SetResolution](../../aspose.imaging/rasterimage/setresolution)(double, double) | Imposta la risoluzione per questo[`RasterImage`](../../aspose.imaging/rasterimage) . |
| virtual [ToBitmap](../../aspose.imaging/rasterimage/tobitmap)() | Converte l'immagine raster in bitmap. |
| [WriteArgb32ScanLine](../../aspose.imaging/rasterimage/writeargb32scanline)(int, int[]) | Scrive l'intera linea di scansione nell'indice della linea di scansione specificato. |
| [WriteScanLine](../../aspose.imaging/rasterimage/writescanline)(int, Color[]) | Scrive l'intera linea di scansione nell'indice della linea di scansione specificato. |

### Esempi

Questo esempio mostra come caricare un'immagine PNG da un file.

```csharp
[C#]

string dir = "c:\\temp\\";

// Carica un'immagine PNG da un file.
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(dir + "sample.png"))
{
    // Trasforma l'immagine in una rappresentazione in scala di grigi
    pngImage.Grayscale();

    // Salva in un file.
    pngImage.Save(dir + "sample.grayscale.png");
}
```

### Guarda anche

* class [RasterCachedImage](../../aspose.imaging/rastercachedimage)
* spazio dei nomi [Aspose.Imaging.FileFormats.Png](../../aspose.imaging.fileformats.png)
* assemblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
