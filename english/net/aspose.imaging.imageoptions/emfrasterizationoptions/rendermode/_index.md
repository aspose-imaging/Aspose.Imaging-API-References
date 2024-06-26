---
title: EmfRasterizationOptions.RenderMode
second_title: Aspose.Imaging for .NET API Reference
description: EmfRasterizationOptions property. Gets or sets the render mode
type: docs
weight: 20
url: /net/aspose.imaging.imageoptions/emfrasterizationoptions/rendermode/
---
## EmfRasterizationOptions.RenderMode property

Gets or sets the render mode.

```csharp
public EmfRenderMode RenderMode { get; set; }
```

### Property Value

The render mode.

## Examples

This example shows how to load a EMF image from a file and convert it to SVG using EmfRasterizationOptions.

```csharp
[C#]

string dir = "c:\\temp\\";

// Using Aspose.Imaging.Image.Load is a unified way to load all types of images including EMF.
using (Aspose.Imaging.FileFormats.Emf.EmfImage emfImage = (Aspose.Imaging.FileFormats.Emf.EmfImage)Aspose.Imaging.Image.Load(dir + "test.emf"))
{
    Aspose.Imaging.ImageOptions.SvgOptions saveOptions = new Aspose.Imaging.ImageOptions.SvgOptions();

    // Text will be converted to shapes.
    saveOptions.TextAsShapes = true;

    Aspose.Imaging.ImageOptions.EmfRasterizationOptions rasterizationOptions = new Aspose.Imaging.ImageOptions.EmfRasterizationOptions();

    // The background color of the drawing surface.
    rasterizationOptions.BackgroundColor = Aspose.Imaging.Color.WhiteSmoke;

    // The page size.
    rasterizationOptions.PageSize = emfImage.Size;

    // If embedded emf exists, then render emf; otherwise render wmf.
    rasterizationOptions.RenderMode = Aspose.Imaging.FileFormats.Emf.EmfRenderMode.Auto;

    // Set the horizontal margin
    rasterizationOptions.BorderX = 50;

    // Set the vertical margin
    rasterizationOptions.BorderY = 50;

    saveOptions.VectorRasterizationOptions = rasterizationOptions;

    emfImage.Save(dir + "test.output.svg", saveOptions);
}
```

### See Also

* enum [EmfRenderMode](../../../aspose.imaging.fileformats.emf/emfrendermode/)
* class [EmfRasterizationOptions](../)
* namespace [Aspose.Imaging.ImageOptions](../../emfrasterizationoptions/)
* assembly [Aspose.Imaging](../../../)


