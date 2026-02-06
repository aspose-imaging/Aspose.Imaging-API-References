---
title: Class EmfFillRgn
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfFillRgn class. The EMR_FILLRGN record fills the specified region by using the specified brush
type: docs
weight: 3800
url: /net/aspose.imaging.fileformats.emf.emf.records/emffillrgn/
---
## EmfFillRgn class

The EMR_FILLRGN record fills the specified region by using the specified brush.

```csharp
public sealed class EmfFillRgn : EmfDrawingRecordType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfFillRgn](emffillrgn/#constructor)() | Initializes a new instance of the `EmfFillRgn` class. |
| [EmfFillRgn](emffillrgn/#constructor_1)(EmfRecord) | Initializes a new instance of the `EmfFillRgn` class. |

## Properties

| Name | Description |
| --- | --- |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.records/emffillrgn/bounds/) { get; set; } | Gets or sets a 128-bit WMF RectL object, specified in [MS-WMF] section 2.2.2.19, which specifies the bounding rectangle. |
| [IhBrush](../../aspose.imaging.fileformats.emf.emf.records/emffillrgn/ihbrush/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the brush EMF Object Table index to fill the region. |
| [RgnData](../../aspose.imaging.fileformats.emf.emf.records/emffillrgn/rgndata/) { get; set; } | Gets or sets a RgnDataSize length array of bytes that contains a RegionData (section 2.2.24) object. |
| [RgnDataSize](../../aspose.imaging.fileformats.emf.emf.records/emffillrgn/rgndatasize/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the size of region data, in bytes. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | Gets or sets the size of the record |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | Gets or sets the type. |

### See Also

* class [EmfDrawingRecordType](../emfdrawingrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


