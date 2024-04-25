---
title: RawLineSize
second_title: Aspose.Imaging for .NET API Reference
description: 
type: docs
weight: 90
url: /aspose.imaging.fileformats.bmp/bmpimage/rawlinesize/
---
## BmpImage.RawLineSize property

Quickly access the size of each raw line in bytes with this straightforward property. Ideal for developers needing to efficiently handle raw image data.

```csharp
public override int RawLineSize { get; }
```

### Property Value

The raw line size in bytes.

### Examples

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

The following example shows how the bitmap compression affects the output image size.

```csharp
[C#]

Aspose.Imaging.FileFormats.Bmp.BitmapCompression[] compressions = new Aspose.Imaging.FileFormats.Bmp.BitmapCompression[]
{
    Aspose.Imaging.FileFormats.Bmp.BitmapCompression.Rgb,
    Aspose.Imaging.FileFormats.Bmp.BitmapCompression.Rle8,
};

Aspose.Imaging.Color[] paletterColors = new Aspose.Imaging.Color[]
{
    Aspose.Imaging.Color.Red,
    Aspose.Imaging.Color.Green,
};

// Create a monochrome palette which contains only red and green colors.
Aspose.Imaging.IColorPalette palette = new Aspose.Imaging.ColorPalette(paletterColors);

foreach (Aspose.Imaging.FileFormats.Bmp.BitmapCompression compression in compressions)
{
    // Create a 8-bpp BMP image of 100 x 100 px.
    using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(100, 100, 8, palette, compression, 0.0, 0.0))
    {
        Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(bmpImage);

        // Fill the entire image in red.
        Aspose.Imaging.Brushes.SolidBrush redBrush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
        gr.FillRectangle(redBrush, bmpImage.Bounds);

        // Save the image to a stream to get the output image size.
        using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
        {
            bmpImage.Save(stream);

            System.Console.WriteLine("---------------------------------------------");
            System.Console.WriteLine("The compression={0}", bmpImage.Compression);
            System.Console.WriteLine("The number of bits per pixel={0}", bmpImage.BitsPerPixel);
            System.Console.WriteLine("The image dimensions={0} x {1}", bmpImage.Width, bmpImage.Height);
            System.Console.WriteLine("The raw line size={0}", bmpImage.RawLineSize);
            System.Console.WriteLine("The output size in bytes={0}", stream.Length);
        }
    }
}

// The output looks like this:
// ---------------------------------------------
// The compression = Rgb
// The number of bits per pixel = 8
// The image dimensions = 100 x 100
// The raw line size = 100
// The output size in bytes = 11078
// ---------------------------------------------
// The compression = Rle8
// The number of bits per pixel = 8
// The image dimensions = 100 x 100
// The raw line size = 100
// The output size in bytes = 856
```

### See Also

* class [BmpImage](../../bmpimage)
* namespace [Aspose.Imaging.FileFormats.Bmp](../../bmpimage)
* assembly [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
