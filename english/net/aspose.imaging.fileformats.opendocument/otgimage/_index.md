---
title: Class OtgImage
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.OpenDocument.OtgImage class. Process OpenDocument Template OTG drawing image files with our API leveraging the OpenDocument XML format with Graphics Content for seamless manipulation. Easily parse documents customize background colors and adjust page dimensions ensuring optimal control and flexibility for your OTG vector graphics projects
type: docs
weight: 7510
url: /net/aspose.imaging.fileformats.opendocument/otgimage/
---
## OtgImage class

Process OpenDocument Template (OTG) drawing image files with our API, leveraging the OpenDocument XML format with Graphics Content for seamless manipulation. Easily parse documents, customize background colors, and adjust page dimensions, ensuring optimal control and flexibility for your OTG vector graphics projects.

```csharp
public class OtgImage : OdImage
```

## Constructors

| Name | Description |
| --- | --- |
| [OtgImage](otgimage/#constructor)(StreamContainer) | Create a new object of the `OtgImage` class by supplying a stream container. This constructor enables developers to create OTG images directly from stream containers, streamlining the process of working with OTG image data. |
| [OtgImage](otgimage/#constructor_1)(StreamContainer, LoadOptions) | Initialize a new `OtgImage` object by providing a stream container and loading options. This constructor empowers developers to efficiently load OTG images from streams while specifying custom loading configurations. |

## Properties

| Name | Description |
| --- | --- |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette/) { get; set; } | Gets or sets a value indicating whether automatic adjust palette. |
| virtual [BackgroundColor](../../aspose.imaging/image/backgroundcolor/) { get; set; } | Gets or sets a value for the background color. |
| override [BitsPerPixel](../../aspose.imaging.fileformats.opendocument/odimage/bitsperpixel/) { get; } | Retrieves the count of bits per pixel for the image. This property provides insight into the level of detail and color depth represented in the image, aiding in various image processing tasks and optimizations. |
| [Bounds](../../aspose.imaging/image/bounds/) { get; } | Gets the image bounds. |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint/) { get; set; } | Gets or sets the buffer size hint which is defined max allowed size for all internal buffers. |
| [Container](../../aspose.imaging/image/container/) { get; } | Gets the [`Image`](../../aspose.imaging/image/) container. |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer/) { get; } | Gets the object's data stream. |
| [Disposed](../../aspose.imaging/disposableobject/disposed/) { get; } | Gets a value indicating whether this instance is disposed. |
| [ExifData](../../aspose.imaging/image/exifdata/) { get; set; } | Gets or sets the Exif data. |
| override [FileFormat](../../aspose.imaging.fileformats.opendocument/otgimage/fileformat/) { get; } | This property provides access to the OTG file format, offering crucial insights into the type of data encapsulated within the image file. It serves as a pivotal reference point for software developers, enabling them to effectively handle OTG files within their applications. By utilizing this property, you can ascertain the specific format of the image file, facilitating seamless integration and manipulation of OTG files in their software systems. |
| virtual [HasBackgroundColor](../../aspose.imaging/image/hasbackgroundcolor/) { get; set; } | Gets or sets a value indicating whether image has background color. |
| override [Height](../../aspose.imaging/vectormultipageimage/height/) { get; } | Gets the image height. |
| virtual [HeightF](../../aspose.imaging/vectorimage/heightf/) { get; } | Gets the object height, in inches. |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor/) { get; set; } | Gets or sets the interrupt monitor. |
| override [IsCached](../../aspose.imaging.fileformats.opendocument/odimage/iscached/) { get; } | Obtains a boolean value indicating whether the data of the object is currently cached, thus eliminating the need for data reading. This property serves as an optimization indicator, enhancing performance by minimizing redundant data access operation. |
| [Metadata](../../aspose.imaging.fileformats.opendocument/odimage/metadata/) { get; } | Retrieves metadata specific to OpenDocument files. This property allows access to essential information embedded within OD files, facilitating various operations such as extraction, modification, or analysis of metadata. |
| override [Metadata](../../aspose.imaging/vectormultipageimage/metadata/) { get; } | Gets the image metadata. |
| override [PageCount](../../aspose.imaging.fileformats.opendocument/odimage/pagecount/) { get; } | Retrieves the total count of pages within the image. This property is essential for applications managing multi-page images, enabling them to accurately determine the number of pages available for processing or display. |
| virtual [PageExportingAction](../../aspose.imaging/vectormultipageimage/pageexportingaction/) { get; set; } | Gets or sets the page exporting action. Please note that setting this method will automatically release page resources after it is executed. It will be executed just before each page is saved. |
| override [Pages](../../aspose.imaging.fileformats.opendocument/otgimage/pages/) { get; } | Retrieves the collection of pages associated with the image, enabling software developers to access and manipulate each individual page efficiently. This property facilitates seamless iteration through the pages for various operations, enhancing the functionality and versatility of image processing applications. |
| [Palette](../../aspose.imaging/image/palette/) { get; set; } | Gets or sets the color palette. The color palette is not used when pixels are represented directly. |
| [Records](../../aspose.imaging.fileformats.opendocument/odimage/records/) { get; } | Retrieves the OpenDocument records stored within the image. This property grants access to specific structured data elements embedded within OpenDocument files, facilitating retrieval or manipulation of relevant information for further processing or analysis. |
| [Size](../../aspose.imaging/image/size/) { get; } | Gets the image size. |
| [SizeF](../../aspose.imaging/vectorimage/sizef/) { get; } | Gets the object size, in inches. |
| virtual [UsePalette](../../aspose.imaging/image/usepalette/) { get; } | Gets a value indicating whether the image palette is used. |
| override [Width](../../aspose.imaging/vectormultipageimage/width/) { get; } | Gets the image width. |
| virtual [WidthF](../../aspose.imaging/vectorimage/widthf/) { get; } | Gets the object width, in inches. |
| [XmpData](../../aspose.imaging/image/xmpdata/) { get; set; } | Gets or sets the Xmp data. |

