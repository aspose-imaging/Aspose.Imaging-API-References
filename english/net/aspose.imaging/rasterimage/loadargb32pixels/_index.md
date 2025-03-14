---
title: RasterImage.LoadArgb32Pixels
second_title: Aspose.Imaging for .NET API Reference
description: RasterImage method. Loads 32bit ARGB pixels
type: docs
weight: 360
url: /net/aspose.imaging/rasterimage/loadargb32pixels/
---
## RasterImage.LoadArgb32Pixels method

Loads 32-bit ARGB pixels.

```csharp
public int[] LoadArgb32Pixels(Rectangle rectangle)
```

| Parameter | Type | Description |
| --- | --- | --- |
| rectangle | Rectangle | The rectangle to load pixels from. |

### Return Value

The loaded 32-bit ARGB pixels array.

## Examples

The following example shows how to load and process pixels of a raster image. The pixels are represented as 32-bit integer values. For example, consider a problem of counting of fully transparent pixels of an image.

```csharp
[C#]

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(@"c:\temp\alpha.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // Load pixels for the whole image. Any rectangular part of the image can be specified as a parameter of the Aspose.Imaging.RasterImage.LoadArgb32Pixels method.
    int[] pixels = rasterImage.LoadArgb32Pixels(rasterImage.Bounds);

    int count = 0;
    foreach (int pixel in pixels)
    {
        int alpha = (pixel >> 24) & 0xff;
        if (alpha == 0)
        {
            count++;
        }
    }

    System.Console.WriteLine("The number of fully transparent pixels is {0}", count);
    System.Console.WriteLine("The total number of pixels is {0}", image.Width * image.Height);
}
```

### See Also

* struct [Rectangle](../../rectangle/)
* class [RasterImage](../)
* namespace [Aspose.Imaging](../../rasterimage/)
* assembly [Aspose.Imaging](../../../)


