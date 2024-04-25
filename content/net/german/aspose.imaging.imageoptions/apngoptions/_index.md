---
title: ApngOptions
second_title: Aspose.Imaging für .NET-API-Referenz
description: Das animierte PNG-Dateiformat options
type: docs
weight: 9900
url: /de/aspose.imaging.imageoptions/apngoptions/
---
## ApngOptions class

Das animierte PNG-Dateiformat options

```csharp
public class ApngOptions : PngOptions
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [ApngOptions](apngoptions)() | Default_Constructor |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [BitDepth](../../aspose.imaging.imageoptions/pngoptions/bitdepth) { get; set; } | Die Bittiefe. |
| [BufferSizeHint](../../aspose.imaging/imageoptionsbase/buffersizehint) { get; set; } | Ruft den Puffergrößenhinweis ab oder legt ihn fest, der als maximal zulässige Größe für alle internen Puffer definiert ist. |
| [ColorType](../../aspose.imaging.imageoptions/pngoptions/colortype) { get; set; } | Ruft den Typ der Farbe ab oder legt ihn fest. |
| [CompressionLevel](../../aspose.imaging.imageoptions/pngoptions/compressionlevel) { get; set; } | Die PNG-Bildkomprimierungsstufe im Bereich von 0 bis 9, wobei 9 die maximale Komprimierung und 0 der Speichermodus ist. |
| [DefaultFrameTime](../../aspose.imaging.imageoptions/apngoptions/defaultframetime) { get; set; } | Ruft die Standard-Frame-Dauer ab oder legt sie fest. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Ruft einen Wert ab, der angibt, ob diese Instanz verworfen wird. |
| [FilterType](../../aspose.imaging.imageoptions/pngoptions/filtertype) { get; set; } | Ruft den beim Speichern der PNG-Datei verwendeten Filtertyp ab oder legt ihn fest. |
| [FullFrame](../../aspose.imaging/imageoptionsbase/fullframe) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob [Vollbild]. |
| [MultiPageOptions](../../aspose.imaging/imageoptionsbase/multipageoptions) { get; set; } | Die mehrseitigen Optionen |
| [NumPlays](../../aspose.imaging.imageoptions/apngoptions/numplays) { get; set; } | Ruft ab oder legt fest, wie oft die Animation wiederholt werden soll. 0 bedeutet Endlosschleife. |
| virtual [Palette](../../aspose.imaging/imageoptionsbase/palette) { get; set; } | Ruft die Farbpalette ab oder legt sie fest. |
| [ProgressEventHandler](../../aspose.imaging/imageoptionsbase/progresseventhandler) { get; set; } | Ruft den Fortschrittsereignishandler ab oder legt ihn fest. |
| [Progressive](../../aspose.imaging.imageoptions/pngoptions/progressive) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob dies der Fall ist[`PngOptions`](../pngoptions) ist progressiv. |
| virtual [ResolutionSettings](../../aspose.imaging/imageoptionsbase/resolutionsettings) { get; set; } | Ruft die Auflösungseinstellungen ab oder legt sie fest. |
| [Source](../../aspose.imaging/imageoptionsbase/source) { get; set; } | Ruft die Quelle zum Erstellen des Bildes ab oder legt sie fest. |
| [VectorRasterizationOptions](../../aspose.imaging/imageoptionsbase/vectorrasterizationoptions) { get; set; } | Ruft die Optionen für die Vektorrasterung ab oder legt sie fest. |
| override [XmpData](../../aspose.imaging.imageoptions/pngoptions/xmpdata) { get; set; } | Ruft den XMP-Metadatencontainer ab oder legt ihn fest. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| virtual [Clone](../../aspose.imaging/imageoptionsbase/clone)() | Klont diese Instanz. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Verwirft die aktuelle Instanz. |

### Beispiele

Das folgende Beispiel zeigt, wie das Dateiformat apng APNG aus einem anderen nicht animierten mehrseitigen Format exportiert wird.

```csharp
[C#]

using Aspose.Imaging;
using Aspose.Imaging.ImageOptions;

using (Image image = Image.Load("img4.tif")) {
    // Festlegen der Standard-Frame-Dauer
    image.Save("img4.tif.500ms.png", new ApngOptions() { DefaultFrameTime = 500 }); // 500 ms
    image.Save("img4.tif.250ms.png", new ApngOptions() { DefaultFrameTime = 250 }); // 250 ms
}
```

Das folgende Beispiel zeigt, wie Sie in das APNG-Dateiformat exportieren.

```csharp
[C#]

using Aspose.Imaging;
using Aspose.Imaging.ImageOptions;

using (Image image = Image.Load("Animation1.webp")) {
    // Export in APNG-Animation mit unbegrenzten Animationszyklen als Standard
    image.Save("Animation1.webp.png", new ApngOptions());
    // Animationszyklen einrichten
    image.Save("Animation2.webp.png", new ApngOptions() { NumPlays = 5 }); // 5 Zyklen
}
```

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

* class [PngOptions](../pngoptions)
* namensraum [Aspose.Imaging.ImageOptions](../../aspose.imaging.imageoptions)
* Montage [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
