---
title: EmfPlusHeader
second_title: Aspose.Imaging för .NET API-referens
description: EmfPlusHeader-posten anger starten av EMF-data i metafilen. EmfPlusHeader-posten MÅSTE vara inbäddad i en EMF EMR_COMMENT_EMFPLUS-post som MÅSTE vara posten omedelbart efter EMF-huvudet i metafilen. EMR_COMMENT_EMFPLUS-posten specificeras i MS-EMF avsnitt 2.3.3.2.
type: docs
weight: 6140
url: /sv/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/
---
## EmfPlusHeader class

EmfPlusHeader-posten anger starten av EMF+-data i metafilen. EmfPlusHeader-posten MÅSTE vara inbäddad i en EMF EMR_COMMENT_EMFPLUS-post, som MÅSTE vara posten omedelbart efter EMF-huvudet i metafilen. EMR_COMMENT_EMFPLUS-posten specificeras i [MS-EMF] avsnitt 2.3.3.2.

```csharp
public sealed class EmfPlusHeader : EmfPlusControlRecordType
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [EmfPlusHeader](emfplusheader)(EmfPlusRecord) | Initierar en ny instans av[`EmfPlusHeader`](../emfplusheader) class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize) { get; set; } | Hämtar eller ställer in ett 32-bitars osignerat heltal som MÅSTE definiera det 32-bitars-justerade antalet byte med data i RecordData-fältet som följer. Detta nummer inkluderar inte posthuvudet på 12 byte. |
| [DualMode](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/dualmode) { get; set; } | Hämtar eller ställer in ett värde som indikerar om [dual mode]. Om den är inställd indikerar denna flagga att denna metafil är "dual-mode", vilket betyder att den innehåller två uppsättningar poster, som var och en helt specificerar grafikinnehållet. Om det är klart specificeras grafikinnehållet av EMF+ -poster, och möjligen EMF-poster som föregås av en EmfPlusGetDC-post. Om denna flagga är inställd, BÖR endast EMF-poster vara tillräckliga för att definiera grafikinnehållet. Observera att oavsett om "dual-mode"-flaggan är inställd eller inte, finns alltid vissa EMF-poster närvarande, nämligen EMF-kontrollposter och EMF-posterna som innehåller EMF+-poster. EMF-kontrollposter specificeras i [MS-EMF] avsnitt 2.3.4. |
| [EmfPlusFlags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/emfplusflags) { get; set; } | Hämtar eller ställer in EMF plus-flaggor. Ett 32-bitars osignerat heltal som innehåller information om hur denna metafil registrerades. om den 31:a biten av fältet är inställd, indikerar denna flagga att metafilen registrerades med en referens enhetskontext för en videoskärm. Om den är ren, spelades metafilen in med en referensenhetskontext för en skrivare. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags) { get; set; } | Hämtar eller ställer in ett 16-bitars osignerat heltal som innehåller information för vissa poster om hur operationen ska utföras och om postens struktur. |
| [IsValid](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/isvalid) { get; } | Får ett värde som indikerar om denna instans är giltig. |
| [LogicalDpiX](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/logicaldpix) { get; set; } | Hämtar eller ställer in den logiska dpi x. Ett 32-bitars heltal utan tecken som anger den horisontella upplösningen för vilken metafilen spelades in, i enheter av pixlar per tum. |
| [LogicalDpiY](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/logicaldpiy) { get; set; } | Hämtar eller ställer in den logiska dpi y. Ett 32-bitars heltal utan tecken som anger den vertikala upplösningen för vilken metafilen registrerades, i enheter av linjer per tum |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size) { get; set; } | Hämtar eller ställer in ett 32-bitars osignerat heltal som anger det 32-bitars justerade antalet bytes i hela posten, inklusive 12-byte posthuvudet och postspecifika data. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type) { get; } | Får ett 16-bitars osignerat heltal som identifierar posttypen. |
| [Version](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/version) { get; set; } | Hämtar eller ställer in versionen. Ett EmfPlusGraphicsVersion-objekt (avsnitt 2.2.2.19) som anger versionen av operativsystemet systemgrafik som användes för att skapa denna metafil. |
| [VideoDisplay](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/videodisplay) { get; set; } | Hämtar eller ställer in ett värde som anger om videovisning. är inställd, denna flagga indikerar att metafilen spelades in med en referens device -kontext för en videovisning. Om den är ren, spelades metafilen in med en referens device -kontext för en skrivare. |

### Se även

* class [EmfPlusControlRecordType](../emfpluscontrolrecordtype)
* namnutrymme [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records)
* hopsättning [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
