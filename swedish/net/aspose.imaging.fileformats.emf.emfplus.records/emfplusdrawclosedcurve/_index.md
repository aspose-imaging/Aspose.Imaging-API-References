---
title: EmfPlusDrawClosedCurve
second_title: Aspose.Imaging för .NET API-referens
description: EmfPlusDrawClosedCurve-posten anger att rita en stängd kardinalspline
type: docs
weight: 5920
url: /sv/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/
---
## EmfPlusDrawClosedCurve class

EmfPlusDrawClosedCurve-posten anger att rita en stängd kardinalspline

```csharp
public sealed class EmfPlusDrawClosedCurve : EmfPlusDrawingRecordType
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [EmfPlusDrawClosedCurve](emfplusdrawclosedcurve)(EmfPlusRecord) | Initierar en ny instans av[`EmfPlusDrawClosedCurve`](../emfplusdrawclosedcurve) class. RecordType - Ett 16-bitars osignerat heltal som identifierar denna posttyp som EmfPlusDrawClosedCurve från RecordType-uppräkningen (avsnitt 2.1.1.1). Värdet MÅSTE vara 0x4017. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Compressed](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/compressed) { get; set; } | Hämtar eller ställer in ett värde som indikerar om detta[`EmfPlusDrawClosedCurve`](../emfplusdrawclosedcurve)är komprimerad. Denna bit indikerar om PointData-fältet specificerar komprimerad data. Om den är inställd, specificerar PointData absoluta platser i koordinatutrymmet med 16-bitars heltalskoordinater. Om den är ren, specificerar PointData absoluta platser i koordinatutrymmet med 32-bitars flyttalskoordinater Obs! Om den relativa flaggan (nedan) är inställd är denna flagga odefinierad och MÅSTE ignoreras |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize) { get; set; } | Hämtar eller ställer in ett 32-bitars osignerat heltal som MÅSTE definiera det 32-bitars-justerade antalet byte med data i RecordData-fältet som följer. Detta nummer inkluderar inte posthuvudet på 12 byte. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags) { get; set; } | Hämtar eller ställer in ett 16-bitars osignerat heltal som innehåller information för vissa poster om hur operationen ska utföras och om postens struktur. |
| [ObjectId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/objectid) { get; set; } | Hämtar eller ställer in objektidentifieraren. Indexet för ett EmfPlusPen-objekt (avsnitt 2.2.1.7) i EMF+ Objekttabellen för att rita den stängda kurvan. Värdet MÅSTE vara noll till 63, inklusive. |
| [PointData](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/pointdata) { get; set; } | Hämtar eller ställer in punktdata En matris med Räknepunkter som anger ändpunkterna för linjerna som definierar spline. I en sluten kardinal spline, fortsätter kurvan genom den sista punkten i PointData-matrisen och ansluter till den första punkten i matrisen. Typen av data i denna matris specificeras av Flags-fältet, enligt följande: Data Type Meaning EmfPlusPointR objekt (avsnitt 2.2.2.37) Om P-flaggan är inställd i flaggorna anger punkterna relativa platser. EmfPlusPointF-objekt (avsnitt 2.2.2.36) Om P- och C-bitarna är inställda i fältet Flaggor anger punkterna absolute locations. EmfPlusPoint-objekt (avsnitt 2.2.2.35) Om P-biten är ren och C-biten är inställd i fältet Flags, anger punkterna relativa platser. |
| [Relative](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/relative) { get; set; } | Hämtar eller ställer in ett värde som indikerar om detta[`EmfPlusDrawClosedCurve`](../emfplusdrawclosedcurve)är relativ. Den här biten indikerar om PointData-fältet anger relativa eller absoluta platser. Om inställt anger varje element i PointData en plats i koordinatutrymmet som är relativ till den plats som specificerats av föregående element i arrayen. I fallet med det första elementet i PointData antas en tidigare plats vid koordinater (0,0). Om den är ren, anger PointData absoluta platser enligt C-flaggan. Obs! Om denna flagga är inställd är den komprimerade flaggan (ovan) odefinierad och MÅSTE ignoreras |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size) { get; set; } | Hämtar eller ställer in ett 32-bitars osignerat heltal som anger det 32-bitars justerade antalet bytes i hela posten, inklusive 12-byte posthuvudet och postspecifika data. |
| [Tension](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/tension) { get; set; } | Hämtar eller ställer in spänningen Ett 32-bitars flyttalnummer som anger hur hårt splinen böjs när den passerar genom punkterna. Ett värde på 0 anger att spline är en sekvens av räta linjer. När värdet ökar, blir kurvan mer avrundad. För mer information, se [SPLINE77] och [PETZOLD]. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type) { get; } | Får ett 16-bitars osignerat heltal som identifierar posttypen. |

### Se även

* class [EmfPlusDrawingRecordType](../emfplusdrawingrecordtype)
* namnutrymme [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records)
* hopsättning [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
