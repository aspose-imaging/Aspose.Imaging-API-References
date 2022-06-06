---
title: WebPImage
second_title: Aspose.Imaging for .NET API Reference
description: 
type: docs
weight: 8080
url: /net/aspose.imaging.fileformats.webp/webpimage/
---
## WebPImage class

A webp image.

```csharp
public sealed class WebPImage : RasterCachedMultipageImage, IMultipageImageExt
```

## Constructors

| Name | Description |
| --- | --- |
| [WebPImage](webpimage)(RasterImage) | Initializes a new instance of the [`WebPImage`](../webpimage) class from rasterImage. |
| [WebPImage](webpimage)(Stream) | Initializes a new instance of the [`WebPImage`](../webpimage) class from stream. |
| [WebPImage](webpimage)(string) | Initializes a new instance of the [`WebPImage`](../webpimage) class from file. |
| [WebPImage](webpimage)(RasterImage, LoadOptions) | Initializes a new instance of the [`WebPImage`](../webpimage) class from rasterImage. |
| [WebPImage](webpimage)(Stream, LoadOptions) | Initializes a new instance of the [`WebPImage`](../webpimage) class from stream. |
| [WebPImage](webpimage)(string, LoadOptions) | Initializes a new instance of the [`WebPImage`](../webpimage) class from file. |
| [WebPImage](webpimage)(int, int, WebPOptions) | Initializes a new instance of the [`WebPImage`](../webpimage) class with empty image. |
| [WebPImage](webpimage)(int, int, WebPOptions, LoadOptions) | Initializes a new instance of the [`WebPImage`](../webpimage) class with empty image. |

## Properties

