---
title: TiffImage.TiffImage
second_title: Aspose.Imaging for .NET API Reference
description: TiffImage constructor. Initialize a new object of the TiffImage class specifying the frame parameter. This constructor facilitates the creation of a TiffImage instance allowing developers to specify the frame to be loaded or processed streamlining Tiff image handling tasks within their applications
type: docs
weight: 10
url: /net/aspose.imaging.fileformats.tiff/tiffimage/tiffimage/
---
## TiffImage(TiffFrame) {#constructor}

Initialize a new object of the [`TiffImage`](../) class, specifying the frame parameter. This constructor facilitates the creation of a TiffImage instance, allowing developers to specify the frame to be loaded or processed, streamlining Tiff image handling tasks within their applications.

```csharp
public TiffImage(TiffFrame frame)
```

| Parameter | Type | Description |
| --- | --- | --- |
| frame | TiffFrame | The tiff frame to initialize image with. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Tiff *frame* cannot be empty. |

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

### See Also

* class [TiffFrame](../../tiffframe/)
* class [TiffImage](../)
* namespace [Aspose.Imaging.FileFormats.Tiff](../../tiffimage/)
* assembly [Aspose.Imaging](../../../)

---

## TiffImage(TiffFrame[]) {#constructor_1}

Create a new instance of the [`TiffImage`](../) class, providing a list of frames as a parameter. This constructor enables the initialization of a TiffImage object with multiple frames, facilitating efficient handling and processing of TIFF image sequences within software applications.

```csharp
public TiffImage(TiffFrame[] frames)
```

| Parameter | Type | Description |
| --- | --- | --- |
| frames | TiffFrame[] | The frames. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | frames |

## Examples

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

* class [TiffFrame](../../tiffframe/)
* class [TiffImage](../)
* namespace [Aspose.Imaging.FileFormats.Tiff](../../tiffimage/)
* assembly [Aspose.Imaging](../../../)


