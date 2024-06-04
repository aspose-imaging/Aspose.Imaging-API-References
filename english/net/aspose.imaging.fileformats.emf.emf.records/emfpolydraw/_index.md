---
title: Class EmfPolyDraw
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfPolyDraw class. The EMR_POLYDRAW record specifies a set of line segments and Bezier curves
type: docs
weight: 4030
url: /net/aspose.imaging.fileformats.emf.emf.records/emfpolydraw/
---
## EmfPolyDraw class

The EMR_POLYDRAW record specifies a set of line segments and Bezier curves.

```csharp
public sealed class EmfPolyDraw : EmfDrawingRecordType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfPolyDraw](emfpolydraw/#constructor)() | Initializes a new instance of the `EmfPolyDraw` class. |
| [EmfPolyDraw](emfpolydraw/#constructor_1)(EmfRecord) | Initializes a new instance of the `EmfPolyDraw` class. |

## Properties

| Name | Description |
| --- | --- |
| [AbTypes](../../aspose.imaging.fileformats.emf.emf.records/emfpolydraw/abtypes/) { get; set; } | Gets or sets a Count length array of byte values that specifies how each point in the Gets or sets aPoints array is used. This value MUST be in the Point (section 2.1.26) enumeration. |
| [APoints](../../aspose.imaging.fileformats.emf.emf.records/emfpolydraw/apoints/) { get; set; } | Gets or sets a Count length array of WMF PointL objects, specified in [MS-WMF] section 2.2.2.15, which specifies the array of points, in logical units. |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.records/emfpolydraw/bounds/) { get; set; } | Gets or sets a 128-bit WMF RectL object, specified in [MS-WMF] section 2.2.2.19, which specifies the bounding rectangle, in device units. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | Gets or sets the size of the record |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | Gets or sets the type. |

### See Also

* class [EmfDrawingRecordType](../emfdrawingrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


