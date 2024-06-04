---
title: Class EmfPolyPolyline
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfPolyPolyline class. The EMR_POLYPOLYLINE record specifies multiple series of connected line segments
type: docs
weight: 4070
url: /net/aspose.imaging.fileformats.emf.emf.records/emfpolypolyline/
---
## EmfPolyPolyline class

The EMR_POLYPOLYLINE record specifies multiple series of connected line segments.

```csharp
public sealed class EmfPolyPolyline : EmfDrawingRecordType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfPolyPolyline](emfpolypolyline/#constructor)() | Initializes a new instance of the `EmfPolyPolyline` class. |
| [EmfPolyPolyline](emfpolypolyline/#constructor_1)(EmfRecord) | Initializes a new instance of the `EmfPolyPolyline` class. |

## Properties

| Name | Description |
| --- | --- |
| [APoints](../../aspose.imaging.fileformats.emf.emf.records/emfpolypolyline/apoints/) { get; set; } | Gets or sets a Count-length array of WMF PointL objects ([MS-WMF] section 2.2.2.15) that specify the point data, in logical units. |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.records/emfpolypolyline/bounds/) { get; set; } | Gets or sets a 128-bit WMF RectL object ([MS-WMF] section 2.2.2.19) that specifies the bounding rectangle in device units. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | Gets or sets the size of the record |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | Gets or sets the type. |

## Remarks

The line segments SHOULD be drawn using the current pen. The figures formed by the segments SHOULD NOT filled. The current position SHOULD neither be used nor updated by this record.

### See Also

* class [EmfDrawingRecordType](../emfdrawingrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


