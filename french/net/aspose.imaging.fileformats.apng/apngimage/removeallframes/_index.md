---
title: RemoveAllFrames
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Supprime tous les cadres de la propre collection de cadres.
type: docs
weight: 270
url: /fr/net/aspose.imaging.fileformats.apng/apngimage/removeallframes/
---
## ApngImage.RemoveAllFrames method

Supprime tous les cadres de la propre collection de cadres.

```csharp
public void RemoveAllFrames()
```

### Exemples

L'exemple suivant montre comment créer une image APNG à partir d'une autre image raster d'une seule page.

```csharp
[C#]

using Aspose.Imaging;
using Aspose.Imaging.ImageOptions;
using Aspose.Imaging.FileFormats.Apng;

const int AnimationDuration = 1000; // 1 s
const int FrameDuration = 70; // 70 ms
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
        // Il est possible de définir ici le temps de trame par défaut de l'image : apngImage.DefaultFrameTime = (uint)FrameDuration ;

        int numOfFrames = AnimationDuration / FrameDuration;
        int numOfFrames2 = numOfFrames / 2;

        // Nettoyage car l'image contient un frame par défaut
        apngImage.RemoveAllFrames();

        // ajoute la première image
        apngImage.AddFrame(sourceImage);

        // ajoute des cadres intermédiaires
        for (int frameIndex = 1; frameIndex < numOfFrames - 1; ++frameIndex)
        {
            apngImage.AddFrame(sourceImage);
            ApngFrame lastFrame = (ApngFrame)apngImage.Pages[apngImage.PageCount - 1];
            float gamma = frameIndex >= numOfFrames2 ? numOfFrames - frameIndex - 1 : frameIndex;
            lastFrame.AdjustGamma(gamma);
        }

        // ajoute la dernière image
        apngImage.AddFrame(sourceImage);

        apngImage.Save();
    }
}
```

### Voir également

* class [ApngImage](../../apngimage)
* espace de noms [Aspose.Imaging.FileFormats.Apng](../../apngimage)
* Assemblée [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
