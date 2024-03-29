---
title: RemoveAllFrames
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Rimuove tutti i frame dalla propria raccolta di frame.
type: docs
weight: 270
url: /it/net/aspose.imaging.fileformats.apng/apngimage/removeallframes/
---
## ApngImage.RemoveAllFrames method

Rimuove tutti i frame dalla propria raccolta di frame.

```csharp
public void RemoveAllFrames()
```

### Esempi

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

* class [ApngImage](../../apngimage)
* spazio dei nomi [Aspose.Imaging.FileFormats.Apng](../../apngimage)
* assemblea [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
