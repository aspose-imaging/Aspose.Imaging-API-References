---
title: TiffFrame.TiffFrame
second_title: Aspose.Imaging for .NET API Reference
description: TiffFrame constructor. Initializes a new instance of the TiffFrame class
type: docs
weight: 10
url: /net/aspose.imaging.fileformats.tiff/tiffframe/tiffframe/
---
## TiffFrame(Stream) {#constructor_3}

Initializes a new instance of the [`TiffFrame`](../) class.

```csharp
public TiffFrame(Stream stream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream to load an image from and initialize frame pixel and palette data with. |

### See Also

* class [TiffFrame](../)
* namespace [Aspose.Imaging.FileFormats.Tiff](../../tiffframe/)
* assembly [Aspose.Imaging](../../../)

---

## TiffFrame(Stream, TiffOptions) {#constructor_4}

Initializes a new instance of the [`TiffFrame`](../) class.

```csharp
public TiffFrame(Stream stream, TiffOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream to load an image from and initialize frame pixel and palette data with. |
| options | TiffOptions | The options to use for the newly created frame. |

### See Also

* class [TiffOptions](../../../aspose.imaging.imageoptions/tiffoptions/)
* class [TiffFrame](../)
* namespace [Aspose.Imaging.FileFormats.Tiff](../../tiffframe/)
* assembly [Aspose.Imaging](../../../)

---

## TiffFrame(string) {#constructor_5}

Initializes a new instance of the [`TiffFrame`](../) class.

```csharp
public TiffFrame(string path)
```

| Parameter | Type | Description |
| --- | --- | --- |
| path | String | The path to load an image from and initialize frame pixel and palette data with. |

### See Also

* class [TiffFrame](../)
* namespace [Aspose.Imaging.FileFormats.Tiff](../../tiffframe/)
* assembly [Aspose.Imaging](../../../)

---

## TiffFrame(string, TiffOptions) {#constructor_6}

Initializes a new instance of the [`TiffFrame`](../) class.

```csharp
public TiffFrame(string path, TiffOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| path | String | The path to load an image from and initialize frame pixel and palette data with. |
| options | TiffOptions | The options to use for the newly created frame. |

### See Also

* class [TiffOptions](../../../aspose.imaging.imageoptions/tiffoptions/)
* class [TiffFrame](../)
* namespace [Aspose.Imaging.FileFormats.Tiff](../../tiffframe/)
* assembly [Aspose.Imaging](../../../)

---

## TiffFrame(RasterImage) {#constructor_1}

Initializes a new instance of the [`TiffFrame`](../) class.

```csharp
public TiffFrame(RasterImage image)
```

| Parameter | Type | Description |
| --- | --- | --- |
| image | RasterImage | The image to initialize frame pixel and palette data with. |

## Examples

The following example shows how to compose a mutlipage TIFF from individual raster images.

```csharp
[C#]

Aspose.Imaging.ImageOptions.TiffOptions createTiffOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Aspose.Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);
createTiffOptions.Source = new Aspose.Imaging.Sources.FileCreateSource("c:\\temp\\multipage.tif", false);
createTiffOptions.Photometric = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.Rgb;
createTiffOptions.BitsPerSample = new ushort[] { 8, 8, 8 };

using (Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = (Aspose.Imaging.FileFormats.Tiff.TiffImage)Image.Create(createTiffOptions, 100, 100))
{
    // This is Font and Brush for drawing text on individual frames.
    Aspose.Imaging.Font font = new Aspose.Imaging.Font("Arial", 64);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.White);

    // Create 5 frames
    for (int i = 1; i <= 5; i++)
    {
        Aspose.Imaging.ImageOptions.PngOptions createPngOptions = new Aspose.Imaging.ImageOptions.PngOptions();
        createPngOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream());

        // Create a PNG image and draw the number of page on it.
        Aspose.Imaging.FileFormats.Png.PngImage pngImage = (Aspose.Imaging.FileFormats.Png.PngImage)Image.Create(createPngOptions, 100, 100);
        Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(pngImage);
        gr.DrawString(i.ToString(), font, brush, 10, 10);

        // Create a frame based on the PNG image.
        Aspose.Imaging.FileFormats.Tiff.TiffFrame frame = new Aspose.Imaging.FileFormats.Tiff.TiffFrame(pngImage);

        // Add the frame to the TIFF image.
        tiffImage.AddFrame(frame);
    }

    // The image was created with a single default frame. Let's remove it.
    Aspose.Imaging.FileFormats.Tiff.TiffFrame activeFrame = tiffImage.ActiveFrame;
    tiffImage.ActiveFrame = tiffImage.Frames[1];
    tiffImage.RemoveFrame(0);

    // Don't forget to dispose the frame if you won't add it to some other TiffImage
    activeFrame.Dispose();

    tiffImage.Save();
}
```

### See Also

* class [RasterImage](../../../aspose.imaging/rasterimage/)
* class [TiffFrame](../)
* namespace [Aspose.Imaging.FileFormats.Tiff](../../tiffframe/)
* assembly [Aspose.Imaging](../../../)

---

## TiffFrame(RasterImage, TiffOptions) {#constructor_2}

Initializes a new instance of the [`TiffFrame`](../) class.

```csharp
public TiffFrame(RasterImage image, TiffOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| image | RasterImage | The image to initialize frame pixel and palette data with. |
| options | TiffOptions | The options to use for the newly created frame. |

### See Also

* class [RasterImage](../../../aspose.imaging/rasterimage/)
* class [TiffOptions](../../../aspose.imaging.imageoptions/tiffoptions/)
* class [TiffFrame](../)
* namespace [Aspose.Imaging.FileFormats.Tiff](../../tiffframe/)
* assembly [Aspose.Imaging](../../../)

---

## TiffFrame(TiffOptions, int, int) {#constructor}

Initializes a new instance of the [`TiffFrame`](../) class.

```csharp
public TiffFrame(TiffOptions options, int width, int height)
```

| Parameter | Type | Description |
| --- | --- | --- |
| options | TiffOptions | The frame options. |
| width | Int32 | The width. |
| height | Int32 | The height. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Options parameter is null. |

## Examples

This example shows how to create a TIFF image from scratch and save it to a file.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.TiffOptions createOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);
    
