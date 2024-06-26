---
title: EmfPlusDrawArc.DataSize
second_title: Aspose.Imaging for .NET API Reference
description: EmfPlusDrawArc property. Gets or sets the size of the data. A 32bit unsigned integer that specifies the 32bitaligned number of bytes of recordspecific data that follows. For this record type the value MUST be one of the following 0x00000010 If the C bit is set in the Flags field. 0x00000018 If the C bit is clear in the Flags field
type: docs
weight: 20
url: /net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawarc/datasize/
---
## EmfPlusDrawArc.DataSize property

Gets or sets the size of the data. A 32-bit unsigned integer that specifies the 32-bit-aligned number of bytes of record-specific data that follows. For this record type, the value MUST be one of the following: 0x00000010 If the C bit is set in the Flags field. 0x00000018 If the C bit is clear in the Flags field.

```csharp
public override int DataSize { get; set; }
```

### Property Value

The size of the data.

### Exceptions

| exception | condition |
| --- | --- |
| InvalidDataException | Invalid value |

### See Also

* class [EmfPlusDrawArc](../)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../emfplusdrawarc/)
* assembly [Aspose.Imaging](../../../)


