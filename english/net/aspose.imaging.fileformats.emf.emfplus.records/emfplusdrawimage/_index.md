---
title: Class EmfPlusDrawImage
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusDrawImage class. The EmfPlusDrawImage record specifies drawing a scaled image
type: docs
weight: 6080
url: /net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimage/
---
## EmfPlusDrawImage class

The EmfPlusDrawImage record specifies drawing a scaled image.

```csharp
public sealed class EmfPlusDrawImage : EmfPlusDrawingRecordType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfPlusDrawImage](emfplusdrawimage/)(EmfPlusRecord) | Initializes a new instance of the `EmfPlusDrawImage` class. |

## Properties

| Name | Description |
| --- | --- |
| [Compressed](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimage/compressed/) { get; set; } | Gets or sets a value indicating whether the PointData is compressed. If set, RectData contains an EmfPlusRect object (section 2.2.2.38). If clear, RectData contains an EmfPlusRectF object (section 2.2.2.39). |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | Gets or sets a 32-bit unsigned integer that MUST define the 32-bit–aligned number of bytes of data in the RecordData field that follows. This number does not include the 12-byte record header. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags/) { get; set; } | Gets or sets a 16-bit unsigned integer that contains information for some records on how the operation is to be performed and on the structure of the record. |
| [ImageAttributesId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimage/imageattributesid/) { get; set; } | Gets or sets the image attributes identifier A 32-bit unsigned integer that specifies the index of an optional EmfPlusImageAttributes object (section 2.2.1.5) in the EMF+ Object Table. |
| [ObjectId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimage/objectid/) { get; set; } | Gets or sets the object identifier. The index of an EmfPlusImage object (section 2.2.1.4) in the EMF+ Object Table, which specifies the image to render. The value MUST be zero to 63, inclusive. |
| [RectData](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimage/rectdata/) { get; set; } | Gets or sets the rect data Either an EmfPlusRect or EmfPlusRectF object that defines the bounding box of the image. The portion of the image specified by the SrcRect field is scaled to fit this rectangle. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the 32-bit-aligned number of bytes in the entire record, including the 12-byte record header and record-specific data. |
| [SrcRect](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimage/srcrect/) { get; set; } | Gets or sets the source rect An EmfPlusRectF object that specifies a portion of the image to be rendered. The portion of the image specified by this rectangle is scaled to fit the destination rectangle specified by the RectData field. |
| [SrcUnit](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimage/srcunit/) { get; set; } | Gets or sets the source unit 32-bit signed integer that specifies the units of the SrcRect field. It MUST be the UnitTypePixel member of the UnitType enumeration (section 2.1.1.33). |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | Gets a 16-bit unsigned integer that identifies the record type. |

### See Also

* class [EmfPlusDrawingRecordType](../emfplusdrawingrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


