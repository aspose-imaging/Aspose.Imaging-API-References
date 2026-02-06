---
title: Class EmfChord
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfChord class. The EMR_CHORD record specifies a chord which is a region bounded by the intersection of an ellipse and a line segment called a secant. The chord is outlined by using the current pen and filled by using the current brush
type: docs
weight: 3390
url: /net/aspose.imaging.fileformats.emf.emf.records/emfchord/
---
## EmfChord class

The EMR_CHORD record specifies a chord, which is a region bounded by the intersection of an ellipse and a line segment, called a secant. The chord is outlined by using the current pen and filled by using the current brush.

```csharp
public sealed class EmfChord : EmfDrawingRecordType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfChord](emfchord/#constructor)() | Initializes a new instance of the `EmfChord` class. |
| [EmfChord](emfchord/#constructor_1)(EmfRecord) | Initializes a new instance of the `EmfChord` class. |

## Properties

| Name | Description |
| --- | --- |
| [Box](../../aspose.imaging.fileformats.emf.emf.records/emfchord/box/) { get; set; } | Gets or sets a 128-bit WMF RectL object, specified in [MS-WMF] section 2.2.2.19, which specifies the inclusive-inclusive bounding rectangle. |
| [End](../../aspose.imaging.fileformats.emf.emf.records/emfchord/end/) { get; set; } | Gets or sets a 64-bit WMF PointL object that specifies the logical coordinates of the endpoint of the radial defining the end of the chord. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | Gets or sets the size of the record |
| [Start](../../aspose.imaging.fileformats.emf.emf.records/emfchord/start/) { get; set; } | Gets or sets a 64-bit WMF PointL object, specified in [MS-WMF] section 2.2.2.15, which specifies the logical coordinates of the endpoint of the radial defining the beginning of the chord. |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | Gets or sets the type. |

### See Also

* class [EmfDrawingRecordType](../emfdrawingrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


