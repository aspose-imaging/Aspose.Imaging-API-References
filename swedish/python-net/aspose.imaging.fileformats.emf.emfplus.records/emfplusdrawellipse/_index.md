---
title: "EmfPlusDrawEllipse klass"
type: docs
weight: 120
url: /sv/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawellipse/
---

**Summary:** The EmfPlusDrawEllipse record specifies drawing an ellipse.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawEllipse

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusDrawEllipse(source)](#EmfPlusDrawEllipse_source_1) | Initierar en ny instans av [EmfPlusDrawEllipse](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawellipse/) klass. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| komprimerad | bool | r/w | Hämtar eller anger ett värde som indikerar om PointData är komprimerad. <br/>            Om satt, innehåller RectData ett EmfPlusRect-objekt (avsnitt 2.2.2.38). <br/>            Om rensad, innehåller RectData ett EmfPlusRectF-objekt (avsnitt 2.2.2.39). |
| data_size | int | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som MÅSTE definiera det 32-bitars‑justerade antalet<br/>            databytes i RecordData‑fältet som följer. Detta tal inkluderar inte 12‑bytes posthuvudet. |
| flaggor | int | r/w | Hämtar eller anger ett 16-bitars osignerat heltal som innehåller information för vissa poster om hur<br/>            operationen ska utföras och om postens struktur. |
| object_id | System.Byte | r/w | Hämtar eller anger objektidentifieraren.<br/>            Indexet för ett EmfPlusPen‑objekt (avsnitt 2.2.1.7) i EMF+<br/>            objekttabellen för att rita ellipsen. Värdet MÅSTE vara 0 till 63, inklusive. |
| rect_data | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r/w | Hämtar eller anger rektangeldata<br/>            Antingen ett EmfPlusRect‑ eller EmfPlusRectF‑objekt som definierar ellipsens omgivningsruta. |
| storlek | int | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar det 32-bitars‑justerade antalet bytes<br/>            i hela posten, inklusive 12‑bytes posthuvudet och post‑specifik data. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Hämtar ett 16-bitars osignerat heltal som identifierar posttypen. |


### Constructor: EmfPlusDrawEllipse(source) {#EmfPlusDrawEllipse_source_1}


```
 EmfPlusDrawEllipse(source) 
```

Initierar en ny instans av [EmfPlusDrawEllipse](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawellipse/) klass.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | Källan. |

