---
title: TiffFrame.CreateFrameFrom
second_title: Aspose.Imaging for .NET API Reference
description: TiffFrame method. Creates the frame from specified tiffFrame using the specified options. The pixel data is preserved but converted to the desired format
type: docs
weight: 30
url: /net/aspose.imaging.fileformats.tiff/tiffframe/createframefrom/
---
## TiffFrame.CreateFrameFrom method

Creates the frame from specified *tiffFrame* using the specified *options*. The pixel data is preserved but converted to the desired format.

```csharp
public static TiffFrame CreateFrameFrom(TiffFrame tiffFrame, TiffOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| tiffFrame | TiffFrame | The tiff frame to create from. |
| options | TiffOptions | The new options to use. |

### Return Value

The newly created frame.

## Examples

The following example shows how to create a grayscale copy of an existing frame and add it to a TIFF image.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.TiffOptions createTiffOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Aspose.Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

// Create a permanent, not temporary file source.
createTiffOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(dir + "multipage.tif", false);
createTiffOptions.Photometric = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.Rgb;
createTiffOptions.BitsPerSample = new ushort[] { 8, 8, 8 };

using (Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = (Aspose.Imaging.FileFormats.Tiff.TiffImage)Image.Create(createTiffOptions, 100, 100))
{
    // The linear gradient from the left-top to the right-bottom corner of the image.
    Aspose.Imaging.Brushes.LinearGradientBrush brush =
        new Aspose.Imaging.Brushes.LinearGradientBrush(
            new Aspose.Imaging.Point(0, 0),
            new Aspose.Imaging.Point(tiffImage.Width, tiffImage.Height),
            Aspose.Imaging.Color.Red,
            Aspose.Imaging.Color.Green);

    // Fill the active frame with a linear gradient brush.
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(tiffImage.ActiveFrame);
    gr.FillRectangle(brush, tiffImage.Bounds);

    // Grayscale options
    Aspose.Imaging.ImageOptions.TiffOptions createTiffFrameOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Aspose.Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);
    createTiffFrameOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream());
    createTiffFrameOptions.Photometric = Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.MinIsBlack;
    createTiffFrameOptions.BitsPerSample = new ushort[] { 8 };

    // Create a grayscale copy of the active frame.
    // The pixel data is preserved but converted to the desired format.
    Aspose.Imaging.FileFormats.Tiff.TiffFrame grayscaleFrame = Aspose.Imaging.FileFormats.Tiff.TiffFrame.CreateFrameFrom(tiffImage.ActiveFrame, createTiffFrameOptions);

    // Add the newly created frame to the TIFF image.
    tiffImage.AddFrame(grayscaleFrame);

    tiffImage.Save();
}
```

### See Also

* class [TiffOptions](../../../aspose.imaging.imageoptions/tiffoptions/)
* class [TiffFrame](../)
* namespace [Aspose.Imaging.FileFormats.Tiff](../../tiffframe/)
* assembly [Aspose.Imaging](../../../)


