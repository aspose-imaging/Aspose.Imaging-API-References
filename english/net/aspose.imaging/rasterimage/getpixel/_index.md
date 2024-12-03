---
title: RasterImage.GetPixel
second_title: Aspose.Imaging for .NET API Reference
description: RasterImage method. Gets an image pixel
type: docs
weight: 330
url: /net/aspose.imaging/rasterimage/getpixel/
---
## RasterImage.GetPixel method

Gets an image pixel.

```csharp
public Color GetPixel(int x, int y)
```

| Parameter | Type | Description |
| --- | --- | --- |
| x | Int32 | The pixel x location. |
| y | Int32 | The pixel y location. |

### Return Value

The pixel color for the specified location.

## Examples

The following example loads a raster image and obtains the color of an arbitrary pixel.

```csharp
[C#]

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(@"c:\temp\sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // Get the color of the top-left pixel of the image.
    Color color = rasterImage.GetPixel(0, 0);

    // Obtain the values of the individual color components
    byte alpha = color.A;
    byte red = color.R;
    int green = color.G;
    int blue = color.B;

    System.Console.WriteLine("The color of the pixel(0,0) is A={0},R={1},G={2},B={3}", alpha, red, green, blue);
}
```

### See Also

* struct [Color](../../color/)
* class [RasterImage](../)
* namespace [Aspose.Imaging](../../rasterimage/)
* assembly [Aspose.Imaging](../../../)


