---
title: CmxImage.Pages
second_title: Aspose.Imaging for .NET API Reference
description: CmxImage property. Retrieve the pages of the image seamlessly with this intuitive property. Ideal for developers seeking to access and manipulate individual pages within multipage images ensuring efficient navigation and processing
type: docs
weight: 100
url: /net/aspose.imaging.fileformats.cmx/cmximage/pages/
---
## CmxImage.Pages property

Retrieve the pages of the image seamlessly with this intuitive property. Ideal for developers seeking to access and manipulate individual pages within multi-page images, ensuring efficient navigation and processing.

```csharp
public override Image[] Pages { get; }
```

### Property Value

The pages.

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

* class [Image](../../../aspose.imaging/image/)
* class [CmxImage](../)
* namespace [Aspose.Imaging.FileFormats.Cmx](../../cmximage/)
* assembly [Aspose.Imaging](../../../)


