---
title: GetCloseImagePalette
second_title: Aspose.Imaging for .NET API Reference
description: 
type: docs
weight: 60
url: /net/aspose.imaging/colorpalettehelper/getcloseimagepalette/
---
## ColorPaletteHelper.GetCloseImagePalette method (1 of 4)

Gets color palette from raster image (palletizes image) in case the image does not have one. In case palette exists it will be used instead performing calculations.

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, int entriesCount)
```

| Parameter | Type | Description |
| --- | --- | --- |
| image | RasterImage | The raster image. |
| entriesCount | Int32 | The desired entries count. |

## Return Value

The color palette which starts with the most frequent colors from the *image* and contains *entriesCount* entries.

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

* interface [IColorPalette](../../icolorpalette)
* class [RasterImage](../../rasterimage)
* class [ColorPaletteHelper](../../colorpalettehelper)
* namespace [Aspose.Imaging](../../colorpalettehelper)
* assembly [Aspose.Imaging](../../../)

---

## ColorPaletteHelper.GetCloseImagePalette method (2 of 4)

Gets color palette from raster image (palletizes image) in case the image does not have one. Palette is about to be optimized for better indexed image quality or taken "AS IS" when PaletteMiningMethod.UseCurrentPalette is used.

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, int entriesCount, 
    PaletteMiningMethod paletteMiningMethod)
```

| Parameter | Type | Description |
| --- | --- | --- |
| image | RasterImage | The raster image. |
| entriesCount | Int32 | The desired entries count. |
| paletteMiningMethod | PaletteMiningMethod | The palette mining method. |

## Return Value

The color palette which starts with the most frequent colors from the *image* and contains *entriesCount* entries.

### Examples

The following example shows how to compress a PNG image, using indexed color with best fit palette

```csharp
[C#]

// Loads png image        
    string  sourceFilePath="OriginalRings.png";
    string  outputFilePath="OriginalRingsOutput.png";
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(sourceFilePath))
{
    image.Save(outputFilePath, new Aspose.Imaging.ImageOptions.PngOptions()
    {
         Progressive = true,
             // Use indexed color type
         ColorType = Aspose.Imaging.FileFormats.Png.PngColorType.IndexedColor,
             // Use maximal compression
         CompressionLevel = 9,
      // Get the closest 8-bit color palette which covers as many pixels as possible, so that a palettized image
         // is almost visually indistinguishable from a non-palletized one.
         Palette = Aspose.Imaging.ColorPaletteHelper.GetCloseImagePalette((Aspose.Imaging.RasterImage)image, 256, Aspose.Imaging.PaletteMiningMethod.Histogram)
    });
}
    // The output file size should be significantly reduced
```

### See Also

* interface [IColorPalette](../../icolorpalette)
* class [RasterImage](../../rasterimage)
* enum [PaletteMiningMethod](../../paletteminingmethod)
* class [ColorPaletteHelper](../../colorpalettehelper)
* namespace [Aspose.Imaging](../../colorpalettehelper)
* assembly [Aspose.Imaging](../../../)

---

## ColorPaletteHelper.GetCloseImagePalette method (3 of 4)

Gets color palette from raster image (palletizes image) in case the image does not have one. In case palette exists it will be used instead performing calculations.

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, Rectangle destBounds, 
    int entriesCount)
```

| Parameter | Type | Description |
| --- | --- | --- |
| image | RasterImage | The raster image. |
| destBounds | Rectangle | The destination image bounds. |
| entriesCount | Int32 | The desired entries count. |

## Return Value

The color palette which starts with the most frequent colors from the *image* and contains *entriesCount* entries.

### See Also

* interface [IColorPalette](../../icolorpalette)
* class [RasterImage](../../rasterimage)
* struct [Rectangle](../../rectangle)
* class [ColorPaletteHelper](../../colorpalettehelper)
* namespace [Aspose.Imaging](../../colorpalettehelper)
* assembly [Aspose.Imaging](../../../)

---

## ColorPaletteHelper.GetCloseImagePalette method (4 of 4)

Gets color palette from raster image (palletizes image) in case the image does not have one. In case palette exists it will be used instead performing calculations.

```csharp
public static IColorPalette GetCloseImagePalette(RasterImage image, Rectangle destBounds, 
    int entriesCount, bool useImagePalette)
```

| Parameter | Type | Description |
| --- | --- | --- |
| image | RasterImage | The raster image. |
| destBounds | Rectangle | The destination image bounds. |
| entriesCount | Int32 | The desired entries count. |
| useImagePalette | Boolean | If set, it will use its own image palette if available |

## Return Value

The color palette which starts with the most frequent colors from the *image* and contains *entriesCount* entries.

### See Also

* interface [IColorPalette](../../icolorpalette)
* class [RasterImage](../../rasterimage)
* struct [Rectangle](../../rectangle)
* class [ColorPaletteHelper](../../colorpalettehelper)
* namespace [Aspose.Imaging](../../colorpalettehelper)
* assembly [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
