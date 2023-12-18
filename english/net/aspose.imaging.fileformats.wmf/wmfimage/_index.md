---
title: WmfImage
second_title: Aspose.Imaging for .NET API Reference
description: 
type: docs
weight: 9350
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
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette) { get; set; } | Gets or sets a value indicating whether automatic adjust palette. |
| virtual [BackgroundColor](../../aspose.imaging/image/backgroundcolor) { get; set; } | Gets or sets a value for the background color. |
| override [BitsPerPixel](../../aspose.imaging.fileformats.wmf/wmfimage/bitsperpixel) { get; } | Gets the image bits per pixel count. |
| [Bounds](../../aspose.imaging/image/bounds) { get; } | Gets the image bounds. |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint) { get; set; } | Gets or sets the buffer size hint which is defined max allowed size for all internal buffers. |
| [Container](../../aspose.imaging/image/container) { get; } | Gets the [`Image`](../../aspose.imaging/image) container. |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer) { get; } | Gets the object's data stream. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Gets a value indicating whether this instance is disposed. |
| override [FileFormat](../../aspose.imaging.fileformats.wmf/wmfimage/fileformat) { get; } | Gets a value of file format |
| [FrameBounds](../../aspose.imaging.fileformats.wmf/wmfimage/framebounds) { get; } | Gets the frame bounds. |
| virtual [HasBackgroundColor](../../aspose.imaging/image/hasbackgroundcolor) { get; set; } | Gets or sets a value indicating whether image has background color. |
| override [Height](../../aspose.imaging.fileformats.wmf/wmfimage/height) { get; } | Gets the image height. |
| virtual [HeightF](../../aspose.imaging/vectorimage/heightf) { get; } | Gets the object height, in inches. |
| [Inch](../../aspose.imaging.fileformats.wmf/wmfimage/inch) { get; set; } | Gets or sets the inch. |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor) { get; set; } | Gets or sets the interrupt monitor. |
| override [IsCached](../../aspose.imaging.fileformats.wmf/wmfimage/iscached) { get; } | Gets a value indicating whether object's data is cached currently and no data readig is required. |
| [Palette](../../aspose.imaging/image/palette) { get; set; } | Gets or sets the color palette. The color palette is not used when pixels are represented directly. |
| virtual [Records](../../aspose.imaging.fileformats.emf/metaimage/records) { get; set; } | Gets or sets the records. |
| [Size](../../aspose.imaging/image/size) { get; } | Gets the image size. |
| [SizeF](../../aspose.imaging/vectorimage/sizef) { get; } | Gets the object size, in inches. |
| virtual [UsePalette](../../aspose.imaging/image/usepalette) { get; } | Gets a value indicating whether the image palette is used. |
| override [Width](../../aspose.imaging.fileformats.wmf/wmfimage/width) { get; } | Gets the image width. |
| virtual [WidthF](../../aspose.imaging/vectorimage/widthf) { get; } | Gets the object width, in inches. |

## Methods

