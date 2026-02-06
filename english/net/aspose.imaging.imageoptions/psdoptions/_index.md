---
title: Class PsdOptions
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.ImageOptions.PsdOptions class. Create Photoshop Document PSD images with our API offering versatile options with different format versions compression methods color modes and bits counts per color channel. Seamlessly handle XMP metadata containers ensuring comprehensive image processing with the power of PSD format features like image layers layer masks and file information for customization and creativity in your designs
type: docs
weight: 10520
url: /net/aspose.imaging.imageoptions/psdoptions/
---
## PsdOptions class

Create Photoshop Document (PSD) images with our API, offering versatile options with different format versions, compression methods, color modes, and bits counts per color channel. Seamlessly handle XMP metadata containers, ensuring comprehensive image processing with the power of PSD format features like image layers, layer masks, and file information for customization and creativity in your designs.

```csharp
public class PsdOptions : ImageOptionsBase
```

## Constructors

| Name | Description |
| --- | --- |
| [PsdOptions](psdoptions/#constructor)() | Initializes a new instance of the `PsdOptions` class. |
| [PsdOptions](psdoptions/#constructor_1)(PsdOptions) | Initializes a new instance of the `PsdOptions` class. |

## Properties

| Name | Description |
| --- | --- |
| [BufferSizeHint](../../aspose.imaging/imageoptionsbase/buffersizehint/) { get; set; } | Gets or sets the buffer size hint which is defined max allowed size for all internal buffers. |
| [ChannelBitsCount](../../aspose.imaging.imageoptions/psdoptions/channelbitscount/) { get; set; } | Gets or sets the bits count per color channel. |
| [ChannelsCount](../../aspose.imaging.imageoptions/psdoptions/channelscount/) { get; set; } | Gets or sets the color channels count. |
| [ColorMode](../../aspose.imaging.imageoptions/psdoptions/colormode/) { get; set; } | Gets or sets the psd color mode. |
| [CompressionMethod](../../aspose.imaging.imageoptions/psdoptions/compressionmethod/) { get; set; } | Gets or sets the psd compression method. |
| [Disposed](../../aspose.imaging/disposableobject/disposed/) { get; } | Gets a value indicating whether this instance is disposed. |
| virtual [ExifData](../../aspose.imaging/imageoptionsbase/exifdata/) { get; set; } | Gets or sets the Exif data. |
| [FullFrame](../../aspose.imaging/imageoptionsbase/fullframe/) { get; set; } | Gets or sets a value indicating whether [full frame]. |
| [KeepMetadata](../../aspose.imaging/imageoptionsbase/keepmetadata/) { get; set; } | Gets a value whether to keep original image metadata on export. |
| [MultiPageOptions](../../aspose.imaging/imageoptionsbase/multipageoptions/) { get; set; } | The multipage options |
| virtual [Palette](../../aspose.imaging/imageoptionsbase/palette/) { get; set; } | Gets or sets the color palette. |
| [ProgressEventHandler](../../aspose.imaging/imageoptionsbase/progresseventhandler/) { get; set; } | Gets or sets the progress event handler. |
| [PsdVersion](../../aspose.imaging.imageoptions/psdoptions/psdversion/) { get; set; } | Gets or sets the file format version. It can be PSD or PSB. |
| [RefreshImagePreviewData](../../aspose.imaging.imageoptions/psdoptions/refreshimagepreviewdata/) { get; set; } | Gets or sets a value indicating whether [refresh image preview data] - option used to maximize compatibility with another PSD image viewers. Please note, text layers drawing to final layout is not supported for Compact Framework platform |
| [RemoveGlobalTextEngineResource](../../aspose.imaging.imageoptions/psdoptions/removeglobaltextengineresource/) { get; set; } | Gets or sets a value indicating whether - Remove the global text engine resource - Used for some text-layered psd files, in only case, when they can not be opened in Adobe Photoshop after processing (mostly for absent fonts text layers related). After using this option, user need to Make next in opened in Photoshop file: Menu "Text" -&gt; "Process absent fonts". After that operation all text will appear again. Please note, that this operation may cause some final layout changes. |
| virtual [ResolutionSettings](../../aspose.imaging/imageoptionsbase/resolutionsettings/) { get; set; } | Gets or sets the resolution settings. |
| [Source](../../aspose.imaging/imageoptionsbase/source/) { get; set; } | Gets or sets the source to create image in. |
| [VectorizationOptions](../../aspose.imaging.imageoptions/psdoptions/vectorizationoptions/) { get; set; } | Gets or sets the PSD vectorization options. |
| [VectorRasterizationOptions](../../aspose.imaging/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | Gets or sets the vector rasterization options. |
| [Version](../../aspose.imaging.imageoptions/psdoptions/version/) { get; set; } | Gets or sets the psd file version. |
| override [XmpData](../../aspose.imaging.imageoptions/psdoptions/xmpdata/) { get; set; } | Get or set XMP data container |

## Methods

| Name | Description |
| --- | --- |
| virtual [Clone](../../aspose.imaging/imageoptionsbase/clone/)() | Creates a memberwise clone of this instance. |
| [Dispose](../../aspose.imaging/disposableobject/dispose/)() | Disposes the current instance. |
| [TrySetMetadata](../../aspose.imaging/imageoptionsbase/trysetmetadata/)(IImageMetadataFormat) | Tries to set a *metadata* instance, if this [`Image`](../../aspose.imaging/image/) instance supports and implements [`IImageMetadataFormat`](../../aspose.imaging.metadata/iimagemetadataformat/) instance. |

## Examples

This example demonstrates the use of Aspsoe.Imaging for .Net API to convert Images to PSD format. To achieve this goal this example loads an existing image and then saves it back to PSD format.

```csharp
[C#]

string dir = "c:\\temp\\";

//Creates an instance of image class and initialize it with an existing file through File path
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    //Create an instance of PsdOptions class
    Aspose.Imaging.ImageOptions.PsdOptions psdOptions = new Aspose.Imaging.ImageOptions.PsdOptions();

    //Set the CompressionMethod as RLE
    //Note: Other supported CompressionMethod is CompressionMethod.RAW [No Compression]
    psdOptions.CompressionMethod = Aspose.Imaging.FileFormats.Psd.CompressionMethod.RLE;

    //Set the ColorMode to GrayScale
    //Note: Other supported ColorModes are ColorModes.Bitmap and ColorModes.RGB
    psdOptions.ColorMode = Aspose.Imaging.FileFormats.Psd.ColorModes.Grayscale;

    //Save the image to disk location with supplied PsdOptions settings
    image.Save(dir + "output.psd", psdOptions);
}
```

The following example shows how to convert a multipage vector image to PSD format in general way without referencing to a particular image type.

```csharp
[C#]

string dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
string inputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr");
string outputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr.psd");

Aspose.Imaging.ImageOptionsBase exportOptions = new Aspose.Imaging.ImageOptions.PsdOptions();

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFilePath))
{
    exportOptions.MultiPageOptions = null;

    // Export only first two pages. These pages will be presented as layers in the output PSD.
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


