---
title: DjvuImage.Pages
second_title: Aspose.Imaging for .NET API Reference
description: DjvuImage property. Access the individual pages of your DjVu image collection with this property. Simplify navigation and manipulation of your document or book stored in DjVu format by accessing each page directly. Improve your workflow efficiency with easy page retrieval
type: docs
weight: 120
url: /net/aspose.imaging.fileformats.djvu/djvuimage/pages/
---
## DjvuImage.Pages property

Access the individual pages of your DjVu image collection with this property. Simplify navigation and manipulation of your document or book stored in DjVu format by accessing each page directly. Improve your workflow efficiency with easy page retrieval.

```csharp
public override Image[] Pages { get; }
```

### Property Value

The pages.

## Examples

This example shows how to load a DJVU image from a file stream.

```csharp
[C#]

string dir = "c:\\temp\\";

// Load a DJVU image from a file stream.
using (System.IO.Stream stream = System.IO.File.OpenRead(dir + "sample.djvu"))
{
    using (Aspose.Imaging.FileFormats.Djvu.DjvuImage djvuImage = new Aspose.Imaging.FileFormats.Djvu.DjvuImage(stream))
    {
        // Save each page as an individual PNG image.
        foreach (Aspose.Imaging.FileFormats.Djvu.DjvuPage djvuPage in djvuImage.Pages)
        {
            // Generate a file name based on the page number.
            string fileName = string.Format("sample.{0}.png", djvuPage.PageNumber);
            djvuPage.Save(dir + fileName, new Aspose.Imaging.ImageOptions.PngOptions());
        }
    }
}
```

### See Also

* class [Image](../../../aspose.imaging/image/)
* class [DjvuImage](../)
* namespace [Aspose.Imaging.FileFormats.Djvu](../../djvuimage/)
* assembly [Aspose.Imaging](../../../)


