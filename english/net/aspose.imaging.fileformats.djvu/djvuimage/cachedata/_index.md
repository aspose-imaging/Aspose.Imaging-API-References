---
title: DjvuImage.CacheData
second_title: Aspose.Imaging for .NET API Reference
description: DjvuImage method. Cache the data privately to optimize performance and reduce the need for repeated data retrieval from external sources. This approach also helps conserve resources particularly in scenarios where data access is frequent or resources are limited
type: docs
weight: 210
url: /net/aspose.imaging.fileformats.djvu/djvuimage/cachedata/
---
## DjvuImage.CacheData method

Cache the data privately to optimize performance and reduce the need for repeated data retrieval from external sources. This approach also helps conserve resources, particularly in scenarios where data access is frequent or resources are limited.

```csharp
public override void CacheData()
```

## Examples

The following example shows how to cache all pages of a DJVU image.

```csharp
[C#]

string dir = "c:\\temp\\";

// Load an image from a DJVU file.
using (Aspose.Imaging.FileFormats.Djvu.DjvuImage image = (Aspose.Imaging.FileFormats.Djvu.DjvuImage)Aspose.Imaging.Image.Load(dir + "sample.djvu"))
{
    // This call caches all the pages so that no additional data loading will be performed from the underlying data stream.
    image.CacheData();

    // Or you can cache the pages individually.
    foreach (Aspose.Imaging.FileFormats.Djvu.DjvuPage page in image.Pages)
    {
        page.CacheData();
    }
}
```

### See Also

* class [DjvuImage](../)
* namespace [Aspose.Imaging.FileFormats.Djvu](../../djvuimage/)
* assembly [Aspose.Imaging](../../../)


