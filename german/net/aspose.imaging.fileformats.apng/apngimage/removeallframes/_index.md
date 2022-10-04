---
title: RemoveAllFrames
second_title: Aspose.Imaging für .NET-API-Referenz
description: Entfernt alle Frames aus der eigenen Frame-Sammlung.
type: docs
weight: 270
url: /de/net/aspose.imaging.fileformats.apng/apngimage/removeallframes/
---
## ApngImage.RemoveAllFrames method

Entfernt alle Frames aus der eigenen Frame-Sammlung.

```csharp
public void RemoveAllFrames()
```

### Beispiele

Das folgende Beispiel zeigt, wie Sie ein APNG-Bild aus einem anderen einseitigen Rasterbild erstellen.

```csharp
[C#]

using Aspose.Imaging;
using Aspose.Imaging.ImageOptions;
using Aspose.Imaging.FileFormats.Apng;

const int AnimationDuration = 1000; // 1 Sek
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
        // Es ist möglich, dort die Standard-Frame-Zeit des Bildes einzustellen: apngImage.DefaultFrameTime = (uint)FrameDuration;

        int numOfFrames = AnimationDuration / FrameDuration;
        int numOfFrames2 = numOfFrames / 2;

        // Bereinigen, da das Bild standardmäßig einen Frame enthält
        apngImage.RemoveAllFrames();

        // ersten Frame hinzufügen
        apngImage.AddFrame(sourceImage);

        // Zwischenframes hinzufügen
        for (int frameIndex = 1; frameIndex < numOfFrames - 1; ++frameIndex)
        {
            apngImage.AddFrame(sourceImage);
            ApngFrame lastFrame = (ApngFrame)apngImage.Pages[apngImage.PageCount - 1];
            float gamma = frameIndex >= numOfFrames2 ? numOfFrames - frameIndex - 1 : frameIndex;
            lastFrame.AdjustGamma(gamma);
        }

        // letzten Frame hinzufügen
        apngImage.AddFrame(sourceImage);

        apngImage.Save();
    }
}
```

### Siehe auch

* class [ApngImage](../../apngimage)
* namensraum [Aspose.Imaging.FileFormats.Apng](../../apngimage)
* Montage [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->