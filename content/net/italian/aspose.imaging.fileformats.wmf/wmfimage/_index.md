---
title: WmfImage
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Limmagine Wmf
type: docs
weight: 9280
url: /it/aspose.imaging.fileformats.wmf/wmfimage/
---
## WmfImage class

L'immagine Wmf

```csharp
public class WmfImage : MetaImage
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [WmfImage](wmfimage#constructor)() | Inizializza una nuova istanza di[`WmfImage`](../wmfimage) classe. |
| [WmfImage](wmfimage#constructor_1)(int, int) | Inizializza una nuova istanza di[`WmfImage`](../wmfimage) classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette) { get; set; } | Ottiene o imposta un valore che indica se regolare automaticamente la tavolozza. |
| virtual [BackgroundColor](../../aspose.imaging/image/backgroundcolor) { get; set; } | Ottiene o imposta un valore per il colore di sfondo. |
| override [BitsPerPixel](../../aspose.imaging.fileformats.wmf/wmfimage/bitsperpixel) { get; } | Ottiene il numero di bit dell'immagine per pixel. |
| [Bounds](../../aspose.imaging/image/bounds) { get; } | Ottiene i limiti dell'immagine. |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint) { get; set; } | Ottiene o imposta l'hint per la dimensione del buffer che è la dimensione massima consentita per tutti i buffer interni. |
| [Container](../../aspose.imaging/image/container) { get; } | Ottiene il[`Image`](../../aspose.imaging/image) contenitore. |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer) { get; } | Ottiene il flusso di dati dell'oggetto. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Ottiene un valore che indica se questa istanza è stata eliminata. |
| override [FileFormat](../../aspose.imaging.fileformats.wmf/wmfimage/fileformat) { get; } | Ottiene un valore di formato file |
| [FrameBounds](../../aspose.imaging.fileformats.wmf/wmfimage/framebounds) { get; } | Ottiene i limiti del frame. |
| virtual [HasBackgroundColor](../../aspose.imaging/image/hasbackgroundcolor) { get; set; } | Ottiene o imposta un valore che indica se l'immagine ha il colore di sfondo. |
| override [Height](../../aspose.imaging.fileformats.wmf/wmfimage/height) { get; } | Ottiene l'altezza dell'immagine. |
| virtual [HeightF](../../aspose.imaging/vectorimage/heightf) { get; } | Ottiene l'altezza dell'oggetto, in pollici. |
| [Inch](../../aspose.imaging.fileformats.wmf/wmfimage/inch) { get; set; } | Ottiene o imposta i pollici. |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor) { get; set; } | Ottiene o imposta il monitor di interruzione. |
| override [IsCached](../../aspose.imaging.fileformats.wmf/wmfimage/iscached) { get; } | Ottiene un valore che indica se i dati dell'oggetto sono attualmente memorizzati nella cache e non è richiesta alcuna lettura dei dati. |
| [Palette](../../aspose.imaging/image/palette) { get; set; } | Ottiene o imposta la tavolozza dei colori. La tavolozza dei colori non viene utilizzata quando i pixel sono rappresentati direttamente. |
| virtual [Records](../../aspose.imaging.fileformats.emf/metaimage/records) { get; set; } | Ottiene o imposta i record. |
| [Size](../../aspose.imaging/image/size) { get; } | Ottiene la dimensione dell'immagine. |
| [SizeF](../../aspose.imaging/vectorimage/sizef) { get; } | Ottiene la dimensione dell'oggetto, in pollici. |
| virtual [UsePalette](../../aspose.imaging/image/usepalette) { get; } | Ottiene un valore che indica se viene utilizzata la tavolozza dell'immagine. |
| override [Width](../../aspose.imaging.fileformats.wmf/wmfimage/width) { get; } | Ottiene la larghezza dell'immagine. |
| virtual [WidthF](../../aspose.imaging/vectorimage/widthf) { get; } | Ottiene la larghezza dell'oggetto, in pollici. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AddRecord](../../aspose.imaging.fileformats.wmf/wmfimage/addrecord)(WmfObject) | Aggiunge il record. |
| override [CacheData](../../aspose.imaging.fileformats.wmf/wmfimage/cachedata)() | Memorizza i dati nella cache e garantisce che nessun ulteriore caricamento dei dati venga eseguito dal sottostante [`DataStreamContainer`](../../aspose.imaging/datastreamsupporter/datastreamcontainer) . |
| [CanSave](../../aspose.imaging/image/cansave)(ImageOptionsBase) | Determina se l'immagine può essere salvata nel formato file specificato rappresentato dalle opzioni di salvataggio passate. |
| override [Crop](../../aspose.imaging.fileformats.wmf/wmfimage/crop#crop)(Rectangle) | Ritaglia il rettangolo specificato. |
| virtual [Crop](../../aspose.imaging.fileformats.emf/metaimage/crop)(int, int, int, int) | Ritaglia immagine con spostamenti. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Elimina l'istanza corrente. |
| override [GetDefaultOptions](../../aspose.imaging.fileformats.wmf/wmfimage/getdefaultoptions)(object[]) | Ottiene le opzioni predefinite. |
| virtual [GetEmbeddedImages](../../aspose.imaging/vectorimage/getembeddedimages)() | Ottiene le immagini incorporate. |
| [GetMissedFonts](../../aspose.imaging.fileformats.emf/metaimage/getmissedfonts)() | Restituisce l'elenco dei caratteri utilizzati all'interno del metafile ma non trovati. |
| virtual [GetOriginalOptions](../../aspose.imaging/image/getoriginaloptions)() | Ottiene le opzioni in base alle impostazioni del file originale. Questo può essere utile per mantenere invariati la profondità di bit e altri parametri dell'immagine originale. Ad esempio, se carichiamo un'immagine PNG in bianco e nero con 1 bit per pixel e quindi salvalo usando il [`Save`](../../aspose.imaging/datastreamsupporter/save) metodo, verrà prodotta l'immagine PNG di output con 8 bit per pixel. Per evitarlo e salvare l'immagine PNG con 1 bit per pixel, utilizzare questo metodo per ottenere le opzioni di salvataggio corrispondenti e passarle al[`Save`](../../aspose.imaging/image/save) metodo come secondo parametro. |
| [GetPostScript](../../aspose.imaging.fileformats.wmf/wmfimage/getpostscript)() | Ottiene lo script del post. |
| override [GetUsedFonts](../../aspose.imaging.fileformats.wmf/wmfimage/getusedfonts)() | Restituisce l'elenco dei caratteri utilizzati all'interno del metafile. |
| [Resize](../../aspose.imaging/image/resize)(int, int) | Ridimensiona l'immagine. Il predefinitoNearestNeighbourResample viene utilizzato. |
| override [Resize](../../aspose.imaging.fileformats.wmf/wmfimage/resize#resize_1)(int, int, ImageResizeSettings) | Ridimensiona l'immagine. |
| override [Resize](../../aspose.imaging.fileformats.wmf/wmfimage/resize#resize_2)(int, int, ResizeType) | Ridimensiona l'immagine. |
| override [ResizeCanvas](../../aspose.imaging.fileformats.wmf/wmfimage/resizecanvas)(Rectangle) | Ridimensiona la tela. |
| [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int) | Ridimensiona proporzionalmente l'altezza. Il predefinitoNearestNeighbourResample viene utilizzato. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int, ImageResizeSettings) | Ridimensiona proporzionalmente l'altezza. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int, ResizeType) | Ridimensiona proporzionalmente l'altezza. |
| [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int) | Ridimensiona proporzionalmente la larghezza. Il predefinitoNearestNeighbourResample viene utilizzato. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int, ImageResizeSettings) | Ridimensiona proporzionalmente la larghezza. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int, ResizeType) | Ridimensiona proporzionalmente la larghezza. |
| override [RotateFlip](../../aspose.imaging.fileformats.wmf/wmfimage/rotateflip)(RotateFlipType) | Ruota, capovolge o ruota e capovolge l'immagine. |
| [Save](../../aspose.imaging/image/save)() | Salva i dati dell'immagine nel flusso sottostante. |
| [Save](../../aspose.imaging/datastreamsupporter/save)(Stream) | Salva i dati dell'oggetto nel flusso specificato. |
| override [Save](../../aspose.imaging/image/save)(string) | Salva l'immagine nella posizione del file specificata. |
| [Save](../../aspose.imaging/image/save)(Stream, ImageOptionsBase) | Salva i dati dell'immagine nel flusso specificato nel formato file specificato in base alle opzioni di salvataggio. |
| virtual [Save](../../aspose.imaging/datastreamsupporter/save)(string, bool) | Salva i dati dell'oggetto nella posizione del file specificata. |
| virtual [Save](../../aspose.imaging/image/save)(string, ImageOptionsBase) | Salva i dati dell'oggetto nel percorso file specificato nel formato file specificato in base alle opzioni di salvataggio. |
| virtual [Save](../../aspose.imaging/image/save)(Stream, ImageOptionsBase, Rectangle) | Salva i dati dell'immagine nel flusso specificato nel formato file specificato in base alle opzioni di salvataggio. |
| virtual [Save](../../aspose.imaging/image/save)(string, ImageOptionsBase, Rectangle) | Salva i dati dell'oggetto nel percorso file specificato nel formato file specificato in base alle opzioni di salvataggio. |
| override [SetPalette](../../aspose.imaging.fileformats.wmf/wmfimage/setpalette)(IColorPalette, bool) | Imposta la tavolozza dell'immagine. |

### Esempi

L'esempio seguente mostra come convertire un'immagine wmz in wmf fromat

```csharp
[C#]

string file = "example.wmz";
string baseFolder = System.IO.Path.Combine("D:", "Compressed");
string inputFile = System.IO.Path.Combine(baseFolder, file);
string outFile = inputFile + ".wmf";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFile))
{
    Aspose.Imaging.ImageOptions.VectorRasterizationOptions vectorRasterizationOptions = new Aspose.Imaging.ImageOptions.WmfRasterizationOptions() { PageSize = image.Size};
    image.Save(outFile, new Aspose.Imaging.ImageOptions.WmfOptions() {VectorRasterizationOptions = vectorRasterizationOptions});
}
```

L'esempio seguente mostra come convertire un'immagine wmf in wmz fromat

```csharp
[C#]

string file = "castle.wmf";
string baseFolder = System.IO.Path.Combine("D:", "Compressed");
string inputFile = System.IO.Path.Combine(baseFolder, file);
string outFile = inputFile + ".wmz";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFile))
{
    Aspose.Imaging.ImageOptions.VectorRasterizationOptions vectorRasterizationOptions = new Aspose.Imaging.ImageOptions.WmfRasterizationOptions() { PageSize = image.Size};
    image.Save(outFile, new Aspose.Imaging.ImageOptions.WmfOptions() {VectorRasterizationOptions = vectorRasterizationOptions, Compress = true});
}
```

L'esempio seguente mostra come convertire un'immagine compressa (*.emz,*.wmz, *.svgz) in raster fromat

```csharp
[C#]

string[] files = new[] {"example.emz", "example.wmz", "example.svgz"};
string baseFolder = System.IO.Path.Combine("D:","Compressed");
foreach (var file in files)
{
    string inputFile = System.IO.Path.Combine(baseFolder, file);
    string outFile = inputFile + ".png";
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFile))
    {
        Aspose.Imaging.ImageOptions.VectorRasterizationOptions vectorRasterizationOptions = (Aspose.Imaging.ImageOptions.VectorRasterizationOptions)image.GetDefaultOptions(new object[] { Color.White, image.Width, image.Height });
        image.Save(outFile, new Aspose.Imaging.ImageOptions.PngOptions(){VectorRasterizationOptions = vectorRasterizationOptions});
    }
}
```

Questo esempio mostra come caricare un'immagine WMF da un file e convertirla in SVG utilizzando WmfRasterizationOptions.

```csharp
[C#]

string dir = "c:\\temp\\";

// L'uso di Aspose.Imaging.Image.Load è un modo unificato per caricare tutti i tipi di immagini, incluso WMF.
using (Aspose.Imaging.FileFormats.Wmf.WmfImage wmfImage = (Aspose.Imaging.FileFormats.Wmf.WmfImage)Aspose.Imaging.Image.Load(dir + "test.wmf"))
{
    Aspose.Imaging.ImageOptions.SvgOptions saveOptions = new Aspose.Imaging.ImageOptions.SvgOptions();
        
    // Il testo verrà convertito in forme.
    saveOptions.TextAsShapes = true;

    Aspose.Imaging.ImageOptions.WmfRasterizationOptions rasterizationOptions = new Aspose.Imaging.ImageOptions.WmfRasterizationOptions();

    // Il colore di sfondo della superficie di disegno.
    rasterizationOptions.BackgroundColor = Aspose.Imaging.Color.WhiteSmoke;

    // La dimensione della pagina.
    rasterizationOptions.PageSize = wmfImage.Size;

    // Se esiste emf incorporato, renderizza emf; altrimenti renderizza wmf.
    rasterizationOptions.RenderMode = Aspose.Imaging.FileFormats.Wmf.WmfRenderMode.Auto;

    saveOptions.VectorRasterizationOptions = rasterizationOptions;

    wmfImage.Save(dir + "test.output.svg", saveOptions);
}
```

### Guarda anche

* class [MetaImage](../../aspose.imaging.fileformats.emf/metaimage)
* spazio dei nomi [Aspose.Imaging.FileFormats.Wmf](../../aspose.imaging.fileformats.wmf)
* assemblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
