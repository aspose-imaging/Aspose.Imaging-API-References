---
title: VectorImage.GetEmbeddedImages
second_title: Aspose.Imaging for .NET API Reference
description: VectorImage method. Gets the embedded images
type: docs
weight: 70
url: /net/aspose.imaging/vectorimage/getembeddedimages/
---
## VectorImage.GetEmbeddedImages method

Gets the embedded images.

```csharp
public virtual EmbeddedImage[] GetEmbeddedImages()
```

### Return Value

Array of images

## Examples

Support extracting embedded raster images from a vector image

```csharp
[C#]

var inputFileName = "test.cdr";
using (var image = Aspose.Imaging.Image.Load(inputFileName))        
{
    var vectorImage = ((Aspose.Imaging.VectorImage) image);
    var images = vectorImage.GetEmbeddedImages();
    var i = 0;
    foreach (var im in images)
    {
        var outFileName = string.Format("image{0}.png", i++);
        using (im)
        {
            im.Image.Save(outFileName, new PngOptions());
        }
    }
}
```

### See Also

* class [EmbeddedImage](../../embeddedimage/)
* class [VectorImage](../)
* namespace [Aspose.Imaging](../../vectorimage/)
* assembly [Aspose.Imaging](../../../)


