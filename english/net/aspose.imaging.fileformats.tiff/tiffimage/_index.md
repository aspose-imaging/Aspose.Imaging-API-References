---
title: Class TiffImage
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Tiff.TiffImage class. Process Tagged Image File Format TIFF raster images with our API offering comprehensive support for various resolutions and advanced editing capabilities like EXIF data manipulation and alpha channels. Normalize angles for scanned images resize transform to grayscale and apply filters gamma corrections and image parameters adjustments with ease. Seamlessly handle multiframe TIFF files create graphics paths add shapes and effortlessly save images to different formats
type: docs
weight: 7990
url: /net/aspose.imaging.fileformats.tiff/tiffimage/
---
## TiffImage class

Process Tagged Image File Format (TIFF) raster images with our API, offering comprehensive support for various resolutions and advanced editing capabilities like EXIF data manipulation and alpha channels. Normalize angles for scanned images, resize, transform to grayscale, and apply filters, gamma corrections and image parameters adjustments with ease. Seamlessly handle multi-frame TIFF files, create graphics paths, add shapes, and effortlessly save images to different formats.

```csharp
public class TiffImage : RasterCachedMultipageImage, IMultipageImageExt
```

## Constructors

| Name | Description |
| --- | --- |
| [TiffImage](tiffimage/#constructor)(TiffFrame) | Initialize a new object of the `TiffImage` class, specifying the frame parameter. This constructor facilitates the creation of a TiffImage instance, allowing developers to specify the frame to be loaded or processed, streamlining Tiff image handling tasks within their applications. |
| [TiffImage](tiffimage/#constructor_1)(TiffFrame[]) | Create a new instance of the `TiffImage` class, providing a list of frames as a parameter. This constructor enables the initialization of a TiffImage object with multiple frames, facilitating efficient handling and processing of TIFF image sequences within software applications. |

## Properties

| Name | Description |
| --- | --- |
| [ActiveFrame](../../aspose.imaging.fileformats.tiff/tiffimage/activeframe/) { get; set; } | Manage the active frame seamlessly, facilitating dynamic navigation and manipulation within the designated context. Empower your application to interact efficiently with multimedia content, enhancing user engagement and productivity. |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette/) { get; set; } | Gets or sets a value indicating whether automatic adjust palette. |
| override [BackgroundColor](../../aspose.imaging/rastercachedmultipageimage/backgroundcolor/) { get; set; } | Gets or sets a value for the background color. |
| override [BitsPerPixel](../../aspose.imaging/rastercachedmultipageimage/bitsperpixel/) { get; } | Gets the image bits per pixel count. |
| [Bounds](../../aspose.imaging/image/bounds/) { get; } | Gets the image bounds. |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint/) { get; set; } | Gets or sets the buffer size hint which is defined max allowed size for all internal buffers. |
| [ByteOrder](../../aspose.imaging.fileformats.tiff/tiffimage/byteorder/) { get; set; } | Toggle the byte order for TIFF files seamlessly, ensuring precise control over data interpretation. Empower your applications with the flexibility to adapt to diverse file specifications, enhancing compatibility and efficiency in data processing. |
| [Container](../../aspose.imaging/image/container/) { get; } | Gets the [`Image`](../../aspose.imaging/image/) container. |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer/) { get; } | Gets the object's data stream. |
| [Disposed](../../aspose.imaging/disposableobject/disposed/) { get; } | Gets a value indicating whether this instance is disposed. |
| [ExifData](../../aspose.imaging/image/exifdata/) { get; set; } | Gets or sets the Exif data. |
| override [FileFormat](../../aspose.imaging.fileformats.tiff/tiffimage/fileformat/) { get; } | Retrieve the file format value associated with the image. This property serves as a critical aspect of image metadata retrieval, allowing software applications to identify and interpret the format of the image data efficiently. |
| [Frames](../../aspose.imaging.fileformats.tiff/tiffimage/frames/) { get; } | Retrieve an array of [`TiffFrame`](../tiffframe/) instances, enabling comprehensive access and manipulation of individual frames within the TIFF image. Harness the power of this array to streamline image processing workflows, ensuring precise control and optimization of visual content. |
| override [HasAlpha](../../aspose.imaging.fileformats.tiff/tiffimage/hasalpha/) { get; } | Determine whether the image has an alpha channel, providing crucial information for rendering and compositing operations. Integrate this feature to optimize visual processing workflows, ensuring accurate representation and manipulation of transparent elements. |
| virtual [HasBackgroundColor](../../aspose.imaging/image/hasbackgroundcolor/) { get; set; } | Gets or sets a value indicating whether image has background color. |
| override [HasTransparentColor](../../aspose.imaging/rastercachedmultipageimage/hastransparentcolor/) { get; } | Gets a value indicating whether image has transparent color. |
| override [Height](../../aspose.imaging/rastercachedmultipageimage/height/) { get; } | Gets the image height. |
| override [HorizontalResolution](../../aspose.imaging.fileformats.tiff/tiffimage/horizontalresolution/) { get; set; } | Retrieve the horizontal resolution of the specified [`Image`](../../aspose.imaging/image/) in pixels per inch, facilitating precise adjustment and rendering capabilities. Access essential image metadata effortlessly, empowering streamlined image processing workflows for enhanced user experiences. |
| override [ImageOpacity](../../aspose.imaging/rastercachedmultipageimage/imageopacity/) { get; } | Gets opacity of this image. |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor/) { get; set; } | Gets or sets the interrupt monitor. |
| override [IsCached](../../aspose.imaging/rastercachedmultipageimage/iscached/) { get; } | Gets a value indicating whether image data is cached currently. |
| [IsRawDataAvailable](../../aspose.imaging/rasterimage/israwdataavailable/) { get; } | Gets a value indicating whether raw data loading is available. |
| override [Metadata](../../aspose.imaging/rastercachedmultipageimage/metadata/) { get; } | Gets or sets XMP data from frame. |
| override [PageCount](../../aspose.imaging.fileformats.tiff/tiffimage/pagecount/) { get; } | Retrieve the total count of pages within the specified document, facilitating efficient navigation and management of multi-page content. Incorporate this functionality to enhance user experience, enabling seamless access to comprehensive document structures. |
| virtual [PageExportingAction](../../aspose.imaging/rastercachedmultipageimage/pageexportingaction/) { get; set; } | Gets or sets the page exporting action. Please note that setting this method will automatically release page resources after it is executed. It will be executed just before each page is saved. |
| override [Pages](../../aspose.imaging.fileformats.tiff/tiffimage/pages/) { get; } | Access the pages of the document seamlessly, enabling dynamic navigation and manipulation within the content structure. Empower your application with efficient access to individual pages, facilitating streamlined document processing and enhanced user interaction. |
| [Palette](../../aspose.imaging/image/palette/) { get; set; } | Gets or sets the color palette. The color palette is not used when pixels are represented directly. |
| override [PremultiplyComponents](../../aspose.imaging.fileformats.tiff/tiffimage/premultiplycomponents/) { get; set; } | Indicate if components necessitate premultiplication, ensuring efficient handling of visual elements. Enhance rendering processes by toggling this property, streamlining graphic workflows for optimized performance. |
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
| override [VerticalResolution](../../aspose.imaging.fileformats.tiff/tiffimage/verticalresolution/) { get; set; } | Access the vertical resolution of the designated [`Image`](../../aspose.imaging/image/) in pixels per inch, enabling precise adjustments and rendering optimizations. Utilize essential image data effortlessly to streamline image processing workflows, ensuring superior quality and performance in your applications. |
| override [Width](../../aspose.imaging/rastercachedmultipageimage/width/) { get; } | Gets the image width. |
| [XmpData](../../aspose.imaging/image/xmpdata/) { get; set; } | Gets or sets the Xmp data. |

