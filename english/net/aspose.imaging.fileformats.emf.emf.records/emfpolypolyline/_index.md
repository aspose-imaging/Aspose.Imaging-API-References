---
title: Class EmfPolyPolyline
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfPolyPolyline class. The EMR_POLYPOLYLINE record specifies multiple series of connected line segments
type: docs
weight: 4150
url: /net/aspose.imaging.fileformats.emf.emf.records/emfpolypolyline/
---
## EmfPolyPolyline class

The EMR_POLYPOLYLINE record specifies multiple series of connected line segments.

```csharp
public sealed class EmfPolyPolyline : EmfPolyPolyShape
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfPolyPolyline](emfpolypolyline/#constructor)() | Initializes a new instance of the `EmfPolyPolyline` class. |
| [EmfPolyPolyline](emfpolypolyline/#constructor_1)(EmfRecord) | Initializes a new instance of the `EmfPolyPolyline` class. |

## Properties

| Name | Description |
| --- | --- |
| [APoints](../../aspose.imaging.fileformats.emf.emf.records/emfpolypolyshape/apoints/) { get; set; } | Gets or sets an array of WMF PointS objects, specified in [MS-WMF] section 2.2.2.16, which specifies the array of points. |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.records/emfboundedrecord/bounds/) { get; set; } | Gets or sets an 128-bit WMF RectL object ([MS-WMF] section 2.2.2.19) that specifies the bounding rectangle, in device units. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | Gets or sets the size of the record |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | Gets or sets the type. |

## Remarks

The line segments SHOULD be drawn using the current pen. The figures formed by the segments SHOULD NOT filled. The current position SHOULD neither be used nor updated by this record.

### See Also

* class [EmfPolyPolyShape](../emfpolypolyshape/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


