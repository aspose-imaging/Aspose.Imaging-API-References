---
title: Class EmfPlusSetAntiAliasMode
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusSetAntiAliasMode class. The EmfPlusSetAntiAliasMode record specifies the antialiasing mode for text output
type: docs
weight: 6400
url: /net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetantialiasmode/
---
## EmfPlusSetAntiAliasMode class

The EmfPlusSetAntiAliasMode record specifies the anti-aliasing mode for text output.

```csharp
public sealed class EmfPlusSetAntiAliasMode : EmfPlusPropertyRecordType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfPlusSetAntiAliasMode](emfplussetantialiasmode/)(EmfPlusRecord) | Initializes a new instance of the `EmfPlusSetAntiAliasMode` class. |

## Properties

| Name | Description |
| --- | --- |
| [AntiAliasing](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussetantialiasmode/antialiasing/) { get; set; } | Gets or sets a value indicating whether [anti aliasing]. If set, anti-aliasing SHOULD be performed. If clear, anti-aliasing SHOULD NOT be performed. |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | Gets or sets a 32-bit unsigned integer that MUST define the 32-bit–aligned number of bytes of data in the RecordData field that follows. This number does not include the 12-byte record header. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags/) { get; set; } | Gets or sets a 16-bit unsigned integer that contains information for some records on how the operation is to be performed and on the structure of the record. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the 32-bit-aligned number of bytes in the entire record, including the 12-byte record header and record-specific data. |
| [SmoothingMode](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussetantialiasmode/smoothingmode/) { get; set; } | Gets or sets the smoothing mode. (7 bits): The smoothing mode value, from the SmoothingMode enumeration (section 2.1.1.28) |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | Gets a 16-bit unsigned integer that identifies the record type. |

### See Also

* class [EmfPlusPropertyRecordType](../emfpluspropertyrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


