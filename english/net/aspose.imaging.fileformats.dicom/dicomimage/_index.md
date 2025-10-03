---
title: Class DicomImage
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Dicom.DicomImage class. This Class implements Digital Imaging and Communications in Medicine DICOM raster image format support and offers a comprehensive solution for processing DICOM images with precision and flexibility. You can seamlessly manipulate image pages including operations to get add or remove pages and control the default and active pages. With capabilities to work with alpha channels embed XMP metadata resize rotate crop binarize adjust apply filters and convert to other raster formats. This API empowers developers to handle DICOM images effectively while meeting diverse application requirements in medical imaging contexts
type: docs
weight: 2460
url: /net/aspose.imaging.fileformats.dicom/dicomimage/
---
## DicomImage class

This Class implements Digital Imaging and Communications in Medicine (DICOM) raster image format support and offers a comprehensive solution for processing DICOM images with precision and flexibility. You can seamlessly manipulate image pages, including operations to get, add, or remove pages, and control the default and active pages. With capabilities to work with alpha channels, embed XMP metadata, resize, rotate, crop, binarize, adjust, apply filters, and convert to other raster formats. This API empowers developers to handle DICOM images effectively while meeting diverse application requirements in medical imaging contexts.

```csharp
public sealed class DicomImage : RasterCachedMultipageImage, IMultipageImageExt
```

## Constructors

