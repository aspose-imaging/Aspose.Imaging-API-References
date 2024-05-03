---
title: PsdOptions.CompressionMethod
second_title: Aspose.Imaging for .NET API Reference
description: PsdOptions property. Gets or sets the psd compression method
type: docs
weight: 50
url: /net/aspose.imaging.imageoptions/psdoptions/compressionmethod/
---
## PsdOptions.CompressionMethod property

Gets or sets the psd compression method.

```csharp
public CompressionMethod CompressionMethod { get; set; }
```

### Property Value

The compression method.

## Examples

This example demonstrates the use of Aspsoe.Imaging for .Net API to convert Images to PSD format. To achieve this goal this example loads an existing image and then saves it back to PSD format.

```csharp
[C#]

string dir = "c:\\temp\\";

//Creates an instance of image class and initialize it with an existing file through File path
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    //Create an instance of PsdOptions class
    Aspose.Imaging.ImageOptions.PsdOptions psdOptions = new Aspose.Imaging.ImageOptions.PsdOptions();

    //Set the CompressionMethod as RLE
    //Note: Other supported CompressionMethod is CompressionMethod.RAW [No Compression]
    psdOptions.CompressionMethod = Aspose.Imaging.FileFormats.Psd.CompressionMethod.RLE;

    //Set the ColorMode to GrayScale
    //Note: Other supported ColorModes are ColorModes.Bitmap and ColorModes.RGB
    psdOptions.ColorMode = Aspose.Imaging.FileFormats.Psd.ColorModes.Grayscale;

    //Save the image to disk location with supplied PsdOptions settings
    image.Save(dir + "output.psd", psdOptions);
}
```

This example shows how to save a PNG image to PSD format using various PSD-specific options.

```csharp
[C#]

string dir = "c:\\temp\\";

// Create a PNG image of 100x100 px.
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(100, 100, Aspose.Imaging.FileFormats.Png.PngColorType.TruecolorWithAlpha))
{
    // Define a linear blue-transparent gradient.
    Aspose.Imaging.Brushes.LinearGradientBrush gradientBrush = new Aspose.Imaging.Brushes.LinearGradientBrush(
            new Aspose.Imaging.Point(0, 0),
            new Aspose.Imaging.Point(pngImage.Width, pngImage.Height),
            Aspose.Imaging.Color.Blue,
            Aspose.Imaging.Color.Transparent);

    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(pngImage);

    // Fill the PNG image with the linear blue-transparent gradient.
    graphics.FillRectangle(gradientBrush, pngImage.Bounds);

    // The following options will be used to save the PNG image to PSD format.
    Aspose.Imaging.ImageOptions.PsdOptions saveOptions = new Aspose.Imaging.ImageOptions.PsdOptions();

    // The number of bits per channel
    saveOptions.ChannelBitsCount = 8;

    // The number of channels. One channel for each color component R,G,B,A
    saveOptions.ChannelsCount = 4;

    // The color mode
    saveOptions.ColorMode = Aspose.Imaging.FileFormats.Psd.ColorModes.Rgb;

    // No compression
    saveOptions.CompressionMethod = Imaging.FileFormats.Psd.CompressionMethod.Raw;

    // Default version is 6
    saveOptions.Version = 6;            

    using (System.IO.FileStream stream = System.IO.File.Create(dir + "saveoptions.psd"))
    {
        pngImage.Save(stream, saveOptions);
        System.Console.WriteLine("The size of the PSD image with RAW compression: {0}", stream.Length);
    }

    using (System.IO.FileStream stream = System.IO.File.Create(dir + "saveoptions.RLE.psd"))
    {
        // The RLE compression allows to reduce the size of the output image
        saveOptions.CompressionMethod = Imaging.FileFormats.Psd.CompressionMethod.RLE;

        pngImage.Save(stream, saveOptions);
        System.Console.WriteLine("The size of the PSD image with RLE compression: {0}", stream.Length);
    }

    // The output may look like this:
    // The size of the PSD image with RAW compression: 40090
    // The size of the PSD image with RLE compression: 16185
}
```

### See Also

* enum [CompressionMethod](../../../aspose.imaging.fileformats.psd/compressionmethod/)
* class [PsdOptions](../)
* namespace [Aspose.Imaging.ImageOptions](../../psdoptions/)
* assembly [Aspose.Imaging](../../../)


