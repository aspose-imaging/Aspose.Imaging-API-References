---
title: ApngOptions
second_title: Aspose.Imaging for .NET API Reference
description: 
type: docs
weight: 9980
url: /net/aspose.imaging.imageoptions/apngoptions/
---
## ApngOptions class

The animated PNG file format options

```csharp
public class ApngOptions : PngOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [ApngOptions](apngoptions)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [BitDepth](../../aspose.imaging.imageoptions/pngoptions/bitdepth) { get; set; } | The bit depth. |
| [BufferSizeHint](../../aspose.imaging/imageoptionsbase/buffersizehint) { get; set; } | Gets or sets the buffer size hint which is defined max allowed size for all internal buffers. |
| [ColorType](../../aspose.imaging.imageoptions/pngoptions/colortype) { get; set; } | Gets or sets the type of the color. |
| [CompressionLevel](../../aspose.imaging.imageoptions/pngoptions/compressionlevel) { get; set; } | The png image compression level in the 0-9 range, where 9 is maximum compression and 0 is store mode. |
| [DefaultFrameTime](../../aspose.imaging.imageoptions/apngoptions/defaultframetime) { get; set; } | Gets or sets the default frame duration. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Gets a value indicating whether this instance is disposed. |
| [FilterType](../../aspose.imaging.imageoptions/pngoptions/filtertype) { get; set; } | Gets or sets the filter type used during png file save process. |
| [FullFrame](../../aspose.imaging/imageoptionsbase/fullframe) { get; set; } | Gets or sets a value indicating whether [full frame]. |
| [MultiPageOptions](../../aspose.imaging/imageoptionsbase/multipageoptions) { get; set; } | The multipage options |
| [NumPlays](../../aspose.imaging.imageoptions/apngoptions/numplays) { get; set; } | Gets or sets the number of times to loop animation. 0 indicates infinite looping. |
| virtual [Palette](../../aspose.imaging/imageoptionsbase/palette) { get; set; } | Gets or sets the color palette. |
| [ProgressEventHandler](../../aspose.imaging/imageoptionsbase/progresseventhandler) { get; set; } | Gets or sets the progress event handler. |
| [Progressive](../../aspose.imaging.imageoptions/pngoptions/progressive) { get; set; } | Gets or sets a value indicating whether this [`PngOptions`](../pngoptions) is progressive. |
| virtual [ResolutionSettings](../../aspose.imaging/imageoptionsbase/resolutionsettings) { get; set; } | Gets or sets the resolution settings. |
| [Source](../../aspose.imaging/imageoptionsbase/source) { get; set; } | Gets or sets the source to create image in. |
| [VectorRasterizationOptions](../../aspose.imaging/imageoptionsbase/vectorrasterizationoptions) { get; set; } | Gets or sets the vector rasterization options. |
| override [XmpData](../../aspose.imaging.imageoptions/pngoptions/xmpdata) { get; set; } | Gets or sets the XMP metadata container. |

## Methods

| Name | Description |
| --- | --- |
| virtual [Clone](../../aspose.imaging/imageoptionsbase/clone)() | Clones this instance. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Disposes the current instance. |

### Examples

The following example shows how to export apng APNG file format from other non-animated multi-page format.

```csharp
[C#]

using Aspose.Imaging;
using Aspose.Imaging.ImageOptions;

using (Image image = Image.Load("img4.tif")) {
    // Setting up the default frame duration
    image.Save("img4.tif.500ms.png", new ApngOptions() { DefaultFrameTime = 500 }); // 500 ms
    image.Save("img4.tif.250ms.png", new ApngOptions() { DefaultFrameTime = 250 }); // 250 ms
}
```

The following example shows how to export to APNG file format.

```csharp
[C#]

using Aspose.Imaging;
using Aspose.Imaging.ImageOptions;

using (Image image = Image.Load("Animation1.webp")) {
    // Export to APNG animation with unlimited animation cycles as default
    image.Save("Animation1.webp.png", new ApngOptions());
    // Setting up animation cycles
    image.Save("Animation2.webp.png", new ApngOptions() { NumPlays = 5 }); // 5 cycles
}
```

The following example shows how to create APNG image from another raster single-page image.

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
        // It is possible to set image default frame time there: apngImage.DefaultFrameTime = (uint)FrameDuration;

        int numOfFrames = AnimationDuration / FrameDuration;
        int numOfFrames2 = numOfFrames / 2;

        // Cleaning because the image contains one frame by default
        apngImage.RemoveAllFrames();

        // add first frame
        apngImage.AddFrame(sourceImage);

        // add intermediate frames
        for (int frameIndex = 1; frameIndex < numOfFrames - 1; ++frameIndex)
        {
            apngImage.AddFrame(sourceImage);
            ApngFrame lastFrame = (ApngFrame)apngImage.Pages[apngImage.PageCount - 1];
            float gamma = frameIndex >= numOfFrames2 ? numOfFrames - frameIndex - 1 : frameIndex;
            lastFrame.AdjustGamma(gamma);
        }

        // add last frame
        apngImage.AddFrame(sourceImage);

        apngImage.Save();
    }
}
```

### See Also

* class [PngOptions](../pngoptions)
* namespace [Aspose.Imaging.ImageOptions](../../aspose.imaging.imageoptions)
* assembly [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
