---
title: OtgRasterizationOptions
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Le opzioni di rasterizzazione Otg
type: docs
weight: 10090
url: /it/net/aspose.imaging.imageoptions/otgrasterizationoptions/
---
## OtgRasterizationOptions class

Le opzioni di rasterizzazione Otg

```csharp
public class OtgRasterizationOptions : OdRasterizationOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [OtgRasterizationOptions](otgrasterizationoptions)() | Default_Costruttore |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [BackgroundColor](../../aspose.imaging.imageoptions/vectorrasterizationoptions/backgroundcolor) { get; set; } | Ottiene o imposta un colore di sfondo. |
| [BorderX](../../aspose.imaging.imageoptions/vectorrasterizationoptions/borderx) { get; set; } | Ottiene o imposta il bordo X. |
| [BorderY](../../aspose.imaging.imageoptions/vectorrasterizationoptions/bordery) { get; set; } | Ottiene o imposta il bordo Y. |
| [BufferSizeHint](../../aspose.imaging/imageoptionsbase/buffersizehint) { get; set; } | Ottiene o imposta l'hint per la dimensione del buffer che è la dimensione massima consentita per tutti i buffer interni. |
| [CenterDrawing](../../aspose.imaging.imageoptions/vectorrasterizationoptions/centerdrawing) { get; set; } | Ottiene o imposta un valore che indica se centrare il disegno. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Ottiene un valore che indica se questa istanza è stata eliminata. |
| [DrawColor](../../aspose.imaging.imageoptions/vectorrasterizationoptions/drawcolor) { get; set; } | Ottiene o imposta un colore di primo piano. |
| [FullFrame](../../aspose.imaging/imageoptionsbase/fullframe) { get; set; } | Ottiene o imposta un valore che indica se [fotogramma intero]. |
| [MultiPageOptions](../../aspose.imaging/imageoptionsbase/multipageoptions) { get; set; } | Le opzioni multipagina |
| [PageHeight](../../aspose.imaging.imageoptions/vectorrasterizationoptions/pageheight) { get; set; } | Ottiene o imposta l'altezza della pagina. |
| [PageSize](../../aspose.imaging.imageoptions/vectorrasterizationoptions/pagesize) { get; set; } | Ottiene o imposta la dimensione della pagina. |
| [PageWidth](../../aspose.imaging.imageoptions/vectorrasterizationoptions/pagewidth) { get; set; } | Ottiene o imposta la larghezza della pagina. |
| virtual [Palette](../../aspose.imaging/imageoptionsbase/palette) { get; set; } | Ottiene o imposta la tavolozza dei colori. |
| [Positioning](../../aspose.imaging.imageoptions/vectorrasterizationoptions/positioning) { get; set; } | Ottiene o imposta il posizionamento. |
| [ProgressEventHandler](../../aspose.imaging/imageoptionsbase/progresseventhandler) { get; set; } | Ottiene o imposta il gestore dell'evento di avanzamento. |
| virtual [ResolutionSettings](../../aspose.imaging/imageoptionsbase/resolutionsettings) { get; set; } | Ottiene o imposta le impostazioni di risoluzione. |
| [SmoothingMode](../../aspose.imaging.imageoptions/vectorrasterizationoptions/smoothingmode) { get; set; } | Ottiene o imposta la modalità di smoothing. |
| [Source](../../aspose.imaging/imageoptionsbase/source) { get; set; } | Ottiene o imposta l'origine in cui creare l'immagine. |
| [TextRenderingHint](../../aspose.imaging.imageoptions/vectorrasterizationoptions/textrenderinghint) { get; set; } | Ottiene o imposta il suggerimento per il rendering del testo. |
| [VectorRasterizationOptions](../../aspose.imaging/imageoptionsbase/vectorrasterizationoptions) { get; set; } | Ottiene o imposta le opzioni di rasterizzazione del vettore. |
| virtual [XmpData](../../aspose.imaging/imageoptionsbase/xmpdata) { get; set; } | Ottiene o imposta il contenitore di metadati XMP. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| virtual [Clone](../../aspose.imaging/imageoptionsbase/clone)() | Clona questa istanza. |
| [CopyTo](../../aspose.imaging.imageoptions/vectorrasterizationoptions/copyto)(VectorRasterizationOptions) | Copia in. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Elimina l'istanza corrente. |

### Esempi

Il seguente frammento di codice mostra come convertire un'immagine OTG in PDF e altri formati di immagine.

```csharp
[C#]

string dir = "c:\\aspose.imaging\\issues\\net\\3567\\";
string inputFilePath = dir + "VariousObjectsMultiPage.otg";
Aspose.Imaging.ImageOptionsBase[] options = { new Aspose.Imaging.ImageOptions.PngOptions(), new Aspose.Imaging.ImageOptions.PdfOptions() };
foreach (Aspose.Imaging.ImageOptionsBase saveOptions in options)
{
    string extension = saveOptions is Aspose.Imaging.ImageOptions.PngOptions ? ".png" : ".pdf";
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFilePath))
    {
        Aspose.Imaging.ImageOptions.OtgRasterizationOptions otgRasterizationOptions = new Aspose.Imaging.ImageOptions.OtgRasterizationOptions();
        otgRasterizationOptions.PageSize = image.Size;
        saveOptions.VectorRasterizationOptions = otgRasterizationOptions;

        image.Save(inputFilePath + extension, saveOptions);
    }
}
```

### Guarda anche

* class [OdRasterizationOptions](../odrasterizationoptions)
* spazio dei nomi [Aspose.Imaging.ImageOptions](../../aspose.imaging.imageoptions)
* assemblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
