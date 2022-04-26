---
title: Jpeg2000Image
second_title: Aspose.Imaging for .NET API Reference
description: 
type: docs
weight: 10
url: /net/aspose.imaging.fileformats.jpeg2000/jpeg2000image/jpeg2000image/
---
## Jpeg2000Image constructor (1 of 9)

Initializes a new instance of the [`Jpeg2000Image`](../../jpeg2000image) class.

```csharp
public Jpeg2000Image(string path)
```

| Parameter | Type | Description |
| --- | --- | --- |
| path | String | The path to load image from and initialize pixel and palette data with. |

### Examples

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

* class [Jpeg2000Image](../../jpeg2000image)
* namespace [Aspose.Imaging.FileFormats.Jpeg2000](../../jpeg2000image)
* assembly [Aspose.Imaging](../../../)

---

## Jpeg2000Image constructor (2 of 9)

Initializes a new instance of the [`Jpeg2000Image`](../../jpeg2000image) class.

```csharp
public Jpeg2000Image(string path, int bitsPerPixel)
```

| Parameter | Type | Description |
| --- | --- | --- |
| path | String | The path to load image from and initialize pixel and palette data with |
| bitsPerPixel | Int32 | The bits per pixel. |

### See Also

* class [Jpeg2000Image](../../jpeg2000image)
* namespace [Aspose.Imaging.FileFormats.Jpeg2000](../../jpeg2000image)
* assembly [Aspose.Imaging](../../../)

---

## Jpeg2000Image constructor (3 of 9)

Initializes a new instance of the [`Jpeg2000Image`](../../jpeg2000image) class.

```csharp
public Jpeg2000Image(Stream stream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream to load image from and initialize pixel and palette data with. |

### Examples

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

* class [Jpeg2000Image](../../jpeg2000image)
* namespace [Aspose.Imaging.FileFormats.Jpeg2000](../../jpeg2000image)
* assembly [Aspose.Imaging](../../../)

---

## Jpeg2000Image constructor (4 of 9)

Initializes a new instance of the [`Jpeg2000Image`](../../jpeg2000image) class.

```csharp
public Jpeg2000Image(Stream stream, int bitsPerPixel)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream to load image from and initialize pixel and palette data with. |
| bitsPerPixel | Int32 | The bits per pixel. |

### See Also

* class [Jpeg2000Image](../../jpeg2000image)
* namespace [Aspose.Imaging.FileFormats.Jpeg2000](../../jpeg2000image)
* assembly [Aspose.Imaging](../../../)

---

## Jpeg2000Image constructor (5 of 9)

Initializes a new instance of the [`Jpeg2000Image`](../../jpeg2000image) class.

```csharp
public Jpeg2000Image(int width, int height)
```

| Parameter | Type | Description |
| --- | --- | --- |
| width | Int32 | The image width |
| height | Int32 | The image height |

### Examples

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

* class [Jpeg2000Image](../../jpeg2000image)
* namespace [Aspose.Imaging.FileFormats.Jpeg2000](../../jpeg2000image)
* assembly [Aspose.Imaging](../../../)

---

## Jpeg2000Image constructor (6 of 9)

Initializes a new instance of the [`Jpeg2000Image`](../../jpeg2000image) class.

```csharp
public Jpeg2000Image(int width, int height, Jpeg2000Options options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| width | Int32 | The image width |
| height | Int32 | The image height |
| options | Jpeg2000Options | The options. |

### Examples

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

* class [Jpeg2000Options](../../../aspose.imaging.imageoptions/jpeg2000options)
* class [Jpeg2000Image](../../jpeg2000image)
* namespace [Aspose.Imaging.FileFormats.Jpeg2000](../../jpeg2000image)
* assembly [Aspose.Imaging](../../../)

---

## Jpeg2000Image constructor (7 of 9)

Initializes a new instance of the [`Jpeg2000Image`](../../jpeg2000image) class.

```csharp
public Jpeg2000Image(int width, int height, int bitsCount)
```

| Parameter | Type | Description |
| --- | --- | --- |
| width | Int32 | The image width |
| height | Int32 | The image height |
| bitsCount | Int32 | The bits count. |

### See Also

* class [Jpeg2000Image](../../jpeg2000image)
* namespace [Aspose.Imaging.FileFormats.Jpeg2000](../../jpeg2000image)
* assembly [Aspose.Imaging](../../../)

---

## Jpeg2000Image constructor (8 of 9)

Initializes a new instance of the [`Jpeg2000Image`](../../jpeg2000image) class.

```csharp
public Jpeg2000Image(RasterImage image)
```

| Parameter | Type | Description |
| --- | --- | --- |
| image | RasterImage | The image. |

### Examples

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

* class [RasterImage](../../../aspose.imaging/rasterimage)
* class [Jpeg2000Image](../../jpeg2000image)
* namespace [Aspose.Imaging.FileFormats.Jpeg2000](../../jpeg2000image)
* assembly [Aspose.Imaging](../../../)

---

## Jpeg2000Image constructor (9 of 9)

Initializes a new instance of the [`Jpeg2000Image`](../../jpeg2000image) class.

```csharp
public Jpeg2000Image(RasterImage rasterImage, int bitsPerPixel)
```

| Parameter | Type | Description |
| --- | --- | --- |
| rasterImage | RasterImage | The image to initialize pixel and palette data with. |
| bitsPerPixel | Int32 | The bits per pixel. |

### See Also

* class [RasterImage](../../../aspose.imaging/rasterimage)
* class [Jpeg2000Image](../../jpeg2000image)
* namespace [Aspose.Imaging.FileFormats.Jpeg2000](../../jpeg2000image)
* assembly [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
