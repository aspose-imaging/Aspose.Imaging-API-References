---
title: PngImage.HorizontalResolution
second_title: Aspose.Imaging for .NET API Reference
description: PngImage property. Retrieve or modify the horizontal resolution of the image. This property represents the number of pixels per inch along the horizontal axis of the image. Adjusting this resolution can affect the physical size of the image when printed or displayed
type: docs
weight: 90
url: /net/aspose.imaging.fileformats.png/pngimage/horizontalresolution/
---
## PngImage.HorizontalResolution property

Retrieve or modify the horizontal resolution of the image. This property represents the number of pixels per inch along the horizontal axis of the image. Adjusting this resolution can affect the physical size of the image when printed or displayed.

```csharp
public override double HorizontalResolution { get; set; }
```

## Examples

The following example shows how to set horizontal/vertical resolution of a PNG image.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.png"))
{
    Aspose.Imaging.FileFormats.Png.PngImage pngImage = (Aspose.Imaging.FileFormats.Png.PngImage)image;

    // Get horizontal and vertical resolution of the PngImage.
    double horizontalResolution = pngImage.HorizontalResolution;
    double verticalResolution = pngImage.VerticalResolution;
    System.Console.WriteLine("The horizontal resolution, in pixels per inch: {0}", horizontalResolution);
    System.Console.WriteLine("The vertical resolution, in pixels per inch: {0}", verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0)
    {
        // Use the SetResolution method for updating both resolution values in a single call.
        System.Console.WriteLine("Set resolution values to 96 dpi");
        pngImage.SetResolution(96.0, 96.0);

        System.Console.WriteLine("The horizontal resolution, in pixels per inch: {0}", pngImage.HorizontalResolution);
        System.Console.WriteLine("The vertical resolution, in pixels per inch: {0}", pngImage.VerticalResolution);
    }
}
```

### See Also

* class [PngImage](../)
* namespace [Aspose.Imaging.FileFormats.Png](../../pngimage/)
* assembly [Aspose.Imaging](../../../)


