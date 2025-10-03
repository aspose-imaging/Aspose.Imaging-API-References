---
title: Class PngImage
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Png.PngImage class. Manipulate Portable Network Graphics PNG raster images with our versatile API featuring support for compression levels and various color depths including Grayscale Indexed Color TrueColor and alpha channels. Seamlessly process XMP metadata enabling comprehensive image metadata management while easily loading PNG images performing diverse manipulations applying filters and converting images to other file formats for optimal versatility and customization
type: docs
weight: 7520
url: /net/aspose.imaging.fileformats.png/pngimage/
---
## PngImage class

Manipulate Portable Network Graphics (PNG) raster images with our versatile API, featuring support for compression levels and various color depths including Grayscale, Indexed Color, TrueColor, and alpha channels. Seamlessly process XMP metadata, enabling comprehensive image metadata management, while easily loading PNG images, performing diverse manipulations, applying filters, and converting images to other file formats for optimal versatility and customization.

```csharp
public class PngImage : RasterCachedImage
```

## Constructors

| Name | Description |
| --- | --- |
| [PngImage](pngimage/#constructor_1)(RasterImage) | Creates a new instance of the `PngImage` class by providing a raster image as a parameter. This constructor allows developers to directly initialize a PNG image object using an existing raster image, streamlining the process of working with PNG images in their applications. |
| [PngImage](pngimage/#constructor_5)(Stream) | Creates a new instance of the `PngImage` class by initializing it with a stream. This constructor allows developers to load PNG images directly from a stream, providing flexibility in image retrieval from different sources. |
| [PngImage](pngimage/#constructor_6)(string) | Constructs a new instance of the `PngImage` class using the path parameter to specify the location of the image file to load. This constructor enables developers to conveniently create PNG images by loading them from a file, simplifying the process of working with PNG images in their applications. |
| [PngImage](pngimage/#constructor_3)(int, int) | Initialize a new object of the `PngImage` class by providing the width and height parameters. This constructor simplifies the creation of PNG images by allowing developers to specify the dimensions directly, facilitating efficient management of PNG image data within their applications. |
| [PngImage](pngimage/#constructor_2)(RasterImage, PngColorType) | Creates a new instance of the `PngImage` class by specifying a raster image and a color type. This constructor enables developers to directly convert raster images into PNG format while specifying the desired color type, offering flexibility in color representation. |
| [PngImage](pngimage/#constructor_7)(string, PngColorType) | Initializes a new instance of the `PngImage` class by specifying the path to the image file and the color type. This constructor allows for convenient creation of PNG images from files with different color types, providing flexibility in handling various image formats. |
| [PngImage](pngimage/#constructor_4)(int, int, PngColorType) | Instantiate a fresh instance of the `PngImage` class, specifying the desired width, height, and color type parameters. This constructor enables swift creation of PNG images with tailored dimensions and color configurations, facilitating streamlined image generation for various applications and workflows. |
| [PngImage](pngimage/#constructor)(PngOptions, int, int) | Initialize a new instance of the `PngImage` class, incorporating PNG options alongside width and height parameters. This constructor empowers developers to create PNG images with customizable settings and dimensions, offering flexibility in image generation for diverse use cases. |

## Properties

| Name | Description |
| --- | --- |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette/) { get; set; } | Gets or sets a value indicating whether automatic adjust palette. |
| override [BackgroundColor](../../aspose.imaging.fileformats.png/pngimage/backgroundcolor/) { get; set; } | Retrieves the background color of the image, if one is specified. This property is helpful for applications that need to identify and potentially manipulate the background color of an image. |
| override [BitsPerPixel](../../aspose.imaging.fileformats.png/pngimage/bitsperpixel/) { get; } | Retrieve the bits per pixel value for the image. This property provides crucial information regarding the color depth of the image, enabling developers to understand the level of detail and color accuracy present in the image data. |
| [Bounds](../../aspose.imaging/image/bounds/) { get; } | Gets the image bounds. |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint/) { get; set; } | Gets or sets the buffer size hint which is defined max allowed size for all internal buffers. |
| [Container](../../aspose.imaging/image/container/) { get; } | Gets the [`Image`](../../aspose.imaging/image/) container. |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer/) { get; } | Gets the object's data stream. |
| [Disposed](../../aspose.imaging/disposableobject/disposed/) { get; } | Gets a value indicating whether this instance is disposed. |
| [ExifData](../../aspose.imaging/image/exifdata/) { get; set; } | Gets or sets the Exif data. |
| override [FileFormat](../../aspose.imaging.fileformats.png/pngimage/fileformat/) { get; } | Retrieves the format of the file associated with the image instance. This property provides essential information regarding the file type, enabling efficient handling and processing based on the specific format requirements. |
| override [HasAlpha](../../aspose.imaging.fileformats.png/pngimage/hasalpha/) { get; } | Returns a boolean value indicating whether the image has an alpha channel, which determines its transparency. This property is useful for applications that need to handle transparency, allowing developers to determine whether additional processing is required to handle transparent areas in the image. |
| override [HasBackgroundColor](../../aspose.imaging.fileformats.png/pngimage/hasbackgroundcolor/) { get; set; } | Retrieves a boolean value indicating whether the image has a background color. This property is useful for applications needing to determine if an image includes a background color, which can be important for various processing tasks such as compositing, rendering, or exporting. |
| override [HasTransparentColor](../../aspose.imaging.fileformats.png/pngimage/hastransparentcolor/) { get; set; } | Provides a boolean value indicating whether the image contains a transparent color. This property is crucial for applications that need to handle transparency, allowing developers to determine whether additional processing is required to handle transparent regions in the image. |
| override [Height](../../aspose.imaging.fileformats.png/pngimage/height/) { get; } | Obtain the height of the image. This property returns the vertical dimension of the image, allowing developers to determine its size in pixels along the vertical axis. |
| override [HorizontalResolution](../../aspose.imaging.fileformats.png/pngimage/horizontalresolution/) { get; set; } | Retrieve or modify the horizontal resolution of the image. This property represents the number of pixels per inch along the horizontal axis of the image. Adjusting this resolution can affect the physical size of the image when printed or displayed. |
| virtual [ImageOpacity](../../aspose.imaging/rasterimage/imageopacity/) { get; } | Gets opacity of this image. |
| [Interlaced](../../aspose.imaging.fileformats.png/pngimage/interlaced/) { get; } | Retrieves a boolean value indicating whether the `PngImage` is interlaced, which determines if the image data is stored in a progressive manner for faster loading or transmission. |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor/) { get; set; } | Gets or sets the interrupt monitor. |
| override [IsCached](../../aspose.imaging/rastercachedimage/iscached/) { get; } | Gets a value indicating whether image data is cached currently. |
| [IsInterlaced](../../aspose.imaging.fileformats.png/pngimage/isinterlaced/) { get; } | Returns a boolean value indicating if the image instance is interlaced. This property is crucial for optimizing loading strategies and ensuring efficient performance during image processing or display tasks. |
| [IsRawDataAvailable](../../aspose.imaging/rasterimage/israwdataavailable/) { get; } | Gets a value indicating whether raw data loading is available. |
| virtual [Metadata](../../aspose.imaging/image/metadata/) { get; } | Gets the image metadata. |
| [Palette](../../aspose.imaging/image/palette/) { get; set; } | Gets or sets the color palette. The color palette is not used when pixels are represented directly. |
| virtual [PremultiplyComponents](../../aspose.imaging/rasterimage/premultiplycomponents/) { get; set; } | Gets or sets a value indicating whether the image components must be premultiplied. |
| [RawCustomColorConverter](../../aspose.imaging/rasterimage/rawcustomcolorconverter/) { get; set; } | Gets or sets the custom color converter |
| override [RawDataFormat](../../aspose.imaging.fileformats.png/pngimage/rawdataformat/) { get; } | Accesses the raw data format of the image. This property provides insight into how the image data is structured internally, which can be useful for advanced image processing tasks or format conversion. |
| [RawDataSettings](../../aspose.imaging/rasterimage/rawdatasettings/) { get; } | Gets the current raw data settings. Note when using these settings the data loads without conversion. |
| [RawFallbackIndex](../../aspose.imaging/rasterimage/rawfallbackindex/) { get; set; } | Gets or sets the fallback index to use when palette index is out of bounds |
| [RawIndexedColorConverter](../../aspose.imaging/rasterimage/rawindexedcolorconverter/) { get; set; } | Gets or sets the indexed color converter |
| virtual [RawLineSize](../../aspose.imaging/rasterimage/rawlinesize/) { get; } | Gets the raw line size in bytes. |
| [Size](../../aspose.imaging/image/size/) { get; } | Gets the image size. |
| override [TransparentColor](../../aspose.imaging.fileformats.png/pngimage/transparentcolor/) { get; set; } | Retrieves the transparent color of the image, if it exists. This property is valuable for applications requiring precise handling of transparent areas within images, allowing developers to access and manipulate the specific transparent color used. |
| virtual [UpdateXmpData](../../aspose.imaging/rasterimage/updatexmpdata/) { get; set; } | Gets or sets a value indicating whether to update the XMP metadata. |
| override [UsePalette](../../aspose.imaging/rasterimage/usepalette/) { get; } | Gets a value indicating whether the image palette is used. |
| virtual [UseRawData](../../aspose.imaging/rasterimage/userawdata/) { get; set; } | Gets or sets a value indicating whether to use raw data loading when the raw data loading is available. |
| override [VerticalResolution](../../aspose.imaging.fileformats.png/pngimage/verticalresolution/) { get; set; } | Provides access to the vertical resolution of the image. Developers can use this property to retrieve or modify the resolution setting, which indicates the number of pixels per inch (PPI) along the vertical axis of the image. |
| override [Width](../../aspose.imaging.fileformats.png/pngimage/width/) { get; } | Allows retrieval of the width of the image, providing essential information about its dimensions. This property is frequently used by developers to determine the image's width, enabling them to perform various operations based on its size |
| [XmpData](../../aspose.imaging/image/xmpdata/) { get; set; } | Gets or sets the Xmp data. |

## Methods

| Name | Description |
| --- | --- |
| override [AdjustBrightness](../../aspose.imaging/rastercachedimage/adjustbrightness/)(int) | Adjust of a brightness for image. |
| override [AdjustContrast](../../aspose.imaging/rastercachedimage/adjustcontrast/)(float) | Image contrasting |
| override [AdjustGamma](../../aspose.imaging/rastercachedimage/adjustgamma/)(float) | Gamma-correction of an image. |
| override [AdjustGamma](../../aspose.imaging/rastercachedimage/adjustgamma/)(float, float, float) | Gamma-correction of an image. |
| override [AnalyzePercentageDigitalSignature](../../aspose.imaging/rastercachedimage/analyzepercentagedigitalsignature/)(string) | Calculates the percentage similarity between the extracted data and the original password. |
| override [AutoBrightnessContrast](../../aspose.imaging/rastercachedimage/autobrightnesscontrast/)() | Performs automatic adaptive brightness and contrast normalization for the entire image. |
| [AutoRotate](../../aspose.imaging/rasterimage/autorotate/)() | Automatically rotates the image based on orientation data extracted from Exif metadata. This method ensures that images are displayed in the correct orientation, enhancing user experience and eliminating the need for manual adjustments. By analyzing Exif information, the image is rotated accordingly, providing a seamless viewing experience across different platforms and devices. This automated rotation process simplifies image handling and improves overall usability, especially when dealing with large batches of images with varying orientations. |
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
| override [GetDefaultOptions](../../aspose.imaging.fileformats.png/pngimage/getdefaultoptions/)(object[]) | Gets the default options. |
| [GetDefaultPixels](../../aspose.imaging/rasterimage/getdefaultpixels/)(Rectangle, IPartialArgb32PixelLoader) | Gets the default pixels array using partial pixel loader. |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata/)(Rectangle, RawDataSettings) | Gets the default raw data array. |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata/)(Rectangle, IPartialRawDataLoader, RawDataSettings) | Gets the default raw data array using partial pixel loader. |
| override [GetModifyDate](../../aspose.imaging.fileformats.png/pngimage/getmodifydate/)(bool) | Retrieves the timestamp indicating the most recent modification of the resource image. This method provides access to vital metadata, enabling applications to ascertain when the image was last altered, facilitating version tracking and content management. |
| override [GetOriginalOptions](../../aspose.imaging.fileformats.png/pngimage/getoriginaloptions/)() | Gets the options based on the original file settings. This can be helpful to keep bit-depth and other parameters of the original image unchanged. For example, if we load a black-white PNG image with 1 bit per pixel and then save it using the [`Save`](../../aspose.imaging/datastreamsupporter/save/) method, the output PNG image with 8-bit per pixel will be produced. To avoid it and save PNG image with 1-bit per pixel, use this method to get corresponding saving options and pass them to the [`Save`](../../aspose.imaging/image/save/) method as the second parameter. |
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
| virtual [SetResolution](../../aspose.imaging/rasterimage/setresolution/)(double, double) | Sets the resolution for this [`RasterImage`](../../aspose.imaging/rasterimage/). |
| virtual [ToBitmap](../../aspose.imaging/rasterimage/tobitmap/)() | Converts raster image to the bitmap. This method is not supported in versions from .Net7.0 and higher |
| virtual [TrySetMetadata](../../aspose.imaging/image/trysetmetadata/)(IImageMetadataFormat) | Tries to set a *metadata* instance, if this [`Image`](../../aspose.imaging/image/) instance supports and implements [`IImageMetadataFormat`](../../aspose.imaging.metadata/iimagemetadataformat/) type. |
| [WriteArgb32ScanLine](../../aspose.imaging/rasterimage/writeargb32scanline/)(int, int[]) | Writes the whole scan line to the specified scan line index. |
| [WriteScanLine](../../aspose.imaging/rasterimage/writescanline/)(int, Color[]) | Writes the whole scan line to the specified scan line index. |

## Examples

This example shows how to load a PNG image from a file.

```csharp
[C#]

string dir = "c:\\temp\\";

// Load a PNG image from a file.
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(dir + "sample.png"))
{
    // Transform the image to grayscale representation
    pngImage.Grayscale();

    // Save to a file.
    pngImage.Save(dir + "sample.grayscale.png");
}
```

### See Also

* class [RasterCachedImage](../../aspose.imaging/rastercachedimage/)
* namespace [Aspose.Imaging.FileFormats.Png](../../aspose.imaging.fileformats.png/)
* assembly [Aspose.Imaging](../../)


