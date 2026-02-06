---
title: Class EmfNamedEscape
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfNamedEscape class. The MR_NAMEDESCAPE record passes arbitrary information to a specified printer driver
type: docs
weight: 3960
url: /net/aspose.imaging.fileformats.emf.emf.records/emfnamedescape/
---
## EmfNamedEscape class

The MR_NAMEDESCAPE record passes arbitrary information to a specified printer driver.

```csharp
public sealed class EmfNamedEscape : EmfEscapeRecordType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfNamedEscape](emfnamedescape/)(EmfRecord) | Initializes a new instance of the `EmfNamedEscape` class. |

## Properties

| Name | Description |
| --- | --- |
| [CjDriver](../../aspose.imaging.fileformats.emf.emf.records/emfnamedescape/cjdriver/) { get; set; } | Gets or sets A 32-bit unsigned integer that specifies the number of bytes in the DriverName field. This value MUST be an even number. |
| [CjIn](../../aspose.imaging.fileformats.emf.emf.records/emfnamedescape/cjin/) { get; set; } | Gets or sets A 32-bit unsigned integer specifying the number of bytes to pass to the printer driver. |
| [Data](../../aspose.imaging.fileformats.emf.emf.records/emfnamedescape/data/) { get; set; } | Gets or sets The data to pass to the printer driver. There MUST be cjIn bytes available. |
| [DriverName](../../aspose.imaging.fileformats.emf.emf.records/emfnamedescape/drivername/) { get; set; } | Gets or sets A string of 16-bit Unicode characters that specifies the name of the printer driver that will receive data. This value MUST be cjDriver bytes long, and it MUST be terminated with a null character. |
| [IEscape](../../aspose.imaging.fileformats.emf.emf.records/emfescaperecordtype/iescape/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the printer driver escape to execute. This MUST be one of the values in the WMF MetafileEscapes enumeration ([MSWMF] section 2.1.1.17). |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | Gets or sets the size of the record |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | Gets or sets the type. |

### See Also

* class [EmfEscapeRecordType](../emfescaperecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


