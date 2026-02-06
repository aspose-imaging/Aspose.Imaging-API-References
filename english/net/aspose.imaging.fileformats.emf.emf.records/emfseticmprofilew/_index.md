---
title: Class EmfSetIcmProfileW
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfSetIcmProfileW class. The EMR_SETICMPROFILEW record specifies a color profile in a file with a name consisting of Unicode characters for graphics output
type: docs
weight: 4480
url: /net/aspose.imaging.fileformats.emf.emf.records/emfseticmprofilew/
---
## EmfSetIcmProfileW class

The EMR_SETICMPROFILEW record specifies a color profile in a file with a name consisting of Unicode characters, for graphics output.

```csharp
public sealed class EmfSetIcmProfileW : EmfStateRecordType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfSetIcmProfileW](emfseticmprofilew/)(EmfRecord) | Initializes a new instance of the `EmfSetIcmProfileW` class. |

## Properties

| Name | Description |
| --- | --- |
| [CbData](../../aspose.imaging.fileformats.emf.emf.records/emfseticmprofilew/cbdata/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the size of color profile data, if attached. |
| [CbName](../../aspose.imaging.fileformats.emf.emf.records/emfseticmprofilew/cbname/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the number of bytes in the Unicode UTF16-LE name of the desired color profile. |
| [Data](../../aspose.imaging.fileformats.emf.emf.records/emfseticmprofilew/data/) { get; set; } | Gets or sets an array of size (cbName + cbData) in bytes, which specifies the UTF16-LE name and raw data of the desired color profile. |
| [DwFlags](../../aspose.imaging.fileformats.emf.emf.records/emfseticmprofilew/dwflags/) { get; set; } | Gets or sets a 32-bit unsigned integer that contains color profile flags. |
| [Name](../../aspose.imaging.fileformats.emf.emf.records/emfseticmprofilew/name/) { get; } | Gets the name |
| [RawData](../../aspose.imaging.fileformats.emf.emf.records/emfseticmprofilew/rawdata/) { get; } | Gets the raw data |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | Gets or sets the size of the record |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | Gets or sets the type. |

### See Also

* class [EmfStateRecordType](../emfstaterecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


