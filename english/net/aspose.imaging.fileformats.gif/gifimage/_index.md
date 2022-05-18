---
title: GifImage
second_title: Aspose.Imaging for .NET API Reference
description: 
type: docs
weight: 6690
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
| [ActiveFrame](../../aspose.imaging.fileformats.gif/gifimage/activeframe) { get; set; } | Gets or sets the active frame. |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette) { get; set; } | Gets or sets a value indicating whether automatic adjust palette. |
| override [BackgroundColor](../../aspose.imaging.fileformats.gif/gifimage/backgroundcolor) { get; set; } | Gets or sets the background color. |
| [BackgroundColorIndex](../../aspose.imaging.fileformats.gif/gifimage/backgroundcolorindex) { get; set; } | Gets or sets the background color index. |
| override [BitsPerPixel](../../aspose.imaging/rastercachedmultipageimage/bitsperpixel) { get; } | Gets the image bits per pixel count. |
| [Blocks](../../aspose.imaging.fileformats.gif/gifimage/blocks) { get; } | Gets the GIF blocks. |
| [Bounds](../../aspose.imaging/image/bounds) { get; } | Gets the image bounds. |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint) { get; set; } | Gets or sets the buffer size hint which is defined max allowed size for all internal buffers. |
| [Container](../../aspose.imaging/image/container) { get; } | Gets the [`Image`](../../aspose.imaging/image) container. |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer) { get; } | Gets the object's data stream. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Gets a value indicating whether this instance is disposed. |
| override [FileFormat](../../aspose.imaging.fileformats.gif/gifimage/fileformat) { get; } | Gets a value of file format |
| override [HasAlpha](../../aspose.imaging/rastercachedmultipageimage/hasalpha) { get; } | Gets a value indicating whether this instance has alpha. |
| override [HasBackgroundColor](../../aspose.imaging.fileformats.gif/gifimage/hasbackgroundcolor) { get; } | Gets a value indicating whether image has background color. |
| [HasTrailer](../../aspose.imaging.fileformats.gif/gifimage/hastrailer) { get; set; } | Gets or sets a value indicating whether GIF has trailer. |
| override [HasTransparentColor](../../aspose.imaging.fileformats.gif/gifimage/hastransparentcolor) { get; set; } | Gets a value indicating whether active frame has transparent color. |
| override [Height](../../aspose.imaging/rastercachedmultipageimage/height) { get; } | Gets the image height. |
| virtual [HorizontalResolution](../../aspose.imaging/rasterimage/horizontalresolution) { get; set; } | Gets or sets the horizontal resolution, in pixels per inch, of this [`RasterImage`](../../aspose.imaging/rasterimage). |
| override [ImageOpacity](../../aspose.imaging.fileformats.gif/gifimage/imageopacity) { get; } | Gets opacity of this image (active frame). |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor) { get; set; } | Gets or sets the interrupt monitor. |
| [IsCached](../../aspose.imaging/rastercachedmultipageimage/iscached) { get; } | Gets a value indicating whether image data is cached currently. |
| [IsInterlaced](../../aspose.imaging.fileformats.gif/gifimage/isinterlaced) { get; } | Gets a value indicating whether this image instance is interlaced. |
| [IsPaletteSorted](../../aspose.imaging.fileformats.gif/gifimage/ispalettesorted) { get; set; } | Gets or sets a value indicating whether palette is sorted. |
| [IsRawDataAvailable](../../aspose.imaging/rasterimage/israwdataavailable) { get; } | Gets a value indicating whether raw data loading is available. |
| [LoopsCount](../../aspose.imaging.fileformats.gif/gifimage/loopscount) { get; set; } | Gets the loops count (If gif image contains information about loops) |
| override [PageCount](../../aspose.imaging.fileformats.gif/gifimage/pagecount) { get; } | Gets the page count. |
| override [PageExportingAction](../../aspose.imaging.fileformats.gif/gifimage/pageexportingaction) { get; set; } | Gets or sets the page exporting action. Please note that setting this method will automatically release page resources after it is executed. It will be executed just before each page is saved. |
| override [Pages](../../aspose.imaging.fileformats.gif/gifimage/pages) { get; } | Gets the pages. |
| [Palette](../../aspose.imaging/image/palette) { get; set; } | Gets or sets the color palette. The color palette is not used when pixels are represented directly. |
| [PaletteColorResolutionBits](../../aspose.imaging.fileformats.gif/gifimage/palettecolorresolutionbits) { get; set; } | Gets or sets the palette color resolution bits. |
| [PixelAspectRatio](../../aspose.imaging.fileformats.gif/gifimage/pixelaspectratio) { get; set; } | Gets or sets the pixel aspect ratio. |
| virtual [PremultiplyComponents](../../aspose.imaging/rasterimage/premultiplycomponents) { get; set; } | Gets or sets a value indicating whether the image components must be premultiplied. |
| [RawCustomColorConverter](../../aspose.imaging/rasterimage/rawcustomcolorconverter) { get; set; } | Gets or sets the custom color converter |
| virtual [RawDataFormat](../../aspose.imaging/rasterimage/rawdataformat) { get; } | Gets the raw data format. |
| [RawDataSettings](../../aspose.imaging/rasterimage/rawdatasettings) { get; } | Gets the current raw data settings. Note when using these settings the data loads without conversion. |
| [RawFallbackIndex](../../aspose.imaging/rasterimage/rawfallbackindex) { get; set; } | Gets or sets the fallback index to use when palette index is out of bounds |
| [RawIndexedColorConverter](../../aspose.imaging/rasterimage/rawindexedcolorconverter) { get; set; } | Gets or sets the indexed color converter |
| virtual [RawLineSize](../../aspose.imaging/rasterimage/rawlinesize) { get; } | Gets the raw line size in bytes. |
| [Size](../../aspose.imaging/image/size) { get; } | Gets the image size. |
| override [TransparentColor](../../aspose.imaging.fileformats.gif/gifimage/transparentcolor) { get; } | Gets active frame transparent color. |
| virtual [UpdateXmpData](../../aspose.imaging/rasterimage/updatexmpdata) { get; set; } | Gets or sets a value indicating whether to update the XMP metadata. |
| override [UsePalette](../../aspose.imaging/rasterimage/usepalette) { get; } | Gets a value indicating whether the image palette is used. |
| virtual [UseRawData](../../aspose.imaging/rasterimage/userawdata) { get; set; } | Gets or sets a value indicating whether to use raw data loading when the raw data loading is available. |
| virtual [VerticalResolution](../../aspose.imaging/rasterimage/verticalresolution) { get; set; } | Gets or sets the vertical resolution, in pixels per inch, of this [`RasterImage`](../../aspose.imaging/rasterimage). |
| override [Width](../../aspose.imaging/rastercachedmultipageimage/width) { get; } | Gets the image width. |
| override [XmpData](../../aspose.imaging.fileformats.gif/gifimage/xmpdata) { get; set; } | Gets or sets the XMP metadata. |

