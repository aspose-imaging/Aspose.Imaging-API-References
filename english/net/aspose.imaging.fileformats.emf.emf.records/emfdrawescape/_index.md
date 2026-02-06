---
title: Class EmfDrawEscape
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfDrawEscape class. The EMR_DRAWESCAPE record passes arbitrary information to a printer driver. The intent is that the information will result in drawing being done
type: docs
weight: 3650
url: /net/aspose.imaging.fileformats.emf.emf.records/emfdrawescape/
---
## EmfDrawEscape class

The EMR_DRAWESCAPE record passes arbitrary information to a printer driver. The intent is that the information will result in drawing being done.

```csharp
public sealed class EmfDrawEscape : EmfEscapeRecordType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfDrawEscape](emfdrawescape/)(EmfRecord) | Initializes a new instance of the `EmfDrawEscape` class. |

## Properties

| Name | Description |
| --- | --- |
| [CjIn](../../aspose.imaging.fileformats.emf.emf.records/emfdrawescape/cjin/) { get; set; } | Gets or sets a 32-bit unsigned integer specifying the number of bytes to pass to the printer driver. |
| [Data](../../aspose.imaging.fileformats.emf.emf.records/emfdrawescape/data/) { get; set; } | Gets or sets the data to pass to the printer driver. There MUST be cjIn bytes available. |
| [IEscape](../../aspose.imaging.fileformats.emf.emf.records/emfescaperecordtype/iescape/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the printer driver escape to execute. This MUST be one of the values in the WMF MetafileEscapes enumeration ([MSWMF] section 2.1.1.17). |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | Gets or sets the size of the record |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | Gets or sets the type. |

### See Also

* class [EmfEscapeRecordType](../emfescaperecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


