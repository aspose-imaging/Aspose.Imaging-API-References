---
title: DicomImage
second_title: Aspose.Imaging for .NET API Reference
description: 
type: docs
weight: 2410
url: /net/aspose.imaging.fileformats.dicom/dicomimage/
---
## DicomImage class

It is class of the implementation working with image from DICOM file

```csharp
public sealed class DicomImage : RasterCachedMultipageImage, IMultipageImageExt
```

## Constructors

| Name | Description |
| --- | --- |
| [DicomImage](dicomimage)(Stream) | Initializes a new instance of the [`DicomImage`](../dicomimage) class. |
| [DicomImage](dicomimage)(Stream, LoadOptions) | Initializes a new instance of the [`DicomImage`](../dicomimage) class. |
| [DicomImage](dicomimage)(DicomOptions, int, int) | Initializes a new instance of the [`DicomImage`](../dicomimage) class. |

## Properties

| Name | Description |
| --- | --- |
| [ActivePage](../../aspose.imaging.fileformats.dicom/dicomimage/activepage) { get; set; } | Gets or sets the active page. |
| [ActivePageIndex](../../aspose.imaging.fileformats.dicom/dicomimage/activepageindex) { get; } | Gets the index active page. |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette) { get; set; } | Gets or sets a value indicating whether automatic adjust palette. |
| override [BackgroundColor](../../aspose.imaging/rastercachedmultipageimage/backgroundcolor) { get; set; } | Gets or sets a value for the background color. |
| override [BitsPerPixel](../../aspose.imaging/rastercachedmultipageimage/bitsperpixel) { get; } | Gets the image bits per pixel count. |
| [Bounds](../../aspose.imaging/image/bounds) { get; } | Gets the image bounds. |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint) { get; set; } | Gets or sets the buffer size hint which is defined max allowed size for all internal buffers. |
| [Container](../../aspose.imaging/image/container) { get; } | Gets the [`Image`](../../aspose.imaging/image) container. |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer) { get; } | Gets the object's data stream. |
| [DicomPages](../../aspose.imaging.fileformats.dicom/dicomimage/dicompages) { get; } | Gets the pages. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Gets a value indicating whether this instance is disposed. |
| override [FileFormat](../../aspose.imaging.fileformats.dicom/dicomimage/fileformat) { get; } | Gets a value of file format |
| [FileInfo](../../aspose.imaging.fileformats.dicom/dicomimage/fileinfo) { get; } | Gets a value, which contains info header the DICOM file |
| override [HasAlpha](../../aspose.imaging.fileformats.dicom/dicomimage/hasalpha) { get; } | Gets the Has alpha channel. |
| virtual [HasBackgroundColor](../../aspose.imaging/image/hasbackgroundcolor) { get; set; } | Gets or sets a value indicating whether image has background color. |
| override [HasTransparentColor](../../aspose.imaging/rastercachedmultipageimage/hastransparentcolor) { get; } | Gets a value indicating whether image has transparent color. |
| override [Height](../../aspose.imaging/rastercachedmultipageimage/height) { get; } | Gets the image height. |
| virtual [HorizontalResolution](../../aspose.imaging/rasterimage/horizontalresolution) { get; set; } | Gets or sets the horizontal resolution, in pixels per inch, of this [`RasterImage`](../../aspose.imaging/rasterimage). |
| override [ImageOpacity](../../aspose.imaging/rastercachedmultipageimage/imageopacity) { get; } | Gets opacity of this image. |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor) { get; set; } | Gets or sets the interrupt monitor. |
| [IsCached](../../aspose.imaging/rastercachedmultipageimage/iscached) { get; } | Gets a value indicating whether image data is cached currently. |
| [IsRawDataAvailable](../../aspose.imaging/rasterimage/israwdataavailable) { get; } | Gets a value indicating whether raw data loading is available. |
| override [PageCount](../../aspose.imaging.fileformats.dicom/dicomimage/pagecount) { get; } | Gets the page count. |
| override [PageExportingAction](../../aspose.imaging.fileformats.dicom/dicomimage/pageexportingaction) { get; set; } | Gets or sets the page exporting action. Please note that setting this method will automatically release page resources after it is executed. It will be executed just before each page is saved. |
| override [Pages](../../aspose.imaging.fileformats.dicom/dicomimage/pages) { get; } | Gets the pages. |
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
| override [XmpData](../../aspose.imaging.fileformats.dicom/dicomimage/xmpdata) { get; set; } | Gets or sets the Xmp data. |

