---
title: CdrImage.CacheData
second_title: Aspose.Imaging for .NET API Reference
description: CdrImage method. Effortlessly cache the data to prevent additional loading from the underlying source with this userfriendly method. Ideal for developers seeking to optimize performance by preloading data ensuring faster access and smoother operation in their applications. DataStreamContainer
type: docs
weight: 110
url: /net/aspose.imaging.fileformats.cdr/cdrimage/cachedata/
---
## CdrImage.CacheData method

Effortlessly cache the data to prevent additional loading from the underlying source with this user-friendly method. Ideal for developers seeking to optimize performance by preloading data, ensuring faster access and smoother operation in their applications. [`DataStreamContainer`](../../../aspose.imaging/datastreamsupporter/datastreamcontainer/).

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

* class [CdrImage](../)
* namespace [Aspose.Imaging.FileFormats.Cdr](../../cdrimage/)
* assembly [Aspose.Imaging](../../../)


