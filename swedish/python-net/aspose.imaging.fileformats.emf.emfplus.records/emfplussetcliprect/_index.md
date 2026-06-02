---
title: "EmfPlusSetClipRect klass"
type: docs
weight: 470
url: /sv/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetcliprect/
---

**Summary:** The EmfPlusSetClipRect record combines the current clipping region with a rectangle.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusSetClipRect

**Inheritance:** EmfPlusClippingRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusSetClipRect(source)](#EmfPlusSetClipRect_source_1) | Initierar en ny instans av klassen [EmfPlusSetClipRect](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetcliprect/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| clip_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r/w | Hämtar eller anger ett EmfPlusRectF-objekt (avsnitt 2.2.2.39) som definierar rektangeln för<br/>            användning i CombineMode‑operationen. |
| cm | [EmfPlusCombineMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluscombinemode/) | r/w | Hämtar eller anger CM (4 bitar): Anger den logiska operationen för att kombinera två regioner. Se den<br/>CombineMode uppräkning (sektion 2.1.1.4) för betydelserna av värdena. |
| data_size | int | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som MÅSTE definiera det 32-bitars‑justerade antalet<br/>            databytes i RecordData‑fältet som följer. Detta tal inkluderar inte 12‑bytes posthuvudet. |
| flaggor | int | r/w | Hämtar eller anger ett 16-bitars osignerat heltal som innehåller information för vissa poster om hur<br/>            operationen ska utföras och om postens struktur. |
| storlek | int | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar det 32-bitars‑justerade antalet bytes<br/>            i hela posten, inklusive 12‑bytes posthuvudet och post‑specifik data. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Hämtar ett 16-bitars osignerat heltal som identifierar posttypen. |


### Constructor: EmfPlusSetClipRect(source) {#EmfPlusSetClipRect_source_1}


```
 EmfPlusSetClipRect(source) 
```

Initierar en ny instans av klassen [EmfPlusSetClipRect](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetcliprect/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | Källan. |

