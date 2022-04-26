---
title: TiffFrame
second_title: Aspose.Imaging for .NET API Reference
description: 
type: docs
weight: 7830
url: /net/aspose.imaging.fileformats.tiff/tiffframe/
---
## TiffFrame class

The tiff frame.

```csharp
public sealed class TiffFrame : RasterCachedImage
```

## Constructors

| Name | Description |
| --- | --- |
| [TiffFrame](tiffframe)(RasterImage) | Initializes a new instance of the [`TiffFrame`](../tiffframe) class. |
| [TiffFrame](tiffframe)(Stream) | Initializes a new instance of the [`TiffFrame`](../tiffframe) class. |
| [TiffFrame](tiffframe)(string) | Initializes a new instance of the [`TiffFrame`](../tiffframe) class. |
| [TiffFrame](tiffframe)(RasterImage, TiffOptions) | Initializes a new instance of the [`TiffFrame`](../tiffframe) class. |
| [TiffFrame](tiffframe)(Stream, TiffOptions) | Initializes a new instance of the [`TiffFrame`](../tiffframe) class. |
| [TiffFrame](tiffframe)(string, TiffOptions) | Initializes a new instance of the [`TiffFrame`](../tiffframe) class. |
| [TiffFrame](tiffframe)(TiffOptions, int, int) | Initializes a new instance of the [`TiffFrame`](../tiffframe) class. |

## Properties

| Name | Description |
| --- | --- |
| override [BackgroundColor](backgroundcolor) { get; set; } | Gets or sets a value for the background color. |
| override [BitsPerPixel](bitsperpixel) { get; } | Gets the image bits per pixel count. |
| [ExifData](exifdata) { get; set; } | Gets or sets EXIF data from frame. |
| [FrameOptions](frameoptions) { get; } | Gets the frame create options. |
| override [HasAlpha](hasalpha) { get; } | Gets a value indicating whether this instance has alpha. |
| override [HasTransparentColor](hastransparentcolor) { get; set; } | Gets a value indicating whether image has transparent color. |
| override [Height](height) { get; } | Gets the image height. |
| override [HorizontalResolution](horizontalresolution) { get; set; } | Gets or sets the horizontal resolution, in pixels per inch, of this [`RasterImage`](../../aspose.imaging/rasterimage). |
| [PathResources](pathresources) { get; set; } | Gets or sets the path resources. |
| override [VerticalResolution](verticalresolution) { get; set; } | Gets or sets the vertical resolution, in pixels per inch, of this [`RasterImage`](../../aspose.imaging/rasterimage). |
| override [Width](width) { get; } | Gets the image width. |
| override [XmpData](xmpdata) { get; set; } | Gets or sets XMP data from frame. |

## Methods

| Name | Description |
| --- | --- |
| static [CopyFrame](copyframe)(TiffFrame) | Copies the entire frame (duplicates). |
| static [CreateFrameFrom](createframefrom)(TiffFrame, TiffOptions) | Creates the frame from specified *tiffFrame* using the specified *options*. The pixel data is preserved but converted to the desired format. |
| [AlignResolutions](alignresolutions)() | Helper method to make horizontal and vertical resolutions equal. |
| override [Crop](crop)(Rectangle) | Cropping the image. |
| override [GetOriginalOptions](getoriginaloptions)() | Gets the options based on the original file settings. This can be helpful to keep bit-depth and other parameters of the original image unchanged. For example, if we load a black-white PNG image with 1 bit per pixel and then save it using the [`Save`](../../aspose.imaging/datastreamsupporter/save) method, the output PNG image with 8-bit per pixel will be produced. To avoid it and save PNG image with 1-bit per pixel, use this method to get corresponding saving options and pass them to the [`Save`](../../aspose.imaging/image/save) method as the second parameter. |
| override [Resize](resize)(int, int, ResizeType) | Resizes the image. |
| override [Rotate](rotate)(float, bool, Color) | Rotate image around the center. |

### Examples

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

* class [RasterCachedImage](../../aspose.imaging/rastercachedimage)
* namespace [Aspose.Imaging.FileFormats.Tiff](../../aspose.imaging.fileformats.tiff)
* assembly [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
