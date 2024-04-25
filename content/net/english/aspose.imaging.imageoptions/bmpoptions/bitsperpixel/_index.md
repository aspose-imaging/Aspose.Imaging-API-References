---
title: BitsPerPixel
second_title: Aspose.Imaging for .NET API Reference
description: 
type: docs
weight: 20
url: /aspose.imaging.imageoptions/bmpoptions/bitsperpixel/
---
## BmpOptions.BitsPerPixel property

Gets or sets the image bits per pixel count.

```csharp
public int BitsPerPixel { get; set; }
```

### Property Value

The image bits per pixel count.

### Examples

The following example loads a BMP image and saves it back to BMP using various save options.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)image;

    // Create BmpOptions
    Aspose.Imaging.ImageOptions.BmpOptions saveOptions = new Aspose.Imaging.ImageOptions.BmpOptions();

    // Use 8 bits per pixel to reduce the size of the output image.
    saveOptions.BitsPerPixel = 8;

    // Set the closest 8-bit color palette which covers the maximal number of image pixels, so that a palettized image
    // is almost visually indistinguishable from a non-palletized one.
    saveOptions.Palette = Aspose.Imaging.ColorPaletteHelper.GetCloseImagePalette(rasterImage, 256);

    // Save without compression.
    // You can also use RLE-8 compression to reduce the size of the output image.
    saveOptions.Compression = Aspose.Imaging.FileFormats.Bmp.BitmapCompression.Rgb;

    // Set the horizontal and vertical resolution to 96 dpi.
    saveOptions.ResolutionSettings = new Aspose.Imaging.ResolutionSetting(96.0, 96.0);

    image.Save(dir + "sample.bmpoptions.bmp", saveOptions);
}
```

The following example creates a palettized grayscale BMP image and then saves it to a file.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.BmpOptions createOptions = new Aspose.Imaging.ImageOptions.BmpOptions();

// Save to a file
createOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(dir + "output.palette8bit.bmp", false);
    
// Use 8 bits per pixel to reduce the size of the output image.
createOptions.BitsPerPixel = 8;

// Set the standard 8-bit grayscale color palette which covers all grayscale colors.
// If the processed image contains only grayscale colors, then its palettized version
// is visually indistinguishable from a non-palletized one.
createOptions.Palette = Aspose.Imaging.ColorPaletteHelper.Create8BitGrayscale(false);

// Save without compression.
// You can also use RLE-8 compression to reduce the size of the output image.
createOptions.Compression = Aspose.Imaging.FileFormats.Bmp.BitmapCompression.Rgb;

// Set the horizontal and vertical resolution to 96 dpi.
createOptions.ResolutionSettings = new Aspose.Imaging.ResolutionSetting(96.0, 96.0);

// Create a BMP image of 100 x 100 px and save it to a file.
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(createOptions, 100, 100))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);

    Aspose.Imaging.Brushes.LinearGradientBrush gradientBrush = new Aspose.Imaging.Brushes.LinearGradientBrush(
        new Aspose.Imaging.Point(0, 0),
        new Aspose.Imaging.Point(image.Width, image.Height),
        Aspose.Imaging.Color.Black,
        Aspose.Imaging.Color.White);

    // Fill the image with a grayscale gradient
    graphics.FillRectangle(gradientBrush, image.Bounds);

    image.Save();
}
```

The following example shows how to palletize a BMP image to reduce its output size.

```csharp
[C#]

// Create a BMP image 100 x 100 px.
using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(100, 100))
{
    // The linear gradient from the left-top to the right-bottom corner of the image.
    Aspose.Imaging.Brushes.LinearGradientBrush brush =
        new Aspose.Imaging.Brushes.LinearGradientBrush(
            new Aspose.Imaging.Point(0, 0),
            new Aspose.Imaging.Point(bmpImage.Width, bmpImage.Height),
            Aspose.Imaging.Color.Red,
            Aspose.Imaging.Color.Green);

    // Fill the entire image with the linear gradient brush.
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(bmpImage);
    gr.FillRectangle(brush, bmpImage.Bounds);

    // Get the closest 8-bit color palette which covers as many pixels as possible, so that a palettized image
    // is almost visually indistinguishable from a non-palletized one.
    Aspose.Imaging.IColorPalette palette = Aspose.Imaging.ColorPaletteHelper.GetCloseImagePalette(bmpImage, 256);

    // 8-bit palette contains at most 256 colors.
    Aspose.Imaging.ImageOptions.BmpOptions saveOptions = new Aspose.Imaging.ImageOptions.BmpOptions();
    saveOptions.Palette = palette;
    saveOptions.BitsPerPixel = 8;

    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        bmpImage.Save(stream, saveOptions);
        System.Console.WriteLine("The palettized image size is {0} bytes.", stream.Length);
    }

    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        bmpImage.Save(stream);
        System.Console.WriteLine("The non-palettized image size is {0} bytes.", stream.Length);
    }
}

// The output looks like this:
// The palettized image size is 11078 bytes.
// The non-palettized image size is 40054 bytes.
```

### See Also

* class [BmpOptions](../../bmpoptions)
* namespace [Aspose.Imaging.ImageOptions](../../bmpoptions)
* assembly [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
