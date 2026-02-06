---
title: Class EmfPlusStateRecordType
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusStateRecordType class. The State Record Types specify operations on the state of the playback device context
type: docs
weight: 6550
url: /net/aspose.imaging.fileformats.emf.emfplus.records/emfplusstaterecordtype/
---
## EmfPlusStateRecordType class

The State Record Types specify operations on the state of the playback device context.

```csharp
public abstract class EmfPlusStateRecordType : EmfPlusRecord
```

## Properties

| Name | Description |
| --- | --- |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | Gets or sets a 32-bit unsigned integer that MUST define the 32-bit–aligned number of bytes of data in the RecordData field that follows. This number does not include the 12-byte record header. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags/) { get; set; } | Gets or sets a 16-bit unsigned integer that contains information for some records on how the operation is to be performed and on the structure of the record. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the 32-bit-aligned number of bytes in the entire record, including the 12-byte record header and record-specific data. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | Gets a 16-bit unsigned integer that identifies the record type. |

## Remarks

Each graphics state container MUST be added to an array of saved graphics containers. The graphics state container is not written to the EMF+ metafile, so its format can be determined by the implementation.

### See Also

* class [EmfPlusRecord](../emfplusrecord/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


