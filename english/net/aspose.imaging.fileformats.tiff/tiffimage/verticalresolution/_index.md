---
title: TiffImage.VerticalResolution
second_title: Aspose.Imaging for .NET API Reference
description: TiffImage property. Access the vertical resolution of the designated Image in pixels per inch enabling precise adjustments and rendering optimizations. Utilize essential image data effortlessly to streamline image processing workflows ensuring superior quality and performance in your applications
type: docs
weight: 110
url: /net/aspose.imaging.fileformats.tiff/tiffimage/verticalresolution/
---
## TiffImage.VerticalResolution property

Access the vertical resolution of the designated [`Image`](../../../aspose.imaging/image/) in pixels per inch, enabling precise adjustments and rendering optimizations. Utilize essential image data effortlessly to streamline image processing workflows, ensuring superior quality and performance in your applications.

```csharp
public override double VerticalResolution { get; set; }
```

### Property Value

The vertical resolution.

## Remarks

Note by default this value is always 96 since different platforms cannot return the screen resolution. You may consider using the SetResolution method for updating both resolution values in single call.

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


