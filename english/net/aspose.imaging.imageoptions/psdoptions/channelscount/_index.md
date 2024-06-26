---
title: PsdOptions.ChannelsCount
second_title: Aspose.Imaging for .NET API Reference
description: PsdOptions property. Gets or sets the color channels count
type: docs
weight: 30
url: /net/aspose.imaging.imageoptions/psdoptions/channelscount/
---
## PsdOptions.ChannelsCount property

Gets or sets the color channels count.

```csharp
public short ChannelsCount { get; set; }
```

### Property Value

The color channels count.

## Examples

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

* class [PsdOptions](../)
* namespace [Aspose.Imaging.ImageOptions](../../psdoptions/)
* assembly [Aspose.Imaging](../../../)


