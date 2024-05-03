---
title: TiffImage.SetResolution
second_title: Aspose.Imaging for .NET API Reference
description: TiffImage method. Establishes the resolution for the specified RasterImage enabling precise control over image rendering and display properties. Integrate this functionality to optimize visual output and ensure compatibility with diverse output devices and platforms enhancing the overall user experience
type: docs
weight: 390
url: /net/aspose.imaging.fileformats.tiff/tiffimage/setresolution/
---
## TiffImage.SetResolution method

Establishes the resolution for the specified [`RasterImage`](../../../aspose.imaging/rasterimage/), enabling precise control over image rendering and display properties. Integrate this functionality to optimize visual output and ensure compatibility with diverse output devices and platforms, enhancing the overall user experience.

```csharp
public override void SetResolution(double dpiX, double dpiY)
```

| Parameter | Type | Description |
| --- | --- | --- |
| dpiX | Double | The horizontal resolution, in dots per inch, of the [`RasterImage`](../../../aspose.imaging/rasterimage/). |
| dpiY | Double | The vertical resolution, in dots per inch, of the [`RasterImage`](../../../aspose.imaging/rasterimage/). |

## Examples

The following example shows how to set horizontal/vertical resolution of a TIFF image.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.tif"))
{
    Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = (Aspose.Imaging.FileFormats.Tiff.TiffImage)image;

    // Get horizontal and vertical resolution of the TiffImage.
    double horizontalResolution = tiffImage.HorizontalResolution;
    double verticalResolution = tiffImage.VerticalResolution;
    System.Console.WriteLine("The horizontal resolution, in pixels per inch: {0}", horizontalResolution);
    System.Console.WriteLine("The vertical resolution, in pixels per inch: {0}", verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0)
    {
        // Use the SetResolution method for updating both resolution values in a single call.
        System.Console.WriteLine("Set resolution values to 96 dpi");
        tiffImage.SetResolution(96.0, 96.0);

        System.Console.WriteLine("The horizontal resolution, in pixels per inch: {0}", tiffImage.HorizontalResolution);
        System.Console.WriteLine("The vertical resolution, in pixels per inch: {0}", tiffImage.VerticalResolution);
    }
}
```

### See Also

* class [TiffImage](../)
* namespace [Aspose.Imaging.FileFormats.Tiff](../../tiffimage/)
* assembly [Aspose.Imaging](../../../)


