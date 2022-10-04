---
title: Html5CanvasOptions
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Opzioni di creazione del formato del file Canvas HTML5.
type: docs
weight: 10010
url: /it/net/aspose.imaging.imageoptions/html5canvasoptions/
---
## Html5CanvasOptions class

Opzioni di creazione del formato del file Canvas HTML5.

```csharp
public class Html5CanvasOptions : ImageOptionsBase
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [Html5CanvasOptions](html5canvasoptions)() | Default_Costruttore |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [BufferSizeHint](../../aspose.imaging/imageoptionsbase/buffersizehint) { get; set; } | Ottiene o imposta l'hint per la dimensione del buffer che è la dimensione massima consentita per tutti i buffer interni. |
| [CanvasTagId](../../aspose.imaging.imageoptions/html5canvasoptions/canvastagid) { get; set; } | Ottiene o imposta l'identificatore del tag canvas. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Ottiene un valore che indica se questa istanza è stata eliminata. |
| [Encoding](../../aspose.imaging.imageoptions/html5canvasoptions/encoding) { get; set; } | Ottiene o imposta la codifica. |
| [FullFrame](../../aspose.imaging/imageoptionsbase/fullframe) { get; set; } | Ottiene o imposta un valore che indica se [fotogramma intero]. |
| [FullHtmlPage](../../aspose.imaging.imageoptions/html5canvasoptions/fullhtmlpage) { get; set; } | Ottiene o imposta un valore che indica se deve essere generata la pagina HTML completa. |
| [MultiPageOptions](../../aspose.imaging/imageoptionsbase/multipageoptions) { get; set; } | Le opzioni multipagina |
| virtual [Palette](../../aspose.imaging/imageoptionsbase/palette) { get; set; } | Ottiene o imposta la tavolozza dei colori. |
| [ProgressEventHandler](../../aspose.imaging/imageoptionsbase/progresseventhandler) { get; set; } | Ottiene o imposta il gestore dell'evento di avanzamento. |
| virtual [ResolutionSettings](../../aspose.imaging/imageoptionsbase/resolutionsettings) { get; set; } | Ottiene o imposta le impostazioni di risoluzione. |
| [Source](../../aspose.imaging/imageoptionsbase/source) { get; set; } | Ottiene o imposta l'origine in cui creare l'immagine. |
| [VectorRasterizationOptions](../../aspose.imaging/imageoptionsbase/vectorrasterizationoptions) { get; set; } | Ottiene o imposta le opzioni di rasterizzazione del vettore. |
| virtual [XmpData](../../aspose.imaging/imageoptionsbase/xmpdata) { get; set; } | Ottiene o imposta il contenitore di metadati XMP. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| virtual [Clone](../../aspose.imaging/imageoptionsbase/clone)() | Clona questa istanza. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Elimina l'istanza corrente. |

### Esempi

Qualsiasi immagine vettoriale (SVG, WMF, CMX, ecc.) può essere utilizzata come origine per le immagini della tela. Il codice seguente crea una semplice immagine Canvas.

```csharp
[C#]

using (var image = Image.Load(@"Sample.svg"))
{
    image.Save(@"Canvas.html", new Html5CanvasOptions
    {
        VectorRasterizationOptions = new SvgRasterizationOptions()
    });
}
```

Puoi incorporare più di un'immagine Canvas all'interno di una pagina HTML o aggiornare una pagina già esistente. Per fare ciò devi esportare solo il tag Canvas.

```csharp
[C#]

using (var image = Image.Load(@"Sample.svg"))
{
    image.Save(@"Canvas.html", new Html5CanvasOptions
    {
        VectorRasterizationOptions = new SvgRasterizationOptions(),
        FullHtmlPage = false
    });
}
```

### Guarda anche

* class [ImageOptionsBase](../../aspose.imaging/imageoptionsbase)
* spazio dei nomi [Aspose.Imaging.ImageOptions](../../aspose.imaging.imageoptions)
* assemblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->