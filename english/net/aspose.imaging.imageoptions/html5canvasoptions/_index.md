---
title: Class Html5CanvasOptions
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.ImageOptions.Html5CanvasOptions class. Create HTML5 Canvas files effortlessly with our API allowing you to seamlessly combine elements like forms text images animations and links. Benefit from robust features including tag identifier and encoding settings support ensuring optimal performance and customization for your web projects
type: docs
weight: 10270
url: /net/aspose.imaging.imageoptions/html5canvasoptions/
---
## Html5CanvasOptions class

Create HTML5 Canvas files effortlessly with our API, allowing you to seamlessly combine elements like forms, text, images, animations, and links. Benefit from robust features including tag identifier and encoding settings support, ensuring optimal performance and customization for your web projects.

```csharp
public class Html5CanvasOptions : ImageOptionsBase
```

## Constructors

| Name | Description |
| --- | --- |
| [Html5CanvasOptions](html5canvasoptions/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [BufferSizeHint](../../aspose.imaging/imageoptionsbase/buffersizehint/) { get; set; } | Gets or sets the buffer size hint which is defined max allowed size for all internal buffers. |
| [CanvasTagId](../../aspose.imaging.imageoptions/html5canvasoptions/canvastagid/) { get; set; } | Gets or sets the canvas tag identifier. |
| [Disposed](../../aspose.imaging/disposableobject/disposed/) { get; } | Gets a value indicating whether this instance is disposed. |
| [Encoding](../../aspose.imaging.imageoptions/html5canvasoptions/encoding/) { get; set; } | Gets or sets the encoding. |
| virtual [ExifData](../../aspose.imaging/imageoptionsbase/exifdata/) { get; set; } | Gets or sets the Exif data. |
| [FullFrame](../../aspose.imaging/imageoptionsbase/fullframe/) { get; set; } | Gets or sets a value indicating whether [full frame]. |
| [FullHtmlPage](../../aspose.imaging.imageoptions/html5canvasoptions/fullhtmlpage/) { get; set; } | Gets or sets a value indicating whether the full HTML page should be generated. |
| [KeepMetadata](../../aspose.imaging/imageoptionsbase/keepmetadata/) { get; set; } | Gets a value whether to keep original image metadata on export. |
| [MultiPageOptions](../../aspose.imaging/imageoptionsbase/multipageoptions/) { get; set; } | The multipage options |
| virtual [Palette](../../aspose.imaging/imageoptionsbase/palette/) { get; set; } | Gets or sets the color palette. |
| [ProgressEventHandler](../../aspose.imaging/imageoptionsbase/progresseventhandler/) { get; set; } | Gets or sets the progress event handler. |
| virtual [ResolutionSettings](../../aspose.imaging/imageoptionsbase/resolutionsettings/) { get; set; } | Gets or sets the resolution settings. |
| [Source](../../aspose.imaging/imageoptionsbase/source/) { get; set; } | Gets or sets the source to create image in. |
| [VectorRasterizationOptions](../../aspose.imaging/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | Gets or sets the vector rasterization options. |
| virtual [XmpData](../../aspose.imaging/imageoptionsbase/xmpdata/) { get; set; } | Gets or sets the XMP metadata container. |

## Methods

| Name | Description |
| --- | --- |
| virtual [Clone](../../aspose.imaging/imageoptionsbase/clone/)() | Creates a memberwise clone of this instance. |
| [Dispose](../../aspose.imaging/disposableobject/dispose/)() | Disposes the current instance. |
| [TrySetMetadata](../../aspose.imaging/imageoptionsbase/trysetmetadata/)(IImageMetadataFormat) | Tries to set a *metadata* instance, if this [`Image`](../../aspose.imaging/image/) instance supports and implements [`IImageMetadataFormat`](../../aspose.imaging.metadata/iimagemetadataformat/) instance. |

## Examples

Any vector image (SVG, WMF, CMX, etc.) can be used as a source for your Canvas images. The following code creates a simple Canvas image.

```csharp
[C#]

using (var image = Image.Load(@"Sample.svg"))
{
    image.Save(@"Canvas.html", new Html5CanvasOptions
    {
        VectorRasterizationOptions = new SvgRasterizationOptions()
    });
}
```

You can embed more than one Canvas image within HTML page or update already exsiting page. In order to do that you need to export only the Canvas tag.

```csharp
[C#]

using (var image = Image.Load(@"Sample.svg"))
{
    image.Save(@"Canvas.html", new Html5CanvasOptions
    {
        VectorRasterizationOptions = new SvgRasterizationOptions(),
        FullHtmlPage = false
    });
}
```

### See Also

* class [ImageOptionsBase](../../aspose.imaging/imageoptionsbase/)
* namespace [Aspose.Imaging.ImageOptions](../../aspose.imaging.imageoptions/)
* assembly [Aspose.Imaging](../../)


