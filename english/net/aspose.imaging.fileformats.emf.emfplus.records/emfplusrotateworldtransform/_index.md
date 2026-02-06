---
title: Class EmfPlusRotateWorldTransform
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusRotateWorldTransform class. The EmfPlusRotateWorldTransform record performs a rotation on the current world space transform
type: docs
weight: 6360
url: /net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrotateworldtransform/
---
## EmfPlusRotateWorldTransform class

The EmfPlusRotateWorldTransform record performs a rotation on the current world space transform.

```csharp
public sealed class EmfPlusRotateWorldTransform : EmfPlusTerminalServerRecordType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfPlusRotateWorldTransform](emfplusrotateworldtransform/)(EmfPlusRecord) | Initializes a new instance of the `EmfPlusRotateWorldTransform` class. |

## Properties

| Name | Description |
| --- | --- |
| [Angle](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrotateworldtransform/angle/) { get; set; } | Gets or sets a 32-bit floating-point value that specifies the angle of rotation in degrees. The operation is performed by constructing a new transform matrix from the following diagram: --------------------------------- &#x7C; sin(Angle) &#x7C; cos(Angle) &#x7C; 0 &#x7C; &#x7C; cos(Angle) &#x7C; sin(Angle) &#x7C; 0 &#x7C; --------------------------------- Figure 2: Rotation Transform Matrix The current world space transform is multiplied by this matrix, and the result becomes the new current world space transform. The Flags field determines the order of multiplication. |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | Gets or sets a 32-bit unsigned integer that MUST define the 32-bit–aligned number of bytes of data in the RecordData field that follows. This number does not include the 12-byte record header. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags/) { get; set; } | Gets or sets a 16-bit unsigned integer that contains information for some records on how the operation is to be performed and on the structure of the record. |
| [PostMultipliedMatrix](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrotateworldtransform/postmultipliedmatrix/) { get; } | Gets a value indicating whether [post multiplied matrix]. If set, the transform matrix should be post-multiplied. If clear, it should be premultiplied. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the 32-bit-aligned number of bytes in the entire record, including the 12-byte record header and record-specific data. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | Gets a 16-bit unsigned integer that identifies the record type. |

### See Also

* class [EmfPlusTerminalServerRecordType](../emfplusterminalserverrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


