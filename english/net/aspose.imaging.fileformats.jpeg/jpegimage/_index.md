---
title: Class JpegImage
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Jpeg.JpegImage class. Efficiently manipulate JPEG raster images with our API offering support for various color profiles such as RGB and CMYK customizable bits per pixel resolution and processing of EXIF JFIF and XMP metadata containers. Enjoy automated rotation based on orientation data and choose from different compression levels including lossless JPEG to achieve optimal image quality and file size balance for your projects
type: docs
weight: 6840
url: /net/aspose.imaging.fileformats.jpeg/jpegimage/
---
## JpegImage class

Efficiently manipulate JPEG raster images with our API, offering support for various color profiles such as RGB and CMYK, customizable bits per pixel resolution, and processing of EXIF, JFIF, and XMP metadata containers. Enjoy automated rotation based on orientation data and choose from different compression levels, including lossless JPEG, to achieve optimal image quality and file size balance for your projects.

```csharp
public sealed class JpegImage : RasterCachedImage, IHasJpegExifData
```

## Constructors

| Name | Description |
| --- | --- |
| [JpegImage](jpegimage/#constructor_1)(RasterImage) | Initialize a new instance of the `JpegImage` class with a raster image parameter. This constructor provides a convenient way to create JPEG images directly from raster images, streamlining the workflow for working with JPEG images in your applications. |
| [JpegImage](jpegimage/#constructor_3)(Stream) | Initialize a JPEG image object with the `JpegImage` class using a stream parameter. This constructor simplifies the process of working with JPEG images, offering a straightforward approach for integrating them into your projects effortlessly. |
| [JpegImage](jpegimage/#constructor_4)(string) | The `JpegImage` class initiates effortlessly by invoking its constructor with the specified path parameter. This constructor enables seamless creation of JPEG images, ensuring swift integration into your projects with ease. |
| [JpegImage](jpegimage/#constructor_2)(int, int) | Create a new instance of the `JpegImage` class with the specified width and height parameters. This constructor allows you to create JPEG images with custom dimensions, giving you flexibility in managing image sizes in your application. |
| [JpegImage](jpegimage/#constructor)(JpegOptions, int, int) | Initialize a new `JpegImage` object with the provided JPEG options. This constructor empowers you to tailor various settings for the JPEG image, such as compression level, quality, and additional parameters, granting precise control over the resulting image format. |

## Properties

| Name | Description |
| --- | --- |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette/) { get; set; } | Gets or sets a value indicating whether automatic adjust palette. |
| virtual [BackgroundColor](../../aspose.imaging/image/backgroundcolor/) { get; set; } | Gets or sets a value for the background color. |
| override [BitsPerPixel](../../aspose.imaging.fileformats.jpeg/jpegimage/bitsperpixel/) { get; } | Retrieve the pixel depth of the image effortlessly with this property, offering insights into the richness of color or grayscale representation. Whether it's a vibrant photograph or a monochrome illustration, this property provides crucial information about the image's visual complexity. |
| [Bounds](../../aspose.imaging/image/bounds/) { get; } | Gets the image bounds. |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint/) { get; set; } | Gets or sets the buffer size hint which is defined max allowed size for all internal buffers. |
| [CmykColorProfile](../../aspose.imaging.fileformats.jpeg/jpegimage/cmykcolorprofile/) { get; set; } | The CMYK color profile associated with CMYK and YCCK JPEG images ensures precise color conversion and fidelity. It works in conjunction with the RGBColorProfile to guarantee accurate color representation across various devices and applications. This pairing is crucial for maintaining consistency in color rendering and achieving optimal image quality. |
| [Comment](../../aspose.imaging.fileformats.jpeg/jpegimage/comment/) { get; set; } | Manage JPEG file comments with this property, allowing you to add or retrieve descriptive annotations associated with the image. Whether it's tagging images with metadata or appending additional context, this property offers flexibility in organizing and categorizing your JPEG files. |
| [Container](../../aspose.imaging/image/container/) { get; } | Gets the [`Image`](../../aspose.imaging/image/) container. |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer/) { get; } | Gets the object's data stream. |
| [DestinationCmykColorProfile](../../aspose.imaging.fileformats.jpeg/jpegimage/destinationcmykcolorprofile/) { get; set; } | The CMYK color profile is vital for the accurate color conversion of CMYK and YCCK JPEG images during the saving process. It works in tandem with the RGBColorProfile to ensure correct color representation, maintaining consistency and quality across different devices and software. This synchronization is crucial for achieving accurate and reliable color rendering in the final saved images. |
| [DestinationRgbColorProfile](../../aspose.imaging.fileformats.jpeg/jpegimage/destinationrgbcolorprofile/) { get; set; } | The RGBColorProfile is essential for the accurate color conversion of CMYK and YCCK JPEG images during the saving process. When paired with the CMYKColorProfile, it ensures that the colors are rendered correctly and maintains consistency across different devices and applications. This combination is crucial for preserving the intended color representation and achieving high-quality image output. |
| [Disposed](../../aspose.imaging/disposableobject/disposed/) { get; } | Gets a value indicating whether this instance is disposed. |
| [ExifData](../../aspose.imaging.fileformats.jpeg/jpegimage/exifdata/) { get; set; } | Manage EXIF data with this property, allowing you to add or retrieve metadata associated with the image. Whether it's extracting information about the camera settings or modifying existing metadata, this property offers flexibility in managing the EXIF data container. (2 properties) |
| override [FileFormat](../../aspose.imaging.fileformats.jpeg/jpegimage/fileformat/) { get; } | Retrieve the format of the image effortlessly with this property. It provides valuable insight into the file format, aiding in seamless integration and compatibility checks across various platforms and applications. |
| virtual [HasAlpha](../../aspose.imaging/rasterimage/hasalpha/) { get; } | Gets a value indicating whether this instance has alpha. |
| virtual [HasBackgroundColor](../../aspose.imaging/image/hasbackgroundcolor/) { get; set; } | Gets or sets a value indicating whether image has background color. |
| virtual [HasTransparentColor](../../aspose.imaging/rasterimage/hastransparentcolor/) { get; set; } | Gets a value indicating whether image has transparent color. |
| override [Height](../../aspose.imaging.fileformats.jpeg/jpegimage/height/) { get; } | Retrieve the height of the image effortlessly with this property. It provides quick access to the vertical dimension of the image, allowing you to efficiently determine its size and aspect ratio without the need for complex calculations or additional methods. |
| override [HorizontalResolution](../../aspose.imaging.fileformats.jpeg/jpegimage/horizontalresolution/) { get; set; } | This property grants you access to the horizontal resolution of the [`RasterImage`](../../aspose.imaging/rasterimage/), measured in pixels per inch. By setting or retrieving this value, you can precisely control the resolution of the image, ensuring it meets your specific requirements for quality and clarity. |
| [IgnoreEmbeddedColorProfile](../../aspose.imaging.fileformats.jpeg/jpegimage/ignoreembeddedcolorprofile/) { get; set; } | Retrieves or modifies the flag denoting whether the embedded color profile is disregarded. By setting this flag, users can specify whether the default color profile should be used instead of the embedded one. This option ensures greater control over color management, facilitating adjustments for consistency and compatibility across various platforms and applications. |
| virtual [ImageOpacity](../../aspose.imaging/rasterimage/imageopacity/) { get; } | Gets opacity of this image. |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor/) { get; set; } | Gets or sets the interrupt monitor. |
| override [IsCached](../../aspose.imaging/rastercachedimage/iscached/) { get; } | Gets a value indicating whether image data is cached currently. |
| [IsRawDataAvailable](../../aspose.imaging/rasterimage/israwdataavailable/) { get; } | Gets a value indicating whether raw data loading is available. |
| [Jfif](../../aspose.imaging.fileformats.jpeg/jpegimage/jfif/) { get; set; } | This property allows you to access or modify the JFIF (JPEG File Interchange Format) data associated with the JPEG image. JFIF is a standard format for exchanging JPEG-compressed images between computers and other devices. By getting or setting this property, you can interact with the JFIF data, which may include information such as the image's resolution, aspect ratio, and thumbnail. |
| [JpegOptions](../../aspose.imaging.fileformats.jpeg/jpegimage/jpegoptions/) { get; } | Gain access to the JPEG options employed during the creation or loading of this `JpegImage` instance with ease. This property offers valuable details about the specific settings utilized, empowering users to understand and replicate image processing workflows effectively. Whether it's compression levels, quality settings, or other parameters, this property provides essential insights for seamless image manipulation. |
| virtual [Metadata](../../aspose.imaging/image/metadata/) { get; } | Gets the image metadata. |
| [Palette](../../aspose.imaging/image/palette/) { get; set; } | Gets or sets the color palette. The color palette is not used when pixels are represented directly. |
| virtual [PremultiplyComponents](../../aspose.imaging/rasterimage/premultiplycomponents/) { get; set; } | Gets or sets a value indicating whether the image components must be premultiplied. |
| [RawCustomColorConverter](../../aspose.imaging/rasterimage/rawcustomcolorconverter/) { get; set; } | Gets or sets the custom color converter |
| override [RawDataFormat](../../aspose.imaging.fileformats.jpeg/jpegimage/rawdataformat/) { get; } | This property retrieves the raw data format of the image, which indicates how the image data is structured and encoded. Understanding the raw data format is essential for processing or manipulating the image data effectively. It provides insights into the underlying representation of the image, such as whether it's compressed, encoded in a specific color space, or stored in a particular file format. Accessing this property allows you to gain valuable information about the image's data structure, enabling you to perform various operations or optimizations tailored to its specific format. |
| [RawDataSettings](../../aspose.imaging/rasterimage/rawdatasettings/) { get; } | Gets the current raw data settings. Note when using these settings the data loads without conversion. |
| [RawFallbackIndex](../../aspose.imaging/rasterimage/rawfallbackindex/) { get; set; } | Gets or sets the fallback index to use when palette index is out of bounds |
| [RawIndexedColorConverter](../../aspose.imaging/rasterimage/rawindexedcolorconverter/) { get; set; } | Gets or sets the indexed color converter |
| virtual [RawLineSize](../../aspose.imaging/rasterimage/rawlinesize/) { get; } | Gets the raw line size in bytes. |
| [RgbColorProfile](../../aspose.imaging.fileformats.jpeg/jpegimage/rgbcolorprofile/) { get; set; } | The RGB color profile for CMYK and YCCK JPEG images ensures accurate color conversion and representation. It must be paired with the CMYKColorProfile to maintain consistency and fidelity in color rendering. This pairing is essential for applications that require precise color management and reproduction of images, ensuring that the RGB data is properly interpreted and displayed. |
| [Size](../../aspose.imaging/image/size/) { get; } | Gets the image size. |
| virtual [TransparentColor](../../aspose.imaging/rasterimage/transparentcolor/) { get; set; } | Gets the image transparent color. |
| virtual [UpdateXmpData](../../aspose.imaging/rasterimage/updatexmpdata/) { get; set; } | Gets or sets a value indicating whether to update the XMP metadata. |
| override [UsePalette](../../aspose.imaging/rasterimage/usepalette/) { get; } | Gets a value indicating whether the image palette is used. |
| virtual [UseRawData](../../aspose.imaging/rasterimage/userawdata/) { get; set; } | Gets or sets a value indicating whether to use raw data loading when the raw data loading is available. |
| override [VerticalResolution](../../aspose.imaging.fileformats.jpeg/jpegimage/verticalresolution/) { get; set; } | This property manages the vertical resolution, expressed in pixels per inch, for the associated [`RasterImage`](../../aspose.imaging/rasterimage/). Adjusting this resolution impacts the size and quality of the image when printed or displayed at a fixed physical size. By setting this property, you control how densely the image's pixels are packed vertically, affecting its overall sharpness and clarity. |
| override [Width](../../aspose.imaging.fileformats.jpeg/jpegimage/width/) { get; } | This property retrieves the width of the image, expressed in pixels. It provides essential information about the image's dimensions, enabling accurate rendering, manipulation, or display of the image data. |
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
| override [GetModifyDate](../../aspose.imaging.fileformats.jpeg/jpegimage/getmodifydate/)(bool) | Retrieves the date and time when the resource image underwent its latest modification. This method provides valuable metadata, enabling users to track and manage updates to the image file effectively. By accessing this information, users can ensure the integrity and currency of their image assets, facilitating informed decision-making regarding image usage and maintenance. |
| override [GetOriginalOptions](../../aspose.imaging.fileformats.jpeg/jpegimage/getoriginaloptions/)() | Gets the original image options of this [`Image`](../../aspose.imaging/image/) instance. |
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
| override [RemoveMetadata](../../aspose.imaging.fileformats.jpeg/jpegimage/removemetadata/)() | Removes this image instance metadata by setting this [`XmpData`](../../aspose.imaging.xmp/ihasxmpdata/xmpdata/) and [`ExifData`](../../aspose.imaging.exif/ihasexifdata/exifdata/) values to `null`. |
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
| override [SetResolution](../../aspose.imaging.fileformats.jpeg/jpegimage/setresolution/)(double, double) | Establishes the resolution for the specified [`RasterImage`](../../aspose.imaging/rasterimage/), ensuring accurate scaling and printing capabilities. This method empowers users to tailor the image resolution to suit their specific requirements, whether for digital display or physical reproduction. By setting the resolution, users can optimize image quality and ensure compatibility with various output devices and mediums, enhancing the overall visual experience and usability of the image. |
| virtual [ToBitmap](../../aspose.imaging/rasterimage/tobitmap/)() | Converts raster image to the bitmap. This method is not supported in versions from .Net7.0 and higher |
| virtual [TrySetMetadata](../../aspose.imaging/image/trysetmetadata/)(IImageMetadataFormat) | Tries to set a *metadata* instance, if this [`Image`](../../aspose.imaging/image/) instance supports and implements [`IImageMetadataFormat`](../../aspose.imaging.metadata/iimagemetadataformat/) type. |
| [WriteArgb32ScanLine](../../aspose.imaging/rasterimage/writeargb32scanline/)(int, int[]) | Writes the whole scan line to the specified scan line index. |
| [WriteScanLine](../../aspose.imaging/rasterimage/writescanline/)(int, Color[]) | Writes the whole scan line to the specified scan line index. |

## Examples

Access camera manufacturer maker notes in Jpeg image.

```csharp
[C#]

using (var image = (JpegImage)Image.Load("Sample.jpg"))
{
    foreach (var makerNote in image.ExifData.MakerNotes)
    {
        Console.WriteLine("Name = {0}, Value = {1}", makerNote.Name, makerNote.Value);
    }
}
```

The example shows how to load a JpegImage from a file.

```csharp
[C#]

string dir = "c:\\temp\\";

// Load a JPEG image from a file.
using (Aspose.Imaging.FileFormats.Jpeg.JpegImage jpegImage = new Aspose.Imaging.FileFormats.Jpeg.JpegImage(dir + "sample.jpg"))
{
    // Do some image processing.
    // Save to another JPEG file.
    jpegImage.Save(dir + "sample.output.jpg");
}
```

### See Also

* class [RasterCachedImage](../../aspose.imaging/rastercachedimage/)
* interface [IHasJpegExifData](../../aspose.imaging.exif/ihasjpegexifdata/)
* namespace [Aspose.Imaging.FileFormats.Jpeg](../../aspose.imaging.fileformats.jpeg/)
* assembly [Aspose.Imaging](../../)


