---
title: WebPImage.WebPImage
second_title: Aspose.Imaging for .NET API Reference
description: WebPImage constructor. Instantiate a new instance of the WebPImage class initialized from a provided stream source. Utilize this constructor to seamlessly create WebP image objects directly from streams enabling efficient handling and manipulation of WebP image data within your application
type: docs
weight: 10
url: /net/aspose.imaging.fileformats.webp/webpimage/webpimage/
---
## WebPImage(Stream) {#constructor_4}

Instantiate a new instance of the [`WebPImage`](../) class, initialized from a provided stream source. Utilize this constructor to seamlessly create WebP image objects directly from streams, enabling efficient handling and manipulation of WebP image data within your application.

```csharp
public WebPImage(Stream stream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream WebP image. |

## Examples

This example shows how to load a WebP image from a file stream and save it to PNG.

```csharp
[C#]

string dir = "c:\\temp\\";

// Load a WebP image from a file stream.
using (System.IO.Stream stream = System.IO.File.OpenRead(dir + "test.webp"))
using (Aspose.Imaging.FileFormats.Webp.WebPImage webPImage = new Aspose.Imaging.FileFormats.Webp.WebPImage(stream))
{
    // Save to PNG
    // Note that only the active frame will be stored to PNG, since PNG is not a multi-page format.
    webPImage.Save(dir + "test.output.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### See Also

* class [WebPImage](../)
* namespace [Aspose.Imaging.FileFormats.Webp](../../webpimage/)
* assembly [Aspose.Imaging](../../../)

---

## WebPImage(Stream, LoadOptions) {#constructor_5}

Create a new instance of the [`WebPImage`](../) class using a stream and specified load options, facilitating versatile handling of WebP image data. Incorporate this constructor to seamlessly initialize WebP image objects from streams while customizing loading parameters as needed within your application.

```csharp
public WebPImage(Stream stream, LoadOptions loadOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream WebP image. |
| loadOptions | LoadOptions | The load options. |

### See Also

* class [LoadOptions](../../../aspose.imaging/loadoptions/)
* class [WebPImage](../)
* namespace [Aspose.Imaging.FileFormats.Webp](../../webpimage/)
* assembly [Aspose.Imaging](../../../)

---

## WebPImage(string) {#constructor_6}

Instantiate a fresh instance of the [`WebPImage`](../) class, initialized from a provided file source. Utilize this constructor to seamlessly create WebP image objects directly from files, streamlining the process of loading and manipulating WebP image data within your application.

```csharp
public WebPImage(string path)
```

| Parameter | Type | Description |
| --- | --- | --- |
| path | String | The path to file WebP Image |

## Examples

This example shows how to load a WebP image from a file and save it to PNG.

```csharp
[C#]

string dir = "c:\\temp\\";

// Load a WebP image from a file.
using (Aspose.Imaging.FileFormats.Webp.WebPImage webPImage = new Aspose.Imaging.FileFormats.Webp.WebPImage(dir + "test.webp"))
{
    // Save to PNG
    // Note that only the active frame will be stored to PNG, since PNG is not a multi-page format.
    webPImage.Save(dir + "test.output.png", new Aspose.Imaging.ImageOptions.PngOptions());
}
```

### See Also

* class [WebPImage](../)
* namespace [Aspose.Imaging.FileFormats.Webp](../../webpimage/)
* assembly [Aspose.Imaging](../../../)

---

## WebPImage(string, LoadOptions) {#constructor_7}

Create a new instance of the [`WebPImage`](../) class using a file and specified load options, facilitating flexible handling of WebP image data. Utilize this constructor to seamlessly initialize WebP image objects from files while customizing loading parameters according to your application's requirements.

```csharp
public WebPImage(string path, LoadOptions loadOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| path | String | The path to file WebP Image |
| loadOptions | LoadOptions | The load options. |

### See Also

* class [LoadOptions](../../../aspose.imaging/loadoptions/)
* class [WebPImage](../)
* namespace [Aspose.Imaging.FileFormats.Webp](../../webpimage/)
* assembly [Aspose.Imaging](../../../)

---

## WebPImage(RasterImage) {#constructor}

Instantiate a new instance of the [`WebPImage`](../) class, initialized from a provided rasterImage object. This constructor allows for seamless conversion of raster images to WebP format, enabling efficient handling and manipulation of image data within your application.

```csharp
public WebPImage(RasterImage rasterImage)
```

| Parameter | Type | Description |
| --- | --- | --- |
| rasterImage | RasterImage | The raster image. |

## Examples

This example shows how to create a WebP image from another raster image.

```csharp
[C#]

string dir = "c:\\temp\\";

// Load a PNG image of 100x100 px.
using (Aspose.Imaging.FileFormats.Png.PngImage pngImage = new Aspose.Imaging.FileFormats.Png.PngImage(100, 100))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(pngImage);

    // Fill the entire image in red.
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    graphics.FillRectangle(brush, pngImage.Bounds);

    // Create a WebP image based on the PNG image.
    using (Aspose.Imaging.FileFormats.Webp.WebPImage webPImage = new Aspose.Imaging.FileFormats.Webp.WebPImage(pngImage))
    {
        // Save to a WebP file with default options
        webPImage.Save(dir + "output.webp", new Aspose.Imaging.ImageOptions.WebPOptions());
    }
}
```

### See Also

* class [RasterImage](../../../aspose.imaging/rasterimage/)
* class [WebPImage](../)
* namespace [Aspose.Imaging.FileFormats.Webp](../../webpimage/)
* assembly [Aspose.Imaging](../../../)

---

## WebPImage(RasterImage, LoadOptions) {#constructor_1}

Create a new instance of the [`WebPImage`](../) class using a rasterImage object and specified load options, enabling flexible handling of image data. Utilize this constructor to seamlessly initialize WebP image objects from raster images while customizing loading parameters according to your application's requirements.

```csharp
public WebPImage(RasterImage rasterImage, LoadOptions loadOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| rasterImage | RasterImage | The raster image. |
| loadOptions | LoadOptions | The load options. |

### See Also

* class [RasterImage](../../../aspose.imaging/rasterimage/)
* class [LoadOptions](../../../aspose.imaging/loadoptions/)
* class [WebPImage](../)
* namespace [Aspose.Imaging.FileFormats.Webp](../../webpimage/)
* assembly [Aspose.Imaging](../../../)

---

## WebPImage(int, int, WebPOptions) {#constructor_2}

Instantiate a new instance of the [`WebPImage`](../) class with an empty image of specified width and height dimensions. This constructor allows for the creation of blank WebP images, providing a foundation for subsequent image manipulation and content generation within your application.

```csharp
public WebPImage(int width, int height, WebPOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| width | Int32 | The image width |
| height | Int32 | The image height. |
| options | WebPOptions | The options. |

## Examples

This example shows how to create a WebP image with the specified options from scratch.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.WebPOptions createOptions = new Aspose.Imaging.ImageOptions.WebPOptions();
createOptions.Lossless = true;
createOptions.Quality = 100f;
//createOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(dir + "output.webp");

// Create a WebP image of 100x100 px.
using (Aspose.Imaging.FileFormats.Webp.WebPImage webPImage = new Aspose.Imaging.FileFormats.Webp.WebPImage(100, 100, createOptions))
{
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(webPImage);

    // Fill the entire image in red.
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    graphics.FillRectangle(brush, webPImage.Bounds);

    // Save to a WebP file
    webPImage.Save(dir + "output.webp");
}
```

This example shows how to create a multi-frame animated WebP image with the specified options.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.WebPOptions createOptions = new Aspose.Imaging.ImageOptions.WebPOptions();
createOptions.Lossless = true;
createOptions.Quality = 100f;
createOptions.AnimBackgroundColor = (uint)Aspose.Imaging.Color.Gray.ToArgb();

// The default frame plus 36 + 36 additional frames.
createOptions.AnimLoopCount = 36 + 36 + 1;

// Create a WebP image of 100x100 px.
using (Aspose.Imaging.FileFormats.Webp.WebPImage webPImage = new Aspose.Imaging.FileFormats.Webp.WebPImage(100, 100, createOptions))
{
    // The first circle is red
    Aspose.Imaging.Brushes.SolidBrush brush1 = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);

    // The second circle is black
    Aspose.Imaging.Brushes.SolidBrush brush2 = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Black);

    // Gradually inscrease the angle of the red arc shape.
    for (int angle = 10; angle <= 360; angle += 10)
    {
        Aspose.Imaging.FileFormats.Webp.WebPFrameBlock block = new Aspose.Imaging.FileFormats.Webp.WebPFrameBlock(100, 100);
        Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(block);
        graphics.FillPie(brush1, block.Bounds, 0, angle);

        webPImage.AddBlock(block);
    }

    // Gradually inscrease the angle of the black arc and wipe out the red arc.
    for (int angle = 10; angle <= 360; angle += 10)
    {
        Aspose.Imaging.FileFormats.Webp.WebPFrameBlock block = new Aspose.Imaging.FileFormats.Webp.WebPFrameBlock(100, 100);

        Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(block);
        graphics.FillPie(brush2, block.Bounds, 0, angle);
        graphics.FillPie(brush1, block.Bounds, angle, 360 - angle);

        webPImage.AddBlock(block);
    }

    // Save to a WebP file
    webPImage.Save(dir + "output.webp");
}
```

### See Also

* class [WebPOptions](../../../aspose.imaging.imageoptions/webpoptions/)
* class [WebPImage](../)
* namespace [Aspose.Imaging.FileFormats.Webp](../../webpimage/)
* assembly [Aspose.Imaging](../../../)

---

## WebPImage(int, int, WebPOptions, LoadOptions) {#constructor_3}

Create a new instance of the [`WebPImage`](../) class with an empty image and specified load options. This constructor allows for the initialization of WebP images with customizable loading parameters, providing flexibility in image creation and manipulation within your application.

```csharp
public WebPImage(int width, int height, WebPOptions options, LoadOptions loadOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| width | Int32 | The image width |
| height | Int32 | The image height. |
| options | WebPOptions | The options. |
| loadOptions | LoadOptions | The load options. |

### See Also

* class [WebPOptions](../../../aspose.imaging.imageoptions/webpoptions/)
* class [LoadOptions](../../../aspose.imaging/loadoptions/)
* class [WebPImage](../)
* namespace [Aspose.Imaging.FileFormats.Webp](../../webpimage/)
* assembly [Aspose.Imaging](../../../)


