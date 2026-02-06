---
title: Class GifImage
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Gif.GifImage class. The API for Graphical Interchange Format GIF image file provides developers with versatile tools for processing compressed raster images and animated GIFs. Offering features like XMP metadata handling color palette settings background and transparent color control opacity settings resize crop filter application gamma corrections contrast adjustment grayscale transformation and conversion to other formats. This API empowers seamless manipulation and enhancement of GIF images for a wide range of applications
type: docs
weight: 6800
url: /net/aspose.imaging.fileformats.gif/gifimage/
---
## GifImage class

The API for Graphical Interchange Format (GIF) image file provides developers with versatile tools for processing compressed raster images and animated GIFs. Offering features like XMP metadata handling, color palette settings, background and transparent color control, opacity settings, resize, crop, filter application, gamma corrections, contrast adjustment, grayscale transformation, and conversion to other formats. This API empowers seamless manipulation and enhancement of GIF images for a wide range of applications.

```csharp
public sealed class GifImage : RasterCachedMultipageImage, IMultipageImageExt
```

## Constructors

| Name | Description |
| --- | --- |
| [GifImage](gifimage/#constructor)(GifFrameBlock) | Crafting GIF images becomes effortless with the `GifImage` constructor. With just the firstFrame parameter, it enters in a world of dynamic visual communication. |
| [GifImage](gifimage/#constructor_1)(GifFrameBlock, IColorPalette) | Initiate a new `GifImage` object with specified parameters for the first frame and global palette. Start managing GIF images swiftly, ensuring accurate representation with customizable settings for optimal results. |
| [GifImage](gifimage/#constructor_2)(GifFrameBlock, IColorPalette, bool, byte, byte, byte, bool) | Get started effortlessly with the `GifImage` constructor. With this simple method, you can dive into creating animated GIFs with ease. Just supply the firstFrame, globalPalette, paletteColorResolution, aspectRatio, and other parameters, and you're ready to bring your visuals to life. |

## Properties

| Name | Description |
| --- | --- |
| [ActiveFrame](../../aspose.imaging.fileformats.gif/gifimage/activeframe/) { get; set; } | Manage and manipulate frames with this property, enabling smooth navigation and modification of the active frame within the GIF image. |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette/) { get; set; } | Gets or sets a value indicating whether automatic adjust palette. |
| override [BackgroundColor](../../aspose.imaging.fileformats.gif/gifimage/backgroundcolor/) { get; set; } | Manage the background color of the GIF image with this property. You can set or retrieve the background color to ensure consistency and enhance visual appeal. |
| [BackgroundColorIndex](../../aspose.imaging.fileformats.gif/gifimage/backgroundcolorindex/) { get; set; } | Control the background color index of the GIF image using this property. Set or retrieve the index to maintain consistency or achieve desired visual effects. |
| override [BitsPerPixel](../../aspose.imaging/rastercachedmultipageimage/bitsperpixel/) { get; } | Gets the image bits per pixel count. |
| [Blocks](../../aspose.imaging.fileformats.gif/gifimage/blocks/) { get; } | Gain access to the GIF blocks seamlessly with this property, facilitating easy retrieval and manipulation of the image's underlying data structures. |
| [Bounds](../../aspose.imaging/image/bounds/) { get; } | Gets the image bounds. |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint/) { get; set; } | Gets or sets the buffer size hint which is defined max allowed size for all internal buffers. |
| [Container](../../aspose.imaging/image/container/) { get; } | Gets the [`Image`](../../aspose.imaging/image/) container. |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer/) { get; } | Gets the object's data stream. |
| [Disposed](../../aspose.imaging/disposableobject/disposed/) { get; } | Gets a value indicating whether this instance is disposed. |
| [ExifData](../../aspose.imaging/image/exifdata/) { get; set; } | Gets or sets the Exif data. |
| override [FileFormat](../../aspose.imaging.fileformats.gif/gifimage/fileformat/) { get; } | Retrieve the file format effortlessly with this property. It's your go-to source for identifying the format of your files. Seamlessly integrated into your workflow, it provides vital information without any hassle. |
| override [HasAlpha](../../aspose.imaging/rastercachedmultipageimage/hasalpha/) { get; } | Gets a value indicating whether this instance has alpha. |
| override [HasBackgroundColor](../../aspose.imaging.fileformats.gif/gifimage/hasbackgroundcolor/) { get; } | This property determines whether the GIF image contains a background color. If true, it indicates that the image includes a background color. |
| [HasTrailer](../../aspose.imaging.fileformats.gif/gifimage/hastrailer/) { get; set; } | Manage the presence of a trailer in your GIF files with this property. Whether you need to check if a trailer exists or set its presence, this property simplifies the process. Keep your GIF files structured and compliant with this intuitive feature. |
| override [HasTransparentColor](../../aspose.imaging.fileformats.gif/gifimage/hastransparentcolor/) { get; set; } | Determine whether the active frame of the GIF image includes a transparent color. This property provides a convenient way to check for transparency within the image. |
| override [Height](../../aspose.imaging/rastercachedmultipageimage/height/) { get; } | Gets the image height. |
| virtual [HorizontalResolution](../../aspose.imaging/rasterimage/horizontalresolution/) { get; set; } | Gets or sets the horizontal resolution, in pixels per inch, of this [`RasterImage`](../../aspose.imaging/rasterimage/). |
| override [ImageOpacity](../../aspose.imaging.fileformats.gif/gifimage/imageopacity/) { get; } | Retrieve the opacity of the active frame within the image, offering insight into its transparency level. This property is particularly useful for understanding the degree of transparency or opaqueness of the active frame in the image. |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor/) { get; set; } | Gets or sets the interrupt monitor. |
| override [IsCached](../../aspose.imaging/rastercachedmultipageimage/iscached/) { get; } | Gets a value indicating whether image data is cached currently. |
| [IsInterlaced](../../aspose.imaging.fileformats.gif/gifimage/isinterlaced/) { get; } | Determines if the image is interlaced, impacting its display during loading. This property offers insight into the image's rendering behavior, essential for optimizing loading strategies and enhancing overall viewing experience. |
| [IsPaletteSorted](../../aspose.imaging.fileformats.gif/gifimage/ispalettesorted/) { get; set; } | Control the sorting of the palette in your GIF images using this property. Whether you need to check if the palette is sorted or set the sorting behavior, this property provides a straightforward way to manage the palette organization in your GIF files. |
| [IsRawDataAvailable](../../aspose.imaging/rasterimage/israwdataavailable/) { get; } | Gets a value indicating whether raw data loading is available. |
| [LoopsCount](../../aspose.imaging.fileformats.gif/gifimage/loopscount/) { get; set; } | Retrieve the loop count effortlessly with this property. If your GIF image includes loop information, this property gives you quick access to the loop count, enabling you to seamlessly manage looping behavior in your GIF files. |
| override [Metadata](../../aspose.imaging/rastercachedmultipageimage/metadata/) { get; } | Gets or sets XMP data from frame. |
| override [PageCount](../../aspose.imaging.fileformats.gif/gifimage/pagecount/) { get; } | Retrieve the total number of pages contained within the image with this straightforward property. Ideal for quickly assessing the extent of the image content. |
| virtual [PageExportingAction](../../aspose.imaging/rastercachedmultipageimage/pageexportingaction/) { get; set; } | Gets or sets the page exporting action. Please note that setting this method will automatically release page resources after it is executed. It will be executed just before each page is saved. |
| override [Pages](../../aspose.imaging.fileformats.gif/gifimage/pages/) { get; } | Gain access to the pages within the image through this convenient property, allowing seamless navigation and manipulation of individual pages as needed. |
| [Palette](../../aspose.imaging/image/palette/) { get; set; } | Gets or sets the color palette. The color palette is not used when pixels are represented directly. |
| [PaletteColorResolutionBits](../../aspose.imaging.fileformats.gif/gifimage/palettecolorresolutionbits/) { get; set; } | Manage the palette color resolution of your GIF images with this property. Adjust the number of bits used to represent colors in the palette, providing fine control over color depth and image quality. |
| [PixelAspectRatio](../../aspose.imaging.fileformats.gif/gifimage/pixelaspectratio/) { get; set; } | Manage the pixel aspect ratio of the GIF image with this property. Set or retrieve the aspect ratio to ensure accurate rendering and maintain visual fidelity. |
| virtual [PremultiplyComponents](../../aspose.imaging/rasterimage/premultiplycomponents/) { get; set; } | Gets or sets a value indicating whether the image components must be premultiplied. |
| [RawCustomColorConverter](../../aspose.imaging/rasterimage/rawcustomcolorconverter/) { get; set; } | Gets or sets the custom color converter |
| virtual [RawDataFormat](../../aspose.imaging/rasterimage/rawdataformat/) { get; } | Gets the raw data format. |
| [RawDataSettings](../../aspose.imaging/rasterimage/rawdatasettings/) { get; } | Gets the current raw data settings. Note when using these settings the data loads without conversion. |
| [RawFallbackIndex](../../aspose.imaging/rasterimage/rawfallbackindex/) { get; set; } | Gets or sets the fallback index to use when palette index is out of bounds |
| [RawIndexedColorConverter](../../aspose.imaging/rasterimage/rawindexedcolorconverter/) { get; set; } | Gets or sets the indexed color converter |
| virtual [RawLineSize](../../aspose.imaging/rasterimage/rawlinesize/) { get; } | Gets the raw line size in bytes. |
| [Size](../../aspose.imaging/image/size/) { get; } | Gets the image size. |
| override [TransparentColor](../../aspose.imaging.fileformats.gif/gifimage/transparentcolor/) { get; } | Retrieve the transparent color of the active frame in the GIF image. This property allows you to access the specific color that has been designated as transparent within the currently active frame. |
| virtual [UpdateXmpData](../../aspose.imaging/rasterimage/updatexmpdata/) { get; set; } | Gets or sets a value indicating whether to update the XMP metadata. |
| override [UsePalette](../../aspose.imaging/rasterimage/usepalette/) { get; } | Gets a value indicating whether the image palette is used. |
| virtual [UseRawData](../../aspose.imaging/rasterimage/userawdata/) { get; set; } | Gets or sets a value indicating whether to use raw data loading when the raw data loading is available. |
| virtual [VerticalResolution](../../aspose.imaging/rasterimage/verticalresolution/) { get; set; } | Gets or sets the vertical resolution, in pixels per inch, of this [`RasterImage`](../../aspose.imaging/rasterimage/). |
| override [Width](../../aspose.imaging/rastercachedmultipageimage/width/) { get; } | Gets the image width. |
| [XmpData](../../aspose.imaging/image/xmpdata/) { get; set; } | Gets or sets the Xmp data. |

