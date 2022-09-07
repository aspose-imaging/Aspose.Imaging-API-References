---
title: ApngOptions
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Opzioni del formato del file PNG animato
type: docs
weight: 9900
url: /it/net/aspose.imaging.imageoptions/apngoptions/
---
## ApngOptions class

Opzioni del formato del file PNG animato

```csharp
public class ApngOptions : PngOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [ApngOptions](apngoptions)() | Default_Costruttore |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [BitDepth](../../aspose.imaging.imageoptions/pngoptions/bitdepth) { get; set; } | La profondità di bit. |
| [BufferSizeHint](../../aspose.imaging/imageoptionsbase/buffersizehint) { get; set; } | Ottiene o imposta l'hint per la dimensione del buffer che è la dimensione massima consentita per tutti i buffer interni. |
| [ColorType](../../aspose.imaging.imageoptions/pngoptions/colortype) { get; set; } | Ottiene o imposta il tipo del colore. |
| [CompressionLevel](../../aspose.imaging.imageoptions/pngoptions/compressionlevel) { get; set; } | Il livello di compressione dell'immagine png nell'intervallo 0-9, dove 9 è la compressione massima e 0 è la modalità di memorizzazione. |
| [DefaultFrameTime](../../aspose.imaging.imageoptions/apngoptions/defaultframetime) { get; set; } | Ottiene o imposta la durata del frame predefinita. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Ottiene un valore che indica se questa istanza è stata eliminata. |
| [FilterType](../../aspose.imaging.imageoptions/pngoptions/filtertype) { get; set; } | Ottiene o imposta il tipo di filtro utilizzato durante il processo di salvataggio del file png. |
| [FullFrame](../../aspose.imaging/imageoptionsbase/fullframe) { get; set; } | Ottiene o imposta un valore che indica se [fotogramma intero]. |
| [MultiPageOptions](../../aspose.imaging/imageoptionsbase/multipageoptions) { get; set; } | Le opzioni multipagina |
| [NumPlays](../../aspose.imaging.imageoptions/apngoptions/numplays) { get; set; } | Ottiene o imposta il numero di volte in cui eseguire il ciclo dell'animazione. 0 indica il ciclo infinito. |
| virtual [Palette](../../aspose.imaging/imageoptionsbase/palette) { get; set; } | Ottiene o imposta la tavolozza dei colori. |
| [ProgressEventHandler](../../aspose.imaging/imageoptionsbase/progresseventhandler) { get; set; } | Ottiene o imposta il gestore dell'evento di avanzamento. |
| [Progressive](../../aspose.imaging.imageoptions/pngoptions/progressive) { get; set; } | Ottiene o imposta un valore che indica se questo[`PngOptions`](../pngoptions) è progressivo. |
| virtual [ResolutionSettings](../../aspose.imaging/imageoptionsbase/resolutionsettings) { get; set; } | Ottiene o imposta le impostazioni di risoluzione. |
| [Source](../../aspose.imaging/imageoptionsbase/source) { get; set; } | Ottiene o imposta l'origine in cui creare l'immagine. |
| [VectorRasterizationOptions](../../aspose.imaging/imageoptionsbase/vectorrasterizationoptions) { get; set; } | Ottiene o imposta le opzioni di rasterizzazione del vettore. |
| override [XmpData](../../aspose.imaging.imageoptions/pngoptions/xmpdata) { get; set; } | Ottiene o imposta il contenitore di metadati XMP. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| virtual [Clone](../../aspose.imaging/imageoptionsbase/clone)() | Clona questa istanza. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Elimina l'istanza corrente. |

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

* class [PngOptions](../pngoptions)
* spazio dei nomi [Aspose.Imaging.ImageOptions](../../aspose.imaging.imageoptions)
* assemblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
