---
title: Class EpsImage
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Eps.EpsImage class. The API for Encapsulated PostScript EPS image file format support offers robust capabilities for manipulating compositions comprising text graphics and images. With features such as bitmap preview image handling orientation flipping bounding box retrieval for illustration bounds resizing rotating images and adding preview images this API ensures seamless processing and integration of EPS files into various applications with precision and versatility
type: docs
weight: 6670
url: /net/aspose.imaging.fileformats.eps/epsimage/
---
## EpsImage class

The API for Encapsulated PostScript (EPS) image file format support offers robust capabilities for manipulating compositions comprising text, graphics, and images. With features such as bitmap preview image handling, orientation flipping, bounding box retrieval for illustration bounds, resizing, rotating images, and adding preview images, this API ensures seamless processing and integration of EPS files into various applications with precision and versatility.

```csharp
public sealed class EpsImage : VectorImage
```

## Properties

| Name | Description |
| --- | --- |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette/) { get; set; } | Gets or sets a value indicating whether automatic adjust palette. |
| virtual [BackgroundColor](../../aspose.imaging/image/backgroundcolor/) { get; set; } | Gets or sets a value for the background color. |
| override [BitsPerPixel](../../aspose.imaging.fileformats.eps/epsimage/bitsperpixel/) { get; } | Access the precise bit depth of the image effortlessly with this property. Retrieve the bits per pixel count, providing crucial insights into the image's color depth and aiding in optimizing processing tasks. Ideal for applications requiring fine-grained control over image manipulation and analysis. |
| [BoundingBox](../../aspose.imaging.fileformats.eps/epsimage/boundingbox/) { get; } | Accessing the original bounding box in device-independent points, this property provides crucial geometric information about the `EpsImage` dimensions. By retrieving this data, users can accurately assess the image's size and aspect ratio, facilitating precise layout and positioning in various applications. |
| [BoundingBoxPx](../../aspose.imaging.fileformats.eps/epsimage/boundingboxpx/) { get; } | This property returns the original bounding box of the `EpsImage` instance in pixels, providing essential geometric data for accurate rendering and manipulation. With this information, users can ensure precise placement and sizing /// of EPS images in their projects, enhancing overall visual presentation and quality. |
| [Bounds](../../aspose.imaging/image/bounds/) { get; } | Gets the image bounds. |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint/) { get; set; } | Gets or sets the buffer size hint which is defined max allowed size for all internal buffers. |
| [Container](../../aspose.imaging/image/container/) { get; } | Gets the [`Image`](../../aspose.imaging/image/) container. |
| [CreationDate](../../aspose.imaging.fileformats.eps/epsimage/creationdate/) { get; } | Retrieving the creation date from EPS Document Structuring Conventions (DSC) comments, this property provides essential metadata indicating the EPS file's inception. By accessing this information, users gain insights into the file's origin and chronology, enhancing file management and organization. |
| [Creator](../../aspose.imaging.fileformats.eps/epsimage/creator/) { get; } | This property offers access to the creator information sourced from EPS Document Structuring Conventions (DSC) comments found within the EPS file. Understanding the creator details provides insights into the software or tool used to generate the EPS file, facilitating compatibility assessment across various platforms and applications. |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer/) { get; } | Gets the object's data stream. |
| [Disposed](../../aspose.imaging/disposableobject/disposed/) { get; } | Gets a value indicating whether this instance is disposed. |
| [EpsType](../../aspose.imaging.fileformats.eps/epsimage/epstype/) { get; } | Access and interpret the subtype value of your EPS image, streamlining your workflow and enhancing compatibility across platforms. Ideal for optimizing EPS subtype retrieval in your projects with precision and efficiency. |
| [ExifData](../../aspose.imaging/image/exifdata/) { get; set; } | Gets or sets the Exif data. |
| override [FileFormat](../../aspose.imaging.fileformats.eps/epsimage/fileformat/) { get; } | Access the file format of your image with this property. Retrieve essential information about the format of your image file, facilitating compatibility and efficient processing. Ideal for identifying the format of your image files for seamless integration into your projects. |
| virtual [HasBackgroundColor](../../aspose.imaging/image/hasbackgroundcolor/) { get; set; } | Gets or sets a value indicating whether image has background color. |
| [HasRasterPreview](../../aspose.imaging.fileformats.eps/epsimage/hasrasterpreview/) { get; } | Discover the presence of a raster preview effortlessly with this property. Access the boolean value indicating whether the `EpsImage` instance includes a raster preview, empowering your image processing tasks with clarity and efficiency. Ideal for streamlining workflow decisions based on the presence or absence of raster previews in EPS images. |
| override [Height](../../aspose.imaging/vectorimage/height/) { get; } | Gets the image height. |
| override [HeightF](../../aspose.imaging.fileformats.eps/epsimage/heightf/) { get; } | Access the height of the image using this property. Obtain the image's height with ease, enabling seamless layout adjustments, aspect ratio calculations, and precise rendering across different screen resolutions and display environments. |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor/) { get; set; } | Gets or sets the interrupt monitor. |
| override [IsCached](../../aspose.imaging.fileformats.eps/epsimage/iscached/) { get; } | This property provides a convenient way to check if the object's data is currently cached, eliminating the need for additional data reading. It offers a quick and efficient method to determine if the required information is readily available, optimizing performance and reducing resource overhead in data-intensive operations. |
| virtual [Metadata](../../aspose.imaging/image/metadata/) { get; } | Gets the image metadata. |
| [Palette](../../aspose.imaging/image/palette/) { get; set; } | Gets or sets the color palette. The color palette is not used when pixels are represented directly. |
| [PostScriptVersion](../../aspose.imaging.fileformats.eps/epsimage/postscriptversion/) { get; } | This property retrieves the PostScript version associated with the `EpsImage` instance. It offers insight into the specific PostScript language version utilized within the EPS file, aiding in compatibility assessment and facilitating seamless integration with PostScript-compatible environments. |
| [PreviewImageCount](../../aspose.imaging.fileformats.eps/epsimage/previewimagecount/) { get; } | Access the number of preview images available with ease. This property allows you to effortlessly retrieve the count of preview images associated with your file, enabling efficient management and navigation of your image previews. Ideal for optimizing your workflow and organizing your image assets effectively. |
| [PreviewImages](../../aspose.imaging.fileformats.eps/epsimage/previewimages/) { get; } | Retrieve the preview images associated with your file. This property provides seamless access to the collection of preview images, allowing you to efficiently browse and manage them as needed. Ideal for quickly previewing and selecting the right image for your project. |
| [Size](../../aspose.imaging/image/size/) { get; } | Gets the image size. |
| [SizeF](../../aspose.imaging/vectorimage/sizef/) { get; } | Gets the object size, in inches. |
| [Title](../../aspose.imaging.fileformats.eps/epsimage/title/) { get; } | This property retrieves the title extracted from the EPS Document Structuring Conventions (DSC) comments embedded within the EPS file. It provides valuable metadata about the content of the EPS file, aiding in document organization and identification within compatible software applications. |
| virtual [UsePalette](../../aspose.imaging/image/usepalette/) { get; } | Gets a value indicating whether the image palette is used. |
| override [Width](../../aspose.imaging/vectorimage/width/) { get; } | Gets the image width. |
| override [WidthF](../../aspose.imaging.fileformats.eps/epsimage/widthf/) { get; } | Retrieve the width of the image with this convenient property. Obtain the image's width effortlessly, facilitating precise layout calculations, scaling operations, and dimension-related tasks within your application. Ideal for ensuring accurate rendering and display of images across various platforms and devices. |
| [XmpData](../../aspose.imaging/image/xmpdata/) { get; set; } | Gets or sets the Xmp data. |

