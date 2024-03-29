---
title: DefaultFrameTime
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Ottiene o imposta la durata del frame predefinita.
type: docs
weight: 20
url: /it/net/aspose.imaging.imageoptions/apngoptions/defaultframetime/
---
## ApngOptions.DefaultFrameTime property

Ottiene o imposta la durata del frame predefinita.

```csharp
public uint DefaultFrameTime { get; set; }
```

### Valore della proprietà

La durata del frame predefinita, in millisecondi.

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

* class [ApngOptions](../../apngoptions)
* spazio dei nomi [Aspose.Imaging.ImageOptions](../../apngoptions)
* assemblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
