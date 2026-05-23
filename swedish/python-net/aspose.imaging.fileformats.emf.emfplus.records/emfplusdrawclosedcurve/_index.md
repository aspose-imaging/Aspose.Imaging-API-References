---
title: "EmfPlusDrawClosedCurve-klass"
type: docs
weight: 90
url: /sv/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/
---

**Summary:** The EmfPlusDrawClosedCurve record specifies drawing a closed cardinal spline

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawClosedCurve

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusDrawClosedCurve(source)](#EmfPlusDrawClosedCurve_source_1) | Initierar en ny instans av klassen [EmfPlusDrawClosedCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/).<br/>            RecordType – Ett 16-bitars osignerat heltal som identifierar denna posttyp som EmfPlusDrawClosedCurve<br/>            från RecordType‑enumerationen (avsnitt 2.1.1.1). Värdet MÅSTE vara 0x4017. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| compressed | bool | r/w | Hämtar eller anger ett värde som indikerar om detta [EmfPlusDrawClosedCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/) är komprimerat.<br/>            Denna bit indikerar om PointData-fältet specificerar komprimerad data.<br/>            Om satt, specificerar PointData absoluta positioner i koordinatrymden med 16‑bitars heltalskoordinater. <br/>            Om rensad, specificerar PointData absoluta positioner i koordinatrymden med 32‑bitars flyttalskoordinater<br/>            Obs! Om Relative‑flaggan (nedan) är satt, är denna flagga odefinierad och MÅSTE ignoreras |
| data_size | int | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som MÅSTE definiera det 32-bitars‑justerade antalet<br/>            databytes i RecordData‑fältet som följer. Detta tal inkluderar inte 12‑bytes posthuvudet. |
| flaggor | int | r/w | Hämtar eller anger ett 16-bitars osignerat heltal som innehåller information för vissa poster om hur<br/>            operationen ska utföras och om postens struktur. |
| object_id | System.Byte | r/w | Hämtar eller anger objektidentifieraren.<br/>            Indexet för ett EmfPlusPen-objekt (avsnitt 2.2.1.7) i EMF+<br/>            Object Table för att rita den slutna kurvan. Värdet MÅSTE vara 0 till 63, inklusive. |
| point_data | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | r/w | Hämtar eller anger punktdata<br/>            En array av Count-punkter som specificerar ändpunkterna för linjerna som definierar spline. I en sluten kardinal spline, <br/>            fortsätter kurvan genom den sista punkten i PointData-arrayen och ansluter till den första punkten i arrayen.<br/>            Datatypen i denna array specificeras av Flags-fältet, enligt följande: Datatyp Betydelse<br/>            EmfPlusPointR-objekt (avsnitt 2.2.2.37)<br/>            Om P-flaggan är satt i Flags, specificerar punkterna relativa positioner.<br/>            EmfPlusPointF-objekt (avsnitt 2.2.2.36)<br/>            Om P- och C-bitarna är satta i Flags-fältet, specificerar punkterna absoluta positioner.<br/>            EmfPlusPoint-objekt (avsnitt 2.2.2.35)<br/>            Om P-biten är rensad och C-biten är satt i Flags-fältet, specificerar punkterna relativa positioner. |
| relative | bool | r/w | Hämtar eller anger ett värde som indikerar om detta [EmfPlusDrawClosedCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/) är relativt.<br/>            Denna bit indikerar om PointData-fältet specificerar relativa eller absoluta positioner.<br/>            Om satt, specificerar varje element i PointData en position i koordinatrymden som är relativ <br/>            till positionen som anges av föregående element i arrayen. För det första <br/>            elementet i PointData antas en föregående position med koordinater (0,0). Om rensad, <br/>            specificerar PointData absoluta positioner enligt C-flaggan.<br/>            Obs! Om denna flagga är satt, är Compressed-flaggan (ovan) odefinierad och MÅSTE ignoreras |
| storlek | int | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar det 32-bitars‑justerade antalet bytes<br/>            i hela posten, inklusive 12‑bytes posthuvudet och post‑specifik data. |
| spänning | float | r/w | Hämtar eller anger spänningen<br/>            Ett 32-bitars flyttal som specificerar hur hårt spline <br/>            böjer sig när den passerar genom punkterna. Ett värde på 0 anger att <br/>            spline är en sekvens av raka linjer. När värdet ökar, <br/>            blir kurvan mer rundad. För mer information, se [SPLINE77] och [PETZOLD]. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Hämtar ett 16-bitars osignerat heltal som identifierar posttypen. |


### Constructor: EmfPlusDrawClosedCurve(source) {#EmfPlusDrawClosedCurve_source_1}


```
 EmfPlusDrawClosedCurve(source) 
```

Initierar en ny instans av klassen [EmfPlusDrawClosedCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/).<br/>            RecordType – Ett 16-bitars osignerat heltal som identifierar denna posttyp som EmfPlusDrawClosedCurve<br/>            från RecordType‑enumerationen (avsnitt 2.1.1.1). Värdet MÅSTE vara 0x4017.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | Källan. |

