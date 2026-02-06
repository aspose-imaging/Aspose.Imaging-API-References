---
title: Class EmfPlusSetTextContrast
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.EmfPlus.Records.EmfPlusSetTextContrast class. The EmfPlusSetTextContrast record specifies text contrast according to the gamma correction value
type: docs
weight: 6500
url: /net/aspose.imaging.fileformats.emf.emfplus.records/emfplussettextcontrast/
---
## EmfPlusSetTextContrast class

The EmfPlusSetTextContrast record specifies text contrast according to the gamma correction value.

```csharp
public sealed class EmfPlusSetTextContrast : EmfPlusPropertyRecordType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfPlusSetTextContrast](emfplussettextcontrast/)(EmfPlusRecord) | Initializes a new instance of the `EmfPlusSetTextContrast` class. |

## Properties

| Name | Description |
| --- | --- |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize/) { get; set; } | Gets or sets a 32-bit unsigned integer that MUST define the 32-bit–aligned number of bytes of data in the RecordData field that follows. This number does not include the 12-byte record header. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags/) { get; set; } | Gets or sets a 16-bit unsigned integer that contains information for some records on how the operation is to be performed and on the structure of the record. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the 32-bit-aligned number of bytes in the entire record, including the 12-byte record header and record-specific data. |
| [TextContrast](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussettextcontrast/textcontrast/) { get; set; } | Gets or sets the gamma correction value X 1000, which will be applied to subsequent text rendering operations. The allowable range is 1000 to 2200, representing text gamma values of 1.0 to 2.2. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type/) { get; } | Gets a 16-bit unsigned integer that identifies the record type. |

### See Also

* class [EmfPlusPropertyRecordType](../emfpluspropertyrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records/)
* assembly [Aspose.Imaging](../../)


