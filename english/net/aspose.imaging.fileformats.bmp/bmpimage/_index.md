---
title: Class BmpImage
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Bmp.BmpImage class. You can effortlessly handle Bitmap BMP and Device Independent Bitmap DIB files facilitating efficient manipulation and processing of raster images. Performing various operations on images this API streamlines the workflow offering developers a reliable toolkit for working with BMP and DIB formats in their software applications
type: docs
weight: 1430
url: /net/aspose.imaging.fileformats.bmp/bmpimage/
---
## BmpImage class

You can effortlessly handle Bitmap (BMP) and Device Independent Bitmap (DIB) files, facilitating efficient manipulation and processing of raster images. Performing various operations on images, this API streamlines the workflow, offering developers a reliable toolkit for working with BMP and DIB formats in their software applications.

```csharp
public sealed class BmpImage : RasterCachedImage
```

## Constructors

| Name | Description |
| --- | --- |
| [BmpImage](bmpimage/#constructor)(RasterImage) | Effortlessly create a new instance of the `BmpImage` class by initializing it with a RasterImage object. Perfect for developers looking to seamlessly convert existing raster images to the BmpImage format, ensuring compatibility and ease of integration into their projects. |
| [BmpImage](bmpimage/#constructor_5)(Stream) | Begin using the `BmpImage` class effortlessly by initializing a new instance with this constructor, using a stream as input. Perfect for developers seeking a convenient way to work with BmpImage objects from various data sources, ensuring flexibility and ease of integration. |
| [BmpImage](bmpimage/#constructor_7)(string) | Start using the BmpImage class effortlessly with this constructor that initializes a new instance. Perfect for developers who want to get up and running with `BmpImage` objects quickly and efficiently. |
| [BmpImage](bmpimage/#constructor_2)(int, int) | Start using the `BmpImage` class effortlessly by creating a new instance with specified width and height parameters. Ideal for developers seeking a convenient way to generate BmpImage objects of custom dimensions, ensuring flexibility and ease of integration into their projects. |
| [BmpImage](bmpimage/#constructor_3)(int, int, ushort, IColorPalette) | Begin using the `BmpImage` class seamlessly by initializing a new instance with parameters such as width, height, bit depth, and palette. Perfect for developers seeking a straightforward way to create BmpImage objects with custom dimensions and color configurations, ensuring flexibility and efficiency in their projects. |
| [BmpImage](bmpimage/#constructor_1)(RasterImage, ushort, BitmapCompression, double, double) | Start working with the `BmpImage` class seamlessly by creating a new instance using a rasterImage along with specified parameters like bitsPerPixel and compression. Perfect for developers seeking a straightforward way to handle BmpImage objects, ensuring flexibility and efficiency in their projects. |
| [BmpImage](bmpimage/#constructor_6)(Stream, ushort, BitmapCompression, double, double) | Start working with the `BmpImage` class seamlessly by creating a new instance using a stream, along with specified parameters like bitsPerPixel and compression. Perfect for developers seeking a straightforward way to handle BmpImage objects, ensuring flexibility and efficiency in their projects. |
| [BmpImage](bmpimage/#constructor_8)(string, ushort, BitmapCompression, double, double) | Effortlessly create a new instance of the `BmpImage` class with this constructor, using specified parameters like path, bitsPerPixel, and compression. Ideal for developers looking to initialize BmpImage objects quickly and efficiently, with precise control over image characteristics. |
| [BmpImage](bmpimage/#constructor_4)(int, int, ushort, IColorPalette, BitmapCompression, double, double) | Effortlessly create a new instance of the `BmpImage` class with this constructor, specifying parameters like width, height, bitsPerPixel, and palette. Perfect for developers seeking a convenient way to generate BmpImage objects with custom dimensions and color configurations, ensuring flexibility and ease of integration into their projects. |

## Properties

| Name | Description |
| --- | --- |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette/) { get; set; } | Gets or sets a value indicating whether automatic adjust palette. |
| virtual [BackgroundColor](../../aspose.imaging/image/backgroundcolor/) { get; set; } | Gets or sets a value for the background color. |
| [BitmapInfoHeader](../../aspose.imaging.fileformats.bmp/bmpimage/bitmapinfoheader/) { get; } | Quickly access essential details about your bitmap image with this straightforward function. Perfect for developers needing to retrieve header information for their images. |
| override [BitsPerPixel](../../aspose.imaging.fileformats.bmp/bmpimage/bitsperpixel/) { get; } | Access the number of bits per pixel for the image with ease using this property. Perfect for developers seeking quick information about image quality and depth. |
| [Bounds](../../aspose.imaging/image/bounds/) { get; } | Gets the image bounds. |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint/) { get; set; } | Gets or sets the buffer size hint which is defined max allowed size for all internal buffers. |
| [Compression](../../aspose.imaging.fileformats.bmp/bmpimage/compression/) { get; } | Retrieve the compression type used for the image effortlessly with this property. Perfect for developers needing to quickly access information about image compression. |
| [Container](../../aspose.imaging/image/container/) { get; } | Gets the [`Image`](../../aspose.imaging/image/) container. |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer/) { get; } | Gets the object's data stream. |
| [Disposed](../../aspose.imaging/disposableobject/disposed/) { get; } | Gets a value indicating whether this instance is disposed. |
| override [FileFormat](../../aspose.imaging.fileformats.bmp/bmpimage/fileformat/) { get; } | Easily retrieve the file format value with this user-friendly property. Ideal for developers seeking quick access to information about the file format. |
| override [HasAlpha](../../aspose.imaging.fileformats.bmp/bmpimage/hasalpha/) { get; } | Gets a value indicating whether this instance has alpha. |
| virtual [HasBackgroundColor](../../aspose.imaging/image/hasbackgroundcolor/) { get; set; } | Gets or sets a value indicating whether image has background color. |
| virtual [HasTransparentColor](../../aspose.imaging/rasterimage/hastransparentcolor/) { get; set; } | Gets a value indicating whether image has transparent color. |
| override [Height](../../aspose.imaging.fileformats.bmp/bmpimage/height/) { get; } | Retrieve the height of the image effortlessly with this property. Ideal for developers needing quick access to information about image dimensions. |
| override [HorizontalResolution](../../aspose.imaging.fileformats.bmp/bmpimage/horizontalresolution/) { get; set; } | This property allows you to easily get or set the horizontal resolution, measured in pixels per inch, of the [`RasterImage`](../../aspose.imaging/rasterimage/) object. Ideal for developers needing precise control over image resolution for their applications. |
| virtual [ImageOpacity](../../aspose.imaging/rasterimage/imageopacity/) { get; } | Gets opacity of this image. |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor/) { get; set; } | Gets or sets the interrupt monitor. |
| override [IsCached](../../aspose.imaging/rastercachedimage/iscached/) { get; } | Gets a value indicating whether image data is cached currently. |
| [IsRawDataAvailable](../../aspose.imaging/rasterimage/israwdataavailable/) { get; } | Gets a value indicating whether raw data loading is available. |
| [Palette](../../aspose.imaging/image/palette/) { get; set; } | Gets or sets the color palette. The color palette is not used when pixels are represented directly. |
| virtual [PremultiplyComponents](../../aspose.imaging/rasterimage/premultiplycomponents/) { get; set; } | Gets or sets a value indicating whether the image components must be premultiplied. |
| [RawCustomColorConverter](../../aspose.imaging/rasterimage/rawcustomcolorconverter/) { get; set; } | Gets or sets the custom color converter |
| override [RawDataFormat](../../aspose.imaging.fileformats.bmp/bmpimage/rawdataformat/) { get; } | Easily obtain the format of your raw data with this user-friendly function. Perfect for developers looking to quickly access crucial information about their data format. |
| [RawDataSettings](../../aspose.imaging/rasterimage/rawdatasettings/) { get; } | Gets the current raw data settings. Note when using these settings the data loads without conversion. |
| [RawFallbackIndex](../../aspose.imaging/rasterimage/rawfallbackindex/) { get; set; } | Gets or sets the fallback index to use when palette index is out of bounds |
| [RawIndexedColorConverter](../../aspose.imaging/rasterimage/rawindexedcolorconverter/) { get; set; } | Gets or sets the indexed color converter |
| override [RawLineSize](../../aspose.imaging.fileformats.bmp/bmpimage/rawlinesize/) { get; } | Quickly access the size of each raw line in bytes with this straightforward property. Ideal for developers needing to efficiently handle raw image data. |
| [Size](../../aspose.imaging/image/size/) { get; } | Gets the image size. |
| virtual [TransparentColor](../../aspose.imaging/rasterimage/transparentcolor/) { get; set; } | Gets the image transparent color. |
| virtual [UpdateXmpData](../../aspose.imaging/rasterimage/updatexmpdata/) { get; set; } | Gets or sets a value indicating whether to update the XMP metadata. |
| override [UsePalette](../../aspose.imaging/rasterimage/usepalette/) { get; } | Gets a value indicating whether the image palette is used. |
| virtual [UseRawData](../../aspose.imaging/rasterimage/userawdata/) { get; set; } | Gets or sets a value indicating whether to use raw data loading when the raw data loading is available. |
| override [VerticalResolution](../../aspose.imaging.fileformats.bmp/bmpimage/verticalresolution/) { get; set; } | Easily retrieve or set the vertical resolution, measured in pixels per inch, of this [`RasterImage`](../../aspose.imaging/rasterimage/) object with this property. Perfect for developers requiring precise control over image resolution in their applications. |
| override [Width](../../aspose.imaging.fileformats.bmp/bmpimage/width/) { get; } | Access the width of the image easily with this property. Ideal for developers seeking quick information about the image dimensions. |
| virtual [XmpData](../../aspose.imaging/rasterimage/xmpdata/) { get; set; } | Gets or sets the XMP metadata. |

## Methods

| Name | Description |
| --- | --- |
| override [AdjustBrightness](../../aspose.imaging/rastercachedimage/adjustbrightness/)(int) | Adjust of a brightness for image. |
| override [AdjustContrast](../../aspose.imaging/rastercachedimage/adjustcontrast/)(float) | Image contrasting |
| override [AdjustGamma](../../aspose.imaging/rastercachedimage/adjustgamma/)(float) | Gamma-correction of an image. |
| override [AdjustGamma](../../aspose.imaging/rastercachedimage/adjustgamma/)(float, float, float) | Gamma-correction of an image. |
| override [AnalyzePercentageDigitalSignature](../../aspose.imaging/rastercachedimage/analyzepercentagedigitalsignature/)(string) | Calculates the percentage similarity between the extracted data and the original password. |
| override [AutoBrightnessContrast](../../aspose.imaging/rastercachedimage/autobrightnesscontrast/)() | Performs automatic adaptive brightness and contrast normalization for the entire image. |
| override [BinarizeBradley](../../aspose.imaging/rastercachedimage/binarizebradley/)(double) | Binarization of an image using Bradley's adaptive thresholding algorithm using the integral image thresholding |
| override [BinarizeBradley](../../aspose.imaging/rastercachedimage/binarizebradley/)(double, int) | Binarization of an image using Bradley's adaptive thresholding algorithm using the integral image thresholding |
| override [BinarizeFixed](../../aspose.imaging/rastercachedimage/binarizefixed/)(byte) | Binarization of an image with predefined threshold |
| override [BinarizeOtsu](../../aspose.imaging/rastercachedimage/binarizeotsu/)() | Binarization of an image with Otsu thresholding |
| [Blend](../../aspose.imaging/rasterimage/blend/)(Point, RasterImage, byte) | Blends this image instance with the *overlay* image. |
| override [Blend](../../aspose.imaging/rastercachedimage/blend/)(Point, RasterImage, Rectangle, byte) | Blends this image instance with the *overlay* image. |
| override [CacheData](../../aspose.imaging/rastercachedimage/cachedata/)() | Caches the data and ensures no additional data loading will be performed from the underlying [`DataStreamContainer`](../../aspose.imaging/datastreamsupporter/datastreamcontainer/). |
| [CanSave](../../aspose.imaging/image/cansave/)(ImageOptionsBase) | Determines whether image can be saved to the specified file format represented by the passed save options. |
| override [Crop](../../aspose.imaging/rastercachedimage/crop/)(Rectangle) | Cropping the image. |
| virtual [Crop](../../aspose.imaging/image/crop/)(int, int, int, int) | Crop image with shifts. |
| [Dispose](../../aspose.imaging/disposableobject/dispose/)() | Disposes the current instance. |
| [Dither](../../aspose.imaging/rasterimage/dither/)(DitheringMethod, int) | Performs dithering on the current image. |
| override [Dither](../../aspose.imaging/rastercachedimage/dither/)(DitheringMethod, int, IColorPalette) | Performs dithering on the current image. |
| override [EmbedDigitalSignature](../../aspose.imaging/rastercachedimage/embeddigitalsignature/)(string) | Embed digital sign based on provided password into the image using steganography. |
| virtual [Filter](../../aspose.imaging/rasterimage/filter/)(Rectangle, FilterOptionsBase) | Filters the specified rectangle. |
| [GetArgb32Pixel](../../aspose.imaging/rasterimage/getargb32pixel/)(int, int) | Gets an image 32-bit ARGB pixel. |
| [GetDefaultArgb32Pixels](../../aspose.imaging/rasterimage/getdefaultargb32pixels/)(Rectangle) | Gets the default 32-bit ARGB pixels array. |
| override [GetDefaultOptions](../../aspose.imaging.fileformats.bmp/bmpimage/getdefaultoptions/)(object[]) | Retrieve the default options effortlessly with this straightforward method. Ideal for developers seeking quick access to default image settings or configurations. |
| [GetDefaultPixels](../../aspose.imaging/rasterimage/getdefaultpixels/)(Rectangle, IPartialArgb32PixelLoader) | Gets the default pixels array using partial pixel loader. |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata/)(Rectangle, RawDataSettings) | Gets the default raw data array. |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata/)(Rectangle, IPartialRawDataLoader, RawDataSettings) | Gets the default raw data array using partial pixel loader. |
| virtual [GetModifyDate](../../aspose.imaging/rasterimage/getmodifydate/)(bool) | Gets the date and time the resource image was last modified. |
| virtual [GetOriginalOptions](../../aspose.imaging/image/getoriginaloptions/)() | Gets the options based on the original file settings. This can be helpful to keep bit-depth and other parameters of the original image unchanged. For example, if we load a black-white PNG image with 1 bit per pixel and then save it using the [`Save`](../../aspose.imaging/datastreamsupporter/save/) method, the output PNG image with 8-bit per pixel will be produced. To avoid it and save PNG image with 1-bit per pixel, use this method to get corresponding saving options and pass them to the [`Save`](../../aspose.imaging/image/save/) method as the second parameter. |
| [GetPixel](../../aspose.imaging/rasterimage/getpixel/)(int, int) | Gets an image pixel. |
| virtual [GetSerializedStream](../../aspose.imaging/image/getserializedstream/)(ImageOptionsBase, Rectangle, out int) | Converts to aps. |
| [GetSkewAngle](../../aspose.imaging/rasterimage/getskewangle/)() | Gets the skew angle. This method is applicable to scanned text documents, to determine the skew angle when scanning. |
| override [Grayscale](../../aspose.imaging/rastercachedimage/grayscale/)() | Transformation of an image to its grayscale representation |
| override [IsDigitalSigned](../../aspose.imaging/rastercachedimage/isdigitalsigned/)(string, int) | Performs a fast check to determine if the image is digitally signed, using the provided password and threshold. |
| [LoadArgb32Pixels](../../aspose.imaging/rasterimage/loadargb32pixels/)(Rectangle) | Loads 32-bit ARGB pixels. |
| [LoadArgb64Pixels](../../aspose.imaging/rasterimage/loadargb64pixels/)(Rectangle) | Loads 64-bit ARGB pixels. |
| [LoadCmyk32Pixels](../../aspose.imaging/rasterimage/loadcmyk32pixels/)(Rectangle) | Loads pixels in CMYK format. |
| [LoadPartialArgb32Pixels](../../aspose.imaging/rasterimage/loadpartialargb32pixels/)(Rectangle, IPartialArgb32PixelLoader) | Loads 32-bit ARGB pixels partially by packs. |
| [LoadPartialArgb64Pixels](../../aspose.imaging/rasterimage/loadpartialargb64pixels/)(Rectangle, IPartialArgb64PixelLoader) | Loads 64-bit ARGB pixels partially by packs. |
| [LoadPartialPixels](../../aspose.imaging/rasterimage/loadpartialpixels/)(Rectangle, IPartialPixelLoader) | Loads pixels partially by packs. |
| [LoadPixels](../../aspose.imaging/rasterimage/loadpixels/)(Rectangle) | Loads pixels. |
| [LoadRawData](../../aspose.imaging/rasterimage/loadrawdata/)(Rectangle, RawDataSettings, IPartialRawDataLoader) | Loads raw data. |
| [LoadRawData](../../aspose.imaging/rasterimage/loadrawdata/)(Rectangle, Rectangle, RawDataSettings, IPartialRawDataLoader) | Loads raw data. |
| [NormalizeAngle](../../aspose.imaging/rasterimage/normalizeangle/)() | Normalizes the angle. This method is applicable to scanned text documents to get rid of the skewed scan. This method uses [`GetSkewAngle`](../../aspose.imaging/rasterimage/getskewangle/) and [`Rotate`](../../aspose.imaging/rasterimage/rotate/) methods. |
| virtual [NormalizeAngle](../../aspose.imaging/rasterimage/normalizeangle/)(bool, Color) | Normalizes the angle. This method is applicable to scanned text documents to get rid of the skewed scan. This method uses [`GetSkewAngle`](../../aspose.imaging/rasterimage/getskewangle/) and [`Rotate`](../../aspose.imaging/rasterimage/rotate/) methods. |
| override [NormalizeHistogram](../../aspose.imaging/rastercachedimage/normalizehistogram/)() | Normalizes the image histogram — adjust pixel values to use all available range. |
| [ReadArgb32ScanLine](../../aspose.imaging/rasterimage/readargb32scanline/)(int) | Reads the whole scan line by the specified scan line index. |
| [ReadScanLine](../../aspose.imaging/rasterimage/readscanline/)(int) | Reads the whole scan line by the specified scan line index. |
| override [RemoveMetadata](../../aspose.imaging/rasterimage/removemetadata/)() | Removes this image instance metadata by setting this [`XmpData`](../../aspose.imaging.xmp/ihasxmpdata/xmpdata/) value to `null`. |
| [ReplaceColor](../../aspose.imaging/rasterimage/replacecolor/)(Color, byte, Color) | Replaces one color to another with allowed difference and preserves original alpha value to save smooth edges. |
| virtual [ReplaceColor](../../aspose.imaging/rasterimage/replacecolor/)(int, byte, int) | Replaces one color to another with allowed difference and preserves original alpha value to save smooth edges. |
| [ReplaceNonTransparentColors](../../aspose.imaging/rasterimage/replacenontransparentcolors/)(Color) | Replaces all non-transparent colors with new color and preserves original alpha value to save smooth edges. Note: if you use it on images without transparency, all colors will be replaced with a single one. |
| virtual [ReplaceNonTransparentColors](../../aspose.imaging/rasterimage/replacenontransparentcolors/)(int) | Replaces all non-transparent colors with new color and preserves original alpha value to save smooth edges. Note: if you use it on images without transparency, all colors will be replaced with a single one. |
| [Resize](../../aspose.imaging/image/resize/)(int, int) | Resizes the image. The default NearestNeighbourResample is used. |
| override [Resize](../../aspose.imaging/rastercachedimage/resize/)(int, int, ImageResizeSettings) | Resizes the image. |
| override [Resize](../../aspose.imaging/rastercachedimage/resize/)(int, int, ResizeType) | Resizes the image. |
| [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally/)(int) | Resizes the height proportionally. The default NearestNeighbourResample is used. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally/)(int, ImageResizeSettings) | Resizes the height proportionally. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally/)(int, ResizeType) | Resizes the height proportionally. |
| [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally/)(int) | Resizes the width proportionally. The default NearestNeighbourResample is used. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally/)(int, ImageResizeSettings) | Resizes the width proportionally. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally/)(int, ResizeType) | Resizes the width proportionally. |
| override [Rotate](../../aspose.imaging/rasterimage/rotate/)(float) | Rotate image around the center. |
| override [Rotate](../../aspose.imaging/rastercachedimage/rotate/)(float, bool, Color) | Rotate image around the center. |
| override [RotateFlip](../../aspose.imaging/rastercachedimage/rotateflip/)(RotateFlipType) | Rotates, flips, or rotates and flips the image. |
| [Save](../../aspose.imaging/image/save/)() | Saves the image data to the underlying stream. |
| [Save](../../aspose.imaging/datastreamsupporter/save/)(Stream) | Saves the object's data to the specified stream. |
| override [Save](../../aspose.imaging/image/save/)(string) | Saves the image to the specified file location. |
| [Save](../../aspose.imaging/image/save/)(Stream, ImageOptionsBase) | Saves the image's data to the specified stream in the specified file format according to save options. |
| virtual [Save](../../aspose.imaging/datastreamsupporter/save/)(string, bool) | Saves the object's data to the specified file location. |
| virtual [Save](../../aspose.imaging/image/save/)(string, ImageOptionsBase) | Saves the object's data to the specified file location in the specified file format according to save options. |
| override [Save](../../aspose.imaging/rasterimage/save/)(Stream, ImageOptionsBase, Rectangle) | Saves the image's data to the specified stream in the specified file format according to save options. |
| virtual [Save](../../aspose.imaging/image/save/)(string, ImageOptionsBase, Rectangle) | Saves the object's data to the specified file location in the specified file format according to save options. |
| [SaveArgb32Pixels](../../aspose.imaging/rasterimage/saveargb32pixels/)(Rectangle, int[]) | Saves the 32-bit ARGB pixels. |
| [SaveCmyk32Pixels](../../aspose.imaging/rasterimage/savecmyk32pixels/)(Rectangle, int[]) | Saves the pixels. |
| [SavePixels](../../aspose.imaging/rasterimage/savepixels/)(Rectangle, Color[]) | Saves the pixels. |
| [SaveRawData](../../aspose.imaging/rasterimage/saverawdata/)(byte[], int, Rectangle, RawDataSettings) | Saves the raw data. |
| [SetArgb32Pixel](../../aspose.imaging/rasterimage/setargb32pixel/)(int, int, int) | Sets an image 32-bit ARGB pixel for the specified position. |
| override [SetPalette](../../aspose.imaging/rasterimage/setpalette/)(IColorPalette, bool) | Sets the image palette. |
| [SetPixel](../../aspose.imaging/rasterimage/setpixel/)(int, int, Color) | Sets an image pixel for the specified position. |
| override [SetResolution](../../aspose.imaging.fileformats.bmp/bmpimage/setresolution/)(double, double) | Adjust the resolution of your [`RasterImage`](../../aspose.imaging/rasterimage/) effortlessly with this user-friendly method. Perfect for developers seeking precise control over image resolution in their applications. |
| override [ToBitmap](../../aspose.imaging.fileformats.bmp/bmpimage/tobitmap/)() | Easily convert your raster image to a bitmap with this simple method. Perfect for developers needing to seamlessly transition between different image formats. |
| [WriteArgb32ScanLine](../../aspose.imaging/rasterimage/writeargb32scanline/)(int, int[]) | Writes the whole scan line to the specified scan line index. |
| [WriteScanLine](../../aspose.imaging/rasterimage/writescanline/)(int, Color[]) | Writes the whole scan line to the specified scan line index. |

