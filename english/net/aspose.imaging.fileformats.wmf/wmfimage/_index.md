---
title: WmfImage
second_title: Aspose.Imaging for .NET API Reference
description: 
type: docs
weight: 9240
url: /net/aspose.imaging.fileformats.wmf/wmfimage/
---
## WmfImage class

The Wmf Image

```csharp
public class WmfImage : MetaImage
```

## Constructors

| Name | Description |
| --- | --- |
| [WmfImage](wmfimage)() | Initializes a new instance of the [`WmfImage`](../wmfimage) class. |
| [WmfImage](wmfimage)(int, int) | Initializes a new instance of the [`WmfImage`](../wmfimage) class. |

## Properties

| Name | Description |
| --- | --- |
| override [BitsPerPixel](bitsperpixel) { get; } | Gets the image bits per pixel count. |
| override [FileFormat](fileformat) { get; } | Gets a value of file format |
| [FrameBounds](framebounds) { get; } | Gets the frame bounds. |
| override [Height](height) { get; } | Gets the image height. |
| [Inch](inch) { get; set; } | Gets or sets the inch. |
| override [IsCached](iscached) { get; } | Gets a value indicating whether object's data is cached currently and no data readig is required. |
| override [Width](width) { get; } | Gets the image width. |

## Methods

| Name | Description |
| --- | --- |
| [AddRecord](addrecord)(WmfObject) | Adds the record. |
| override [CacheData](cachedata)() | Caches the data and ensures no additional data loading will be performed from the underlying [`DataStreamContainer`](../../aspose.imaging/datastreamsupporter/datastreamcontainer). |
| override [Crop](crop)(Rectangle) | Crops the specified rectangle. |
| override [GetDefaultOptions](getdefaultoptions)(object[]) | Gets the default options. |
| [GetPostScript](getpostscript)() | Gets the post script. |
| override [GetUsedFonts](getusedfonts)() | Returns the list of font which used inside metafile. |
| override [Resize](resize)(int, int, ImageResizeSettings) | Resizes the image. |
| override [Resize](resize)(int, int, ResizeType) | Resizes the image. |
| override [ResizeCanvas](resizecanvas)(Rectangle) | Resizes the canvas. |
| override [RotateFlip](rotateflip)(RotateFlipType) | Rotates, flips, or rotates and flips the image. |
| override [SetPalette](setpalette)(IColorPalette, bool) | Sets the image palette. |

### Examples

The following example shows how to convert a wmz images to wmf fromat

```csharp
[C#]

string file = "example.wmz";
string baseFolder = System.IO.Path.Combine("D:", "Compressed");
string inputFile = System.IO.Path.Combine(baseFolder, file);
string outFile = inputFile + ".wmf";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFile))
{
    Aspose.Imaging.ImageOptions.VectorRasterizationOptions vectorRasterizationOptions = new Aspose.Imaging.ImageOptions.WmfRasterizationOptions() { PageSize = image.Size};
    image.Save(outFile, new Aspose.Imaging.ImageOptions.WmfOptions() {VectorRasterizationOptions = vectorRasterizationOptions});
}
```

The following example shows how to convert a wmf images to wmz fromat

```csharp
[C#]

string file = "castle.wmf";
string baseFolder = System.IO.Path.Combine("D:", "Compressed");
string inputFile = System.IO.Path.Combine(baseFolder, file);
string outFile = inputFile + ".wmz";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFile))
{
    Aspose.Imaging.ImageOptions.VectorRasterizationOptions vectorRasterizationOptions = new Aspose.Imaging.ImageOptions.WmfRasterizationOptions() { PageSize = image.Size};
    image.Save(outFile, new Aspose.Imaging.ImageOptions.WmfOptions() {VectorRasterizationOptions = vectorRasterizationOptions, Compress = true});
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

* class [MetaImage](../../aspose.imaging.fileformats.emf/metaimage)
* namespace [Aspose.Imaging.FileFormats.Wmf](../../aspose.imaging.fileformats.wmf)
* assembly [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
