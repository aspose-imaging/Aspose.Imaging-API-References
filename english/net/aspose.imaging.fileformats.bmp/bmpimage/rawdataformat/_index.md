---
title: BmpImage.RawDataFormat
second_title: Aspose.Imaging for .NET API Reference
description: BmpImage property. Easily obtain the format of your raw data with this userfriendly function. Perfect for developers looking to quickly access crucial information about their data format
type: docs
weight: 90
url: /net/aspose.imaging.fileformats.bmp/bmpimage/rawdataformat/
---
## BmpImage.RawDataFormat property

Easily obtain the format of your raw data with this user-friendly function. Perfect for developers looking to quickly access crucial information about their data format.

```csharp
public override PixelDataFormat RawDataFormat { get; }
```

### Property Value

The raw data format.

## Examples

The following example shows how to extract information about raw data format and alpha channel from a BMP image.

```csharp
[C#]

// Create a 32-bpp BMP image of 100 x 100 px.
using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(100, 100, 32, null))
{
    System.Console.WriteLine("FileFormat={0}, RawDataFormat={1}, HasAlpha={2}", bmpImage.FileFormat, bmpImage.RawDataFormat, bmpImage.HasAlpha);
};

// Create a 24-bpp BMP image of 100 x 100 px.
using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(100, 100, 24, null))
{
    System.Console.WriteLine("FileFormat={0}, RawDataFormat={1}, HasAlpha={2}", bmpImage.FileFormat, bmpImage.RawDataFormat, bmpImage.HasAlpha);
};

// Generally, BMP doesn't support alpha channel so the output will look like this:
// FileFormat = Bmp, RawDataFormat = Rgb32Bpp, used channels: 8,8,8,8, HasAlpha = False
// FileFormat = Bmp, RawDataFormat = Rgb24Bpp, used channels: 8,8,8, HasAlpha = False
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

* class [PixelDataFormat](../../../aspose.imaging/pixeldataformat/)
* class [BmpImage](../)
* namespace [Aspose.Imaging.FileFormats.Bmp](../../bmpimage/)
* assembly [Aspose.Imaging](../../../)


