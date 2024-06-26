---
title: MultiPageOptions.Pages
second_title: Aspose.Imaging for .NET API Reference
description: MultiPageOptions property. Gets or sets the pages
type: docs
weight: 70
url: /net/aspose.imaging.imageoptions/multipageoptions/pages/
---
## MultiPageOptions.Pages property

Gets or sets the pages.

```csharp
public int[] Pages { get; set; }
```

### Property Value

The pages.

## Examples

This example shows how to convert a multi-page DJVU image to a multi-frame TIFF image.

```csharp
[C#]

string dir = "c:\\temp\\";

// Load a DJVU image from a file stream.
using (System.IO.Stream stream = System.IO.File.OpenRead(dir + "sample.djvu"))
{
    using (Aspose.Imaging.FileFormats.Djvu.DjvuImage djvuImage = new Aspose.Imaging.FileFormats.Djvu.DjvuImage(stream))
    {
        Aspose.Imaging.ImageOptions.TiffOptions saveOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);
        saveOptions.Compression = Aspose.Imaging.FileFormats.Tiff.Enums.TiffCompressions.Deflate;

        // Note that if the image is colorful, it will be automatically converted to B/W format according to the option below:
        saveOptions.BitsPerSample = new ushort[] { 1 };

        saveOptions.MultiPageOptions = new Aspose.Imaging.ImageOptions.DjvuMultiPageOptions();

        // By default, all pages will be stored to the output TIFF, but the desired set of pages can be specified explicitly.
        // Only the first and the second page will be exported.
        saveOptions.MultiPageOptions.Pages = new int[] { 0, 1 };

        // Set page titles.
        saveOptions.MultiPageOptions.PageTitles = new string[] { "The First Page", "The Second Page" };

        // Save to TIFF
        djvuImage.Save(dir + "sample.tif", saveOptions);
    }
}
```

### See Also

* class [MultiPageOptions](../)
* namespace [Aspose.Imaging.ImageOptions](../../multipageoptions/)
* assembly [Aspose.Imaging](../../../)


