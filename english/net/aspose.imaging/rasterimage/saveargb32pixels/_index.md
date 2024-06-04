---
title: RasterImage.SaveArgb32Pixels
second_title: Aspose.Imaging for .NET API Reference
description: RasterImage method. Saves the 32bit ARGB pixels
type: docs
weight: 540
url: /net/aspose.imaging/rasterimage/saveargb32pixels/
---
## RasterImage.SaveArgb32Pixels method

Saves the 32-bit ARGB pixels.

```csharp
public void SaveArgb32Pixels(Rectangle rectangle, int[] pixels)
```

| Parameter | Type | Description |
| --- | --- | --- |
| rectangle | Rectangle | The rectangle to save pixels to. |
| pixels | Int32[] | The 32-bit ARGB pixels array. |

## Examples

The following example fills the central area of a raster image with black pixels using the Aspose.Imaging.RasterImage.SaveArgb32Pixels method.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // The black square
    int[] pixels = new int[(rasterImage.Width / 2) * (rasterImage.Height / 2)];
    for (int i = 0; i < pixels.Length; i++)
    {
        pixels[i] = Color.Black.ToArgb();
    }

    // Draw the black square at the center of the image.
    Aspose.Imaging.Rectangle area = new Aspose.Imaging.Rectangle(rasterImage.Width / 4, rasterImage.Height / 4, rasterImage.Width / 2, rasterImage.Height / 2);
    rasterImage.SaveArgb32Pixels(area, pixels);

    rasterImage.Save(dir + "sample.SaveArgb32Pixels.png");
}
```

### See Also

* struct [Rectangle](../../rectangle/)
* class [RasterImage](../)
* namespace [Aspose.Imaging](../../rasterimage/)
* assembly [Aspose.Imaging](../../../)