## Methods

| Name | Description |
| --- | --- |
| [AddPage](../../aspose.imaging.fileformats.dicom/dicomimage/addpage)() | Adds a new page to the end of the page list. |
| [AddPage](../../aspose.imaging.fileformats.dicom/dicomimage/addpage)(RasterImage) | Adds page to the image. |
| override [AdjustBrightness](../../aspose.imaging.fileformats.dicom/dicomimage/adjustbrightness)(int) | Adjust of a *brightness* for image. |
| override [AdjustContrast](../../aspose.imaging.fileformats.dicom/dicomimage/adjustcontrast)(float) | [`Image`](../../aspose.imaging/image) contrasting |
| override [AdjustGamma](../../aspose.imaging.fileformats.dicom/dicomimage/adjustgamma)(float) | Gamma-correction of an image. |
| override [AdjustGamma](../../aspose.imaging.fileformats.dicom/dicomimage/adjustgamma)(float, float, float) | Gamma-correction of an image. |
| override [BinarizeBradley](../../aspose.imaging/rastercachedmultipageimage/binarizebradley)(double) | Binarization of an image using Bradley's adaptive thresholding algorithm using the integral image thresholding |
| override [BinarizeBradley](../../aspose.imaging.fileformats.dicom/dicomimage/binarizebradley)(double, int) | Binarization of an image using Bradley's adaptive thresholding algorithm using the integral image thresholding |
| override [BinarizeFixed](../../aspose.imaging.fileformats.dicom/dicomimage/binarizefixed)(byte) | Binarization of an image with predefined threshold |
| override [BinarizeOtsu](../../aspose.imaging.fileformats.dicom/dicomimage/binarizeotsu)() | Binarization of an image with Otsu thresholding |
| override [CacheData](../../aspose.imaging.fileformats.dicom/dicomimage/cachedata)() | Caches the data private. |
| [CanSave](../../aspose.imaging/image/cansave)(ImageOptionsBase) | Determines whether image can be saved to the specified file format represented by the passed save options. |
| override [Crop](../../aspose.imaging.fileformats.dicom/dicomimage/crop)(Rectangle) | Cropping the image. |
| override [Crop](../../aspose.imaging.fileformats.dicom/dicomimage/crop)(int, int, int, int) | Crop image with shifts. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Disposes the current instance. |
| [Dither](../../aspose.imaging/rasterimage/dither)(DitheringMethod, int) | Performs dithering on the current image. |
| override [Dither](../../aspose.imaging.fileformats.dicom/dicomimage/dither)(DitheringMethod, int, IColorPalette) | Performs dithering on the current image. |
| override [Filter](../../aspose.imaging.fileformats.dicom/dicomimage/filter)(Rectangle, FilterOptionsBase) | Filters the specified rectangle. |
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
| override [Grayscale](../../aspose.imaging.fileformats.dicom/dicomimage/grayscale)() | Transformation of an image to its grayscale representation |
| [InsertPage](../../aspose.imaging.fileformats.dicom/dicomimage/insertpage)(int) | Inserts a new page into the page list at the specified index. |
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
| [RemovePage](../../aspose.imaging.fileformats.dicom/dicomimage/removepage)(int) | Removes the page at the specified index of the page list. |
| [ReplaceColor](../../aspose.imaging/rasterimage/replacecolor)(Color, byte, Color) | Replaces one color to another with allowed difference and preserves original alpha value to save smooth edges. |
| override [ReplaceColor](../../aspose.imaging/rastercachedmultipageimage/replacecolor)(int, byte, int) | Replaces one color to another with allowed difference and preserves original alpha value to save smooth edges. |
| [ReplaceNonTransparentColors](../../aspose.imaging/rasterimage/replacenontransparentcolors)(Color) | Replaces all non-transparent colors with new color and preserves original alpha value to save smooth edges. Note: if you use it on images without transparency, all colors will be replaced with a single one. |
| override [ReplaceNonTransparentColors](../../aspose.imaging/rastercachedmultipageimage/replacenontransparentcolors)(int) | Replaces all non-transparent colors with new color and preserves original alpha value to save smooth edges. Note: if you use it on images without transparency, all colors will be replaced with a single one. |
| [Resize](../../aspose.imaging/image/resize)(int, int) | Resizes the image. The default NearestNeighbourResample is used. |
| override [Resize](../../aspose.imaging.fileformats.dicom/dicomimage/resize)(int, int, ImageResizeSettings) | Resizes the image. |
| override [Resize](../../aspose.imaging.fileformats.dicom/dicomimage/resize)(int, int, ResizeType) | Resizes the image. |
| [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int) | Resizes the height proportionally. The default NearestNeighbourResample is used. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int, ImageResizeSettings) | Resizes the height proportionally. |
| override [ResizeHeightProportionally](../../aspose.imaging.fileformats.dicom/dicomimage/resizeheightproportionally)(int, ResizeType) | Resizes the width proportionally. |
| [ResizeProportional](../../aspose.imaging.fileformats.dicom/dicomimage/resizeproportional)(int, int, ResizeType) | Performs proportional resize on the image. The proportional resize will resize each frame according to the ratio of *newWidth*/width and *newHeight*/height. |
| [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int) | Resizes the width proportionally. The default NearestNeighbourResample is used. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int, ImageResizeSettings) | Resizes the width proportionally. |
| override [ResizeWidthProportionally](../../aspose.imaging.fileformats.dicom/dicomimage/resizewidthproportionally)(int, ResizeType) | Resizes the width proportionally. |
| virtual [Rotate](../../aspose.imaging/rasterimage/rotate)(float) | Rotate image around the center. |
| override [Rotate](../../aspose.imaging.fileformats.dicom/dicomimage/rotate)(float, bool, Color) | !:RasterCahcedMultipageImage.Rotate image around the center. |
| override [RotateFlip](../../aspose.imaging.fileformats.dicom/dicomimage/rotateflip)(RotateFlipType) | Rotates, flips, or rotates and flips the Active frame only. |
| [Save](../../aspose.imaging/image/save)() | Saves the image data to the underlying stream. |
| [Save](../../aspose.imaging/datastreamsupporter/save)(Stream) | Saves the object's data to the specified stream. |
| override [Save](../../aspose.imaging/image/save)(string) | Saves the image to the specified file location. |
| [Save](../../aspose.imaging/image/save)(Stream, ImageOptionsBase) | Saves the image's data to the specified stream in the specified file format according to save options. |
| virtual [Save](../../aspose.imaging/datastreamsupporter/save)(string, bool) | Saves the object's data to the specified file location. |
| virtual [Save](../../aspose.imaging/image/save)(string, ImageOptionsBase) | Saves the object's data to the specified file location in the specified file format according to save options. |
| override [Save](../../aspose.imaging.fileformats.dicom/dicomimage/save)(Stream, ImageOptionsBase, Rectangle) | Saves the image's data to the specified stream in the specified file format according to save options. |
| virtual [Save](../../aspose.imaging/image/save)(string, ImageOptionsBase, Rectangle) | Saves the object's data to the specified file location in the specified file format according to save options. |
| [SaveAll](../../aspose.imaging.fileformats.dicom/dicomimage/saveall)(string, ImageOptionsBase) | Saves the object's data to the specified file (indexer + filename) location in the specified file format according to save options.. |
| [SaveArgb32Pixels](../../aspose.imaging/rasterimage/saveargb32pixels)(Rectangle, int[]) | Saves the 32-bit ARGB pixels. |
| [SaveCmyk32Pixels](../../aspose.imaging/rasterimage/savecmyk32pixels)(Rectangle, int[]) | Saves the pixels. |
| [SavePixels](../../aspose.imaging/rasterimage/savepixels)(Rectangle, Color[]) | Saves the pixels. |
| [SaveRawData](../../aspose.imaging/rasterimage/saverawdata)(byte[], int, Rectangle, RawDataSettings) | Saves the raw data. |
| [SetArgb32Pixel](../../aspose.imaging/rasterimage/setargb32pixel)(int, int, int) | Sets an image 32-bit ARGB pixel for the specified position. |
| override [SetPalette](../../aspose.imaging/rasterimage/setpalette)(IColorPalette, bool) | Sets the image palette. |
| [SetPixel](../../aspose.imaging/rasterimage/setpixel)(int, int, Color) | Sets an image pixel for the specified position. |
| override [SetResolution](../../aspose.imaging.fileformats.dicom/dicomimage/setresolution)(double, double) | Sets the resolution for this [`RasterImage`](../../aspose.imaging/rasterimage). |
| virtual [ToBitmap](../../aspose.imaging/rasterimage/tobitmap)() | Converts raster image to the bitmap. |
| [WriteArgb32ScanLine](../../aspose.imaging/rasterimage/writeargb32scanline)(int, int[]) | Writes the whole scan line to the specified scan line index. |
| [WriteScanLine](../../aspose.imaging/rasterimage/writescanline)(int, Color[]) | Writes the whole scan line to the specified scan line index. |

