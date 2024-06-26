---
title: WmfRasterizationOptions.RenderMode
second_title: Aspose.Imaging for .NET API Reference
description: WmfRasterizationOptions property. Gets or sets the WMF render mode
type: docs
weight: 20
url: /net/aspose.imaging.imageoptions/wmfrasterizationoptions/rendermode/
---
## WmfRasterizationOptions.RenderMode property

Gets or sets the WMF render mode.

```csharp
public WmfRenderMode RenderMode { get; set; }
```

### Property Value

The WMF render mode.

## Examples

This example shows how to load a WMF image from a file and convert it to SVG using WmfRasterizationOptions.

```csharp
[C#]

string dir = "c:\\temp\\";

// Using Aspose.Imaging.Image.Load is a unified way to load all types of images including WMF.
using (Aspose.Imaging.FileFormats.Wmf.WmfImage wmfImage = (Aspose.Imaging.FileFormats.Wmf.WmfImage)Aspose.Imaging.Image.Load(dir + "test.wmf"))
{
    Aspose.Imaging.ImageOptions.SvgOptions saveOptions = new Aspose.Imaging.ImageOptions.SvgOptions();
        
    // Text will be converted to shapes.
    saveOptions.TextAsShapes = true;

    Aspose.Imaging.ImageOptions.WmfRasterizationOptions rasterizationOptions = new Aspose.Imaging.ImageOptions.WmfRasterizationOptions();

    // The background color of the drawing surface.
    rasterizationOptions.BackgroundColor = Aspose.Imaging.Color.WhiteSmoke;

    // The page size.
    rasterizationOptions.PageSize = wmfImage.Size;

    // If embedded emf exists, then render emf; otherwise render wmf.
    rasterizationOptions.RenderMode = Aspose.Imaging.FileFormats.Wmf.WmfRenderMode.Auto;

    saveOptions.VectorRasterizationOptions = rasterizationOptions;

    wmfImage.Save(dir + "test.output.svg", saveOptions);
}
```

### See Also

* enum [WmfRenderMode](../../../aspose.imaging.fileformats.wmf/wmfrendermode/)
* class [WmfRasterizationOptions](../)
* namespace [Aspose.Imaging.ImageOptions](../../wmfrasterizationoptions/)
* assembly [Aspose.Imaging](../../../)


