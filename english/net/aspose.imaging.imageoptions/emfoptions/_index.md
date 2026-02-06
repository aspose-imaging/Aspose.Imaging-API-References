---
title: Class EmfOptions
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.ImageOptions.EmfOptions class. The Emf options
type: docs
weight: 10310
url: /net/aspose.imaging.imageoptions/emfoptions/
---
## EmfOptions class

The Emf options.

```csharp
public class EmfOptions : MetafileOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfOptions](emfoptions/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [BufferSizeHint](../../aspose.imaging/imageoptionsbase/buffersizehint/) { get; set; } | Gets or sets the buffer size hint which is defined max allowed size for all internal buffers. |
| [Compress](../../aspose.imaging.imageoptions/metafileoptions/compress/) { get; set; } | Gets or sets a value indicating whether this ICompressedOptions is compressed. |
| [Disposed](../../aspose.imaging/disposableobject/disposed/) { get; } | Gets a value indicating whether this instance is disposed. |
| virtual [ExifData](../../aspose.imaging/imageoptionsbase/exifdata/) { get; set; } | Gets or sets the Exif data. |
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

## Examples

The following example shows how to convert a emz images to emf fromat

```csharp
[C#]

string file = "example.emz";
string baseFolder = System.IO.Path.Combine("D:", "Compressed");
string inputFile = System.IO.Path.Combine(baseFolder, file);
string outFile = inputFile + ".emf";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFile))
{
    Aspose.Imaging.ImageOptions.VectorRasterizationOptions vectorRasterizationOptions = new Aspose.Imaging.ImageOptions.EmfRasterizationOptions {PageSize = image.Size};
    image.Save(outFile, new Aspose.Imaging.ImageOptions.EmfOptions {VectorRasterizationOptions = vectorRasterizationOptions});
}
```

The following example shows how to convert a emf images to emz fromat

```csharp
[C#]

string file = "input.emf";
string baseFolder = System.IO.Path.Combine("D:", "Compressed");
string inputFile = System.IO.Path.Combine(baseFolder, file);
string outFile = inputFile + ".emz";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFile))
{
    Aspose.Imaging.ImageOptions.VectorRasterizationOptions vectorRasterizationOptions = new Aspose.Imaging.ImageOptions.EmfRasterizationOptions() { PageSize = image.Size};
    image.Save(outFile, new Aspose.Imaging.ImageOptions.EmfOptions() {VectorRasterizationOptions = vectorRasterizationOptions, Compress = true});
}
```

The following example shows how to convert a multipage vector image to EMF format in general way without referencing to a particular image type.

```csharp
[C#]

string dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
string inputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr");
string outputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr.emf");

Aspose.Imaging.ImageOptionsBase exportOptions = new Aspose.Imaging.ImageOptions.EmfOptions();

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFilePath))
{
    exportOptions.MultiPageOptions = null;

    // Export only first two pages. In fact, only one page will be converted because EMF is not a multi-page format.
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

* class [MetafileOptions](../metafileoptions/)
* namespace [Aspose.Imaging.ImageOptions](../../aspose.imaging.imageoptions/)
* assembly [Aspose.Imaging](../../)


