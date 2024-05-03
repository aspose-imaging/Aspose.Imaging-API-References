---
title: DjvuPage.PageNumber
second_title: Aspose.Imaging for .NET API Reference
description: DjvuPage property. Gets the page number
type: docs
weight: 50
url: /net/aspose.imaging.fileformats.djvu/djvupage/pagenumber/
---
## DjvuPage.PageNumber property

Gets the page number.

```csharp
public int PageNumber { get; }
```

### Property Value

The page number.

## Examples

This example shows how to load a DJVU image from a file stream and print information about the pages.

```csharp
[C#]

string dir = "c:\\temp\\";

// Load a DJVU image from a file stream.
using (System.IO.Stream stream = System.IO.File.OpenRead(dir + "sample.djvu"))
{
    using (Aspose.Imaging.FileFormats.Djvu.DjvuImage djvuImage = new Aspose.Imaging.FileFormats.Djvu.DjvuImage(stream))
    {
        System.Console.WriteLine("The total number of pages: {0}", djvuImage.Pages.Length);
        System.Console.WriteLine("The active page number:    {0}", djvuImage.ActivePage.PageNumber);
        System.Console.WriteLine("The first page number:     {0}", djvuImage.FirstPage.PageNumber);
        System.Console.WriteLine("The last page number:      {0}", djvuImage.LastPage.PageNumber);

        foreach (Aspose.Imaging.FileFormats.Djvu.DjvuPage djvuPage in djvuImage.Pages)
        {
            System.Console.WriteLine("--------------------------------------------------");
            System.Console.WriteLine("Page number:     {0}", djvuPage.PageNumber);
            System.Console.WriteLine("Page size:       {0}", djvuPage.Size);
            System.Console.WriteLine("Page raw format: {0}", djvuPage.RawDataFormat);
        }
    }
}

//The output may look like this:
//The total number of pages: 2
//The active page number:    1
//The first page number:     1
//The last page number:      2
//--------------------------------------------------
//Page number:     1
//Page size:       { Width = 2481, Height = 3508}
//Page raw format: RgbIndexed1Bpp, used channels: 1
//--------------------------------------------------
//Page number:     2
//Page size:       { Width = 2481, Height = 3508}
//Page raw format: RgbIndexed1Bpp, used channels: 1
```

### See Also

* class [DjvuPage](../)
* namespace [Aspose.Imaging.FileFormats.Djvu](../../djvupage/)
* assembly [Aspose.Imaging](../../../)


