---
title: Class CmxImage
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Cmx.CmxImage class. The API for Corel Metafile Exchange CMX vector image format with metadata descriptions support is a comprehensive solution for developers working with CMX files. This API allows for the seamless loading of CMX images extracting metadata such as bits per pixel object dimensions and more. With additional functionalities like resizing rotating setting palettes and converting to other formats this API empowers developers to efficiently manipulate and customize CMX vector images to meet their specific application requirements
type: docs
weight: 1950
url: /net/aspose.imaging.fileformats.cmx/cmximage/
---
## CmxImage class

The API for Corel Metafile Exchange (CMX) vector image format with metadata descriptions support is a comprehensive solution for developers working with CMX files. This API allows for the seamless loading of CMX images, extracting metadata such as bits per pixel, object dimensions, and more. With additional functionalities like resizing, rotating, setting palettes, and converting to other formats, this API empowers developers to efficiently manipulate and customize CMX vector images to meet their specific application requirements.

```csharp
public class CmxImage : VectorMultipageImage, ICmxImage
```

## Constructors

| Name | Description |
| --- | --- |
| [CmxImage](cmximage/)(StreamContainer, LoadOptions) | Start working with the `CmxImage` class seamlessly by initializing a new instance with a streamContainer and loadOptions parameters. Ideal for developers seeking a convenient way to load CMX images from various data sources while customizing the loading process as needed. |

## Properties

| Name | Description |
| --- | --- |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette/) { get; set; } | Gets or sets a value indicating whether automatic adjust palette. |
| virtual [BackgroundColor](../../aspose.imaging/image/backgroundcolor/) { get; set; } | Gets or sets a value for the background color. |
| override [BitsPerPixel](../../aspose.imaging.fileformats.cmx/cmximage/bitsperpixel/) { get; } | Retrieve the bit depth of the image effortlessly with this user-friendly property. Ideal for developers seeking to determine the level of detail or color depth present in their images, ensuring accurate processing and manipulation. |
| [Bounds](../../aspose.imaging/image/bounds/) { get; } | Gets the image bounds. |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint/) { get; set; } | Gets or sets the buffer size hint which is defined max allowed size for all internal buffers. |
| [CmxPage](../../aspose.imaging.fileformats.cmx/cmximage/cmxpage/) { get; } | Effortlessly retrieve the CMX page of the image with this intuitive property. Ideal for developers seeking quick access to individual pages within CMX images, ensuring efficient navigation and management. |
| [Container](../../aspose.imaging/image/container/) { get; } | Gets the [`Image`](../../aspose.imaging/image/) container. |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer/) { get; } | Gets the object's data stream. |
| [Disposed](../../aspose.imaging/disposableobject/disposed/) { get; } | Gets a value indicating whether this instance is disposed. |
| [Document](../../aspose.imaging.fileformats.cmx/cmximage/document/) { get; } | Retrieve the CMX document effortlessly with this intuitive property. Ideal for developers seeking to access or modify CMX images, ensuring flexibility and efficiency in their applications. |
| [ExifData](../../aspose.imaging/image/exifdata/) { get; set; } | Gets or sets the Exif data. |
| override [FileFormat](../../aspose.imaging.fileformats.cmx/cmximage/fileformat/) { get; } | Retrieve the file format of the image effortlessly with this user-friendly property. Ideal for developers seeking to determine the format of their images dynamically, ensuring compatibility and accurate processing in their applications. |
| virtual [HasBackgroundColor](../../aspose.imaging/image/hasbackgroundcolor/) { get; set; } | Gets or sets a value indicating whether image has background color. |
| override [Height](../../aspose.imaging/vectormultipageimage/height/) { get; } | Gets the image height. |
| override [HeightF](../../aspose.imaging.fileformats.cmx/cmximage/heightf/) { get; } | Effortlessly obtain the height of the object, measured in inches, with this user-friendly property. Ideal for developers seeking precise dimensional information for effective layout and presentation in their applications. |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor/) { get; set; } | Gets or sets the interrupt monitor. |
| override [IsCached](../../aspose.imaging.fileformats.cmx/cmximage/iscached/) { get; } | Determine whether the object's data is currently cached, eliminating the need for data reading. Ideal for developers seeking to optimize performance by leveraging cached data efficiently, ensuring faster access to object information. |
| override [Metadata](../../aspose.imaging/vectormultipageimage/metadata/) { get; } | Gets the image metadata. |
| override [PageCount](../../aspose.imaging.fileformats.cmx/cmximage/pagecount/) { get; } | Retrieve the total page count of the image with this intuitive property. Ideal for developers seeking to manage multi-page images dynamically, ensuring efficient navigation and manipulation of image content. |
| virtual [PageExportingAction](../../aspose.imaging/vectormultipageimage/pageexportingaction/) { get; set; } | Gets or sets the page exporting action. Please note that setting this method will automatically release page resources after it is executed. It will be executed just before each page is saved. |
| override [Pages](../../aspose.imaging.fileformats.cmx/cmximage/pages/) { get; } | Retrieve the pages of the image seamlessly with this intuitive property. Ideal for developers seeking to access and manipulate individual pages within multi-page images, ensuring efficient navigation and processing. |
| [Palette](../../aspose.imaging/image/palette/) { get; set; } | Gets or sets the color palette. The color palette is not used when pixels are represented directly. |
| [Size](../../aspose.imaging/image/size/) { get; } | Gets the image size. |
| [SizeF](../../aspose.imaging/vectorimage/sizef/) { get; } | Gets the object size, in inches. |
| virtual [UsePalette](../../aspose.imaging/image/usepalette/) { get; } | Gets a value indicating whether the image palette is used. |
| override [Width](../../aspose.imaging/vectormultipageimage/width/) { get; } | Gets the image width. |
| override [WidthF](../../aspose.imaging.fileformats.cmx/cmximage/widthf/) { get; } | Retrieve the width of the object in inches with this intuitive property. Ideal for developers seeking precise measurements of objects in their applications, ensuring accurate layout and presentation. |
| [XmpData](../../aspose.imaging/image/xmpdata/) { get; set; } | Gets or sets the Xmp data. |

