---
title: Class EmfPolyPolygon
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfPolyPolygon class. The EMR_POLYPOLYGON record specifies a series of closed polygons
type: docs
weight: 4050
url: /net/aspose.imaging.fileformats.emf.emf.records/emfpolypolygon/
---
## EmfPolyPolygon class

The EMR_POLYPOLYGON record specifies a series of closed polygons.

```csharp
public sealed class EmfPolyPolygon : EmfDrawingRecordType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfPolyPolygon](emfpolypolygon/#constructor)() | Initializes a new instance of the `EmfPolyPolygon` class. |
| [EmfPolyPolygon](emfpolypolygon/#constructor_1)(EmfRecord) | Initializes a new instance of the `EmfPolyPolygon` class. |

## Properties

| Name | Description |
| --- | --- |
| [APoints](../../aspose.imaging.fileformats.emf.emf.records/emfpolypolygon/apoints/) { get; set; } | Gets or sets an array of WMF PointL objects ([MS-WMF] section 2.2.2.15) that specifies the points for all polygons in logical units. The number of points is specified by the Count field value. |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.records/emfpolypolygon/bounds/) { get; set; } | Gets or sets a WMF RectL object ([MS-WMF] section 2.2.2.19) that specifies the bounding rectangle, in device units. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | Gets or sets the size of the record |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | Gets or sets the type. |

## Remarks

Each polygon SHOULD be outlined using the current pen, and filled using the current brush and polygon fill mode that are defined in the playback device context. The polygons defined by this record can overlap.

### See Also

* class [EmfDrawingRecordType](../emfdrawingrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


