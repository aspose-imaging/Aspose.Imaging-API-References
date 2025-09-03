---
title: RasterImage.LoadArgb64Pixels
second_title: Aspose.Imaging for .NET API Reference
description: RasterImage method. Loads 64bit ARGB pixels
type: docs
weight: 410
url: /net/aspose.imaging/rasterimage/loadargb64pixels/
---
## RasterImage.LoadArgb64Pixels method

Loads 64-bit ARGB pixels.

```csharp
public long[] LoadArgb64Pixels(Rectangle rectangle)
```

| Parameter | Type | Description |
| --- | --- | --- |
| rectangle | Rectangle | The rectangle to load pixels from. |

### Return Value

The loaded 64-bit ARGB pixels array.

## Examples

The following example shows how to load and process pixels of a raster image. The pixels are represented as 64-bit integer values. For example, consider a problem of counting of fully transparent pixels of an image.

```csharp
[C#]

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(@"c:\temp\16rgba.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // Load pixels for the whole image. Any rectangular part of the image can be specified as a parameter of the Aspose.Imaging.RasterImage.LoadArgb64Pixels method.
    // Note that the image itself must have 16 bits per sample, because Aspose.Imaging.RasterImage.LoadArgb64Pixels doesn't work with 8 bit per sample.
    // In order to work with 8 bits per sample please use the good old Aspose.Imaging.RasterImage.LoadArgb32Pixels method.
    long[] pixels = rasterImage.LoadArgb64Pixels(rasterImage.Bounds);

    int count = 0;
    foreach (int pixel in pixels)
    {
        // Note that all color components including alpha are represented by 16-bit values, so their allowed values are in the range [0, 63535].
        int alpha = (pixel >> 48) & 0xffff;
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


