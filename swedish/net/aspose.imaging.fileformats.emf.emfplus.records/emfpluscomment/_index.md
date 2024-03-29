---
title: EmfPlusComment
second_title: Aspose.Imaging för .NET API-referens
description: EmfPlusComment-posten anger godtyckliga privata data.
type: docs
weight: 5880
url: /sv/net/aspose.imaging.fileformats.emf.emfplus.records/emfpluscomment/
---
## EmfPlusComment class

EmfPlusComment-posten anger godtyckliga privata data.

```csharp
public sealed class EmfPlusComment : EmfPlusRecord
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [EmfPlusComment](emfpluscomment)(EmfPlusRecord) | Initierar en ny instans av[`EmfPlusComment`](../emfpluscomment) class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize) { get; set; } | Hämtar eller ställer in ett 32-bitars osignerat heltal som MÅSTE definiera det 32-bitars-justerade antalet byte med data i RecordData-fältet som följer. Detta nummer inkluderar inte posthuvudet på 12 byte. |
| override [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfpluscomment/flags) { get; set; } | Hämtar eller ställer in ett 16-bitars osignerat heltal som inte används. Det här fältet SKA sättas till noll och MÅSTE ignoreras vid kvitto |
| [PrivateData](../../aspose.imaging.fileformats.emf.emfplus.records/emfpluscomment/privatedata) { get; set; } | Hämtar eller ställer in en DataSize-length byte-array av privata data. byte av postspecifik data som följer. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size) { get; set; } | Hämtar eller ställer in ett 32-bitars osignerat heltal som anger det 32-bitars justerade antalet bytes i hela posten, inklusive 12-byte posthuvudet och postspecifika data. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type) { get; } | Får ett 16-bitars osignerat heltal som identifierar posttypen. |

### Se även

* class [EmfPlusRecord](../emfplusrecord)
* namnutrymme [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records)
* hopsättning [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
