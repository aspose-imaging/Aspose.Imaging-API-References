---
title: Class EmfResizePalette
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfResizePalette class. The EMR_RESIZEPALETTE record increases or decreases the size of an existing LogPalette object section 2.2.17
type: docs
weight: 4290
url: /net/aspose.imaging.fileformats.emf.emf.records/emfresizepalette/
---
## EmfResizePalette class

The EMR_RESIZEPALETTE record increases or decreases the size of an existing LogPalette object (section 2.2.17).

```csharp
public sealed class EmfResizePalette : EmfObjectManipulationRecordType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfResizePalette](emfresizepalette/)(EmfRecord) | Initializes a new instance of the `EmfResizePalette` class. |

## Properties

| Name | Description |
| --- | --- |
| [IhPal](../../aspose.imaging.fileformats.emf.emf.records/emfresizepalette/ihpal/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the index of the palette object in the EMF Object Table (section 3.1.1.1). |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | Gets or sets the size of the record |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | Gets or sets the type. |

## Remarks

The new size of the LogPalette object MUST be reflected in the NumberOfEntries field in that structure.

### See Also

* class [EmfObjectManipulationRecordType](../emfobjectmanipulationrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


