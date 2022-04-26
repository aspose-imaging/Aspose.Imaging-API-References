---
title: GifImage
second_title: Aspose.Imaging for .NET API Reference
description: 
type: docs
weight: 6660
url: /net/aspose.imaging.fileformats.gif/gifimage/
---
## GifImage class

A gif image.

```csharp
public sealed class GifImage : RasterCachedMultipageImage, IMultipageImageExt
```

## Constructors

| Name | Description |
| --- | --- |
| [GifImage](gifimage)(GifFrameBlock) | Initializes a new instance of the [`GifImage`](../gifimage) class. |
| [GifImage](gifimage)(GifFrameBlock, IColorPalette) | Initializes a new instance of the [`GifImage`](../gifimage) class. |
| [GifImage](gifimage)(GifFrameBlock, IColorPalette, bool, byte, byte, byte, bool) | Initializes a new instance of the [`GifImage`](../gifimage) class. |

## Properties

| Name | Description |
| --- | --- |
| [ActiveFrame](activeframe) { get; set; } | Gets or sets the active frame. |
| override [BackgroundColor](backgroundcolor) { get; set; } | Gets or sets the background color. |
| [BackgroundColorIndex](backgroundcolorindex) { get; set; } | Gets or sets the background color index. |
| [Blocks](blocks) { get; } | Gets the GIF blocks. |
| override [FileFormat](fileformat) { get; } | Gets a value of file format |
| override [HasBackgroundColor](hasbackgroundcolor) { get; } | Gets a value indicating whether image has background color. |
| [HasTrailer](hastrailer) { get; set; } | Gets or sets a value indicating whether GIF has trailer. |
| override [HasTransparentColor](hastransparentcolor) { get; set; } | Gets a value indicating whether active frame has transparent color. |
| override [ImageOpacity](imageopacity) { get; } | Gets opacity of this image (active frame). |
| [IsInterlaced](isinterlaced) { get; } | Gets a value indicating whether this image instance is interlaced. |
| [IsPaletteSorted](ispalettesorted) { get; set; } | Gets or sets a value indicating whether palette is sorted. |
| [LoopsCount](loopscount) { get; set; } | Gets the loops count (If gif image contains information about loops) |
| override [PageCount](pagecount) { get; } | Gets the page count. |
| override [PageExportingAction](pageexportingaction) { get; set; } | Gets or sets the page exporting action. Please note that setting this method will automatically release page resources after it is executed. It will be executed just before each page is saved. |
| override [Pages](pages) { get; } | Gets the pages. |
| [PaletteColorResolutionBits](palettecolorresolutionbits) { get; set; } | Gets or sets the palette color resolution bits. |
| [PixelAspectRatio](pixelaspectratio) { get; set; } | Gets or sets the pixel aspect ratio. |
| override [TransparentColor](transparentcolor) { get; } | Gets active frame transparent color. |
| override [XmpData](xmpdata) { get; set; } | Gets or sets the XMP metadata. |

## Methods

