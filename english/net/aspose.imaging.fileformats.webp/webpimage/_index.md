---
title: WebPImage
second_title: Aspose.Imaging for .NET API Reference
description: 
type: docs
weight: 8070
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
| override [FileFormat](fileformat) { get; } | Gets a value of file format |
| override [HasAlpha](hasalpha) { get; } | Gets the Has alpha channel. |
| [Options](options) { get; } | Gets or sets the options. |
| override [PageCount](pagecount) { get; } | Gets the page count. |
| override [PageExportingAction](pageexportingaction) { get; set; } | Gets or sets the page exporting action. Please note that setting this method will automatically release page resources after it is executed. It will be executed just before each page is saved. |
| override [Pages](pages) { get; } | Gets the blocks. |

## Methods

| Name | Description |
| --- | --- |
| [AddBlock](addblock)(IFrame) | Adds a new Webp block. |
| [AddPage](addpage)(RasterImage) | Adds page to the image. |
| override [AdjustBrightness](adjustbrightness)(int) | Adjust of a *brightness* for image. |
| override [AdjustContrast](adjustcontrast)(float) | [`Image`](../../aspose.imaging/image) contrasting |
| override [AdjustGamma](adjustgamma)(float) | Gamma-correction of an image. |
| override [AdjustGamma](adjustgamma)(float, float, float) | Gamma-correction of an image. |
| override [BinarizeBradley](binarizebradley)(double, int) | Binarization of an image using Bradley's adaptive thresholding algorithm using the integral image thresholding |
| override [BinarizeFixed](binarizefixed)(byte) | Binarization of an image with predefined threshold |
| override [BinarizeOtsu](binarizeotsu)() | Binarization of an image with Otsu thresholding |
| [ClearBlocks](clearblocks)() | Clears all the Webp blocks. |
| override [Crop](crop)(Rectangle) | Cropping the image. |
| override [Crop](crop)(int, int, int, int) | Crop image with shifts. |
| override [Dither](dither)(DitheringMethod, int, IColorPalette) | Performs dithering on the current image. |
| override [Filter](filter)(Rectangle, FilterOptionsBase) | Filters the specified rectangle. |
| override [Grayscale](grayscale)() | Transformation of an image to its grayscale representation |
| [InsertBlock](insertblock)(int, IFrame) | Adds a new Webp block. |
| [RemoveBlock](removeblock)(IFrame) | Removes the Webp block. |
| override [Resize](resize)(int, int, ImageResizeSettings) | Resizes the image. |
| override [Resize](resize)(int, int, ResizeType) | Resizes the image. |
| override [ResizeHeightProportionally](resizeheightproportionally)(int, ResizeType) | Resizes the width proportionally. |
| override [ResizeWidthProportionally](resizewidthproportionally)(int, ResizeType) | Resizes the width proportionally. |
| override [Rotate](rotate)(float, bool, Color) | !:RasterCahcedMultipageImage.Rotate image around the center. |
| override [RotateFlip](rotateflip)(RotateFlipType) | Rotates, flips, or rotates and flips the Active frame only. |

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
