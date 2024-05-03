---
title: RasterImage.Grayscale
second_title: Aspose.Imaging for .NET API Reference
description: RasterImage method. Transformation of an image to its grayscale representation
type: docs
weight: 360
url: /net/aspose.imaging/rasterimage/grayscale/
---
## RasterImage.Grayscale method

Transformation of an image to its grayscale representation

```csharp
public virtual void Grayscale()
```

## Examples

The following example transforms a colored raster image to its grayscale representation. Grayscale images are composed exclusively of shades of gray and carry only intensity information.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    rasterImage.Grayscale();
    rasterImage.Save(dir + "sample.Grayscale.png");
}
```

### See Also

* class [RasterImage](../)
* namespace [Aspose.Imaging](../../rasterimage/)
* assembly [Aspose.Imaging](../../../)


