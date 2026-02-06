---
title: Class EmfAngleArc
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfAngleArc class. The EMR_ANGLEARC record specifies a line segment of an arc. The line segment is drawn from the current position to the beginning of the arc. The arc is drawn along the perimeter of a circle with the given radius and center. The length of the arc is defined by the given start and sweep angles
type: docs
weight: 3300
url: /net/aspose.imaging.fileformats.emf.emf.records/emfanglearc/
---
## EmfAngleArc class

The EMR_ANGLEARC record specifies a line segment of an arc. The line segment is drawn from the current position to the beginning of the arc. The arc is drawn along the perimeter of a circle with the given radius and center. The length of the arc is defined by the given start and sweep angles

```csharp
public sealed class EmfAngleArc : EmfDrawingRecordType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfAngleArc](emfanglearc/#constructor)() | Initializes a new instance of the `EmfAngleArc` class. |
| [EmfAngleArc](emfanglearc/#constructor_1)(EmfRecord) | Initializes a new instance of the `EmfAngleArc` class. |

## Properties

| Name | Description |
| --- | --- |
| [Center](../../aspose.imaging.fileformats.emf.emf.records/emfanglearc/center/) { get; set; } | Gets or sets a 64-bit WMF PointL object, specified in [MS-WMF] section 2.2.2.15, which specifies the logical coordinates of the circle's center. |
| [Radius](../../aspose.imaging.fileformats.emf.emf.records/emfanglearc/radius/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the circle's radius, in logical units. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | Gets or sets the size of the record |
| [StartAngle](../../aspose.imaging.fileformats.emf.emf.records/emfanglearc/startangle/) { get; set; } | Gets or sets a 32-bit float that specifies the arc's start angle, in degrees. |
| [SweepAngle](../../aspose.imaging.fileformats.emf.emf.records/emfanglearc/sweepangle/) { get; set; } | Gets or sets a 32-bit float that specifies the arc's sweep angle, in degrees. |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | Gets or sets the type. |

### See Also

* class [EmfDrawingRecordType](../emfdrawingrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


