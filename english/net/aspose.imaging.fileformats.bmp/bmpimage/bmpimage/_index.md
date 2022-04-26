---
title: BmpImage
second_title: Aspose.Imaging for .NET API Reference
description: 
type: docs
weight: 10
url: /net/aspose.imaging.fileformats.bmp/bmpimage/bmpimage/
---
## BmpImage constructor (1 of 9)

Initializes a new instance of the [`BmpImage`](../../bmpimage) class.

```csharp
public BmpImage(string path)
```

| Parameter | Type | Description |
| --- | --- | --- |
| path | String | The path to load image from and initialize pixel and palette data with. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | raster image is null;rasterImage |
| [BmpImageException](../../../aspose.imaging.coreexceptions.imageformats/bmpimageexception) | The height should be positive. |
| ArgumentException | Palette should be specified for images with 8 bits per pixel or less.;palette |

### Examples

The example shows how to load a BmpImage from a file.

```csharp
[C#]

string dir = "c:\\temp\\";

// Load a BMP image from a file.
// The source pixels will be converted to 32-bpp format if required.
using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(dir + "sample.bmp"))
{
    // Do some image processing.
    // Save to another BMP file.
    bmpImage.Save(dir + "sample.output.32bpp.bmp");
}
```

### See Also

* class [BmpImage](../../bmpimage)
* namespace [Aspose.Imaging.FileFormats.Bmp](../../bmpimage)
* assembly [Aspose.Imaging](../../../)

---

## BmpImage constructor (2 of 9)

Initializes a new instance of the [`BmpImage`](../../bmpimage) class.

```csharp
public BmpImage(string path, ushort bitsPerPixel, BitmapCompression compression, 
    double horizontalResolution, double verticalResolution)
```

| Parameter | Type | Description |
| --- | --- | --- |
| path | String | The path to load image from and initialize pixel and palette data with. |
| bitsPerPixel | UInt16 | The bits per pixel. |
| compression | BitmapCompression | The compression to use. |
| horizontalResolution | Double | The horizontal resolution. Note due to the rounding the resulting resolution may slightly differ from the passed. |
| verticalResolution | Double | The vertical resolution. Note due to the rounding the resulting resolution may slightly differ from the passed. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | The raster image cannot be null;rasterImage |
| [BmpImageException](../../../aspose.imaging.coreexceptions.imageformats/bmpimageexception) | The height should be positive. |
| ArgumentException | Palette should be specified for images with 8 bits per pixel or less.;palette |

### Examples

The example shows how to load a BmpImage from a file with the specified bit depth and resolution.

```csharp
[C#]

string dir = "c:\\temp\\";

// Load a BMP image from a file.
// The source pixels will be converted to 24-bpp format if required.
// The resolution will be set to 96 dpi.
using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage =
    new Aspose.Imaging.FileFormats.Bmp.BmpImage(dir + "sample.bmp", 24, Aspose.Imaging.FileFormats.Bmp.BitmapCompression.Rgb, 96.0, 96.0))
{
    // Do some image processing.
    // Save to another BMP file.
    bmpImage.Save(dir + "sample.output.24bpp.96dpi.bmp");
}
```

### See Also

* enum [BitmapCompression](../../bitmapcompression)
* class [BmpImage](../../bmpimage)
* namespace [Aspose.Imaging.FileFormats.Bmp](../../bmpimage)
* assembly [Aspose.Imaging](../../../)

---

## BmpImage constructor (3 of 9)

Initializes a new instance of the [`BmpImage`](../../bmpimage) class.

