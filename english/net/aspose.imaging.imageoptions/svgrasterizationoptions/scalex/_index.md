---
title: SvgRasterizationOptions.ScaleX
second_title: Aspose.Imaging for .NET API Reference
description: SvgRasterizationOptions property. Gets or sets the scale x
type: docs
weight: 20
url: /net/aspose.imaging.imageoptions/svgrasterizationoptions/scalex/
---
## SvgRasterizationOptions.ScaleX property

Gets or sets the scale x.

```csharp
public float ScaleX { get; set; }
```

### Property Value

The scale x.

## Examples

This example shows how to load an SVG image from a file and rasterize it to PNG using various options.

```csharp
[C#]

string dir = "c:\\temp\\";

// Using Aspose.Imaging.Image.Load is a unified way to load image.
using (Aspose.Imaging.FileFormats.Svg.SvgImage svgImage = (Aspose.Imaging.FileFormats.Svg.SvgImage)Aspose.Imaging.Image.Load(dir + "test.svg"))
{
    // In order to rasterize SVG we need to specify rasterization options.
    Aspose.Imaging.ImageOptions.SvgRasterizationOptions rasterizationOptions = new Aspose.Imaging.ImageOptions.SvgRasterizationOptions();

    // Set default color of a background for an image. Default value is white.
    rasterizationOptions.BackgroundColor = Aspose.Imaging.Color.Gray;

    // Set the page size
    rasterizationOptions.PageSize = svgImage.Size;

    // Antialiasing is applied to lines and curves and the edges of filled areas.
    rasterizationOptions.SmoothingMode = Aspose.Imaging.SmoothingMode.AntiAlias;

    // Each character is drawn using its antialiased glyph bitmap without hinting.
    rasterizationOptions.TextRenderingHint = Aspose.Imaging.TextRenderingHint.AntiAlias;

    // Reduce the image size 10 times, i.e. the output size will be 10% of the original size.
    rasterizationOptions.ScaleX = 0.1f;
    rasterizationOptions.ScaleY = 0.1f;

    Aspose.Imaging.ImageOptions.PngOptions saveOptions = new Aspose.Imaging.ImageOptions.PngOptions();
    saveOptions.VectorRasterizationOptions = rasterizationOptions;

    // Save to a PNG file
    svgImage.Save(dir + "test.output.png", saveOptions);
}
```

### See Also

* class [SvgRasterizationOptions](../)
* namespace [Aspose.Imaging.ImageOptions](../../svgrasterizationoptions/)
* assembly [Aspose.Imaging](../../../)


