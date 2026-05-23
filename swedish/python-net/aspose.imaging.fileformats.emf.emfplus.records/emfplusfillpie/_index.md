---
title: "EmfPlusFillPie-klass"
type: docs
weight: 260
url: /sv/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpie/
---

**Summary:** The EmfPlusFillPie record specifies filling a section of the interior of an ellipse

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusFillPie

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusFillPie(source)](#EmfPlusFillPie_source_1) | Initierar en ny instans av klassen [EmfPlusFillPie](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpie/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| brush_id | int | r/w | Hämtar eller anger borstidentifieraren<br/>            Ett 32-bitars osignerat heltal som definierar borsten, vars innehåll <br/>            bestäms av S-biten i Flags-fältet. |
| komprimerad | bool | r/w | Hämtar eller anger ett värde som indikerar om PointData är komprimerad.<br/>            Om satt innehåller RectData ett EmfPlusRect-objekt (avsnitt 2.2.2.38).<br/>            Om rensad innehåller RectData ett EmfPlusRectF-objekt (avsnitt 2.2.2.39). |
| data_size | int | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som MÅSTE definiera det 32-bitars‑justerade antalet<br/>            databytes i RecordData‑fältet som följer. Detta tal inkluderar inte 12‑bytes posthuvudet. |
| flaggor | int | r/w | Hämtar eller anger ett 16-bitars osignerat heltal som innehåller information för vissa poster om hur<br/>            operationen ska utföras och om postens struktur. |
| is_color | bool | r/w | Hämtar eller anger ett värde som indikerar om denna instans är färg.<br/>Om satt, specificerar BrushId en färg som ett EmfPlusARGB-objekt (sektion 2.2.2.1).<br/>Om rensad, innehåller BrushId indexet för ett EmfPlusBrush-objekt (sektion 2.2.1.1) i EMF+ Object Table. |
| rect_data | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r/w | Hämtar eller anger rektangeldata<br/> Antingen ett EmfPlusRect- eller EmfPlusRectF-objekt som definierar den omgivande rutan för <br/> ellipsen som innehåller pajbiten. Denna rektangel definierar position, storlek, <br/> och form på pajen. Typen av objekt i detta fält anges av värdet <br/> i Flags-fältet. |
| storlek | int | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar det 32-bitars‑justerade antalet bytes<br/>            i hela posten, inklusive 12‑bytes posthuvudet och post‑specifik data. |
| start_angle | float | r/w | Hämtar eller anger startvinkeln<br/> Ett 32-bitars, icke-negativt flyttal som specificerar vinkeln mellan <br/> x-axeln och startpunkten för pajbiten. Alla värden är acceptabla, men det <br/> MÅSTE tolkas modulo 360, där resultatet som används ligger i intervallet <br/> 0.0 inklusivt till 360.0 exklusivt. |
| sweep_angle | float | r/w | Hämtar eller anger svevvinkeln<br/> Ett 32-bitars flyttal som specificerar omfattningen av den båge som definierar <br/> pajbiten att rita, som en vinkel i grader mätt från startpunkten <br/> definierad av StartAngle-värdet. Alla värden är acceptabla, men det MÅSTE begränsas <br/> till -360.0 till 360.0 inklusivt. Ett positivt värde indikerar att sveven är definierad <br/> i medurs riktning, och ett negativt värde indikerar att sveven är definierad <br/> i moturs riktning. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Hämtar ett 16-bitars osignerat heltal som identifierar posttypen. |


### Constructor: EmfPlusFillPie(source) {#EmfPlusFillPie_source_1}


```
 EmfPlusFillPie(source) 
```

Initierar en ny instans av klassen [EmfPlusFillPie](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpie/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | Källan. |