```csharp
public BmpImage(Stream stream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream to load image from and initialize pixel and palette data with. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | The raster image cannot be null;rasterImage |
| [BmpImageException](../../../aspose.imaging.coreexceptions.imageformats/bmpimageexception) | The height should be positive. |
| ArgumentException | Palette should be specified for images with 8 bits per pixel or less.;palette |

### Examples

The example shows how to load a BmpImage from a file stream.

```csharp
[C#]

string dir = "c:\\temp\\";

// Load a BMP image from a file stream.
// The source pixels will be converted to 32-bpp format if required.
using (System.IO.Stream stream = System.IO.File.OpenRead(dir + "sample.bmp"))
{
    using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(stream))
    {
        // Do some image processing.
        // Save to another BMP file.
        bmpImage.Save(dir + "sample.output.32bpp.bmp");
    }
}
```

### See Also

* class [BmpImage](../../bmpimage)
* namespace [Aspose.Imaging.FileFormats.Bmp](../../bmpimage)
* assembly [Aspose.Imaging](../../../)

---

## BmpImage constructor (4 of 9)

Initializes a new instance of the [`BmpImage`](../../bmpimage) class.

```csharp
public BmpImage(Stream stream, ushort bitsPerPixel, BitmapCompression compression, 
    double horizontalResolution, double verticalResolution)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream to load image from and initialize pixel and palette data with. |
| bitsPerPixel | UInt16 | The bits per pixel. |
| compression | BitmapCompression | The compression to use. |
| horizontalResolution | Double | The horizontal resolution. Note due to the rounding the resulting resolution may slightly differ from the passed. |
| verticalResolution | Double | The vertical resolution. Note due to the rounding the resulting resolution may slightly differ from the passed. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | The raster image cannot be null;rasterImage |
| [BmpImageException](../../../aspose.imaging.coreexceptions.imageformats/bmpimageexception) | The height should be positive. |
| ArgumentException | Palette should be specified for images with 8 bits per pixel or less.;palette |

### Examples

The example shows how to load a BmpImage from a file stream with the specified bit depth and resolution.

```csharp
[C#]

string dir = "c:\\temp\\";

// Load a BMP image from a file stream.
// The source pixels will be converted to 24-bpp format if required.
// The resolution will be set to 96 dpi.
using (System.IO.Stream stream = System.IO.File.OpenRead(dir + "sample.bmp"))
{
    using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage =
        new Aspose.Imaging.FileFormats.Bmp.BmpImage(stream, 24, Aspose.Imaging.FileFormats.Bmp.BitmapCompression.Rgb, 96.0, 96.0))
    {
        // Do some image processing.
        // Save to another BMP file.
        bmpImage.Save(dir + "sample.output.24bpp.96dpi.bmp");
    }
}
```

### See Also

* enum [BitmapCompression](../../bitmapcompression)
* class [BmpImage](../../bmpimage)
* namespace [Aspose.Imaging.FileFormats.Bmp](../../bmpimage)
* assembly [Aspose.Imaging](../../../)

---

## BmpImage constructor (5 of 9)

Initializes a new instance of the [`BmpImage`](../../bmpimage) class.

```csharp
public BmpImage(RasterImage rasterImage)
```

| Parameter | Type | Description |
| --- | --- | --- |
| rasterImage | RasterImage | The image to initialize pixel and palette data with. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | The raster image cannot be null;rasterImage |
| [BmpImageException](../../../aspose.imaging.coreexceptions.imageformats/bmpimageexception) | The height should be positive. |
| ArgumentException | Palette should be specified for images with 8 bits per pixel or less.;palette |

### Examples

The example shows how to load a BmpImage from another instance of RasterImage.

```csharp
[C#]

string dir = "c:\\temp\\";

// Create a new PNG image.
Aspose.Imaging.ImageOptions.PngOptions createOptions = new Aspose.Imaging.ImageOptions.PngOptions();
createOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream(), true);
using (Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Create(createOptions, 100, 100))
{
    // Fill the entire PNG image in red.
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(rasterImage);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    gr.FillRectangle(brush, rasterImage.Bounds);

    // Create a BMP image based on the PNG image.
    // The source pixels will be converted to 32-bpp format if required.
    using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(rasterImage))
    {
        // Save to a BMP file
        bmpImage.Save(dir + "output.32bpp.bmp");
    }
}
```

### See Also

* class [RasterImage](../../../aspose.imaging/rasterimage)
* class [BmpImage](../../bmpimage)
* namespace [Aspose.Imaging.FileFormats.Bmp](../../bmpimage)
* assembly [Aspose.Imaging](../../../)

---

## BmpImage constructor (6 of 9)

Initializes a new instance of the [`BmpImage`](../../bmpimage) class.