## Examples

Decompress BMP image which was previously compressed using DXT1 compression algorithm.

```csharp
[C#]

using (var image = Image.Load("CompressedTiger.bmp"))
{
    image.Save("DecompressedTiger.bmp", new BmpOptions());
}
```

Compress BMP image using DXT1 compression algorithm.

```csharp
[C#]

using (var image = Image.Load("Tiger.bmp"))
{
    image.Save("CompressedTiger.bmp", new BmpOptions { Compression = BitmapCompression.Dxt1 });
}
```

The example shows how to remove any object from the image using Graphics Path with Telea algorithm.

```csharp
[C#]

var imageFilePath = "ball.png"; 
using (var image = Image.Load(imageFilePath))
{
    var pngImage = (PngImage)image;

    var mask = new GraphicsPath();
    var firstFigure = new Figure();
    firstFigure.AddShape(new EllipseShape(new RectangleF(350, 170, 570 - 350, 400 - 170)));
    mask.AddFigure(firstFigure);

    var options = new TeleaWatermarkOptions(mask);

    var result = WatermarkRemover.PaintOver(pngImage, options);

    result.Save(outputPath);
}
```

The example shows how to export a BmpImage with the Rgb compression type.

```csharp
[C#]

string sourcePath = "input.png";
// Load a PNG image from a file.
using (Image pngImage = Image.Load(sourcePath))
{
    // BMP image is saved with transparency support by default, that is achieved by using the BitmapCompression.Bitfields compression method. 
    // To save a BMP image with the Rgb compression method, the BmpOptions with the Compression property set to BitmapCompression.Rgb should be specified.
    pngImage.Save(outputPath, new BmpOptions() { Compression = BitmapCompression.Rgb });
}
```