// Set 8 bits for each color component.
createOptions.BitsPerSample = new ushort[] { 8, 8, 8 };

// Set the Big Endian byte order (Motorola)
createOptions.ByteOrder = Aspose.Imaging.FileFormats.Tiff.Enums.TiffByteOrder.BigEndian;

// Set the LZW compression.
createOptions.Compression = Aspose.Imaging.FileFormats.Tiff.Enums.TiffCompressions.Lzw;

// Set the RGB color model.
createOptions.Photometric = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.Rgb;

// All color components will be stored within a single plane.
createOptions.PlanarConfiguration = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPlanarConfigs.Contiguous;

// Create a TIFF Frame of 100x100 px.
// Note that you don't have to dispose a frame explicitly if it is included into TiffImage.
// When the container is disposed all frames will be disposed automatically.
Aspose.Imaging.FileFormats.Tiff.TiffFrame firstFrame = new Aspose.Imaging.FileFormats.Tiff.TiffFrame(createOptions, 100, 100);
    
// Fill the entire frame with the blue-yellow gradient.
Aspose.Imaging.Brushes.LinearGradientBrush gradientBrush = new Aspose.Imaging.Brushes.LinearGradientBrush(
        new Aspose.Imaging.Point(0, 0),
        new Aspose.Imaging.Point(firstFrame.Width, firstFrame.Height),
        Aspose.Imaging.Color.Blue,
        Aspose.Imaging.Color.Yellow);

Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(firstFrame);
graphics.FillRectangle(gradientBrush, firstFrame.Bounds);

