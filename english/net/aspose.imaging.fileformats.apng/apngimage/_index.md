---
title: Class ApngImage
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Apng.ApngImage class. The API for Animated PNG Animated Portable Network Graphics image file format is a versatile solution for developers looking to integrate animated content into their applications. This API offers extensive control over frame settings allowing users to define framespecific parameters including loop duration and PNG file settings. With this featurerich tool you can effortlessly manage and optimize the display of APNG images import and export images enhancing the dynamic and interactive aspects of your applications
type: docs
weight: 1350
url: /net/aspose.imaging.fileformats.apng/apngimage/
---
## ApngImage class

The API for Animated PNG (Animated Portable Network Graphics) image file format is a versatile solution for developers looking to integrate animated content into their applications. This API offers extensive control over frame settings, allowing users to define frame-specific parameters, including loop duration and PNG file settings. With this feature-rich tool, you can effortlessly manage and optimize the display of APNG images, import and export images, enhancing the dynamic and interactive aspects of your applications.

```csharp
public sealed class ApngImage : RasterCachedMultipageImage, IMultipageImageExt
```

## Constructors

| Name | Description |
| --- | --- |
| [ApngImage](apngimage/)(ApngOptions, int, int) | Begin working with the `ApngImage` class by initializing a new instance effortlessly. Perfect for developers seeking to start using ApngImage objects quickly and efficiently in their projects. |

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
| [DefaultFrameTime](../../aspose.imaging.fileformats.apng/apngimage/defaultframetime/) { get; set; } | Easily adjust the default frame duration for creating new frames with this flexible property. Perfect for developers seeking to customize frame timing efficiently in their animations. |
| [Disposed](../../aspose.imaging/disposableobject/disposed/) { get; } | Gets a value indicating whether this instance is disposed. |
| [ExifData](../../aspose.imaging/image/exifdata/) { get; set; } | Gets or sets the Exif data. |
| override [FileFormat](../../aspose.imaging.fileformats.apng/apngimage/fileformat/) { get; } | Quickly access information about the file format with this convenient property. Ideal for developers who need to retrieve details about the format of their Apng files easily. |
| override [HasAlpha](../../aspose.imaging/rastercachedmultipageimage/hasalpha/) { get; } | Gets a value indicating whether this instance has alpha. |
| virtual [HasBackgroundColor](../../aspose.imaging/image/hasbackgroundcolor/) { get; set; } | Gets or sets a value indicating whether image has background color. |
| override [HasTransparentColor](../../aspose.imaging/rastercachedmultipageimage/hastransparentcolor/) { get; } | Gets a value indicating whether image has transparent color. |
| override [Height](../../aspose.imaging/rastercachedmultipageimage/height/) { get; } | Gets the image height. |
| virtual [HorizontalResolution](../../aspose.imaging/rasterimage/horizontalresolution/) { get; set; } | Gets or sets the horizontal resolution, in pixels per inch, of this [`RasterImage`](../../aspose.imaging/rasterimage/). |
| override [ImageOpacity](../../aspose.imaging/rastercachedmultipageimage/imageopacity/) { get; } | Gets opacity of this image. |
| [Interlaced](../../aspose.imaging.fileformats.apng/apngimage/interlaced/) { get; } | Quickly determine whether this [`PngImage`](../../aspose.imaging.fileformats.png/pngimage/) object is interlaced with this convenient property. Ideal for developers needing to check the interlacing status of PNG images easily. |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor/) { get; set; } | Gets or sets the interrupt monitor. |
| override [IsCached](../../aspose.imaging/rastercachedmultipageimage/iscached/) { get; } | Gets a value indicating whether image data is cached currently. |
| [IsRawDataAvailable](../../aspose.imaging/rasterimage/israwdataavailable/) { get; } | Gets a value indicating whether raw data loading is available. |
| override [Metadata](../../aspose.imaging/rastercachedmultipageimage/metadata/) { get; } | Gets or sets XMP data from frame. |
| [NumPlays](../../aspose.imaging.fileformats.apng/apngimage/numplays/) { get; set; } | Effortlessly control the number of times your animation loops with this versatile property. Perfect for developers seeking precise control over animation behavior, with support for infinite looping in case of the value equals to 0. |
| override [PageCount](../../aspose.imaging.fileformats.apng/apngimage/pagecount/) { get; } | Retrieve the total number of pages in your image file effortlessly with this property. Ideal for developers needing quick access to page count information. |
| virtual [PageExportingAction](../../aspose.imaging/rastercachedmultipageimage/pageexportingaction/) { get; set; } | Gets or sets the page exporting action. Please note that setting this method will automatically release page resources after it is executed. It will be executed just before each page is saved. |
| override [Pages](../../aspose.imaging.fileformats.apng/apngimage/pages/) { get; } | Effortlessly access the pages of your image with this convenient property. Perfect for developers seeking quick and easy access to individual pages for manipulation. |
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
| [AddFrame](../../aspose.imaging.fileformats.apng/apngimage/addframe/#addframe)() | Easily append a new frame to the end of your frame collection with this straightforward method. Ideal for developers looking to expand their frame collection dynamically for animations with multi-frame images. A new frame will be created according to the size of the current image. |
| [AddFrame](../../aspose.imaging.fileformats.apng/apngimage/addframe/#addframe_1)(RasterImage) | Effortlessly expand your frame collection by adding a new frame to the end with this intuitive method. Perfect for developers seeking to enhance their animations of multi-frame images dynamically. The contents of the new frame will be filled from the specified image. |
| [AddFrame](../../aspose.imaging.fileformats.apng/apngimage/addframe/#addframe_2)(RasterImage, uint) | Expand your frame collection seamlessly by appending a new frame to the with this intuitive method. Ideal for developers looking to enrich their animations of multi-frame images. The contents of the new frame will be filled from the specified image. |
| [AddPage](../../aspose.imaging.fileformats.apng/apngimage/addpage/)(RasterImage) | Add a new page to the image effortlessly with this intuitive method. Perfect for developers seeking to expand the content of their image files dynamically. |
| override [AdjustBrightness](../../aspose.imaging.fileformats.apng/apngimage/adjustbrightness/)(int) | Easily adjust the *brightness* of the image with this intuitive method, using the specified brightness parameter. Ideal for developers seeking to enhance or dim the overall brightness of images dynamically. |
| override [AdjustContrast](../../aspose.imaging.fileformats.apng/apngimage/adjustcontrast/)(float) | Enhance the contrast of the [`Image`](../../aspose.imaging/image/) to make details stand out with this intuitive method. Ideal for developers seeking to improve the visual clarity and impact of their images dynamically. |
| override [AdjustGamma](../../aspose.imaging.fileformats.apng/apngimage/adjustgamma/#adjustgamma)(float) | Apply gamma correction to the image using a floating-point coefficient with this intuitive method. Ideal for developers seeking precise color control in their images. |
| override [AdjustGamma](../../aspose.imaging.fileformats.apng/apngimage/adjustgamma/#adjustgamma_1)(float, float, float) | Perform gamma correction on the image separately for the red, green, and blue channels using individual coefficients with this intuitive method. Ideal for developers seeking to fine-tune color balance and enhance the visual quality of their images. |
| override [AnalyzePercentageDigitalSignature](../../aspose.imaging/rastercachedmultipageimage/analyzepercentagedigitalsignature/)(string) | Calculates the percentage similarity between the extracted data and the original password. |
| override [AutoBrightnessContrast](../../aspose.imaging/rastercachedimage/autobrightnesscontrast/)() | Performs automatic adaptive brightness and contrast normalization for the entire image. |
| [AutoRotate](../../aspose.imaging/rasterimage/autorotate/)() | Automatically rotates the image based on orientation data extracted from Exif metadata. This method ensures that images are displayed in the correct orientation, enhancing user experience and eliminating the need for manual adjustments. By analyzing Exif information, the image is rotated accordingly, providing a seamless viewing experience across different platforms and devices. This automated rotation process simplifies image handling and improves overall usability, especially when dealing with large batches of images with varying orientations. |
| override [BinarizeBradley](../../aspose.imaging/rastercachedmultipageimage/binarizebradley/)(double) | Binarization of an image using Bradley's adaptive thresholding algorithm using the integral image thresholding |
| override [BinarizeBradley](../../aspose.imaging.fileformats.apng/apngimage/binarizebradley/#binarizebradley_1)(double, int) | Binarization of an image using Bradley's adaptive thresholding algorithm using the integral image thresholding |
| override [BinarizeFixed](../../aspose.imaging.fileformats.apng/apngimage/binarizefixed/)(byte) | Effortlessly binarize the image using a predefined threshold with this intuitive method. Ideal for developers seeking to convert images into binary form, simplifying them for further processing or analysis. |
| override [BinarizeOtsu](../../aspose.imaging.fileformats.apng/apngimage/binarizeotsu/)() | Perform binarization on the image using Otsu thresholding with this intuitive method. Ideal for developers seeking to automatically determine the optimal threshold for converting images into binary form, enhancing their clarity and suitability for further analysis. |
| [Blend](../../aspose.imaging/rasterimage/blend/)(Point, RasterImage, byte) | Blends this image instance with the *overlay* image. |
| override [Blend](../../aspose.imaging/rastercachedmultipageimage/blend/)(Point, RasterImage, Rectangle, byte) | Blends this image instance with the *overlay* image. |
| override [CacheData](../../aspose.imaging/rastercachedmultipageimage/cachedata/)() | Caches the data private. |
| [CanSave](../../aspose.imaging/image/cansave/)(ImageOptionsBase) | Determines whether image can be saved to the specified file format represented by the passed save options. |
| override [Crop](../../aspose.imaging.fileformats.apng/apngimage/crop/#crop)(Rectangle) | Effortlessly crop the image to focus on specific areas with this intuitive method. Perfect for developers seeking to refine the composition of their images dynamically. |
| override [Crop](../../aspose.imaging.fileformats.apng/apngimage/crop/#crop_1)(int, int, int, int) | Crop the image while adjusting shifts seamlessly with this intuitive method. Ideal for developers seeking precise control over the cropping process to focus on specific areas of their Apng images. |
| [Dispose](../../aspose.imaging/disposableobject/dispose/)() | Disposes the current instance. |
| [Dither](../../aspose.imaging/rasterimage/dither/)(DitheringMethod, int) | Performs dithering on the current image. |
| override [Dither](../../aspose.imaging.fileformats.apng/apngimage/dither/#dither_1)(DitheringMethod, int, IColorPalette) | Easily apply dithering effects to the current image with this intuitive method. Ideal for developers looking to add texture or reduce color banding in their images. |
| override [EmbedDigitalSignature](../../aspose.imaging/rastercachedmultipageimage/embeddigitalsignature/)(string) | Embed digital sign based on provided password into each page of the image. |
| override [Filter](../../aspose.imaging.fileformats.apng/apngimage/filter/)(Rectangle, FilterOptionsBase) | Effortlessly apply filters to the specified rectangle of the image with this intuitive method. Perfect for developers seeking to enhance or modify specific areas. |
| [GetArgb32Pixel](../../aspose.imaging/rasterimage/getargb32pixel/)(int, int) | Gets an image 32-bit ARGB pixel. |
| [GetDefaultArgb32Pixels](../../aspose.imaging/rasterimage/getdefaultargb32pixels/)(Rectangle) | Gets the default 32-bit ARGB pixels array. |
| override [GetDefaultOptions](../../aspose.imaging.fileformats.apng/apngimage/getdefaultoptions/)(object[]) | Retrieve the default options effortlessly with this straightforward method. Ideal for developers seeking quick access to default Apng image settings. |
| [GetDefaultPixels](../../aspose.imaging/rasterimage/getdefaultpixels/)(Rectangle, IPartialArgb32PixelLoader) | Gets the default pixels array using partial pixel loader. |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata/)(Rectangle, RawDataSettings) | Gets the default raw data array. |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata/)(Rectangle, IPartialRawDataLoader, RawDataSettings) | Gets the default raw data array using partial pixel loader. |
| override [GetModifyDate](../../aspose.imaging.fileformats.apng/apngimage/getmodifydate/)(bool) | Quickly obtain the date and time when the resource image was last modified with this user-friendly method. Ideal for developers needing to track changes and manage resources effectively. |
| override [GetOriginalOptions](../../aspose.imaging.fileformats.apng/apngimage/getoriginaloptions/)() | Retrieve options based on the original file settings effortlessly with this intuitive method. Perfect for developers seeking to access and utilize settings that align with the characteristics of the original file. This can be helpful to keep bit-depth and other parameters of the original image unchanged. For example, if we load a black-white PNG image with 1 bit per pixel and then save it using the [`Save`](../../aspose.imaging/datastreamsupporter/save/) method, the output PNG image with 8-bit per pixel will be produced. To avoid it and save PNG image with 1-bit per pixel, use this method to get corresponding saving options and pass them to the [`Save`](../../aspose.imaging/image/save/) method as the second parameter. |
| [GetPixel](../../aspose.imaging/rasterimage/getpixel/)(int, int) | Gets an image pixel. |
| override [GetSerializedStream](../../aspose.imaging/rastercachedmultipageimage/getserializedstream/)(ImageOptionsBase, Rectangle, out int) | Converts to aps. |
| [GetSkewAngle](../../aspose.imaging/rasterimage/getskewangle/)() | Gets the skew angle. This method is applicable to scanned text documents, to determine the skew angle when scanning. |
| override [Grayscale](../../aspose.imaging.fileformats.apng/apngimage/grayscale/)() | Easily transform the image into its grayscale representation with this intuitive method. Ideal for developers seeking to convert color images to grayscale, simplifying their visualization or analysis processes. |
| [InsertFrame](../../aspose.imaging.fileformats.apng/apngimage/insertframe/#insertframe)(int) | Effortlessly insert a new frame into your frame collection at the specified with this intuitive method. Ideal for developers seeking precise control over the arrangement of frames in their animations of multi-frame images. A new frame will be created according to the size of the current image. |
| [InsertFrame](../../aspose.imaging.fileformats.apng/apngimage/insertframe/#insertframe_1)(int, RasterImage) | Inserts new frame into the own frame collection at the specified index. The contents of the new frame will be filled from the specified image. |
| [InsertFrame](../../aspose.imaging.fileformats.apng/apngimage/insertframe/#insertframe_2)(int, RasterImage, uint) | Inserts new frame into the own frame collection at the specified index. The contents of the new frame will be filled from the specified image. |
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
| [PopFrameAt](../../aspose.imaging.fileformats.apng/apngimage/popframeat/)(int) | Remove and retrieve the frame at the specified index from your frame collection with this intuitive method. Perfect for developers seeking efficient management of frames in their animations. |
| [ReadArgb32ScanLine](../../aspose.imaging/rasterimage/readargb32scanline/)(int) | Reads the whole scan line by the specified scan line index. |
| [ReadScanLine](../../aspose.imaging/rasterimage/readscanline/)(int) | Reads the whole scan line by the specified scan line index. |
| [RemoveAllFrames](../../aspose.imaging.fileformats.apng/apngimage/removeallframes/)() | Clear your frame collection by removing all frames with this intuitive method. Ideal for developers seeking to reset or refresh their animations. |
| [RemoveFrameAt](../../aspose.imaging.fileformats.apng/apngimage/removeframeat/)(int) | Remove the frame at the specified index from your frame collection seamlessly with this method. Perfect for developers seeking streamlined management of frames in their multi-frame images. The frame to be deleted will be disposed. |
| override [RemoveMetadata](../../aspose.imaging/rasterimage/removemetadata/)() | Removes this image instance metadata by setting this [`XmpData`](../../aspose.imaging.xmp/ihasxmpdata/xmpdata/) value to `null`. |
| [ReplaceColor](../../aspose.imaging/rasterimage/replacecolor/)(Color, byte, Color) | Replaces one color to another with allowed difference and preserves original alpha value to save smooth edges. |
| override [ReplaceColor](../../aspose.imaging/rastercachedmultipageimage/replacecolor/)(int, byte, int) | Replaces one color to another with allowed difference and preserves original alpha value to save smooth edges. |
| [ReplaceNonTransparentColors](../../aspose.imaging/rasterimage/replacenontransparentcolors/)(Color) | Replaces all non-transparent colors with new color and preserves original alpha value to save smooth edges. Note: if you use it on images without transparency, all colors will be replaced with a single one. |
| override [ReplaceNonTransparentColors](../../aspose.imaging/rastercachedmultipageimage/replacenontransparentcolors/)(int) | Replaces all non-transparent colors with new color and preserves original alpha value to save smooth edges. Note: if you use it on images without transparency, all colors will be replaced with a single one. |
| [ResetDefaultImage](../../aspose.imaging.fileformats.apng/apngimage/resetdefaultimage/)() | Remove a previously set default image with this intuitive method. Ideal for developers seeking to reset or clear the default image in their animation. After this, the default image is the first frame in the own frame collection (it cannot be deleted using this method). |
| [Resize](../../aspose.imaging/image/resize/)(int, int) | Resizes the image. The default NearestNeighbourResample is used. |
| override [Resize](../../aspose.imaging.fileformats.apng/apngimage/resize/#resize_1)(int, int, ImageResizeSettings) | Resizes the image. |
| override [Resize](../../aspose.imaging.fileformats.apng/apngimage/resize/#resize_2)(int, int, ResizeType) | Resize the image seamlessly with this intuitive method. Perfect for developers seeking to adjust the dimensions of their images dynamically. |
| [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally/)(int) | Resizes the height proportionally. The default NearestNeighbourResample is used. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally/)(int, ImageResizeSettings) | Resizes the height proportionally. |
| override [ResizeHeightProportionally](../../aspose.imaging.fileformats.apng/apngimage/resizeheightproportionally/#resizeheightproportionally_2)(int, ResizeType) | Effortlessly adjust the height of your image while maintaining its proportions with this intuitive method. Perfect for developers looking to resize images dynamically while preserving their aspect ratio. |
| [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally/)(int) | Resizes the width proportionally. The default NearestNeighbourResample is used. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally/)(int, ImageResizeSettings) | Resizes the width proportionally. |
| override [ResizeWidthProportionally](../../aspose.imaging.fileformats.apng/apngimage/resizewidthproportionally/#resizewidthproportionally_2)(int, ResizeType) | Proportionally resize the width of the image effortlessly with this intuitive method. Ideal for developers seeking to maintain the aspect ratio of their images while adjusting their dimensions. |
| override [Rotate](../../aspose.imaging/rasterimage/rotate/)(float) | Rotate image around the center. |
| override [Rotate](../../aspose.imaging.fileformats.apng/apngimage/rotate/#rotate_1)(float, bool, Color) | Rotate the image around its center effortlessly with this intuitive method. Perfect for developers seeking to adjust the orientation of their images dynamically. |
| override [RotateFlip](../../aspose.imaging.fileformats.apng/apngimage/rotateflip/)(RotateFlipType) | Effortlessly manipulate the active frame by rotating, flipping, or both with this intuitive method. Ideal for developers seeking to customize image frame orientations. |
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
| [SetDefaultImage](../../aspose.imaging.fileformats.apng/apngimage/setdefaultimage/)(RasterImage) | Set the specified raster image as the default image for the current animation effortlessly with this method. Perfect for developers seeking to customize the default image in their animations. |
| override [SetPalette](../../aspose.imaging/rasterimage/setpalette/)(IColorPalette, bool) | Sets the image palette. |
| [SetPixel](../../aspose.imaging/rasterimage/setpixel/)(int, int, Color) | Sets an image pixel for the specified position. |
| virtual [SetResolution](../../aspose.imaging/rasterimage/setresolution/)(double, double) | Sets the resolution for this [`RasterImage`](../../aspose.imaging/rasterimage/). |
| virtual [ToBitmap](../../aspose.imaging/rasterimage/tobitmap/)() | Converts raster image to the bitmap. This method is not supported in versions from .Net7.0 and higher |
| virtual [TrySetMetadata](../../aspose.imaging/image/trysetmetadata/)(IImageMetadataFormat) | Tries to set a *metadata* instance, if this [`Image`](../../aspose.imaging/image/) instance supports and implements [`IImageMetadataFormat`](../../aspose.imaging.metadata/iimagemetadataformat/) type. |
| [WriteArgb32ScanLine](../../aspose.imaging/rasterimage/writeargb32scanline/)(int, int[]) | Writes the whole scan line to the specified scan line index. |
| [WriteScanLine](../../aspose.imaging/rasterimage/writescanline/)(int, Color[]) | Writes the whole scan line to the specified scan line index. |

## Examples

The following example shows how to export apng APNG file format from other non-animated multi-page format.

```csharp
[C#]

using Aspose.Imaging;
using Aspose.Imaging.ImageOptions;

using (Image image = Image.Load("img4.tif")) {
    // Setting up the default frame duration
    image.Save("img4.tif.500ms.png", new ApngOptions() { DefaultFrameTime = 500 }); // 500 ms
    image.Save("img4.tif.250ms.png", new ApngOptions() { DefaultFrameTime = 250 }); // 250 ms
}
```

The following example shows how to export to APNG file format.

```csharp
[C#]

using Aspose.Imaging;
using Aspose.Imaging.ImageOptions;

using (Image image = Image.Load("Animation1.webp")) {
    // Export to APNG animation with unlimited animation cycles as default
    image.Save("Animation1.webp.png", new ApngOptions());
    // Setting up animation cycles
    image.Save("Animation2.webp.png", new ApngOptions() { NumPlays = 5 }); // 5 cycles
}
```

The following example shows how to create APNG image from another raster single-page image.

```csharp
[C#]

using Aspose.Imaging;
using Aspose.Imaging.ImageOptions;
using Aspose.Imaging.FileFormats.Apng;

const int AnimationDuration = 1000; // 1 s
const int FrameDuration = 70; // 70 ms
using (RasterImage sourceImage = (RasterImage)Image.Load("not_animated.png"))
{
    ApngOptions createOptions = new ApngOptions
    {
        Source = new FileCreateSource("raster_animation.png", false),
        DefaultFrameTime = (uint)FrameDuration,
        ColorType = PngColorType.TruecolorWithAlpha,
    };

    using (ApngImage apngImage = (ApngImage)Image.Create(
        createOptions,
        sourceImage.Width,
        sourceImage.Height))
    {
        // It is possible to set image default frame time there: apngImage.DefaultFrameTime = (uint)FrameDuration;

        int numOfFrames = AnimationDuration / FrameDuration;
        int numOfFrames2 = numOfFrames / 2;

        // Cleaning because the image contains one frame by default
        apngImage.RemoveAllFrames();

        // add first frame
        apngImage.AddFrame(sourceImage);

        // add intermediate frames
        for (int frameIndex = 1; frameIndex < numOfFrames - 1; ++frameIndex)
        {
            apngImage.AddFrame(sourceImage);
            ApngFrame lastFrame = (ApngFrame)apngImage.Pages[apngImage.PageCount - 1];
            float gamma = frameIndex >= numOfFrames2 ? numOfFrames - frameIndex - 1 : frameIndex;
            lastFrame.AdjustGamma(gamma);
        }

        // add last frame
        apngImage.AddFrame(sourceImage);

        apngImage.Save();
    }
}
```

### See Also

* class [RasterCachedMultipageImage](../../aspose.imaging/rastercachedmultipageimage/)
* interface [IMultipageImageExt](../../aspose.imaging/imultipageimageext/)
* namespace [Aspose.Imaging.FileFormats.Apng](../../aspose.imaging.fileformats.apng/)
* assembly [Aspose.Imaging](../../)


