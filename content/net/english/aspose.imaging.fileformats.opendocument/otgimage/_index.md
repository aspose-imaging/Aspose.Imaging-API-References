---
title: OtgImage
second_title: Aspose.Imaging for .NET API Reference
description: 
type: docs
weight: 7400
url: /aspose.imaging.fileformats.opendocument/otgimage/
---
## OtgImage class

Process OpenDocument Template (OTG) drawing image files with our API, leveraging the OpenDocument XML format with Graphics Content for seamless manipulation. Easily parse documents, customize background colors, and adjust page dimensions, ensuring optimal control and flexibility for your OTG vector graphics projects.

```csharp
public class OtgImage : OdImage
```

## Constructors

| Name | Description |
| --- | --- |
| [OtgImage](otgimage)(StreamContainer) | Create a new object of the [`OtgImage`](../otgimage) class by supplying a stream container. This constructor enables developers to create OTG images directly from stream containers, streamlining the process of working with OTG image data. |
| [OtgImage](otgimage)(StreamContainer, LoadOptions) | Initialize a new [`OtgImage`](../otgimage) object by providing a stream container and loading options. This constructor empowers developers to efficiently load OTG images from streams while specifying custom loading configurations. |

## Properties

| Name | Description |
| --- | --- |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette) { get; set; } | Gets or sets a value indicating whether automatic adjust palette. |
| virtual [BackgroundColor](../../aspose.imaging/image/backgroundcolor) { get; set; } | Gets or sets a value for the background color. |
| override [BitsPerPixel](../../aspose.imaging.fileformats.opendocument/odimage/bitsperpixel) { get; } | Retrieves the count of bits per pixel for the image. This property provides insight into the level of detail and color depth represented in the image, aiding in various image processing tasks and optimizations. |
| [Bounds](../../aspose.imaging/image/bounds) { get; } | Gets the image bounds. |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint) { get; set; } | Gets or sets the buffer size hint which is defined max allowed size for all internal buffers. |
| [Container](../../aspose.imaging/image/container) { get; } | Gets the [`Image`](../../aspose.imaging/image) container. |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer) { get; } | Gets the object's data stream. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Gets a value indicating whether this instance is disposed. |
| override [FileFormat](../../aspose.imaging.fileformats.opendocument/otgimage/fileformat) { get; } | This property provides access to the OTG file format, offering crucial insights into the type of data encapsulated within the image file. It serves as a pivotal reference point for software developers, enabling them to effectively handle OTG files within their applications. By utilizing this property, you can ascertain the specific format of the image file, facilitating seamless integration and manipulation of OTG files in their software systems. |
| virtual [HasBackgroundColor](../../aspose.imaging/image/hasbackgroundcolor) { get; set; } | Gets or sets a value indicating whether image has background color. |
| override [Height](../../aspose.imaging.fileformats.opendocument/odimage/height) { get; } | Returns the height of the image, denoting the vertical dimension in pixels. This property is crucial for understanding the image's overall size and proportions, facilitating accurate display and processing of image content. |
| virtual [HeightF](../../aspose.imaging/vectorimage/heightf) { get; } | Gets the object height, in inches. |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor) { get; set; } | Gets or sets the interrupt monitor. |
| override [IsCached](../../aspose.imaging.fileformats.opendocument/odimage/iscached) { get; } | Obtains a boolean value indicating whether the data of the object is currently cached, thus eliminating the need for data reading. This property serves as an optimization indicator, enhancing performance by minimizing redundant data access operation. |
| [Metadata](../../aspose.imaging.fileformats.opendocument/odimage/metadata) { get; } | Retrieves metadata specific to OpenDocument files. This property allows access to essential information embedded within OD files, facilitating various operations such as extraction, modification, or analysis of metadata. |
| override [PageCount](../../aspose.imaging.fileformats.opendocument/odimage/pagecount) { get; } | Retrieves the total count of pages within the image. This property is essential for applications managing multi-page images, enabling them to accurately determine the number of pages available for processing or display. |
| override [PageExportingAction](../../aspose.imaging.fileformats.opendocument/otgimage/pageexportingaction) { get; set; } | This property allows for the retrieval or modification of the page exporting action associated with the image. It serves as a crucial parameter, dictating the behavior of the image when exported or processed further. Please note that setting this method will automatically release page resources after it is executed. It will be executed just before each page is saved. |
| override [Pages](../../aspose.imaging.fileformats.opendocument/otgimage/pages) { get; } | Retrieves the collection of pages associated with the image, enabling software developers to access and manipulate each individual page efficiently. This property facilitates seamless iteration through the pages for various operations, enhancing the functionality and versatility of image processing applications. |
| [Palette](../../aspose.imaging/image/palette) { get; set; } | Gets or sets the color palette. The color palette is not used when pixels are represented directly. |
| [Records](../../aspose.imaging.fileformats.opendocument/odimage/records) { get; } | Retrieves the OpenDocument records stored within the image. This property grants access to specific structured data elements embedded within OpenDocument files, facilitating retrieval or manipulation of relevant information for further processing or analysis. |
| [Size](../../aspose.imaging/image/size) { get; } | Gets the image size. |
| [SizeF](../../aspose.imaging/vectorimage/sizef) { get; } | Gets the object size, in inches. |
| virtual [UsePalette](../../aspose.imaging/image/usepalette) { get; } | Gets a value indicating whether the image palette is used. |
| override [Width](../../aspose.imaging.fileformats.opendocument/odimage/width) { get; } | Retrieves the width of the image, indicating the horizontal dimension in pixels. This property provides essential information about the image's size, enabling precise rendering, manipulation, and analysis of image data. |
| virtual [WidthF](../../aspose.imaging/vectorimage/widthf) { get; } | Gets the object width, in inches. |

