---
title: OdgImage
second_title: Aspose.Imaging for .NET API Reference
description: 
type: docs
weight: 7380
url: /net/aspose.imaging.fileformats.opendocument/odgimage/
---
## OdgImage class

The Open Document Graphic

```csharp
public class OdgImage : OdImage
```

## Constructors

| Name | Description |
| --- | --- |
| [OdgImage](odgimage)(StreamContainer) | Initializes a new instance of the [`OdgImage`](../odgimage) class. |

## Properties

| Name | Description |
| --- | --- |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette) { get; set; } | Gets or sets a value indicating whether automatic adjust palette. |
| virtual [BackgroundColor](../../aspose.imaging/image/backgroundcolor) { get; set; } | Gets or sets a value for the background color. |
| override [BitsPerPixel](../../aspose.imaging.fileformats.opendocument/odimage/bitsperpixel) { get; } | Gets the image bits per pixel count. |
| [Bounds](../../aspose.imaging/image/bounds) { get; } | Gets the image bounds. |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint) { get; set; } | Gets or sets the buffer size hint which is defined max allowed size for all internal buffers. |
| [Container](../../aspose.imaging/image/container) { get; } | Gets the [`Image`](../../aspose.imaging/image) container. |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer) { get; } | Gets the object's data stream. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Gets a value indicating whether this instance is disposed. |
| override [FileFormat](../../aspose.imaging.fileformats.opendocument/odgimage/fileformat) { get; } | Gets a value of file format |
| virtual [HasBackgroundColor](../../aspose.imaging/image/hasbackgroundcolor) { get; set; } | Gets or sets a value indicating whether image has background color. |
| override [Height](../../aspose.imaging.fileformats.opendocument/odimage/height) { get; } | Gets the image height. |
| virtual [HeightF](../../aspose.imaging/vectorimage/heightf) { get; } | Gets the object height, in inches. |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor) { get; set; } | Gets or sets the interrupt monitor. |
| override [IsCached](../../aspose.imaging.fileformats.opendocument/odimage/iscached) { get; } | Gets a value indicating whether object's data is cached currently and no data reading is required. |
| [Metadata](../../aspose.imaging.fileformats.opendocument/odimage/metadata) { get; } | Gets the metadata. |
| override [PageCount](../../aspose.imaging.fileformats.opendocument/odimage/pagecount) { get; } | Gets the page count. |
| override [PageExportingAction](../../aspose.imaging.fileformats.opendocument/odgimage/pageexportingaction) { get; set; } | Gets or sets the page exporting action. Please note that setting this method will automatically release page resources after it is executed. It will be executed just before each page is saved. |
| override [Pages](../../aspose.imaging.fileformats.opendocument/odgimage/pages) { get; } | Gets the pages. |
| [Palette](../../aspose.imaging/image/palette) { get; set; } | Gets or sets the color palette. The color palette is not used when pixels are represented directly. |
| [Records](../../aspose.imaging.fileformats.opendocument/odimage/records) { get; } | Gets the records. |
| [Size](../../aspose.imaging/image/size) { get; } | Gets the image size. |
| [SizeF](../../aspose.imaging/vectorimage/sizef) { get; } | Gets the object size, in inches. |
| virtual [UsePalette](../../aspose.imaging/image/usepalette) { get; } | Gets a value indicating whether the image palette is used. |
| override [Width](../../aspose.imaging.fileformats.opendocument/odimage/width) { get; } | Gets the image width. |
| virtual [WidthF](../../aspose.imaging/vectorimage/widthf) { get; } | Gets the object width, in inches. |

## Methods