```csharp
public BmpImage(RasterImage rasterImage, ushort bitsPerPixel, BitmapCompression compression, 
    double horizontalResolution, double verticalResolution)
```

| Parameter | Type | Description |
| --- | --- | --- |
| rasterImage | RasterImage | The image to initialize pixel and palette data with. |
| bitsPerPixel | UInt16 | The bits per pixel. |
| compression | BitmapCompression | The compression to use. |
| horizontalResolution | Double | The horizontal resolution. Note due to the rounding the resulting resolution may slightly differ from the passed. |
| verticalResolution | Double | The vertical resolution. Note due to the rounding the resulting resolution may slightly differ from the passed. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | The raster image cannot be null;rasterImage |
| [BmpImageException](../../../aspose.imaging.coreexceptions.imageformats/bmpimageexception) | The height should be positive. |
| ArgumentException | Palette should be specified for images with 8 bits per pixel or less.;palette |

### Examples

The example shows how to load a BmpImage from another instance of RasterImage with the specified bit depth and compression.

```csharp
[C#]

string dir = "c:\\temp\\";

// Create a new PNG image.
Aspose.Imaging.ImageOptions.PngOptions createOptions = new Aspose.Imaging.ImageOptions.PngOptions();
createOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream(), true);
using (Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Create(createOptions, 100, 100))
{
    // Fill the entire PNG image in red.
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(rasterImage);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    gr.FillRectangle(brush, rasterImage.Bounds);

    // Create a BMP image based on the PNG image.
    // The source pixels will be converted to 24-bpp format if required.
    // The resolution will be set to 96 dpi.
    using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(rasterImage, 24, Aspose.Imaging.FileFormats.Bmp.BitmapCompression.Rgb, 96.0, 96.0))
    {
        // Save to a BMP file
        bmpImage.Save(dir + "output.24bpp.96dpi.bmp");
    }
}
```

### See Also

* class [RasterImage](../../../aspose.imaging/rasterimage)
* enum [BitmapCompression](../../bitmapcompression)
* class [BmpImage](../../bmpimage)
* namespace [Aspose.Imaging.FileFormats.Bmp](../../bmpimage)
* assembly [Aspose.Imaging](../../../)

---

## BmpImage constructor (7 of 9)

Initializes a new instance of the [`BmpImage`](../../bmpimage) class.

```csharp
public BmpImage(int width, int height)
```

| Parameter | Type | Description |
| --- | --- | --- |
| width | Int32 | The image width. |
| height | Int32 | The image height. |

### Exceptions

| exception | condition |
| --- | --- |
| [BmpImageException](../../../aspose.imaging.coreexceptions.imageformats/bmpimageexception) | The height should be positive. |
| ArgumentException | Palette should be specified for images with 8 bits per pixel or less.;palette |

### Examples

The example shows how to create a BmpImage of the specified size.

```csharp
[C#]

string dir = "c:\\temp\\";

// Create a 32-bpp BMP image of 100 x 100 px.
using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(100, 100))
{
    // Fill the entire image in red.
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(bmpImage);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    gr.FillRectangle(brush, bmpImage.Bounds);

    // Save to a BMP file
    bmpImage.Save(dir + "output.bmp");
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

* class [BmpImage](../../bmpimage)
* namespace [Aspose.Imaging.FileFormats.Bmp](../../bmpimage)
* assembly [Aspose.Imaging](../../../)

---

## BmpImage constructor (8 of 9)

Initializes a new instance of the [`BmpImage`](../../bmpimage) class.

```csharp
public BmpImage(int width, int height, ushort bitsPerPixel, IColorPalette palette)
```

| Parameter | Type | Description |
| --- | --- | --- |
| width | Int32 | The image width. |
| height | Int32 | The image height. |
| bitsPerPixel | UInt16 | The bits per pixel. |
| palette | IColorPalette | The color palette. |

### Exceptions

| exception | condition |
| --- | --- |
| [BmpImageException](../../../aspose.imaging.coreexceptions.imageformats/bmpimageexception) | The height should be positive. |
| ArgumentException | Palette should be specified for images with 8 bits per pixel or less.;palette |

### Examples

The example shows how to create a BmpImage of the specified size with the specified palette.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.Color[] paletterColors = new Aspose.Imaging.Color[]
{
    Aspose.Imaging.Color.Red,
    Aspose.Imaging.Color.Green,
};

// Create a monochrome palette which contains only red and green colors.
Aspose.Imaging.IColorPalette palette = new Aspose.Imaging.ColorPalette(paletterColors);

// Create a monochrome 1-bpp BMP image of 100 x 100 px.
using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(100, 100, 1, palette))
{
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(bmpImage);

    // Fill the upper half of the image in red.
    Aspose.Imaging.Brushes.SolidBrush redBrush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    gr.FillRectangle(redBrush, new Aspose.Imaging.Rectangle(0, 0, bmpImage.Width, bmpImage.Height / 2));

    // Fill the lower half of the image in green.
    Aspose.Imaging.Brushes.SolidBrush greenBrush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Green);
    gr.FillRectangle(greenBrush, new Aspose.Imaging.Rectangle(0, bmpImage.Height / 2, bmpImage.Width, bmpImage.Height / 2));

    // Save to BMP
    bmpImage.Save(dir + "output.monochrome.bmp");
}
```

