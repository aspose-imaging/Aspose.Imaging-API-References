---
title: Jpeg2000Options.Codec
second_title: Aspose.Imaging for .NET API Reference
description: Jpeg2000Options property. Gets or sets the JPEG2000 codec
type: docs
weight: 20
url: /net/aspose.imaging.imageoptions/jpeg2000options/codec/
---
## Jpeg2000Options.Codec property

Gets or sets the JPEG2000 codec

```csharp
public Jpeg2000Codec Codec { get; set; }
```

### Property Value

The JPEG2000 codec

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

* enum [Jpeg2000Codec](../../../aspose.imaging.fileformats.jpeg2000/jpeg2000codec/)
* class [Jpeg2000Options](../)
* namespace [Aspose.Imaging.ImageOptions](../../jpeg2000options/)
* assembly [Aspose.Imaging](../../../)


