---
title: RasterImage
second_title: Aspose.Imaging for .NET API Reference
description: 
type: docs
weight: 10800
url: /net/aspose.imaging/rasterimage/
---
## RasterImage class

Represents a raster image supporting raster graphics operations.

```csharp
public abstract class RasterImage : Image, IRasterImageArgb32PixelLoader
```

## Properties

| Name | Description |
| --- | --- |
| virtual [HasAlpha](hasalpha) { get; } | Gets a value indicating whether this instance has alpha. |
| virtual [HasTransparentColor](hastransparentcolor) { get; set; } | Gets a value indicating whether image has transparent color. |
| virtual [HorizontalResolution](horizontalresolution) { get; set; } | Gets or sets the horizontal resolution, in pixels per inch, of this [`RasterImage`](../rasterimage). |
| virtual [ImageOpacity](imageopacity) { get; } | Gets opacity of this image. |
| [IsRawDataAvailable](israwdataavailable) { get; } | Gets a value indicating whether raw data loading is available. |
| virtual [PremultiplyComponents](premultiplycomponents) { get; set; } | Gets or sets a value indicating whether the image components must be premultiplied. |
| [RawCustomColorConverter](rawcustomcolorconverter) { get; set; } | Gets or sets the custom color converter |
| virtual [RawDataFormat](rawdataformat) { get; } | Gets the raw data format. |
| [RawDataSettings](rawdatasettings) { get; } | Gets the current raw data settings. Note when using these settings the data loads without conversion. |
| [RawFallbackIndex](rawfallbackindex) { get; set; } | Gets or sets the fallback index to use when palette index is out of bounds |
| [RawIndexedColorConverter](rawindexedcolorconverter) { get; set; } | Gets or sets the indexed color converter |
| virtual [RawLineSize](rawlinesize) { get; } | Gets the raw line size in bytes. |
| virtual [TransparentColor](transparentcolor) { get; set; } | Gets the image transparent color. |
| virtual [UpdateXmpData](updatexmpdata) { get; set; } | Gets or sets a value indicating whether to update the XMP metadata. |
| override [UsePalette](usepalette) { get; } | Gets a value indicating whether the image palette is used. |
| virtual [UseRawData](userawdata) { get; set; } | Gets or sets a value indicating whether to use raw data loading when the raw data loading is available. |
| virtual [VerticalResolution](verticalresolution) { get; set; } | Gets or sets the vertical resolution, in pixels per inch, of this [`RasterImage`](../rasterimage). |
| virtual [XmpData](xmpdata) { get; set; } | Gets or sets the XMP metadata. |

## Methods

