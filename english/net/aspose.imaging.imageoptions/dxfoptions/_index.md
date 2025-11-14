---
title: Class DxfOptions
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.ImageOptions.DxfOptions class. API for Drawing Interchange Format DXF vector image creation offers tailored solutions for generating AutoCAD drawing files with precision and flexibility. Designed specifically for working with text lines and Bezier curves developers can efficiently manipulate these elements count Bezier points and convert curves into polylines for seamless exporting ensuring compatibility and fidelity in DXF vector images
type: docs
weight: 10240
url: /net/aspose.imaging.imageoptions/dxfoptions/
---
## DxfOptions class

API for Drawing Interchange Format (DXF) vector image creation offers tailored solutions for generating AutoCAD drawing files with precision and flexibility. Designed specifically for working with text lines and Bezier curves, developers can efficiently manipulate these elements, count Bezier points, and convert curves into polylines for seamless exporting, ensuring compatibility and fidelity in DXF vector images.

```csharp
public class DxfOptions : ImageOptionsBase
```

## Constructors

| Name | Description |
| --- | --- |
| [DxfOptions](dxfoptions/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [BezierPointCount](../../aspose.imaging.imageoptions/dxfoptions/bezierpointcount/) { get; set; } | How many points to generate when converting Bezier curves to polylines, minimum 4. Used when  and  are both /// set to `true` |
| [BufferSizeHint](../../aspose.imaging/imageoptionsbase/buffersizehint/) { get; set; } | Gets or sets the buffer size hint which is defined max allowed size for all internal buffers. |
| [ConvertTextBeziers](../../aspose.imaging.imageoptions/dxfoptions/converttextbeziers/) { get; set; } | Works when  is set to `true`. Wether to convert Bezier curves in text contours to multipoint polylines. |
| [Disposed](../../aspose.imaging/disposableobject/disposed/) { get; } | Gets a value indicating whether this instance is disposed. |
| virtual [ExifData](../../aspose.imaging/imageoptionsbase/exifdata/) { get; set; } | Gets or sets the Exif data. |
| [FullFrame](../../aspose.imaging/imageoptionsbase/fullframe/) { get; set; } | Gets or sets a value indicating whether [full frame]. |
| [KeepMetadata](../../aspose.imaging/imageoptionsbase/keepmetadata/) { get; set; } | Gets a value whether to keep original image metadata on export. |
| [MultiPageOptions](../../aspose.imaging/imageoptionsbase/multipageoptions/) { get; set; } | The multipage options |
| virtual [Palette](../../aspose.imaging/imageoptionsbase/palette/) { get; set; } | Gets or sets the color palette. |
| [ProgressEventHandler](../../aspose.imaging/imageoptionsbase/progresseventhandler/) { get; set; } | Gets or sets the progress event handler. |
| virtual [ResolutionSettings](../../aspose.imaging/imageoptionsbase/resolutionsettings/) { get; set; } | Gets or sets the resolution settings. |
| [Source](../../aspose.imaging/imageoptionsbase/source/) { get; set; } | Gets or sets the source to create image in. |
| [TextAsLines](../../aspose.imaging.imageoptions/dxfoptions/textaslines/) { get; set; } | Whether text should be exported as contours consisting of polylines (default) or as editable Autocad TEXT entities. If this option set |
| [VectorRasterizationOptions](../../aspose.imaging/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | Gets or sets the vector rasterization options. |
| virtual [XmpData](../../aspose.imaging/imageoptionsbase/xmpdata/) { get; set; } | Gets or sets the XMP metadata container. |

## Methods

| Name | Description |
| --- | --- |
| virtual [Clone](../../aspose.imaging/imageoptionsbase/clone/)() | Creates a memberwise clone of this instance. |
| [Dispose](../../aspose.imaging/disposableobject/dispose/)() | Disposes the current instance. |
| [TrySetMetadata](../../aspose.imaging/imageoptionsbase/trysetmetadata/)(IImageMetadataFormat) | Tries to set a *metadata* instance, if this [`Image`](../../aspose.imaging/image/) instance supports and implements [`IImageMetadataFormat`](../../aspose.imaging.metadata/iimagemetadataformat/) instance. |

## Examples

This example demonstrates export to Dxf format

```csharp
[C#]

//Create Image instance and initialize it with an existing image file from disk location
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(@"input.svg"))
{
    Aspose.Imaging.ImageOptions.DxfOptions options = new Aspose.Imaging.ImageOptions.DxfOptions();
    options.TextAsLines = true;
    options.ConvertTextBeziers = true;
    options.BezierPointCount = 20;
    image.Save("output.dxf", options);
}
```

### See Also

* class [ImageOptionsBase](../../aspose.imaging/imageoptionsbase/)
* namespace [Aspose.Imaging.ImageOptions](../../aspose.imaging.imageoptions/)
* assembly [Aspose.Imaging](../../)


