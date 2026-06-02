---
title: "EmfPlusFillEllipse-klass"
type: docs
weight: 240
url: /sv/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillellipse/
---

**Summary:** The EmfPlusFillEllipse record specifies filling the interior of an ellipse

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusFillEllipse

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusFillEllipse(source)](#EmfPlusFillEllipse_source_1) | Initierar en ny instans av klassen [EmfPlusFillEllipse](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillellipse/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| brush_id | int | r/w | Hämtar eller anger penselidentifieraren<br/>            Ett 32‑bitars osignerat heltal som specificerar penseln, vars innehåll<br/>            bestäms av S‑bit i Flags‑fältet. Denna definition används <br/>            för att fylla ellipsens insida. |
| data_size | int | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som MÅSTE definiera det 32-bitars‑justerade antalet<br/>            databytes i RecordData‑fältet som följer. Detta tal inkluderar inte 12‑bytes posthuvudet. |
| flaggor | int | r/w | Hämtar eller anger ett 16-bitars osignerat heltal som innehåller information för vissa poster om hur<br/>            operationen ska utföras och om postens struktur. |
| is_color | bool | r/w | Hämtar eller anger ett värde som indikerar om denna instans är färg.<br/>            Om satt, specificerar BrushId en färg som ett EmfPlusARGB-objekt (avsnitt 2.2.2.1).<br/>            Om rensad, innehåller BrushId indexet för ett EmfPlusBrush-objekt <br/>            (avsnitt 2.2.1.1) i EMF+ objekt-tabellen. |
| is_compressed | bool | r/w | Hämtar eller anger ett värde som indikerar om denna instans är komprimerad.<br/>            Om den är satt innehåller RectData ett EmfPlusRect-objekt (avsnitt 2.2.2.38). <br/>            Om den är rensad innehåller RectData ett EmfPlusRectF-objekt (avsnitt 2.2.2.39). |
| rect_data | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r/w | Hämtar eller anger rektangeldata<br/>            Antingen ett EmfPlusRect- eller EmfPlusRectF-objekt som definierar den omgivande rutan för ellipsen |
| storlek | int | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar det 32-bitars‑justerade antalet bytes<br/>            i hela posten, inklusive 12‑bytes posthuvudet och post‑specifik data. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Hämtar ett 16-bitars osignerat heltal som identifierar posttypen. |


### Constructor: EmfPlusFillEllipse(source) {#EmfPlusFillEllipse_source_1}


```
 EmfPlusFillEllipse(source) 
```

Initierar en ny instans av klassen [EmfPlusFillEllipse](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillellipse/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | Källan. |

