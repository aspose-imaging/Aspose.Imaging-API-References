---
title: EpsImage
second_title: Aspose.Imaging for .NET API Reference
description: 
type: docs
weight: 6560
url: /net/aspose.imaging.fileformats.eps/epsimage/
---
## EpsImage class

The EPS image class.

```csharp
public sealed class EpsImage : VectorImage
```

## Properties

| Name | Description |
| --- | --- |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette) { get; set; } | Gets or sets a value indicating whether automatic adjust palette. |
| virtual [BackgroundColor](../../aspose.imaging/image/backgroundcolor) { get; set; } | Gets or sets a value for the background color. |
| override [BitsPerPixel](../../aspose.imaging.fileformats.eps/epsimage/bitsperpixel) { get; } | Gets the image bits per pixel count. |
| [BoundingBox](../../aspose.imaging.fileformats.eps/epsimage/boundingbox) { get; } | Gets the original bounding box of this [`EpsImage`](../epsimage) instance in device independent points. |
| [BoundingBoxPx](../../aspose.imaging.fileformats.eps/epsimage/boundingboxpx) { get; } | Gets the original bounding box of this [`EpsImage`](../epsimage) instance in pixels. |
| [Bounds](../../aspose.imaging/image/bounds) { get; } | Gets the image bounds. |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint) { get; set; } | Gets or sets the buffer size hint which is defined max allowed size for all internal buffers. |
| [Container](../../aspose.imaging/image/container) { get; } | Gets the [`Image`](../../aspose.imaging/image) container. |
| [CreationDate](../../aspose.imaging.fileformats.eps/epsimage/creationdate) { get; } | Gets the creation date from the EPS DSC comments. |
| [Creator](../../aspose.imaging.fileformats.eps/epsimage/creator) { get; } | Gets the creator from the EPS DSC comments. |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer) { get; } | Gets the object's data stream. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Gets a value indicating whether this instance is disposed. |
| [EpsType](../../aspose.imaging.fileformats.eps/epsimage/epstype) { get; } | Gets EPS subtype value. |
| override [FileFormat](../../aspose.imaging.fileformats.eps/epsimage/fileformat) { get; } | Gets the file format. |
| virtual [HasBackgroundColor](../../aspose.imaging/image/hasbackgroundcolor) { get; set; } | Gets or sets a value indicating whether image has background color. |
| [HasRasterPreview](../../aspose.imaging.fileformats.eps/epsimage/hasrasterpreview) { get; } | Gets the value indicating whether this [`EpsImage`](../epsimage) instane has a raster preview. |
| override [Height](../../aspose.imaging.fileformats.eps/epsimage/height) { get; } | Gets the image height. |
| virtual [HeightF](../../aspose.imaging/vectorimage/heightf) { get; } | Gets the object height, in inches. |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor) { get; set; } | Gets or sets the interrupt monitor. |
| override [IsCached](../../aspose.imaging.fileformats.eps/epsimage/iscached) { get; } | Gets a value indicating whether object's data is cached currently and no data reading is required. |
| [Palette](../../aspose.imaging/image/palette) { get; set; } | Gets or sets the color palette. The color palette is not used when pixels are represented directly. |
| [PostScriptVersion](../../aspose.imaging.fileformats.eps/epsimage/postscriptversion) { get; } | Gets the PostScript version. |
| [PreviewImageCount](../../aspose.imaging.fileformats.eps/epsimage/previewimagecount) { get; } | Gets the preview image count. |
| [PreviewImages](../../aspose.imaging.fileformats.eps/epsimage/previewimages) { get; } | Gets the preview images. |
| [Size](../../aspose.imaging/image/size) { get; } | Gets the image size. |
| [SizeF](../../aspose.imaging/vectorimage/sizef) { get; } | Gets the object size, in inches. |
| [Title](../../aspose.imaging.fileformats.eps/epsimage/title) { get; } | Gets the title from the EPS DSC comments. |
| virtual [UsePalette](../../aspose.imaging/image/usepalette) { get; } | Gets a value indicating whether the image palette is used. |
| override [Width](../../aspose.imaging.fileformats.eps/epsimage/width) { get; } | Gets the image width. |
| virtual [WidthF](../../aspose.imaging/vectorimage/widthf) { get; } | Gets the object width, in inches. |

## Methods