| Name | Description |
| --- | --- |
| override [CacheData](../../aspose.imaging/vectormultipageimage/cachedata)() | Caches the data and ensures no additional data loading will be performed from the underlying [`DataStreamContainer`](../../aspose.imaging/datastreamsupporter/datastreamcontainer). |
| [CanSave](../../aspose.imaging/image/cansave)(ImageOptionsBase) | Determines whether image can be saved to the specified file format represented by the passed save options. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Disposes the current instance. |
| override [GetDefaultOptions](../../aspose.imaging.fileformats.opendocument/odgimage/getdefaultoptions)(object[]) | Gets the default options. |
| override [GetEmbeddedImages](../../aspose.imaging/vectormultipageimage/getembeddedimages)() | Gets the embedded images. |
| virtual [GetOriginalOptions](../../aspose.imaging/image/getoriginaloptions)() | Gets the options based on the original file settings. This can be helpful to keep bit-depth and other parameters of the original image unchanged. For example, if we load a black-white PNG image with 1 bit per pixel and then save it using the [`Save`](../../aspose.imaging/datastreamsupporter/save) method, the output PNG image with 8-bit per pixel will be produced. To avoid it and save PNG image with 1-bit per pixel, use this method to get corresponding saving options and pass them to the [`Save`](../../aspose.imaging/image/save) method as the second parameter. |
| [Resize](../../aspose.imaging/image/resize)(int, int) | Resizes the image. The default NearestNeighbourResample is used. |
| override [Resize](../../aspose.imaging.fileformats.opendocument/odgimage/resize)(int, int, ImageResizeSettings) | Resizes the image. |
| override [Resize](../../aspose.imaging.fileformats.opendocument/odgimage/resize)(int, int, ResizeType) | Resizes the image. |
| [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int) | Resizes the height proportionally. The default NearestNeighbourResample is used. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int, ImageResizeSettings) | Resizes the height proportionally. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int, ResizeType) | Resizes the height proportionally. |
| [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int) | Resizes the width proportionally. The default NearestNeighbourResample is used. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int, ImageResizeSettings) | Resizes the width proportionally. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int, ResizeType) | Resizes the width proportionally. |
| override [RotateFlip](../../aspose.imaging.fileformats.opendocument/odgimage/rotateflip)(RotateFlipType) | Rotates, flips, or rotates and flips the image. |
| [Save](../../aspose.imaging/image/save)() | Saves the image data to the underlying stream. |
| [Save](../../aspose.imaging/datastreamsupporter/save)(Stream) | Saves the object's data to the specified stream. |
| override [Save](../../aspose.imaging/image/save)(string) | Saves the image to the specified file location. |
| [Save](../../aspose.imaging/image/save)(Stream, ImageOptionsBase) | Saves the image's data to the specified stream in the specified file format according to save options. |
| virtual [Save](../../aspose.imaging/datastreamsupporter/save)(string, bool) | Saves the object's data to the specified file location. |
| virtual [Save](../../aspose.imaging/image/save)(string, ImageOptionsBase) | Saves the object's data to the specified file location in the specified file format according to save options. |
| virtual [Save](../../aspose.imaging/image/save)(Stream, ImageOptionsBase, Rectangle) | Saves the image's data to the specified stream in the specified file format according to save options. |
| virtual [Save](../../aspose.imaging/image/save)(string, ImageOptionsBase, Rectangle) | Saves the object's data to the specified file location in the specified file format according to save options. |
| override [SetPalette](../../aspose.imaging/vectormultipageimage/setpalette)(IColorPalette, bool) | Sets the image palette. |

### Examples

This example loads a multi-page ODG image.

```csharp
[C#]

string dir = "c:\\temp\\";

// Using Aspose.Imaging.Image.Load is a unified way to load image.
using (Aspose.Imaging.FileFormats.OpenDocument.OdImage image = (Aspose.Imaging.FileFormats.OpenDocument.OdImage)Aspose.Imaging.Image.Load(dir + "sample.odg"))
{
    // Cast to OdgImage
    Aspose.Imaging.FileFormats.OpenDocument.OdgImage odgImage = (Aspose.Imaging.FileFormats.OpenDocument.OdgImage)image;

    // Get all pages
    Aspose.Imaging.Image[] pages = odgImage.Pages;

    // Do some image processing
}
```

The following example shows how to export a FODG (Flat XML ODF Template) image to PDF format.

```csharp
[C#]

string dir = "c:\\aspose.imaging\\issues\\net\\3635";

string inputFileName = System.IO.Path.Combine(dir, "VariousObjectsMultiPage.fodg");
string outputFileName = inputFileName + ".pdf";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFileName))
{
    Aspose.Imaging.ImageOptions.OdgRasterizationOptions rasterizationOptions = new Aspose.Imaging.ImageOptions.OdgRasterizationOptions();
    rasterizationOptions.BackgroundColor = Aspose.Imaging.Color.White;
    rasterizationOptions.PageSize = image.Size;

    Aspose.Imaging.ImageOptions.PdfOptions saveOptions = new Aspose.Imaging.ImageOptions.PdfOptions();
    saveOptions.VectorRasterizationOptions = rasterizationOptions;

    image.Save(outputFileName, saveOptions);
}
```

### See Also

* class [OdImage](../odimage)
* namespace [Aspose.Imaging.FileFormats.OpenDocument](../../aspose.imaging.fileformats.opendocument)
* assembly [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