| Name | Description |
| --- | --- |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette) { get; set; } | Gets or sets a value indicating whether automatic adjust palette. |
| override [BackgroundColor](../../aspose.imaging/rastercachedmultipageimage/backgroundcolor) { get; set; } | Gets or sets a value for the background color. |
| override [BitsPerPixel](../../aspose.imaging/rastercachedmultipageimage/bitsperpixel) { get; } | Gets the image bits per pixel count. |
| [Bounds](../../aspose.imaging/image/bounds) { get; } | Gets the image bounds. |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint) { get; set; } | Gets or sets the buffer size hint which is defined max allowed size for all internal buffers. |
| [Container](../../aspose.imaging/image/container) { get; } | Gets the [`Image`](../../aspose.imaging/image) container. |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer) { get; } | Gets the object's data stream. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Gets a value indicating whether this instance is disposed. |
| override [FileFormat](../../aspose.imaging.fileformats.webp/webpimage/fileformat) { get; } | Gets a value of file format |
| override [HasAlpha](../../aspose.imaging.fileformats.webp/webpimage/hasalpha) { get; } | Gets the Has alpha channel. |
| virtual [HasBackgroundColor](../../aspose.imaging/image/hasbackgroundcolor) { get; set; } | Gets or sets a value indicating whether image has background color. |
| override [HasTransparentColor](../../aspose.imaging/rastercachedmultipageimage/hastransparentcolor) { get; } | Gets a value indicating whether image has transparent color. |
| override [Height](../../aspose.imaging/rastercachedmultipageimage/height) { get; } | Gets the image height. |
| virtual [HorizontalResolution](../../aspose.imaging/rasterimage/horizontalresolution) { get; set; } | Gets or sets the horizontal resolution, in pixels per inch, of this [`RasterImage`](../../aspose.imaging/rasterimage). |
| override [ImageOpacity](../../aspose.imaging/rastercachedmultipageimage/imageopacity) { get; } | Gets opacity of this image. |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor) { get; set; } | Gets or sets the interrupt monitor. |
| [IsCached](../../aspose.imaging/rastercachedmultipageimage/iscached) { get; } | Gets a value indicating whether image data is cached currently. |
| [IsRawDataAvailable](../../aspose.imaging/rasterimage/israwdataavailable) { get; } | Gets a value indicating whether raw data loading is available. |
| [Options](../../aspose.imaging.fileformats.webp/webpimage/options) { get; } | Gets or sets the options. |
| override [PageCount](../../aspose.imaging.fileformats.webp/webpimage/pagecount) { get; } | Gets the page count. |
| override [PageExportingAction](../../aspose.imaging.fileformats.webp/webpimage/pageexportingaction) { get; set; } | Gets or sets the page exporting action. Please note that setting this method will automatically release page resources after it is executed. It will be executed just before each page is saved. |
| override [Pages](../../aspose.imaging.fileformats.webp/webpimage/pages) { get; } | Gets the blocks. |
| [Palette](../../aspose.imaging/image/palette) { get; set; } | Gets or sets the color palette. The color palette is not used when pixels are represented directly. |
| virtual [PremultiplyComponents](../../aspose.imaging/rasterimage/premultiplycomponents) { get; set; } | Gets or sets a value indicating whether the image components must be premultiplied. |
| [RawCustomColorConverter](../../aspose.imaging/rasterimage/rawcustomcolorconverter) { get; set; } | Gets or sets the custom color converter |
| virtual [RawDataFormat](../../aspose.imaging/rasterimage/rawdataformat) { get; } | Gets the raw data format. |
| [RawDataSettings](../../aspose.imaging/rasterimage/rawdatasettings) { get; } | Gets the current raw data settings. Note when using these settings the data loads without conversion. |
| [RawFallbackIndex](../../aspose.imaging/rasterimage/rawfallbackindex) { get; set; } | Gets or sets the fallback index to use when palette index is out of bounds |
| [RawIndexedColorConverter](../../aspose.imaging/rasterimage/rawindexedcolorconverter) { get; set; } | Gets or sets the indexed color converter |
| virtual [RawLineSize](../../aspose.imaging/rasterimage/rawlinesize) { get; } | Gets the raw line size in bytes. |
| [Size](../../aspose.imaging/image/size) { get; } | Gets the image size. |
| virtual [TransparentColor](../../aspose.imaging/rasterimage/transparentcolor) { get; set; } | Gets the image transparent color. |
| virtual [UpdateXmpData](../../aspose.imaging/rasterimage/updatexmpdata) { get; set; } | Gets or sets a value indicating whether to update the XMP metadata. |
| override [UsePalette](../../aspose.imaging/rasterimage/usepalette) { get; } | Gets a value indicating whether the image palette is used. |
| virtual [UseRawData](../../aspose.imaging/rasterimage/userawdata) { get; set; } | Gets or sets a value indicating whether to use raw data loading when the raw data loading is available. |
| virtual [VerticalResolution](../../aspose.imaging/rasterimage/verticalresolution) { get; set; } | Gets or sets the vertical resolution, in pixels per inch, of this [`RasterImage`](../../aspose.imaging/rasterimage). |
| override [Width](../../aspose.imaging/rastercachedmultipageimage/width) { get; } | Gets the image width. |
| override [XmpData](../../aspose.imaging/rastercachedmultipageimage/xmpdata) { get; set; } | Gets or sets XMP data from frame. |

## Methods