### Examples

Change Color Type in DICOM compression.

```csharp
[C#]

using (var inputImage = Image.Load("original.jpg"))
{
    var options = new DicomOptions { ColorType = ColorType.Grayscale8Bit };

    inputImage.Save("original_8Bit.dcm", options);
}
```

Use RLE compression in DICOM image.

```csharp
[C#]

using (var inputImage = Image.Load("original.jpg"))
{
    var options = new DicomOptions
    {
        ColorType = ColorType.Rgb24Bit,
        Compression = new Compression { Type = CompressionType.Rle }
    };

    inputImage.Save("original_RLE.dcm", options);
}
```

Use JPEG 2000 compression in DICOM image.

```csharp
[C#]

using (var inputImage = Image.Load("original.jpg"))
{
    var options = new DicomOptions
    {
        ColorType = ColorType.Rgb24Bit,
        Compression = new Compression
        {
            Type = CompressionType.Jpeg2000,
            Jpeg2000 = new Jpeg2000Options
            {
                Codec = Jpeg2000Codec.Jp2,
                Irreversible = false
            }
        }
    };

    inputImage.Save("original_JPEG2000.dcm", options);
}
```

Use JPEG compression in DICOM image.

```csharp
[C#]

using (var inputImage = Image.Load("original.jpg"))
{
    var options = new DicomOptions
    {
        ColorType = ColorType.Rgb24Bit,
        Compression = new Compression
        {
            Type = CompressionType.Jpeg,
            Jpeg = new JpegOptions
            {
                CompressionType = JpegCompressionMode.Baseline,
                SampleRoundingMode = SampleRoundingMode.Truncate,
                Quality = 50
            }
        }
    };

    inputImage.Save("original_JPEG.dcm", options);
}
```

