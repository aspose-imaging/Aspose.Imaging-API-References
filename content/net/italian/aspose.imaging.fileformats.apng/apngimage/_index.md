---
title: ApngImage
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Limmagine PNG animata.
type: docs
weight: 1320
url: /it/aspose.imaging.fileformats.apng/apngimage/
---
## ApngImage class

L'immagine PNG animata.

```csharp
public sealed class ApngImage : RasterCachedMultipageImage, IMultipageImageExt
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [ApngImage](apngimage)(ApngOptions, int, int) | Inizializza una nuova istanza di[`ApngImage`](../apngimage) classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette) { get; set; } | Ottiene o imposta un valore che indica se regolare automaticamente la tavolozza. |
| override [BackgroundColor](../../aspose.imaging/rastercachedmultipageimage/backgroundcolor) { get; set; } | Ottiene o imposta un valore per il colore di sfondo. |
| override [BitsPerPixel](../../aspose.imaging/rastercachedmultipageimage/bitsperpixel) { get; } | Ottiene il numero di bit dell'immagine per pixel. |
| [Bounds](../../aspose.imaging/image/bounds) { get; } | Ottiene i limiti dell'immagine. |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint) { get; set; } | Ottiene o imposta l'hint per la dimensione del buffer che è la dimensione massima consentita per tutti i buffer interni. |
| [Container](../../aspose.imaging/image/container) { get; } | Ottiene il[`Image`](../../aspose.imaging/image) contenitore. |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer) { get; } | Ottiene il flusso di dati dell'oggetto. |
| [DefaultFrameTime](../../aspose.imaging.fileformats.apng/apngimage/defaultframetime) { get; set; } | Ottiene o imposta la durata del frame predefinita. Utilizzato durante la creazione di nuovi frame. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Ottiene un valore che indica se questa istanza è stata eliminata. |
| override [FileFormat](../../aspose.imaging.fileformats.apng/apngimage/fileformat) { get; } | Ottiene un valore di formato file |
| override [HasAlpha](../../aspose.imaging/rastercachedmultipageimage/hasalpha) { get; } | Ottiene un valore che indica se questa istanza ha alpha. |
| virtual [HasBackgroundColor](../../aspose.imaging/image/hasbackgroundcolor) { get; set; } | Ottiene o imposta un valore che indica se l'immagine ha il colore di sfondo. |
| override [HasTransparentColor](../../aspose.imaging/rastercachedmultipageimage/hastransparentcolor) { get; } | Ottiene un valore che indica se l'immagine ha un colore trasparente. |
| override [Height](../../aspose.imaging/rastercachedmultipageimage/height) { get; } | Ottiene l'altezza dell'immagine. |
| virtual [HorizontalResolution](../../aspose.imaging/rasterimage/horizontalresolution) { get; set; } | Ottiene o imposta la risoluzione orizzontale, in pixel per pollice, di questo[`RasterImage`](../../aspose.imaging/rasterimage) . |
| override [ImageOpacity](../../aspose.imaging/rastercachedmultipageimage/imageopacity) { get; } | Ottiene l'opacità di questa immagine. |
| [Interlaced](../../aspose.imaging.fileformats.apng/apngimage/interlaced) { get; } | Ottiene un valore che indica se questo[`PngImage`](../../aspose.imaging.fileformats.png/pngimage) è intrecciato. |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor) { get; set; } | Ottiene o imposta il monitor di interruzione. |
| [IsCached](../../aspose.imaging/rastercachedmultipageimage/iscached) { get; } | Ottiene un valore che indica se i dati dell'immagine sono attualmente memorizzati nella cache. |
| [IsRawDataAvailable](../../aspose.imaging/rasterimage/israwdataavailable) { get; } | Ottiene un valore che indica se è disponibile il caricamento dei dati grezzi. |
| [NumPlays](../../aspose.imaging.fileformats.apng/apngimage/numplays) { get; set; } | Ottiene o imposta il numero di volte in cui eseguire il ciclo dell'animazione. 0 indica il ciclo infinito. |
| override [PageCount](../../aspose.imaging.fileformats.apng/apngimage/pagecount) { get; } | Ottiene il conteggio delle pagine. |
| override [PageExportingAction](../../aspose.imaging.fileformats.apng/apngimage/pageexportingaction) { get; set; } | Ottiene o imposta l'azione di esportazione della pagina. Tieni presente che l'impostazione di questo metodo rilascerà automaticamente le risorse della pagina dopo l'esecuzione. Verrà eseguito appena prima del salvataggio di ogni pagina. |
| override [Pages](../../aspose.imaging.fileformats.apng/apngimage/pages) { get; } | Ottiene le pagine. |
| [Palette](../../aspose.imaging/image/palette) { get; set; } | Ottiene o imposta la tavolozza dei colori. La tavolozza dei colori non viene utilizzata quando i pixel sono rappresentati direttamente. |
| virtual [PremultiplyComponents](../../aspose.imaging/rasterimage/premultiplycomponents) { get; set; } | Ottiene o imposta un valore che indica se i componenti dell'immagine devono essere premoltiplicati. |
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
| virtual [VerticalResolution](../../aspose.imaging/rasterimage/verticalresolution) { get; set; } | Ottiene o imposta la risoluzione verticale, in pixel per pollice, di questo[`RasterImage`](../../aspose.imaging/rasterimage) . |
| override [Width](../../aspose.imaging/rastercachedmultipageimage/width) { get; } | Ottiene la larghezza dell'immagine. |
| override [XmpData](../../aspose.imaging.fileformats.apng/apngimage/xmpdata) { get; set; } | Ottiene o imposta i metadati XMP. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AddFrame](../../aspose.imaging.fileformats.apng/apngimage/addframe#addframe)() | Aggiunge una nuova cornice alla fine della propria raccolta di cornici. Verrà creata una nuova cornice in base alle dimensioni dell'immagine corrente. |
| [AddFrame](../../aspose.imaging.fileformats.apng/apngimage/addframe#addframe_1)(RasterImage) | Aggiunge un nuovo frame alla fine della propria raccolta di frame. Il contenuto del nuovo frame verrà riempito dall'immagine specificata. |
| [AddFrame](../../aspose.imaging.fileformats.apng/apngimage/addframe#addframe_2)(RasterImage, uint) | Aggiunge un nuovo frame alla fine della propria raccolta di frame. Il contenuto del nuovo frame verrà riempito dall'immagine specificata. |
| [AddPage](../../aspose.imaging.fileformats.apng/apngimage/addpage)(RasterImage) | Aggiunge la pagina all'immagine. |
| override [AdjustBrightness](../../aspose.imaging.fileformats.apng/apngimage/adjustbrightness)(int) | Regolazione di a*brightness* per immagine. |
| override [AdjustContrast](../../aspose.imaging.fileformats.apng/apngimage/adjustcontrast)(float) | [`Image`](../../aspose.imaging/image) contrasto |
| override [AdjustGamma](../../aspose.imaging.fileformats.apng/apngimage/adjustgamma#adjustgamma)(float) | Correzione gamma di un'immagine. |
| override [AdjustGamma](../../aspose.imaging.fileformats.apng/apngimage/adjustgamma#adjustgamma_1)(float, float, float) | Correzione gamma di un'immagine. |
| override [BinarizeBradley](../../aspose.imaging/rastercachedmultipageimage/binarizebradley)(double) | Binarizzazione di un'immagine utilizzando l'algoritmo di soglia adattivo di Bradley utilizzando la soglia di immagine integrale |
| override [BinarizeBradley](../../aspose.imaging.fileformats.apng/apngimage/binarizebradley#binarizebradley_1)(double, int) | Binarizzazione di un'immagine utilizzando l'algoritmo di soglia adattivo di Bradley utilizzando la soglia di immagine integrale |
| override [BinarizeFixed](../../aspose.imaging.fileformats.apng/apngimage/binarizefixed)(byte) | Binarizzazione di un'immagine con soglia predefinita |
| override [BinarizeOtsu](../../aspose.imaging.fileformats.apng/apngimage/binarizeotsu)() | Binarizzazione di un'immagine con soglia Otsu |
| override [CacheData](../../aspose.imaging/rastercachedmultipageimage/cachedata)() | Memorizza nella cache i dati privati. |
| [CanSave](../../aspose.imaging/image/cansave)(ImageOptionsBase) | Determina se l'immagine può essere salvata nel formato file specificato rappresentato dalle opzioni di salvataggio passate. |
| override [Crop](../../aspose.imaging.fileformats.apng/apngimage/crop#crop)(Rectangle) | Ritaglio dell'immagine. |
| override [Crop](../../aspose.imaging.fileformats.apng/apngimage/crop#crop_1)(int, int, int, int) | Ritaglia immagine con spostamenti. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Elimina l'istanza corrente. |
| [Dither](../../aspose.imaging/rasterimage/dither)(DitheringMethod, int) | Esegue il dithering sull'immagine corrente. |
| override [Dither](../../aspose.imaging.fileformats.apng/apngimage/dither#dither_1)(DitheringMethod, int, IColorPalette) | Esegue il dithering sull'immagine corrente. |
| override [Filter](../../aspose.imaging.fileformats.apng/apngimage/filter)(Rectangle, FilterOptionsBase) | Filtra il rettangolo specificato. |
| [GetArgb32Pixel](../../aspose.imaging/rasterimage/getargb32pixel)(int, int) | Ottiene un'immagine ARGB pixel a 32 bit. |
| [GetDefaultArgb32Pixels](../../aspose.imaging/rasterimage/getdefaultargb32pixels)(Rectangle) | Ottiene l'array di pixel ARGB a 32 bit predefinito. |
| override [GetDefaultOptions](../../aspose.imaging.fileformats.apng/apngimage/getdefaultoptions)(object[]) | Ottiene le opzioni predefinite. |
| [GetDefaultPixels](../../aspose.imaging/rasterimage/getdefaultpixels)(Rectangle, IPartialArgb32PixelLoader) | Ottiene l'array di pixel predefinito utilizzando il caricatore di pixel parziale. |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata)(Rectangle, RawDataSettings) | Ottiene l'array di dati grezzi predefinito. |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata)(Rectangle, IPartialRawDataLoader, RawDataSettings) | Ottiene l'array di dati grezzi predefinito utilizzando il caricatore di pixel parziale. |
| override [GetModifyDate](../../aspose.imaging.fileformats.apng/apngimage/getmodifydate)(bool) | Ottiene la data e l'ora dell'ultima modifica dell'immagine della risorsa. |
| override [GetOriginalOptions](../../aspose.imaging.fileformats.apng/apngimage/getoriginaloptions)() | Ottiene le opzioni in base alle impostazioni del file originale. Questo può essere utile per mantenere invariati la profondità di bit e altri parametri dell'immagine originale. Ad esempio, se carichiamo un'immagine PNG in bianco e nero con 1 bit per pixel e quindi salvalo usando il [`Save`](../../aspose.imaging/datastreamsupporter/save) metodo, verrà prodotta l'immagine PNG di output con 8 bit per pixel. Per evitarlo e salvare l'immagine PNG con 1 bit per pixel, utilizzare questo metodo per ottenere le opzioni di salvataggio corrispondenti e passarle al[`Save`](../../aspose.imaging/image/save) metodo come secondo parametro. |
| [GetPixel](../../aspose.imaging/rasterimage/getpixel)(int, int) | Ottiene un pixel dell'immagine. |
| [GetSkewAngle](../../aspose.imaging/rasterimage/getskewangle)() | Ottiene l'angolo di inclinazione. Questo metodo è applicabile ai documenti di testo scansionati, per determinare l'angolo di inclinazione durante la scansione. |
| override [Grayscale](../../aspose.imaging.fileformats.apng/apngimage/grayscale)() | Trasformazione di un'immagine nella sua rappresentazione in scala di grigi |
| [InsertFrame](../../aspose.imaging.fileformats.apng/apngimage/insertframe#insertframe)(int) | Inserisce un nuovo frame nella propria raccolta di frame all'indice specificato. Verrà creato un nuovo frame in base alle dimensioni dell'immagine corrente. |
| [InsertFrame](../../aspose.imaging.fileformats.apng/apngimage/insertframe#insertframe_1)(int, RasterImage) | Inserisce il nuovo frame nella propria raccolta di frame all'indice specificato. Il contenuto del nuovo frame verrà riempito dall'immagine specificata. |
| [InsertFrame](../../aspose.imaging.fileformats.apng/apngimage/insertframe#insertframe_2)(int, RasterImage, uint) | Inserisce il nuovo frame nella propria raccolta di frame all'indice specificato. Il contenuto del nuovo frame verrà riempito dall'immagine specificata. |
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
| [PopFrameAt](../../aspose.imaging.fileformats.apng/apngimage/popframeat)(int) | Rimuove e restituisce il frame all'indice specificato della propria raccolta di frame. |
| [ReadArgb32ScanLine](../../aspose.imaging/rasterimage/readargb32scanline)(int) | Legge l'intera linea di scansione in base all'indice della linea di scansione specificato. |
| [ReadScanLine](../../aspose.imaging/rasterimage/readscanline)(int) | Legge l'intera linea di scansione in base all'indice della linea di scansione specificato. |
| [RemoveAllFrames](../../aspose.imaging.fileformats.apng/apngimage/removeallframes)() | Rimuove tutti i frame dalla propria raccolta di frame. |
| [RemoveFrameAt](../../aspose.imaging.fileformats.apng/apngimage/removeframeat)(int) | Rimuove il frame in corrispondenza dell'indice specificato della propria raccolta di frame. Il frame da eliminare verrà eliminato. |
| [ReplaceColor](../../aspose.imaging/rasterimage/replacecolor)(Color, byte, Color) | Sostituisce un colore con un altro con la differenza consentita e conserva il valore alfa originale per salvare i bordi smussati. |
| override [ReplaceColor](../../aspose.imaging/rastercachedmultipageimage/replacecolor)(int, byte, int) | Sostituisce un colore con un altro con la differenza consentita e conserva il valore alfa originale per salvare i bordi smussati. |
| [ReplaceNonTransparentColors](../../aspose.imaging/rasterimage/replacenontransparentcolors)(Color) | Sostituisce tutti i colori non trasparenti con un nuovo colore e conserva il valore alfa originale per salvare i bordi smussati. Nota: se lo usi su immagini senza trasparenza, tutti i colori verranno sostituiti con uno solo. |
| override [ReplaceNonTransparentColors](../../aspose.imaging/rastercachedmultipageimage/replacenontransparentcolors)(int) | Sostituisce tutti i colori non trasparenti con un nuovo colore e conserva il valore alfa originale per salvare i bordi smussati. Nota: se lo usi su immagini senza trasparenza, tutti i colori verranno sostituiti con uno solo. |
| [ResetDefaultImage](../../aspose.imaging.fileformats.apng/apngimage/resetdefaultimage)() | Elimina un'immagine predefinita impostata in precedenza. Dopodiché, l'immagine predefinita è il primo fotogramma nella propria raccolta di fotogrammi (non può essere eliminata utilizzando questo metodo). |
| [Resize](../../aspose.imaging/image/resize)(int, int) | Ridimensiona l'immagine. Il predefinitoNearestNeighbourResample viene utilizzato. |
| override [Resize](../../aspose.imaging.fileformats.apng/apngimage/resize#resize_1)(int, int, ImageResizeSettings) | Ridimensiona l'immagine. |
| override [Resize](../../aspose.imaging.fileformats.apng/apngimage/resize#resize_2)(int, int, ResizeType) | Ridimensiona l'immagine. |
| [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int) | Ridimensiona proporzionalmente l'altezza. Il predefinitoNearestNeighbourResample viene utilizzato. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int, ImageResizeSettings) | Ridimensiona proporzionalmente l'altezza. |
| override [ResizeHeightProportionally](../../aspose.imaging.fileformats.apng/apngimage/resizeheightproportionally#resizeheightproportionally_2)(int, ResizeType) | Ridimensiona proporzionalmente la larghezza. |
| [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int) | Ridimensiona proporzionalmente la larghezza. Il predefinitoNearestNeighbourResample viene utilizzato. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int, ImageResizeSettings) | Ridimensiona proporzionalmente la larghezza. |
| override [ResizeWidthProportionally](../../aspose.imaging.fileformats.apng/apngimage/resizewidthproportionally#resizewidthproportionally_2)(int, ResizeType) | Ridimensiona proporzionalmente la larghezza. |
| virtual [Rotate](../../aspose.imaging/rasterimage/rotate)(float) | Ruota l'immagine attorno al centro. |
| override [Rotate](../../aspose.imaging.fileformats.apng/apngimage/rotate#rotate_1)(float, bool, Color) | !:RasterCahcedMultipageImage.Rotate immagine intorno al centro. |
| override [RotateFlip](../../aspose.imaging.fileformats.apng/apngimage/rotateflip)(RotateFlipType) | Ruota, capovolge o ruota e capovolge solo il fotogramma attivo. |
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
| [SetDefaultImage](../../aspose.imaging.fileformats.apng/apngimage/setdefaultimage)(RasterImage) | Imposta l'immagine raster specificata come immagine predefinita dell'animazione corrente. |
| override [SetPalette](../../aspose.imaging/rasterimage/setpalette)(IColorPalette, bool) | Imposta la tavolozza dell'immagine. |
| [SetPixel](../../aspose.imaging/rasterimage/setpixel)(int, int, Color) | Imposta un pixel dell'immagine per la posizione specificata. |
| virtual [SetResolution](../../aspose.imaging/rasterimage/setresolution)(double, double) | Imposta la risoluzione per questo[`RasterImage`](../../aspose.imaging/rasterimage) . |
| virtual [ToBitmap](../../aspose.imaging/rasterimage/tobitmap)() | Converte l'immagine raster in bitmap. |
| [WriteArgb32ScanLine](../../aspose.imaging/rasterimage/writeargb32scanline)(int, int[]) | Scrive l'intera linea di scansione nell'indice della linea di scansione specificato. |
| [WriteScanLine](../../aspose.imaging/rasterimage/writescanline)(int, Color[]) | Scrive l'intera linea di scansione nell'indice della linea di scansione specificato. |

### Esempi

L'esempio seguente mostra come esportare il formato di file apng APNG da un altro formato multipagina non animato.

```csharp
[C#]

using Aspose.Imaging;
using Aspose.Imaging.ImageOptions;

using (Image image = Image.Load("img4.tif")) {
    // Impostazione della durata del frame predefinita
    image.Save("img4.tif.500ms.png", new ApngOptions() { DefaultFrameTime = 500 }); // 500 ms
    image.Save("img4.tif.250ms.png", new ApngOptions() { DefaultFrameTime = 250 }); // 250 ms
}
```

L'esempio seguente mostra come esportare in formato file APNG.

```csharp
[C#]

using Aspose.Imaging;
using Aspose.Imaging.ImageOptions;

using (Image image = Image.Load("Animation1.webp")) {
    // Esporta in animazione APNG con cicli di animazione illimitati come impostazione predefinita
    image.Save("Animation1.webp.png", new ApngOptions());
    // Impostazione dei cicli di animazione
    image.Save("Animation2.webp.png", new ApngOptions() { NumPlays = 5 }); // 5 cicli
}
```

L'esempio seguente mostra come creare un'immagine APNG da un'altra immagine raster a pagina singola.

```csharp
[C#]

using Aspose.Imaging;
using Aspose.Imaging.ImageOptions;
using Aspose.Imaging.FileFormats.Apng;

const int AnimationDuration = 1000; // 1 secondo
const int FrameDuration = 70; // 70 ms
using (RasterImage sourceImage = (RasterImage)Image.Load("not_animated.png"))
{
    ApngOptions createOptions = new ApngOptions
    {
        Source = new FileCreateSource("raster_animation.png", false),
        DefaultFrameTime = (uint)FrameDuration,
        ColorType = PngColorType.TruecolorWithAlpha,
    };

    using (ApngImage apngImage = (ApngImage)Image.Create(
        createOptions,
        sourceImage.Width,
        sourceImage.Height))
    {
        // È possibile impostare il frame time predefinito dell'immagine qui: apngImage.DefaultFrameTime = (uint)FrameDuration;

        int numOfFrames = AnimationDuration / FrameDuration;
        int numOfFrames2 = numOfFrames / 2;

        // Pulizia perché l'immagine contiene un frame per impostazione predefinita
        apngImage.RemoveAllFrames();

        // aggiungi il primo fotogramma
        apngImage.AddFrame(sourceImage);

        // aggiungi frame intermedi
        for (int frameIndex = 1; frameIndex < numOfFrames - 1; ++frameIndex)
        {
            apngImage.AddFrame(sourceImage);
            ApngFrame lastFrame = (ApngFrame)apngImage.Pages[apngImage.PageCount - 1];
            float gamma = frameIndex >= numOfFrames2 ? numOfFrames - frameIndex - 1 : frameIndex;
            lastFrame.AdjustGamma(gamma);
        }

        // aggiungi l'ultimo fotogramma
        apngImage.AddFrame(sourceImage);

        apngImage.Save();
    }
}
```

### Guarda anche

* class [RasterCachedMultipageImage](../../aspose.imaging/rastercachedmultipageimage)
* interface [IMultipageImageExt](../../aspose.imaging/imultipageimageext)
* spazio dei nomi [Aspose.Imaging.FileFormats.Apng](../../aspose.imaging.fileformats.apng)
* assemblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
