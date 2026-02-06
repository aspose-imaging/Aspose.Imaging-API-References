---
title: Class EmfSetIcmMode
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfSetIcmMode class. The EMR_SETICMMODE record specifies the mode of Image Color Management ICM for graphics operations
type: docs
weight: 4460
url: /net/aspose.imaging.fileformats.emf.emf.records/emfseticmmode/
---
## EmfSetIcmMode class

The EMR_SETICMMODE record specifies the mode of Image Color Management (ICM) for graphics operations.

```csharp
public sealed class EmfSetIcmMode : EmfStateRecordType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfSetIcmMode](emfseticmmode/)(EmfRecord) | Initializes a new instance of the `EmfSetIcmMode` class. |

## Properties

| Name | Description |
| --- | --- |
| [IcmMode](../../aspose.imaging.fileformats.emf.emf.records/emfseticmmode/icmmode/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies whether to enable or disable ICM, from the ICMMode enumeration (section 2.1.18). This value is part of the state of the playback device context. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | Gets or sets the size of the record |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | Gets or sets the type. |

## Remarks

When ICM mode is enabled, colors specified in EMF records SHOULD be color matched, whereas the default color profile in the playback device context SHOULD be used when a bit-block transfer is performed. If the default color profile is not desired, ICM mode SHOULD be turned off before performing the bit-block transfer.

### See Also

* class [EmfStateRecordType](../emfstaterecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


