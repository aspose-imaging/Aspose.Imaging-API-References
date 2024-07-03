---
title: Class EmfPlusTranslateWorldTransform
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusTranslateWorldTransform class. The EmfPlusTranslateWorldTransform record performs a translation on the current world space transform
type: docs
weight: 6520
url: /net/aspose.imaging.fileformats.emf.emfplus.records/emfplustranslateworldtransform/
---
## EmfPlusTranslateWorldTransform class

The EmfPlusTranslateWorldTransform record performs a translation on the current world space transform.

```csharp
public sealed class EmfPlusTranslateWorldTransform : EmfPlusTerminalServerRecordType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfPlusTranslateWorldTransform](emfplustranslateworldtransform/)(EmfPlusRecord) | Initializes a new instance of the `EmfPlusTranslateWorldTransform` class. |

## Properties

| Name | Description |
| --- | --- |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | Gets or sets a 32-bit unsigned integer that MUST define the 32-bit–aligned number of bytes of data in the RecordData field that follows. This number does not include the 12-byte record header. |
| [Dx](../../aspose.imaging.fileformats.emf.emfplus.records/emfplustranslateworldtransform/dx/) { get; set; } | Gets or sets a 32-bit floating-point value that defines the horizontal distance. The translation is performed by constructing a new world transform matrix from the dx and dy fields |
| [Dy](../../aspose.imaging.fileformats.emf.emfplus.records/emfplustranslateworldtransform/dy/) { get; set; } | Gets or sets a 32-bit floating-point value that defines the vertical distance value. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags/) { get; set; } | Gets or sets a 16-bit unsigned integer that contains information for some records on how the operation is to be performed and on the structure of the record. |
| [PostMultipliedMatrix](../../aspose.imaging.fileformats.emf.emfplus.records/emfplustranslateworldtransform/postmultipliedmatrix/) { get; } | Gets a value indicating whether [post multiplied matrix]. If set, the transform matrix should be post-multiplied. If clear, it should be premultiplied. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the 32-bit-aligned number of bytes in the entire record, including the 12-byte record header and record-specific data. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | Gets a 16-bit unsigned integer that identifies the record type. |

### See Also

* class [EmfPlusTerminalServerRecordType](../emfplusterminalserverrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


