---
title: BmpOptions.Compression
second_title: Aspose.Imaging for .NET API Reference
description: BmpOptions property. Gets or sets the compression type. The default compression type is Bitfields that allows saving a BmpImage with transparency
type: docs
weight: 30
url: /net/aspose.imaging.imageoptions/bmpoptions/compression/
---
## BmpOptions.Compression property

Gets or sets the compression type. The default compression type is Bitfields, that allows saving a [`BmpImage`](../../../aspose.imaging.fileformats.bmp/bmpimage/) with transparency.

```csharp
public BitmapCompression Compression { get; set; }
```

### Property Value

The compression type.

## Examples

Decompress BMP image which was previously compressed using DXT1 compression algorithm.

```csharp
[C#]

using (var image = Image.Load("CompressedTiger.bmp"))
{
    image.Save("DecompressedTiger.bmp", new BmpOptions());
}
```

Compress BMP image using DXT1 compression algorithm.

```csharp
[C#]

using (var image = Image.Load("Tiger.bmp"))
{
    image.Save("CompressedTiger.bmp", new BmpOptions { Compression = BitmapCompression.Dxt1 });
}
```

The example shows how to export a BmpImage with the Rgb compression type.

```csharp
[C#]

string sourcePath = "input.png";
// Load a PNG image from a file.
using (Image pngImage = Image.Load(sourcePath))
{
    // BMP image is saved with transparency support by default, that is achieved by using the BitmapCompression.Bitfields compression method. 
    // To save a BMP image with the Rgb compression method, the BmpOptions with the Compression property set to BitmapCompression.Rgb should be specified.
    pngImage.Save(outputPath, new BmpOptions() { Compression = BitmapCompression.Rgb });
}
```

The example shows how to export a BmpImage from a Png file while keeping the alpha channel, save a Bmp file with transparency.

```csharp
[C#]

string sourcePath = "input.png";
// Load a PNG image from a file.
using (Image pngImage = Image.Load(sourcePath))
{
    // BMP image is saved with transparency support by default. 
    // If you want to explicitly specify such mode, the BmpOptions's Compression property should be set to BitmapCompression.Bitfields.
    // The BitmapCompression.Bitfields compression method is the default compression method in the BmpOptions.
    // So the same result of exporting a Bmp image with transparency can be achieved by either one of the following ways.
    // With an implicit default options:
    pngImage.Save(outputPath);
    // With an explicit default options:
    pngImage.Save(outputPath, new BmpOptions());
    // Specifying the BitmapCompression.Bitfields compression method:
    pngImage.Save(outputPath, new BmpOptions() { Compression = BitmapCompression.Bitfields });
}
```

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

### See Also

* enum [BitmapCompression](../../../aspose.imaging.fileformats.bmp/bitmapcompression/)
* class [BmpOptions](../)
* namespace [Aspose.Imaging.ImageOptions](../../bmpoptions/)
* assembly [Aspose.Imaging](../../../)


