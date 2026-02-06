---
title: Class EmfPlusScaleWorldTransform
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusScaleWorldTransform class. The EmfPlusScaleWorldTransform record performs a scaling on the current world space transform
type: docs
weight: 6380
url: /net/aspose.imaging.fileformats.emf.emfplus.records/emfplusscaleworldtransform/
---
## EmfPlusScaleWorldTransform class

The EmfPlusScaleWorldTransform record performs a scaling on the current world space transform.

```csharp
public sealed class EmfPlusScaleWorldTransform : EmfPlusTerminalServerRecordType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfPlusScaleWorldTransform](emfplusscaleworldtransform/)(EmfPlusRecord) | Initializes a new instance of the `EmfPlusScaleWorldTransform` class. |

## Properties

| Name | Description |
| --- | --- |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | Gets or sets a 32-bit unsigned integer that MUST define the 32-bit–aligned number of bytes of data in the RecordData field that follows. This number does not include the 12-byte record header. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags/) { get; set; } | Gets or sets a 16-bit unsigned integer that contains information for some records on how the operation is to be performed and on the structure of the record. |
| [PostMultipliedMatrix](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusscaleworldtransform/postmultipliedmatrix/) { get; } | Gets a value indicating whether [post multiplied matrix]. If set, the transform matrix should be post-multipled. If clear, it should be premultiplied. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the 32-bit-aligned number of bytes in the entire record, including the 12-byte record header and record-specific data. |
| [Sx](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusscaleworldtransform/sx/) { get; set; } | Gets or sets a 32-bit floating-point value that defines the horizontal scale factor. The scaling is performed by constructing a new transform matrix from the Sx and Sy field values, as shown in the following table. ----------------- &#x7C; Sx &#x7C; 0 &#x7C; 0 &#x7C; &#x7C; 0 &#x7C; Sx &#x7C; 0 &#x7C; ----------------- Figure 3: Scale Transform Matrix |
| [Sy](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusscaleworldtransform/sy/) { get; set; } | Gets or sets a 32-bit floating-point value that defines the vertical scale factor. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | Gets a 16-bit unsigned integer that identifies the record type. |

### See Also

* class [EmfPlusTerminalServerRecordType](../emfplusterminalserverrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


