---
title: PngImage.VerticalResolution
second_title: Aspose.Imaging for .NET API Reference
description: PngImage property. Provides access to the vertical resolution of the image. Developers can use this property to retrieve or modify the resolution setting which indicates the number of pixels per inch PPI along the vertical axis of the image
type: docs
weight: 140
url: /net/aspose.imaging.fileformats.png/pngimage/verticalresolution/
---
## PngImage.VerticalResolution property

Provides access to the vertical resolution of the image. Developers can use this property to retrieve or modify the resolution setting, which indicates the number of pixels per inch (PPI) along the vertical axis of the image.

```csharp
public override double VerticalResolution { get; set; }
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