## Methods

| Name | Description |
| --- | --- |
| override [CacheData](../../aspose.imaging/vectormultipageimage/cachedata/)() | Caches the data and ensures no additional data loading will be performed from the underlying [`DataStreamContainer`](../../aspose.imaging/datastreamsupporter/datastreamcontainer/). |
| [CanSave](../../aspose.imaging/image/cansave/)(ImageOptionsBase) | Determines whether image can be saved to the specified file format represented by the passed save options. |
| override [Crop](../../aspose.imaging/vectormultipageimage/crop/)(Rectangle) | Crops the specified rectangle. |
| virtual [Crop](../../aspose.imaging/image/crop/)(int, int, int, int) | Crop image with shifts. |
| [Dispose](../../aspose.imaging/disposableobject/dispose/)() | Disposes the current instance. |
| override [GetDefaultOptions](../../aspose.imaging/vectorimage/getdefaultoptions/)(object[]) | Gets the default image options. |
| override [GetEmbeddedImages](../../aspose.imaging/vectormultipageimage/getembeddedimages/)() | Gets the embedded images. |
| virtual [GetOriginalOptions](../../aspose.imaging/image/getoriginaloptions/)() | Gets the options based on the original file settings. This can be helpful to keep bit-depth and other parameters of the original image unchanged. For example, if we load a black-white PNG image with 1 bit per pixel and then save it using the [`Save`](../../aspose.imaging/datastreamsupporter/save/) method, the output PNG image with 8-bit per pixel will be produced. To avoid it and save PNG image with 1-bit per pixel, use this method to get corresponding saving options and pass them to the [`Save`](../../aspose.imaging/image/save/) method as the second parameter. |
| override [GetSerializedStream](../../aspose.imaging/vectormultipageimage/getserializedstream/)(ImageOptionsBase, Rectangle, out int) | Converts to aps. |
| override [RemoveBackground](../../aspose.imaging/vectormultipageimage/removebackground/)() | Removes the background. |
| override [RemoveBackground](../../aspose.imaging/vectormultipageimage/removebackground/)(RemoveBackgroundSettings) | Removes the background. |
| virtual [RemoveMetadata](../../aspose.imaging/image/removemetadata/)() | Removes metadata. |
| [Resize](../../aspose.imaging/image/resize/)(int, int) | Resizes the image. The default NearestNeighbourResample is used. |
| override [Resize](../../aspose.imaging/vectormultipageimage/resize/)(int, int, ImageResizeSettings) | Resizes the image. |
| override [Resize](../../aspose.imaging/vectormultipageimage/resize/)(int, int, ResizeType) | Resizes the image. |
| [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally/)(int) | Resizes the height proportionally. The default NearestNeighbourResample is used. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally/)(int, ImageResizeSettings) | Resizes the height proportionally. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally/)(int, ResizeType) | Resizes the height proportionally. |
| [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally/)(int) | Resizes the width proportionally. The default NearestNeighbourResample is used. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally/)(int, ImageResizeSettings) | Resizes the width proportionally. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally/)(int, ResizeType) | Resizes the width proportionally. |
| override [Rotate](../../aspose.imaging/vectormultipageimage/rotate/)(float) | Rotate image around the center. |
| override [RotateFlip](../../aspose.imaging/vectormultipageimage/rotateflip/)(RotateFlipType) | Rotates, flips, or rotates and flips the image. |
| [Save](../../aspose.imaging/image/save/)() | Saves the image data to the underlying stream. |
| [Save](../../aspose.imaging/datastreamsupporter/save/)(Stream) | Saves the object's data to the specified stream. |
| override [Save](../../aspose.imaging/image/save/)(string) | Saves the image to the specified file location. |
| [Save](../../aspose.imaging/image/save/)(Stream, ImageOptionsBase) | Saves the image's data to the specified stream in the specified file format according to save options. |
| virtual [Save](../../aspose.imaging/datastreamsupporter/save/)(string, bool) | Saves the object's data to the specified file location. |
| virtual [Save](../../aspose.imaging/image/save/)(string, ImageOptionsBase) | Saves the object's data to the specified file location in the specified file format according to save options. |
| virtual [Save](../../aspose.imaging/image/save/)(Stream, ImageOptionsBase, Rectangle) | Saves the image's data to the specified stream in the specified file format according to save options. |
| virtual [Save](../../aspose.imaging/image/save/)(string, ImageOptionsBase, Rectangle) | Saves the object's data to the specified file location in the specified file format according to save options. |
| override [SetPalette](../../aspose.imaging/vectormultipageimage/setpalette/)(IColorPalette, bool) | Sets the image palette. |
| virtual [TrySetMetadata](../../aspose.imaging/image/trysetmetadata/)(IImageMetadataFormat) | Tries to set a *metadata* instance, if this [`Image`](../../aspose.imaging/image/) instance supports and implements [`IImageMetadataFormat`](../../aspose.imaging.metadata/iimagemetadataformat/) type. |

## Examples

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

* class [OdImage](../odimage/)
* namespace [Aspose.Imaging.FileFormats.OpenDocument](../../aspose.imaging.fileformats.opendocument/)
* assembly [Aspose.Imaging](../../)