| Name | Description |
| --- | --- |
| [AddBlock](../../aspose.imaging.fileformats.webp/webpimage/addblock)(IFrame) | Adds a new Webp block. |
| [AddPage](../../aspose.imaging.fileformats.webp/webpimage/addpage)(RasterImage) | Adds page to the image. |
| override [AdjustBrightness](../../aspose.imaging.fileformats.webp/webpimage/adjustbrightness)(int) | Adjust of a *brightness* for image. |
| override [AdjustContrast](../../aspose.imaging.fileformats.webp/webpimage/adjustcontrast)(float) | [`Image`](../../aspose.imaging/image) contrasting |
| override [AdjustGamma](../../aspose.imaging.fileformats.webp/webpimage/adjustgamma)(float) | Gamma-correction of an image. |
| override [AdjustGamma](../../aspose.imaging.fileformats.webp/webpimage/adjustgamma)(float, float, float) | Gamma-correction of an image. |
| override [BinarizeBradley](../../aspose.imaging/rastercachedmultipageimage/binarizebradley)(double) | Binarization of an image using Bradley's adaptive thresholding algorithm using the integral image thresholding |
| override [BinarizeBradley](../../aspose.imaging.fileformats.webp/webpimage/binarizebradley)(double, int) | Binarization of an image using Bradley's adaptive thresholding algorithm using the integral image thresholding |
| override [BinarizeFixed](../../aspose.imaging.fileformats.webp/webpimage/binarizefixed)(byte) | Binarization of an image with predefined threshold |
| override [BinarizeOtsu](../../aspose.imaging.fileformats.webp/webpimage/binarizeotsu)() | Binarization of an image with Otsu thresholding |
| override [CacheData](../../aspose.imaging/rastercachedmultipageimage/cachedata)() | Caches the data private. |
| [CanSave](../../aspose.imaging/image/cansave)(ImageOptionsBase) | Determines whether image can be saved to the specified file format represented by the passed save options. |
| [ClearBlocks](../../aspose.imaging.fileformats.webp/webpimage/clearblocks)() | Clears all the Webp blocks. |
| override [Crop](../../aspose.imaging.fileformats.webp/webpimage/crop)(Rectangle) | Cropping the image. |
| override [Crop](../../aspose.imaging.fileformats.webp/webpimage/crop)(int, int, int, int) | Crop image with shifts. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Disposes the current instance. |
| [Dither](../../aspose.imaging/rasterimage/dither)(DitheringMethod, int) | Performs dithering on the current image. |
| override [Dither](../../aspose.imaging.fileformats.webp/webpimage/dither)(DitheringMethod, int, IColorPalette) | Performs dithering on the current image. |
| override [Filter](../../aspose.imaging.fileformats.webp/webpimage/filter)(Rectangle, FilterOptionsBase) | Filters the specified rectangle. |
| [GetArgb32Pixel](../../aspose.imaging/rasterimage/getargb32pixel)(int, int) | Gets an image 32-bit ARGB pixel. |
| [GetDefaultArgb32Pixels](../../aspose.imaging/rasterimage/getdefaultargb32pixels)(Rectangle) | Gets the default 32-bit ARGB pixels array. |
| virtual [GetDefaultOptions](../../aspose.imaging/image/getdefaultoptions)(object[]) | Gets the default options. |
| [GetDefaultPixels](../../aspose.imaging/rasterimage/getdefaultpixels)(Rectangle, IPartialArgb32PixelLoader) | Gets the default pixels array using partial pixel loader. |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata)(Rectangle, RawDataSettings) | Gets the default raw data array. |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata)(Rectangle, IPartialRawDataLoader, RawDataSettings) | Gets the default raw data array using partial pixel loader. |
| virtual [GetModifyDate](../../aspose.imaging/rasterimage/getmodifydate)(bool) | Gets the date and time the resource image was last modified. |
| virtual [GetOriginalOptions](../../aspose.imaging/image/getoriginaloptions)() | Gets the options based on the original file settings. This can be helpful to keep bit-depth and other parameters of the original image unchanged. For example, if we load a black-white PNG image with 1 bit per pixel and then save it using the [`Save`](../../aspose.imaging/datastreamsupporter/save) method, the output PNG image with 8-bit per pixel will be produced. To avoid it and save PNG image with 1-bit per pixel, use this method to get corresponding saving options and pass them to the [`Save`](../../aspose.imaging/image/save) method as the second parameter. |
| [GetPixel](../../aspose.imaging/rasterimage/getpixel)(int, int) | Gets an image pixel. |
| [GetSkewAngle](../../aspose.imaging/rasterimage/getskewangle)() | Gets the skew angle. This method is applicable to scanned text documents, to determine the skew angle when scanning. |
| override [Grayscale](../../aspose.imaging.fileformats.webp/webpimage/grayscale)() | Transformation of an image to its grayscale representation |
| [InsertBlock](../../aspose.imaging.fileformats.webp/webpimage/insertblock)(int, IFrame) | Adds a new Webp block. |
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
| [ReadArgb32ScanLine](../../aspose.imaging/rasterimage/readargb32scanline)(int) | Reads the whole scan line by the specified scan line index. |
| [ReadScanLine](../../aspose.imaging/rasterimage/readscanline)(int) | Reads the whole scan line by the specified scan line index. |
| [RemoveBlock](../../aspose.imaging.fileformats.webp/webpimage/removeblock)(IFrame) | Removes the Webp block. |
| [ReplaceColor](../../aspose.imaging/rasterimage/replacecolor)(Color, byte, Color) | Replaces one color to another with allowed difference and preserves original alpha value to save smooth edges. |
| override [ReplaceColor](../../aspose.imaging/rastercachedmultipageimage/replacecolor)(int, byte, int) | Replaces one color to another with allowed difference and preserves original alpha value to save smooth edges. |
| [ReplaceNonTransparentColors](../../aspose.imaging/rasterimage/replacenontransparentcolors)(Color) | Replaces all non-transparent colors with new color and preserves original alpha value to save smooth edges. Note: if you use it on images without transparency, all colors will be replaced with a single one. |
| override [ReplaceNonTransparentColors](../../aspose.imaging/rastercachedmultipageimage/replacenontransparentcolors)(int) | Replaces all non-transparent colors with new color and preserves original alpha value to save smooth edges. Note: if you use it on images without transparency, all colors will be replaced with a single one. |
| [Resize](../../aspose.imaging/image/resize)(int, int) | Resizes the image. The default NearestNeighbourResample is used. |
| override [Resize](../../aspose.imaging.fileformats.webp/webpimage/resize)(int, int, ImageResizeSettings) | Resizes the image. |
| override [Resize](../../aspose.imaging.fileformats.webp/webpimage/resize)(int, int, ResizeType) | Resizes the image. |
| [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int) | Resizes the height proportionally. The default NearestNeighbourResample is used. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int, ImageResizeSettings) | Resizes the height proportionally. |
| override [ResizeHeightProportionally](../../aspose.imaging.fileformats.webp/webpimage/resizeheightproportionally)(int, ResizeType) | Resizes the width proportionally. |
| [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int) | Resizes the width proportionally. The default NearestNeighbourResample is used. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int, ImageResizeSettings) | Resizes the width proportionally. |
| override [ResizeWidthProportionally](../../aspose.imaging.fileformats.webp/webpimage/resizewidthproportionally)(int, ResizeType) | Resizes the width proportionally. |
| virtual [Rotate](../../aspose.imaging/rasterimage/rotate)(float) | Rotate image around the center. |
| override [Rotate](../../aspose.imaging.fileformats.webp/webpimage/rotate)(float, bool, Color) | !:RasterCahcedMultipageImage.Rotate image around the center. |
| override [RotateFlip](../../aspose.imaging.fileformats.webp/webpimage/rotateflip)(RotateFlipType) | Rotates, flips, or rotates and flips the Active frame only. |
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
| override [SetPalette](../../aspose.imaging/rasterimage/setpalette)(IColorPalette, bool) | Sets the image palette. |
| [SetPixel](../../aspose.imaging/rasterimage/setpixel)(int, int, Color) | Sets an image pixel for the specified position. |
| virtual [SetResolution](../../aspose.imaging/rasterimage/setresolution)(double, double) | Sets the resolution for this [`RasterImage`](../../aspose.imaging/rasterimage). |
| virtual [ToBitmap](../../aspose.imaging/rasterimage/tobitmap)() | Converts raster image to the bitmap. |
| [WriteArgb32ScanLine](../../aspose.imaging/rasterimage/writeargb32scanline)(int, int[]) | Writes the whole scan line to the specified scan line index. |
| [WriteScanLine](../../aspose.imaging/rasterimage/writescanline)(int, Color[]) | Writes the whole scan line to the specified scan line index. |

### Examples

This example shows how to load a WebP image from a file and save it to PNG.

```csharp
[C#]

string dir = "c:\\temp\\";

// Load a WebP image from a file.
using (Aspose.Imaging.FileFormats.Webp.WebPImage webPImage = new Aspose.Imaging.FileFormats.Webp.WebPImage(dir + "test.webp"))
{
    // Save to PNG
    // Note that only the active frame will be stored to PNG, since PNG is not a multi-page format.
    webPImage.Save(dir + "test.output.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### See Also

* class [RasterCachedMultipageImage](../../aspose.imaging/rastercachedmultipageimage)
* interface [IMultipageImageExt](../../aspose.imaging/imultipageimageext)
* namespace [Aspose.Imaging.FileFormats.Webp](../../aspose.imaging.fileformats.webp)
* assembly [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
