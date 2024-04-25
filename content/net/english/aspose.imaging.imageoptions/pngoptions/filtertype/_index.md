---
title: FilterType
second_title: Aspose.Imaging for .NET API Reference
description: 
type: docs
weight: 50
url: /aspose.imaging.imageoptions/pngoptions/filtertype/
---
## PngOptions.FilterType property

Gets or sets the filter type used during png file save process.

```csharp
public PngFilterType FilterType { get; set; }
```

### Examples

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

The following example shows how different filter types affect the size of the output PNG image.

```csharp
[C#]

Aspose.Imaging.FileFormats.Png.PngFilterType[] filterTypes = new Aspose.Imaging.FileFormats.Png.PngFilterType[]
{
    Aspose.Imaging.FileFormats.Png.PngFilterType.None,
    Aspose.Imaging.FileFormats.Png.PngFilterType.Up,
    Aspose.Imaging.FileFormats.Png.PngFilterType.Sub,
    Aspose.Imaging.FileFormats.Png.PngFilterType.Paeth,
    Aspose.Imaging.FileFormats.Png.PngFilterType.Avg,
    Aspose.Imaging.FileFormats.Png.PngFilterType.Adaptive,
};

foreach (Aspose.Imaging.FileFormats.Png.PngFilterType filterType in filterTypes)
{
    Aspose.Imaging.ImageOptions.PngOptions options = new Aspose.Imaging.ImageOptions.PngOptions();

    using (Aspose.Imaging.Image image = Image.Load("c:\\temp\\sample.png"))
    {
        // Set a filter type
        options.FilterType = filterType;

        using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
        {
            image.Save(stream, options);
            System.Console.WriteLine("The filter type is {0}, the output image size is {1} bytes.", filterType, stream.Length);
        }
    }
}

//The output may look like this:
//The filter type is None, the output image size is 116845 bytes.
//The filter type is Up, the output image size is 86360 bytes.
//The filter type is Sub, the output image size is 94907 bytes.
//The filter type is Paeth, the output image size is 86403 bytes.
//The filter type is Avg, the output image size is 89956 bytes.
//The filter type is Adaptive, the output image size is 97248 bytes.
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

* enum [PngFilterType](../../../aspose.imaging.fileformats.png/pngfiltertype)
* class [PngOptions](../../pngoptions)
* namespace [Aspose.Imaging.ImageOptions](../../pngoptions)
* assembly [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
