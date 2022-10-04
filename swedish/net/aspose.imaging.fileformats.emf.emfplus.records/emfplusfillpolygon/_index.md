---
title: EmfPlusFillPolygon
second_title: Aspose.Imaging för .NET API-referens
description: EmfPlusFillPolygon-posten anger fyllning av det inre av en polygon.
type: docs
weight: 6100
url: /sv/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpolygon/
---
## EmfPlusFillPolygon class

EmfPlusFillPolygon-posten anger fyllning av det inre av en polygon.

```csharp
public sealed class EmfPlusFillPolygon : EmfPlusDrawingRecordType
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [EmfPlusFillPolygon](emfplusfillpolygon)(EmfPlusRecord) | Initierar en ny instans av[`EmfPlusFillPolygon`](../emfplusfillpolygon) class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [BrushId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpolygon/brushid) { get; set; } | Hämtar eller ställer in penselidentifieraren Ett 32-bitars osignerat heltal som definierar penseln, vars innehåll bestäms av S-biten i fältet Flaggor. |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize) { get; set; } | Hämtar eller ställer in ett 32-bitars osignerat heltal som MÅSTE definiera det 32-bitars-justerade antalet byte med data i RecordData-fältet som följer. Detta nummer inkluderar inte posthuvudet på 12 byte. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags) { get; set; } | Hämtar eller ställer in ett 16-bitars osignerat heltal som innehåller information för vissa poster om hur operationen ska utföras och om postens struktur. |
| [IsColor](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpolygon/iscolor) { get; set; } | Hämtar eller ställer in ett värde som indikerar om denna instans är färg. Om den är inställd anger BrushId en färg som ett EmfPlusARGB-objekt (avsnitt 2.2.2.1). Om den är ren, innehåller BrushId indexet för ett EmfPlusBrush-objekt (avsnitt 2.2.1.1) i EMF+-objekttabellen. |
| [IsCompressed](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpolygon/iscompressed) { get; set; } | Hämtar eller ställer in ett värde som indikerar om denna instans är komprimerad. Om angivet, anger PointData absoluta platser i koordinatutrymmet med 16-bitars heltalskoordinater. Om den är ren, specificerar PointData absoluta platser i koordinatutrymmet med 32-bitars flyttalskoordinater |
| [IsRelative](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpolygon/isrelative) { get; set; } | Hämtar eller ställer in ett värde som anger om denna instans är relativ. Om den är inställd, anger varje element i PointData en plats i koordinatutrymmet som är relativt platsen som specificerats av det föregående elementet i arrayen. I fallet med det första elementet i PointData antas en tidigare plats vid koordinater (0,0). Om den är ren, specificerar PointData absoluta platser enligt C-flaggan |
| [PointData](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpolygon/pointdata) { get; set; } | Hämtar eller ställer in punktdata En matris med Räknepunkter som definierar polygonens hörn. De två första punkterna i arrayen anger den första sidan av polygonen. Varje ytterligare punkt specificerar en ny sida, vars hörn inkluderar punkten och föregående punkt. Om den sista punkten och den första punkten inte sammanfaller, anger de den sista sidan av polygonen. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size) { get; set; } | Hämtar eller ställer in ett 32-bitars osignerat heltal som anger det 32-bitars justerade antalet bytes i hela posten, inklusive 12-byte posthuvudet och postspecifika data. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type) { get; } | Får ett 16-bitars osignerat heltal som identifierar posttypen. |

### Se även

* class [EmfPlusDrawingRecordType](../emfplusdrawingrecordtype)
* namnutrymme [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records)
* hopsättning [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->