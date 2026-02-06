---
title: Class EmfEof
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfEof class. The EMR_EOF record indicates the end of the metafile and specifies a palette
type: docs
weight: 3690
url: /net/aspose.imaging.fileformats.emf.emf.records/emfeof/
---
## EmfEof class

The EMR_EOF record indicates the end of the metafile and specifies a palette.

```csharp
public sealed class EmfEof : EmfControlRecordType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfEof](emfeof/#constructor)() | Initializes a new instance of the `EmfEof` class. |
| [EmfEof](emfeof/#constructor_1)(EmfRecord) | Initializes a new instance of the `EmfEof` class. |

## Properties

| Name | Description |
| --- | --- |
| [PaletteArgb32Entries](../../aspose.imaging.fileformats.emf.emf.records/emfeof/paletteargb32entries/) { get; set; } | Gets or sets an optional buffer that contains palette data, which is not required to be contiguous with the fixed portion of the EMR_EOF record. Accordingly, fields in this buffer that are labeled "UndefinedSpace" are optional and MUST be ignored. The size of this field MUST be a multiple of 4 bytes |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | Gets or sets the size of the record |
| [SizeLast](../../aspose.imaging.fileformats.emf.emf.records/emfeof/sizelast/) { get; set; } | Gets or sets a 32-bit unsigned integer that MUST be the same as Size and MUST be the last field of the record and hence the metafile. LogPaletteEntry objects, if they exist, MUST precede this field. |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | Gets or sets the type. |

### See Also

* class [EmfControlRecordType](../emfcontrolrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


