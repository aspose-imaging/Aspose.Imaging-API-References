---
title: EmfPlusSetPageTransform
second_title: Aspose.Imaging för .NET API-referens
description: EmfPlusSetPageTransform-posten anger skalningsfaktorer och enheter för att konvertera sidutrymme -koordinater till enhetsutrymmeskoordinater.
type: docs
weight: 6350
url: /sv/net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetpagetransform/
---
## EmfPlusSetPageTransform class

EmfPlusSetPageTransform-posten anger skalningsfaktorer och enheter för att konvertera sidutrymme -koordinater till enhetsutrymmeskoordinater.

```csharp
public sealed class EmfPlusSetPageTransform : EmfPlusTerminalServerRecordType
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [EmfPlusSetPageTransform](emfplussetpagetransform)(EmfPlusRecord) | Initierar en ny instans av[`EmfPlusSetPageTransform`](../emfplussetpagetransform) class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize) { get; set; } | Hämtar eller ställer in ett 32-bitars osignerat heltal som MÅSTE definiera det 32-bitars-justerade antalet byte med data i RecordData-fältet som följer. Detta nummer inkluderar inte posthuvudet på 12 byte. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags) { get; set; } | Hämtar eller ställer in ett 16-bitars osignerat heltal som innehåller information för vissa poster om hur operationen ska utföras och om postens struktur. |
| [PageScale](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussetpagetransform/pagescale) { get; set; } | Hämtar eller ställer in ett 32-bitars flyttalsvärde som anger skalfaktorn för att konvertera sidutrymmeskoordinater till enhetsutrymmeskoordinater. |
| [PageUnit](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussetpagetransform/pageunit) { get; } | Hämtar måttenheten för sidutrymmeskoordinater, från uppräkningen UnitType (avsnitt 2.1.1.33). Detta värde SKA INTE vara UnitTypeDisplay eller UnitTypeWorld. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size) { get; set; } | Hämtar eller ställer in ett 32-bitars osignerat heltal som anger det 32-bitars justerade antalet bytes i hela posten, inklusive 12-byte posthuvudet och postspecifika data. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type) { get; } | Får ett 16-bitars osignerat heltal som identifierar posttypen. |

### Se även

* class [EmfPlusTerminalServerRecordType](../emfplusterminalserverrecordtype)
* namnutrymme [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records)
* hopsättning [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
