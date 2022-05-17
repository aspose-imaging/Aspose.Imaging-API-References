---
title: SvgImage
second_title: Aspose.Imaging for .NET API Reference
description: 
type: docs
weight: 7540
url: /net/aspose.imaging.fileformats.svg/svgimage/
---
## SvgImage class

Represents SVG image class.

```csharp
public sealed class SvgImage : VectorImage
```

## Constructors

| Name | Description |
| --- | --- |
| [SvgImage](svgimage)(Stream) | Initializes a new instance of the [`SvgImage`](../svgimage) class. |
| [SvgImage](svgimage)(string) | Initializes a new instance of the [`SvgImage`](../svgimage) class. |
| [SvgImage](svgimage)(int, int) | Initializes a new instance of the [`SvgImage`](../svgimage) class. |
| [SvgImage](svgimage)(SvgOptions, int, int) | Initializes a new instance of the [`SvgImage`](../svgimage) class. |

## Properties

| Name | Description |
| --- | --- |
| override [BitsPerPixel](bitsperpixel) { get; } | Gets the image bits per pixel count this parameter is not applicable to vector images |
| override [FileFormat](fileformat) { get; } | Gets a value of file format |
| override [Height](height) { get; } | Gets the image height. |
| override [IsCached](iscached) { get; } | Gets a value indicating whether object's data is cached currently and no data reading is required. |
| override [Width](width) { get; } | Gets the image width. |

## Methods

| Name | Description |
| --- | --- |
| override [CacheData](cachedata)() | Caches the data and ensures no additional data loading will be performed from the underlying [`DataStreamContainer`](../../aspose.imaging/datastreamsupporter/datastreamcontainer). |
| override [GetDefaultOptions](getdefaultoptions)(object[]) | Gets the default options. |
| override [Resize](resize)(int, int, ImageResizeSettings) | Resizes the image. |
| override [Resize](resize)(int, int, ResizeType) | Resizes the image. |
| override [RotateFlip](rotateflip)(RotateFlipType) | Rotates, flips, or rotates and flips the image. |
| override [SetPalette](setpalette)(IColorPalette, bool) | Sets the image palette. |

### Examples

The following example shows how to convert a svgz images to svg fromat

```csharp
[C#]

string file = "example.svgz";
string baseFolder = System.IO.Path.Combine("D:", "Compressed");
string inputFile = System.IO.Path.Combine(baseFolder, file);
string outFile = inputFile + ".svg";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFile))
{
    Aspose.Imaging.ImageOptions.VectorRasterizationOptions vectorRasterizationOptions = new Aspose.Imaging.ImageOptions.SvgRasterizationOptions() { PageSize = image.Size};
    image.Save(outFile, new Aspose.Imaging.ImageOptions.SvgOptions() {VectorRasterizationOptions = vectorRasterizationOptions});
}
```

The following example shows how to convert a svg images to svgz fromat

```csharp
[C#]

string file = "juanmontoya_lingerie.svg";
string baseFolder = System.IO.Path.Combine("D:", "Compressed");
string inputFile = System.IO.Path.Combine(baseFolder, file);
string outFile = inputFile + ".svgz";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFile))
{
    Aspose.Imaging.ImageOptions.VectorRasterizationOptions vectorRasterizationOptions = new Aspose.Imaging.ImageOptions.SvgRasterizationOptions() { PageSize = image.Size};
    image.Save(outFile, new Aspose.Imaging.ImageOptions.SvgOptions() {VectorRasterizationOptions = vectorRasterizationOptions, Compress = true});
}
```

This example shows how to load an SVG image from a file stream and rasterize it to PNG.

```csharp
[C#]

string dir = "c:\\temp\\";

// Load an SVG image from a file stream.
using (System.IO.Stream stream = System.IO.File.OpenRead(dir + "test.svg"))
using (Aspose.Imaging.FileFormats.Svg.SvgImage svgImage = new Aspose.Imaging.FileFormats.Svg.SvgImage(stream))
{
    // In order to rasterize SVG we need to specify rasterization options.
    Aspose.Imaging.ImageOptions.SvgRasterizationOptions rasterizationOptions = new Aspose.Imaging.ImageOptions.SvgRasterizationOptions();
    Aspose.Imaging.ImageOptions.PngOptions saveOptions = new Aspose.Imaging.ImageOptions.PngOptions();
    saveOptions.VectorRasterizationOptions = rasterizationOptions;

    svgImage.Save(dir + "test.output.png", saveOptions);
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

### See Also

* class [VectorImage](../../aspose.imaging/vectorimage)
* namespace [Aspose.Imaging.FileFormats.Svg](../../aspose.imaging.fileformats.svg)
* assembly [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
