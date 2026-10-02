---
title: TiffFrame.HorizontalResolution
second_title: Aspose.Imaging for .NET API Reference
description: TiffFrame property. Gets or sets the horizontal resolution in pixels per inch of this RasterImage
type: docs
weight: 100
url: /net/aspose.imaging.fileformats.tiff/tiffframe/horizontalresolution/
---
## TiffFrame.HorizontalResolution property

Gets or sets the horizontal resolution, in pixels per inch, of this [`RasterImage`](../../../aspose.imaging/rasterimage/).

```csharp
public override double HorizontalResolution { get; set; }
```

### Property Value

The horizontal resolution.

## Examples

The following example shows how to set horizontal/vertical resolution of a separate TIFF frame.

```csharp
[C#]

string dir = "c:\\temp\\";

// Load a TIFF image from a file.
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.tif"))
{
    Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = (Aspose.Imaging.FileFormats.Tiff.TiffImage)image;

    int i = 0;
    foreach (Aspose.Imaging.FileFormats.Tiff.TiffFrame frame in tiffImage.Frames)
    {
        // Get horizontal and vertical resolution of the TiffFrame.
        double horizontalResolution = frame.HorizontalResolution;
        double verticalResolution = frame.VerticalResolution;
        System.Console.WriteLine("The horizontal resolution of frame {0}, pixels per inch: {1}", i, horizontalResolution);
        System.Console.WriteLine("The vertical resolution, of frame {0}, pixels per inch: {1}", i, verticalResolution);

        if (horizontalResolution != 96.0 || verticalResolution != 96.0)
        {
            // Use the SetResolution method for updating both resolution values in a single call.
            System.Console.WriteLine("Set resolution values to 96 dpi");
            frame.SetResolution(96.0, 96.0);

            System.Console.WriteLine("The horizontal resolution of frame {0}, pixels per inch: {1}", i, horizontalResolution);
            System.Console.WriteLine("The vertical resolution, of frame {0}, pixels per inch: {1}", i, verticalResolution);
        }

        ++i;
    }
}
```

### See Also

* class [TiffFrame](../)
* namespace [Aspose.Imaging.FileFormats.Tiff](../../tiffframe/)
* assembly [Aspose.Imaging](../../../)


