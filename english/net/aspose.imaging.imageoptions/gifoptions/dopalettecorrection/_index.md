---
title: GifOptions.DoPaletteCorrection
second_title: Aspose.Imaging for .NET API Reference
description: GifOptions property. Gets or sets a value indicating whether palette correction is applied
type: docs
weight: 50
url: /net/aspose.imaging.imageoptions/gifoptions/dopalettecorrection/
---
## GifOptions.DoPaletteCorrection property

Gets or sets a value indicating whether palette correction is applied.

```csharp
public bool DoPaletteCorrection { get; set; }
```

### Property Value

`true` if palette correction is applied; otherwise, `false`.

## Remarks

Palette correction means that whenever image is exported to GIF the source image colors will be analyzed in order to build the best matching palette (in case image Palette does not exist or not specified in the options). The analyze process takes some time however the output image will have the best matching color palette and result is visually better.

## Examples

This example shows how to save a BMP image to GIF format using various options.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(1000, 1000))
{
    // Fill the entire image with the blue-yellow gradient.
    Aspose.Imaging.Brushes.LinearGradientBrush gradientBrush = new Aspose.Imaging.Brushes.LinearGradientBrush(
            new Aspose.Imaging.Point(0, 0),
            new Aspose.Imaging.Point(bmpImage.Width, bmpImage.Height),
            Aspose.Imaging.Color.Blue,
            Aspose.Imaging.Color.Yellow);

    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(bmpImage);
    graphics.FillRectangle(gradientBrush, bmpImage.Bounds);

    Aspose.Imaging.ImageOptions.GifOptions saveOptions = new Aspose.Imaging.ImageOptions.GifOptions();

    // The number of bits required to store a color, minus 1.
    saveOptions.ColorResolution = 7;

    // Palette correction means that whenever image is exported to GIF the source image colors will be analyzed
    // in order to build the best matching palette (in case image Palette does not exist or not specified in the options)
    saveOptions.DoPaletteCorrection = true;

    // Load a GIF image in a progressive way.
    // An interlaced GIF doesn't display its scanlines linearly from top to bottom, but instead reorders it
    // so the content of the GIF becomes clear even before it finishes loading.
    saveOptions.Interlaced = true;

    // Save as a lossless GIF.
    using (System.IO.Stream stream = System.IO.File.OpenWrite(dir + "output.gif"))
    {
        bmpImage.Save(stream, saveOptions);
        System.Console.WriteLine("The size of the lossless GIF: {0} bytes.", stream.Length);
    }

    // Set the maximum allowed pixel difference. If greater than zero, lossy compression will be used.
    // The recommended value for optimal lossy compression is 80. 30 is very light compression, 200 is heavy.
    saveOptions.MaxDiff = 80;

    // Save as a lossy GIF.
    using (System.IO.Stream stream = System.IO.File.OpenWrite(dir + "output.lossy.gif"))
    {
        bmpImage.Save(stream, saveOptions);
        System.Console.WriteLine("The size of the lossy GIF: {0} bytes.", stream.Length);
    }
}

//The output may look like this:
//The size of the lossless GIF: 212816 bytes.
//The size of the lossy GIF: 89726 bytes.
```

### See Also

* class [GifOptions](../)
* namespace [Aspose.Imaging.ImageOptions](../../gifoptions/)
* assembly [Aspose.Imaging](../../../)


