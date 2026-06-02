---
title: "EmfPlusDrawCurve klass"
type: docs
weight: 100
url: /sv/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawcurve/
---

**Summary:** The EmfPlusDrawCurve record specifies drawing a cardinal spline<br/>            NOTE: ObjectID (1 byte): The index of an EmfPlusPen object (section 2.2.1.7)<br/>             in the EMF+ Object Table to draw the curve. The value MUST be zero to 63, inclusive.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawCurve

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusDrawCurve(source)](#EmfPlusDrawCurve_source_1) | Initierar en ny instans av [EmfPlusDrawCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawcurve/) klass. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| compressed | bool | r/w | Hämtar eller anger ett värde som indikerar om detta [EmfPlusDrawClosedCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/) är komprimerat.<br/>            Denna bit indikerar om PointData-fältet specificerar komprimerad data.<br/>            Om satt, specificerar PointData absoluta positioner i koordinatrymden med 16‑bitars heltalskoordinater. <br/>            Om rensad, specificerar PointData absoluta positioner i koordinatrymden med 32‑bitars flyttalskoordinater<br/>            Obs! Om Relative‑flaggan (nedan) är satt, är denna flagga odefinierad och MÅSTE ignoreras |
| data_size | int | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som MÅSTE definiera det 32-bitars‑justerade antalet<br/>            databytes i RecordData‑fältet som följer. Detta tal inkluderar inte 12‑bytes posthuvudet. |
| flaggor | int | r/w | Hämtar eller anger ett 16-bitars osignerat heltal som innehåller information för vissa poster om hur<br/>            operationen ska utföras och om postens struktur. |
| num_segments | int | r/w | Hämtar eller anger segmentantalet <br/>            En 32-bitars osignerad heltal som specificerar antalet linjesegment som utgör spline:n. |
| object_id | System.Byte | r/w | Hämtar eller anger objektidentifieraren.<br/>            Index för ett EmfPlusPen-objekt (avsnitt 2.2.1.7) i EMF+<br/>            objekttabell för att rita kurvan. Värdet MÅSTE vara mellan 0 och 63, inklusive. |
| point_data | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | r/w | Hämtar eller anger en array av antingen 32-bitars signerade heltal eller 32-bitars flyttal av <br/>            Count-längd som definierar koordinatvärden för linjernas ändpunkter som ska ritas. |
| storlek | int | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar det 32-bitars‑justerade antalet bytes<br/>            i hela posten, inklusive 12‑bytes posthuvudet och post‑specifik data. |
| spänning | float | r/w | Hämtar eller anger spänningen<br/>            Ett 32-bitars flyttal som specificerar hur hårt spline <br/>            böjer sig när den passerar genom punkterna. Ett värde på 0 anger att <br/>            spline är en sekvens av raka linjer. När värdet ökar, <br/>            blir kurvan mer rundad. För mer information, se [SPLINE77] och [PETZOLD]. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Hämtar ett 16-bitars osignerat heltal som identifierar posttypen. |


### Constructor: EmfPlusDrawCurve(source) {#EmfPlusDrawCurve_source_1}


```
 EmfPlusDrawCurve(source) 
```

Initierar en ny instans av [EmfPlusDrawCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawcurve/) klass.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | Källan. |

