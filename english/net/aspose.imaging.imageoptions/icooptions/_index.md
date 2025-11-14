---
title: Class IcoOptions
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.ImageOptions.IcoOptions class. Create custom ICO image files for application icons effortlessly with our API empowering you to represent your software seamlessly. Our API supports PNG and BMP image frames with various bits per pixel values ensuring versatility and compatibility for your icon creation needs
type: docs
weight: 10300
url: /net/aspose.imaging.imageoptions/icooptions/
---
## IcoOptions class

Create custom ICO image files for application icons effortlessly with our API, empowering you to represent your software seamlessly. Our API supports PNG and BMP image frames with various bits per pixel values, ensuring versatility and compatibility for your icon creation needs.

```csharp
public class IcoOptions : ImageOptionsBase
```

## Constructors

| Name | Description |
| --- | --- |
| [IcoOptions](icooptions/#constructor)() | Initializes a new instance of the `IcoOptions` class with the ICO frame format equals to Png and bitsPerPixel equals to 32. |
| [IcoOptions](icooptions/#constructor_1)(FileFormat, int) | Initializes a new instance of the `IcoOptions` class. |

## Properties

| Name | Description |
| --- | --- |
| [BitsPerPixel](../../aspose.imaging.imageoptions/icooptions/bitsperpixel/) { get; set; } | Gets or sets the bits-per-pixel value. |
| [BufferSizeHint](../../aspose.imaging/imageoptionsbase/buffersizehint/) { get; set; } | Gets or sets the buffer size hint which is defined max allowed size for all internal buffers. |
| [Disposed](../../aspose.imaging/disposableobject/disposed/) { get; } | Gets a value indicating whether this instance is disposed. |
| virtual [ExifData](../../aspose.imaging/imageoptionsbase/exifdata/) { get; set; } | Gets or sets the Exif data. |
| [Format](../../aspose.imaging.imageoptions/icooptions/format/) { get; set; } | Gets or sets the ICO frame format. |
| [FullFrame](../../aspose.imaging/imageoptionsbase/fullframe/) { get; set; } | Gets or sets a value indicating whether [full frame]. |
| [KeepMetadata](../../aspose.imaging/imageoptionsbase/keepmetadata/) { get; set; } | Gets a value whether to keep original image metadata on export. |
| [MultiPageOptions](../../aspose.imaging/imageoptionsbase/multipageoptions/) { get; set; } | The multipage options |
| virtual [Palette](../../aspose.imaging/imageoptionsbase/palette/) { get; set; } | Gets or sets the color palette. |
| [ProgressEventHandler](../../aspose.imaging/imageoptionsbase/progresseventhandler/) { get; set; } | Gets or sets the progress event handler. |
| virtual [ResolutionSettings](../../aspose.imaging/imageoptionsbase/resolutionsettings/) { get; set; } | Gets or sets the resolution settings. |
| [Source](../../aspose.imaging/imageoptionsbase/source/) { get; set; } | Gets or sets the source to create image in. |
| [VectorRasterizationOptions](../../aspose.imaging/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | Gets or sets the vector rasterization options. |
| virtual [XmpData](../../aspose.imaging/imageoptionsbase/xmpdata/) { get; set; } | Gets or sets the XMP metadata container. |

## Methods

| Name | Description |
| --- | --- |
| virtual [Clone](../../aspose.imaging/imageoptionsbase/clone/)() | Creates a memberwise clone of this instance. |
| [Dispose](../../aspose.imaging/disposableobject/dispose/)() | Disposes the current instance. |
| [TrySetMetadata](../../aspose.imaging/imageoptionsbase/trysetmetadata/)(IImageMetadataFormat) | Tries to set a *metadata* instance, if this [`Image`](../../aspose.imaging/image/) instance supports and implements [`IImageMetadataFormat`](../../aspose.imaging.metadata/iimagemetadataformat/) instance. |

### See Also

* class [ImageOptionsBase](../../aspose.imaging/imageoptionsbase/)
* namespace [Aspose.Imaging.ImageOptions](../../aspose.imaging.imageoptions/)
* assembly [Aspose.Imaging](../../)


