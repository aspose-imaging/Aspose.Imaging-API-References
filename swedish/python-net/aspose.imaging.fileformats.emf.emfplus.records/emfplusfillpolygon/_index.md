---
title: "EmfPlusFillPolygon klass"
type: docs
weight: 270
url: /sv/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpolygon/
---

**Summary:** The EmfPlusFillPolygon record specifies filling the interior of a polygon.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusFillPolygon

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusFillPolygon(source)](#EmfPlusFillPolygon_source_1) | Initierar en ny instans av [EmfPlusFillPolygon](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpolygon/) klass. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| brush_id | int | r/w | Hämtar eller anger borstidentifieraren<br/>Ett 32-bitars osignerat heltal som definierar borsten, vars innehåll<br/>bestäms av S-bit i Flags-fältet. |
| data_size | int | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som MÅSTE definiera det 32-bitars‑justerade antalet<br/>            databytes i RecordData‑fältet som följer. Detta tal inkluderar inte 12‑bytes posthuvudet. |
| flaggor | int | r/w | Hämtar eller anger ett 16-bitars osignerat heltal som innehåller information för vissa poster om hur<br/>            operationen ska utföras och om postens struktur. |
| is_color | bool | r/w | Hämtar eller anger ett värde som indikerar om denna instans är färg.<br/>Om satt, specificerar BrushId en färg som ett EmfPlusARGB-objekt (sektion 2.2.2.1).<br/>Om rensad, innehåller BrushId indexet för ett EmfPlusBrush-objekt (sektion 2.2.1.1) i EMF+ Object Table. |
| is_compressed | bool | r/w | Hämtar eller anger ett värde som indikerar om denna instans är komprimerad.<br/>Om satt, specificerar PointData absoluta positioner i koordinatrymden med 16-bitars<br/>heltalskoordinater. Om rensad, specificerar PointData absoluta positioner i koordinat<br/>rymden med 32-bitars flyttalskoordinater. |
| is_relative | bool | r/w | Hämtar eller anger ett värde som indikerar om denna instans är relativ.<br/>Om satt, specificerar varje element i PointData en plats i koordinat<br/>rymden som är relativ till platsen som angavs av föregående element<br/>i arrayen. För det första elementet i PointData antas en föregående<br/>plats med koordinater (0,0). Om rensad, specificerar PointData<br/>absoluta platser enligt C-flaggan. |
| point_data | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | r/w | Hämtar eller anger punktdata<br/>En array av Count-punkter som definierar polygonens hörn.<br/>De två första punkterna i arrayen anger den första sidan av polygonen.<br/>Varje ytterligare punkt anger en ny sida, vars hörn<br/>inkluderar punkten och föregående punkt. Om den sista punkten och den<br/>första punkten inte sammanfaller, anger de den sista sidan av polygonen. |
| storlek | int | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar det 32-bitars‑justerade antalet bytes<br/>            i hela posten, inklusive 12‑bytes posthuvudet och post‑specifik data. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Hämtar ett 16-bitars osignerat heltal som identifierar posttypen. |


### Constructor: EmfPlusFillPolygon(source) {#EmfPlusFillPolygon_source_1}


```
 EmfPlusFillPolygon(source) 
```

Initierar en ny instans av [EmfPlusFillPolygon](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpolygon/) klass.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | Källan. |

