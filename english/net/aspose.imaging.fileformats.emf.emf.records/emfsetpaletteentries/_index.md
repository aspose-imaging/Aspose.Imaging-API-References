---
title: Class EmfSetPaletteEntries
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FileFormats.Emf.Emf.Records.EmfSetPaletteEntries class. The EMR_SETPALETTEENTRIES record defines RGB color values in a range of entries for an existing LogPalette section 2.2.17 object
type: docs
weight: 4560
url: /net/aspose.imaging.fileformats.emf.emf.records/emfsetpaletteentries/
---
## EmfSetPaletteEntries class

The EMR_SETPALETTEENTRIES record defines RGB color values in a range of entries for an existing LogPalette (section 2.2.17) object.

```csharp
public sealed class EmfSetPaletteEntries : EmfObjectManipulationRecordType
```

## Constructors

| Name | Description |
| --- | --- |
| [EmfSetPaletteEntries](emfsetpaletteentries/)(EmfRecord) | Initializes a new instance of the `EmfSetPaletteEntries` class. |

## Properties

| Name | Description |
| --- | --- |
| [Argb32PalEntries](../../aspose.imaging.fileformats.emf.emf.records/emfsetpaletteentries/argb32palentries/) { get; set; } | Gets or sets an array of LogPaletteEntry (section 2.2.18) objects, of NumberOfEntries length, which specifies the palette entry data. The Values members do not contain any values. |
| [IhPal](../../aspose.imaging.fileformats.emf.emf.records/emfsetpaletteentries/ihpal/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the palette EMF Object Table index. |
| [NumberofEntries](../../aspose.imaging.fileformats.emf.emf.records/emfsetpaletteentries/numberofentries/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the number of entries. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size/) { get; set; } | Gets or sets the size of the record |
| [Start](../../aspose.imaging.fileformats.emf.emf.records/emfsetpaletteentries/start/) { get; set; } | Gets or sets a 32-bit unsigned integer that specifies the index of the first entry to set. |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type/) { get; set; } | Gets or sets the type. |

### See Also

* class [EmfObjectManipulationRecordType](../emfobjectmanipulationrecordtype/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records/)
* assembly [Aspose.Imaging](../../)


