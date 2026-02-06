---
title: Class DjvuImage
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Djvu.DjvuImage class. DjVu document class supports graphics file format and facilitates seamless management of scanned documents and books integrating text drawings images and photos into a single format. Supporting multipage operations you can efficiently access unique document identifiers count pages set active pages and retrieve specific document pages. With features for resizing rotating dithering cropping grayscale transformation gamma corrections adjustments and filters application this class empowers precise manipulation and enhancement of DjVu images to meet diverse application needs with ease and precision
type: docs
weight: 2530
url: /net/aspose.imaging.fileformats.djvu/djvuimage/
---
## DjvuImage class

DjVu document class supports graphics file format and facilitates seamless management of scanned documents and books, integrating text, drawings, images, and photos into a single format. Supporting multi-page operations, you can efficiently access unique document identifiers, count pages, set active pages, and retrieve specific document pages. With features for resizing, rotating, dithering, cropping, grayscale transformation, gamma corrections, adjustments, and filters application, this class empowers precise manipulation and enhancement of DjVu images to meet diverse application needs with ease and precision.

```csharp
public sealed class DjvuImage : RasterCachedMultipageImage, INotifyPropertyChanged
```

## Constructors

| Name | Description |
| --- | --- |
| [DjvuImage](djvuimage/#constructor)(Stream) | Start working with DjVu images by initializing a new instance of the `DjvuImage` class using a Stream parameter. Perfect for developers who want seamless integration of DjVu image processing into their projects. |
| [DjvuImage](djvuimage/#constructor_1)(Stream, LoadOptions) | Start working with DjVu images seamlessly with this constructor, which initializes a new `DjvuImage` class instance using a Stream and LoadOptions parameters. Perfect for developers who want precise control over DjVu image loading options while maintaining simplicity and efficiency. |

## Properties

| Name | Description |
| --- | --- |
| [ActivePage](../../aspose.imaging.fileformats.djvu/djvuimage/activepage/) { get; set; } | Navigate through your DjVu document by accessing or setting the currently active page using this property. Seamlessly switch between pages to focus on specific content and enhance your document viewing experience. |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette/) { get; set; } | Gets or sets a value indicating whether automatic adjust palette. |
| override [BackgroundColor](../../aspose.imaging/rastercachedmultipageimage/backgroundcolor/) { get; set; } | Gets or sets a value for the background color. |
| override [BitsPerPixel](../../aspose.imaging/rastercachedmultipageimage/bitsperpixel/) { get; } | Gets the image bits per pixel count. |
| [Bounds](../../aspose.imaging/image/bounds/) { get; } | Gets the image bounds. |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint/) { get; set; } | Gets or sets the buffer size hint which is defined max allowed size for all internal buffers. |
| [Container](../../aspose.imaging/image/container/) { get; } | Gets the [`Image`](../../aspose.imaging/image/) container. |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer/) { get; } | Gets the object's data stream. |
| [Disposed](../../aspose.imaging/disposableobject/disposed/) { get; } | Gets a value indicating whether this instance is disposed. |
| [DjvuPages](../../aspose.imaging.fileformats.djvu/djvuimage/djvupages/) { get; } | Quickly retrieve all the pages contained within your DjVu document using this property. Simplify your document processing workflow by easily accessing and managing individual pages within your DjVu files. Improve efficiency and streamline your tasks with convenient page retrieval. |
| [ExifData](../../aspose.imaging/image/exifdata/) { get; set; } | Gets or sets the Exif data. |
| override [FileFormat](../../aspose.imaging.fileformats.djvu/djvuimage/fileformat/) { get; } | Obtain the file format information associated with your DjVu image file. Quickly determine the format of your file for seamless integration into your workflow. |
| [FirstPage](../../aspose.imaging.fileformats.djvu/djvuimage/firstpage/) { get; } | Access the first page of your DjVu document with this property. Quickly retrieve the initial page to begin viewing or processing your document efficiently. |
| override [HasAlpha](../../aspose.imaging.fileformats.djvu/djvuimage/hasalpha/) { get; } | Quickly determine whether your DjVu image file contains an alpha channel. Simplify your workflow by checking for the presence of transparency information in your images. |
| virtual [HasBackgroundColor](../../aspose.imaging/image/hasbackgroundcolor/) { get; set; } | Gets or sets a value indicating whether image has background color. |
| override [HasTransparentColor](../../aspose.imaging/rastercachedmultipageimage/hastransparentcolor/) { get; } | Gets a value indicating whether image has transparent color. |
| override [Height](../../aspose.imaging/rastercachedmultipageimage/height/) { get; } | Gets the image height. |
| virtual [HorizontalResolution](../../aspose.imaging/rasterimage/horizontalresolution/) { get; set; } | Gets or sets the horizontal resolution, in pixels per inch, of this [`RasterImage`](../../aspose.imaging/rasterimage/). |
| [Identifier](../../aspose.imaging.fileformats.djvu/djvuimage/identifier/) { get; } | Gets the unique identifier for the document |
| override [ImageOpacity](../../aspose.imaging/rastercachedmultipageimage/imageopacity/) { get; } | Gets opacity of this image. |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor/) { get; set; } | Gets or sets the interrupt monitor. |
| override [IsCached](../../aspose.imaging/rastercachedmultipageimage/iscached/) { get; } | Gets a value indicating whether image data is cached currently. |
| [IsRawDataAvailable](../../aspose.imaging/rasterimage/israwdataavailable/) { get; } | Gets a value indicating whether raw data loading is available. |
| [LastPage](../../aspose.imaging.fileformats.djvu/djvuimage/lastpage/) { get; } | Retrieve the last page of your DjVu document using this property. Quickly access the final page for viewing or processing purposes with ease. |
| override [Metadata](../../aspose.imaging/rastercachedmultipageimage/metadata/) { get; } | Gets or sets XMP data from frame. |
| [NextPage](../../aspose.imaging.fileformats.djvu/djvuimage/nextpage/) { get; } | Navigate through your DjVu document by accessing the next page with this convenient property. Quickly move forward in your document viewing or processing tasks. |
| override [PageCount](../../aspose.imaging.fileformats.djvu/djvuimage/pagecount/) { get; } | Retrieve the total number of pages in your DjVu image collection with this property. Ideal for quickly assessing the extent of your document or book stored in DjVu format. Improve your workflow efficiency with accurate page count information. |
| virtual [PageExportingAction](../../aspose.imaging/rastercachedmultipageimage/pageexportingaction/) { get; set; } | Gets or sets the page exporting action. Please note that setting this method will automatically release page resources after it is executed. It will be executed just before each page is saved. |
| override [Pages](../../aspose.imaging.fileformats.djvu/djvuimage/pages/) { get; } | Access the individual pages of your DjVu image collection with this property. Simplify navigation and manipulation of your document or book stored in DjVu format by accessing each page directly. Improve your workflow efficiency with easy page retrieval. |
| [Palette](../../aspose.imaging/image/palette/) { get; set; } | Gets or sets the color palette. The color palette is not used when pixels are represented directly. |
| virtual [PremultiplyComponents](../../aspose.imaging/rasterimage/premultiplycomponents/) { get; set; } | Gets or sets a value indicating whether the image components must be premultiplied. |
| [PreviousPage](../../aspose.imaging.fileformats.djvu/djvuimage/previouspage/) { get; } | Quickly move backward in your DjVu document viewing or processing tasks by accessing the previous page with this convenient property. Efficiently navigate through your document with ease. |
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
| static [LoadDocument](../../aspose.imaging.fileformats.djvu/djvuimage/loaddocument/#loaddocument)(Stream) | Load your DjVu document with this method. Streamline your process by quickly accessing and importing your DjVu files into your application. |
| static [LoadDocument](../../aspose.imaging.fileformats.djvu/djvuimage/loaddocument/#loaddocument_1)(Stream, LoadOptions) | Import your DjVu document by utilizing this method with stream and loadOptions parameters. Streamline your process by quickly accessing and importing DjVu files into your application, providing flexibility and customization options to meet your needs. |
| override [AdjustBrightness](../../aspose.imaging.fileformats.djvu/djvuimage/adjustbrightness/)(int) | Adjust the *brightness* of an image using a specified parameter, providing control over luminance levels for optimal visual clarity. This method enhances or diminishes the overall brightness of the image, allowing for fine adjustments to achieve desired lighting effects. By modulating brightness, users can optimize image visibility and enhance detail reproduction for improved viewing experience. |
| override [AdjustContrast](../../aspose.imaging.fileformats.djvu/djvuimage/adjustcontrast/)(float) | Enhance [`Image`](../../aspose.imaging/image/) contrast to improve visual clarity and highlight details with this method, which adjusts the difference in brightness between light and dark areas. By fine-tuning contrast levels, users can achieve more vivid and impactful images, enhancing overall image quality and maximizing detail visibility. This adjustment helps to bring out subtle nuances in color and texture, resulting in more dynamic and visually appealing images. |
| override [AdjustGamma](../../aspose.imaging.fileformats.djvu/djvuimage/adjustgamma/#adjustgamma)(float) | Gamma correction, specifically for the red, green, and blue channels, involves adjusting the brightness of each color component separately. By applying different gamma coefficients to the RGB channels, you can fine-tune the overall brightness and contrast of an image. This technique ensures accurate color representation and improves the visual quality of the image across different display devices. |
| override [AdjustGamma](../../aspose.imaging.fileformats.djvu/djvuimage/adjustgamma/#adjustgamma_1)(float, float, float) | Gamma correction is applied to an image with customizable parameters for the red, green, and blue channels, allowing precise adjustment of color balance and brightness. This method enhances image quality by fine-tuning color representation, ensuring optimal rendering across different display devices. Adjusting gamma values for individual channels improves color balance and visual appeal. |
| override [AnalyzePercentageDigitalSignature](../../aspose.imaging/rastercachedmultipageimage/analyzepercentagedigitalsignature/)(string) | Calculates the percentage similarity between the extracted data and the original password. |
| override [AutoBrightnessContrast](../../aspose.imaging/rastercachedimage/autobrightnesscontrast/)() | Performs automatic adaptive brightness and contrast normalization for the entire image. |
| [AutoRotate](../../aspose.imaging/rasterimage/autorotate/)() | Automatically rotates the image based on orientation data extracted from Exif metadata. This method ensures that images are displayed in the correct orientation, enhancing user experience and eliminating the need for manual adjustments. By analyzing Exif information, the image is rotated accordingly, providing a seamless viewing experience across different platforms and devices. This automated rotation process simplifies image handling and improves overall usability, especially when dealing with large batches of images with varying orientations. |
| override [BinarizeBradley](../../aspose.imaging/rastercachedmultipageimage/binarizebradley/)(double) | Binarization of an image using Bradley's adaptive thresholding algorithm using the integral image thresholding |
| override [BinarizeBradley](../../aspose.imaging.fileformats.djvu/djvuimage/binarizebradley/#binarizebradley_1)(double, int) | Binarization using Bradley's adaptive thresholding algorithm with integral image thresholding is a method that calculates a local threshold for each pixel based on a local neighborhood. It adapts to variations in illumination across the image, making it suitable for images with uneven lighting conditions. By computing the threshold using integral images, it efficiently handles large neighborhoods, making it applicable to real-time applications. This technique is commonly used in document processing, OCR (Optical Character Recognition), and image segmentation tasks where accurate binarization is essential for subsequent analysis. |
| override [BinarizeFixed](../../aspose.imaging.fileformats.djvu/djvuimage/binarizefixed/)(byte) | Binarization with a predefined threshold simplifies complex images into binary representations, where pixels are categorized as either black or white based on their intensity compared to a specified threshold value. This technique is commonly used in image processing to enhance clarity, simplify analysis, and prepare images for further processing steps such as optical character recognition (OCR). By applying a fixed threshold, you can quickly transform grayscale images into binary form, making them easier to interpret and extract meaningful information from. |
| override [BinarizeOtsu](../../aspose.imaging.fileformats.djvu/djvuimage/binarizeotsu/)() | Binarization using Otsu thresholding is a technique that automatically calculates an optimal threshold value based on the image's histogram. It separates the image into foreground and background by minimizing the intra-class variance. Otsu's method is widely used for segmenting images into binary form, particularly when the distribution of pixel intensities is bimodal or multimodal. This approach is beneficial for tasks such as object detection, image segmentation, and feature extraction, where accurate delineation between foreground and background is crucial. |
| [Blend](../../aspose.imaging/rasterimage/blend/)(Point, RasterImage, byte) | Blends this image instance with the *overlay* image. |
| override [Blend](../../aspose.imaging/rastercachedmultipageimage/blend/)(Point, RasterImage, Rectangle, byte) | Blends this image instance with the *overlay* image. |
| override [CacheData](../../aspose.imaging.fileformats.djvu/djvuimage/cachedata/)() | Cache the data privately to optimize performance and reduce the need for repeated data retrieval from external sources. This approach also helps conserve resources, particularly in scenarios where data access is frequent or resources are limited. |
| [CanSave](../../aspose.imaging/image/cansave/)(ImageOptionsBase) | Determines whether image can be saved to the specified file format represented by the passed save options. |
| override [Crop](../../aspose.imaging.fileformats.djvu/djvuimage/crop/#crop)(Rectangle) | "Crop" trims your image to focus on specific details or remove unwanted elements, enhancing its composition and visual impact. Whether you're adjusting photos for social media, creating website banners, or designing print materials, this tool helps you refine your images with precision and clarity. |
| override [Crop](../../aspose.imaging.fileformats.djvu/djvuimage/crop/#crop_1)(int, int, int, int) | Crop with shifts allows you to precisely adjust the position and dimensions of the cropped area within an image. This feature is invaluable for refining compositions, aligning elements, and emphasizing focal points in your visuals. By incorporating shifts into the cropping process, you can achieve pixel-perfect precision and fine-tune the framing of your images with ease. |
| [Dispose](../../aspose.imaging/disposableobject/dispose/)() | Disposes the current instance. |
| [Dither](../../aspose.imaging/rasterimage/dither/)(DitheringMethod, int) | Performs dithering on the current image. |
| override [Dither](../../aspose.imaging.fileformats.djvu/djvuimage/dither/#dither_1)(DitheringMethod, int, IColorPalette) | The "Dither" function applies a dithering effect to your image, enhancing its visual quality by reducing banding and improving color transitions. Whether you're working on digital art, photography, or graphic design projects, this feature adds a professional touch to your images, making them appear smoother and more refined. |
| override [EmbedDigitalSignature](../../aspose.imaging/rastercachedmultipageimage/embeddigitalsignature/)(string) | Embed digital sign based on provided password into each page of the image. |
| override [Filter](../../aspose.imaging.fileformats.djvu/djvuimage/filter/)(Rectangle, FilterOptionsBase) | Apply filters to a specified rectangular area within the image to enhance or modify its appearance. By targeting specific regions, this method allows for precise adjustments, such as blurring, sharpening, or applying artistic effects, to achieve desired visual outcomes. Fine-tuning filters on selected areas empowers users to customize image aesthetics, improve clarity, and create artistic effects tailored to their preferences. |
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
| override [Grayscale](../../aspose.imaging.fileformats.djvu/djvuimage/grayscale/)() | Grayscale transformation converts an image to a black-and-white representation, where each pixel's intensity is represented by a single value ranging from black to white. This process removes color information, resulting in a monochromatic image. Grayscale images are commonly used in applications where color is unnecessary or where simplicity is preferred, such as document scanning, printing, and certain types of image analysis. |
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
| [ReplaceColor](../../aspose.imaging/rasterimage/replacecolor/)(Color, byte, Color) | Replaces one color to another with allowed difference and preserves original alpha value to save smooth edges. |
| override [ReplaceColor](../../aspose.imaging/rastercachedmultipageimage/replacecolor/)(int, byte, int) | Replaces one color to another with allowed difference and preserves original alpha value to save smooth edges. |
| [ReplaceNonTransparentColors](../../aspose.imaging/rasterimage/replacenontransparentcolors/)(Color) | Replaces all non-transparent colors with new color and preserves original alpha value to save smooth edges. Note: if you use it on images without transparency, all colors will be replaced with a single one. |
| override [ReplaceNonTransparentColors](../../aspose.imaging/rastercachedmultipageimage/replacenontransparentcolors/)(int) | Replaces all non-transparent colors with new color and preserves original alpha value to save smooth edges. Note: if you use it on images without transparency, all colors will be replaced with a single one. |
| [Resize](../../aspose.imaging/image/resize/)(int, int) | Resizes the image. The default NearestNeighbourResample is used. |
| override [Resize](../../aspose.imaging.fileformats.djvu/djvuimage/resize/#resize_1)(int, int, ImageResizeSettings) | Resize the image to the specified width and height while applying additional settings as needed. This method enables users to adjust the dimensions of the image while maintaining desired attributes such as aspect ratio, image quality, and compression settings. By providing flexibility in resizing options, users can tailor the image to fit specific requirements and optimize its appearance for various applications and platforms. |
| override [Resize](../../aspose.imaging.fileformats.djvu/djvuimage/resize/#resize_2)(int, int, ResizeType) | Resize the image using the `Resize` method, providing a simple and effective way to adjust the dimensions of your images according to your requirements. This versatile functionality empowers you to easily scale images to your desired size, enhancing their usability across various platforms and applications. |
| [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally/)(int) | Resizes the height proportionally. The default NearestNeighbourResample is used. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally/)(int, ImageResizeSettings) | Resizes the height proportionally. |
| override [ResizeHeightProportionally](../../aspose.imaging.fileformats.djvu/djvuimage/resizeheightproportionally/#resizeheightproportionally_2)(int, ResizeType) | The `ResizeHeightProportionally` method allows you to adjust the height of your image while preserving its aspect ratio. This ensures that your image maintains its proportions, preventing distortion and preserving its visual integrity. Whether you're optimizing images for web pages, mobile apps, or print media, this method ensures that your images look their best across different platforms and devices. |
| [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally/)(int) | Resizes the width proportionally. The default NearestNeighbourResample is used. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally/)(int, ImageResizeSettings) | Resizes the width proportionally. |
| override [ResizeWidthProportionally](../../aspose.imaging.fileformats.djvu/djvuimage/resizewidthproportionally/#resizewidthproportionally_2)(int, ResizeType) | The `ResizeWidthProportionally` method offers a convenient solution to adjust the width of your image while maintaining its aspect ratio. By proportionally resizing the width, you can ensure that your images remain visually appealing and consistent across different devices and screen sizes, enhancing their versatility and usability in various contexts. |
| override [Rotate](../../aspose.imaging/rasterimage/rotate/)(float) | Rotate image around the center. |
| override [Rotate](../../aspose.imaging.fileformats.djvu/djvuimage/rotate/#rotate_1)(float, bool, Color) | Rotate the image around its center with the Rotate method of the RasterCachedMultipageImage class. This convenient feature allows you to easily adjust the orientation of images while maintaining their center position, enhancing your image manipulation capabilities. |
| override [RotateFlip](../../aspose.imaging.fileformats.djvu/djvuimage/rotateflip/)(RotateFlipType) | The `RotateFlip` method offers versatile manipulation options for your image, allowing you to rotate, flip, or perform both operations on the active frame independently. Whether you're editing photos, creating graphics, or enhancing digital art, this method provides precise control over the orientation and composition of your images, ensuring they meet your creative vision with ease and efficiency. |
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

## Events

| Name | Description |
| --- | --- |
| event [PropertyChanged](../../aspose.imaging.fileformats.djvu/djvuimage/propertychanged/) | Occurs when a property value changes. |

## Examples

This example shows how to load a DJVU image from a file stream.

```csharp
[C#]

string dir = "c:\\temp\\";

// Load a DJVU image from a file stream.
using (System.IO.Stream stream = System.IO.File.OpenRead(dir + "sample.djvu"))
{
    using (Aspose.Imaging.FileFormats.Djvu.DjvuImage djvuImage = new Aspose.Imaging.FileFormats.Djvu.DjvuImage(stream))
    {
        // Save each page as an individual PNG image.
        foreach (Aspose.Imaging.FileFormats.Djvu.DjvuPage djvuPage in djvuImage.Pages)
        {
            // Generate a file name based on the page number.
            string fileName = string.Format("sample.{0}.png", djvuPage.PageNumber);
            djvuPage.Save(dir + fileName, new Aspose.Imaging.ImageOptions.PngOptions());
        }
    }
}
```

### See Also

* class [RasterCachedMultipageImage](../../aspose.imaging/rastercachedmultipageimage/)
* namespace [Aspose.Imaging.FileFormats.Djvu](../../aspose.imaging.fileformats.djvu/)
* assembly [Aspose.Imaging](../../)


