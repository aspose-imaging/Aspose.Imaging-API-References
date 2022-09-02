---
title: ApngOptions
second_title: Aspose.Imaging för .NET API-referens
description: Det animerade PNG-filformatet options
type: docs
weight: 9900
url: /sv/net/aspose.imaging.imageoptions/apngoptions/
---
## ApngOptions class

Det animerade PNG-filformatet options

```csharp
public class ApngOptions : PngOptions
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [ApngOptions](apngoptions)() | Default_Constructor |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [BitDepth](../../aspose.imaging.imageoptions/pngoptions/bitdepth) { get; set; } | Bitdjupet. |
| [BufferSizeHint](../../aspose.imaging/imageoptionsbase/buffersizehint) { get; set; } | Hämtar eller ställer in buffertstorlekstipset som är definierat som högsta tillåtna storlek för alla interna buffertar. |
| [ColorType](../../aspose.imaging.imageoptions/pngoptions/colortype) { get; set; } | Hämtar eller ställer in typ av färg. |
| [CompressionLevel](../../aspose.imaging.imageoptions/pngoptions/compressionlevel) { get; set; } | Png-bildkomprimeringsnivån i intervallet 0-9, där 9 är maximal komprimering och 0 är lagringsläge. |
| [DefaultFrameTime](../../aspose.imaging.imageoptions/apngoptions/defaultframetime) { get; set; } | Hämtar eller ställer in standardbildlängden. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Får ett värde som indikerar om denna instans är bortskaffad. |
| [FilterType](../../aspose.imaging.imageoptions/pngoptions/filtertype) { get; set; } | Hämtar eller ställer in filtertypen som används under png-filsparprocessen. |
| [FullFrame](../../aspose.imaging/imageoptionsbase/fullframe) { get; set; } | Hämtar eller ställer in ett värde som anger om [helbild]. |
| [MultiPageOptions](../../aspose.imaging/imageoptionsbase/multipageoptions) { get; set; } | Alternativen för flera sidor |
| [NumPlays](../../aspose.imaging.imageoptions/apngoptions/numplays) { get; set; } | Hämtar eller ställer in antalet gånger för loop-animering. 0 indikerar oändlig looping. |
| virtual [Palette](../../aspose.imaging/imageoptionsbase/palette) { get; set; } | Hämtar eller ställer in färgpaletten. |
| [ProgressEventHandler](../../aspose.imaging/imageoptionsbase/progresseventhandler) { get; set; } | Hämtar eller ställer in förloppshändelsehanteraren. |
| [Progressive](../../aspose.imaging.imageoptions/pngoptions/progressive) { get; set; } | Hämtar eller ställer in ett värde som indikerar om detta[`PngOptions`](../pngoptions) är progressiv. |
| virtual [ResolutionSettings](../../aspose.imaging/imageoptionsbase/resolutionsettings) { get; set; } | Hämtar eller ställer in upplösningsinställningarna. |
| [Source](../../aspose.imaging/imageoptionsbase/source) { get; set; } | Hämtar eller ställer in källan för att skapa bild i. |
| [VectorRasterizationOptions](../../aspose.imaging/imageoptionsbase/vectorrasterizationoptions) { get; set; } | Hämtar eller ställer in vektorrasteriseringsalternativen. |
| override [XmpData](../../aspose.imaging.imageoptions/pngoptions/xmpdata) { get; set; } | Hämtar eller ställer in XMP-metadatabehållaren. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| virtual [Clone](../../aspose.imaging/imageoptionsbase/clone)() | Klonar den här instansen. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Tar bort den aktuella instansen. |

### Exempel

Följande exempel visar hur man exporterar apng APNG-filformat från andra icke-animerade flersidiga format.

```csharp
[C#]

using Aspose.Imaging;
using Aspose.Imaging.ImageOptions;

using (Image image = Image.Load("img4.tif")) {
    // Ställa in standardbildlängden
    image.Save("img4.tif.500ms.png", new ApngOptions() { DefaultFrameTime = 500 }); // 500 ms
    image.Save("img4.tif.250ms.png", new ApngOptions() { DefaultFrameTime = 250 }); // 250 ms
}
```

Följande exempel visar hur man exporterar till APNG-filformat.

```csharp
[C#]

using Aspose.Imaging;
using Aspose.Imaging.ImageOptions;

using (Image image = Image.Load("Animation1.webp")) {
    // Exportera till APNG-animering med obegränsade animeringscykler som standard
    image.Save("Animation1.webp.png", new ApngOptions());
    // Ställa in animationscykler
    image.Save("Animation2.webp.png", new ApngOptions() { NumPlays = 5 }); // 5 cykler
}
```

Följande exempel visar hur man skapar APNG-bild från en annan rasterbild på en sida.

```csharp
[C#]

using Aspose.Imaging;
using Aspose.Imaging.ImageOptions;
using Aspose.Imaging.FileFormats.Apng;

const int AnimationDuration = 1000; // 1 s
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
        // Det är möjligt att ställa in bildens standardbildtid där: apngImage.DefaultFrameTime = (uint)FrameDuration;

        int numOfFrames = AnimationDuration / FrameDuration;
        int numOfFrames2 = numOfFrames / 2;

        // Rengöring eftersom bilden innehåller en ram som standard
        apngImage.RemoveAllFrames();

        // lägg till första bildrutan
        apngImage.AddFrame(sourceImage);

        // lägg till mellanliggande ramar
        for (int frameIndex = 1; frameIndex < numOfFrames - 1; ++frameIndex)
        {
            apngImage.AddFrame(sourceImage);
            ApngFrame lastFrame = (ApngFrame)apngImage.Pages[apngImage.PageCount - 1];
            float gamma = frameIndex >= numOfFrames2 ? numOfFrames - frameIndex - 1 : frameIndex;
            lastFrame.AdjustGamma(gamma);
        }

        // lägg till sista bildrutan
        apngImage.AddFrame(sourceImage);

        apngImage.Save();
    }
}
```

### Se även

* class [PngOptions](../pngoptions)
* namnutrymme [Aspose.Imaging.ImageOptions](../../aspose.imaging.imageoptions)
* hopsättning [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
