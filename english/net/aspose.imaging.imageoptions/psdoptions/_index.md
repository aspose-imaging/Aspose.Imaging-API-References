---
title: PsdOptions
second_title: Aspose.Imaging for .NET API Reference
description: 
type: docs
weight: 10130
url: /net/aspose.imaging.imageoptions/psdoptions/
---
## PsdOptions class

The psd file format create options.

```csharp
public class PsdOptions : ImageOptionsBase
```

## Constructors

| Name | Description |
| --- | --- |
| [PsdOptions](psdoptions)() | Initializes a new instance of the [`PsdOptions`](../psdoptions) class. |
| [PsdOptions](psdoptions)(PsdOptions) | Initializes a new instance of the [`PsdOptions`](../psdoptions) class. |

## Properties

| Name | Description |
| --- | --- |
| [ChannelBitsCount](channelbitscount) { get; set; } | Gets or sets the bits count per color channel. |
| [ChannelsCount](channelscount) { get; set; } | Gets or sets the color channels count. |
| [ColorMode](colormode) { get; set; } | Gets or sets the psd color mode. |
| [CompressionMethod](compressionmethod) { get; set; } | Gets or sets the psd compression method. |
| [PsdVersion](psdversion) { get; set; } | Gets or sets the file format version. It can be PSD or PSB. |
| [RefreshImagePreviewData](refreshimagepreviewdata) { get; set; } | Gets or sets a value indicating whether [refresh image preview data] - option used to maximize compatibility with another PSD image viewers. Please note, text layers drawing to final layout is not supported for Compact Framework platform |
| [RemoveGlobalTextEngineResource](removeglobaltextengineresource) { get; set; } | Gets or sets a value indicating whether - Remove the global text engine resource - Used for some text-layered psd files, in only case, when they can not be opened in Adobe Photoshop after processing (mostly for absent fonts text layers related). After using this option, user need to Make next in opened in Photoshop file: Menu "Text" -&gt; "Process absent fonts". After that operation all text will appear again. Please note, that this operation may cause some final layout changes. |
| [VectorizationOptions](vectorizationoptions) { get; set; } | Gets or sets the PSD vectorization options. |
| [Version](version) { get; set; } | Gets or sets the psd file version. |
| override [XmpData](xmpdata) { get; set; } | Get or set XMP data container |

### Examples

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

* class [ImageOptionsBase](../../aspose.imaging/imageoptionsbase)
* namespace [Aspose.Imaging.ImageOptions](../../aspose.imaging.imageoptions)
* assembly [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
