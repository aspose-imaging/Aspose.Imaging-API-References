---
title: CdrImagePage.CacheData
second_title: Aspose.Imaging for .NET API Reference
description: CdrImagePage method. Caches the data and ensures no additional data loading will be performed from the underlying DataStreamContainer
type: docs
weight: 90
url: /net/aspose.imaging.fileformats.cdr/cdrimagepage/cachedata/
---
## CdrImagePage.CacheData method

Caches the data and ensures no additional data loading will be performed from the underlying [`DataStreamContainer`](../../../aspose.imaging/datastreamsupporter/datastreamcontainer/).

```csharp
public override void CacheData()
```

## Examples

The following example shows how to cache all pages of a CDR image.

```csharp
[C#]

string dir = "c:\\temp\\";

// Load an image from a CDR file.
using (Aspose.Imaging.FileFormats.Cdr.CdrImage image = (Aspose.Imaging.FileFormats.Cdr.CdrImage)Aspose.Imaging.Image.Load(dir + "sample.cdr"))
{
    // This call caches only the default page.
    image.CacheData();

    // Cache all pages so that no additional data loading will be performed from the underlying data stream.
    foreach (Aspose.Imaging.FileFormats.Cdr.CdrImagePage page in image.Pages)
    {
        page.CacheData();
    }
}
```

### See Also

* class [CdrImagePage](../)
* namespace [Aspose.Imaging.FileFormats.Cdr](../../cdrimagepage/)
* assembly [Aspose.Imaging](../../../)


