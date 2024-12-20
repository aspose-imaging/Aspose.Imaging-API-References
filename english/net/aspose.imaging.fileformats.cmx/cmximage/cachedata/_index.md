---
title: CmxImage.CacheData
second_title: Aspose.Imaging for .NET API Reference
description: CmxImage method. Cache the data to prevent additional loading from the underlying source DataStreamContainer with this convenient method. Ideal for developers seeking to optimize performance by preloading data ensuring faster access and smoother operation in their applications
type: docs
weight: 110
url: /net/aspose.imaging.fileformats.cmx/cmximage/cachedata/
---
## CmxImage.CacheData method

Cache the data to prevent additional loading from the underlying source [`DataStreamContainer`](../../../aspose.imaging/datastreamsupporter/datastreamcontainer/) with this convenient method. Ideal for developers seeking to optimize performance by preloading data, ensuring faster access and smoother operation in their applications.

```csharp
public override void CacheData()
```

## Examples

The following example shows how to cache all pages of a CMX image.

```csharp
[C#]

string dir = "c:\\temp\\";

// Load an image from a CMX file.
using (Aspose.Imaging.FileFormats.Cmx.CmxImage image = (Aspose.Imaging.FileFormats.Cmx.CmxImage)Aspose.Imaging.Image.Load(dir + "sample.cmx"))
{
    // This call caches only the default page.
    image.CacheData();

    // Cache all pages so that no additional data loading will be performed from the underlying data stream.
    foreach (Aspose.Imaging.FileFormats.Cmx.CmxImagePage page in image.Pages)
    {
        page.CacheData();
    }
}
```

### See Also

* class [CmxImage](../)
* namespace [Aspose.Imaging.FileFormats.Cmx](../../cmximage/)
* assembly [Aspose.Imaging](../../../)


