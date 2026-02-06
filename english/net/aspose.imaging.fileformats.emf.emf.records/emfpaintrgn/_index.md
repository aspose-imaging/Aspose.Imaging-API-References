---
title: Class EmfPaintRgn
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfPaintRgn class. The EMR_PAINTRGN record paints the specified region by using the brush currently selected into the playback device context
type: docs
weight: 4010
url: /net/aspose.imaging.fileformats.emf.emf.records/emfpaintrgn/
---
## EmfPaintRgn class

The EMR_PAINTRGN record paints the specified region by using the brush currently selected into the playback device context.

```csharp
public sealed class EmfPaintRgn : EmfDrawingRecordType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfPaintRgn](emfpaintrgn/#constructor)() | Initializes a new instance of the `EmfPaintRgn` class. |
| [EmfPaintRgn](emfpaintrgn/#constructor_1)(EmfRecord) | Initializes a new instance of the `EmfPaintRgn` class. |

## Properties

| Name | Description |
| --- | --- |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.records/emfpaintrgn/bounds/) { get; set; } | Gets or sets a 128-bit WMF RectL object, specified in [MS-WMF] section 2.2.2.19, which specifies the bounding rectangle. |
| [RgnData](../../aspose.imaging.fileformats.emf.emf.records/emfpaintrgn/rgndata/) { get; set; } | Gets or sets a RgnDataSize length array of bytes that specifies a RegionData (section 2.2.24) object, in logical units. |
| [RgnDataSize](../../aspose.imaging.fileformats.emf.emf.records/emfpaintrgn/rgndatasize/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the size of region data, in bytes. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | Gets or sets the size of the record |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | Gets or sets the type. |

### See Also

* class [EmfDrawingRecordType](../emfdrawingrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