| Name | Description |
| --- | --- |
| [DicomImage](dicomimage/#constructor_1)(Stream) | Create a new instance of the DicomImage class by utilizing a stream parameter in this constructor. Perfect for developers seeking a streamlined way to initialize `DicomImage` objects from existing data streams in their projects. |
| [DicomImage](dicomimage/#constructor_2)(Stream, LoadOptions) | Initiate a new instance of the DicomImage class smoothly by employing a stream and loadOptions parameters in this constructor. Ideal for developers eager to start working with `DicomImage` objects promptly and effectively in their projects. |
| [DicomImage](dicomimage/#constructor)(DicomOptions, int, int) | Initialize a fresh instance of the DicomImage class effortlessly with this constructor, utilizing dicomOptions parameters. Perfect for developers looking to dive into `DicomImage` objects swiftly and efficiently in their projects. |

## Properties

| Name | Description |
| --- | --- |
| [ActivePage](../../aspose.imaging.fileformats.dicom/dicomimage/activepage/) { get; set; } | Manage the active page of the image with this intuitive property. Ideal for developers seeking to dynamically switch between pages within multi-page images, ensuring efficient navigation and processing. |
| [ActivePageIndex](../../aspose.imaging.fileformats.dicom/dicomimage/activepageindex/) { get; } | Retrieve the index of the active page effortlessly with this intuitive property. Ideal for developers seeking quick access to the current page index within multi-page images, ensuring efficient navigation and processing. |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette/) { get; set; } | Gets or sets a value indicating whether automatic adjust palette. |
| override [BackgroundColor](../../aspose.imaging/rastercachedmultipageimage/backgroundcolor/) { get; set; } | Gets or sets a value for the background color. |
| override [BitsPerPixel](../../aspose.imaging/rastercachedmultipageimage/bitsperpixel/) { get; } | Gets the image bits per pixel count. |
| [Bounds](../../aspose.imaging/image/bounds/) { get; } | Gets the image bounds. |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint/) { get; set; } | Gets or sets the buffer size hint which is defined max allowed size for all internal buffers. |
| [Container](../../aspose.imaging/image/container/) { get; } | Gets the [`Image`](../../aspose.imaging/image/) container. |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer/) { get; } | Gets the object's data stream. |
| [DicomPages](../../aspose.imaging.fileformats.dicom/dicomimage/dicompages/) { get; } | Access the pages of the image with this intuitive property. Ideal for developers seeking to interact with individual pages within the image, ensuring seamless navigation and manipulation. |
| [Disposed](../../aspose.imaging/disposableobject/disposed/) { get; } | Gets a value indicating whether this instance is disposed. |
| [ExifData](../../aspose.imaging/image/exifdata/) { get; set; } | Gets or sets the Exif data. |
| override [FileFormat](../../aspose.imaging.fileformats.dicom/dicomimage/fileformat/) { get; } | Retrieve the file format value effortlessly with this intuitive property. Ideal for developers seeking quick access to the format of the image file, ensuring efficient handling and processing based on the file type. |
| [FileInfo](../../aspose.imaging.fileformats.dicom/dicomimage/fileinfo/) { get; } | Retrieve valuable header information from the DICOM file effortlessly with this intuitive property. Ideal for developers seeking quick access to essential details encapsulated within the DICOM file, ensuring efficient data extraction and analysis. |
| override [HasAlpha](../../aspose.imaging.fileformats.dicom/dicomimage/hasalpha/) { get; } | Retrieve whether the image has an alpha channel effortlessly with this intuitive property. Ideal for developers seeking to determine if the image contains transparency information, ensuring precise handling of alpha channel data in image processing tasks. |
| virtual [HasBackgroundColor](../../aspose.imaging/image/hasbackgroundcolor/) { get; set; } | Gets or sets a value indicating whether image has background color. |
| override [HasTransparentColor](../../aspose.imaging/rastercachedmultipageimage/hastransparentcolor/) { get; } | Gets a value indicating whether image has transparent color. |
| override [Height](../../aspose.imaging/rastercachedmultipageimage/height/) { get; } | Gets the image height. |
| virtual [HorizontalResolution](../../aspose.imaging/rasterimage/horizontalresolution/) { get; set; } | Gets or sets the horizontal resolution, in pixels per inch, of this [`RasterImage`](../../aspose.imaging/rasterimage/). |
| override [ImageOpacity](../../aspose.imaging/rastercachedmultipageimage/imageopacity/) { get; } | Gets opacity of this image. |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor/) { get; set; } | Gets or sets the interrupt monitor. |
| override [IsCached](../../aspose.imaging/rastercachedmultipageimage/iscached/) { get; } | Gets a value indicating whether image data is cached currently. |
| [IsRawDataAvailable](../../aspose.imaging/rasterimage/israwdataavailable/) { get; } | Gets a value indicating whether raw data loading is available. |
| override [Metadata](../../aspose.imaging/rastercachedmultipageimage/metadata/) { get; } | Gets or sets XMP data from frame. |
| override [PageCount](../../aspose.imaging.fileformats.dicom/dicomimage/pagecount/) { get; } | Retrieve the total page count of the image with this intuitive property. Ideal for developers seeking quick access to the number of pages within an image, ensuring efficient navigation and management. |
| virtual [PageExportingAction](../../aspose.imaging/rastercachedmultipageimage/pageexportingaction/) { get; set; } | Gets or sets the page exporting action. Please note that setting this method will automatically release page resources after it is executed. It will be executed just before each page is saved. |
| override [Pages](../../aspose.imaging.fileformats.dicom/dicomimage/pages/) { get; } | Access the pages of the image with this intuitive property. Ideal for developers seeking to interact with individual pages within the image, ensuring seamless navigation and manipulation. |
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
| [AddPage](../../aspose.imaging.fileformats.dicom/dicomimage/addpage/#addpage)() | Append a new page to the end of the image's page list with this straightforward method. Ideal for developers seeking to dynamically expand multi-page images, ensuring seamless integration and organization of image content. |
| [AddPage](../../aspose.imaging.fileformats.dicom/dicomimage/addpage/#addpage_1)(RasterImage) | Expand your image collection by adding a new page with this intuitive method. Ideal for developers seeking to dynamically append pages to multi-page images, ensuring seamless expansion and organization of image content. |
| override [AdjustBrightness](../../aspose.imaging.fileformats.dicom/dicomimage/adjustbrightness/)(int) | Enhance image luminance with the adjustment of *brightness*, a parameterized method that allows developers to finely tune the luminosity of images. This user-friendly function empowers developers to seamlessly manipulate image brightness, offering flexibility and control over visual aesthetics. |
| override [AdjustContrast](../../aspose.imaging.fileformats.dicom/dicomimage/adjustcontrast/)(float) | Enhance [`Image`](../../aspose.imaging/image/) contrast with this user-friendly method, which adjusts the disparity between light and dark areas. Improve visual clarity and definition effortlessly, providing developers with intuitive control over image contrast for optimal rendering. |
| override [AdjustGamma](../../aspose.imaging.fileformats.dicom/dicomimage/adjustgamma/#adjustgamma)(float) | Enhance image quality and adjust it with gamma correction, a powerful technique for fine-tuning visual appearance. Perfect for developers aiming to optimize image presentation, adjust color balance, and ensure consistent rendering across different devices and environments. |
| override [AdjustGamma](../../aspose.imaging.fileformats.dicom/dicomimage/adjustgamma/#adjustgamma_1)(float, float, float) | Achieve precise color adjustments by applying gamma correction independently to the red, green, and blue components of an image. This method ensures accurate color balance and optimal visual output, catering to developers seeking granular control over image rendering and color accuracy. |
| override [AnalyzePercentageDigitalSignature](../../aspose.imaging/rastercachedmultipageimage/analyzepercentagedigitalsignature/)(string) | Calculates the percentage similarity between the extracted data and the original password. |
| override [AutoBrightnessContrast](../../aspose.imaging/rastercachedimage/autobrightnesscontrast/)() | Performs automatic adaptive brightness and contrast normalization for the entire image. |
| [AutoRotate](../../aspose.imaging/rasterimage/autorotate/)() | Automatically rotates the image based on orientation data extracted from Exif metadata. This method ensures that images are displayed in the correct orientation, enhancing user experience and eliminating the need for manual adjustments. By analyzing Exif information, the image is rotated accordingly, providing a seamless viewing experience across different platforms and devices. This automated rotation process simplifies image handling and improves overall usability, especially when dealing with large batches of images with varying orientations. |
| override [BinarizeBradley](../../aspose.imaging/rastercachedmultipageimage/binarizebradley/)(double) | Binarization of an image using Bradley's adaptive thresholding algorithm using the integral image thresholding |
| override [BinarizeBradley](../../aspose.imaging.fileformats.dicom/dicomimage/binarizebradley/#binarizebradley_1)(double, int) | Binarize images with Bradley's adaptive thresholding algorithm, leveraging integral image thresholding for improved performance. Ideal for developers looking to automatically segment images based on local variations in brightness, ensuring accurate object detection and extraction in varying lighting conditions. |
| override [BinarizeFixed](../../aspose.imaging.fileformats.dicom/dicomimage/binarizefixed/)(byte) | Easily convert the image into a binary format using a predefined threshold with this straightforward method. Ideal for developers looking to simplify image processing tasks by segmenting the image into foreground and background components based on specified intensity levels. |
| override [BinarizeOtsu](../../aspose.imaging.fileformats.dicom/dicomimage/binarizeotsu/)() | Apply Otsu thresholding to binarize the image, automatically determining the optimal threshold value based on the image's histogram. Perfect for developers seeking a reliable method to segment images into foreground and background regions with minimal manual intervention. |
| [Blend](../../aspose.imaging/rasterimage/blend/)(Point, RasterImage, byte) | Blends this image instance with the *overlay* image. |
| override [Blend](../../aspose.imaging/rastercachedmultipageimage/blend/)(Point, RasterImage, Rectangle, byte) | Blends this image instance with the *overlay* image. |
| override [CacheData](../../aspose.imaging.fileformats.dicom/dicomimage/cachedata/)() | This method efficiently caches data, optimizing performance and ensuring swift access when needed. Ideal for developers seeking to enhance the speed and efficiency of their applications by intelligently managing data resources. |
| [CanSave](../../aspose.imaging/image/cansave/)(ImageOptionsBase) | Determines whether image can be saved to the specified file format represented by the passed save options. |
| override [Crop](../../aspose.imaging.fileformats.dicom/dicomimage/crop/#crop)(Rectangle) | Crop the image to remove unwanted areas and focus on essential content with this simple method. Ideal for developers seeking to customize the visual composition of images, ensuring they convey the desired message effectively. |
| override [Crop](../../aspose.imaging.fileformats.dicom/dicomimage/crop/#crop_1)(int, int, int, int) | Adjust the cropping area of the image by applying shifts with this versatile method. Perfect for developers who need precise control over the cropping process, ensuring that important details are retained while eliminating unnecessary elements. |
| [Dispose](../../aspose.imaging/disposableobject/dispose/)() | Disposes the current instance. |
| [Dither](../../aspose.imaging/rasterimage/dither/)(DitheringMethod, int) | Performs dithering on the current image. |
| override [Dither](../../aspose.imaging.fileformats.dicom/dicomimage/dither/#dither_1)(DitheringMethod, int, IColorPalette) | Enhance the current image by applying dithering effects with this straightforward method. Perfect for developers aiming to add texture and depth to images, improving their visual quality and overall appeal. |
| override [EmbedDigitalSignature](../../aspose.imaging/rastercachedmultipageimage/embeddigitalsignature/)(string) | Embed digital sign based on provided password into each page of the image. |
| override [Filter](../../aspose.imaging.fileformats.dicom/dicomimage/filter/)(Rectangle, FilterOptionsBase) | Effortlessly enhance specific areas of your image by applying filters to designated rectangles. This method provides developers with precise control over image manipulation, allowing for targeted adjustments to achieve desired visual effects with ease. |
| [GetArgb32Pixel](../../aspose.imaging/rasterimage/getargb32pixel/)(int, int) | Gets an image 32-bit ARGB pixel. |
| [GetDefaultArgb32Pixels](../../aspose.imaging/rasterimage/getdefaultargb32pixels/)(Rectangle) | Gets the default 32-bit ARGB pixels array. |
| virtual [GetDefaultOptions](../../aspose.imaging/image/getdefaultoptions/)(object[]) | Gets the default options. |
| [GetDefaultPixels](../../aspose.imaging/rasterimage/getdefaultpixels/)(Rectangle, IPartialArgb32PixelLoader) | Gets the default pixels array using partial pixel loader. |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata/)(Rectangle, RawDataSettings) | Gets the default raw data array. |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata/)(Rectangle, IPartialRawDataLoader, RawDataSettings) | Gets the default raw data array using partial pixel loader. |
| virtual [GetModifyDate](../../aspose.imaging/rasterimage/getmodifydate/)(bool) | Gets the date and time the resource image was last modified. |
| virtual [GetOriginalOptions](../../aspose.imaging/image/getoriginaloptions/)() | Gets the options based on the original file settings. This can be helpful to keep bit-depth and other parameters of the original image unchanged. For example, if we load a black-white PNG image with 1 bit per pixel and then save it using the [`Save`](../../aspose.imaging/datastreamsupporter/save/) method, the output PNG image with 8-bit per pixel will be produced. To avoid it and save PNG image with 1-bit per pixel, use this method to get corresponding saving options and pass them to the [`Save`](../../aspose.imaging/image/save/) method as the second parameter. |
| [GetPixel](../../aspose.imaging/rasterimage/getpixel/)(int, int) | Gets an image pixel. |
| override [GetSerializedStream](../../aspose.imaging/rastercachedmultipageimage/getserializedstream/)(ImageOptionsBase, Rectangle, out int) | Converts to aps. |
| [GetSkewAngle](../../aspose.imaging/rasterimage/getskewangle/)() | Gets the skew angle. This method is applicable to scanned text documents, to determine the skew angle when scanning. |
| override [Grayscale](../../aspose.imaging.fileformats.dicom/dicomimage/grayscale/)() | Easily transform images into their grayscale representation, simplifying visual analysis and processing tasks. Perfect for developers seeking to enhance image clarity, reduce complexity, and facilitate efficient grayscale-based algorithms for diverse applications. |
| [InsertPage](../../aspose.imaging.fileformats.dicom/dicomimage/insertpage/)(int) | Insert a new page into the image's page list at a specified index with this intuitive method. Ideal for developers seeking precise control over the arrangement of pages in multi-page images, ensuring seamless organization and customization of image content. |
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
| override [RemoveMetadata](../../aspose.imaging/rasterimage/removemetadata/)() | Removes this image instance metadata by setting this [`XmpData`](../../aspose.imaging.xmp/ihasxmpdata/xmpdata/) value to `null`. |
| [RemovePage](../../aspose.imaging.fileformats.dicom/dicomimage/removepage/)(int) | Eliminate the page at the specified index from the page list with this convenient method. Ideal for developers seeking precise control over the management of multi-page images, ensuring seamless organization and customization of image content. |
| [ReplaceColor](../../aspose.imaging/rasterimage/replacecolor/)(Color, byte, Color) | Replaces one color to another with allowed difference and preserves original alpha value to save smooth edges. |
| override [ReplaceColor](../../aspose.imaging/rastercachedmultipageimage/replacecolor/)(int, byte, int) | Replaces one color to another with allowed difference and preserves original alpha value to save smooth edges. |
| [ReplaceNonTransparentColors](../../aspose.imaging/rasterimage/replacenontransparentcolors/)(Color) | Replaces all non-transparent colors with new color and preserves original alpha value to save smooth edges. Note: if you use it on images without transparency, all colors will be replaced with a single one. |
| override [ReplaceNonTransparentColors](../../aspose.imaging/rastercachedmultipageimage/replacenontransparentcolors/)(int) | Replaces all non-transparent colors with new color and preserves original alpha value to save smooth edges. Note: if you use it on images without transparency, all colors will be replaced with a single one. |
| [Resize](../../aspose.imaging/image/resize/)(int, int) | Resizes the image. The default NearestNeighbourResample is used. |
| override [Resize](../../aspose.imaging.fileformats.dicom/dicomimage/resize/#resize_1)(int, int, ImageResizeSettings) | Adjust the size of your image with this simple resizing method. Whether you need to shrink or enlarge your image, this function ensures that your resizing needs are met efficiently and accurately, making it perfect for developers seeking quick and easy image size adjustments. |
| override [Resize](../../aspose.imaging.fileformats.dicom/dicomimage/resize/#resize_2)(int, int, ResizeType) | Adjust the size of the image with this straightforward method. Ideal for developers looking to dynamically resize images, ensuring they fit seamlessly into various contexts and layouts within their applications. |
| [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally/)(int) | Resizes the height proportionally. The default NearestNeighbourResample is used. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally/)(int, ImageResizeSettings) | Resizes the height proportionally. |
| override [ResizeHeightProportionally](../../aspose.imaging.fileformats.dicom/dicomimage/resizeheightproportionally/#resizeheightproportionally_2)(int, ResizeType) | Adjust the height of the image while maintaining its aspect ratio with this user-friendly method. Perfect for developers seeking to dynamically resize images while preserving their proportions, ensuring optimal display and usability in their applications. |
| [ResizeProportional](../../aspose.imaging.fileformats.dicom/dicomimage/resizeproportional/)(int, int, ResizeType) | Resize the image while maintaining its aspect ratio with this convenient method. Ideal for developers seeking to adjust the image dimensions proportionally, ensuring consistency and preserving the original content's proportions. The proportional resize will resize each frame according to the ratio of *newWidth*/width and *newHeight*/height. |
| [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally/)(int) | Resizes the width proportionally. The default NearestNeighbourResample is used. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally/)(int, ImageResizeSettings) | Resizes the width proportionally. |
| override [ResizeWidthProportionally](../../aspose.imaging.fileformats.dicom/dicomimage/resizewidthproportionally/#resizewidthproportionally_2)(int, ResizeType) | Adjust the width of the image while maintaining its aspect ratio with this convenient method. Ideal for developers seeking to resize images proportionally, ensuring consistent and visually appealing results across different display environment. |
| override [Rotate](../../aspose.imaging/rasterimage/rotate/)(float) | Rotate image around the center. |
| override [Rotate](../../aspose.imaging.fileformats.dicom/dicomimage/rotate/#rotate_1)(float, bool, Color) | Rotate the image around its center with this convenient method. Ideal for developers seeking to adjust image orientation dynamically, ensuring optimal presentation and alignment within their applications. |
| override [RotateFlip](../../aspose.imaging.fileformats.dicom/dicomimage/rotateflip/)(RotateFlipType) | Easily manipulate the active frame by rotating, flipping, or performing both actions simultaneously with this straightforward method. Ideal for developers who need to dynamically adjust the orientation of specific frames within their image sequences, ensuring optimal presentation and alignment. |
| [Save](../../aspose.imaging/image/save/)() | Saves the image data to the underlying stream. |
| [Save](../../aspose.imaging/datastreamsupporter/save/)(Stream) | Saves the object's data to the specified stream. |
| override [Save](../../aspose.imaging/image/save/)(string) | Saves the image to the specified file location. |
| [Save](../../aspose.imaging/image/save/)(Stream, ImageOptionsBase) | Saves the image's data to the specified stream in the specified file format according to save options. |
| virtual [Save](../../aspose.imaging/datastreamsupporter/save/)(string, bool) | Saves the object's data to the specified file location. |
| virtual [Save](../../aspose.imaging/image/save/)(string, ImageOptionsBase) | Saves the object's data to the specified file location in the specified file format according to save options. |
| override [Save](../../aspose.imaging.fileformats.dicom/dicomimage/save/#save_3)(Stream, ImageOptionsBase, Rectangle) | Easily save your image data to a specified stream in the desired file format using this convenient method. Whether you're working with JPEG, PNG, or another format, this function ensures that your image data is saved efficiently and accurately, making it ideal for developers looking to streamline their file-saving processes. |
| virtual [Save](../../aspose.imaging/image/save/)(string, ImageOptionsBase, Rectangle) | Saves the object's data to the specified file location in the specified file format according to save options. |
| [SaveAll](../../aspose.imaging.fileformats.dicom/dicomimage/saveall/)(string, ImageOptionsBase) | Preserve the object's data by saving it to the designated file (indexer + filename) location along with specified file format and options. Ideal for developers seeking to securely store data in various formats while maintaining flexibility and control over saving parameters. |
| [SaveArgb32Pixels](../../aspose.imaging/rasterimage/saveargb32pixels/)(Rectangle, int[]) | Saves the 32-bit ARGB pixels. |
| [SaveCmyk32Pixels](../../aspose.imaging/rasterimage/savecmyk32pixels/)(Rectangle, int[]) | Saves the pixels. |
| [SavePixels](../../aspose.imaging/rasterimage/savepixels/)(Rectangle, Color[]) | Saves the pixels. |
| [SaveRawData](../../aspose.imaging/rasterimage/saverawdata/)(byte[], int, Rectangle, RawDataSettings) | Saves the raw data. |
| [SetArgb32Pixel](../../aspose.imaging/rasterimage/setargb32pixel/)(int, int, int) | Sets an image 32-bit ARGB pixel for the specified position. |
| override [SetPalette](../../aspose.imaging/rasterimage/setpalette/)(IColorPalette, bool) | Sets the image palette. |
| [SetPixel](../../aspose.imaging/rasterimage/setpixel/)(int, int, Color) | Sets an image pixel for the specified position. |
| override [SetResolution](../../aspose.imaging.fileformats.dicom/dicomimage/setresolution/)(double, double) | Adjust the resolution of this [`RasterImage`](../../aspose.imaging/rasterimage/) with precision using this straightforward method. Ideal for developers looking to tailor image resolution to specific requirements, ensuring optimal display quality and file size management. |
| virtual [ToBitmap](../../aspose.imaging/rasterimage/tobitmap/)() | Converts raster image to the bitmap. This method is not supported in versions from .Net7.0 and higher |
| virtual [TrySetMetadata](../../aspose.imaging/image/trysetmetadata/)(IImageMetadataFormat) | Tries to set a *metadata* instance, if this [`Image`](../../aspose.imaging/image/) instance supports and implements [`IImageMetadataFormat`](../../aspose.imaging.metadata/iimagemetadataformat/) type. |
| [WriteArgb32ScanLine](../../aspose.imaging/rasterimage/writeargb32scanline/)(int, int[]) | Writes the whole scan line to the specified scan line index. |
| [WriteScanLine](../../aspose.imaging/rasterimage/writescanline/)(int, Color[]) | Writes the whole scan line to the specified scan line index. |

## Examples

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

* class [RasterCachedMultipageImage](../../aspose.imaging/rastercachedmultipageimage/)
* interface [IMultipageImageExt](../../aspose.imaging/imultipageimageext/)
* namespace [Aspose.Imaging.FileFormats.Dicom](../../aspose.imaging.fileformats.dicom/)
* assembly [Aspose.Imaging](../../)


