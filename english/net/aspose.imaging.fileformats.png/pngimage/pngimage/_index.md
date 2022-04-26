---
title: PngImage
second_title: Aspose.Imaging for .NET API Reference
description: 
type: docs
weight: 10
url: /net/aspose.imaging.fileformats.png/pngimage/pngimage/
---
## PngImage constructor (1 of 8)

Initializes a new instance of the [`PngImage`](../../pngimage) class.

```csharp
public PngImage(int width, int height)
```

| Parameter | Type | Description |
| --- | --- | --- |
| width | Int32 | The width. |
| height | Int32 | The height. |

### Examples

This example shows how to create a PNG image of the specified size, fill it with a solid color and save it to a file.

```csharp
[C#]

string dir = "c:\\temp\\";

// Create a PNG image of 100x100 px.
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(100, 100))
{
    // Do some image processing, e.g. fill the entire image in red.
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(pngImage);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    graphics.FillRectangle(brush, pngImage.Bounds);

    // Save to a file.
    pngImage.Save(dir + "output.png");
}
```

### See Also

* class [PngImage](../../pngimage)
* namespace [Aspose.Imaging.FileFormats.Png](../../pngimage)
* assembly [Aspose.Imaging](../../../)

---

## PngImage constructor (2 of 8)

Initializes a new instance of the [`PngImage`](../../pngimage) class.

```csharp
public PngImage(string path)
```

| Parameter | Type | Description |
| --- | --- | --- |
| path | String | The path to load an image. |

### Examples

This example shows how to load a PNG image from a file.

```csharp
[C#]

string dir = "c:\\temp\\";

// Load a PNG image from a file.
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(dir + "sample.png"))
{
    // Transform the image to grayscale representation
    pngImage.Grayscale();

    // Save to a file.
    pngImage.Save(dir + "sample.grayscale.png");
}
```

### See Also

* class [PngImage](../../pngimage)
* namespace [Aspose.Imaging.FileFormats.Png](../../pngimage)
* assembly [Aspose.Imaging](../../../)

---

## PngImage constructor (3 of 8)

Initializes a new instance of the [`PngImage`](../../pngimage) class.

```csharp
public PngImage(RasterImage rasterImage)
```

| Parameter | Type | Description |
| --- | --- | --- |
| rasterImage | RasterImage | The raster image. |

### Examples

This example shows how to load PNG image from a BMP image.

```csharp
[C#]

string dir = "c:\\temp\\";

// Load a TrueColor PNG image from a BMP image.
// First, create a temporal BMP image that will be a foundation for building a PNG image.
// You can also load BMP image from a file or use an image of any other raster format.
using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(100, 100))
{
    // Fill the entire BMP image in red.
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(bmpImage);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    gr.FillRectangle(brush, bmpImage.Bounds);

    using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(bmpImage))
    {
        System.Console.WriteLine("The PNG color type: {0}", pngImage.GetOriginalOptions());
        pngImage.Save(dir + "output.png");
    }
}
```

### See Also

* class [RasterImage](../../../aspose.imaging/rasterimage)
* class [PngImage](../../pngimage)
* namespace [Aspose.Imaging.FileFormats.Png](../../pngimage)
* assembly [Aspose.Imaging](../../../)

---

## PngImage constructor (4 of 8)

Initializes a new instance of the [`PngImage`](../../pngimage) class.

```csharp
public PngImage(string path, PngColorType colorType)
```

| Parameter | Type | Description |
| --- | --- | --- |
| path | String | The path to load an image. |
| colorType | PngColorType | The color type. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException |  |

### Examples

This example shows how to load a PNG image from a file with the specified color type.

```csharp
[C#]

string dir = "c:\\temp\\";

// Load a PNG image from a file.
// Note that the colorful image will be converted to grayscale automatically.
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(dir + "sample.png", Aspose.Imaging.FileFormats.Png.PngColorType.Grayscale))
{
    // Save to a file.
    pngImage.Save(dir + "sample.grayscale.png");
}
```

### See Also