## Methods

| Name | Description |
| --- | --- |
| override [CacheData](../../aspose.imaging.fileformats.eps/epsimage/cachedata/)() | This method does nothing as the current implementation of the `EpsImage` class does not involve caching data. While it may not perform any action, understanding this behavior is crucial for developers working with EPS images, ensuring efficient resource management and optimal performance within their applications. |
| [CanSave](../../aspose.imaging/image/cansave/)(ImageOptionsBase) | Determines whether image can be saved to the specified file format represented by the passed save options. |
| override [Crop](../../aspose.imaging/vectorimage/crop/)(Rectangle) | Crops the specified rectangle. |
| virtual [Crop](../../aspose.imaging/image/crop/)(int, int, int, int) | Crop image with shifts. |
| [Dispose](../../aspose.imaging/disposableobject/dispose/)() | Disposes the current instance. |
| override [GetDefaultOptions](../../aspose.imaging/vectorimage/getdefaultoptions/)(object[]) | Gets the default image options. |
| virtual [GetEmbeddedImages](../../aspose.imaging/vectorimage/getembeddedimages/)() | Gets the embedded images. |
| virtual [GetOriginalOptions](../../aspose.imaging/image/getoriginaloptions/)() | Gets the options based on the original file settings. This can be helpful to keep bit-depth and other parameters of the original image unchanged. For example, if we load a black-white PNG image with 1 bit per pixel and then save it using the [`Save`](../../aspose.imaging/datastreamsupporter/save/) method, the output PNG image with 8-bit per pixel will be produced. To avoid it and save PNG image with 1-bit per pixel, use this method to get corresponding saving options and pass them to the [`Save`](../../aspose.imaging/image/save/) method as the second parameter. |
| [GetPreviewImage](../../aspose.imaging.fileformats.eps/epsimage/getpreviewimage/)(EpsPreviewFormat) | Retrieves the existing preview image in the specified *format* or returns `null` if none is found. This method offers flexibility in accessing preview images tailored to specific formats, optimizing compatibility and resource management within applications. |
| [GetPreviewImages](../../aspose.imaging.fileformats.eps/epsimage/getpreviewimages/)() | Accesses the preview images linked to the `EpsImage` instance, allowing seamless retrieval for inspection or utilization in applications. This method provides convenient access to preview images, enhancing user interaction with the image data. |
| virtual [GetSerializedStream](../../aspose.imaging/image/getserializedstream/)(ImageOptionsBase, Rectangle, out int) | Converts to aps. |
| virtual [RemoveBackground](../../aspose.imaging/vectorimage/removebackground/)() | Removes the background. |
| virtual [RemoveBackground](../../aspose.imaging/vectorimage/removebackground/)(RemoveBackgroundSettings) | Removes the background. |
| virtual [RemoveMetadata](../../aspose.imaging/image/removemetadata/)() | Removes metadata. |
| [Resize](../../aspose.imaging/image/resize/)(int, int) | Resizes the image. The default NearestNeighbourResample is used. |
| override [Resize](../../aspose.imaging/vectorimage/resize/)(int, int, ImageResizeSettings) | Resizes the image with extended options. |
| override [Resize](../../aspose.imaging/vectorimage/resize/)(int, int, ResizeType) | Resizes the specified new width. |
| [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally/)(int) | Resizes the height proportionally. The default NearestNeighbourResample is used. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally/)(int, ImageResizeSettings) | Resizes the height proportionally. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally/)(int, ResizeType) | Resizes the height proportionally. |
| [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally/)(int) | Resizes the width proportionally. The default NearestNeighbourResample is used. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally/)(int, ImageResizeSettings) | Resizes the width proportionally. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally/)(int, ResizeType) | Resizes the width proportionally. |
| override [Rotate](../../aspose.imaging/vectorimage/rotate/)(float) | Rotate image around the center. |
| override [RotateFlip](../../aspose.imaging/vectorimage/rotateflip/)(RotateFlipType) | Rotates, flips, or rotates and flips the image. |
| [Save](../../aspose.imaging/image/save/)() | Saves the image data to the underlying stream. |
| [Save](../../aspose.imaging/datastreamsupporter/save/)(Stream) | Saves the object's data to the specified stream. |
| override [Save](../../aspose.imaging/image/save/)(string) | Saves the image to the specified file location. |
| [Save](../../aspose.imaging/image/save/)(Stream, ImageOptionsBase) | Saves the image's data to the specified stream in the specified file format according to save options. |
| virtual [Save](../../aspose.imaging/datastreamsupporter/save/)(string, bool) | Saves the object's data to the specified file location. |
| virtual [Save](../../aspose.imaging/image/save/)(string, ImageOptionsBase) | Saves the object's data to the specified file location in the specified file format according to save options. |
| virtual [Save](../../aspose.imaging/image/save/)(Stream, ImageOptionsBase, Rectangle) | Saves the image's data to the specified stream in the specified file format according to save options. |
| virtual [Save](../../aspose.imaging/image/save/)(string, ImageOptionsBase, Rectangle) | Saves the object's data to the specified file location in the specified file format according to save options. |
| override [SetPalette](../../aspose.imaging.fileformats.eps/epsimage/setpalette/)(IColorPalette, bool) | Customize image palettes to achieve unique color schemes and enhance visual appeal. Tailor colors for specific effects and optimize image quality across different platforms and devices with ease. |
| virtual [TrySetMetadata](../../aspose.imaging/image/trysetmetadata/)(IImageMetadataFormat) | Tries to set a *metadata* instance, if this [`Image`](../../aspose.imaging/image/) instance supports and implements [`IImageMetadataFormat`](../../aspose.imaging.metadata/iimagemetadataformat/) type. |

