---
title: ApngImage
second_title: Aspose.Imaging for .NET API Reference
description: 
type: docs
weight: 1280
url: /net/aspose.imaging.fileformats.apng/apngimage/
---
## ApngImage class

The animated PNG image.

```csharp
public sealed class ApngImage : RasterCachedMultipageImage, IMultipageImageExt
```

## Constructors

| Name | Description |
| --- | --- |
| [ApngImage](apngimage)(ApngOptions, int, int) | Initializes a new instance of the [`ApngImage`](../apngimage) class. |

## Properties

| Name | Description |
| --- | --- |
| [DefaultFrameTime](defaultframetime) { get; set; } | Gets or sets the default frame duration. Used when creating new frames. |
| override [FileFormat](fileformat) { get; } | Gets a value of file format |
| [Interlaced](interlaced) { get; } | Gets a value indicating whether this [`PngImage`](../../aspose.imaging.fileformats.png/pngimage) is interlaced. |
| [NumPlays](numplays) { get; set; } | Gets or sets the number of times to loop animation. 0 indicates infinite looping. |
| override [PageCount](pagecount) { get; } | Gets the page count. |
| override [PageExportingAction](pageexportingaction) { get; set; } | Gets or sets the page exporting action. Please note that setting this method will automatically release page resources after it is executed. It will be executed just before each page is saved. |
| override [Pages](pages) { get; } | Gets the pages. |
| override [XmpData](xmpdata) { get; set; } | Gets or sets the XMP metadata. |

## Methods

| Name | Description |
| --- | --- |
| [AddFrame](addframe)() | Adds new frame to the end of the own frame collection. A new frame will be created according to the size of the current image. |
| [AddFrame](addframe)(RasterImage) | Adds new frame to the end of the own frame collection. The contents of the new frame will be filled from the specified image. |
| [AddFrame](addframe)(RasterImage, uint) | Adds new frame to the end of the own frame collection. The contents of the new frame will be filled from the specified image. |
| [AddPage](addpage)(RasterImage) | Adds page to the image. |
| override [AdjustBrightness](adjustbrightness)(int) | Adjust of a *brightness* for image. |
| override [AdjustContrast](adjustcontrast)(float) | [`Image`](../../aspose.imaging/image) contrasting |
| override [AdjustGamma](adjustgamma)(float) | Gamma-correction of an image. |
| override [AdjustGamma](adjustgamma)(float, float, float) | Gamma-correction of an image. |
| override [BinarizeBradley](binarizebradley)(double, int) | Binarization of an image using Bradley's adaptive thresholding algorithm using the integral image thresholding |
| override [BinarizeFixed](binarizefixed)(byte) | Binarization of an image with predefined threshold |
| override [BinarizeOtsu](binarizeotsu)() | Binarization of an image with Otsu thresholding |
| override [Crop](crop)(Rectangle) | Cropping the image. |
| override [Crop](crop)(int, int, int, int) | Crop image with shifts. |
| override [Dither](dither)(DitheringMethod, int, IColorPalette) | Performs dithering on the current image. |
| override [Filter](filter)(Rectangle, FilterOptionsBase) | Filters the specified rectangle. |
| override [GetDefaultOptions](getdefaultoptions)(object[]) | Gets the default options. |
| override [GetModifyDate](getmodifydate)(bool) | Gets the date and time the resource image was last modified. |
| override [GetOriginalOptions](getoriginaloptions)() | Gets the options based on the original file settings. This can be helpful to keep bit-depth and other parameters of the original image unchanged. For example, if we load a black-white PNG image with 1 bit per pixel and then save it using the [`Save`](../../aspose.imaging/datastreamsupporter/save) method, the output PNG image with 8-bit per pixel will be produced. To avoid it and save PNG image with 1-bit per pixel, use this method to get corresponding saving options and pass them to the [`Save`](../../aspose.imaging/image/save) method as the second parameter. |
| override [Grayscale](grayscale)() | Transformation of an image to its grayscale representation |
| [InsertFrame](insertframe)(int) | Inserts new frame into the own frame collection at the specified index. A new frame will be created according to the size of the current image. |
| [InsertFrame](insertframe)(int, RasterImage) | Inserts new frame into the own frame collection at the specified index. The contents of the new frame will be filled from the specified image. |
| [InsertFrame](insertframe)(int, RasterImage, uint) | Inserts new frame into the own frame collection at the specified index. The contents of the new frame will be filled from the specified image. |
| [PopFrameAt](popframeat)(int) | Removes and returns the frame at the specified index of the own frame collection. |
| [RemoveAllFrames](removeallframes)() | Removes all frames from the own frame collection. |
| [RemoveFrameAt](removeframeat)(int) | Removes the frame at the specified index of the own frame collection. The frame to be deleted will be disposed. |
| [ResetDefaultImage](resetdefaultimage)() | Deletes a previously set default image. After this, the default image is the first frame in the own frame collection (it cannot be deleted using this method). |
| override [Resize](resize)(int, int, ImageResizeSettings) | Resizes the image. |
| override [Resize](resize)(int, int, ResizeType) | Resizes the image. |
| override [ResizeHeightProportionally](resizeheightproportionally)(int, ResizeType) | Resizes the width proportionally. |
| override [ResizeWidthProportionally](resizewidthproportionally)(int, ResizeType) | Resizes the width proportionally. |
| override [Rotate](rotate)(float, bool, Color) | !:RasterCahcedMultipageImage.Rotate image around the center. |
| override [RotateFlip](rotateflip)(RotateFlipType) | Rotates, flips, or rotates and flips the Active frame only. |
| [SetDefaultImage](setdefaultimage)(RasterImage) | Sets the specified raster image as the default image of the current animation. |

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

* class [RasterCachedMultipageImage](../../aspose.imaging/rastercachedmultipageimage)
* interface [IMultipageImageExt](../../aspose.imaging/imultipageimageext)
* namespace [Aspose.Imaging.FileFormats.Apng](../../aspose.imaging.fileformats.apng)
* assembly [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
