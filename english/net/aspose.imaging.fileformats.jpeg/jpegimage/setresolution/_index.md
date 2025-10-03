---
title: JpegImage.SetResolution
second_title: Aspose.Imaging for .NET API Reference
description: JpegImage method. Establishes the resolution for the specified RasterImage ensuring accurate scaling and printing capabilities. This method empowers users to tailor the image resolution to suit their specific requirements whether for digital display or physical reproduction. By setting the resolution users can optimize image quality and ensure compatibility with various output devices and mediums enhancing the overall visual experience and usability of the image
type: docs
weight: 210
url: /net/aspose.imaging.fileformats.jpeg/jpegimage/setresolution/
---
## JpegImage.SetResolution method

Establishes the resolution for the specified [`RasterImage`](../../../aspose.imaging/rasterimage/), ensuring accurate scaling and printing capabilities. This method empowers users to tailor the image resolution to suit their specific requirements, whether for digital display or physical reproduction. By setting the resolution, users can optimize image quality and ensure compatibility with various output devices and mediums, enhancing the overall visual experience and usability of the image.

```csharp
public override void SetResolution(double dpiX, double dpiY)
```

| Parameter | Type | Description |
| --- | --- | --- |
| dpiX | Double | The horizontal resolution, in dots per inch, of the [`RasterImage`](../../../aspose.imaging/rasterimage/). |
| dpiY | Double | The vertical resolution, in dots per inch, of the [`RasterImage`](../../../aspose.imaging/rasterimage/). |

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