| Name | Description |
| --- | --- |
| override [CacheData](../../aspose.imaging.fileformats.eps/epsimage/cachedata)() | Does nothing since currently [`EpsImage`](../epsimage) class does not cache data. |
| [CanSave](../../aspose.imaging/image/cansave)(ImageOptionsBase) | Determines whether image can be saved to the specified file format represented by the passed save options. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Disposes the current instance. |
| override [GetDefaultOptions](../../aspose.imaging.fileformats.eps/epsimage/getdefaultoptions)(object[]) | Gets the default options. |
| virtual [GetEmbeddedImages](../../aspose.imaging/vectorimage/getembeddedimages)() | Gets the embedded images. |
| virtual [GetOriginalOptions](../../aspose.imaging/image/getoriginaloptions)() | Gets the options based on the original file settings. This can be helpful to keep bit-depth and other parameters of the original image unchanged. For example, if we load a black-white PNG image with 1 bit per pixel and then save it using the [`Save`](../../aspose.imaging/datastreamsupporter/save) method, the output PNG image with 8-bit per pixel will be produced. To avoid it and save PNG image with 1-bit per pixel, use this method to get corresponding saving options and pass them to the [`Save`](../../aspose.imaging/image/save) method as the second parameter. |
| [GetPreviewImage](../../aspose.imaging.fileformats.eps/epsimage/getpreviewimage)(EpsPreviewFormat) | Gets the exisiting preview image of specified *format* or returns `null`. |
| [GetPreviewImages](../../aspose.imaging.fileformats.eps/epsimage/getpreviewimages)() | Gets the preview images. |
| [Resize](../../aspose.imaging/image/resize)(int, int) | Resizes the image. The default NearestNeighbourResample is used. |
| override [Resize](../../aspose.imaging.fileformats.eps/epsimage/resize)(int, int, ImageResizeSettings) | Resizes the image. |
| override [Resize](../../aspose.imaging.fileformats.eps/epsimage/resize)(int, int, ResizeType) | Resizes the image. |
| [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int) | Resizes the height proportionally. The default NearestNeighbourResample is used. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int, ImageResizeSettings) | Resizes the height proportionally. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int, ResizeType) | Resizes the height proportionally. |
| [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int) | Resizes the width proportionally. The default NearestNeighbourResample is used. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int, ImageResizeSettings) | Resizes the width proportionally. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int, ResizeType) | Resizes the width proportionally. |
| override [RotateFlip](../../aspose.imaging.fileformats.eps/epsimage/rotateflip)(RotateFlipType) | Rotates, flips, or rotates and flips the image. |
| [Save](../../aspose.imaging/image/save)() | Saves the image data to the underlying stream. |
| [Save](../../aspose.imaging/datastreamsupporter/save)(Stream) | Saves the object's data to the specified stream. |
| override [Save](../../aspose.imaging/image/save)(string) | Saves the image to the specified file location. |
| [Save](../../aspose.imaging/image/save)(Stream, ImageOptionsBase) | Saves the image's data to the specified stream in the specified file format according to save options. |
| virtual [Save](../../aspose.imaging/datastreamsupporter/save)(string, bool) | Saves the object's data to the specified file location. |
| virtual [Save](../../aspose.imaging/image/save)(string, ImageOptionsBase) | Saves the object's data to the specified file location in the specified file format according to save options. |
| virtual [Save](../../aspose.imaging/image/save)(Stream, ImageOptionsBase, Rectangle) | Saves the image's data to the specified stream in the specified file format according to save options. |
| virtual [Save](../../aspose.imaging/image/save)(string, ImageOptionsBase, Rectangle) | Saves the object's data to the specified file location in the specified file format according to save options. |
| override [SetPalette](../../aspose.imaging.fileformats.eps/epsimage/setpalette)(IColorPalette, bool) | Sets the image palette. |

### Examples

Resize EPS image and export it to PNG format.

```csharp
[C#]

// Load EPS image
using (var image = Image.Load("AstrixObelix.eps"))
{
    // Resize the image using the Mitchell cubic interpolation method
    image.Resize(400, 400, ResizeType.Mitchell);

    // Export image to PNG format
    image.Save("ExportResult.png", new PngOptions());
}
```

Convert EPS image to PDF using PostScript rendering.

```csharp
[C#]

using (var image = (EpsImage)Image.Load("Sample.eps"))
{
    var options = new PdfOptions
    {
        PdfCoreOptions = new PdfCoreOptions
        {
            PdfCompliance = PdfComplianceVersion.PdfA1b // Set required PDF compliance
        }
    };
  
    image.Save("Sample.pdf", options);
}
```

Convert EPS image to PNG using PostScript rendering.

```csharp
[C#]

using (var image = (EpsImage)Image.Load("Sample.eps"))
{
    var options = new PngOptions
    {
        VectorRasterizationOptions = new EpsRasterizationOptions
        {
            PageWidth = 500, // Image width
            PageHeight = 500 // Image height
            PreviewToExport = EpsPreviewFormat.PostScriptRendering; // Render raster image using the PostScript
        }
    };

    image.Save("Sample.png", options);
}
```

Resize EPS image using advanced settings.

```csharp
[C#]

// Load EPS image
using (var image = Image.Load("AstrixObelix.eps"))
{
    // Resize the image using advanced resize settings
    image.Resize(400, 400, new ImageResizeSettings
    {
        // Set the interpolation mode
        Mode = ResizeType.LanczosResample,

        // Set the type of the filter
        FilterType = ImageFilterType.SmallRectangular,

        // Sets the color compare method
        ColorCompareMethod = ColorCompareMethod.Euclidian,

        // Set the color quantization method
        ColorQuantizationMethod = ColorQuantizationMethod.Popularity
    });

    // Export image to PNG format
    image.Save("ExportResult.png", new PngOptions());
}
```

### See Also

* class [VectorImage](../../aspose.imaging/vectorimage)
* namespace [Aspose.Imaging.FileFormats.Eps](../../aspose.imaging.fileformats.eps)
* assembly [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