| Name | Description |
| --- | --- |
| [AddBlock](addblock)(IGifBlock) | Adds a new GIF block. |
| [AddPage](addpage)(RasterImage) | Adds page to the image. |
| override [AdjustBrightness](adjustbrightness)(int) | Adjust of a *brightness* for image. |
| override [AdjustContrast](adjustcontrast)(float) | Adjusts the contrast. |
| override [AdjustGamma](adjustgamma)(float) | Gamma-correction of an image. |
| override [AdjustGamma](adjustgamma)(float, float, float) | Gamma-correction of an image. |
| override [BinarizeBradley](binarizebradley)(double) | Binarization of an image using Bradley's adaptive thresholding algorithm using the integral image thresholding |
| override [BinarizeFixed](binarizefixed)(byte) | Binarization of an image with predefined threshold |
| override [BinarizeOtsu](binarizeotsu)() | Binarization of an image with Otsu thresholding |
| [ClearBlocks](clearblocks)() | Clears all the GIF blocks. |
| override [Crop](crop)(Rectangle) | Cropping the image. |
| override [Dither](dither)(DitheringMethod, int, IColorPalette) | Performs dithering on the current image. |
| override [Filter](filter)(Rectangle, FilterOptionsBase) | Filters the specified rectangle. |
| override [GetOriginalOptions](getoriginaloptions)() | Gets the options based on the original file settings. This can be helpful to keep bit-depth and other parameters of the original image unchanged. For example, if we load a black-white PNG image with 1 bit per pixel and then save it using the [`Save`](../../aspose.imaging/datastreamsupporter/save) method, the output PNG image with 8-bit per pixel will be produced. To avoid it and save PNG image with 1-bit per pixel, use this method to get corresponding saving options and pass them to the [`Save`](../../aspose.imaging/image/save) method as the second parameter. |
| override [Grayscale](grayscale)() | Transformation of an image to its grayscale representation |
| [InsertBlock](insertblock)(int, IGifBlock) | Adds a new GIF block. |
| [OrderBlocks](orderblocks)() | Orders the GIF blocks according to the GIF specification. Some [`GifGraphicsControlBlock`](../../aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock) may be removed for proper GIF layout. |
| [RemoveBlock](removeblock)(IGifBlock) | Removes the GIF block. |
| override [Resize](resize)(int, int, ImageResizeSettings) | Resizes the image. |
| override [Resize](resize)(int, int, ResizeType) | Resizes the image. |
| [ResizeProportional](resizeproportional)(int, int, ResizeType) | Performs proportional resize on the image. The proportional resize will resize each frame according to the ratio of *newWidth*/width and *newHeight*/height. |
| override [Rotate](rotate)(float, bool, Color) | !:RasterCahcedMultipageImage.Rotate image around the center. |
| override [RotateFlip](rotateflip)(RotateFlipType) | Rotates, flips, or rotates and flips the Active frame only. |
| [SetFrameTime](setframetime)(ushort) | Sets all frames duration in milliseconds. Changing this value will reset delay for all frames. |

### Examples

Export of part of animation from GIF image based on time interval.

```csharp
[C#]

using (var image = Image.Load("Animation.gif"))
{
    var options = new GifOptions
    {
        FullFrame = true,
        MultiPageOptions = new MultiPageOptions
        {
            Mode = MultiPageMode.TimeInterval,
            TimeInterval = new TimeInterval(0, 400)
        }
    };

    image.Save("PartOfAnimation.gif", options);
}
```

This example shows how to create a GIF image and save it to a file.

```csharp
[C#]

string dir = "c:\\temp\\";

// Create a GIF Frame block of 100x100 px.
using (Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock firstBlock = new Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock(100, 100))
{
    // Fill the entire block in red.
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(firstBlock);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    gr.FillRectangle(brush, firstBlock.Bounds);

    using (Aspose.Imaging.FileFormats.Gif.GifImage gifImage = new Aspose.Imaging.FileFormats.Gif.GifImage(firstBlock))
    {
        gifImage.Save(dir + "output.gif");
    }
}
```

Create multipage GIF image using single page raster images.

```csharp
[C#]

static void Main(string[] args)
{
    // Load frames
    var frames = LoadFrames("Animation frames").ToArray();

    // Create GIF image using the first frame
    using (var image = new GifImage(new GifFrameBlock(frames[0])))
    {
        // Add frames to the GIF image using the AddPage method
        for (var index = 1; index < frames.Length; index++)
        {
            image.AddPage(frames[index]);
        }

        // Save GIF image
        image.Save("Multipage.gif");
    }
}

private static IEnumerable<RasterImage> LoadFrames(string directory)
{
    foreach (var filePath in Directory.GetFiles(directory))
    {
        yield return (RasterImage)Image.Load(filePath);
    }
}
```

### See Also

* class [RasterCachedMultipageImage](../../aspose.imaging/rastercachedmultipageimage)
* interface [IMultipageImageExt](../../aspose.imaging/imultipageimageext)
* namespace [Aspose.Imaging.FileFormats.Gif](../../aspose.imaging.fileformats.gif)
* assembly [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
