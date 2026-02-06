---
title: Class EmfFrameRgn
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfFrameRgn class. The EMR_FRAMERGN record draws a border around the specified region using the specified brush
type: docs
weight: 3830
url: /net/aspose.imaging.fileformats.emf.emf.records/emfframergn/
---
## EmfFrameRgn class

The EMR_FRAMERGN record draws a border around the specified region using the specified brush.

```csharp
public sealed class EmfFrameRgn : EmfDrawingRecordType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfFrameRgn](emfframergn/#constructor)() | Initializes a new instance of the `EmfFrameRgn` class. |
| [EmfFrameRgn](emfframergn/#constructor_1)(EmfRecord) | Initializes a new instance of the `EmfFrameRgn` class. |

## Properties

| Name | Description |
| --- | --- |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.records/emfframergn/bounds/) { get; set; } | Gets or sets 128-bit WMF RectL object, specified in [MS-WMF] section 2.2.2.19, which specifies the bounding rectangle. |
| [Height](../../aspose.imaging.fileformats.emf.emf.records/emfframergn/height/) { get; set; } | Gets or sets a 32-bit signed integer that specifies the height of the horizontal brush stroke, in logical units. |
| [IhBrush](../../aspose.imaging.fileformats.emf.emf.records/emfframergn/ihbrush/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the brush EMF Object Table index. |
| [RgnData](../../aspose.imaging.fileformats.emf.emf.records/emfframergn/rgndata/) { get; set; } | Gets or sets a RgnDataSize length array of bytes that specifies a RegionData object, in logical units |
| [RgnDataSize](../../aspose.imaging.fileformats.emf.emf.records/emfframergn/rgndatasize/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the size of region data, in bytes. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | Gets or sets the size of the record |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | Gets or sets the type. |
| [Width](../../aspose.imaging.fileformats.emf.emf.records/emfframergn/width/) { get; set; } | Gets or sets a 32-bit signed integer that specifies the width of the vertical brush stroke, in logical units. |

### See Also

* class [EmfDrawingRecordType](../emfdrawingrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


