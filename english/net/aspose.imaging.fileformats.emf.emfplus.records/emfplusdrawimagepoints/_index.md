---
title: Class EmfPlusDrawImagePoints
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusDrawImagePoints class. The EmfPlusDrawImagePoints record specifies drawing a scaled image inside a parallelogram
type: docs
weight: 6090
url: /net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/
---
## EmfPlusDrawImagePoints class

The EmfPlusDrawImagePoints record specifies drawing a scaled image inside a parallelogram.

```csharp
public sealed class EmfPlusDrawImagePoints : EmfPlusDrawingRecordType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfPlusDrawImagePoints](emfplusdrawimagepoints/)(EmfPlusRecord) | Initializes a new instance of the `EmfPlusDrawImagePoints` class. |

## Properties

| Name | Description |
| --- | --- |
| [ApplyingAnEffect](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/applyinganeffect/) { get; set; } | Gets or sets a value indicating whether [applying an effect]. This bit indicates that the rendering of the image includes applying an effect. If set, an object of the Effect class MUST have been specified in an earlier EmfPlusSerializableObject record (section 2.3.5.2). |
| [Compressed](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/compressed/) { get; set; } | Gets or sets a value indicating whether the PointData is compressed. This bit indicates whether the PointData field specifies compressed data. If set, PointData specifies absolute locations in the coordinate space with 16-bit integer coordinates. If clear, PointData specifies absolute locations in the coordinate space with 32-bit floating-point coordinates. Note If the P flag (below) is set, this flag is undefined and MUST be ignored. |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | Gets or sets a 32-bit unsigned integer that MUST define the 32-bit–aligned number of bytes of data in the RecordData field that follows. This number does not include the 12-byte record header. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags/) { get; set; } | Gets or sets a 16-bit unsigned integer that contains information for some records on how the operation is to be performed and on the structure of the record. |
| [ImageAttributesId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/imageattributesid/) { get; set; } | Gets or sets a 32-bit unsigned integer that contains the index of the optional EmfPlusImageAttributes object (section 2.2.1.5) in the EMF+ Object Table. |
| [ObjectId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/objectid/) { get; set; } | Gets or sets the object identifier. The index of an EmfPlusImage object (section 2.2.1.4) in the EMF+ Object Table, which specifies the image to render. The value MUST be zero to 63, inclusive. |
| [PointData](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/pointdata/) { get; set; } | Gets or sets an array of Count points that specify three points of a parallelogram. The three points represent the upper-left, upper-right, and lower-left corners of the parallelogram. The fourth point of the parallelogram is extrapolated from the first three. The portion of the image specified by the SrcRect field SHOULD have scaling and shearing transforms applied if necessary to fit inside the parallelogram. |
| [Relative](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/relative/) { get; set; } | Gets or sets a value indicating whether this `EmfPlusDrawImagePoints` is relative. This bit indicates whether the PointData field specifies relative or absolute locations. If set, each element in PointData specifies a location in the coordinate space that is relative to the location specified by the previous element in the array. In the case of the first element in PointData, a previous location at coordinates (0,0) is assumed. If clear, PointData specifies absolute locations according to the C flag. Note If this flag is set, the C flag (above) is undefined and MUST be ignored. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the 32-bit-aligned number of bytes in the entire record, including the 12-byte record header and record-specific data. |
| [SrcRect](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/srcrect/) { get; set; } | Gets or sets an EmfPlusRectF object (section 2.2.2.39) that defines a portion of the image to be rendered. |
| [SrcUnit](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/srcunit/) { get; set; } | Gets or sets a 32-bit signed integer that defines the units of the SrcRect field. It MUST be the UnitPixel value of the UnitType enumeration (section 2.1.1.33). |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | Gets a 16-bit unsigned integer that identifies the record type. |

## Remarks

An EmfPlusImage can specify either a bitmap or metafile. Colors in an image can be manipulated during rendering. They can be corrected, darkened, lightened, and removed.

### See Also

* class [EmfPlusDrawingRecordType](../emfplusdrawingrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