* enum [PngColorType](../../pngcolortype)
* class [PngImage](../../pngimage)
* namespace [Aspose.Imaging.FileFormats.Png](../../pngimage)
* assembly [Aspose.Imaging](../../../)

---

## PngImage constructor (5 of 8)

Initializes a new instance of the [`PngImage`](../../pngimage) class.

```csharp
public PngImage(RasterImage rasterImage, PngColorType colorType)
```

| Parameter | Type | Description |
| --- | --- | --- |
| rasterImage | RasterImage | The raster image. |
| colorType | PngColorType | The color type. |

### Examples

This example shows how to load PNG image from a BMP image with the specified color type.

```csharp
[C#]

string dir = "c:\\temp\\";

// Load a grayscale PNG image from a colored BMP image.
// First, create a temporal BMP image that will be a foundation for building a PNG image.
// You can also load BMP image from a file or use an image of any other raster format.
using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(100, 100))
{
    // Fill the entire BMP image in red.
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(bmpImage);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    gr.FillRectangle(brush, bmpImage.Bounds);

    // The colors of the image pixels will be converted to their grayscale counterparts.
    using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(bmpImage, Aspose.Imaging.FileFormats.Png.PngColorType.Grayscale))
    {
        pngImage.Save(dir + "output.grayscale.png");
    }
}
```

### See Also

* class [RasterImage](../../../aspose.imaging/rasterimage)
* enum [PngColorType](../../pngcolortype)
* class [PngImage](../../pngimage)
* namespace [Aspose.Imaging.FileFormats.Png](../../pngimage)
* assembly [Aspose.Imaging](../../../)

---

## PngImage constructor (6 of 8)

Initializes a new instance of the [`PngImage`](../../pngimage) class.

```csharp
public PngImage(Stream stream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream to load an image. |

### Examples

This example shows how to load a PNG image from a file or a file stream.

```csharp
[C#]

string dir = "c:\\temp\\";

// Load a PNG image from a file stream.
using (System.IO.Stream stream = System.IO.File.OpenRead(dir + "sample.png"))
{
    using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(stream))
    {
        // Transform the image to grayscale representation
        pngImage.Grayscale();

        // Save to a file.
        pngImage.Save(dir + "sample.grayscale.png");
    }
}
```

### See Also

* class [PngImage](../../pngimage)
* namespace [Aspose.Imaging.FileFormats.Png](../../pngimage)
* assembly [Aspose.Imaging](../../../)

---

## PngImage constructor (7 of 8)

Initializes a new instance of the [`PngImage`](../../pngimage) class.

```csharp
public PngImage(int width, int height, PngColorType colorType)
```

| Parameter | Type | Description |
| --- | --- | --- |
| width | Int32 | The width. |
| height | Int32 | The height. |
| colorType | PngColorType | The color type. |

### Examples

This example shows how to create a PNG image of the specified size with the specified color type, fill it with a solid color and save it to a file.

```csharp
[C#]

string dir = "c:\\temp\\";

// Create a grayscale PNG image of 100x100 px.
// All colors will be automatically converted to the grayscale format.
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(100, 100, Aspose.Imaging.FileFormats.Png.PngColorType.Grayscale))
{
    // Do some image processing, e.g. fill the entire image in red.
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(pngImage);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    graphics.FillRectangle(brush, pngImage.Bounds);

    // Save to a file.
    pngImage.Save(dir + "output.grayscale.png");
}
```

### See Also

* enum [PngColorType](../../pngcolortype)
* class [PngImage](../../pngimage)
* namespace [Aspose.Imaging.FileFormats.Png](../../pngimage)
* assembly [Aspose.Imaging](../../../)

---

## PngImage constructor (8 of 8)

Initializes a new instance of the [`PngImage`](../../pngimage) class.

```csharp
public PngImage(PngOptions pngOptions, int width, int height)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pngOptions | PngOptions | The png options. |
| width | Int32 | The width. |
| height | Int32 | The height. |

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

### See Also

* class [PngOptions](../../../aspose.imaging.imageoptions/pngoptions)
* class [PngImage](../../pngimage)
* namespace [Aspose.Imaging.FileFormats.Png](../../pngimage)
* assembly [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
