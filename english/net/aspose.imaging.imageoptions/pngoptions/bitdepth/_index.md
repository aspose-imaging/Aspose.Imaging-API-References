---
title: PngOptions.BitDepth
second_title: Aspose.Imaging for .NET API Reference
description: PngOptions property. Gets or sets the bit depth values in range of 1 2 4 8 16
type: docs
weight: 20
url: /net/aspose.imaging.imageoptions/pngoptions/bitdepth/
---
## PngOptions.BitDepth property

Gets or sets the bit depth values in range of 1, 2, 4, 8, 16.

Mind the next limits:

IndexedColor supports bit depth of 1, 2, 4, 8.

Grayscale, GrayscaleWithAlpha support bit depth of 8.

Truecolor, TruecolorWithAlpha support bit depth of 8, 16.

```csharp
public byte BitDepth { get; set; }
```

## Examples

This example shows how to create a PNG image with the specified options, fill it with a linear gradient colors and save it to a file.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.PngOptions createOptions = new Aspose.Imaging.ImageOptions.PngOptions();

// The number of bits per color channel
createOptions.BitDepth = 8;

// Each pixel is a (red, green, blue) triple followed by the alpha component.
createOptions.ColorType = Imaging.FileFormats.Png.PngColorType.TruecolorWithAlpha;

// The maximum level of compression.
createOptions.CompressionLevel = 9;

// Usage of filters allows to compress continuous tonal images more effectively.
createOptions.FilterType = Aspose.Imaging.FileFormats.Png.PngFilterType.Sub;

// Use progressive loading
createOptions.Progressive = true;

// Create a PNG image with custom parameters.
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(createOptions, 100, 100))
{
    Aspose.Imaging.Brushes.LinearGradientBrush gradientBrush = new Aspose.Imaging.Brushes.LinearGradientBrush(
            new Aspose.Imaging.Point(0, 0),
            new Aspose.Imaging.Point(pngImage.Width, pngImage.Height),
            Aspose.Imaging.Color.Blue,
            Aspose.Imaging.Color.Transparent);

    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(pngImage);

    // Fill the image with a semi-transparent gradient.
    graphics.FillRectangle(gradientBrush, pngImage.Bounds);

    // Save to a file.
    pngImage.Save(dir + "output.explicitoptions.png");
}
```

The following example shows how to save an image to PNG format using various options.

```csharp
[C#]

string dir = "c:\\temp\\";

// Create a PNG image of 100x100 px.
// You can also load image of any supported format from a file or a stream.
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(100, 100))
{
    Aspose.Imaging.Brushes.LinearGradientBrush gradientBrush = new Aspose.Imaging.Brushes.LinearGradientBrush(
            new Aspose.Imaging.Point(0, 0),
            new Aspose.Imaging.Point(pngImage.Width, pngImage.Height),
            Aspose.Imaging.Color.Blue,
            Aspose.Imaging.Color.Transparent);

    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(pngImage);

    // Fill the image with the blue-transparent gradient.
    graphics.FillRectangle(gradientBrush, pngImage.Bounds);

    Aspose.Imaging.ImageOptions.PngOptions saveOptions = new Aspose.Imaging.ImageOptions.PngOptions();

    // Progressive loading.
    saveOptions.Progressive = true;

    // Set the horizontal and vertical resolution to 96 pixels per inch.
    saveOptions.ResolutionSettings = new Aspose.Imaging.ResolutionSetting(96.0, 96.0);

    // Each pixel is a (red, green, blue) triple followed by alpha.
    saveOptions.ColorType = Imaging.FileFormats.Png.PngColorType.TruecolorWithAlpha;

    // Set the maximum level of compression.
    saveOptions.CompressionLevel = 9;

    // This is the best compression, but the slowest execution time.
    // Adaptive filtering means that saving process will choose most sutable filter for each data row.
    saveOptions.FilterType = Aspose.Imaging.FileFormats.Png.PngFilterType.Adaptive;

    // The number of bits per channel.
    saveOptions.BitDepth = 8;

    // Save to a file.
    pngImage.Save(dir + "output.png", saveOptions);
}
```

### See Also

* class [PngOptions](../)
* namespace [Aspose.Imaging.ImageOptions](../../pngoptions/)
* assembly [Aspose.Imaging](../../../)