### See Also

* interface [IColorPalette](../../../aspose.imaging/icolorpalette)
* class [BmpImage](../../bmpimage)
* namespace [Aspose.Imaging.FileFormats.Bmp](../../bmpimage)
* assembly [Aspose.Imaging](../../../)

---

## BmpImage constructor (9 of 9)

Initializes a new instance of the [`BmpImage`](../../bmpimage) class.

```csharp
public BmpImage(int width, int height, ushort bitsPerPixel, IColorPalette palette, 
    BitmapCompression compression, double horizontalResolution, double verticalResolution)
```

| Parameter | Type | Description |
| --- | --- | --- |
| width | Int32 | The image width. |
| height | Int32 | The image height. |
| bitsPerPixel | UInt16 | The bits per pixel. |
| palette | IColorPalette | The color palette. |
| compression | BitmapCompression | The compression to use. |
| horizontalResolution | Double | The horizontal resolution. Note due to the rounding the resulting resolution may slightly differ from the passed. |
| verticalResolution | Double | The vertical resolution. Note due to the rounding the resulting resolution may slightly differ from the passed. |

### Exceptions

| exception | condition |
| --- | --- |
| [BmpImageException](../../../aspose.imaging.coreexceptions.imageformats/bmpimageexception) | The height should be positive. |
| ArgumentException | Palette should be specified for images with 8 bits per pixel or less.;palette |

### Examples

The example shows how to create a BmpImage using various options.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.Color[] paletterColors = new Aspose.Imaging.Color[]
{
    Aspose.Imaging.Color.Red,
    Aspose.Imaging.Color.Green,
};

// Create a monochrome palette which contains only red and green colors.
Aspose.Imaging.IColorPalette palette = new Aspose.Imaging.ColorPalette(paletterColors);

// Create a monochrome 1-bpp BMP image of 100 x 100 px.
// The horizontal and vertical resolution will be set to 96 dpi.
using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(100, 100, 1, palette, Aspose.Imaging.FileFormats.Bmp.BitmapCompression.Rgb, 96.0, 96.0))
{
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(bmpImage);

    // Fill the upper half of the image in red.
    Aspose.Imaging.Brushes.SolidBrush redBrush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    gr.FillRectangle(redBrush, new Aspose.Imaging.Rectangle(0, 0, bmpImage.Width, bmpImage.Height / 2));

    // Fill the lower half of the image in green.
    Aspose.Imaging.Brushes.SolidBrush greenBrush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Green);
    gr.FillRectangle(greenBrush, new Aspose.Imaging.Rectangle(0, bmpImage.Height / 2, bmpImage.Width, bmpImage.Height / 2));

    // Save to a BMP file
    bmpImage.Save(dir + "output.monochrome.96dpi.bmp");
}
```

### See Also

* interface [IColorPalette](../../../aspose.imaging/icolorpalette)
* enum [BitmapCompression](../../bitmapcompression)
* class [BmpImage](../../bmpimage)
* namespace [Aspose.Imaging.FileFormats.Bmp](../../bmpimage)
* assembly [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
