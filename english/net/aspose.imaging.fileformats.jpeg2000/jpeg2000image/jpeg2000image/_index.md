---
title: Jpeg2000Image.Jpeg2000Image
second_title: Aspose.Imaging for .NET API Reference
description: Jpeg2000Image constructor. Start working with the Jpeg2000Image class by initializing a new instance with the path to the image you want to load. This constructor enables easy access to JPEG2000 images simplifying the process of loading and handling image files. By providing the file path you can quickly begin processing and manipulating JPEG2000 images in your application
type: docs
weight: 10
url: /net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/jpeg2000image/
---
## Jpeg2000Image(string) {#constructor_7}

Start working with the [`Jpeg2000Image`](../) class by initializing a new instance with the path to the image you want to load. This constructor enables easy access to JPEG2000 images, simplifying the process of loading and handling image files. By providing the file path, you can quickly begin processing and manipulating JPEG2000 images in your application.

```csharp
public Jpeg2000Image(string path)
```

| Parameter | Type | Description |
| --- | --- | --- |
| path | String | The path to load image from and initialize pixel and palette data with. |

## Examples

This example shows how to load a JPEG2000 image from a file and save it to PNG.

```csharp
[C#]

string dir = "c:\\temp\\";

// Load a JPEG2000 image.
using (Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image jpeg2000Image = new Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image(dir + "sample.jp2"))
{
    // Save to PNG
    jpeg2000Image.Save(dir + "sample.output.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### See Also

* class [Jpeg2000Image](../)
* namespace [Aspose.Imaging.FileFormats.Jpeg2000](../../jpeg2000image/)
* assembly [Aspose.Imaging](../../../)

---

## Jpeg2000Image(string, int) {#constructor_8}

Get started easily with the [`Jpeg2000Image`](../) class by creating a new instance with both the file path and the desired bits per pixel parameter. This constructor allows for fine-tuning the image loading process, ensuring compatibility with various image formats and quality settings. With this flexibility, you can efficiently manage and manipulate JPEG2000 images according to your specific requirements.

```csharp
public Jpeg2000Image(string path, int bitsPerPixel)
```

| Parameter | Type | Description |
| --- | --- | --- |
| path | String | The path to load image from and initialize pixel and palette data with |
| bitsPerPixel | Int32 | The bits per pixel. |

### See Also

* class [Jpeg2000Image](../)
* namespace [Aspose.Imaging.FileFormats.Jpeg2000](../../jpeg2000image/)
* assembly [Aspose.Imaging](../../../)

---

## Jpeg2000Image(Stream) {#constructor_5}

Easily initialize a new instance of the [`Jpeg2000Image`](../) class by providing a stream object. This constructor simplifies the process of loading JPEG2000 images directly from streams, offering flexibility and convenience for handling image data from various sources.

```csharp
public Jpeg2000Image(Stream stream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream to load image from and initialize pixel and palette data with. |

## Examples

This example shows how to load a JPEG2000 image from a file stream and save it to PNG.

```csharp
[C#]

string dir = "c:\\temp\\";

// Load a JPEG2000 image from stream.
using (System.IO.Stream stream = System.IO.File.OpenRead(dir + "sample.jp2"))
using (Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image jpeg2000Image = new Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image(stream))
{
    // Save to PNG
    jpeg2000Image.Save(dir + "sample.output.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### See Also

* class [Jpeg2000Image](../)
* namespace [Aspose.Imaging.FileFormats.Jpeg2000](../../jpeg2000image/)
* assembly [Aspose.Imaging](../../../)

---

## Jpeg2000Image(Stream, int) {#constructor_6}

Initialize a new instance of the [`Jpeg2000Image`](../) class with a stream to load the image, along with bits per pixel parameters. This constructor offers flexibility by allowing you to specify both the image data source and the desired bits per pixel, providing finer control over the image loading process.

```csharp
public Jpeg2000Image(Stream stream, int bitsPerPixel)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream to load image from and initialize pixel and palette data with. |
| bitsPerPixel | Int32 | The bits per pixel. |

### See Also

* class [Jpeg2000Image](../)
* namespace [Aspose.Imaging.FileFormats.Jpeg2000](../../jpeg2000image/)
* assembly [Aspose.Imaging](../../../)

---

## Jpeg2000Image(int, int) {#constructor_2}

Create a new instance of the [`Jpeg2000Image`](../) class, specifying the width and height parameters. This constructor allows you to initialize a JPEG2000 image with specific dimensions, which is useful for scenarios where you need to create an image of a certain size programmatically.

```csharp
public Jpeg2000Image(int width, int height)
```

| Parameter | Type | Description |
| --- | --- | --- |
| width | Int32 | The image width |
| height | Int32 | The image height |

## Examples

This example shows how to create a JPEG2000 image and save it to a file.

```csharp
[C#]

string dir = "c:\\temp\\";

// Create a JPEG2000 image of 100x100 px.
using (Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image jpeg2000Image = new Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image(100, 100))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(jpeg2000Image);

    // Fill the entire image in red.
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    graphics.FillRectangle(brush, jpeg2000Image.Bounds);

    // Save to a file
    jpeg2000Image.Save(dir + "sample.output.jp2", new Aspose.Imaging.ImageOptions.Jpeg2000Options());
}
```

### See Also

* class [Jpeg2000Image](../)
* namespace [Aspose.Imaging.FileFormats.Jpeg2000](../../jpeg2000image/)
* assembly [Aspose.Imaging](../../../)

---

## Jpeg2000Image(int, int, Jpeg2000Options) {#constructor_3}

Instantiate a new [`Jpeg2000Image`](../) object, providing the width, height, and image options parameters. This constructor allows for the creation of JPEG2000 images with specific dimensions and additional options, offering flexibility in image generation.

```csharp
public Jpeg2000Image(int width, int height, Jpeg2000Options options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| width | Int32 | The image width |
| height | Int32 | The image height |
| options | Jpeg2000Options | The options. |

## Examples

This example shows how to create a PNG image and save it to JPEG2000 with the desired options.

```csharp
[C#]

string dir = "c:\\temp\\";

// Create a PNG image of 100x100 px.
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(100, 100))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(pngImage);

    // Fill the entire image in red.
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    graphics.FillRectangle(brush, pngImage.Bounds);

    Aspose.Imaging.ImageOptions.Jpeg2000Options saveOptions = new Aspose.Imaging.ImageOptions.Jpeg2000Options();

    // Use the irreversible Discrete Wavelet Transform 9-7
    saveOptions.Irreversible = true;

    // JP2 is the "container" format for JPEG 2000 codestreams.
    // J2K is raw compressed data, without a wrapper.
    saveOptions.Codec = Imaging.FileFormats.Jpeg2000.Jpeg2000Codec.J2K;

    // Save to a file
    pngImage.Save(dir + "output.j2k", saveOptions);
}
```

This example shows how to create a JPEG2000 image with the desired options and save it to a file.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.Jpeg2000Options createOptions = new Aspose.Imaging.ImageOptions.Jpeg2000Options();

// Use the irreversible Discrete Wavelet Transform 9-7
createOptions.Irreversible = true;

// JP2 is the "container" format for JPEG 2000 codestreams.
// J2K is raw compressed data, without a wrapper.
createOptions.Codec = Imaging.FileFormats.Jpeg2000.Jpeg2000Codec.J2K;

// Create a JPEG2000 image of 100x100 px.
using (Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image jpeg2000Image = new Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image(100, 100, createOptions))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(jpeg2000Image);

    // Fill the entire image in red.
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    graphics.FillRectangle(brush, jpeg2000Image.Bounds);

    // Save to a file
    jpeg2000Image.Save(dir + "sample.output.j2k");
}
```

