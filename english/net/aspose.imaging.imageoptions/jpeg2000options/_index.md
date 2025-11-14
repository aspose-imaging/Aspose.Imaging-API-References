---
title: Class Jpeg2000Options
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.ImageOptions.Jpeg2000Options class. Create JPEG2000 JP2 image files with our API utilizing advanced wavelet technology for coding lossless content. Benefit from support for various codecs including irreversible and lossless compression as well as XMP metadata containers ensuring versatility and highquality image creation tailored to your needs
type: docs
weight: 10310
url: /net/aspose.imaging.imageoptions/jpeg2000options/
---
## Jpeg2000Options class

Create JPEG2000 (JP2) image files with our API, utilizing advanced wavelet technology for coding lossless content. Benefit from support for various codecs, including irreversible and lossless compression, as well as XMP metadata containers, ensuring versatility and high-quality image creation tailored to your needs.

```csharp
public class Jpeg2000Options : ImageOptionsBase
```

## Constructors

| Name | Description |
| --- | --- |
| [Jpeg2000Options](jpeg2000options/#constructor)() | Initializes a new instance of the `Jpeg2000Options` class. |
| [Jpeg2000Options](jpeg2000options/#constructor_1)(Jpeg2000Options) | Initializes a new instance of the `Jpeg2000Options` class. |

## Properties

| Name | Description |
| --- | --- |
| [BufferSizeHint](../../aspose.imaging/imageoptionsbase/buffersizehint/) { get; set; } | Gets or sets the buffer size hint which is defined max allowed size for all internal buffers. |
| [Codec](../../aspose.imaging.imageoptions/jpeg2000options/codec/) { get; set; } | Gets or sets the JPEG2000 codec |
| [Comments](../../aspose.imaging.imageoptions/jpeg2000options/comments/) { get; set; } | Gets or sets the Jpeg comment markers. |
| [CompressionRatios](../../aspose.imaging.imageoptions/jpeg2000options/compressionratios/) { get; set; } | Gets or sets the Array of compression ratio. Different compression ratios for successive layers. The rate specified for each quality level is the desired compression factor. Decreasing ratios required. |
| [Disposed](../../aspose.imaging/disposableobject/disposed/) { get; } | Gets a value indicating whether this instance is disposed. |
| virtual [ExifData](../../aspose.imaging/imageoptionsbase/exifdata/) { get; set; } | Gets or sets the Exif data. |
| [FullFrame](../../aspose.imaging/imageoptionsbase/fullframe/) { get; set; } | Gets or sets a value indicating whether [full frame]. |
| [Irreversible](../../aspose.imaging.imageoptions/jpeg2000options/irreversible/) { get; set; } | Gets or sets a value indicating whether use the irreversible DWT 9-7 (true) or use lossless DWT 5-3 compression (default). |
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

## Examples

The following example shows how to convert a multipage vector image to JPEG 2000 format in general way without referencing to a particular image type.

```csharp
[C#]

string dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
string inputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr");
string outputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr.j2k");

Aspose.Imaging.ImageOptionsBase exportOptions = new Aspose.Imaging.ImageOptions.Jpeg2000Options();

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFilePath))
{
    exportOptions.MultiPageOptions = null;

    // Export only first two pages. In fact, only one page will be rasterized because JPEG 2000 is not a multi-page format.
    Aspose.Imaging.IMultipageImage multipageImage = image as Aspose.Imaging.IMultipageImage;
    if (multipageImage != null && (multipageImage.Pages != null && multipageImage.PageCount > 2))
    {
        exportOptions.MultiPageOptions = new Aspose.Imaging.ImageOptions.MultiPageOptions(new Aspose.Imaging.IntRange(0, 2));
    }

    if (image is Aspose.Imaging.VectorImage)
    {
        exportOptions.VectorRasterizationOptions = (Aspose.Imaging.ImageOptions.VectorRasterizationOptions)image.GetDefaultOptions(new object[] { Aspose.Imaging.Color.White, image.Width, image.Height });
        exportOptions.VectorRasterizationOptions.TextRenderingHint = Aspose.Imaging.TextRenderingHint.SingleBitPerPixel;
        exportOptions.VectorRasterizationOptions.SmoothingMode = Aspose.Imaging.SmoothingMode.None;
    }

    image.Save(outputFilePath, exportOptions);
}
```

### See Also

* class [ImageOptionsBase](../../aspose.imaging/imageoptionsbase/)
* namespace [Aspose.Imaging.ImageOptions](../../aspose.imaging.imageoptions/)
* assembly [Aspose.Imaging](../../)


