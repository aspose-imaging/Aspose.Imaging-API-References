---
title: Class EmfPolyBezier16
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfPolyBezier16 class. The EMR_POLYBEZIER16 record specifies one or more Bezier curves. The curves are drawn using the current pen
type: docs
weight: 4070
url: /net/aspose.imaging.fileformats.emf.emf.records/emfpolybezier16/
---
## EmfPolyBezier16 class

The EMR_POLYBEZIER16 record specifies one or more Bezier curves. The curves are drawn using the current pen.

```csharp
public sealed class EmfPolyBezier16 : EmfPolyShape
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfPolyBezier16](emfpolybezier16/#constructor)() | Initializes a new instance of the `EmfPolyBezier16` class. |
| [EmfPolyBezier16](emfpolybezier16/#constructor_1)(EmfRecord) | Initializes a new instance of the `EmfPolyBezier16` class. |

## Properties

| Name | Description |
| --- | --- |
| [APoints](../../aspose.imaging.fileformats.emf.emf.records/emfpolyshape/apoints/) { get; set; } | Gets or sets an array of WMF PointL objects ([MS-WMF] section 2.2.2.15) that specifies the point data, in logical units. |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.records/emfboundedrecord/bounds/) { get; set; } | Gets or sets an 128-bit WMF RectL object ([MS-WMF] section 2.2.2.19) that specifies the bounding rectangle, in device units. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | Gets or sets the size of the record |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | Gets or sets the type. |

## Remarks

Cubic Bezier curves are defined using the endpoints and control points specified by the aPoints field. The first curve is drawn from the first point to the fourth point, using the second and third points as control points. Each subsequent curve in the sequence needs exactly three more points: the ending point of the previous curve is used as the starting point, the next two points in the sequence are control points, and the third is the ending point. The cubic Bezier curves SHOULD be drawn using the current pen

### See Also

* class [EmfPolyShape](../emfpolyshape/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