## Methods

| Name | Description |
| --- | --- |
| [AddBlock](../../aspose.imaging.fileformats.gif/gifimage/addblock)(IGifBlock) | Adds a new GIF block. |
| [AddPage](../../aspose.imaging.fileformats.gif/gifimage/addpage)(RasterImage) | Adds page to the image. |
| override [AdjustBrightness](../../aspose.imaging.fileformats.gif/gifimage/adjustbrightness)(int) | Adjust of a *brightness* for image. |
| override [AdjustContrast](../../aspose.imaging.fileformats.gif/gifimage/adjustcontrast)(float) | Adjusts the contrast. |
| override [AdjustGamma](../../aspose.imaging.fileformats.gif/gifimage/adjustgamma)(float) | Gamma-correction of an image. |
| override [AdjustGamma](../../aspose.imaging.fileformats.gif/gifimage/adjustgamma)(float, float, float) | Gamma-correction of an image. |
| override [BinarizeBradley](../../aspose.imaging.fileformats.gif/gifimage/binarizebradley)(double) | Binarization of an image using Bradley's adaptive thresholding algorithm using the integral image thresholding |
| override [BinarizeBradley](../../aspose.imaging/rastercachedmultipageimage/binarizebradley)(double, int) | Binarization of an image using Bradley's adaptive thresholding algorithm using the integral image thresholding |
| override [BinarizeFixed](../../aspose.imaging.fileformats.gif/gifimage/binarizefixed)(byte) | Binarization of an image with predefined threshold |
| override [BinarizeOtsu](../../aspose.imaging.fileformats.gif/gifimage/binarizeotsu)() | Binarization of an image with Otsu thresholding |
| override [CacheData](../../aspose.imaging/rastercachedmultipageimage/cachedata)() | Caches the data private. |
| [CanSave](../../aspose.imaging/image/cansave)(ImageOptionsBase) | Determines whether image can be saved to the specified file format represented by the passed save options. |
| [ClearBlocks](../../aspose.imaging.fileformats.gif/gifimage/clearblocks)() | Clears all the GIF blocks. |
| override [Crop](../../aspose.imaging.fileformats.gif/gifimage/crop)(Rectangle) | Cropping the image. |
| override [Crop](../../aspose.imaging/rastercachedmultipageimage/crop)(int, int, int, int) | Crop image with shifts. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Disposes the current instance. |
| [Dither](../../aspose.imaging/rasterimage/dither)(DitheringMethod, int) | Performs dithering on the current image. |
| override [Dither](../../aspose.imaging.fileformats.gif/gifimage/dither)(DitheringMethod, int, IColorPalette) | Performs dithering on the current image. |
| override [Filter](../../aspose.imaging.fileformats.gif/gifimage/filter)(Rectangle, FilterOptionsBase) | Filters the specified rectangle. |
| [GetArgb32Pixel](../../aspose.imaging/rasterimage/getargb32pixel)(int, int) | Gets an image 32-bit ARGB pixel. |
| [GetDefaultArgb32Pixels](../../aspose.imaging/rasterimage/getdefaultargb32pixels)(Rectangle) | Gets the default 32-bit ARGB pixels array. |
| virtual [GetDefaultOptions](../../aspose.imaging/image/getdefaultoptions)(object[]) | Gets the default options. |
| [GetDefaultPixels](../../aspose.imaging/rasterimage/getdefaultpixels)(Rectangle, IPartialArgb32PixelLoader) | Gets the default pixels array using partial pixel loader. |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata)(Rectangle, RawDataSettings) | Gets the default raw data array. |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata)(Rectangle, IPartialRawDataLoader, RawDataSettings) | Gets the default raw data array using partial pixel loader. |
| virtual [GetModifyDate](../../aspose.imaging/rasterimage/getmodifydate)(bool) | Gets the date and time the resource image was last modified. |
| override [GetOriginalOptions](../../aspose.imaging.fileformats.gif/gifimage/getoriginaloptions)() | Gets the options based on the original file settings. This can be helpful to keep bit-depth and other parameters of the original image unchanged. For example, if we load a black-white PNG image with 1 bit per pixel and then save it using the [`Save`](../../aspose.imaging/datastreamsupporter/save) method, the output PNG image with 8-bit per pixel will be produced. To avoid it and save PNG image with 1-bit per pixel, use this method to get corresponding saving options and pass them to the [`Save`](../../aspose.imaging/image/save) method as the second parameter. |
| [GetPixel](../../aspose.imaging/rasterimage/getpixel)(int, int) | Gets an image pixel. |
| [GetSkewAngle](../../aspose.imaging/rasterimage/getskewangle)() | Gets the skew angle. This method is applicable to scanned text documents, to determine the skew angle when scanning. |
| override [Grayscale](../../aspose.imaging.fileformats.gif/gifimage/grayscale)() | Transformation of an image to its grayscale representation |
| [InsertBlock](../../aspose.imaging.fileformats.gif/gifimage/insertblock)(int, IGifBlock) | Adds a new GIF block. |
| [LoadArgb32Pixels](../../aspose.imaging/rasterimage/loadargb32pixels)(Rectangle) | Loads 32-bit ARGB pixels. |
| [LoadArgb64Pixels](../../aspose.imaging/rasterimage/loadargb64pixels)(Rectangle) | Loads 64-bit ARGB pixels. |
| [LoadCmyk32Pixels](../../aspose.imaging/rasterimage/loadcmyk32pixels)(Rectangle) | Loads pixels in CMYK format. |
| [LoadPartialArgb32Pixels](../../aspose.imaging/rasterimage/loadpartialargb32pixels)(Rectangle, IPartialArgb32PixelLoader) | Loads 32-bit ARGB pixels partially by packs. |
| [LoadPartialPixels](../../aspose.imaging/rasterimage/loadpartialpixels)(Rectangle, IPartialPixelLoader) | Loads pixels partially by packs. |
| [LoadPixels](../../aspose.imaging/rasterimage/loadpixels)(Rectangle) | Loads pixels. |
| [LoadRawData](../../aspose.imaging/rasterimage/loadrawdata)(Rectangle, RawDataSettings, IPartialRawDataLoader) | Loads raw data. |
| [LoadRawData](../../aspose.imaging/rasterimage/loadrawdata)(Rectangle, Rectangle, RawDataSettings, IPartialRawDataLoader) | Loads raw data. |
| [NormalizeAngle](../../aspose.imaging/rasterimage/normalizeangle)() | Normalizes the angle. This method is applicable to scanned text documents to get rid of the skewed scan. This method uses [`GetSkewAngle`](../../aspose.imaging/rasterimage/getskewangle) and [`Rotate`](../../aspose.imaging/rasterimage/rotate) methods. |
| override [NormalizeAngle](../../aspose.imaging/rastercachedmultipageimage/normalizeangle)(bool, Color) | Normalizes the angle. This method is applicable to scanned text documents to get rid of the skewed scan. This method uses !:GetSkewAngle and [`Rotate`](../../aspose.imaging/rastercachedmultipageimage/rotate) methods. |
| [OrderBlocks](../../aspose.imaging.fileformats.gif/gifimage/orderblocks)() | Orders the GIF blocks according to the GIF specification. Some [`GifGraphicsControlBlock`](../../aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock) may be removed for proper GIF layout. |
| [ReadArgb32ScanLine](../../aspose.imaging/rasterimage/readargb32scanline)(int) | Reads the whole scan line by the specified scan line index. |
| [ReadScanLine](../../aspose.imaging/rasterimage/readscanline)(int) | Reads the whole scan line by the specified scan line index. |
| [RemoveBlock](../../aspose.imaging.fileformats.gif/gifimage/removeblock)(IGifBlock) | Removes the GIF block. |
| [ReplaceColor](../../aspose.imaging/rasterimage/replacecolor)(Color, byte, Color) | Replaces one color to another with allowed difference and preserves original alpha value to save smooth edges. |
| override [ReplaceColor](../../aspose.imaging/rastercachedmultipageimage/replacecolor)(int, byte, int) | Replaces one color to another with allowed difference and preserves original alpha value to save smooth edges. |
| [ReplaceNonTransparentColors](../../aspose.imaging/rasterimage/replacenontransparentcolors)(Color) | Replaces all non-transparent colors with new color and preserves original alpha value to save smooth edges. Note: if you use it on images without transparency, all colors will be replaced with a single one. |
| override [ReplaceNonTransparentColors](../../aspose.imaging/rastercachedmultipageimage/replacenontransparentcolors)(int) | Replaces all non-transparent colors with new color and preserves original alpha value to save smooth edges. Note: if you use it on images without transparency, all colors will be replaced with a single one. |
| [Resize](../../aspose.imaging/image/resize)(int, int) | Resizes the image. The default NearestNeighbourResample is used. |
| override [Resize](../../aspose.imaging.fileformats.gif/gifimage/resize)(int, int, ImageResizeSettings) | Resizes the image. |
| override [Resize](../../aspose.imaging.fileformats.gif/gifimage/resize)(int, int, ResizeType) | Resizes the image. |
| [ResizeFullFrame](../../aspose.imaging.fileformats.gif/gifimage/resizefullframe)(int, int, ResizeType) | Resizes the image using full frames for each GIF page. Required to avoid possible artifacts appearance. |
| [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int) | Resizes the height proportionally. The default NearestNeighbourResample is used. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int, ImageResizeSettings) | Resizes the height proportionally. |
| override [ResizeHeightProportionally](../../aspose.imaging/rastercachedmultipageimage/resizeheightproportionally)(int, ResizeType) | Resizes the width proportionally. |
| [ResizeProportional](../../aspose.imaging.fileformats.gif/gifimage/resizeproportional)(int, int, ResizeType) | Performs proportional resize on the image. The proportional resize will resize each frame according to the ratio of *newWidth*/width and *newHeight*/height. |
| [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int) | Resizes the width proportionally. The default NearestNeighbourResample is used. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int, ImageResizeSettings) | Resizes the width proportionally. |
| override [ResizeWidthProportionally](../../aspose.imaging/rastercachedmultipageimage/resizewidthproportionally)(int, ResizeType) | Resizes the width proportionally. |
| virtual [Rotate](../../aspose.imaging/rasterimage/rotate)(float) | Rotate image around the center. |
| override [Rotate](../../aspose.imaging.fileformats.gif/gifimage/rotate)(float, bool, Color) | !:RasterCahcedMultipageImage.Rotate image around the center. |
| override [RotateFlip](../../aspose.imaging.fileformats.gif/gifimage/rotateflip)(RotateFlipType) | Rotates, flips, or rotates and flips the Active frame only. |
| [Save](../../aspose.imaging/image/save)() | Saves the image data to the underlying stream. |
| [Save](../../aspose.imaging/datastreamsupporter/save)(Stream) | Saves the object's data to the specified stream. |
| override [Save](../../aspose.imaging/image/save)(string) | Saves the image to the specified file location. |
| [Save](../../aspose.imaging/image/save)(Stream, ImageOptionsBase) | Saves the image's data to the specified stream in the specified file format according to save options. |
| virtual [Save](../../aspose.imaging/datastreamsupporter/save)(string, bool) | Saves the object's data to the specified file location. |
| virtual [Save](../../aspose.imaging/image/save)(string, ImageOptionsBase) | Saves the object's data to the specified file location in the specified file format according to save options. |
| override [Save](../../aspose.imaging/rasterimage/save)(Stream, ImageOptionsBase, Rectangle) | Saves the image's data to the specified stream in the specified file format according to save options. |
| virtual [Save](../../aspose.imaging/image/save)(string, ImageOptionsBase, Rectangle) | Saves the object's data to the specified file location in the specified file format according to save options. |
| [SaveArgb32Pixels](../../aspose.imaging/rasterimage/saveargb32pixels)(Rectangle, int[]) | Saves the 32-bit ARGB pixels. |
| [SaveCmyk32Pixels](../../aspose.imaging/rasterimage/savecmyk32pixels)(Rectangle, int[]) | Saves the pixels. |
| [SavePixels](../../aspose.imaging/rasterimage/savepixels)(Rectangle, Color[]) | Saves the pixels. |
| [SaveRawData](../../aspose.imaging/rasterimage/saverawdata)(byte[], int, Rectangle, RawDataSettings) | Saves the raw data. |
| [SetArgb32Pixel](../../aspose.imaging/rasterimage/setargb32pixel)(int, int, int) | Sets an image 32-bit ARGB pixel for the specified position. |
| [SetFrameTime](../../aspose.imaging.fileformats.gif/gifimage/setframetime)(ushort) | Sets all frames duration in milliseconds. Changing this value will reset delay for all frames. |
| override [SetPalette](../../aspose.imaging/rasterimage/setpalette)(IColorPalette, bool) | Sets the image palette. |
| [SetPixel](../../aspose.imaging/rasterimage/setpixel)(int, int, Color) | Sets an image pixel for the specified position. |
| virtual [SetResolution](../../aspose.imaging/rasterimage/setresolution)(double, double) | Sets the resolution for this [`RasterImage`](../../aspose.imaging/rasterimage). |
| virtual [ToBitmap](../../aspose.imaging/rasterimage/tobitmap)() | Converts raster image to the bitmap. |
| [WriteArgb32ScanLine](../../aspose.imaging/rasterimage/writeargb32scanline)(int, int[]) | Writes the whole scan line to the specified scan line index. |
| [WriteScanLine](../../aspose.imaging/rasterimage/writescanline)(int, Color[]) | Writes the whole scan line to the specified scan line index. |

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
