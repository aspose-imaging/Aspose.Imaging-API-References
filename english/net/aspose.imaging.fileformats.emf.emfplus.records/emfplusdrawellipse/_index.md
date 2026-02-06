---
title: Class EmfPlusDrawEllipse
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusDrawEllipse class. The EmfPlusDrawEllipse record specifies drawing an ellipse
type: docs
weight: 6070
url: /net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawellipse/
---
## EmfPlusDrawEllipse class

The EmfPlusDrawEllipse record specifies drawing an ellipse.

```csharp
public sealed class EmfPlusDrawEllipse : EmfPlusDrawingRecordType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfPlusDrawEllipse](emfplusdrawellipse/)(EmfPlusRecord) | Initializes a new instance of the `EmfPlusDrawEllipse` class. |

## Properties

| Name | Description |
| --- | --- |
| [Compressed](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawellipse/compressed/) { get; set; } | Gets or sets a value indicating whether the PointData is compressed. If set, RectData contains an EmfPlusRect object (section 2.2.2.38). If clear, RectData contains an EmfPlusRectF object (section 2.2.2.39). |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | Gets or sets a 32-bit unsigned integer that MUST define the 32-bit–aligned number of bytes of data in the RecordData field that follows. This number does not include the 12-byte record header. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags/) { get; set; } | Gets or sets a 16-bit unsigned integer that contains information for some records on how the operation is to be performed and on the structure of the record. |
| [ObjectId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawellipse/objectid/) { get; set; } | Gets or sets the object identifier. The index of an EmfPlusPen (section 2.2.1.7) object in the EMF+ Object Table to draw the ellipse. The value MUST be zero to 63, inclusive. |
| [RectData](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawellipse/rectdata/) { get; set; } | Gets or sets the rectangle data Either an EmfPlusRect or EmfPlusRectF object that defines the bounding box of the ellipse. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the 32-bit-aligned number of bytes in the entire record, including the 12-byte record header and record-specific data. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | Gets a 16-bit unsigned integer that identifies the record type. |

### See Also

* class [EmfPlusDrawingRecordType](../emfplusdrawingrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