The example shows how to remove any object from the image using Graphics Path with Content Aware fill algorithm.

```csharp
[C#]

var imageFilePath = "ball.png"; 
using (var image = Image.Load(imageFilePath))
{
    var pngImage = (PngImage)image;

    var mask = new GraphicsPath();
    var firstFigure = new Figure();
    firstFigure.AddShape(new EllipseShape(new RectangleF(350, 170, 570 - 350, 400 - 170)));
    mask.AddFigure(firstFigure);

    var options = new ContentAwareFillWatermarkOptions(mask) 
    { 
        MaxPaintingAttempts = 4
    };

    var result = WatermarkRemover.PaintOver(pngImage, options);

    result.Save(outputPath);
}
```

The following example shows how to create a BMP image of the specified size.

```csharp
[C#]

string dir = "c:\\temp\\";

// Create a BMP image 100 x 100 px.
using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(100, 100))
{
    // Fill the image with a simple linear red-black gradient.
    int width = bmpImage.Width;
    int height = bmpImage.Height;
    for (int y = 0; y < height; y++)
    {
        for (int x = 0; x < width; x++)
        {
            int hue = (255 * x) / width;
            bmpImage.SetPixel(x, y, Aspose.Imaging.Color.FromArgb(255, hue, 0, 0));
        }
    }

    using (System.IO.FileStream stream = new System.IO.FileStream(dir + "output.bmp", System.IO.FileMode.Create))
    {
        bmpImage.Save(stream);
    }
}
```

The example shows how to export a BmpImage from a Png file while keeping the alpha channel, save a Bmp file with transparency.

```csharp
[C#]

string sourcePath = "input.png";
// Load a PNG image from a file.
using (Image pngImage = Image.Load(sourcePath))
{
    // BMP image is saved with transparency support by default. 
    // If you want to explicitly specify such mode, the BmpOptions's Compression property should be set to BitmapCompression.Bitfields.
    // The BitmapCompression.Bitfields compression method is the default compression method in the BmpOptions.
    // So the same result of exporting a Bmp image with transparency can be achieved by either one of the following ways.
    // With an implicit default options:
    pngImage.Save(outputPath);
    // With an explicit default options:
    pngImage.Save(outputPath, new BmpOptions());
    // Specifying the BitmapCompression.Bitfields compression method:
    pngImage.Save(outputPath, new BmpOptions() { Compression = BitmapCompression.Bitfields });
}
```

### See Also

* class [RasterCachedImage](../../aspose.imaging/rastercachedimage/)
* namespace [Aspose.Imaging.FileFormats.Bmp](../../aspose.imaging.fileformats.bmp/)
* assembly [Aspose.Imaging](../../)


