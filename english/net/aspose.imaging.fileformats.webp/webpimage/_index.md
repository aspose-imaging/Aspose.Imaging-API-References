---
title: Class WebPImage
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Webp.WebPImage class. Manipulate WebP raster images with our API using its modern features for both lossless and lossy compression ensuring optimal image quality with reduced file sizes. Seamlessly handle extended file formats animations and alpha channels while easily updating dimensions resizing proportionally cropping rotating applying filters adjusting image parameters and converting to other image formats for versatile web image optimization
type: docs
weight: 8260
url: /net/aspose.imaging.fileformats.webp/webpimage/
---
## WebPImage class

Manipulate WebP raster images with our API, using its modern features for both lossless and lossy compression, ensuring optimal image quality with reduced file sizes. Seamlessly handle extended file formats, animations, and alpha channels, while easily updating dimensions, resizing proportionally, cropping, rotating, applying filters, adjusting image parameters, and converting to other image formats for versatile web image optimization.

```csharp
public sealed class WebPImage : RasterCachedMultipageImage, IMultipageImageExt
```

## Constructors

| Name | Description |
| --- | --- |
| [WebPImage](webpimage/#constructor)(RasterImage) | Instantiate a new instance of the `WebPImage` class, initialized from a provided rasterImage object. This constructor allows for seamless conversion of raster images to WebP format, enabling efficient handling and manipulation of image data within your application. |
| [WebPImage](webpimage/#constructor_4)(Stream) | Instantiate a new instance of the `WebPImage` class, initialized from a provided stream source. Utilize this constructor to seamlessly create WebP image objects directly from streams, enabling efficient handling and manipulation of WebP image data within your application. |
| [WebPImage](webpimage/#constructor_6)(string) | Instantiate a fresh instance of the `WebPImage` class, initialized from a provided file source. Utilize this constructor to seamlessly create WebP image objects directly from files, streamlining the process of loading and manipulating WebP image data within your application. |
| [WebPImage](webpimage/#constructor_1)(RasterImage, LoadOptions) | Create a new instance of the `WebPImage` class using a rasterImage object and specified load options, enabling flexible handling of image data. Utilize this constructor to seamlessly initialize WebP image objects from raster images while customizing loading parameters according to your application's requirements. |
| [WebPImage](webpimage/#constructor_5)(Stream, LoadOptions) | Create a new instance of the `WebPImage` class using a stream and specified load options, facilitating versatile handling of WebP image data. Incorporate this constructor to seamlessly initialize WebP image objects from streams while customizing loading parameters as needed within your application. |
| [WebPImage](webpimage/#constructor_7)(string, LoadOptions) | Create a new instance of the `WebPImage` class using a file and specified load options, facilitating flexible handling of WebP image data. Utilize this constructor to seamlessly initialize WebP image objects from files while customizing loading parameters according to your application's requirements. |
| [WebPImage](webpimage/#constructor_2)(int, int, WebPOptions) | Instantiate a new instance of the `WebPImage` class with an empty image of specified width and height dimensions. This constructor allows for the creation of blank WebP images, providing a foundation for subsequent image manipulation and content generation within your application. |
| [WebPImage](webpimage/#constructor_3)(int, int, WebPOptions, LoadOptions) | Create a new instance of the `WebPImage` class with an empty image and specified load options. This constructor allows for the initialization of WebP images with customizable loading parameters, providing flexibility in image creation and manipulation within your application. |

## Properties

| Name | Description |
| --- | --- |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette/) { get; set; } | Gets or sets a value indicating whether automatic adjust palette. |
| override [BackgroundColor](../../aspose.imaging/rastercachedmultipageimage/backgroundcolor/) { get; set; } | Gets or sets a value for the background color. |
| override [BitsPerPixel](../../aspose.imaging/rastercachedmultipageimage/bitsperpixel/) { get; } | Gets the image bits per pixel count. |
| [Bounds](../../aspose.imaging/image/bounds/) { get; } | Gets the image bounds. |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint/) { get; set; } | Gets or sets the buffer size hint which is defined max allowed size for all internal buffers. |
| [Container](../../aspose.imaging/image/container/) { get; } | Gets the [`Image`](../../aspose.imaging/image/) container. |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer/) { get; } | Gets the object's data stream. |
| [Disposed](../../aspose.imaging/disposableobject/disposed/) { get; } | Gets a value indicating whether this instance is disposed. |
| [ExifData](../../aspose.imaging/image/exifdata/) { get; set; } | Gets or sets the Exif data. |
| override [FileFormat](../../aspose.imaging.fileformats.webp/webpimage/fileformat/) { get; } | Access the file format value associated with the image, providing information about the format in which the image is stored. Utilize this property to determine the file format of the image, facilitating compatibility checks and format-specific processing within your application. |
| override [HasAlpha](../../aspose.imaging.fileformats.webp/webpimage/hasalpha/) { get; } | Retrieve whether the image contains an alpha channel, indicating the presence of transparency information. Utilize this property to determine whether the image includes transparency, enabling appropriate handling and processing of alpha-related operations within your application. |
| virtual [HasBackgroundColor](../../aspose.imaging/image/hasbackgroundcolor/) { get; set; } | Gets or sets a value indicating whether image has background color. |
| override [HasTransparentColor](../../aspose.imaging/rastercachedmultipageimage/hastransparentcolor/) { get; } | Gets a value indicating whether image has transparent color. |
| override [Height](../../aspose.imaging/rastercachedmultipageimage/height/) { get; } | Gets the image height. |
| virtual [HorizontalResolution](../../aspose.imaging/rasterimage/horizontalresolution/) { get; set; } | Gets or sets the horizontal resolution, in pixels per inch, of this [`RasterImage`](../../aspose.imaging/rasterimage/). |
| override [ImageOpacity](../../aspose.imaging/rastercachedmultipageimage/imageopacity/) { get; } | Gets opacity of this image. |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor/) { get; set; } | Gets or sets the interrupt monitor. |
| override [IsCached](../../aspose.imaging/rastercachedmultipageimage/iscached/) { get; } | Gets a value indicating whether image data is cached currently. |
| [IsRawDataAvailable](../../aspose.imaging/rasterimage/israwdataavailable/) { get; } | Gets a value indicating whether raw data loading is available. |
| override [Metadata](../../aspose.imaging/rastercachedmultipageimage/metadata/) { get; } | Gets or sets XMP data from frame. |
| [Options](../../aspose.imaging.fileformats.webp/webpimage/options/) { get; } | Retrieve or modify the options associated with the specified property, enabling fine-tuned customization of behavior and settings. Utilize this property to seamlessly access and manipulate configurable parameters, facilitating versatile control and optimization within your application's functionality. |
| override [PageCount](../../aspose.imaging.fileformats.webp/webpimage/pagecount/) { get; } | Retrieve the total count of pages within the specified document, facilitating efficient navigation and management of multi-page content. Incorporate this functionality to enhance user experience, enabling seamless access to comprehensive document structures. |
| virtual [PageExportingAction](../../aspose.imaging/rastercachedmultipageimage/pageexportingaction/) { get; set; } | Gets or sets the page exporting action. Please note that setting this method will automatically release page resources after it is executed. It will be executed just before each page is saved. |
| override [Pages](../../aspose.imaging.fileformats.webp/webpimage/pages/) { get; } | Access the WebP blocks within the image, allowing detailed examination or manipulation of the underlying block structure. Utilize this property to analyze or modify individual blocks within the WebP image data, facilitating advanced image processing techniques within your application. |
| [Palette](../../aspose.imaging/image/palette/) { get; set; } | Gets or sets the color palette. The color palette is not used when pixels are represented directly. |
| virtual [PremultiplyComponents](../../aspose.imaging/rasterimage/premultiplycomponents/) { get; set; } | Gets or sets a value indicating whether the image components must be premultiplied. |
| [RawCustomColorConverter](../../aspose.imaging/rasterimage/rawcustomcolorconverter/) { get; set; } | Gets or sets the custom color converter |
| virtual [RawDataFormat](../../aspose.imaging/rasterimage/rawdataformat/) { get; } | Gets the raw data format. |
| [RawDataSettings](../../aspose.imaging/rasterimage/rawdatasettings/) { get; } | Gets the current raw data settings. Note when using these settings the data loads without conversion. |
| [RawFallbackIndex](../../aspose.imaging/rasterimage/rawfallbackindex/) { get; set; } | Gets or sets the fallback index to use when palette index is out of bounds |
| [RawIndexedColorConverter](../../aspose.imaging/rasterimage/rawindexedcolorconverter/) { get; set; } | Gets or sets the indexed color converter |
| virtual [RawLineSize](../../aspose.imaging/rasterimage/rawlinesize/) { get; } | Gets the raw line size in bytes. |
| [Size](../../aspose.imaging/image/size/) { get; } | Gets the image size. |
| virtual [TransparentColor](../../aspose.imaging/rasterimage/transparentcolor/) { get; set; } | Gets the image transparent color. |
| virtual [UpdateXmpData](../../aspose.imaging/rasterimage/updatexmpdata/) { get; set; } | Gets or sets a value indicating whether to update the XMP metadata. |
| override [UsePalette](../../aspose.imaging/rasterimage/usepalette/) { get; } | Gets a value indicating whether the image palette is used. |
| virtual [UseRawData](../../aspose.imaging/rasterimage/userawdata/) { get; set; } | Gets or sets a value indicating whether to use raw data loading when the raw data loading is available. |
| virtual [VerticalResolution](../../aspose.imaging/rasterimage/verticalresolution/) { get; set; } | Gets or sets the vertical resolution, in pixels per inch, of this [`RasterImage`](../../aspose.imaging/rasterimage/). |
| override [Width](../../aspose.imaging/rastercachedmultipageimage/width/) { get; } | Gets the image width. |
| [XmpData](../../aspose.imaging/image/xmpdata/) { get; set; } | Gets or sets the Xmp data. |

## Methods

| Name | Description |
| --- | --- |
| [AddBlock](../../aspose.imaging.fileformats.webp/webpimage/addblock/)(IFrame) | Incorporate a new WebP block into the image, enriching its content and facilitating advanced image manipulation. Integrate this method to dynamically enhance the structure and complexity of the WebP image data within your application, enabling precise control and optimization of image rendering. |
| [AddPage](../../aspose.imaging.fileformats.webp/webpimage/addpage/)(RasterImage) | Append a new page to the image, expanding its content and accommodating additional visual elements. Integrate this method to facilitate dynamic page management within your application, enabling seamless creation and augmentation of multi-page documents or images. |
| override [AdjustBrightness](../../aspose.imaging.fileformats.webp/webpimage/adjustbrightness/)(int) | Implement *brightness* adjustment for the image, allowing the modification of overall luminance levels. Incorporate this method into your image processing workflow to enhance visibility and improve the visual quality of images within your application. |
| override [AdjustContrast](../../aspose.imaging.fileformats.webp/webpimage/adjustcontrast/)(float) | Enhance the contrast of the [`Image`](../../aspose.imaging/image/), amplifying the differences between light and dark areas. Integrate this method into your image processing workflow to improve visual clarity and overall image quality within your application. |
| override [AdjustGamma](../../aspose.imaging.fileformats.webp/webpimage/adjustgamma/#adjustgamma)(float) | Apply gamma correction to the image, adjusting pixel intensities to achieve desired brightness and color balance. Incorporate this method into your image processing workflow to enhance visual quality and improve the accuracy of subsequent analysis or display tasks within your application. |
| override [AdjustGamma](../../aspose.imaging.fileformats.webp/webpimage/adjustgamma/#adjustgamma_1)(float, float, float) | Perform gamma correction on the image using individual coefficients for the red, green, and blue channels, allowing for fine-tuned adjustments of color balance and contrast. Integrate this method into your image processing pipeline to achieve precise control over color rendering and enhance visual fidelity within your application. |
| override [AnalyzePercentageDigitalSignature](../../aspose.imaging/rastercachedmultipageimage/analyzepercentagedigitalsignature/)(string) | Calculates the percentage similarity between the extracted data and the original password. |
| override [AutoBrightnessContrast](../../aspose.imaging/rastercachedimage/autobrightnesscontrast/)() | Performs automatic adaptive brightness and contrast normalization for the entire image. |
| [AutoRotate](../../aspose.imaging/rasterimage/autorotate/)() | Automatically rotates the image based on orientation data extracted from Exif metadata. This method ensures that images are displayed in the correct orientation, enhancing user experience and eliminating the need for manual adjustments. By analyzing Exif information, the image is rotated accordingly, providing a seamless viewing experience across different platforms and devices. This automated rotation process simplifies image handling and improves overall usability, especially when dealing with large batches of images with varying orientations. |
| override [BinarizeBradley](../../aspose.imaging/rastercachedmultipageimage/binarizebradley/)(double) | Binarization of an image using Bradley's adaptive thresholding algorithm using the integral image thresholding |
| override [BinarizeBradley](../../aspose.imaging.fileformats.webp/webpimage/binarizebradley/#binarizebradley_1)(double, int) | Apply binarization to the image using Bradley's adaptive thresholding algorithm with integral image thresholding. This method dynamically computes local thresholds based on the image's neighborhood, enhancing adaptability to varying lighting conditions and ensuring robust segmentation for subsequent processing tasks within your application. |
| override [BinarizeFixed](../../aspose.imaging.fileformats.webp/webpimage/binarizefixed/)(byte) | Perform binarization on the image using a predefined threshold value, converting it into a binary image where pixels are classified as foreground or background based on their intensity relative to the threshold. Integrate this method into your image processing workflow to facilitate segmentation and feature extraction tasks, enhancing the accuracy and efficiency of subsequent analysis within your application. |
| override [BinarizeOtsu](../../aspose.imaging.fileformats.webp/webpimage/binarizeotsu/)() | Perform binarization on the image using Otsu's thresholding method, automatically determining the optimal threshold value based on the image's histogram. Integrate this method into your image processing workflow to achieve effective segmentation and feature extraction, enhancing the accuracy and reliability of image analysis tasks within your application. |
| [Blend](../../aspose.imaging/rasterimage/blend/)(Point, RasterImage, byte) | Blends this image instance with the *overlay* image. |
| override [Blend](../../aspose.imaging/rastercachedmultipageimage/blend/)(Point, RasterImage, Rectangle, byte) | Blends this image instance with the *overlay* image. |
| override [CacheData](../../aspose.imaging/rastercachedmultipageimage/cachedata/)() | Caches the data private. |
| [CanSave](../../aspose.imaging/image/cansave/)(ImageOptionsBase) | Determines whether image can be saved to the specified file format represented by the passed save options. |
| [ClearBlocks](../../aspose.imaging.fileformats.webp/webpimage/clearblocks/)() | Clear all existing WebP blocks from the image, facilitating a clean slate for subsequent modifications or additions. Utilize this method to effectively reset the block structure within the WebP image data, ensuring optimal management and organization of image content within your application. |
| override [Crop](../../aspose.imaging.fileformats.webp/webpimage/crop/#crop)(Rectangle) | Crop the image using a specified rectangle region, removing unwanted portions while retaining the desired content. Integrate this method into your image processing workflow to precisely extract and focus on specific areas of interest within the image, enhancing clarity and composition for various applications. |
| override [Crop](../../aspose.imaging.fileformats.webp/webpimage/crop/#crop_1)(int, int, int, int) | Crop the image by applying left, right, top, and bottom shifts, effectively selecting a region of interest within the image. Utilize this method to dynamically extract desired portions of the image while adjusting its composition and focus according to your application's requirements. |
| [Dispose](../../aspose.imaging/disposableobject/dispose/)() | Disposes the current instance. |
| [Dither](../../aspose.imaging/rasterimage/dither/)(DitheringMethod, int) | Performs dithering on the current image. |
| override [Dither](../../aspose.imaging.fileformats.webp/webpimage/dither/#dither_1)(DitheringMethod, int, IColorPalette) | Perform dithering on the current image to reduce color banding and enhance visual quality. Integrate this method into your image processing workflow to achieve smoother transitions between colors and improve the overall appearance of the image within your application. |
| override [EmbedDigitalSignature](../../aspose.imaging/rastercachedmultipageimage/embeddigitalsignature/)(string) | Embed digital sign based on provided password into each page of the image. |
| override [Filter](../../aspose.imaging.fileformats.webp/webpimage/filter/)(Rectangle, FilterOptionsBase) | Filter the content within the specified rectangle, applying a designated image processing filter to enhance or modify the selected region. Integrate this method into your image manipulation workflow to achieve targeted enhancements or transformations within your application. |
| [GetArgb32Pixel](../../aspose.imaging/rasterimage/getargb32pixel/)(int, int) | Gets an image 32-bit ARGB pixel. |
| [GetDefaultArgb32Pixels](../../aspose.imaging/rasterimage/getdefaultargb32pixels/)(Rectangle) | Gets the default 32-bit ARGB pixels array. |
| virtual [GetDefaultOptions](../../aspose.imaging/image/getdefaultoptions/)(object[]) | Gets the default options. |
| [GetDefaultPixels](../../aspose.imaging/rasterimage/getdefaultpixels/)(Rectangle, IPartialArgb32PixelLoader) | Gets the default pixels array using partial pixel loader. |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata/)(Rectangle, RawDataSettings) | Gets the default raw data array. |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata/)(Rectangle, IPartialRawDataLoader, RawDataSettings) | Gets the default raw data array using partial pixel loader. |
| virtual [GetModifyDate](../../aspose.imaging/rasterimage/getmodifydate/)(bool) | Gets the date and time the resource image was last modified. |
| override [GetOriginalOptions](../../aspose.imaging.fileformats.webp/webpimage/getoriginaloptions/)() | Gets the options based on the original file settings. This can be helpful to keep bit-depth and other parameters of the original image unchanged. For example, if we load a black-white PNG image with 1 bit per pixel and then save it using the [`Save`](../../aspose.imaging/datastreamsupporter/save/) method, the output PNG image with 8-bit per pixel will be produced. To avoid it and save PNG image with 1-bit per pixel, use this method to get corresponding saving options and pass them to the [`Save`](../../aspose.imaging/image/save/) method as the second parameter. |
| [GetPixel](../../aspose.imaging/rasterimage/getpixel/)(int, int) | Gets an image pixel. |
| override [GetSerializedStream](../../aspose.imaging/rastercachedmultipageimage/getserializedstream/)(ImageOptionsBase, Rectangle, out int) | Converts to aps. |
| [GetSkewAngle](../../aspose.imaging/rasterimage/getskewangle/)() | Gets the skew angle. This method is applicable to scanned text documents, to determine the skew angle when scanning. |
| override [Grayscale](../../aspose.imaging.fileformats.webp/webpimage/grayscale/)() | Convert the image to its grayscale representation, transforming it into a single-channel image where each pixel represents intensity or luminance. Integrate this method into your image processing pipeline to simplify analysis and enhance compatibility with grayscale-based algorithms, facilitating various computer vision and image analysis tasks within your application. |
| [InsertBlock](../../aspose.imaging.fileformats.webp/webpimage/insertblock/)(int, IFrame) | Insert a new WebP block at the specified index within the image, enabling precise control over the block sequence. Integrate this method to seamlessly incorporate additional WebP blocks into the image data structure, facilitating advanced image processing and optimization within your application. |
| override [IsDigitalSigned](../../aspose.imaging/rastercachedmultipageimage/isdigitalsigned/)(string, int) | Performs a fast check to determine if the image is digitally signed, using the provided password and threshold. |
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
| override [NormalizeAngle](../../aspose.imaging/rastercachedmultipageimage/normalizeangle/)(bool, Color) | Normalizes the angle. This method is applicable to scanned text documents to get rid of the skewed scan. This method uses [`GetSkewAngle`](../../aspose.imaging/rasterimage/getskewangle/) and [`Rotate`](../../aspose.imaging/rastercachedmultipageimage/rotate/) methods. |
| override [NormalizeHistogram](../../aspose.imaging/rastercachedmultipageimage/normalizehistogram/)() | Normalizes the image histogram — adjust pixel values to use all available range. |
| [ReadArgb32ScanLine](../../aspose.imaging/rasterimage/readargb32scanline/)(int) | Reads the whole scan line by the specified scan line index. |
| [ReadScanLine](../../aspose.imaging/rasterimage/readscanline/)(int) | Reads the whole scan line by the specified scan line index. |
| [RemoveBlock](../../aspose.imaging.fileformats.webp/webpimage/removeblock/)(IFrame) | Remove the specified WebP block from the image, facilitating efficient management of image data structure. Utilize this method to streamline image processing workflows by eliminating unnecessary blocks or components within your application. |
| override [RemoveMetadata](../../aspose.imaging/rasterimage/removemetadata/)() | Removes this image instance metadata by setting this [`XmpData`](../../aspose.imaging.xmp/ihasxmpdata/xmpdata/) value to `null`. |
| [ReplaceColor](../../aspose.imaging/rasterimage/replacecolor/)(Color, byte, Color) | Replaces one color to another with allowed difference and preserves original alpha value to save smooth edges. |
| override [ReplaceColor](../../aspose.imaging/rastercachedmultipageimage/replacecolor/)(int, byte, int) | Replaces one color to another with allowed difference and preserves original alpha value to save smooth edges. |
| [ReplaceNonTransparentColors](../../aspose.imaging/rasterimage/replacenontransparentcolors/)(Color) | Replaces all non-transparent colors with new color and preserves original alpha value to save smooth edges. Note: if you use it on images without transparency, all colors will be replaced with a single one. |
| override [ReplaceNonTransparentColors](../../aspose.imaging/rastercachedmultipageimage/replacenontransparentcolors/)(int) | Replaces all non-transparent colors with new color and preserves original alpha value to save smooth edges. Note: if you use it on images without transparency, all colors will be replaced with a single one. |
| [Resize](../../aspose.imaging/image/resize/)(int, int) | Resizes the image. The default NearestNeighbourResample is used. |
| override [Resize](../../aspose.imaging.fileformats.webp/webpimage/resize/#resize_1)(int, int, ImageResizeSettings) | Resize the image according to specified settings, enabling precise control over dimensions, aspect ratio, and scaling behavior. Integrate this method into your image processing workflow to achieve customized resizing operations tailored to the specific requirements of your application. |
| override [Resize](../../aspose.imaging.fileformats.webp/webpimage/resize/#resize_2)(int, int, ResizeType) | Resize the image, adjusting its dimensions while preserving the aspect ratio. Integrate this method into your image processing workflow to dynamically scale images to fit various display or storage requirements within your application. |
| [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally/)(int) | Resizes the height proportionally. The default NearestNeighbourResample is used. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally/)(int, ImageResizeSettings) | Resizes the height proportionally. |
| override [ResizeHeightProportionally](../../aspose.imaging.fileformats.webp/webpimage/resizeheightproportionally/#resizeheightproportionally_2)(int, ResizeType) | Adjust the height of the image proportionally, while preserving its aspect ratio for consistent resizing. Integrate this method into your image processing workflow to dynamically resize images with uniform proportions, ensuring optimal display or storage within your application. |
| [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally/)(int) | Resizes the width proportionally. The default NearestNeighbourResample is used. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally/)(int, ImageResizeSettings) | Resizes the width proportionally. |
| override [ResizeWidthProportionally](../../aspose.imaging.fileformats.webp/webpimage/resizewidthproportionally/#resizewidthproportionally_2)(int, ResizeType) | Proportionally adjust the width of the image while maintaining its aspect ratio. Integrate this method into your image processing workflow to dynamically resize images with consistent proportions, ensuring optimal display or storage within your application. |
| override [Rotate](../../aspose.imaging/rasterimage/rotate/)(float) | Rotate image around the center. |
| override [Rotate](../../aspose.imaging.fileformats.webp/webpimage/rotate/#rotate_1)(float, bool, Color) | Rotate the image around its center by a specified angle, while proportionally resizing it and applying specified background color parameters. Incorporate this method into your image processing workflow to achieve precise transformations with customizable background colors, ensuring optimal visual presentation within your application. |
| override [RotateFlip](../../aspose.imaging.fileformats.webp/webpimage/rotateflip/)(RotateFlipType) | Apply rotation, flipping, or both operations exclusively to the active frame within the image. Integrate this method into your image processing workflow to achieve precise manipulation of individual frames, enhancing flexibility and control over frame transformations within your application. |
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

* class [RasterCachedMultipageImage](../../aspose.imaging/rastercachedmultipageimage/)
* interface [IMultipageImageExt](../../aspose.imaging/imultipageimageext/)
* namespace [Aspose.Imaging.FileFormats.Webp](../../aspose.imaging.fileformats.webp/)
* assembly [Aspose.Imaging](../../)


