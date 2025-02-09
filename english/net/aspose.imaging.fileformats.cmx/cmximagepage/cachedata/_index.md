---
title: CmxImagePage.CacheData
second_title: Aspose.Imaging for .NET API Reference
description: CmxImagePage method. Cache can not be used
type: docs
weight: 100
url: /net/aspose.imaging.fileformats.cmx/cmximagepage/cachedata/
---
## CmxImagePage.CacheData method

Cache can not be used.

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

* class [CmxImagePage](../)
* namespace [Aspose.Imaging.FileFormats.Cmx](../../cmximagepage/)
* assembly [Aspose.Imaging](../../../)