## Methods

| Name | Description |
| --- | --- |
| [AddBlock](../../aspose.imaging.fileformats.gif/gifimage/addblock/)(IGifBlock) | Adding a new GIF block allows you to include additional data within the image. This method enables you to append custom blocks to the GIF image, which can contain various types of information. |
| [AddPage](../../aspose.imaging.fileformats.gif/gifimage/addpage/)(RasterImage) | Incorporate a new page seamlessly into the existing image, enhancing its content and expanding its scope. This method augment image collections with additional content, fostering creativity and flexibility in image management and composition. |
| override [AdjustBrightness](../../aspose.imaging.fileformats.gif/gifimage/adjustbrightness/)(int) | Adjusts the brightness of the image according to the specified *brightness* parameter. This method modifies the brightness of the entire image uniformly, enhancing or reducing the overall luminance to achieve the desired effect. |
| override [AdjustContrast](../../aspose.imaging.fileformats.gif/gifimage/adjustcontrast/)(float) | Adjusts the contrast of the image, enhancing or reducing the difference in brightness between pixels. This method modifies the image's overall tonal range, making darker areas darker and brighter areas brighter to improve visual clarity and detail. |
| override [AdjustGamma](../../aspose.imaging.fileformats.gif/gifimage/adjustgamma/#adjustgamma)(float) | Enhance image quality by applying gamma correction. This method adjusts the color gamma of the image to achieve optimal visual clarity. It modifies the gamma value of each pixel, resulting in improved color rendition and overall image appearance. |
| override [AdjustGamma](../../aspose.imaging.fileformats.gif/gifimage/adjustgamma/#adjustgamma_1)(float, float, float) | Gamma-correction of an image applies a nonlinear adjustment to the pixel values, enhancing or reducing brightness based on the specified coefficients for the red, green, and blue channels. This method helps to fine-tune the color balance and luminance of the image, improving its overall appearance and visual quality. |
| override [AnalyzePercentageDigitalSignature](../../aspose.imaging/rastercachedmultipageimage/analyzepercentagedigitalsignature/)(string) | Calculates the percentage similarity between the extracted data and the original password. |
| override [AutoBrightnessContrast](../../aspose.imaging/rastercachedimage/autobrightnesscontrast/)() | Performs automatic adaptive brightness and contrast normalization for the entire image. |
| [AutoRotate](../../aspose.imaging/rasterimage/autorotate/)() | Automatically rotates the image based on orientation data extracted from Exif metadata. This method ensures that images are displayed in the correct orientation, enhancing user experience and eliminating the need for manual adjustments. By analyzing Exif information, the image is rotated accordingly, providing a seamless viewing experience across different platforms and devices. This automated rotation process simplifies image handling and improves overall usability, especially when dealing with large batches of images with varying orientations. |
| override [BinarizeBradley](../../aspose.imaging.fileformats.gif/gifimage/binarizebradley/#binarizebradley)(double) | Binarization of an image using Bradley's adaptive thresholding algorithm with integral image thresholding is a method for converting a grayscale image into a binary image. This algorithm calculates a local threshold for each pixel based on the average intensity of the surrounding pixels within a specified window. By adaptively adjusting the threshold based on local pixel intensities, Bradley's method is effective at handling variations in lighting and contrast across the image. |
| override [BinarizeBradley](../../aspose.imaging/rastercachedmultipageimage/binarizebradley/)(double, int) | Binarization of an image using Bradley's adaptive thresholding algorithm using the integral image thresholding |
| override [BinarizeFixed](../../aspose.imaging.fileformats.gif/gifimage/binarizefixed/)(byte) | Binarization of an image with a predefined threshold converts a grayscale or color image into a binary image, where each pixel is classified as either black or white based on whether its intensity value exceeds a specified threshold. |
| override [BinarizeOtsu](../../aspose.imaging.fileformats.gif/gifimage/binarizeotsu/)() | Binarization of an image with Otsu thresholding is a method used to automatically determine the optimal threshold value for converting a grayscale image into a binary image. The Otsu thresholding algorithm calculates the threshold that minimizes the intra-class variance of the pixel intensities in the two resulting classes (foreground and background). This technique is particularly useful when the optimal threshold value is unknown and needs to be determined adaptively based on the image's histogram. |
| [Blend](../../aspose.imaging/rasterimage/blend/)(Point, RasterImage, byte) | Blends this image instance with the *overlay* image. |
| override [Blend](../../aspose.imaging/rastercachedmultipageimage/blend/)(Point, RasterImage, Rectangle, byte) | Blends this image instance with the *overlay* image. |
| override [CacheData](../../aspose.imaging/rastercachedmultipageimage/cachedata/)() | Caches the data private. |
| [CanSave](../../aspose.imaging/image/cansave/)(ImageOptionsBase) | Determines whether image can be saved to the specified file format represented by the passed save options. |
| [ClearBlocks](../../aspose.imaging.fileformats.gif/gifimage/clearblocks/)() | Clearing all the GIF blocks removes any existing data stored within the image. This operation effectively resets the image to an empty state, removing any previously added blocks. Use this method when you need to start fresh with a clean slate for creating or modifying a GIF image. |
| override [Crop](../../aspose.imaging.fileformats.gif/gifimage/crop/#crop)(Rectangle) | Crop the image using a specified rectangle area. This operation removes the outer portion of the image, leaving only the selected region defined by the rectangle. |
| override [Crop](../../aspose.imaging/rastercachedmultipageimage/crop/)(int, int, int, int) | Crop image with shifts. |
| [Dispose](../../aspose.imaging/disposableobject/dispose/)() | Disposes the current instance. |
| [Dither](../../aspose.imaging/rasterimage/dither/)(DitheringMethod, int) | Performs dithering on the current image. |
| override [Dither](../../aspose.imaging.fileformats.gif/gifimage/dither/#dither_1)(DitheringMethod, int, IColorPalette) | Apply dithering to the current image. This process enhances image quality by reducing color banding and improving color transitions, resulting in a smoother appearance. |
| override [EmbedDigitalSignature](../../aspose.imaging/rastercachedmultipageimage/embeddigitalsignature/)(string) | Embed digital sign based on provided password into each page of the image. |
| override [Filter](../../aspose.imaging.fileformats.gif/gifimage/filter/)(Rectangle, FilterOptionsBase) | Apply a specific filter to the designated area of the image, enhancing its visual quality or altering its appearance as desired. This method selectively processes pixels within the defined rectangle, allowing for targeted adjustments to be made while preserving the integrity of the surrounding image data. |
| [GetArgb32Pixel](../../aspose.imaging/rasterimage/getargb32pixel/)(int, int) | Gets an image 32-bit ARGB pixel. |
| [GetDefaultArgb32Pixels](../../aspose.imaging/rasterimage/getdefaultargb32pixels/)(Rectangle) | Gets the default 32-bit ARGB pixels array. |
| virtual [GetDefaultOptions](../../aspose.imaging/image/getdefaultoptions/)(object[]) | Gets the default options. |
| [GetDefaultPixels](../../aspose.imaging/rasterimage/getdefaultpixels/)(Rectangle, IPartialArgb32PixelLoader) | Gets the default pixels array using partial pixel loader. |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata/)(Rectangle, RawDataSettings) | Gets the default raw data array. |
| [GetDefaultRawData](../../aspose.imaging/rasterimage/getdefaultrawdata/)(Rectangle, IPartialRawDataLoader, RawDataSettings) | Gets the default raw data array using partial pixel loader. |
| virtual [GetModifyDate](../../aspose.imaging/rasterimage/getmodifydate/)(bool) | Gets the date and time the resource image was last modified. |
| override [GetOriginalOptions](../../aspose.imaging.fileformats.gif/gifimage/getoriginaloptions/)() | Retrieve the original file settings-based options, crucial for maintaining fidelity and consistency in image processing and manipulation. This method allows seamless integration of file-specific parameters into subsequent operations, ensuring accurate rendition and adherence to the image's inherent characteristics. This can be helpful to keep bit-depth and other parameters of the original image unchanged. For example, if we load a black-white PNG image with 1 bit per pixel and then save it using the [`Save`](../../aspose.imaging/datastreamsupporter/save/) method, the output PNG image with 8-bit per pixel will be produced. To avoid it and save PNG image with 1-bit per pixel, use this method to get corresponding saving options and pass them to the [`Save`](../../aspose.imaging/image/save/) method as the second parameter. |
| [GetPixel](../../aspose.imaging/rasterimage/getpixel/)(int, int) | Gets an image pixel. |
| override [GetSerializedStream](../../aspose.imaging/rastercachedmultipageimage/getserializedstream/)(ImageOptionsBase, Rectangle, out int) | Converts to aps. |
| [GetSkewAngle](../../aspose.imaging/rasterimage/getskewangle/)() | Gets the skew angle. This method is applicable to scanned text documents, to determine the skew angle when scanning. |
| override [Grayscale](../../aspose.imaging.fileformats.gif/gifimage/grayscale/)() | The transformation of an image to its grayscale representation converts the color image into a grayscale version by removing color information while preserving luminance. This process simplifies the image to shades of gray, making it suitable for various applications such as printing, document processing, and grayscale analysis. |
| [InsertBlock](../../aspose.imaging.fileformats.gif/gifimage/insertblock/)(int, IGifBlock) | Inserting a new GIF block allows you to add custom data at a specific position within the image. This method enables you to place custom blocks at a desired location in the GIF image, providing flexibility in organizing and structuring the image data. |
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
| [OrderBlocks](../../aspose.imaging.fileformats.gif/gifimage/orderblocks/)() | Ordering the GIF blocks according to the GIF specification ensures proper GIF layout and compliance with the standard. This process involves arranging the blocks in the correct sequence as defined by the specification. Additionally, it may involve removing certain [`GifGraphicsControlBlock`](../../aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/) instances that are not necessary for the final layout. By adhering to the GIF specification, the resulting image will be correctly structured and compatible with GIF viewing applications. |
| [ReadArgb32ScanLine](../../aspose.imaging/rasterimage/readargb32scanline/)(int) | Reads the whole scan line by the specified scan line index. |
| [ReadScanLine](../../aspose.imaging/rasterimage/readscanline/)(int) | Reads the whole scan line by the specified scan line index. |
| [RemoveBlock](../../aspose.imaging.fileformats.gif/gifimage/removeblock/)(IGifBlock) | Removing a GIF block removes specific data from the image, offering the ability to clean up or modify the image structure. This method enables you to remove unwanted or unnecessary blocks, optimizing the GIF image for efficient storage. Use this functionality to eliminate outdated information from the image while preserving its integrity and quality. |
| override [RemoveMetadata](../../aspose.imaging/rasterimage/removemetadata/)() | Removes this image instance metadata by setting this [`XmpData`](../../aspose.imaging.xmp/ihasxmpdata/xmpdata/) value to `null`. |
| [ReplaceColor](../../aspose.imaging/rasterimage/replacecolor/)(Color, byte, Color) | Replaces one color to another with allowed difference and preserves original alpha value to save smooth edges. |
| override [ReplaceColor](../../aspose.imaging/rastercachedmultipageimage/replacecolor/)(int, byte, int) | Replaces one color to another with allowed difference and preserves original alpha value to save smooth edges. |
| [ReplaceNonTransparentColors](../../aspose.imaging/rasterimage/replacenontransparentcolors/)(Color) | Replaces all non-transparent colors with new color and preserves original alpha value to save smooth edges. Note: if you use it on images without transparency, all colors will be replaced with a single one. |
| override [ReplaceNonTransparentColors](../../aspose.imaging/rastercachedmultipageimage/replacenontransparentcolors/)(int) | Replaces all non-transparent colors with new color and preserves original alpha value to save smooth edges. Note: if you use it on images without transparency, all colors will be replaced with a single one. |
| [Resize](../../aspose.imaging/image/resize/)(int, int) | Resizes the image. The default NearestNeighbourResample is used. |
| override [Resize](../../aspose.imaging.fileformats.gif/gifimage/resize/#resize_1)(int, int, ImageResizeSettings) | Resizes this [`Image`](../../aspose.imaging/image/) instance. |
| override [Resize](../../aspose.imaging.fileformats.gif/gifimage/resize/#resize_2)(int, int, ResizeType) | Resizes this [`Image`](../../aspose.imaging/image/) instance. |
| [ResizeFullFrame](../../aspose.imaging.fileformats.gif/gifimage/resizefullframe/)(int, int, ResizeType) | Resizing of the image while taking into account the full frames for each page in a GIF, thus preventing potential artifacts from appearing. This method is essential to maintain the integrity and quality of the image, especially when dealing with animated GIFs or sequences of frames. |
| [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally/)(int) | Resizes the height proportionally. The default NearestNeighbourResample is used. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally/)(int, ImageResizeSettings) | Resizes the height proportionally. |
| override [ResizeHeightProportionally](../../aspose.imaging/rastercachedmultipageimage/resizeheightproportionally/)(int, ResizeType) | Resizes the width proportionally. |
| [ResizeProportional](../../aspose.imaging.fileformats.gif/gifimage/resizeproportional/)(int, int, ResizeType) | Proportional resizing maintains the aspect ratio of the image while adjusting its size, ensuring that the image does not appear stretched or distorted. This method resizes the image proportionally, scaling both the width and height by the same factor. The proportional resize will resize each frame according to the ratio of *newWidth*/width and *newHeight*/height. |
| [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally/)(int) | Resizes the width proportionally. The default NearestNeighbourResample is used. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally/)(int, ImageResizeSettings) | Resizes the width proportionally. |
| override [ResizeWidthProportionally](../../aspose.imaging/rastercachedmultipageimage/resizewidthproportionally/)(int, ResizeType) | Resizes the width proportionally. |
| override [Rotate](../../aspose.imaging/rasterimage/rotate/)(float) | Rotate image around the center. |
| override [Rotate](../../aspose.imaging.fileformats.gif/gifimage/rotate/#rotate_1)(float, bool, Color) | This method rotates the image around its center point. By specifying the rotation angle, you can rotate the image clockwise or counterclockwise to achieve the desired orientation. This rotation helps adjust the image's presentation or alignment without distorting its content. |
| override [RotateFlip](../../aspose.imaging.fileformats.gif/gifimage/rotateflip/)(RotateFlipType) | Perform rotation, flipping, or both on the active frame exclusively. This operation applies transformations solely to the currently active frame of the image, preserving the integrity of other frames in the sequence. |
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
| [SetFrameTime](../../aspose.imaging.fileformats.gif/gifimage/setframetime/)(ushort) | Adjusts the duration of each frame in milliseconds, ensuring consistent timing throughout the image sequence. This method uniformly sets the display time for every frame, allowing for precise control over animation speed. Changing this value will reset delay for all frames. |
| override [SetPalette](../../aspose.imaging/rasterimage/setpalette/)(IColorPalette, bool) | Sets the image palette. |
| [SetPixel](../../aspose.imaging/rasterimage/setpixel/)(int, int, Color) | Sets an image pixel for the specified position. |
| virtual [SetResolution](../../aspose.imaging/rasterimage/setresolution/)(double, double) | Sets the resolution for this [`RasterImage`](../../aspose.imaging/rasterimage/). |
| virtual [ToBitmap](../../aspose.imaging/rasterimage/tobitmap/)() | Converts raster image to the bitmap. This method is not supported in versions from .Net7.0 and higher |
| virtual [TrySetMetadata](../../aspose.imaging/image/trysetmetadata/)(IImageMetadataFormat) | Tries to set a *metadata* instance, if this [`Image`](../../aspose.imaging/image/) instance supports and implements [`IImageMetadataFormat`](../../aspose.imaging.metadata/iimagemetadataformat/) type. |
| [WriteArgb32ScanLine](../../aspose.imaging/rasterimage/writeargb32scanline/)(int, int[]) | Writes the whole scan line to the specified scan line index. |
| [WriteScanLine](../../aspose.imaging/rasterimage/writescanline/)(int, Color[]) | Writes the whole scan line to the specified scan line index. |

## Examples

Export of part of animation from GIF image based on time interval.

```csharp
[C#]

using (var image = Image.Load("Animation.gif"))
{
    var options = new GifOptions
    {
        FullFrame = true,
        MultiPageOptions = new MultiPageOptions
        {
            Mode = MultiPageMode.TimeInterval,
            TimeInterval = new TimeInterval(0, 400)
        }
    };

    image.Save("PartOfAnimation.gif", options);
}
```

This example shows how to create a GIF image and save it to a file.

```csharp
[C#]

string dir = "c:\\temp\\";

// Create a GIF Frame block of 100x100 px.
using (Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock firstBlock = new Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock(100, 100))
{
    // Fill the entire block in red.
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(firstBlock);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    gr.FillRectangle(brush, firstBlock.Bounds);

    using (Aspose.Imaging.FileFormats.Gif.GifImage gifImage = new Aspose.Imaging.FileFormats.Gif.GifImage(firstBlock))
    {
        gifImage.Save(dir + "output.gif");
    }
}
```

Create multipage GIF image using single page raster images.

```csharp
[C#]

static void Main(string[] args)
{
    // Load frames
    var frames = LoadFrames("Animation frames").ToArray();

    // Create GIF image using the first frame
    using (var image = new GifImage(new GifFrameBlock(frames[0])))
    {
        // Add frames to the GIF image using the AddPage method
        for (var index = 1; index < frames.Length; index++)
        {
            image.AddPage(frames[index]);
        }

        // Save GIF image
        image.Save("Multipage.gif");
    }
}

private static IEnumerable<RasterImage> LoadFrames(string directory)
{
    foreach (var filePath in Directory.GetFiles(directory))
    {
        yield return (RasterImage)Image.Load(filePath);
    }
}
```

### See Also

* class [RasterCachedMultipageImage](../../aspose.imaging/rastercachedmultipageimage/)
* interface [IMultipageImageExt](../../aspose.imaging/imultipageimageext/)
* namespace [Aspose.Imaging.FileFormats.Gif](../../aspose.imaging.fileformats.gif/)
* assembly [Aspose.Imaging](../../)


