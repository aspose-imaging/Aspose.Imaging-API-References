---
title: Class EmfPolylineTo16
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfPolylineTo16 class. The EMR_POLYLINETO16 record specifies one or more straight lines based upon the current position. A line is drawn from the current position to the first point specified by the aPoints field by using the current pen. For each additional line drawing is performed from the ending point of the previous line to the next point specified by aPoints
type: docs
weight: 4160
url: /net/aspose.imaging.fileformats.emf.emf.records/emfpolylineto16/
---
## EmfPolylineTo16 class

The EMR_POLYLINETO16 record specifies one or more straight lines based upon the current position. A line is drawn from the current position to the first point specified by the aPoints field by using the current pen. For each additional line, drawing is performed from the ending point of the previous line to the next point specified by aPoints.

```csharp
public sealed class EmfPolylineTo16 : EmfDrawingRecordType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfPolylineTo16](emfpolylineto16/#constructor)() | Initializes a new instance of the `EmfPolylineTo16` class. |
| [EmfPolylineTo16](emfpolylineto16/#constructor_1)(EmfRecord) | Initializes a new instance of the `EmfPolylineTo16` class. |

## Properties

| Name | Description |
| --- | --- |
| [APoints](../../aspose.imaging.fileformats.emf.emf.records/emfpolylineto16/apoints/) { get; set; } | Gets or sets a Count length array of WMF PointS objects, specified in [MS-WMF] section 2.2.2.16, which specifies the array of points. |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.records/emfpolylineto16/bounds/) { get; set; } | Gets or sets a 128-bit WMF RectL object, specified in [MS-WMF] section 2.2.2.19, which specifies the bounding rectangle, in device units. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | Gets or sets the size of the record |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | Gets or sets the type. |

### See Also

* class [EmfDrawingRecordType](../emfdrawingrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


