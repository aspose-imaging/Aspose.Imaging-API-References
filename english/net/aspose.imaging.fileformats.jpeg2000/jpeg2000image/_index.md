---
title: Class Jpeg2000Image
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image class. Efficiently manipulate JPEG2000 JP2 image files with our API supporting a range of bits per pixel depths and seamless processing of XMP metadata containing essential image information. With capabilities for lossless compression ensure optimal image quality while maintaining file integrity empowering you to tailor JP2 images to your exact specifications with ease
type: docs
weight: 6940
url: /net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/
---
## Jpeg2000Image class

Efficiently manipulate JPEG2000 (JP2) image files with our API, supporting a range of bits per pixel depths and seamless processing of XMP metadata containing essential image information. With capabilities for lossless compression, ensure optimal image quality while maintaining file integrity, empowering you to tailor JP2 images to your exact specifications with ease.

```csharp
public sealed class Jpeg2000Image : RasterCachedImage
```

## Constructors

| Name | Description |
| --- | --- |
| [Jpeg2000Image](jpeg2000image/#constructor)(RasterImage) | Instantiate a new `Jpeg2000Image` class with a raster image. This constructor facilitates the creation of a JPEG2000 image from an existing raster image, offering seamless integration and conversion between different image formats. |
| [Jpeg2000Image](jpeg2000image/#constructor_5)(Stream) | Easily initialize a new instance of the `Jpeg2000Image` class by providing a stream object. This constructor simplifies the process of loading JPEG2000 images directly from streams, offering flexibility and convenience for handling image data from various sources. |
| [Jpeg2000Image](jpeg2000image/#constructor_7)(string) | Start working with the `Jpeg2000Image` class by initializing a new instance with the path to the image you want to load. This constructor enables easy access to JPEG2000 images, simplifying the process of loading and handling image files. By providing the file path, you can quickly begin processing and manipulating JPEG2000 images in your application. |
| [Jpeg2000Image](jpeg2000image/#constructor_2)(int, int) | Create a new instance of the `Jpeg2000Image` class, specifying the width and height parameters. This constructor allows you to initialize a JPEG2000 image with specific dimensions, which is useful for scenarios where you need to create an image of a certain size programmatically. |
| [Jpeg2000Image](jpeg2000image/#constructor_1)(RasterImage, int) | Initialize a fresh `Jpeg2000Image` instance with a raster image and bits per pixel parameters. This constructor enables precise control over the quality and size of the resulting JPEG2000 image, making it ideal for scenarios where customization is crucial. |
| [Jpeg2000Image](jpeg2000image/#constructor_6)(Stream, int) | Initialize a new instance of the `Jpeg2000Image` class with a stream to load the image, along with bits per pixel parameters. This constructor offers flexibility by allowing you to specify both the image data source and the desired bits per pixel, providing finer control over the image loading process. |
| [Jpeg2000Image](jpeg2000image/#constructor_8)(string, int) | Get started easily with the `Jpeg2000Image` class by creating a new instance with both the file path and the desired bits per pixel parameter. This constructor allows for fine-tuning the image loading process, ensuring compatibility with various image formats and quality settings. With this flexibility, you can efficiently manage and manipulate JPEG2000 images according to your specific requirements. |
| [Jpeg2000Image](jpeg2000image/#constructor_4)(int, int, int) | Create a new instance of the `Jpeg2000Image` class with parameters for width, height, and bits count. This constructor allows for the creation of JPEG2000 images with specific dimensions and bit depths, providing flexibility for various imaging needs. |
| [Jpeg2000Image](jpeg2000image/#constructor_3)(int, int, Jpeg2000Options) | Instantiate a new `Jpeg2000Image` object, providing the width, height, and image options parameters. This constructor allows for the creation of JPEG2000 images with specific dimensions and additional options, offering flexibility in image generation. |

## Properties

| Name | Description |
| --- | --- |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette/) { get; set; } | Gets or sets a value indicating whether automatic adjust palette. |
| virtual [BackgroundColor](../../aspose.imaging/image/backgroundcolor/) { get; set; } | Gets or sets a value for the background color. |
| override [BitsPerPixel](../../aspose.imaging.fileformats.jpeg2000/jpeg2000image/bitsperpixel/) { get; } | This property returns the depth of the image, measured in bits per pixel (bpp). It indicates the amount of color information stored in each pixel of the image. Understanding the image depth is crucial for determining the color fidelity and quality of the image. With this information, users can gauge the level of detail and richness of colors present in the image. |
| [Bounds](../../aspose.imaging/image/bounds/) { get; } | Gets the image bounds. |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint/) { get; set; } | Gets or sets the buffer size hint which is defined max allowed size for all internal buffers. |
| [Codec](../../aspose.imaging.fileformats.jpeg2000/jpeg2000image/codec/) { get; } | This property retrieves the JPEG2000 codec associated with the image. The JPEG2000 codec is responsible for encoding and decoding the image data in the JPEG2000 format, providing efficient compression while maintaining high image quality. Accessing this codec can be useful for performing advanced image processing operations or optimizing image compression settings tailored to specific requirements. |
| [Comments](../../aspose.imaging.fileformats.jpeg2000/jpeg2000image/comments/) { get; set; } | This property allows for retrieving or updating the comments associated with the image. Comments provide additional information about the image content, such as annotations, descriptions, or metadata. Modifying these comments can be useful for organizing and categorizing images, as well as conveying important details to viewers or users. |
| [Container](../../aspose.imaging/image/container/) { get; } | Gets the [`Image`](../../aspose.imaging/image/) container. |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer/) { get; } | Gets the object's data stream. |
| [Disposed](../../aspose.imaging/disposableobject/disposed/) { get; } | Gets a value indicating whether this instance is disposed. |
| [ExifData](../../aspose.imaging/image/exifdata/) { get; set; } | Gets or sets the Exif data. |
| override [FileFormat](../../aspose.imaging.fileformats.jpeg2000/jpeg2000image/fileformat/) { get; } | Retrieve the format of the image file. This property provides information about the file format of the image. Utilize this property to determine the format of the image file programmatically, facilitating appropriate handling and processing based on the file's format. |
| virtual [HasAlpha](../../aspose.imaging/rasterimage/hasalpha/) { get; } | Gets a value indicating whether this instance has alpha. |
| virtual [HasBackgroundColor](../../aspose.imaging/image/hasbackgroundcolor/) { get; set; } | Gets or sets a value indicating whether image has background color. |
| virtual [HasTransparentColor](../../aspose.imaging/rasterimage/hastransparentcolor/) { get; set; } | Gets a value indicating whether image has transparent color. |
| override [Height](../../aspose.imaging.fileformats.jpeg2000/jpeg2000image/height/) { get; } | This property retrieves the height of the image in pixels. It serves as essential information for understanding the image's vertical dimensions, aiding in various image manipulation tasks like resizing, cropping, and rendering. Accessing this property allows users to ascertain the image's vertical size, enabling precise layout and display in applications. |
| override [HorizontalResolution](../../aspose.imaging.fileformats.jpeg2000/jpeg2000image/horizontalresolution/) { get; set; } | This property allows you to retrieve or modify the horizontal resolution of the [`RasterImage`](../../aspose.imaging/rasterimage/), measured in pixels per inch (PPI). Adjusting this resolution can impact the size and quality of the image when printed or displayed. By setting the horizontal resolution, users can optimize the image for specific output devices or applications, ensuring the best possible visual results. |
| virtual [ImageOpacity](../../aspose.imaging/rasterimage/imageopacity/) { get; } | Gets opacity of this image. |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor/) { get; set; } | Gets or sets the interrupt monitor. |
| override [IsCached](../../aspose.imaging/rastercachedimage/iscached/) { get; } | Gets a value indicating whether image data is cached currently. |
| [IsRawDataAvailable](../../aspose.imaging/rasterimage/israwdataavailable/) { get; } | Gets a value indicating whether raw data loading is available. |
| virtual [Metadata](../../aspose.imaging/image/metadata/) { get; } | Gets the image metadata. |
| [Palette](../../aspose.imaging/image/palette/) { get; set; } | Gets or sets the color palette. The color palette is not used when pixels are represented directly. |
| virtual [PremultiplyComponents](../../aspose.imaging/rasterimage/premultiplycomponents/) { get; set; } | Gets or sets a value indicating whether the image components must be premultiplied. |
| [RawCustomColorConverter](../../aspose.imaging/rasterimage/rawcustomcolorconverter/) { get; set; } | Gets or sets the custom color converter |
| override [RawDataFormat](../../aspose.imaging.fileformats.jpeg2000/jpeg2000image/rawdataformat/) { get; } | This property retrieves the raw data format of the image. It provides information about how the pixel data is stored in memory. Use this property to understand the underlying data format of the image, which can be crucial for various image processing operations like color conversion, compression, or decompression. |
| [RawDataSettings](../../aspose.imaging/rasterimage/rawdatasettings/) { get; } | Gets the current raw data settings. Note when using these settings the data loads without conversion. |
| [RawFallbackIndex](../../aspose.imaging/rasterimage/rawfallbackindex/) { get; set; } | Gets or sets the fallback index to use when palette index is out of bounds |
| [RawIndexedColorConverter](../../aspose.imaging/rasterimage/rawindexedcolorconverter/) { get; set; } | Gets or sets the indexed color converter |
| override [RawLineSize](../../aspose.imaging.fileformats.jpeg2000/jpeg2000image/rawlinesize/) { get; } | This property retrieves the size of a single line of raw image data in bytes. It indicates the amount of memory occupied by a single row of pixels in the image's raw data format. Understanding the raw line size is essential for tasks such as memory allocation, data manipulation, and image processing algorithms that operate on individual image lines. |
| [Size](../../aspose.imaging/image/size/) { get; } | Gets the image size. |
| virtual [TransparentColor](../../aspose.imaging/rasterimage/transparentcolor/) { get; set; } | Gets the image transparent color. |
| virtual [UpdateXmpData](../../aspose.imaging/rasterimage/updatexmpdata/) { get; set; } | Gets or sets a value indicating whether to update the XMP metadata. |
| override [UsePalette](../../aspose.imaging/rasterimage/usepalette/) { get; } | Gets a value indicating whether the image palette is used. |
| virtual [UseRawData](../../aspose.imaging/rasterimage/userawdata/) { get; set; } | Gets or sets a value indicating whether to use raw data loading when the raw data loading is available. |
| override [VerticalResolution](../../aspose.imaging.fileformats.jpeg2000/jpeg2000image/verticalresolution/) { get; set; } | This property provides access to the vertical resolution of the [`RasterImage`](../../aspose.imaging/rasterimage/), measured in pixels per inch (PPI). Modifying this resolution can affect the quality and size of the image when printed or displayed. By adjusting the vertical resolution, users can optimize the image for different output devices or applications, ensuring optimal visual rendering. |
| override [Width](../../aspose.imaging.fileformats.jpeg2000/jpeg2000image/width/) { get; } | This property returns the width of the image in pixels. It provides a fundamental piece of information about the image's dimensions, crucial for various image processing tasks, including resizing, cropping, and rendering. |
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
| virtual [GetDefaultOptions](../../aspose.imaging/image/getdefaultoptions/)(object[]) | Gets the default options. |
| [GetDefaultPixels](../../aspose.imaging/rasterimage/getdefaultpixels/)(Rectangle, IPartialArgb32PixelLoader) | Gets the default pixels array using partial pixel loader. |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata/)(Rectangle, RawDataSettings) | Gets the default raw data array. |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata/)(Rectangle, IPartialRawDataLoader, RawDataSettings) | Gets the default raw data array using partial pixel loader. |
| virtual [GetModifyDate](../../aspose.imaging/rasterimage/getmodifydate/)(bool) | Gets the date and time the resource image was last modified. |
| override [GetOriginalOptions](../../aspose.imaging.fileformats.jpeg2000/jpeg2000image/getoriginaloptions/)() | Retrieve the image options based on the original file settings. This method is beneficial for maintaining the bit-depth and other parameters of the original image, ensuring consistency and preserving the integrity of the image data. Accessing these options facilitates seamless handling and processing of the image while retaining its original characteristics. For example, if we load a black-white PNG image with 1 bit per pixel and then save it using the [`Save`](../../aspose.imaging/datastreamsupporter/save/) method, the output PNG image with 8-bit per pixel will be produced. To avoid it and save PNG image with 1-bit per pixel, use this method to get corresponding saving options and pass them to the [`Save`](../../aspose.imaging/image/save/) method as the second parameter. |
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

This example shows how to load a JPEG2000 image from a file and save it to PNG.

```csharp
[C#]

string dir = "c:\\temp\\";

// Load a JPEG2000 image.
using (Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image jpeg2000Image = new Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image(dir + "sample.jp2"))
{
    // Save to PNG
    jpeg2000Image.Save(dir + "sample.output.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### See Also

* class [RasterCachedImage](../../aspose.imaging/rastercachedimage/)
* namespace [Aspose.Imaging.FileFormats.Jpeg2000](../../aspose.imaging.fileformats.jpeg2000/)
* assembly [Aspose.Imaging](../../)