| Name | Description |
| --- | --- |
| [AddRecord](../../aspose.imaging.fileformats.wmf/wmfimage/addrecord)(WmfObject) | Adds the record. |
| override [CacheData](../../aspose.imaging.fileformats.wmf/wmfimage/cachedata)() | Caches the data and ensures no additional data loading will be performed from the underlying [`DataStreamContainer`](../../aspose.imaging/datastreamsupporter/datastreamcontainer). |
| [CanSave](../../aspose.imaging/image/cansave)(ImageOptionsBase) | Determines whether image can be saved to the specified file format represented by the passed save options. |
| override [Crop](../../aspose.imaging.fileformats.wmf/wmfimage/crop)(Rectangle) | Crops the specified rectangle. |
| virtual [Crop](../../aspose.imaging.fileformats.emf/metaimage/crop)(int, int, int, int) | Crop image with shifts. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Disposes the current instance. |
| override [GetDefaultOptions](../../aspose.imaging.fileformats.wmf/wmfimage/getdefaultoptions)(object[]) | Gets the default options. |
| virtual [GetEmbeddedImages](../../aspose.imaging/vectorimage/getembeddedimages)() | Gets the embedded images. |
| [GetMissedFonts](../../aspose.imaging.fileformats.emf/metaimage/getmissedfonts)() | Returns the list of fonts which used inside metafile but not found. |
| virtual [GetOriginalOptions](../../aspose.imaging/image/getoriginaloptions)() | Gets the options based on the original file settings. This can be helpful to keep bit-depth and other parameters of the original image unchanged. For example, if we load a black-white PNG image with 1 bit per pixel and then save it using the [`Save`](../../aspose.imaging/datastreamsupporter/save) method, the output PNG image with 8-bit per pixel will be produced. To avoid it and save PNG image with 1-bit per pixel, use this method to get corresponding saving options and pass them to the [`Save`](../../aspose.imaging/image/save) method as the second parameter. |
| [GetPostScript](../../aspose.imaging.fileformats.wmf/wmfimage/getpostscript)() | Gets the post script. |
| override [GetUsedFonts](../../aspose.imaging.fileformats.wmf/wmfimage/getusedfonts)() | Returns the list of font which used inside metafile. |
| [RemoveBackground](../../aspose.imaging/vectorimage/removebackground)() | Removes the background. |
| [RemoveBackground](../../aspose.imaging/vectorimage/removebackground)(RemoveBackgroundSettings) | Removes the background. |
| [Resize](../../aspose.imaging/image/resize)(int, int) | Resizes the image. The default NearestNeighbourResample is used. |
| override [Resize](../../aspose.imaging.fileformats.wmf/wmfimage/resize)(int, int, ImageResizeSettings) | Resizes the image. |
| override [Resize](../../aspose.imaging.fileformats.wmf/wmfimage/resize)(int, int, ResizeType) | Resizes the image. |
| override [ResizeCanvas](../../aspose.imaging.fileformats.wmf/wmfimage/resizecanvas)(Rectangle) | Resizes the canvas. |
| [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int) | Resizes the height proportionally. The default NearestNeighbourResample is used. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int, ImageResizeSettings) | Resizes the height proportionally. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int, ResizeType) | Resizes the height proportionally. |
| [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int) | Resizes the width proportionally. The default NearestNeighbourResample is used. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int, ImageResizeSettings) | Resizes the width proportionally. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int, ResizeType) | Resizes the width proportionally. |
| override [RotateFlip](../../aspose.imaging.fileformats.wmf/wmfimage/rotateflip)(RotateFlipType) | Rotates, flips, or rotates and flips the image. |
| [Save](../../aspose.imaging/image/save)() | Saves the image data to the underlying stream. |
| [Save](../../aspose.imaging/datastreamsupporter/save)(Stream) | Saves the object's data to the specified stream. |
| override [Save](../../aspose.imaging/image/save)(string) | Saves the image to the specified file location. |
| [Save](../../aspose.imaging/image/save)(Stream, ImageOptionsBase) | Saves the image's data to the specified stream in the specified file format according to save options. |
| virtual [Save](../../aspose.imaging/datastreamsupporter/save)(string, bool) | Saves the object's data to the specified file location. |
| virtual [Save](../../aspose.imaging/image/save)(string, ImageOptionsBase) | Saves the object's data to the specified file location in the specified file format according to save options. |
| virtual [Save](../../aspose.imaging/image/save)(Stream, ImageOptionsBase, Rectangle) | Saves the image's data to the specified stream in the specified file format according to save options. |
| virtual [Save](../../aspose.imaging/image/save)(string, ImageOptionsBase, Rectangle) | Saves the object's data to the specified file location in the specified file format according to save options. |
| override [SetPalette](../../aspose.imaging.fileformats.wmf/wmfimage/setpalette)(IColorPalette, bool) | Sets the image palette. |

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
