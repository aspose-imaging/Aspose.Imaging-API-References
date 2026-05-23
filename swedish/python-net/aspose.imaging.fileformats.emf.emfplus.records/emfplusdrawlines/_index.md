---
title: "EmfPlusDrawLines klass"
type: docs
weight: 150
url: /sv/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawlines/
---

**Summary:** The EmfPlusDrawlLines record specifies drawing a series of connected lines

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawLines

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusDrawLines(source)](#EmfPlusDrawLines_source_1) | Initierar en ny instans av klassen [EmfPlusDrawLines](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawlines/) klass. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| closed_shape | bool | r/w | Hämtar eller anger ett värde som indikerar om [closed shape]. |
| compressed | bool | r/w | Hämtar eller anger ett värde som indikerar om detta [EmfPlusDrawClosedCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/) är komprimerat.<br/>            Denna bit indikerar om PointData-fältet specificerar komprimerad data.<br/>            Om satt, specificerar PointData absoluta positioner i koordinatrymden med 16‑bitars heltalskoordinater. <br/>            Om rensad, specificerar PointData absoluta positioner i koordinatrymden med 32‑bitars flyttalskoordinater<br/>            Obs! Om Relative‑flaggan (nedan) är satt, är denna flagga odefinierad och MÅSTE ignoreras |
| data_size | int | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som MÅSTE definiera det 32-bitars‑justerade antalet<br/>            databytes i RecordData‑fältet som följer. Detta tal inkluderar inte 12‑bytes posthuvudet. |
| flaggor | int | r/w | Hämtar eller anger ett 16-bitars osignerat heltal som innehåller information för vissa poster om hur<br/>            operationen ska utföras och om postens struktur. |
| object_id | System.Byte | r/w | Hämtar eller anger objektidentifieraren.<br/>            Indexet för ett EmfPlusPen-objekt (avsnitt 2.2.1.7) i EMF+<br/>            objekttabell för att rita linjerna. Värdet MÅSTE vara mellan 0 och 63, inklusive. |
| point_data | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | r/w | Hämtar eller anger punktdata<br/>            En array av Count-punkter som specificerar start- och slutpunkterna för de linjer som ska ritas. |
| relative | bool | r/w | Hämtar eller anger ett värde som indikerar om detta [EmfPlusDrawClosedCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/) är relativt.<br/>            Denna bit indikerar om PointData-fältet specificerar relativa eller absoluta positioner.<br/>            Om satt, specificerar varje element i PointData en position i koordinatrymden som är relativ <br/>            till positionen som anges av föregående element i arrayen. För det första <br/>            elementet i PointData antas en föregående position med koordinater (0,0). Om rensad, <br/>            specificerar PointData absoluta positioner enligt C-flaggan.<br/>            Obs! Om denna flagga är satt, är Compressed-flaggan (ovan) odefinierad och MÅSTE ignoreras |
| storlek | int | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar det 32-bitars‑justerade antalet bytes<br/>            i hela posten, inklusive 12‑bytes posthuvudet och post‑specifik data. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Hämtar ett 16-bitars osignerat heltal som identifierar posttypen. |


### Constructor: EmfPlusDrawLines(source) {#EmfPlusDrawLines_source_1}


```
 EmfPlusDrawLines(source) 
```

Initierar en ny instans av klassen [EmfPlusDrawLines](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawlines/) klass.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | Källan. |

