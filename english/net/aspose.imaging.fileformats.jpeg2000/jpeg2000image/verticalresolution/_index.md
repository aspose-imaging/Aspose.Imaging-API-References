---
title: Jpeg2000Image.VerticalResolution
second_title: Aspose.Imaging for .NET API Reference
description: Jpeg2000Image property. This property provides access to the vertical resolution of the RasterImage measured in pixels per inch PPI. Modifying this resolution can affect the quality and size of the image when printed or displayed. By adjusting the vertical resolution users can optimize the image for different output devices or applications ensuring optimal visual rendering
type: docs
weight: 100
url: /net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/verticalresolution/
---
## Jpeg2000Image.VerticalResolution property

This property provides access to the vertical resolution of the [`RasterImage`](../../../aspose.imaging/rasterimage/), measured in pixels per inch (PPI). Modifying this resolution can affect the quality and size of the image when printed or displayed. By adjusting the vertical resolution, users can optimize the image for different output devices or applications, ensuring optimal visual rendering.

```csharp
public override double VerticalResolution { get; set; }
```

### Property Value

The vertical resolution.

## Remarks

Note by default this value is always 96 since different platforms cannot return the screen resolution. You may consider using the SetResolution method for updating both resolution values in single call.

## Examples

The following example shows how to set horizontal/vertical resolution of a JPEG2000 image.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.jp2"))
{
    Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image jpeg2000Image = (Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image)image;

    // Get horizontal and vertical resolution of the Jpeg2000Image.
    double horizontalResolution = jpeg2000Image.HorizontalResolution;
    double verticalResolution = jpeg2000Image.VerticalResolution;
    System.Console.WriteLine("The horizontal resolution, in pixels per inch: {0}", horizontalResolution);
    System.Console.WriteLine("The vertical resolution, in pixels per inch: {0}", verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0)
    {
        // Use the SetResolution method for updating both resolution values in a single call.
        System.Console.WriteLine("Set resolution values to 96 dpi");
        jpeg2000Image.SetResolution(96.0, 96.0);

        System.Console.WriteLine("The horizontal resolution, in pixels per inch: {0}", jpeg2000Image.HorizontalResolution);
        System.Console.WriteLine("The vertical resolution, in pixels per inch: {0}", jpeg2000Image.VerticalResolution);
    }
}
```

### See Also

* class [Jpeg2000Image](../)
* namespace [Aspose.Imaging.FileFormats.Jpeg2000](../../jpeg2000image/)
* assembly [Aspose.Imaging](../../../)


