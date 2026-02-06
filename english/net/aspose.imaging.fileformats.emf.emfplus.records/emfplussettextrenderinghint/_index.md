---
title: Class EmfPlusSetTextRenderingHint
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusSetTextRenderingHint class. The EmfPlusSetTextRenderingHint record specifies the quality of text rendering including the type of antialiasing
type: docs
weight: 6510
url: /net/aspose.imaging.fileformats.emf.emfplus.records/emfplussettextrenderinghint/
---
## EmfPlusSetTextRenderingHint class

The EmfPlusSetTextRenderingHint record specifies the quality of text rendering, including the type of anti-aliasing.

```csharp
public sealed class EmfPlusSetTextRenderingHint : EmfPlusPropertyRecordType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfPlusSetTextRenderingHint](emfplussettextrenderinghint/)(EmfPlusRecord) | Initializes a new instance of the `EmfPlusSetTextRenderingHint` class. |

## Properties

| Name | Description |
| --- | --- |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | Gets or sets a 32-bit unsigned integer that MUST define the 32-bit–aligned number of bytes of data in the RecordData field that follows. This number does not include the 12-byte record header. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags/) { get; set; } | Gets or sets a 16-bit unsigned integer that contains information for some records on how the operation is to be performed and on the structure of the record. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the 32-bit-aligned number of bytes in the entire record, including the 12-byte record header and record-specific data. |
| [TextRenderingHint](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettextrenderinghint/textrenderinghint/) { get; set; } | Gets or sets the text rendering hint value, from the TextRenderingHint enumeration (section 2.1.1.32), which specifies the quality to use in subsequent text rendering. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | Gets a 16-bit unsigned integer that identifies the record type. |

### See Also

* class [EmfPlusPropertyRecordType](../emfpluspropertyrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


