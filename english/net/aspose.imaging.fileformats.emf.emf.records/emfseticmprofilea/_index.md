---
title: Class EmfSetIcmProfileA
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfSetIcmProfileA class. The EMR_SETICMPROFILEA record specifies a color profile in a file with a name consisting of ASCII characters for graphics output
type: docs
weight: 4470
url: /net/aspose.imaging.fileformats.emf.emf.records/emfseticmprofilea/
---
## EmfSetIcmProfileA class

The EMR_SETICMPROFILEA record specifies a color profile in a file with a name consisting of ASCII characters, for graphics output.

```csharp
public sealed class EmfSetIcmProfileA : EmfStateRecordType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfSetIcmProfileA](emfseticmprofilea/)(EmfRecord) | Initializes a new instance of the `EmfSetIcmProfileA` class. |

## Properties

| Name | Description |
| --- | --- |
| [CbData](../../aspose.imaging.fileformats.emf.emf.records/emfseticmprofilea/cbdata/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the size of the color profile data, if it is contained in the Data field. |
| [CbName](../../aspose.imaging.fileformats.emf.emf.records/emfseticmprofilea/cbname/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the number of bytes in the ASCII name of the desired color profile. |
| [Data](../../aspose.imaging.fileformats.emf.emf.records/emfseticmprofilea/data/) { get; set; } | Gets or sets an array of size (cbName + cbData) in bytes, which specifies the ASCII name and raw data of the desired color profile. |
| [DwFlags](../../aspose.imaging.fileformats.emf.emf.records/emfseticmprofilea/dwflags/) { get; set; } | Gets or sets a 32-bit unsigned integer that contains color profile flags. |
| [Name](../../aspose.imaging.fileformats.emf.emf.records/emfseticmprofilea/name/) { get; } | Gets the name |
| [RawData](../../aspose.imaging.fileformats.emf.emf.records/emfseticmprofilea/rawdata/) { get; } | Gets the raw data |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | Gets or sets the size of the record |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | Gets or sets the type. |

### See Also

* class [EmfStateRecordType](../emfstaterecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