## Examples

Resize EPS image and export it to PNG format.

```csharp
[C#]

// Load EPS image
using (var image = Image.Load("AstrixObelix.eps"))
{
    // Resize the image using the Mitchell cubic interpolation method
    image.Resize(400, 400, ResizeType.Mitchell);

    // Export image to PNG format
    image.Save("ExportResult.png", new PngOptions());
}
```

Convert EPS image to PDF using PostScript rendering.

```csharp
[C#]

using (var image = (EpsImage)Image.Load("Sample.eps"))
{
    var options = new PdfOptions
    {
        PdfCoreOptions = new PdfCoreOptions
        {
            PdfCompliance = PdfComplianceVersion.PdfA1b // Set required PDF compliance
        }
    };
  
    image.Save("Sample.pdf", options);
}
```

Convert EPS image to PNG using PostScript rendering.

```csharp
[C#]

using (var image = (EpsImage)Image.Load("Sample.eps"))
{
    var options = new PngOptions
    {
        VectorRasterizationOptions = new EpsRasterizationOptions
        {
            PageWidth = 500, // Image width
            PageHeight = 500 // Image height
            PreviewToExport = EpsPreviewFormat.PostScriptRendering; // Render raster image using the PostScript
        }
    };

    image.Save("Sample.png", options);
}
```

Resize EPS image using advanced settings.

```csharp
[C#]

// Load EPS image
using (var image = Image.Load("AstrixObelix.eps"))
{
    // Resize the image using advanced resize settings
    image.Resize(400, 400, new ImageResizeSettings
    {
        // Set the interpolation mode
        Mode = ResizeType.LanczosResample,

        // Set the type of the filter
        FilterType = ImageFilterType.SmallRectangular,

        // Sets the color compare method
        ColorCompareMethod = ColorCompareMethod.Euclidian,

        // Set the color quantization method
        ColorQuantizationMethod = ColorQuantizationMethod.Popularity
    });

    // Export image to PNG format
    image.Save("ExportResult.png", new PngOptions());
}
```

### See Also

* class [VectorImage](../../aspose.imaging/vectorimage/)
* namespace [Aspose.Imaging.FileFormats.Eps](../../aspose.imaging.fileformats.eps/)
* assembly [Aspose.Imaging](../../)