### See Also

* class [Jpeg2000Options](../../../aspose.imaging.imageoptions/jpeg2000options/)
* class [Jpeg2000Image](../)
* namespace [Aspose.Imaging.FileFormats.Jpeg2000](../../jpeg2000image/)
* assembly [Aspose.Imaging](../../../)

---

## Jpeg2000Image(int, int, int) {#constructor_4}

Create a new instance of the [`Jpeg2000Image`](../) class with parameters for width, height, and bits count. This constructor allows for the creation of JPEG2000 images with specific dimensions and bit depths, providing flexibility for various imaging needs.

```csharp
public Jpeg2000Image(int width, int height, int bitsCount)
```

| Parameter | Type | Description |
| --- | --- | --- |
| width | Int32 | The image width |
| height | Int32 | The image height |
| bitsCount | Int32 | The bits count. |

### See Also

* class [Jpeg2000Image](../)
* namespace [Aspose.Imaging.FileFormats.Jpeg2000](../../jpeg2000image/)
* assembly [Aspose.Imaging](../../../)

---

## Jpeg2000Image(RasterImage) {#constructor}

Instantiate a new [`Jpeg2000Image`](../) class with a raster image. This constructor facilitates the creation of a JPEG2000 image from an existing raster image, offering seamless integration and conversion between different image formats.

```csharp
public Jpeg2000Image(RasterImage image)
```

| Parameter | Type | Description |
| --- | --- | --- |
| image | RasterImage | The image. |

## Examples

This example shows how to create a JPEG2000 image with from another raster image.

```csharp
[C#]

string dir = "c:\\temp\\";

// Create a PNG image of 100x100 px.
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(100, 100))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(pngImage);

    // Fill the entire image in red.
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    graphics.FillRectangle(brush, pngImage.Bounds);

    // Create a JPEG2000 image based on the PNG image.
    using (Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image jpeg2000Image = new Aspose.Imaging.FileFormats.Jpeg2000.Jpeg2000Image(pngImage))
    {
        // Save to a file
        jpeg2000Image.Save(dir + "output.jp2", new Aspose.Imaging.ImageOptions.Jpeg2000Options());
    }
}
```

### See Also

* class [RasterImage](../../../aspose.imaging/rasterimage/)
* class [Jpeg2000Image](../)
* namespace [Aspose.Imaging.FileFormats.Jpeg2000](../../jpeg2000image/)
* assembly [Aspose.Imaging](../../../)

---

## Jpeg2000Image(RasterImage, int) {#constructor_1}

Initialize a fresh [`Jpeg2000Image`](../) instance with a raster image and bits per pixel parameters. This constructor enables precise control over the quality and size of the resulting JPEG2000 image, making it ideal for scenarios where customization is crucial.

```csharp
public Jpeg2000Image(RasterImage rasterImage, int bitsPerPixel)
```

| Parameter | Type | Description |
| --- | --- | --- |
| rasterImage | RasterImage | The image to initialize pixel and palette data with. |
| bitsPerPixel | Int32 | The bits per pixel. |

### See Also

* class [RasterImage](../../../aspose.imaging/rasterimage/)
* class [Jpeg2000Image](../)
* namespace [Aspose.Imaging.FileFormats.Jpeg2000](../../jpeg2000image/)
* assembly [Aspose.Imaging](../../../)


