---
title: JpegOptions.Quality
second_title: Aspose.Imaging for .NET API Reference
description: JpegOptions property. Gets or sets image quality
type: docs
weight: 140
url: /net/aspose.imaging.imageoptions/jpegoptions/quality/
---
## JpegOptions.Quality property

Gets or sets image quality.

```csharp
public int Quality { get; set; }
```

## Examples

The following example loads a BMP image and saves it to JPEG using various save options.

```csharp
[C#]

string dir = "c:\\temp\\";

// Load a BMP image from a file.
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    // Do some image processing.

    // Use additional options to specify the desired image parameters.
    Aspose.Imaging.ImageOptions.JpegOptions saveOptions = new Aspose.Imaging.ImageOptions.JpegOptions();

    // The number of bits per channel is 8.
    // When a palette is used, the color index is stored in the image data instead of the color itself.
    saveOptions.BitsPerChannel = 8;

    // Set the progressive type of compression.
    saveOptions.CompressionType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionMode.Progressive;

    // Set the image quality. It is a value between 1 and 100.
    saveOptions.Quality = 100;

    // Set the horizontal/vertical resolution to 96 dots per inch.
    saveOptions.ResolutionSettings = new Aspose.Imaging.ResolutionSetting(96.0, 96.0);
    saveOptions.ResolutionUnit = Aspose.Imaging.ResolutionUnit.Inch;

    // If the source image is colored, it will be converted to grayscaled.
    saveOptions.ColorType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionColorMode.Grayscale;

    // Use a palette to reduce the output size.
    saveOptions.Palette = Aspose.Imaging.ColorPaletteHelper.Create8BitGrayscale(false);

    image.Save(dir + "sample.palettized.jpg", saveOptions);
}
```

The following example shows how to create JPEG image of the specified size with the specified parameters.

```csharp
[C#]

string dir = "c:\\temp\\";

// Create a JPEG image of 100x100 px.
// Use additional options to specify the desired image parameters.
Aspose.Imaging.ImageOptions.JpegOptions createOptions = new Aspose.Imaging.ImageOptions.JpegOptions();

// The number of bits per channel is 8, 8, 8 for Y, Cr, Cb components accordingly.
createOptions.BitsPerChannel = 8;

// Set the progressive type of compression.
createOptions.CompressionType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionMode.Progressive;

// Set the image quality. It is a value between 1 and 100.
createOptions.Quality = 100;

// Set the horizontal/vertical resolution to 96 dots per inch.
createOptions.ResolutionSettings = new Aspose.Imaging.ResolutionSetting(96.0, 96.0);
createOptions.ResolutionUnit = Aspose.Imaging.ResolutionUnit.Inch;

// This is a standard option for JPEG images.
// Two chroma components (Cb and Cr) can be bandwidth-reduced, subsampled, compressed.
createOptions.ColorType = Aspose.Imaging.FileFormats.Jpeg.JpegCompressionColorMode.YCbCr;

using (Aspose.Imaging.FileFormats.Jpeg.JpegImage jpegImage = new Aspose.Imaging.FileFormats.Jpeg.JpegImage(createOptions, 100, 100))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(jpegImage);

    Aspose.Imaging.Brushes.LinearGradientBrush gradientBrush = new Aspose.Imaging.Brushes.LinearGradientBrush(
        new Aspose.Imaging.Point(0, 0),
        new Aspose.Imaging.Point(jpegImage.Width, jpegImage.Height),
        Aspose.Imaging.Color.Yellow,
        Aspose.Imaging.Color.Blue);

    // Fill the image with a grayscale gradient
    graphics.FillRectangle(gradientBrush, jpegImage.Bounds);

    // Save to a file.
    jpegImage.Save(dir + "output.explicitoptions.jpg");
}
```

### See Also

* class [JpegOptions](../)
* namespace [Aspose.Imaging.ImageOptions](../../jpegoptions/)
* assembly [Aspose.Imaging](../../../)


