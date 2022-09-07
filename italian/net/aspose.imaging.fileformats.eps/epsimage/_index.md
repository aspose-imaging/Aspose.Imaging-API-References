---
title: EpsImage
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Classe base per il formato EPS
type: docs
weight: 6560
url: /it/net/aspose.imaging.fileformats.eps/epsimage/
---
## EpsImage class

Classe base per il formato EPS

```csharp
public abstract class EpsImage : VectorImage
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette) { get; set; } | Ottiene o imposta un valore che indica se regolare automaticamente la tavolozza. |
| virtual [BackgroundColor](../../aspose.imaging/image/backgroundcolor) { get; set; } | Ottiene o imposta un valore per il colore di sfondo. |
| override [BitsPerPixel](../../aspose.imaging.fileformats.eps/epsimage/bitsperpixel) { get; } | Ottiene il numero di bit dell'immagine per pixel. |
| [BoundingBoxBottomLeft](../../aspose.imaging.fileformats.eps/epsimage/boundingboxbottomleft) { get; } | Ottiene la posizione del riquadro di delimitazione in basso a sinistra |
| [BoundingBoxString](../../aspose.imaging.fileformats.eps/epsimage/boundingboxstring) { get; } | Ottiene il valore della stringa BoundingBox |
| [BoundingBoxTopRight](../../aspose.imaging.fileformats.eps/epsimage/boundingboxtopright) { get; } | Ottiene la posizione del riquadro di delimitazione in alto a destra |
| [Bounds](../../aspose.imaging/image/bounds) { get; } | Ottiene i limiti dell'immagine. |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint) { get; set; } | Ottiene o imposta l'hint per la dimensione del buffer che è la dimensione massima consentita per tutti i buffer interni. |
| [Container](../../aspose.imaging/image/container) { get; } | Ottiene il[`Image`](../../aspose.imaging/image) contenitore. |
| [CreationDate](../../aspose.imaging.fileformats.eps/epsimage/creationdate) { get; } | Ottiene il campo CreationDate |
| [CreationDateString](../../aspose.imaging.fileformats.eps/epsimage/creationdatestring) { get; } | Ottiene il valore della stringa del campo CreationDate |
| [Creator](../../aspose.imaging.fileformats.eps/epsimage/creator) { get; } | Ottiene il campo Creator |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer) { get; } | Ottiene il flusso di dati dell'oggetto. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Ottiene un valore che indica se questa istanza è stata eliminata. |
| abstract [EpsType](../../aspose.imaging.fileformats.eps/epsimage/epstype) { get; } | Ottiene il valore del sottotipo EPS |
| override [FileFormat](../../aspose.imaging.fileformats.eps/epsimage/fileformat) { get; } | Ottiene un valore di formato file |
| virtual [HasBackgroundColor](../../aspose.imaging/image/hasbackgroundcolor) { get; set; } | Ottiene o imposta un valore che indica se l'immagine ha il colore di sfondo. |
| abstract [HasRasterPreview](../../aspose.imaging.fileformats.eps/epsimage/hasrasterpreview) { get; } | Ottiene un valore che indica se questa istanza ha un'anteprima raster specifica del formato |
| override [Height](../../aspose.imaging.fileformats.eps/epsimage/height) { get; } | Ottiene l'altezza dell'immagine. |
| virtual [HeightF](../../aspose.imaging/vectorimage/heightf) { get; } | Ottiene l'altezza dell'oggetto, in pollici. |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor) { get; set; } | Ottiene o imposta il monitor di interruzione. |
| override [IsCached](../../aspose.imaging.fileformats.eps/epsimage/iscached) { get; } | Ottiene un valore che indica se i dati dell'oggetto sono attualmente memorizzati nella cache e non è richiesta la lettura dei dati. |
| [PageNumber](../../aspose.imaging.fileformats.eps/epsimage/pagenumber) { get; } | Ottiene il numero di pagina |
| [PagesCount](../../aspose.imaging.fileformats.eps/epsimage/pagescount) { get; } | Ottiene il conteggio delle pagine |
| [Palette](../../aspose.imaging/image/palette) { get; set; } | Ottiene o imposta la tavolozza dei colori. La tavolozza dei colori non viene utilizzata quando i pixel sono rappresentati direttamente. |
| [PhotoshopThumbnail](../../aspose.imaging.fileformats.eps/epsimage/photoshopthumbnail) { get; } | Ottiene la miniatura dell'anteprima di Photoshop (se presente nei dati EPS iniziali) |
| [PostScriptVersion](../../aspose.imaging.fileformats.eps/epsimage/postscriptversion) { get; } | Ottiene il campo della versione PostScript |
| [Size](../../aspose.imaging/image/size) { get; } | Ottiene la dimensione dell'immagine. |
| [SizeF](../../aspose.imaging/vectorimage/sizef) { get; } | Ottiene la dimensione dell'oggetto, in pollici. |
| [Title](../../aspose.imaging.fileformats.eps/epsimage/title) { get; } | Ottiene il campo Titolo |
| virtual [UsePalette](../../aspose.imaging/image/usepalette) { get; } | Ottiene un valore che indica se viene utilizzata la tavolozza dell'immagine. |
| override [Width](../../aspose.imaging.fileformats.eps/epsimage/width) { get; } | Ottiene la larghezza dell'immagine. |
| virtual [WidthF](../../aspose.imaging/vectorimage/widthf) { get; } | Ottiene la larghezza dell'oggetto, in pollici. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [CacheData](../../aspose.imaging.fileformats.eps/epsimage/cachedata)() | Impossibile utilizzare la cache. |
| [CanSave](../../aspose.imaging/image/cansave)(ImageOptionsBase) | Determina se l'immagine può essere salvata nel formato file specificato rappresentato dalle opzioni di salvataggio passate. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Elimina l'istanza corrente. |
| override [GetDefaultOptions](../../aspose.imaging.fileformats.eps/epsimage/getdefaultoptions)(object[]) | Ottiene le opzioni predefinite. |
| virtual [GetEmbeddedImages](../../aspose.imaging/vectorimage/getembeddedimages)() | Ottiene le immagini incorporate. |
| virtual [GetOriginalOptions](../../aspose.imaging/image/getoriginaloptions)() | Ottiene le opzioni in base alle impostazioni del file originale. Questo può essere utile per mantenere invariati la profondità di bit e altri parametri dell'immagine originale. Ad esempio, se carichiamo un'immagine PNG in bianco e nero con 1 bit per pixel e quindi salvalo usando il [`Save`](../../aspose.imaging/datastreamsupporter/save) metodo, verrà prodotta l'immagine PNG di output con 8 bit per pixel. Per evitarlo e salvare l'immagine PNG con 1 bit per pixel, utilizzare questo metodo per ottenere le opzioni di salvataggio corrispondenti e passarle al[`Save`](../../aspose.imaging/image/save) metodo come secondo parametro. |
| [Resize](../../aspose.imaging/image/resize)(int, int) | Ridimensiona l'immagine. Il predefinitoNearestNeighbourResample viene utilizzato. |
| override [Resize](../../aspose.imaging.fileformats.eps/epsimage/resize#resize_1)(int, int, ImageResizeSettings) | Ridimensiona l'immagine. |
| override [Resize](../../aspose.imaging.fileformats.eps/epsimage/resize#resize_2)(int, int, ResizeType) | Ridimensiona l'immagine. |
| [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int) | Ridimensiona proporzionalmente l'altezza. Il predefinitoNearestNeighbourResample viene utilizzato. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int, ImageResizeSettings) | Ridimensiona proporzionalmente l'altezza. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int, ResizeType) | Ridimensiona proporzionalmente l'altezza. |
| [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int) | Ridimensiona proporzionalmente la larghezza. Il predefinitoNearestNeighbourResample viene utilizzato. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int, ImageResizeSettings) | Ridimensiona proporzionalmente la larghezza. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int, ResizeType) | Ridimensiona proporzionalmente la larghezza. |
| override [RotateFlip](../../aspose.imaging.fileformats.eps/epsimage/rotateflip)(RotateFlipType) | Ruota, capovolge o ruota e capovolge l'immagine. |
| [Save](../../aspose.imaging/image/save)() | Salva i dati dell'immagine nel flusso sottostante. |
| [Save](../../aspose.imaging/datastreamsupporter/save)(Stream) | Salva i dati dell'oggetto nel flusso specificato. |
| override [Save](../../aspose.imaging/image/save)(string) | Salva l'immagine nella posizione del file specificata. |
| [Save](../../aspose.imaging/image/save)(Stream, ImageOptionsBase) | Salva i dati dell'immagine nel flusso specificato nel formato file specificato in base alle opzioni di salvataggio. |
| virtual [Save](../../aspose.imaging/datastreamsupporter/save)(string, bool) | Salva i dati dell'oggetto nella posizione del file specificata. |
| virtual [Save](../../aspose.imaging/image/save)(string, ImageOptionsBase) | Salva i dati dell'oggetto nel percorso file specificato nel formato file specificato in base alle opzioni di salvataggio. |
| virtual [Save](../../aspose.imaging/image/save)(Stream, ImageOptionsBase, Rectangle) | Salva i dati dell'immagine nel flusso specificato nel formato file specificato in base alle opzioni di salvataggio. |
| virtual [Save](../../aspose.imaging/image/save)(string, ImageOptionsBase, Rectangle) | Salva i dati dell'oggetto nel percorso file specificato nel formato file specificato in base alle opzioni di salvataggio. |
| override [SetPalette](../../aspose.imaging.fileformats.eps/epsimage/setpalette)(IColorPalette, bool) | Imposta la tavolozza dell'immagine. |

### Esempi

Ridimensiona l'immagine EPS ed esportala in formato PNG.

```csharp
[C#]

// Carica immagine EPS
using (var image = Image.Load("AstrixObelix.eps"))
{
    // Ridimensiona l'immagine usando il metodo di interpolazione cubica di Mitchell
    image.Resize(400, 400, ResizeType.Mitchell);

    // Esporta l'immagine in formato PNG
    image.Save("ExportResult.png", new PngOptions());
}
```

Converti l'immagine EPS in PDF utilizzando il rendering PostScript.

```csharp
[C#]

using (var image = (EpsImage)Image.Load("Sample.eps"))
{
    var options = new PdfOptions
    {
        PdfCoreOptions = new PdfCoreOptions
        {
            PdfCompliance = PdfComplianceVersion.PdfA1b // Imposta la conformità PDF richiesta
        }
    };
  
    image.Save("Sample.pdf", options);
}
```

Converti l'immagine EPS in PNG usando il rendering PostScript.

```csharp
[C#]

using (var image = (EpsImage)Image.Load("Sample.eps"))
{
    var options = new PngOptions
    {
        VectorRasterizationOptions = new EpsRasterizationOptions
        {
            PageWidth = 500, // Larghezza immagine
            PageHeight = 500 // Altezza dell'immagine
            PreviewToExport = EpsPreviewFormat.PostScriptRendering; // Rendering di immagini raster utilizzando PostScript
        }
    };

    image.Save("Sample.png", options);
}
```

Ridimensiona l'immagine EPS utilizzando le impostazioni avanzate.

```csharp
[C#]

// Carica immagine EPS
using (var image = Image.Load("AstrixObelix.eps"))
{
    // Ridimensiona l'immagine utilizzando le impostazioni di ridimensionamento avanzate
    image.Resize(400, 400, new ImageResizeSettings
    {
        // Imposta la modalità di interpolazione
        Mode = ResizeType.LanczosResample,

        // Imposta il tipo di filtro
        FilterType = ImageFilterType.SmallRectangular,

        // Imposta il metodo di confronto dei colori
        ColorCompareMethod = ColorCompareMethod.Euclidian,

        // Imposta il metodo di quantizzazione del colore
        ColorQuantizationMethod = ColorQuantizationMethod.Popularity
    });

    // Esporta l'immagine in formato PNG
    image.Save("ExportResult.png", new PngOptions());
}
```

### Guarda anche

* class [VectorImage](../../aspose.imaging/vectorimage)
* spazio dei nomi [Aspose.Imaging.FileFormats.Eps](../../aspose.imaging.fileformats.eps)
* assemblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
