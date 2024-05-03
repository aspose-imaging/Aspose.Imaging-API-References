---
title: RasterImage.VerticalResolution
second_title: Aspose.Imaging for .NET API Reference
description: RasterImage property. Gets or sets the vertical resolution in pixels per inch of this RasterImage
type: docs
weight: 170
url: /net/aspose.imaging/rasterimage/verticalresolution/
---
## RasterImage.VerticalResolution property

Gets or sets the vertical resolution, in pixels per inch, of this [`RasterImage`](../).

```csharp
public virtual double VerticalResolution { get; set; }
```

### Property Value

The vertical resolution.

## Remarks

Note by default this value is always 96 since different platforms cannot return the screen resolution. You may consider using the SetResolution method for updating both resolution values in single call.

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


