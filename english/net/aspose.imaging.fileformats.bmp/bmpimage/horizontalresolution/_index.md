---
title: BmpImage.HorizontalResolution
second_title: Aspose.Imaging for .NET API Reference
description: BmpImage property. This property allows you to easily get or set the horizontal resolution measured in pixels per inch of the RasterImage object. Ideal for developers needing precise control over image resolution for their applications
type: docs
weight: 80
url: /net/aspose.imaging.fileformats.bmp/bmpimage/horizontalresolution/
---
## BmpImage.HorizontalResolution property

This property allows you to easily get or set the horizontal resolution, measured in pixels per inch, of the [`RasterImage`](../../../aspose.imaging/rasterimage/) object. Ideal for developers needing precise control over image resolution for their applications.

```csharp
public override double HorizontalResolution { get; set; }
```

### Property Value

The horizontal resolution.

## Remarks

Note by default this value is always 96 since different platforms cannot return the screen resolution. You may consider using the SetResolution method for updating both resolution values in single call.

## Examples

The following example shows how to set horizontal/vertical resolution of a BMP image.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = (Aspose.Imaging.FileFormats.Bmp.BmpImage)image;

    // Get horizontal and vertical resolution of the BmpImage
    double horizontalResolution = bmpImage.HorizontalResolution;
    double verticalResolution = bmpImage.VerticalResolution;
    System.Console.WriteLine("The horizontal resolution, in pixels per inch: {0}", horizontalResolution);
    System.Console.WriteLine("The vertical resolution, in pixels per inch: {0}", verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0)
    {
        // Use the SetResolution method for updating both resolution values in a single call.
        System.Console.WriteLine("Set resolution values to 96 dpi");
        bmpImage.SetResolution(96.0, 96.0);

        System.Console.WriteLine("The horizontal resolution, in pixels per inch: {0}", bmpImage.HorizontalResolution);
        System.Console.WriteLine("The vertical resolution, in pixels per inch: {0}", bmpImage.VerticalResolution);
    }

    // The output may look like this:
    // The horizontal resolution, in pixels per inch: 0
    // The vertical resolution, in pixels per inch: 0
    // Set resolution values to 96 dpi
    // The horizontal resolution, in pixels per inch: 96.012
    // The vertical resolution, in pixels per inch: 96.012
}
```

The following example gets the general information about the image including pixel format, image size, resolution, compression etc.

```csharp
[C#]

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(@"c:\temp\sample.bmp"))
{
    Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = (Aspose.Imaging.FileFormats.Bmp.BmpImage)image;                

    System.Console.WriteLine("The pixel format: {0}", bmpImage.RawDataFormat);                
    System.Console.WriteLine("The raw line size in bytes: {0}", bmpImage.RawLineSize);
    System.Console.WriteLine("The bitmap compression: {0}", bmpImage.Compression);
    System.Console.WriteLine("The bitmap width: {0}", bmpImage.Width);
    System.Console.WriteLine("The bitmap height: {0}", bmpImage.Height);
    System.Console.WriteLine("The number of bits per pixel: {0}", bmpImage.BitsPerPixel);

    double hres = bmpImage.HorizontalResolution;
    double vres = bmpImage.VerticalResolution;
    System.Console.WriteLine("The horizontal resolution, in pixels per inch: {0}", hres);
    System.Console.WriteLine("The vertical resolution, in pixels per inch: {0}", vres);

    if (hres != 96.0 || vres != 96.0)
    {
        // You may consider using the SetResolution method for updating both resolution values in single call.
        System.Console.WriteLine("Set resolution values to 96 dpi");
        bmpImage.SetResolution(96.0, 96.0);

        System.Console.WriteLine("The horizontal resolution, in pixels per inch: {0}", bmpImage.HorizontalResolution);
        System.Console.WriteLine("The vertical resolution, in pixels per inch: {0}", bmpImage.VerticalResolution);
    }

    //The output may look like this:
    //The pixel format: Rgb24Bpp, used channels: 8,8,8
    //The raw line size in bytes: 1500
    //The bitmap compression: Rgb
    //The bitmap width: 500
    //The bitmap height: 375
    //The number of bits per pixel: 24
    //The horizontal resolution, in pixels per inch: 0
    //The vertical resolution, in pixels per inch: 0
    //Set resolution values to 96 dpi
    //The horizontal resolution, in pixels per inch: 96.012
    //The vertical resolution, in pixels per inch: 96.012
}
```

### See Also

* class [BmpImage](../)
* namespace [Aspose.Imaging.FileFormats.Bmp](../../bmpimage/)
* assembly [Aspose.Imaging](../../../)


