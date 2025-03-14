---
title: RasterImage.SetResolution
second_title: Aspose.Imaging for .NET API Reference
description: RasterImage method. Sets the resolution for this RasterImage
type: docs
weight: 600
url: /net/aspose.imaging/rasterimage/setresolution/
---
## RasterImage.SetResolution method

Sets the resolution for this [`RasterImage`](../).

```csharp
public virtual void SetResolution(double dpiX, double dpiY)
```

| Parameter | Type | Description |
| --- | --- | --- |
| dpiX | Double | The horizontal resolution, in dots per inch, of the [`RasterImage`](../). |
| dpiY | Double | The vertical resolution, in dots per inch, of the [`RasterImage`](../). |

## Examples

The following example shows how to set horizontal/vertical resolution of a raster image.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.jpg"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // Get horizontal and vertical resolution of the image
    double horizontalResolution = rasterImage.HorizontalResolution;
    double verticalResolution = rasterImage.VerticalResolution;
    System.Console.WriteLine("The horizontal resolution, in pixels per inch: {0}", horizontalResolution);
    System.Console.WriteLine("The vertical resolution, in pixels per inch: {0}", verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0)
    {
        // Use the SetResolution method for updating both resolution values in a single call.
        System.Console.WriteLine("Set resolution values to 96 dpi");
        rasterImage.SetResolution(96.0, 96.0);

        System.Console.WriteLine("The horizontal resolution, in pixels per inch: {0}", rasterImage.HorizontalResolution);
        System.Console.WriteLine("The vertical resolution, in pixels per inch: {0}", rasterImage.VerticalResolution);
    }

    // The output may look like this:
    // The horizontal resolution, in pixels per inch: 300
    // The vertical resolution, in pixels per inch: 300
    // Set resolution values to 96 dpi
    // The horizontal resolution, in pixels per inch: 96
    // The vertical resolution, in pixels per inch: 96
}
```

### See Also

* class [RasterImage](../)
* namespace [Aspose.Imaging](../../rasterimage/)
* assembly [Aspose.Imaging](../../../)