| Name | Description |
| --- | --- |
| virtual [AdjustBrightness](adjustbrightness)(int) | Adjust of a brightness for image. |
| virtual [AdjustContrast](adjustcontrast)(float) | Image contrasting |
| virtual [AdjustGamma](adjustgamma)(float) | Gamma-correction of an image. |
| virtual [AdjustGamma](adjustgamma)(float, float, float) | Gamma-correction of an image. |
| virtual [BinarizeBradley](binarizebradley)(double) | Binarization of an image using Bradley's adaptive thresholding algorithm using the integral image thresholding |
| virtual [BinarizeBradley](binarizebradley)(double, int) | Binarization of an image using Bradley's adaptive thresholding algorithm using the integral image thresholding |
| virtual [BinarizeFixed](binarizefixed)(byte) | Binarization of an image with predefined threshold |
| virtual [BinarizeOtsu](binarizeotsu)() | Binarization of an image with Otsu thresholding |
| virtual [Crop](crop)(Rectangle) | Crops the specified rectangle. |
| virtual [Crop](crop)(int, int, int, int) | Crop image with shifts. |
| [Dither](dither)(DitheringMethod, int) | Performs dithering on the current image. |
| abstract [Dither](dither)(DitheringMethod, int, IColorPalette) | Performs dithering on the current image. |
| virtual [Filter](filter)(Rectangle, FilterOptionsBase) | Filters the specified rectangle. |
| [GetArgb32Pixel](getargb32pixel)(int, int) | Gets an image 32-bit ARGB pixel. |
| [GetDefaultArgb32Pixels](getdefaultargb32pixels)(Rectangle) | Gets the default 32-bit ARGB pixels array. |
| [GetDefaultPixels](getdefaultpixels)(Rectangle, IPartialArgb32PixelLoader) | Gets the default pixels array using partial pixel loader. |
| [GetDefaultRawData](getdefaultrawdata)(Rectangle, RawDataSettings) | Gets the default raw data array. |
| [GetDefaultRawData](getdefaultrawdata)(Rectangle, IPartialRawDataLoader, RawDataSettings) | Gets the default raw data array using partial pixel loader. |
| virtual [GetModifyDate](getmodifydate)(bool) | Gets the date and time the resource image was last modified. |
| [GetPixel](getpixel)(int, int) | Gets an image pixel. |
| [GetSkewAngle](getskewangle)() | Gets the skew angle. This method is applicable to scanned text documents, to determine the skew angle when scanning. |
| virtual [Grayscale](grayscale)() | Transformation of an image to its grayscale representation |
| [LoadArgb32Pixels](loadargb32pixels)(Rectangle) | Loads 32-bit ARGB pixels. |
| [LoadArgb64Pixels](loadargb64pixels)(Rectangle) | Loads 64-bit ARGB pixels. |
| [LoadCmyk32Pixels](loadcmyk32pixels)(Rectangle) | Loads pixels in CMYK format. |
| [LoadPartialArgb32Pixels](loadpartialargb32pixels)(Rectangle, IPartialArgb32PixelLoader) | Loads 32-bit ARGB pixels partially by packs. |
| [LoadPartialPixels](loadpartialpixels)(Rectangle, IPartialPixelLoader) | Loads pixels partially by packs. |
| [LoadPixels](loadpixels)(Rectangle) | Loads pixels. |
| [LoadRawData](loadrawdata)(Rectangle, RawDataSettings, IPartialRawDataLoader) | Loads raw data. |
| [LoadRawData](loadrawdata)(Rectangle, Rectangle, RawDataSettings, IPartialRawDataLoader) | Loads raw data. |
| [NormalizeAngle](normalizeangle)() | Normalizes the angle. This method is applicable to scanned text documents to get rid of the skewed scan. This method uses [`GetSkewAngle`](./getskewangle) and [`Rotate`](./rotate) methods. |
| virtual [NormalizeAngle](normalizeangle)(bool, Color) | Normalizes the angle. This method is applicable to scanned text documents to get rid of the skewed scan. This method uses [`GetSkewAngle`](./getskewangle) and [`Rotate`](./rotate) methods. |
| [ReadArgb32ScanLine](readargb32scanline)(int) | Reads the whole scan line by the specified scan line index. |
| [ReadScanLine](readscanline)(int) | Reads the whole scan line by the specified scan line index. |
| [ReplaceColor](replacecolor)(Color, byte, Color) | Replaces one color to another with allowed difference and preserves original alpha value to save smooth edges. |
| virtual [ReplaceColor](replacecolor)(int, byte, int) | Replaces one color to another with allowed difference and preserves original alpha value to save smooth edges. |
| [ReplaceNonTransparentColors](replacenontransparentcolors)(Color) | Replaces all non-transparent colors with new color and preserves original alpha value to save smooth edges. Note: if you use it on images without transparency, all colors will be replaced with a single one. |
| virtual [ReplaceNonTransparentColors](replacenontransparentcolors)(int) | Replaces all non-transparent colors with new color and preserves original alpha value to save smooth edges. Note: if you use it on images without transparency, all colors will be replaced with a single one. |
| override [Resize](resize)(int, int, ImageResizeSettings) | Resizes the image with extended options. |
| override [Resize](resize)(int, int, ResizeType) | Resizes the image. |
| virtual [Rotate](rotate)(float) | Rotate image around the center. |
| virtual [Rotate](rotate)(float, bool, Color) | Rotate image around the center. |
| override [Save](save)(Stream, ImageOptionsBase, Rectangle) | Saves the image's data to the specified stream in the specified file format according to save options. |
| [SaveArgb32Pixels](saveargb32pixels)(Rectangle, int[]) | Saves the 32-bit ARGB pixels. |
| [SaveCmyk32Pixels](savecmyk32pixels)(Rectangle, int[]) | Saves the pixels. |
| [SavePixels](savepixels)(Rectangle, Color[]) | Saves the pixels. |
| [SaveRawData](saverawdata)(byte[], int, Rectangle, RawDataSettings) | Saves the raw data. |
| [SetArgb32Pixel](setargb32pixel)(int, int, int) | Sets an image 32-bit ARGB pixel for the specified position. |
| override [SetPalette](setpalette)(IColorPalette, bool) | Sets the image palette. |
| [SetPixel](setpixel)(int, int, Color) | Sets an image pixel for the specified position. |
| virtual [SetResolution](setresolution)(double, double) | Sets the resolution for this [`RasterImage`](../rasterimage). |
| virtual [ToBitmap](tobitmap)() | Converts raster image to the bitmap. |
| [WriteArgb32ScanLine](writeargb32scanline)(int, int[]) | Writes the whole scan line to the specified scan line index. |
| [WriteScanLine](writescanline)(int, Color[]) | Writes the whole scan line to the specified scan line index. |

### Examples

This example shows how to Loads Pixel information in an Array of Type Color, manipulates the array and set it back to the image. To perform these operations, this example creates a new Image file (in GIF format) uisng MemoryStream object.

```csharp
[C#]

//Create an instance of MemoryStream
using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
{
    //Create an instance of GifOptions and set its various properties including the Source property
    Aspose.Imaging.ImageOptions.GifOptions gifOptions = new Aspose.Imaging.ImageOptions.GifOptions();
    gifOptions.Source = new Aspose.Imaging.Sources.StreamSource(stream);

    //Create an instance of Image
    using (Aspose.Imaging.RasterImage image = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Create(gifOptions, 500, 500))
    {
        //Get the pixels of image by specifying the area as image boundary
        Aspose.Imaging.Color[] pixels = image.LoadPixels(image.Bounds);

        //Loop over the Array and sets color of alrenative indexed pixel
        for (int index = 0; index < pixels.Length; index++)
        {
            if (index % 2 == 0)
            {
                //Set the indexed pixel color to yellow
                pixels[index] = Aspose.Imaging.Color.Yellow;
            }
            else
            {
                //Set the indexed pixel color to blue
                pixels[index] = Aspose.Imaging.Color.Blue;
            }
        }

        //Apply the pixel changes to the image
        image.SavePixels(image.Bounds, pixels);

        // save all changes.
        image.Save();
    }

    // Write MemoryStream to File
    using (System.IO.FileStream fileStream = new System.IO.FileStream(@"C:\temp\output.gif", System.IO.FileMode.Create))
    {
        stream.WriteTo(fileStream);
    }   
}
```

### See Also

* class [Image](../image)
* interface [IRasterImageArgb32PixelLoader](../irasterimageargb32pixelloader)
* namespace [Aspose.Imaging](../../aspose.imaging)
* assembly [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