// Create a TIFF image.
using (Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = new Aspose.Imaging.FileFormats.Tiff.TiffImage(firstFrame))
{
    tiffImage.Save(dir + "output.tif");
}
```

This example shows how to create a TIFF image with 2 frames and save it to a file.

```csharp
[C#]

string dir = "c:\\temp\\";

// Options for the first frame
Aspose.Imaging.ImageOptions.TiffOptions createOptions1 = new Aspose.Imaging.ImageOptions.TiffOptions(Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

// Set 8 bits for each color component.
createOptions1.BitsPerSample = new ushort[] { 8, 8, 8 };

// Set the Big Endian byte order (Motorola)
createOptions1.ByteOrder = Aspose.Imaging.FileFormats.Tiff.Enums.TiffByteOrder.BigEndian;

// Set the LZW compression.
createOptions1.Compression = Aspose.Imaging.FileFormats.Tiff.Enums.TiffCompressions.Lzw;

// Set the RGB color model.
createOptions1.Photometric = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.Rgb;

// All color components will be stored within a single plane.
createOptions1.PlanarConfiguration = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPlanarConfigs.Contiguous;

// Create the first TIFF frame of 100x100 px.
// Note that you don't have to dispose frames explicitly if they are included into TiffImage.
// When the container is disposed all frames will be disposed automatically.
Aspose.Imaging.FileFormats.Tiff.TiffFrame frame1 = new Aspose.Imaging.FileFormats.Tiff.TiffFrame(createOptions1, 100, 100);

// Fill the first frame with the blue-yellow gradient.
Aspose.Imaging.Brushes.LinearGradientBrush gradientBrush = new Aspose.Imaging.Brushes.LinearGradientBrush(
        new Aspose.Imaging.Point(0, 0),
        new Aspose.Imaging.Point(frame1.Width, frame1.Height),
        Aspose.Imaging.Color.Blue,
        Aspose.Imaging.Color.Yellow);

Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(frame1);
graphics.FillRectangle(gradientBrush, frame1.Bounds);

// Options for the first frame
Aspose.Imaging.ImageOptions.TiffOptions createOptions2 = new Aspose.Imaging.ImageOptions.TiffOptions(Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

// Set 1 bit per pixel for a B/W image.
createOptions2.BitsPerSample = new ushort[] { 1 };

// Set the Little Endian byte order (Intel)
createOptions2.ByteOrder = Aspose.Imaging.FileFormats.Tiff.Enums.TiffByteOrder.LittleEndian;

// Set the CCITT Group 3 Fax compression.
createOptions2.Compression = Aspose.Imaging.FileFormats.Tiff.Enums.TiffCompressions.CcittFax3;

// Set the B/W color model where 0 is black, 1 is white.
createOptions2.Photometric = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.MinIsBlack;

// Create the second TIFF frame of 200x200px.
Aspose.Imaging.FileFormats.Tiff.TiffFrame frame2 = new Aspose.Imaging.FileFormats.Tiff.TiffFrame(createOptions2, 200, 200);

// Fill the second frame with the blue-yellow gradient.
// It will be automatically converted to the B/W format due to the corresponding settings of the frame.
Aspose.Imaging.Graphics graphics2 = new Aspose.Imaging.Graphics(frame2);
graphics2.FillRectangle(gradientBrush, frame2.Bounds);

// Create a TIFF image.
using (Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = new Aspose.Imaging.FileFormats.Tiff.TiffImage(
    new Aspose.Imaging.FileFormats.Tiff.TiffFrame[] { frame1, frame2 }))
{
    tiffImage.Save(dir + "output.mutliframe.tif");
}
```

### See Also

* class [TiffOptions](../../../aspose.imaging.imageoptions/tiffoptions/)
* class [TiffFrame](../)
* namespace [Aspose.Imaging.FileFormats.Tiff](../../tiffframe/)
* assembly [Aspose.Imaging](../../../)


