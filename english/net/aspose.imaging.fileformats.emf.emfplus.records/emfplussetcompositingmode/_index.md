---
title: Class EmfPlusSetCompositingMode
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusSetCompositingMode class. The EmfPlusSetCompositingMode record specifies how source colors are combined with background colors
type: docs
weight: 6440
url: /net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetcompositingmode/
---
## EmfPlusSetCompositingMode class

The EmfPlusSetCompositingMode record specifies how source colors are combined with background colors.

```csharp
public sealed class EmfPlusSetCompositingMode : EmfPlusPropertyRecordType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfPlusSetCompositingMode](emfplussetcompositingmode/)(EmfPlusRecord) | Initializes a new instance of the `EmfPlusSetCompositingMode` class. |

## Properties

| Name | Description |
| --- | --- |
| [CompositingMode](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussetcompositingmode/compositingmode/) { get; set; } | Gets or sets the compositing mode value, from the CompositingMode enumeration (section 2.1.1.5). Compositing can be expressed as the state of alpha blending, which can either be on or off. |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | Gets or sets a 32-bit unsigned integer that MUST define the 32-bit–aligned number of bytes of data in the RecordData field that follows. This number does not include the 12-byte record header. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags/) { get; set; } | Gets or sets a 16-bit unsigned integer that contains information for some records on how the operation is to be performed and on the structure of the record. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the 32-bit-aligned number of bytes in the entire record, including the 12-byte record header and record-specific data. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | Gets a 16-bit unsigned integer that identifies the record type. |

### See Also

* class [EmfPlusPropertyRecordType](../emfpluspropertyrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


