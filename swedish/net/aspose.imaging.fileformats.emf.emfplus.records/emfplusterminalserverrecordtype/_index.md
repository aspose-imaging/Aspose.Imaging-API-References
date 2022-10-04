---
title: EmfPlusTerminalServerRecordType
second_title: Aspose.Imaging för .NET API-referens
description: Terminal Server Record Types specificerar grafikbearbetning på en terminalserver. Följande är EMF terminalserverposttyper.
type: docs
weight: 6440
url: /sv/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusterminalserverrecordtype/
---
## EmfPlusTerminalServerRecordType class

Terminal Server Record Types specificerar grafikbearbetning på en terminalserver. Följande är EMF+ terminalserverposttyper.

```csharp
public abstract class EmfPlusTerminalServerRecordType : EmfPlusRecord
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize) { get; set; } | Hämtar eller ställer in ett 32-bitars osignerat heltal som MÅSTE definiera det 32-bitars-justerade antalet byte med data i RecordData-fältet som följer. Detta nummer inkluderar inte posthuvudet på 12 byte. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags) { get; set; } | Hämtar eller ställer in ett 16-bitars osignerat heltal som innehåller information för vissa poster om hur operationen ska utföras och om postens struktur. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size) { get; set; } | Hämtar eller ställer in ett 32-bitars osignerat heltal som anger det 32-bitars justerade antalet bytes i hela posten, inklusive 12-byte posthuvudet och postspecifika data. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type) { get; } | Får ett 16-bitars osignerat heltal som identifierar posttypen. |

### Se även

* class [EmfPlusRecord](../emfplusrecord)
* namnutrymme [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records)
* hopsättning [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->