## Methods

| Name | Description |
| --- | --- |
| [Add](../../aspose.imaging.fileformats.tiff/tiffimage/add/)(TiffImage) | Add the frames from the specified image seamlessly into the current frame, consolidating their content and enhancing compositional flexibility. Integrate this method to streamline frame management and manipulation within your application, facilitating efficient handling of multi-frame images. |
| [AddFrame](../../aspose.imaging.fileformats.tiff/tiffimage/addframe/)(TiffFrame) | Incorporate the specified frame seamlessly into the image, expanding its content and versatility. Utilize this method to enhance image composition and management, empowering efficient handling of multi-frame images within your application. |
| [AddFrames](../../aspose.imaging.fileformats.tiff/tiffimage/addframes/)(TiffFrame[]) | Integrate the array of frames seamlessly into the image, enriching its content and versatility. Utilize this method to enhance image composition and management, enabling efficient handling of multi-frame images within your application. |
| virtual [AddPage](../../aspose.imaging.fileformats.tiff/tiffimage/addpage/)(RasterImage) | Incorporate a new page into the existing image seamlessly, expanding its content and versatility. Utilize this method to enhance document composition and management, empowering efficient handling of multi-page images within your application. |
| override [AdjustBrightness](../../aspose.imaging.fileformats.tiff/tiffimage/adjustbrightness/)(int) | Implement *brightness* adjustment for the image, allowing the modification of overall luminance levels. Incorporate this method into your image processing workflow to enhance visibility and improve the visual quality of images within your application. |
| override [AdjustContrast](../../aspose.imaging.fileformats.tiff/tiffimage/adjustcontrast/)(float) | Enhance the contrast of the [`Image`](../../aspose.imaging/image/) instance, amplifying the differences between its light and dark areas. Integrate this functionality to improve the visual clarity and overall quality of the image within your application. |
| override [AdjustGamma](../../aspose.imaging.fileformats.tiff/tiffimage/adjustgamma/#adjustgamma)(float) | Apply gamma correction to the image, adjusting pixel intensities to achieve desired color balance. Incorporate this method into your image processing workflow to enhance visual quality and improve the accuracy of subsequent analysis or display tasks within your application. |
| override [AdjustGamma](../../aspose.imaging.fileformats.tiff/tiffimage/adjustgamma/#adjustgamma_1)(float, float, float) | Perform gamma correction on the image using individual coefficients for red, green, and blue channels, allowing for fine-tuned adjustments of color balance and contrast. Integrate this method into your image processing pipeline to achieve precise control over color rendering and enhance visual fidelity within your application. |
| [AlignResolutions](../../aspose.imaging.fileformats.tiff/tiffimage/alignresolutions/)() | Implement the AlignResolutions helper method to synchronize horizontal and vertical resolutions, ensuring uniformity in image dimensions. This functionality facilitates streamlined image processing workflows by harmonizing resolution parameters, optimizing visual quality and consistency across various platforms and devices. |
| override [AnalyzePercentageDigitalSignature](../../aspose.imaging/rastercachedmultipageimage/analyzepercentagedigitalsignature/)(string) | Calculates the percentage similarity between the extracted data and the original password. |
| override [AutoBrightnessContrast](../../aspose.imaging/rastercachedimage/autobrightnesscontrast/)() | Performs automatic adaptive brightness and contrast normalization for the entire image. |
| [AutoRotate](../../aspose.imaging/rasterimage/autorotate/)() | Automatically rotates the image based on orientation data extracted from Exif metadata. This method ensures that images are displayed in the correct orientation, enhancing user experience and eliminating the need for manual adjustments. By analyzing Exif information, the image is rotated accordingly, providing a seamless viewing experience across different platforms and devices. This automated rotation process simplifies image handling and improves overall usability, especially when dealing with large batches of images with varying orientations. |
| override [BinarizeBradley](../../aspose.imaging/rastercachedmultipageimage/binarizebradley/)(double) | Binarization of an image using Bradley's adaptive thresholding algorithm using the integral image thresholding |
| override [BinarizeBradley](../../aspose.imaging.fileformats.tiff/tiffimage/binarizebradley/#binarizebradley_1)(double, int) | Implement binarization on the image employing Bradley's adaptive thresholding algorithm with integral image thresholding. This approach dynamically computes local thresholds based on the image's neighborhood, enhancing adaptability to varying lighting conditions and ensuring robust segmentation for subsequent processing tasks within your application. |
| override [BinarizeFixed](../../aspose.imaging.fileformats.tiff/tiffimage/binarizefixed/)(byte) | Apply binarization to the image using a predefined threshold, converting it into a binary image with distinct foreground and background regions. Incorporate this method into your image processing workflow to facilitate segmentation and feature extraction tasks, enhancing the accuracy and efficiency of image analysis within your application. |
| override [BinarizeOtsu](../../aspose.imaging.fileformats.tiff/tiffimage/binarizeotsu/)() | Utilize Otsu thresholding to perform binarization on the image, automatically determining the optimal threshold value based on the image's histogram. Integrate this method into your image processing workflow to achieve effective segmentation and feature extraction, enhancing the accuracy and reliability of image analysis tasks within your application. |
| [Blend](../../aspose.imaging/rasterimage/blend/)(Point, RasterImage, byte) | Blends this image instance with the *overlay* image. |
| override [Blend](../../aspose.imaging/rastercachedmultipageimage/blend/)(Point, RasterImage, Rectangle, byte) | Blends this image instance with the *overlay* image. |
| override [CacheData](../../aspose.imaging/rastercachedmultipageimage/cachedata/)() | Caches the data private. |
| [CanSave](../../aspose.imaging/image/cansave/)(ImageOptionsBase) | Determines whether image can be saved to the specified file format represented by the passed save options. |
| override [Crop](../../aspose.imaging.fileformats.tiff/tiffimage/crop/#crop)(Rectangle) | Crop the image using a specified rectangular region, allowing precise selection of desired content. Integrate this method into your image processing workflow to efficiently remove unwanted areas and focus on essential details, enhancing the overall clarity and composition of the image. |
| override [Crop](../../aspose.imaging.fileformats.tiff/tiffimage/crop/#crop_1)(int, int, int, int) | Perform cropping on the image by specifying shifts in the left, right, top, and bottom directions. This method enables precise selection of the desired portion of the image, facilitating efficient removal of unwanted areas and focusing on essential content. Integrate this functionality into your image processing pipeline to enhance clarity and composition as needed within your application. |
| [Dispose](../../aspose.imaging/disposableobject/dispose/)() | Disposes the current instance. |
| [Dither](../../aspose.imaging/rasterimage/dither/)(DitheringMethod, int) | Performs dithering on the current image. |
| override [Dither](../../aspose.imaging.fileformats.tiff/tiffimage/dither/#dither_1)(DitheringMethod, int, IColorPalette) | Execute dithering on the current image to enhance its visual quality and reduce color banding artifacts. Integrate this method into your image processing workflow to ensure smoother transitions between colors, resulting in improved overall image appearance and clarity. |
| override [EmbedDigitalSignature](../../aspose.imaging/rastercachedmultipageimage/embeddigitalsignature/)(string) | Embed digital sign based on provided password into each page of the image. |
| override [Filter](../../aspose.imaging.fileformats.tiff/tiffimage/filter/)(Rectangle, FilterOptionsBase) | Filter the content within the specified rectangle, applying a designated image processing filter to enhance or modify the selected region. Integrate this method into your image manipulation workflow to achieve targeted enhancements or transformations within your application. |
| [GetArgb32Pixel](../../aspose.imaging/rasterimage/getargb32pixel/)(int, int) | Gets an image 32-bit ARGB pixel. |
| [GetDefaultArgb32Pixels](../../aspose.imaging/rasterimage/getdefaultargb32pixels/)(Rectangle) | Gets the default 32-bit ARGB pixels array. |
| virtual [GetDefaultOptions](../../aspose.imaging/image/getdefaultoptions/)(object[]) | Gets the default options. |
| [GetDefaultPixels](../../aspose.imaging/rasterimage/getdefaultpixels/)(Rectangle, IPartialArgb32PixelLoader) | Gets the default pixels array using partial pixel loader. |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata/)(Rectangle, RawDataSettings) | Gets the default raw data array. |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata/)(Rectangle, IPartialRawDataLoader, RawDataSettings) | Gets the default raw data array using partial pixel loader. |
| virtual [GetModifyDate](../../aspose.imaging/rasterimage/getmodifydate/)(bool) | Gets the date and time the resource image was last modified. |
| override [GetOriginalOptions](../../aspose.imaging.fileformats.tiff/tiffimage/getoriginaloptions/)() | Retrieve options derived from the original file settings, facilitating seamless preservation of key parameters such as bit-depth and other essential attributes of the original image. Utilize this method to maintain fidelity and consistency in image processing tasks, ensuring optimal results without unnecessary alterations. For example, if we load a black-white PNG image with 1 bit per pixel and then save it using the [`Save`](../../aspose.imaging/datastreamsupporter/save/) method, the output PNG image with 8-bit per pixel will be produced. To avoid it and save PNG image with 1-bit per pixel, use this method to get corresponding saving options and pass them to the [`Save`](../../aspose.imaging/image/save/) method as the second parameter. |
| [GetPixel](../../aspose.imaging/rasterimage/getpixel/)(int, int) | Gets an image pixel. |
| override [GetSerializedStream](../../aspose.imaging/rastercachedmultipageimage/getserializedstream/)(ImageOptionsBase, Rectangle, out int) | Converts to aps. |
| [GetSkewAngle](../../aspose.imaging/rasterimage/getskewangle/)() | Gets the skew angle. This method is applicable to scanned text documents, to determine the skew angle when scanning. |
| override [Grayscale](../../aspose.imaging.fileformats.tiff/tiffimage/grayscale/)() | Convert the image to its grayscale representation, transforming it into a single-channel image where each pixel represents intensity. Integrate this method into your image processing pipeline to simplify analysis and enhance compatibility with grayscale-based algorithms, facilitating various computer vision and image analysis tasks within your application. |
| [InsertFrame](../../aspose.imaging.fileformats.tiff/tiffimage/insertframe/)(int, TiffFrame) | Insert the new frame at the specified index within the frame sequence, ensuring precise control over frame arrangement. Employ this method to manage frame sequences effectively, facilitating dynamic manipulation and organization of image content within your application. |
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
| override [NormalizeAngle](../../aspose.imaging.fileformats.tiff/tiffimage/normalizeangle/#normalizeangle_1)(bool, Color) | Utilize the NormalizeAngle method specifically designed for scanned text documents to rectify skewed scans, ensuring accurate alignment. Seamlessly integrate this functionality into your text processing workflows to enhance document readability and quality, improving overall efficiency in text recognition and analysis tasks. This method uses [`GetSkewAngle`](../../aspose.imaging/rasterimage/getskewangle/) and [`Rotate`](./rotate/) methods. |
| override [NormalizeHistogram](../../aspose.imaging/rastercachedmultipageimage/normalizehistogram/)() | Normalizes the image histogram — adjust pixel values to use all available range. |
| [ReadArgb32ScanLine](../../aspose.imaging/rasterimage/readargb32scanline/)(int) | Reads the whole scan line by the specified scan line index. |
| [ReadScanLine](../../aspose.imaging/rasterimage/readscanline/)(int) | Reads the whole scan line by the specified scan line index. |
| [RemoveFrame](../../aspose.imaging.fileformats.tiff/tiffimage/removeframe/#removeframe)(int) | Effortlessly eliminate the frame identified by its index from the image sequence, streamlining frame management within your application. Integrate this functionality to enhance efficiency and precision in frame manipulation, facilitating seamless organization and presentation of image content. |
| [RemoveFrame](../../aspose.imaging.fileformats.tiff/tiffimage/removeframe/#removeframe_1)(TiffFrame) | Efficiently remove the specified frame from the image sequence, facilitating streamlined frame management within your application. Integrate this functionality to enhance precision and flexibility in frame manipulation, ensuring seamless organization and presentation of image content. |
| override [RemoveMetadata](../../aspose.imaging.fileformats.tiff/tiffimage/removemetadata/)() | Removes this image instance metadata by setting this [`XmpData`](../../aspose.imaging.xmp/ihasxmpdata/xmpdata/) and [`ExifData`](../../aspose.imaging.exif/ihasexifdata/exifdata/) values to `null`. |
| [ReplaceColor](../../aspose.imaging/rasterimage/replacecolor/)(Color, byte, Color) | Replaces one color to another with allowed difference and preserves original alpha value to save smooth edges. |
| override [ReplaceColor](../../aspose.imaging/rastercachedmultipageimage/replacecolor/)(int, byte, int) | Replaces one color to another with allowed difference and preserves original alpha value to save smooth edges. |
| [ReplaceFrame](../../aspose.imaging.fileformats.tiff/tiffimage/replaceframe/)(int, TiffFrame) | Substitute the frame at the designated position with another frame seamlessly, facilitating dynamic frame management within the image sequence. Integrate this method to enhance flexibility and precision in frame manipulation, ensuring optimal organization and presentation of image content within your application. |
| [ReplaceNonTransparentColors](../../aspose.imaging/rasterimage/replacenontransparentcolors/)(Color) | Replaces all non-transparent colors with new color and preserves original alpha value to save smooth edges. Note: if you use it on images without transparency, all colors will be replaced with a single one. |
| override [ReplaceNonTransparentColors](../../aspose.imaging/rastercachedmultipageimage/replacenontransparentcolors/)(int) | Replaces all non-transparent colors with new color and preserves original alpha value to save smooth edges. Note: if you use it on images without transparency, all colors will be replaced with a single one. |
| [Resize](../../aspose.imaging/image/resize/)(int, int) | Resizes the image. The default NearestNeighbourResample is used. |
| override [Resize](../../aspose.imaging.fileformats.tiff/tiffimage/resize/#resize_1)(int, int, ImageResizeSettings) | Adjust the size of the image based on specified settings, allowing for precise control over dimensions, aspect ratio, and scaling behavior. Integrate this method into your image processing workflow to achieve customized resizing operations tailored to the specific requirements of your application. |
| override [Resize](../../aspose.imaging.fileformats.tiff/tiffimage/resize/#resize_2)(int, int, ResizeType) | Resize the image according to a specified resizing type, facilitating flexible adjustment of image dimensions while preserving aspect ratio or applying specific scaling algorithms. Incorporate this method into your image processing workflow to achieve precise control over resizing operations within your application. |
| [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally/)(int) | Resizes the height proportionally. The default NearestNeighbourResample is used. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally/)(int, ImageResizeSettings) | Resizes the height proportionally. |
| override [ResizeHeightProportionally](../../aspose.imaging.fileformats.tiff/tiffimage/resizeheightproportionally/#resizeheightproportionally_2)(int, ResizeType) | Conduct a proportional adjustment of the image's height, preserving its aspect ratio for consistent visual integrity. Employ this method to dynamically resize images within your application, ensuring optimal display across diverse platforms and devices without compromising content quality. |
| [ResizeProportional](../../aspose.imaging.fileformats.tiff/tiffimage/resizeproportional/)(int, int, ResizeType) | Conduct a proportional resize operation on the image, preserving its aspect ratio while adjusting its dimensions. Employ this method to dynamically scale images within your application, ensuring consistent visual representation of content integrity. The proportional resize will resize each frame according to the ratio of *newWidth*/width and *newHeight*/height. |
| [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally/)(int) | Resizes the width proportionally. The default NearestNeighbourResample is used. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally/)(int, ImageResizeSettings) | Resizes the width proportionally. |
| override [ResizeWidthProportionally](../../aspose.imaging.fileformats.tiff/tiffimage/resizewidthproportionally/#resizewidthproportionally_2)(int, ResizeType) | Adjust the width of the image while maintaining its aspect ratio, ensuring proportional resizing for optimal visual presentation. Utilize this method to dynamically scale images within your application, facilitating consistent and aesthetically pleasing rendering across various display contexts. |
| override [Rotate](../../aspose.imaging/rasterimage/rotate/)(float) | Rotate image around the center. |
| override [Rotate](../../aspose.imaging.fileformats.tiff/tiffimage/rotate/#rotate_1)(float, bool, Color) | Rotate the image around its center point by a specified angle, enabling precise orientation adjustments. Incorporate this functionality into your image processing pipeline to facilitate accurate transformations, ensuring optimal alignment and presentation of visual content within your application. |
| override [RotateFlip](../../aspose.imaging.fileformats.tiff/tiffimage/rotateflip/)(RotateFlipType) | Perform rotation, flipping, or a combination of both operations exclusively on the active frame. This method allows precise manipulation of individual frames within the image sequence, enhancing flexibility in image editing and composition within your application. |
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
| override [SetResolution](../../aspose.imaging.fileformats.tiff/tiffimage/setresolution/)(double, double) | Establishes the resolution for the specified [`RasterImage`](../../aspose.imaging/rasterimage/), enabling precise control over image rendering and display properties. Integrate this functionality to optimize visual output and ensure compatibility with diverse output devices and platforms, enhancing the overall user experience. |
| virtual [ToBitmap](../../aspose.imaging/rasterimage/tobitmap/)() | Converts raster image to the bitmap. This method is not supported in versions from .Net7.0 and higher |
| virtual [TrySetMetadata](../../aspose.imaging/image/trysetmetadata/)(IImageMetadataFormat) | Tries to set a *metadata* instance, if this [`Image`](../../aspose.imaging/image/) instance supports and implements [`IImageMetadataFormat`](../../aspose.imaging.metadata/iimagemetadataformat/) type. |
| [WriteArgb32ScanLine](../../aspose.imaging/rasterimage/writeargb32scanline/)(int, int[]) | Writes the whole scan line to the specified scan line index. |
| [WriteScanLine](../../aspose.imaging/rasterimage/writescanline/)(int, Color[]) | Writes the whole scan line to the specified scan line index. |

## Examples

Create Graphics Path from Path Resources in TIFF image.

```csharp
[C#]

using (var image = (TiffImage)Image.Load("Bottle.tif"))
{
    // Create the GraphicsPath using PathResources from TIFF image
    var graphicsPath = PathResourceConverter.ToGraphicsPath(image.ActiveFrame.PathResources.ToArray(), image.ActiveFrame.Size);
    var graphics = new Graphics(image);

    // Draw red line and save the image
    graphics.DrawPath(new Pen(Color.Red, 10), graphicsPath);
    image.Save("BottleWithRedBorder.tif");
}
```

Create Path Resources using Graphics Path.

```csharp
[C#]

static void Main(string[] args)
{
    using (var image = (TiffImage)Image.Load("Bottle.tif"))
    {
        // Create rectangular Figure for GraphicsPath
        var figure = new Figure();
        figure.AddShape(CreateBezierShape(100f, 100f, 500f, 100f, 500f, 1000f, 100f, 1000f));

        // Create GraphicsPath using our Figure
        var graphicsPath = new GraphicsPath();
        graphicsPath.AddFigure(figure);

        // Set PathResources using GraphicsPath
        var pathResouze = PathResourceConverter.FromGraphicsPath(graphicsPath, image.Size);
        image.ActiveFrame.PathResources = new List<PathResource>(pathResouze);

        // Save the image
        image.Save("BottleWithRectanglePath.tif");
    }
}

private static BezierShape CreateBezierShape(params float[] coordinates)
{
    var bezierPoints = CoordinatesToBezierPoints(coordinates).ToArray();
    return new BezierShape(bezierPoints, true);
}

private static IEnumerable<PointF> CoordinatesToBezierPoints(float[] coordinates)
{
    for (var coordinateIndex = 0; coordinateIndex < coordinates.Length; coordinateIndex += 2)
        for (var index = 0; index < 3; index++)
            yield return new PointF(coordinates[coordinateIndex], coordinates[coordinateIndex + 1]);
}
```

### See Also

* class [RasterCachedMultipageImage](../../aspose.imaging/rastercachedmultipageimage/)
* interface [IMultipageImageExt](../../aspose.imaging/imultipageimageext/)
* namespace [Aspose.Imaging.FileFormats.Tiff](../../aspose.imaging.fileformats.tiff/)
* assembly [Aspose.Imaging](../../)


