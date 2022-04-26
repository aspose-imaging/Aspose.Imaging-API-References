---
title: EmfImage
second_title: Aspose.Imaging for .NET API Reference
description: 
type: docs
weight: 4630
url: /net/aspose.imaging.fileformats.emf/emfimage/
---
## EmfImage class

EMF file format image.

```csharp
public sealed class EmfImage : MetaImage
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfImage](emfimage)() | Initializes a new instance of the [`EmfImage`](../emfimage) class. |
| [EmfImage](emfimage)(int, int) | Initializes a new instance of the [`EmfImage`](../emfimage) class. |

## Properties

| Name | Description |
| --- | --- |
| override [BitsPerPixel](bitsperpixel) { get; } | Gets the image bits per pixel count this parameter is not applicable to vector images |
| override [FileFormat](fileformat) { get; } | Gets a value of file format |
| [Header](header) { get; set; } | Gets or sets the header record |
| override [Height](height) { get; } | Gets the image height. |
| override [IsCached](iscached) { get; } | Gets a value indicating whether object's data is cached currently and no data reading is required. |
| override [Records](records) { get; set; } | Gets or sets the records. |
| override [Width](width) { get; } | Gets the image width. |

## Methods

| Name | Description |
| --- | --- |
| override [CacheData](cachedata)() | Caches the data and ensures no additional data loading will be performed from the underlying [`DataStreamContainer`](../../aspose.imaging/datastreamsupporter/datastreamcontainer). |
| override [Crop](crop)(Rectangle) | Crops the specified rectangle. |
| override [GetDefaultOptions](getdefaultoptions)(object[]) | Gets the default options. |
| override [GetUsedFonts](getusedfonts)() | Returns the list of font which used inside metafile. |
| override [Resize](resize)(int, int, ImageResizeSettings) | Resizes the image. |
| override [Resize](resize)(int, int, ResizeType) | Resizes the image. |
| override [ResizeCanvas](resizecanvas)(Rectangle) | Resizes the canvas. |
| override [RotateFlip](rotateflip)(RotateFlipType) | Rotates, flips, or rotates and flips the image. |
| override [SetPalette](setpalette)(IColorPalette, bool) | Sets the image palette. |

### Examples

The following example shows how to convert a emz images to emf fromat

```csharp
[C#]

string file = "example.emz";
string baseFolder = System.IO.Path.Combine("D:", "Compressed");
string inputFile = System.IO.Path.Combine(baseFolder, file);
string outFile = inputFile + ".emf";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFile))
{
    Aspose.Imaging.ImageOptions.VectorRasterizationOptions vectorRasterizationOptions = new Aspose.Imaging.ImageOptions.EmfRasterizationOptions {PageSize = image.Size};
    image.Save(outFile, new Aspose.Imaging.ImageOptions.EmfOptions {VectorRasterizationOptions = vectorRasterizationOptions});
}
```

The following example shows how to convert a emf images to emz fromat

```csharp
[C#]

string file = "input.emf";
string baseFolder = System.IO.Path.Combine("D:", "Compressed");
string inputFile = System.IO.Path.Combine(baseFolder, file);
string outFile = inputFile + ".emz";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFile))
{
    Aspose.Imaging.ImageOptions.VectorRasterizationOptions vectorRasterizationOptions = new Aspose.Imaging.ImageOptions.EmfRasterizationOptions() { PageSize = image.Size};
    image.Save(outFile, new Aspose.Imaging.ImageOptions.EmfOptions() {VectorRasterizationOptions = vectorRasterizationOptions, Compress = true});
}
```

The following example shows how to convert a compressed images (*.emz,*.wmz, *.svgz) to raster fromat

```csharp
[C#]

string[] files = new[] {"example.emz", "example.wmz", "example.svgz"};
string baseFolder = System.IO.Path.Combine("D:","Compressed");
foreach (var file in files)
{
    string inputFile = System.IO.Path.Combine(baseFolder, file);
    string outFile = inputFile + ".png";
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFile))
    {
        Aspose.Imaging.ImageOptions.VectorRasterizationOptions vectorRasterizationOptions = (Aspose.Imaging.ImageOptions.VectorRasterizationOptions)image.GetDefaultOptions(new object[] { Color.White, image.Width, image.Height });
        image.Save(outFile, new Aspose.Imaging.ImageOptions.PngOptions(){VectorRasterizationOptions = vectorRasterizationOptions});
    }
}
```

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

* class [MetaImage](../metaimage)
* namespace [Aspose.Imaging.FileFormats.Emf](../../aspose.imaging.fileformats.emf)
* assembly [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