## Methods

| Name | Description |
| --- | --- |
| override [CacheData](../../aspose.imaging/vectormultipageimage/cachedata)() | Caches the data and ensures no additional data loading will be performed from the underlying [`DataStreamContainer`](../../aspose.imaging/datastreamsupporter/datastreamcontainer). |
| [CanSave](../../aspose.imaging/image/cansave)(ImageOptionsBase) | Determines whether image can be saved to the specified file format represented by the passed save options. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Disposes the current instance. |
| override [GetDefaultOptions](../../aspose.imaging.fileformats.opendocument/otgimage/getdefaultoptions)(object[]) | Retrieves the default options configured for the image, providing a convenient way to access and modify the default settings. This property ensures consistency in operations by offering predefined settings that align with common use cases, simplifying the development process. |
| override [GetEmbeddedImages](../../aspose.imaging/vectormultipageimage/getembeddedimages)() | Gets the embedded images. |
| virtual [GetOriginalOptions](../../aspose.imaging/image/getoriginaloptions)() | Gets the options based on the original file settings. This can be helpful to keep bit-depth and other parameters of the original image unchanged. For example, if we load a black-white PNG image with 1 bit per pixel and then save it using the [`Save`](../../aspose.imaging/datastreamsupporter/save) method, the output PNG image with 8-bit per pixel will be produced. To avoid it and save PNG image with 1-bit per pixel, use this method to get corresponding saving options and pass them to the [`Save`](../../aspose.imaging/image/save) method as the second parameter. |
| override [GetSerializedStream](../../aspose.imaging/vectormultipageimage/getserializedstream)(ImageOptionsBase, Rectangle, out int) | Converts to aps. |
| [RemoveBackground](../../aspose.imaging/vectorimage/removebackground)() | Removes the background. |
| [RemoveBackground](../../aspose.imaging/vectorimage/removebackground)(RemoveBackgroundSettings) | Removes the background. |
| [Resize](../../aspose.imaging/image/resize)(int, int) | Resizes the image. The default NearestNeighbourResample is used. |
| override [Resize](../../aspose.imaging.fileformats.opendocument/odimage/resize)(int, int, ImageResizeSettings) | Adjusts the dimensions of the image according to specified width, height, and resize settings. This method provides flexibility in resizing images while maintaining desired proportions and adhering to defined resize configurations, ensuring accurate adjustment of image dimensions to meet specific requirements or display criteria. |
| override [Resize](../../aspose.imaging.fileformats.opendocument/odimage/resize)(int, int, ResizeType) | This method resizes the image, adjusting both width and height based on the specified dimensions and resize type. It offers a comprehensive approach to resizing, allowing for precise adjustments while maintaining image quality and integrity. By incorporating the resize type parameter, users can choose from various resizing algorithms or methods to achieve optimal results for different use cases or preferences. |
| [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int) | Resizes the height proportionally. The default NearestNeighbourResample is used. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int, ImageResizeSettings) | Resizes the height proportionally. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int, ResizeType) | Resizes the height proportionally. |
| [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int) | Resizes the width proportionally. The default NearestNeighbourResample is used. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int, ImageResizeSettings) | Resizes the width proportionally. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int, ResizeType) | Resizes the width proportionally. |
| override [RotateFlip](../../aspose.imaging.fileformats.opendocument/odimage/rotateflip)(RotateFlipType) | This method provides functionality to rotate, flip, or perform both operations simultaneously on the image. It allows users to manipulate the orientation of the image according to their specific requirements. With support for rotation angles and flip directions, it offers flexibility in transforming the image to desired orientations or orientations. |
| [Save](../../aspose.imaging/image/save)() | Saves the image data to the underlying stream. |
| [Save](../../aspose.imaging/datastreamsupporter/save)(Stream) | Saves the object's data to the specified stream. |
| override [Save](../../aspose.imaging/image/save)(string) | Saves the image to the specified file location. |
| [Save](../../aspose.imaging/image/save)(Stream, ImageOptionsBase) | Saves the image's data to the specified stream in the specified file format according to save options. |
| virtual [Save](../../aspose.imaging/datastreamsupporter/save)(string, bool) | Saves the object's data to the specified file location. |
| virtual [Save](../../aspose.imaging/image/save)(string, ImageOptionsBase) | Saves the object's data to the specified file location in the specified file format according to save options. |
| virtual [Save](../../aspose.imaging/image/save)(Stream, ImageOptionsBase, Rectangle) | Saves the image's data to the specified stream in the specified file format according to save options. |
| virtual [Save](../../aspose.imaging/image/save)(string, ImageOptionsBase, Rectangle) | Saves the object's data to the specified file location in the specified file format according to save options. |
| override [SetPalette](../../aspose.imaging/vectormultipageimage/setpalette)(IColorPalette, bool) | Sets the image palette. |

### Examples

The following code snippet demonstrates how to convert an OTG image to PDF and other image formats.

```csharp
[C#]

string dir = "c:\\aspose.imaging\\issues\\net\\3567\\";
string inputFilePath = dir + "VariousObjectsMultiPage.otg";
Aspose.Imaging.ImageOptionsBase[] options = { new Aspose.Imaging.ImageOptions.PngOptions(), new Aspose.Imaging.ImageOptions.PdfOptions() };
foreach (Aspose.Imaging.ImageOptionsBase saveOptions in options)
{
    string extension = saveOptions is Aspose.Imaging.ImageOptions.PngOptions ? ".png" : ".pdf";
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFilePath))
    {
        Aspose.Imaging.ImageOptions.OtgRasterizationOptions otgRasterizationOptions = new Aspose.Imaging.ImageOptions.OtgRasterizationOptions();
        otgRasterizationOptions.PageSize = image.Size;
        saveOptions.VectorRasterizationOptions = otgRasterizationOptions;

        image.Save(inputFilePath + extension, saveOptions);
    }
}
```

### See Also

* class [OdImage](../odimage)
* namespace [Aspose.Imaging.FileFormats.OpenDocument](../../aspose.imaging.fileformats.opendocument)
* assembly [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
