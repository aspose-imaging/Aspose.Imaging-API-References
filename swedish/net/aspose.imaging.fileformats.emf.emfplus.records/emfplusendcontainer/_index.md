---
title: EmfPlusEndContainer
second_title: Aspose.Imaging för .NET API-referens
description: EmfPlusEndContainer-posten stänger en grafiktillståndsbehållare som tidigare öppnades av en start-containeroperation.
type: docs
weight: 6040
url: /sv/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusendcontainer/
---
## EmfPlusEndContainer class

EmfPlusEndContainer-posten stänger en grafiktillståndsbehållare som tidigare öppnades av en start-containeroperation.

```csharp
public sealed class EmfPlusEndContainer : EmfPlusStateRecordType
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [EmfPlusEndContainer](emfplusendcontainer)(EmfPlusRecord) | Initierar en ny instans av[`EmfPlusEndContainer`](../emfplusendcontainer) class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize) { get; set; } | Hämtar eller ställer in ett 32-bitars osignerat heltal som MÅSTE definiera det 32-bitars-justerade antalet byte med data i RecordData-fältet som följer. Detta nummer inkluderar inte posthuvudet på 12 byte. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags) { get; set; } | Hämtar eller ställer in ett 16-bitars osignerat heltal som innehåller information för vissa poster om hur operationen ska utföras och om postens struktur. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size) { get; set; } | Hämtar eller ställer in ett 32-bitars osignerat heltal som anger det 32-bitars justerade antalet bytes i hela posten, inklusive 12-byte posthuvudet och postspecifika data. |
| [StackIndex](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusendcontainer/stackindex) { get; set; } | Hämtar eller ställer in ett 32-bitars osignerat heltal som anger indexet för en grafikstatus -behållare. Indexet MÅSTE matcha värdet som är associerat med ett grafiktillstånd container som öppnats av en tidigare EmfPlusBeginContainer (avsnitt 2.3.7.1) eller EmfPlusBeginContainerNoParams-post (avsnitt 2.3.7.2). |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type) { get; } | Får ett 16-bitars osignerat heltal som identifierar posttypen. |

### Se även

* class [EmfPlusStateRecordType](../emfplusstaterecordtype)
* namnutrymme [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records)
* hopsättning [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
