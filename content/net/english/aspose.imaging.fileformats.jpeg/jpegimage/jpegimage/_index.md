---
title: JpegImage
second_title: Aspose.Imaging for .NET API Reference
description: 
type: docs
weight: 10
url: /aspose.imaging.fileformats.jpeg/jpegimage/jpegimage/
---
## JpegImage constructor (1 of 5)

The [`JpegImage`](../../jpegimage) class initiates effortlessly by invoking its constructor with the specified path parameter. This constructor enables seamless creation of JPEG images, ensuring swift integration into your projects with ease.

```csharp
public JpegImage(string path)
```

| Parameter | Type | Description |
| --- | --- | --- |
| path | String | The path to load image from and initialize pixel and palette data with. |

### Examples

The example shows how to load a JpegImage from a file.

```csharp
[C#]

string dir = "c:\\temp\\";

// Load a JPEG image from a file.
using (Aspose.Imaging.FileFormats.Jpeg.JpegImage jpegImage = new Aspose.Imaging.FileFormats.Jpeg.JpegImage(dir + "sample.jpg"))
{
    // Do some image processing.
    // Save to another JPEG file.
    jpegImage.Save(dir + "sample.output.jpg");
}
```

### See Also

* class [JpegImage](../../jpegimage)
* namespace [Aspose.Imaging.FileFormats.Jpeg](../../jpegimage)
* assembly [Aspose.Imaging](../../../)

---

## JpegImage constructor (2 of 5)

Initialize a JPEG image object with the [`JpegImage`](../../jpegimage) class using a stream parameter. This constructor simplifies the process of working with JPEG images, offering a straightforward approach for integrating them into your projects effortlessly.

```csharp
public JpegImage(Stream stream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream to load image from and initialize pixel and palette data with. |

### Examples

The example shows how to load a JpegImage from a file stream.

```csharp
[C#]

string dir = "c:\\temp\\";

// Load a JPEG image from a file stream.
using (System.IO.Stream stream = System.IO.File.OpenRead(dir + "sample.jpg"))
{
    using (Aspose.Imaging.FileFormats.Jpeg.JpegImage jpegImage = new Aspose.Imaging.FileFormats.Jpeg.JpegImage(stream))
    {
        // Do some image processing.
        // Save to another JPEG file.
        jpegImage.Save(dir + "sample.output.jpg");
    }
}
```

### See Also

* class [JpegImage](../../jpegimage)
* namespace [Aspose.Imaging.FileFormats.Jpeg](../../jpegimage)
* assembly [Aspose.Imaging](../../../)

---

## JpegImage constructor (3 of 5)

Initialize a new instance of the [`JpegImage`](../../jpegimage) class with a raster image parameter. This constructor provides a convenient way to create JPEG images directly from raster images, streamlining the workflow for working with JPEG images in your applications.

```csharp
public JpegImage(RasterImage rasterImage)
```

| Parameter | Type | Description |
| --- | --- | --- |
| rasterImage | RasterImage | The image to initialize pixel and palette data with. |

### Examples

The example shows how to load a JpegImage from another RasterImage.

```csharp
[C#]

string dir = "c:\\temp\\";

// Load a JPEG image from another raster image.
// First, create a temporal PNG image that will be a foundation for building a JPEG image.
// You can also load PNG image from a file or use an image of any other raster format.
Aspose.Imaging.ImageOptions.PngOptions createOptions = new Aspose.Imaging.ImageOptions.PngOptions();
createOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream(), false);
using (Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Create(createOptions, 100, 100))
{
    // Fill the entire PNG image in red.
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(rasterImage);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    graphics.FillRectangle(brush, rasterImage.Bounds);

    // Create a JPEG image based on the PNG image.
    using (Aspose.Imaging.FileFormats.Jpeg.JpegImage jpegImage = new Aspose.Imaging.FileFormats.Jpeg.JpegImage(rasterImage))
    {
        // Save to a JPEG file
        jpegImage.Save(dir + "output.jpg");
    }
}
```

### See Also

* class [RasterImage](../../../aspose.imaging/rasterimage)
* class [JpegImage](../../jpegimage)
* namespace [Aspose.Imaging.FileFormats.Jpeg](../../jpegimage)
* assembly [Aspose.Imaging](../../../)

---

## JpegImage constructor (4 of 5)

Create a new instance of the [`JpegImage`](../../jpegimage) class with the specified width and height parameters. This constructor allows you to create JPEG images with custom dimensions, giving you flexibility in managing image sizes in your application.

```csharp
public JpegImage(int width, int height)
```

| Parameter | Type | Description |
| --- | --- | --- |
| width | Int32 | The image width. |
| height | Int32 | The image height. |

### Examples

The following example shows how to create JPEG image of the specified size.

```csharp
[C#]

string dir = "c:\\temp\\";

// Create a JPEG image of 100x100 px.
using (Aspose.Imaging.FileFormats.Jpeg.JpegImage jpegImage = new Aspose.Imaging.FileFormats.Jpeg.JpegImage(100, 100))
{
    // Do some image processing.
    // Save to a file.
    jpegImage.Save(dir + "output.jpg");
}
```

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

### See Also

* class [JpegImage](../../jpegimage)
* namespace [Aspose.Imaging.FileFormats.Jpeg](../../jpegimage)
* assembly [Aspose.Imaging](../../../)

---

## JpegImage constructor (5 of 5)

Initialize a new [`JpegImage`](../../jpegimage) object with the provided JPEG options. This constructor empowers you to tailor various settings for the JPEG image, such as compression level, quality, and additional parameters, granting precise control over the resulting image format.

```csharp
public JpegImage(JpegOptions jpegOptions, int width, int height)
```

| Parameter | Type | Description |
| --- | --- | --- |
| jpegOptions | JpegOptions | The jpeg options. |
| width | Int32 | Image width. |
| height | Int32 | Image height. |

### Examples

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

* class [JpegOptions](../../../aspose.imaging.imageoptions/jpegoptions)
* class [JpegImage](../../jpegimage)
* namespace [Aspose.Imaging.FileFormats.Jpeg](../../jpegimage)
* assembly [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
