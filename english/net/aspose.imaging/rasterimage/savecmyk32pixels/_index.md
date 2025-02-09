---
title: RasterImage.SaveCmyk32Pixels
second_title: Aspose.Imaging for .NET API Reference
description: RasterImage method. Saves the pixels
type: docs
weight: 540
url: /net/aspose.imaging/rasterimage/savecmyk32pixels/
---
## RasterImage.SaveCmyk32Pixels method

Saves the pixels.

```csharp
public void SaveCmyk32Pixels(Rectangle rectangle, int[] pixels)
```

| Parameter | Type | Description |
| --- | --- | --- |
| rectangle | Rectangle | The rectangle to save pixels to. |
| pixels | Int32[] | The CMYK pixels presented as the 32-bit integer values. |

## Examples

The following example fills the central area of a raster image with black pixels using the Aspose.Imaging.RasterImage.SaveCmyk32Pixels method.

```csharp
[C#]

string dir = @"c:\temp\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // Get an integer representation of black in the CMYK color space.
    int blackCmyk = Aspose.Imaging.CmykColorHelper.ToCmyk(Color.Black);

    // The black square.
    int[] pixels = new int[(rasterImage.Width / 2) * (rasterImage.Height / 2)];
    for (int i = 0; i < pixels.Length; i++)
    {
        pixels[i] = blackCmyk;
    }

    // Draw the black square at the center of the image.
    Aspose.Imaging.Rectangle area = new Aspose.Imaging.Rectangle(rasterImage.Width / 4, rasterImage.Height / 4, rasterImage.Width / 2, rasterImage.Height / 2);
    rasterImage.SaveCmyk32Pixels(area, pixels);

    rasterImage.Save(dir + "sample.SaveCmyk32Pixels.png");
}
```

### See Also

* struct [Rectangle](../../rectangle/)
* class [RasterImage](../)
* namespace [Aspose.Imaging](../../rasterimage/)
* assembly [Aspose.Imaging](../../../)


