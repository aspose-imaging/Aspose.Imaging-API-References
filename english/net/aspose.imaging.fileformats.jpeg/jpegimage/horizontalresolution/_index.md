---
title: JpegImage.HorizontalResolution
second_title: Aspose.Imaging for .NET API Reference
description: JpegImage property. This property grants you access to the horizontal resolution of the RasterImage measured in pixels per inch. By setting or retrieving this value you can precisely control the resolution of the image ensuring it meets your specific requirements for quality and clarity
type: docs
weight: 100
url: /net/aspose.imaging.fileformats.jpeg/jpegimage/horizontalresolution/
---
## JpegImage.HorizontalResolution property

This property grants you access to the horizontal resolution of the [`RasterImage`](../../../aspose.imaging/rasterimage/), measured in pixels per inch. By setting or retrieving this value, you can precisely control the resolution of the image, ensuring it meets your specific requirements for quality and clarity.

```csharp
public override double HorizontalResolution { get; set; }
```

### Property Value

The horizontal resolution.

## Remarks

Note by default this value is always 96 since different platforms cannot return the screen resolution. You may consider using the SetResolution method for updating both resolution values in single call.

## Examples

The following example shows how to set horizontal/vertical resolution of a JPEG image.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.jpg"))
{
    Aspose.Imaging.FileFormats.Jpeg.JpegImage jpegImage = (Aspose.Imaging.FileFormats.Jpeg.JpegImage)image;

    // Get horizontal and vertical resolution of the BmpImage
    double horizontalResolution = jpegImage.HorizontalResolution;
    double verticalResolution = jpegImage.VerticalResolution;
    System.Console.WriteLine("The horizontal resolution, in pixels per inch: {0}", horizontalResolution);
    System.Console.WriteLine("The vertical resolution, in pixels per inch: {0}", verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0)
    {
        // Use the SetResolution method for updating both resolution values in a single call.
        System.Console.WriteLine("Set resolution values to 96 dpi");
        jpegImage.SetResolution(96.0, 96.0);

        System.Console.WriteLine("The horizontal resolution, in pixels per inch: {0}", jpegImage.HorizontalResolution);
        System.Console.WriteLine("The vertical resolution, in pixels per inch: {0}", jpegImage.VerticalResolution);
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

* class [JpegImage](../)
* namespace [Aspose.Imaging.FileFormats.Jpeg](../../jpegimage/)
* assembly [Aspose.Imaging](../../../)


