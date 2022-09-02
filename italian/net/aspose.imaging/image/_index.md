---
title: Image
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Limmagine è la classe base per tutti i tipi di immagini.
type: docs
weight: 9660
url: /it/net/aspose.imaging/image/
---
## Image class

L'immagine è la classe base per tutti i tipi di immagini.

```csharp
public abstract class Image : DataStreamSupporter, IObjectWithBounds
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette) { get; set; } | Ottiene o imposta un valore che indica se regolare automaticamente la tavolozza. |
| virtual [BackgroundColor](../../aspose.imaging/image/backgroundcolor) { get; set; } | Ottiene o imposta un valore per il colore di sfondo. |
| abstract [BitsPerPixel](../../aspose.imaging/image/bitsperpixel) { get; } | Ottiene il numero di bit dell'immagine per pixel. |
| [Bounds](../../aspose.imaging/image/bounds) { get; } | Ottiene i limiti dell'immagine. |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint) { get; set; } | Ottiene o imposta l'hint per la dimensione del buffer che è la dimensione massima consentita per tutti i buffer interni. |
| [Container](../../aspose.imaging/image/container) { get; } | Ottiene il[`Image`](../image) contenitore. |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer) { get; } | Ottiene il flusso di dati dell'oggetto. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Ottiene un valore che indica se questa istanza è stata eliminata. |
| virtual [FileFormat](../../aspose.imaging/image/fileformat) { get; } | Ottiene un valore di formato file |
| virtual [HasBackgroundColor](../../aspose.imaging/image/hasbackgroundcolor) { get; set; } | Ottiene o imposta un valore che indica se l'immagine ha il colore di sfondo. |
| abstract [Height](../../aspose.imaging/image/height) { get; } | Ottiene l'altezza dell'immagine. |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor) { get; set; } | Ottiene o imposta il monitor di interruzione. |
| abstract [IsCached](../../aspose.imaging/datastreamsupporter/iscached) { get; } | Ottiene un valore che indica se i dati dell'oggetto sono attualmente memorizzati nella cache e non è richiesta la lettura dei dati. |
| [Palette](../../aspose.imaging/image/palette) { get; set; } | Ottiene o imposta la tavolozza dei colori. La tavolozza dei colori non viene utilizzata quando i pixel sono rappresentati direttamente. |
| [Size](../../aspose.imaging/image/size) { get; } | Ottiene la dimensione dell'immagine. |
| virtual [UsePalette](../../aspose.imaging/image/usepalette) { get; } | Ottiene un valore che indica se viene utilizzata la tavolozza dell'immagine. |
| abstract [Width](../../aspose.imaging/image/width) { get; } | Ottiene la larghezza dell'immagine. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| static [Create](../../aspose.imaging/image/create#create_1)(Image[]) | Crea una nuova immagine utilizzando le immagini specificate come pagine |
| static [Create](../../aspose.imaging/image/create#create_2)(Image[], bool) | Crea una nuova immagine le immagini specificate come pagine. |
| static [Create](../../aspose.imaging/image/create#create)(ImageOptionsBase, int, int) | Crea una nuova immagine utilizzando le opzioni di creazione specificate. |
| static [Load](../../aspose.imaging/image/load#load)(Stream) | Carica una nuova immagine dal flusso specificato. |
| static [Load](../../aspose.imaging/image/load#load_2)(string) | Carica una nuova immagine dal file specificato. |
| static [Load](../../aspose.imaging/image/load#load_1)(Stream, LoadOptions) | Carica una nuova immagine dal flusso specificato. |
| static [Load](../../aspose.imaging/image/load#load_3)(string, LoadOptions) | Carica una nuova immagine dal file specificato. |
| abstract [CacheData](../../aspose.imaging/datastreamsupporter/cachedata)() | Memorizza i dati nella cache e garantisce che nessun ulteriore caricamento dei dati venga eseguito dal sottostante[`DataStreamContainer`](../datastreamsupporter/datastreamcontainer) . |
| [CanSave](../../aspose.imaging/image/cansave)(ImageOptionsBase) | Determina se l'immagine può essere salvata nel formato file specificato rappresentato dalle opzioni di salvataggio passate. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Elimina l'istanza corrente. |
| virtual [GetDefaultOptions](../../aspose.imaging/image/getdefaultoptions)(object[]) | Ottiene le opzioni predefinite. |
| virtual [GetOriginalOptions](../../aspose.imaging/image/getoriginaloptions)() | Ottiene le opzioni in base alle impostazioni del file originale. Questo può essere utile per mantenere invariati la profondità di bit e altri parametri dell'immagine originale. Ad esempio, se carichiamo un'immagine PNG in bianco e nero con 1 bit per pixel e quindi salvalo usando il [`Save`](../datastreamsupporter/save) metodo, verrà prodotta l'immagine PNG di output con 8 bit per pixel. Per evitarlo e salvare l'immagine PNG con 1 bit per pixel, utilizzare questo metodo per ottenere le opzioni di salvataggio corrispondenti e passarle al[`Save`](./save) metodo come secondo parametro. |
| [Resize](../../aspose.imaging/image/resize#resize)(int, int) | Ridimensiona l'immagine. Il predefinitoNearestNeighbourResample viene utilizzato. |
| abstract [Resize](../../aspose.imaging/image/resize#resize_1)(int, int, ImageResizeSettings) | Ridimensiona l'immagine. |
| abstract [Resize](../../aspose.imaging/image/resize#resize_2)(int, int, ResizeType) | Ridimensiona l'immagine. |
| [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally#resizeheightproportionally)(int) | Ridimensiona proporzionalmente l'altezza. Il predefinitoNearestNeighbourResample viene utilizzato. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally#resizeheightproportionally_1)(int, ImageResizeSettings) | Ridimensiona proporzionalmente l'altezza. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally#resizeheightproportionally_2)(int, ResizeType) | Ridimensiona proporzionalmente l'altezza. |
| [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally#resizewidthproportionally)(int) | Ridimensiona proporzionalmente la larghezza. Il predefinitoNearestNeighbourResample viene utilizzato. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally#resizewidthproportionally_1)(int, ImageResizeSettings) | Ridimensiona proporzionalmente la larghezza. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally#resizewidthproportionally_2)(int, ResizeType) | Ridimensiona proporzionalmente la larghezza. |
| abstract [RotateFlip](../../aspose.imaging/image/rotateflip)(RotateFlipType) | Ruota, capovolge o ruota e capovolge l'immagine. |
| [Save](../../aspose.imaging/image/save#save)() | Salva i dati dell'immagine nel flusso sottostante. |
| [Save](../../aspose.imaging/datastreamsupporter/save)(Stream) | Salva i dati dell'oggetto nel flusso specificato. |
| override [Save](../../aspose.imaging/image/save#save_4)(string) | Salva l'immagine nella posizione del file specificata. |
| [Save](../../aspose.imaging/image/save#save_2)(Stream, ImageOptionsBase) | Salva i dati dell'immagine nel flusso specificato nel formato file specificato in base alle opzioni di salvataggio. |
| virtual [Save](../../aspose.imaging/datastreamsupporter/save)(string, bool) | Salva i dati dell'oggetto nella posizione del file specificata. |
| virtual [Save](../../aspose.imaging/image/save#save_5)(string, ImageOptionsBase) | Salva i dati dell'oggetto nel percorso file specificato nel formato file specificato in base alle opzioni di salvataggio. |
| virtual [Save](../../aspose.imaging/image/save#save_3)(Stream, ImageOptionsBase, Rectangle) | Salva i dati dell'immagine nel flusso specificato nel formato file specificato in base alle opzioni di salvataggio. |
| virtual [Save](../../aspose.imaging/image/save#save_6)(string, ImageOptionsBase, Rectangle) | Salva i dati dell'oggetto nel percorso file specificato nel formato file specificato in base alle opzioni di salvataggio. |
| abstract [SetPalette](../../aspose.imaging/image/setpalette)(IColorPalette, bool) | Imposta la tavolozza dell'immagine. |
| static [CanLoad](../../aspose.imaging/image/canload#canload)(Stream) | Determina se l'immagine può essere caricata dal flusso specificato. |
| static [CanLoad](../../aspose.imaging/image/canload#canload_2)(string) | Determina se l'immagine può essere caricata dal percorso file specificato. |
| static [CanLoad](../../aspose.imaging/image/canload#canload_1)(Stream, LoadOptions) | Determina se l'immagine può essere caricata dal flusso specificato e, facoltativamente, utilizzando quello specificato*loadOptions* . |
| static [CanLoad](../../aspose.imaging/image/canload#canload_3)(string, LoadOptions) | Determina se l'immagine può essere caricata dal percorso file specificato e, facoltativamente, utilizzando le opzioni di apertura specificate. |
| static [GetFileFormat](../../aspose.imaging/image/getfileformat#getfileformat)(Stream) | Ottiene il formato del file. |
| static [GetFileFormat](../../aspose.imaging/image/getfileformat#getfileformat_1)(string) | Ottiene il formato del file. |
| static [GetFittingRectangle](../../aspose.imaging/image/getfittingrectangle#getfittingrectangle)(Rectangle, int, int) | Ottiene il rettangolo che si adatta all'immagine corrente. |
| static [GetFittingRectangle](../../aspose.imaging/image/getfittingrectangle#getfittingrectangle_1)(Rectangle, int[], int, int) | Ottiene il rettangolo che si adatta all'immagine corrente. |
| static [GetProportionalHeight](../../aspose.imaging/image/getproportionalheight)(int, int, int) | Ottiene un'altezza proporzionale. |
| static [GetProportionalWidth](../../aspose.imaging/image/getproportionalwidth)(int, int, int) | Ottiene una larghezza proporzionale. |

### Esempi

Determina se la tavolozza viene utilizzata dall'immagine.

```csharp
[C#]

using (var image = Image.Load(folder + "Sample.bmp"))
{
    if (image.UsePalette)
    {
        Console.WriteLine("The palette is used by the image");
    }
}
```

Ridimensiona l'immagine utilizzando un tipo di ridimensionamento specifico.

```csharp
[C#]

using (var image = Image.Load("Photo.jpg"))
{
    image.Resize(640, 480, ResizeType.CatmullRom);
    image.Save("ResizedPhoto.jpg");

    image.Resize(1024, 768, ResizeType.CubicConvolution);
    image.Save("ResizedPhoto2.jpg");

    var resizeSettings = new ImageResizeSettings
    {
        Mode = ResizeType.CubicBSpline,
        FilterType = ImageFilterType.SmallRectangular
    };

    image.Resize(800, 800, resizeSettings);
    image.Save("ResizedPhoto3.jpg");
}
```

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

### Guarda anche

* class [DataStreamSupporter](../datastreamsupporter)
* interface [IObjectWithBounds](../iobjectwithbounds)
* spazio dei nomi [Aspose.Imaging](../../aspose.imaging)
* assemblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
