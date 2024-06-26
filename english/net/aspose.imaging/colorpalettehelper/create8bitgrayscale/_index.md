---
title: ColorPaletteHelper.Create8BitGrayscale
second_title: Aspose.Imaging for .NET API Reference
description: ColorPaletteHelper method. Creates the 8 bit grayscale palette
type: docs
weight: 40
url: /net/aspose.imaging/colorpalettehelper/create8bitgrayscale/
---
## ColorPaletteHelper.Create8BitGrayscale method

Creates the 8 bit grayscale palette.

```csharp
public static IColorPalette Create8BitGrayscale(bool minIsWhite)
```

| Parameter | Type | Description |
| --- | --- | --- |
| minIsWhite | Boolean | if set to `true` the palette starts with white color, otherwise it starts with black color. |

### Return Value

The 8 bit grayscale palette.

## Examples

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

* interface [IColorPalette](../../icolorpalette/)
* class [ColorPaletteHelper](../)
* namespace [Aspose.Imaging](../../colorpalettehelper/)
* assembly [Aspose.Imaging](../../../)


