---
title: Class TgaImage
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Tga.TgaImage class. Manipulate TGA raster image files with our API tailored for the TARGA Truevision Advanced Raster Adapter format enabling seamless loading and customization. Easily update public properties such as author timestamp image ID and software version while using various bits per pixel settings alpha channel and color transparency. Additionally you can export TGA images to other popular raster formats ensuring compatibility for your projects
type: docs
weight: 7650
url: /net/aspose.imaging.fileformats.tga/tgaimage/
---
## TgaImage class

Manipulate TGA raster image files with our API, tailored for the TARGA (Truevision Advanced Raster Adapter) format, enabling seamless loading and customization. Easily update public properties such as author, timestamp, image ID, and software version, while using various bits per pixel settings, alpha channel and color transparency. Additionally, you can export TGA images to other popular raster formats, ensuring compatibility for your projects.

```csharp
public class TgaImage : RasterCachedImage
```

## Constructors

| Name | Description |
| --- | --- |
| [TgaImage](tgaimage/#constructor)(RasterImage) | Create a new instance of the `TgaImage` class by providing a raster image object. This constructor facilitates the direct integration of existing raster images into the TGA image format, streamlining the conversion process for enhanced compatibility within your software systems. |
| [TgaImage](tgaimage/#constructor_1)(Stream) | Initialize a new instance of the `TgaImage` class using a stream to load the image. This constructor allows for seamless integration of image data from streams, facilitating efficient handling and processing of TGA images within your software applications. |
| [TgaImage](tgaimage/#constructor_2)(string) | Initializes a new `TgaImage` object using the provided file path for loading the image content. This constructor efficiently initializes the image instance, allowing seamless access to TGA image files, simplifying integration into your application workflow. |

## Properties

| Name | Description |
| --- | --- |
| [AuthorComments](../../aspose.imaging.fileformats.tga/tgaimage/authorcomments/) { get; set; } | Retrieves or sets the comments provided by the author of the image. These comments often contain valuable information, such as descriptions, annotations, or additional context about the image. By accessing or modifying the Author Comments property, developers can enhance the metadata associated with the image, providing users with valuable insights and context regarding its content or creation. This is an ASCII field consisting of 324 bytes which are organized as four lines of 80 characters, each followed by a null terminator. |
| [AuthorName](../../aspose.imaging.fileformats.tga/tgaimage/authorname/) { get; set; } | Retrieves or sets the name of the author associated with the image. This property allows developers to access or modify the author's name metadata, providing valuable information about the creator of the image. By utilizing the Author Name property, users can easily identify the individual responsible for creating or contributing to the image, enhancing its overall metadata and providing valuable context for viewers. This field is a total of 40 ASCII characters for the name. If the field is used, it should contain the name of the person who created the image (author). |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette/) { get; set; } | Gets or sets a value indicating whether automatic adjust palette. |
| override [BackgroundColor](../../aspose.imaging.fileformats.tga/tgaimage/backgroundcolor/) { get; set; } | Retrieves or sets the background color of the image. This property allows you to specify the color used for the image background, ensuring consistency and enhancing visual presentation. It is particularly useful for scenarios where the image is displayed on a background with a different color or when rendering the image onto another canvas. |
| override [BitsPerPixel](../../aspose.imaging.fileformats.tga/tgaimage/bitsperpixel/) { get; } | Retrieve the bits per pixel value, providing essential information about the image's color depth. This property serves as a crucial metric for understanding the level of detail and color richness present in the image, aiding developers in optimizing processing algorithms and resource allocation for efficient image manipulation and rendering tasks. |
| [Bounds](../../aspose.imaging/image/bounds/) { get; } | Gets the image bounds. |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint/) { get; set; } | Gets or sets the buffer size hint which is defined max allowed size for all internal buffers. |
| [BytesPerPixel](../../aspose.imaging.fileformats.tga/tgaimage/bytesperpixel/) { get; } | Obtain the bytes per pixel value, which denotes the amount of memory occupied by each pixel in the image. This property serves as a crucial metric for memory management and optimization, aiding developers in efficiently allocating resources and processing image data |
| [Container](../../aspose.imaging/image/container/) { get; } | Gets the [`Image`](../../aspose.imaging/image/) container. |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer/) { get; } | Gets the object's data stream. |
| [DateTimeStamp](../../aspose.imaging.fileformats.tga/tgaimage/datetimestamp/) { get; set; } | Gets or sets Date/Time Stamp. This field defines the value for the date and time that the image was saved. Even though operating systems typically time- and date-stamp files, this feature is provided because the operating system may change the time and date stamp if the file is copied. By using this area, you are guaranteed an unmodified region for date and time recording. |
| [Disposed](../../aspose.imaging/disposableobject/disposed/) { get; } | Gets a value indicating whether this instance is disposed. |
| [ExifData](../../aspose.imaging/image/exifdata/) { get; set; } | Gets or sets the Exif data. |
| override [FileFormat](../../aspose.imaging.fileformats.tga/tgaimage/fileformat/) { get; } | Get crucial information about the file format of the image represented by this instance of `TgaImage`. Understanding the file format is essential for compatibility checks and ensuring seamless integration within software systems, enabling efficient processing and manipulation of images. |
| [GammaValueDenominator](../../aspose.imaging.fileformats.tga/tgaimage/gammavaluedenominator/) { get; } | Retrieves the denominator part of the gamma value, an integral factor in determining color representation within images. For images lacking gamma correction, this value should be 1.0, ensuring accurate color rendering. Appreciating and leveraging this parameter is fundamental for upholding color fidelity and achieving precise image visualization. |
| [GammaValueNumerator](../../aspose.imaging.fileformats.tga/tgaimage/gammavaluenumerator/) { get; } | Gets the numerator part of the gamma value, which is essential for accurate color representation in images. In images without gamma correction, this value should be 1.0. Understanding and utilizing this value is crucial for maintaining color fidelity and ensuring accurate image rendering. |
| override [HasAlpha](../../aspose.imaging.fileformats.tga/tgaimage/hasalpha/) { get; } | Retrieve a boolean value indicating whether the `TgaImage` includes an alpha channel, facilitating transparency effects. This property provides essential information for handling image composition and rendering, assisting developers in implementing diverse visual effects and compositing operations. |
| override [HasBackgroundColor](../../aspose.imaging.fileformats.tga/tgaimage/hasbackgroundcolor/) { get; set; } | Retrieves or sets a value indicating whether the image contains a background color. This property is useful for determining whether the image includes a distinct background color separate from the foreground content. It enables you to customize image processing or rendering based on the presence or absence of a background color. |
| [HasColorMap](../../aspose.imaging.fileformats.tga/tgaimage/hascolormap/) { get; } | Retrieve whether this `TgaImage` instance contains a color map. Understanding the presence of a color map is crucial for accurate interpretation and manipulation of the image's color data. |
| override [HasTransparentColor](../../aspose.imaging.fileformats.tga/tgaimage/hastransparentcolor/) { get; set; } | Retrieves or sets a boolean value indicating whether the image contains a transparent color. This property is essential for identifying whether the image supports transparency, helping you to implement appropriate handling of transparency-related operations such as blending, compositing, or masking. |
| override [Height](../../aspose.imaging.fileformats.tga/tgaimage/height/) { get; } | Obtain the height of the image encapsulated by this `TgaImage` instance. This property furnishes developers with critical details concerning the image's vertical dimensions, enabling seamless integration and manipulation of images within their software solutions. |
| virtual [HorizontalResolution](../../aspose.imaging/rasterimage/horizontalresolution/) { get; set; } | Gets or sets the horizontal resolution, in pixels per inch, of this [`RasterImage`](../../aspose.imaging/rasterimage/). |
| [ImageId](../../aspose.imaging.fileformats.tga/tgaimage/imageid/) { get; set; } | Gets or sets the unique identifier associated with the image. This ID serves as a reference point for identifying and distinguishing the image from others within a system or application. By setting or retrieving the Image ID, you can manage and track images effectively, facilitating organized image management and retrieval processes. |
| virtual [ImageOpacity](../../aspose.imaging/rasterimage/imageopacity/) { get; } | Gets opacity of this image. |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor/) { get; set; } | Gets or sets the interrupt monitor. |
| override [IsCached](../../aspose.imaging/rastercachedimage/iscached/) { get; } | Gets a value indicating whether image data is cached currently. |
| [IsGrayScale](../../aspose.imaging.fileformats.tga/tgaimage/isgrayscale/) { get; } | Obtain a boolean value indicating whether the `TgaImage` represents a gray-scale image. This property is crucial for distinguishing between color and gray-scale images, aiding developers in applying appropriate processing and rendering techniques based on the image's color characteristics. |
| [IsRawDataAvailable](../../aspose.imaging/rasterimage/israwdataavailable/) { get; } | Gets a value indicating whether raw data loading is available. |
| [JobNameOrId](../../aspose.imaging.fileformats.tga/tgaimage/jobnameorid/) { get; set; } | Retrieves or sets the job name or ID associated with the image. This property enables you to access or modify metadata related to the specific job or project associated with the image. By utilizing the Job Name/ID property, users can easily identify the project or task to which the image pertains, facilitating organization and management of image assets within larger workflows or projects. |
| [JobTime](../../aspose.imaging.fileformats.tga/tgaimage/jobtime/) { get; set; } | Retrieves or sets the timestamp indicating the job time associated with the image. This property allows developers to access or modify the time metadata related to the specific job or project associated with the image. |
| virtual [Metadata](../../aspose.imaging/image/metadata/) { get; } | Gets the image metadata. |
| [Palette](../../aspose.imaging/image/palette/) { get; set; } | Gets or sets the color palette. The color palette is not used when pixels are represented directly. |
| [PixelAspectRatioDenominator](../../aspose.imaging.fileformats.tga/tgaimage/pixelaspectratiodenominator/) { get; } | Retrieves the denominator part of the Pixel Aspect Ratio, a crucial factor in determining the visual aspect of pixels within the image. This value is essential for preserving accurate pixel representation and aspect ratios throughout various image rendering and processing operations, ensuring high-quality visual output. |
| [PixelAspectRatioNumerator](../../aspose.imaging.fileformats.tga/tgaimage/pixelaspectrationumerator/) { get; } | Retrieves the numerator component of the Pixel Aspect Ratio, which influences the visual aspect of pixels within the image. Understanding and manipulating this value is essential for achieving accurate pixel representation and aspect ratios in image rendering and processing. |
| virtual [PremultiplyComponents](../../aspose.imaging/rasterimage/premultiplycomponents/) { get; set; } | Gets or sets a value indicating whether the image components must be premultiplied. |
| [RawCustomColorConverter](../../aspose.imaging/rasterimage/rawcustomcolorconverter/) { get; set; } | Gets or sets the custom color converter |
| virtual [RawDataFormat](../../aspose.imaging/rasterimage/rawdataformat/) { get; } | Gets the raw data format. |
| [RawDataSettings](../../aspose.imaging/rasterimage/rawdatasettings/) { get; } | Gets the current raw data settings. Note when using these settings the data loads without conversion. |
| [RawFallbackIndex](../../aspose.imaging/rasterimage/rawfallbackindex/) { get; set; } | Gets or sets the fallback index to use when palette index is out of bounds |
| [RawIndexedColorConverter](../../aspose.imaging/rasterimage/rawindexedcolorconverter/) { get; set; } | Gets or sets the indexed color converter |
| virtual [RawLineSize](../../aspose.imaging/rasterimage/rawlinesize/) { get; } | Gets the raw line size in bytes. |
| [Size](../../aspose.imaging/image/size/) { get; } | Gets the image size. |
| [SoftwareId](../../aspose.imaging.fileformats.tga/tgaimage/softwareid/) { get; set; } | Manages the software identification (ID) associated with the image, allowing for up to 40 ASCII characters. This property serves as a means to uniquely identify the software utilized in creating or processing the image, providing valuable metadata for organizational and informational purposes. |
| [SoftwareVersion](../../aspose.imaging.fileformats.tga/tgaimage/softwareversion/) { get; set; } | Retrieves or sets the software version associated with the image. The accepted length for the version string is typically 3 to 4 characters. This property is useful for tracking the software used to create or manipulate the image and can provide valuable context for image processing and compatibility checks. |
| [SoftwareVersionLetter](../../aspose.imaging.fileformats.tga/tgaimage/softwareversionletter/) { get; set; } | Retrieves or sets the letter component of the software version associated with the image. This property represents an additional detail within the software version string and can be useful for finer version differentiation. |
| [SoftwareVersionNumber](../../aspose.imaging.fileformats.tga/tgaimage/softwareversionnumber/) { get; set; } | Retrieves or sets the numeric component of the software version associated with the image. This property represents the numerical part of the software version string, providing important information about the version of the software used to create or modify the image. |
| override [TransparentColor](../../aspose.imaging.fileformats.tga/tgaimage/transparentcolor/) { get; set; } | Retrieves or sets the key color associated with the image. This property allows you to access or modify the color designated as the key color for specific image processing tasks or effects. Utilizing the Key Color property enables users to apply color-based operations such as chroma keying or color replacement, enhancing image manipulation capabilities and creative possibilities. |
| virtual [UpdateXmpData](../../aspose.imaging/rasterimage/updatexmpdata/) { get; set; } | Gets or sets a value indicating whether to update the XMP metadata. |
| override [UsePalette](../../aspose.imaging/rasterimage/usepalette/) { get; } | Gets a value indicating whether the image palette is used. |
| virtual [UseRawData](../../aspose.imaging/rasterimage/userawdata/) { get; set; } | Gets or sets a value indicating whether to use raw data loading when the raw data loading is available. |
| virtual [VerticalResolution](../../aspose.imaging/rasterimage/verticalresolution/) { get; set; } | Gets or sets the vertical resolution, in pixels per inch, of this [`RasterImage`](../../aspose.imaging/rasterimage/). |
| override [Width](../../aspose.imaging.fileformats.tga/tgaimage/width/) { get; } | Retrieve the width of the image represented by this `TgaImage` instance. This property provides developers with essential information about the image dimensions, facilitating various image manipulation and processing tasks within their software applications. |
| [XmpData](../../aspose.imaging/image/xmpdata/) { get; set; } | Gets or sets the Xmp data. |
| [XOrigin](../../aspose.imaging.fileformats.tga/tgaimage/xorigin/) { get; set; } | Gets or sets absolute horizontal coordinate for the lower left corner of the image as it is positioned on a display device having an origin at the lower left of the screen(e.g., the TARGA series). |
| [YOrigin](../../aspose.imaging.fileformats.tga/tgaimage/yorigin/) { get; set; } | Gets or sets absolute vertical coordinate for the lower left corner of the image as it is positioned on a display device having an origin at the lower left of the screen(e.g., the TARGA series). |

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
| [Clone](../../aspose.imaging.fileformats.tga/tgaimage/clone/#clone)() | Produces a duplicate of the current instance, generating a new object that clones all attributes and properties of the original. This method facilitates the creation of identical copies, ensuring data integrity and preserving the state of the current instance without affecting the original object. |
| [Clone](../../aspose.imaging.fileformats.tga/tgaimage/clone/#clone_1)(TgaImage) | Replicate the properties of another `TgaImage` object, creating a new instance with identical attributes. This operation ensures the preservation of data integrity and facilitates the duplication of image properties without altering the source object. |
| override [Crop](../../aspose.imaging.fileformats.tga/tgaimage/crop/#crop)(Rectangle) | Crop the image to a specified region. This method allows you to define a rectangular area within the image to retain, discarding the rest. This operation is useful for focusing on specific content within the image or removing unwanted portions. |
| override [Crop](../../aspose.imaging.fileformats.tga/tgaimage/crop/#crop_1)(int, int, int, int) | Crop the image by specifying shifts for the left, right, top, and bottom boundaries. This method allows you to trim the image by moving its boundaries independently along the horizontal and vertical axes. By adjusting these shifts, you can precisely control which portions of the image to retain, effectively cropping it to the desired dimensions. |
| [Dispose](../../aspose.imaging/disposableobject/dispose/)() | Disposes the current instance. |
| [Dither](../../aspose.imaging/rasterimage/dither/)(DitheringMethod, int) | Performs dithering on the current image. |
| override [Dither](../../aspose.imaging/rastercachedimage/dither/)(DitheringMethod, int, IColorPalette) | Performs dithering on the current image. |
| override [EmbedDigitalSignature](../../aspose.imaging/rastercachedimage/embeddigitalsignature/)(string) | Embed digital sign based on provided password into the image using steganography. |
| override [Equals](../../aspose.imaging.fileformats.tga/tgaimage/equals/#equals_1)(object) | The method performs an equality comparison between the current `TgaImage` instance and another object provided as a parameter. Specifically, it evaluates whether the properties of the current image match those of the second object, assisting in determining their equivalence for comparison purposes within image processing workflows. |
| [Equals](../../aspose.imaging.fileformats.tga/tgaimage/equals/#equals)(TgaImage) | In an equality comparison, the method evaluates whether the current `TgaImage` instance is equal to the second image provided as a parameter. This operation facilitates determining if two TGA images are identical, aiding in image processing and comparison tasks. |
| virtual [Filter](../../aspose.imaging/rasterimage/filter/)(Rectangle, FilterOptionsBase) | Filters the specified rectangle. |
| [GetArgb32Pixel](../../aspose.imaging/rasterimage/getargb32pixel/)(int, int) | Gets an image 32-bit ARGB pixel. |
| [GetDefaultArgb32Pixels](../../aspose.imaging/rasterimage/getdefaultargb32pixels/)(Rectangle) | Gets the default 32-bit ARGB pixels array. |
| virtual [GetDefaultOptions](../../aspose.imaging/image/getdefaultoptions/)(object[]) | Gets the default options. |
| [GetDefaultPixels](../../aspose.imaging/rasterimage/getdefaultpixels/)(Rectangle, IPartialArgb32PixelLoader) | Gets the default pixels array using partial pixel loader. |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata/)(Rectangle, RawDataSettings) | Gets the default raw data array. |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata/)(Rectangle, IPartialRawDataLoader, RawDataSettings) | Gets the default raw data array using partial pixel loader. |
| override [GetHashCode](../../aspose.imaging.fileformats.tga/tgaimage/gethashcode/)() | Retrieve the hash code of the current instance. However, it's important to note that this hash code may not be suitable for use as a key, particularly because instances of the TgaImage class are not immutable. |
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
| override [Resize](../../aspose.imaging.fileformats.tga/tgaimage/resize/#resize_1)(int, int, ImageResizeSettings) | Resize the image while applying specific settings to maintain the desired dimensions and aspect ratio. By customizing image settings, you can effectively resize the image while ensuring optimal visual quality and compatibility with different display devices or applications. |
| override [Resize](../../aspose.imaging.fileformats.tga/tgaimage/resize/#resize_2)(int, int, ResizeType) | Adjusts the size of the image using a specified resize type, which determines how the resizing operation is performed. This method provides flexibility in resizing images according to different algorithms or techniques. By choosing the appropriate resize type, you can achieve the desired balance between image quality and computational efficiency based on specific requirements or preferences. |
| [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally/)(int) | Resizes the height proportionally. The default NearestNeighbourResample is used. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally/)(int, ImageResizeSettings) | Resizes the height proportionally. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally/)(int, ResizeType) | Resizes the height proportionally. |
| [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally/)(int) | Resizes the width proportionally. The default NearestNeighbourResample is used. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally/)(int, ImageResizeSettings) | Resizes the width proportionally. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally/)(int, ResizeType) | Resizes the width proportionally. |
| override [Rotate](../../aspose.imaging/rasterimage/rotate/)(float) | Rotate image around the center. |
| override [Rotate](../../aspose.imaging.fileformats.tga/tgaimage/rotate/#rotate_1)(float, bool, Color) | Rotates the image around its center by a specified angle while maintaining resize proportionality and preserving the background color. This method allows for precise image manipulation, ensuring that the rotation maintains visual balance and consistency with the specified background color. It's ideal for tasks where accurate rotation around the center is necessary, such as orientation correction or artistic adjustments. |
| override [RotateFlip](../../aspose.imaging.fileformats.tga/tgaimage/rotateflip/)(RotateFlipType) | The "RotateFlip" method enables rotating and flipping operations on the image. It offers versatile functionality for manipulating image orientation, allowing users to perform rotations and flips according to their requirements, facilitating efficient image processing tasks within software applications. |
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
| [operator ==](../../aspose.imaging.fileformats.tga/tgaimage/op_equality/) | Performs an equality comparison between two TGA images, considering both the first and second images involved in the comparison process. This method facilitates straightforward assessment of image equality, ensuring accurate analysis and decision-making within image processing workflows. |
| [operator !=](../../aspose.imaging.fileformats.tga/tgaimage/op_inequality/) | Conducts a non-equality comparison between two TGA images, evaluating both the first and second images involved in the comparison. This method aids in identifying discrepancies or differences between images, enabling precise analysis and decision-making in image processing tasks. |

## Examples

Saving of the JPG image as a TGA image.

```csharp
[C#]

using (RasterImage image = (JpegImage)Image.Load("test.jpg"))
{
    image.Save("test.tga"", new TgaOptions());
}
```

Loading of the PNG image, conversion of it to the TgaImage and saving as a TGA image.

```csharp
[C#]

using (RasterImage image = (RasterImage)Image.Load("test.png"))
{
    using (TgaImage tgaImage = new TgaImage(image))
    {
        tgaImage.Save("test.tga");
    }
}
```

Updating public properties of the loaded TGA image.

```csharp
[C#]

using (TgaImage image = (TgaImage)Image.Load("test.tga"))
{
    image.DateTimeStamp = testTime;
    image.AuthorName = "John Smith";
    image.AuthorComments = "Comment";
    image.ImageId = "ImageId";
    image.JobNameOrId = "Important Job";
    image.JobTime = TimeSpan.FromDays(10);
    image.TransparentColor = Color.FromArgb(123);
    image.SoftwareId = "SoftwareId";
    image.SoftwareVersion = "abc1";
    image.SoftwareVersionLetter = 'a';
    image.SoftwareVersionNumber = 2;
    image.XOrigin = 1000;
    image.YOrigin = 1000;

    image.Save("test.tga")
}
```

Getting values of the public properties of the loaded TGA image.

```csharp
[C#]

using (TgaImage image = (TgaImage)Image.Load("test.tga"))
{
    dateTimeStamp = image.DateTimeStamp;
    authorName = image.AuthorName;
    authorComments = image.AuthorComments;
    imageId = image.ImageId;
    jobNameOrId = image.JobNameOrId;
    jobTime = image.JobTime;
    keyColor = image.TransparentColor;
    softwareId = image.SoftwareId;
    softwareVersion = image.SoftwareVersion;
    softwareVersionLetter = image.SoftwareVersionLetter;
    softwareVersionNumber = image.SoftwareVersionNumber;
    xOrigin = image.XOrigin;
    yOrigin = image.YOrigin;
    gammaValueDenominator = image.GammaValueDenominator;
    gammaValueNumerator = image.GammaValueNumerator;
    hasAlphaChannel = image.HasAlpha;
    hasColorMap = image.HasColorMap;
    height = image.Height;
    isGrayScale = image.IsGrayScale;
    pixelAspectRatioDenominator = image.PixelAspectRatioDenominator;
    pixelAspectRatioNumerator = image.PixelAspectRatioNumerator;
    size = image.Size;
    width = image.Width;
}
```

### See Also

* class [RasterCachedImage](../../aspose.imaging/rastercachedimage/)
* namespace [Aspose.Imaging.FileFormats.Tga](../../aspose.imaging.fileformats.tga/)
* assembly [Aspose.Imaging](../../)