This example shows how to load a DICOM image from a file stream.

```csharp
[C#]

string dir = "c:\\temp\\";

// Load a DICOM image from a file stream.
using (System.IO.Stream stream = System.IO.File.OpenRead(dir + "sample.dicom"))
{
    using (Aspose.Imaging.FileFormats.Dicom.DicomImage dicomImage = new Aspose.Imaging.FileFormats.Dicom.DicomImage(stream))
    {
        // Save each page as an individual PNG image.                    
        foreach (Aspose.Imaging.FileFormats.Dicom.DicomPage dicomPage in dicomImage.DicomPages)
        {
            // Generate a file name based on the page index.
            string fileName = string.Format("sample.{0}.png", dicomPage.Index);

            // A DICOM page is a raster image, so all allowed operations with a raster image are applicable to a DICOM page.
            dicomPage.Save(dir + fileName, new Aspose.Imaging.ImageOptions.PngOptions());
        }
    }
}
```

Create a multi-page Dicom image.

```csharp
[C#]

using (DicomImage image = (DicomImage)Image.Create(
        new DicomOptions() { Source = new StreamSource(new MemoryStream()) },
        100,
        100))
{
    // Draw something using vector graphics
    Graphics graphics = new Graphics(image);
    graphics.FillRectangle(new SolidBrush(Color.BlueViolet), image.Bounds);
    graphics.FillRectangle(new SolidBrush(Color.Aqua), 10, 20, 50, 20);
    graphics.FillEllipse(new SolidBrush(Color.Orange), 30, 50, 70, 30);

    // Save the pixels of the drawn image. They are now on the first page of the Dicom image.
    int[] pixels = image.LoadArgb32Pixels(image.Bounds);

    // Add a few pages after, making them darker
    for (int i = 1; i < 5; i++)
    {
        DicomPage page = image.AddPage();
        page.SaveArgb32Pixels(page.Bounds, pixels);
        page.AdjustBrightness(i * 30);
    }

    // Add a few pages in front of the main page, making them brighter
    for (int i = 1; i < 5; i++)
    {
        DicomPage page = image.InsertPage(0);
        page.SaveArgb32Pixels(page.Bounds, pixels);
        page.AdjustBrightness(-i * 30);
    }

    // Save the created multi-page image to the output file
    image.Save("MultiPage.dcm");
}
```

### See Also

* class [RasterCachedMultipageImage](../../aspose.imaging/rastercachedmultipageimage)
* interface [IMultipageImageExt](../../aspose.imaging/imultipageimageext)
* namespace [Aspose.Imaging.FileFormats.Dicom](../../aspose.imaging.fileformats.dicom)
* assembly [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
