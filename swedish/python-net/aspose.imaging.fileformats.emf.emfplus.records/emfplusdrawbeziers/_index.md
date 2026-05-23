---
title: "EmfPlusDrawBeziers-klass"
type: docs
weight: 80
url: /sv/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawbeziers/
---

**Summary:** The EmfPlusDrawBeziers record specifies drawing a sequence of connected Bezier curves. <br/>            The order for Bezier data points is the start point, control point 1, <br/>            control point 2 and end point. For more information see [MSDN-DrawBeziers].

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawBeziers

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusDrawBeziers(source)](#EmfPlusDrawBeziers_source_1) | Initierar en ny instans av klassen [EmfPlusDrawBeziers](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawbeziers/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| komprimerad | bool | r/w | Hämtar eller anger ett värde som indikerar om PointData är komprimerad. <br/>            Om den är satt specificerar PointData absoluta positioner i koordinatrymden med <br/>            16‑bitars heltalskoordinater. Om den är rensad specificerar PointData absoluta positioner <br/>            i koordinatrymden med 32‑bitars flyttalskoordinater.<br/>            Obs! Om Relative‑flaggan (nedan) är satt är denna flagga odefinierad och MÅSTE ignoreras. |
| data_size | int | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som MÅSTE definiera det 32-bitars‑justerade antalet<br/>            databytes i RecordData‑fältet som följer. Detta tal inkluderar inte 12‑bytes posthuvudet. |
| flaggor | int | r/w | Hämtar eller anger ett 16-bitars osignerat heltal som innehåller information för vissa poster om hur<br/>            operationen ska utföras och om postens struktur. |
| object_id | System.Byte | r/w | Hämtar eller anger objektidentifieraren.<br/>            Indexet för ett EmfPlusPen-objekt (avsnitt 2.2.1.7) i EMF+<br/>            Object Table för att rita Bezier-kurvorna. Värdet MÅSTE vara mellan 0 och 63, inklusive. |
| point_data | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | r/w | Hämtar eller anger punktdata<br/>            En array av Count-punkter som specificerar start-, slut- och kontrollpunkterna för Bezier‑kurvorna. Slutkoordinaten för en Bezier‑kurva är startkoordinaten för nästa. Kontrollpunkterna används för att skapa Bezier‑effekten.<br/>            Datatypen i denna array specificeras av Flags‑fältet, enligt följande: Datatyp Betydelse<br/>            EmfPlusPointR-objekt (avsnitt 2.2.2.37)<br/>            Om P‑flaggan är satt i Flags specificerar punkterna relativa positioner.<br/>            EmfPlusPointF-objekt (avsnitt 2.2.2.36)<br/>            Om P‑ och C‑bitarna är rensade i Flags‑fältet specificerar punkterna absoluta positioner.<br/>            EmfPlusPoint-objekt (avsnitt 2.2.2.35)<br/>            Om P‑biten är rensad och C‑biten är satt i Flags‑fältet specificerar punkterna relativa positioner.<br/>            En Bezier‑kurva passerar inte genom sina kontrollpunkter. Kontrollpunkterna fungerar som |
| relativ | bool | r/w | Hämtar eller anger ett värde som indikerar om PointData är relativt.<br/>            Om angivet, specificerar varje element i PointData en plats i koordinatrymden <br/>            som är relativ till platsen som anges av föregående element i arrayen. <br/>            För det första elementet i PointData antas en föregående plats vid koordinaterna <br/>            (0,0). Om avmarkerat, specificerar PointData absoluta platser enligt <br/>            C flaggan.<br/>            Obs! Om denna flagga är satt är C flaggan (ovan) odefinierad och MÅSTE ignoreras. |
| storlek | int | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar det 32-bitars‑justerade antalet bytes<br/>            i hela posten, inklusive 12‑bytes posthuvudet och post‑specifik data. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Hämtar ett 16-bitars osignerat heltal som identifierar posttypen. |


### Constructor: EmfPlusDrawBeziers(source) {#EmfPlusDrawBeziers_source_1}


```
 EmfPlusDrawBeziers(source) 
```

Initierar en ny instans av klassen [EmfPlusDrawBeziers](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawbeziers/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | Källan. |