## Methods

| Name | Description |
| --- | --- |
| override [CacheData](../../aspose.imaging.fileformats.cmx/cmximage/cachedata/)() | Cache the data to prevent additional loading from the underlying source [`DataStreamContainer`](../../aspose.imaging/datastreamsupporter/datastreamcontainer/) with this convenient method. Ideal for developers seeking to optimize performance by preloading data, ensuring faster access and smoother operation in their applications. |
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
| override [SetPalette](../../aspose.imaging.fileformats.cmx/cmximage/setpalette/)(IColorPalette, bool) | Customize the color palette of the image with this intuitive method. Ideal for developers seeking to apply specific color schemes or adjustments dynamically, ensuring precise control over the visual appearance of their images. |
| virtual [TrySetMetadata](../../aspose.imaging/image/trysetmetadata/)(IImageMetadataFormat) | Tries to set a *metadata* instance, if this [`Image`](../../aspose.imaging/image/) instance supports and implements [`IImageMetadataFormat`](../../aspose.imaging.metadata/iimagemetadataformat/) type. |

## Examples

The following example shows how to cache all pages of a CMX image.

```csharp
[C#]

string dir = "c:\\temp\\";

// Load an image from a CMX file.
using (Aspose.Imaging.FileFormats.Cmx.CmxImage image = (Aspose.Imaging.FileFormats.Cmx.CmxImage)Aspose.Imaging.Image.Load(dir + "sample.cmx"))
{
    // This call caches only the default page.
    image.CacheData();

    // Cache all pages so that no additional data loading will be performed from the underlying data stream.
    foreach (Aspose.Imaging.FileFormats.Cmx.CmxImagePage page in image.Pages)
    {
        page.CacheData();
    }
}
```

### See Also

* class [Image](../../aspose.imaging/image/)
* class [VectorMultipageImage](../../aspose.imaging/vectormultipageimage/)
* interface [ICmxImage](../icmximage/)
* namespace [Aspose.Imaging.FileFormats.Cmx](../../aspose.imaging.fileformats.cmx/)
* assembly [Aspose.Imaging](../../)


