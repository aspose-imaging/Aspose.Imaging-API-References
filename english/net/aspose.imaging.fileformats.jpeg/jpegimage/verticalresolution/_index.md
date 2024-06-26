---
title: JpegImage.VerticalResolution
second_title: Aspose.Imaging for .NET API Reference
description: JpegImage property. This property manages the vertical resolution expressed in pixels per inch for the associated RasterImage. Adjusting this resolution impacts the size and quality of the image when printed or displayed at a fixed physical size. By setting this property you control how densely the images pixels are packed vertically affecting its overall sharpness and clarity
type: docs
weight: 160
url: /net/aspose.imaging.fileformats.jpeg/jpegimage/verticalresolution/
---
## JpegImage.VerticalResolution property

This property manages the vertical resolution, expressed in pixels per inch, for the associated [`RasterImage`](../../../aspose.imaging/rasterimage/). Adjusting this resolution impacts the size and quality of the image when printed or displayed at a fixed physical size. By setting this property, you control how densely the image's pixels are packed vertically, affecting its overall sharpness and clarity.

```csharp
public override double VerticalResolution { get; set; }
```

### Property Value

The vertical resolution.

## Remarks

Note by default this value is always 72 since different platforms cannot return the screen resolution. You may consider using the SetResolution method for updating both resolution values in single call.

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


