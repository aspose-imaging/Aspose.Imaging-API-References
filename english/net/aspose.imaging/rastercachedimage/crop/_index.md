---
title: RasterCachedImage.Crop
second_title: Aspose.Imaging for .NET API Reference
description: RasterCachedImage method. Cropping the image
type: docs
weight: 100
url: /net/aspose.imaging/rastercachedimage/crop/
---
## RasterCachedImage.Crop method

Cropping the image.

```csharp
public override void Crop(Rectangle rectangle)
```

| Parameter | Type | Description |
| --- | --- | --- |
| rectangle | Rectangle | The rectangle. |

## Examples

The following example crops a raster cached image. The cropping area is be specified via Aspose.Imaging.Rectangle.

```csharp
[C#]

string dir = @"c:\temp\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterCachedImage rasterImage = (Aspose.Imaging.RasterCachedImage)image;

    // Crop the image. The cropping area is the rectangular central area of the image.
    Aspose.Imaging.Rectangle area = new Aspose.Imaging.Rectangle(rasterImage.Width / 4, rasterImage.Height / 4, rasterImage.Width / 2, rasterImage.Height / 2);
    rasterImage.Crop(area);

    // Save the cropped image to PNG
    rasterImage.Save(dir + "sample.Crop.png");
}
```

### See Also

* struct [Rectangle](../../rectangle/)
* class [RasterCachedImage](../)
* namespace [Aspose.Imaging](../../rastercachedimage/)
* assembly [Aspose.Imaging](../../../)


