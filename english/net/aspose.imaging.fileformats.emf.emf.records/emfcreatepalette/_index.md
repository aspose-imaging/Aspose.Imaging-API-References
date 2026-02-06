---
title: Class EmfCreatePalette
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfCreatePalette class. The EMR_CREATEPALETTE record defines a logical palette for graphics operations
type: docs
weight: 3610
url: /net/aspose.imaging.fileformats.emf.emf.records/emfcreatepalette/
---
## EmfCreatePalette class

The EMR_CREATEPALETTE record defines a logical palette for graphics operations.

```csharp
public sealed class EmfCreatePalette : EmfObjectCreationRecordType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfCreatePalette](emfcreatepalette/)(EmfRecord) | Initializes a new instance of the `EmfCreatePalette` class. |

## Properties

| Name | Description |
| --- | --- |
| [IhPal](../../aspose.imaging.fileformats.emf.emf.records/emfcreatepalette/ihpal/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the index of the logical palette object in the EMF Object Table (section 3.1.1.1). This index MUST be saved so that this object can be reused or modified. |
| [LogPalette](../../aspose.imaging.fileformats.emf.emf.records/emfcreatepalette/logpalette/) { get; set; } | Gets or sets a LogPalette object (section 2.2.17). The Version field of this object MUST be set to 0x0300. If the NumberOfEntries value in this object is zero, processing of this record MUST fail. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | Gets or sets the size of the record |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | Gets or sets the type. |

### See Also

* class [EmfObjectCreationRecordType](../emfobjectcreationrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


