---
title: Class EmfPolygon
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfPolygon class. The EMR_POLYGON record specifies a polygon consisting of two or more vertexes connected by straight lines
type: docs
weight: 4110
url: /net/aspose.imaging.fileformats.emf.emf.records/emfpolygon/
---
## EmfPolygon class

The EMR_POLYGON record specifies a polygon consisting of two or more vertexes connected by straight lines.

```csharp
public sealed class EmfPolygon : EmfDrawingRecordType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfPolygon](emfpolygon/#constructor)() | Initializes a new instance of the `EmfPolygon` class. |
| [EmfPolygon](emfpolygon/#constructor_1)(EmfRecord) | Initializes a new instance of the `EmfPolygon` class. |

## Properties

| Name | Description |
| --- | --- |
| [APoints](../../aspose.imaging.fileformats.emf.emf.records/emfpolygon/apoints/) { get; set; } | Gets or sets a Count length array of WMF PointL objects ([MS-WMF] section 2.2.2.15) that specifies the vertexes of the polygon in logical units. |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.records/emfpolygon/bounds/) { get; set; } | Gets or sets a 128-bit WMF RectL object ([MS-WMF] section 2.2.2.19) that specifies the bounding rectangle in device units. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | Gets or sets the size of the record |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | Gets or sets the type. |

## Remarks

The polygon SHOULD be outlined using the current pen and filled using the current brush and polygon fill mode. The polygon SHOULD be closed automatically by drawing a line from the last vertex to the first

### See Also

* class [EmfDrawingRecordType](../emfdrawingrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


