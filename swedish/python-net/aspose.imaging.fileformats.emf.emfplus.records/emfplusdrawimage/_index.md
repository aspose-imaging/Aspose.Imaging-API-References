---
title: "EmfPlusDrawImage klass"
type: docs
weight: 130
url: /sv/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimage/
---

**Summary:** The EmfPlusDrawImage record specifies drawing a scaled image.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawImage

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusDrawImage(source)](#EmfPlusDrawImage_source_1) | Initierar en ny instans av [EmfPlusDrawImage](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimage/) klass. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| komprimerad | bool | r/w | Hämtar eller anger ett värde som indikerar om PointData är komprimerad.<br/>            Om satt innehåller RectData ett EmfPlusRect-objekt (avsnitt 2.2.2.38).<br/>            Om rensad innehåller RectData ett EmfPlusRectF-objekt (avsnitt 2.2.2.39). |
| data_size | int | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som MÅSTE definiera det 32-bitars‑justerade antalet<br/>            databytes i RecordData‑fältet som följer. Detta tal inkluderar inte 12‑bytes posthuvudet. |
| flaggor | int | r/w | Hämtar eller anger ett 16-bitars osignerat heltal som innehåller information för vissa poster om hur<br/>            operationen ska utföras och om postens struktur. |
| image_attributes_id | int | r/w | Hämtar eller anger bildattributens identifierare<br/>            En 32-bitars osignerad heltal som specificerar indexet för ett valfritt EmfPlusImageAttributes-objekt (avsnitt 2.2.1.5) i EMF+ objekttabell. |
| object_id | System.Byte | r/w | Hämtar eller anger objektidentifieraren.<br/>            Indexet för ett EmfPlusImage-objekt (avsnitt 2.2.1.4) i EMF+<br/>            Object Table, som specificerar bilden som ska renderas. Värdet MÅSTE vara mellan 0 och 63, inklusive. |
| rect_data | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r/w | Hämtar eller anger rektangeldata<br/>            Antingen ett EmfPlusRect- eller EmfPlusRectF-objekt som definierar bildens omgivningsruta.<br/>            Den del av bilden som anges av SrcRect-fältet skalas för att passa denna rektangel. |
| storlek | int | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar det 32-bitars‑justerade antalet bytes<br/>            i hela posten, inklusive 12‑bytes posthuvudet och post‑specifik data. |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r/w | Hämtar eller anger källrektangeln<br/>            Ett EmfPlusRectF-objekt som specificerar en del av bilden som ska renderas.<br/>            Den del av bilden som anges av denna rektangel skalas för att passa destinations‑<br/>            rektangeln som anges av RectData-fältet. |
| src_unit | [EmfPlusUnitType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusunittype/) | r/w | Hämtar eller anger källenheten<br/>            32-bitars signerat heltal som specificerar enheterna för SrcRect-fältet.<br/>            Det MÅSTE vara UnitTypePixel-medlemmen i UnitType‑enumerationen (avsnitt 2.1.1.33). |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Hämtar ett 16-bitars osignerat heltal som identifierar posttypen. |


### Constructor: EmfPlusDrawImage(source) {#EmfPlusDrawImage_source_1}


```
 EmfPlusDrawImage(source) 
```

Initierar en ny instans av [EmfPlusDrawImage](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimage/) klass.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | Källan. |

