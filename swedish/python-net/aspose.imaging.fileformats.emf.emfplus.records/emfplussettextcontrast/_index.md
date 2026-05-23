---
title: "EmfPlusSetTextContrast klass"
type: docs
weight: 550
url: /sv/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussettextcontrast/
---

**Summary:** The EmfPlusSetTextContrast record specifies text contrast according to the gamma correction value.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusSetTextContrast

**Inheritance:** EmfPlusPropertyRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusSetTextContrast(source)](#EmfPlusSetTextContrast_source_1) | Initierar en ny instans av klassen [EmfPlusSetTextContrast](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussettextcontrast/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| data_size | int | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som MÅSTE definiera det 32-bitars‑justerade antalet<br/>            databytes i RecordData‑fältet som följer. Detta tal inkluderar inte 12‑bytes posthuvudet. |
| flaggor | int | r/w | Hämtar eller anger ett 16-bitars osignerat heltal som innehåller information för vissa poster om hur<br/>            operationen ska utföras och om postens struktur. |
| storlek | int | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar det 32-bitars‑justerade antalet bytes<br/>            i hela posten, inklusive 12‑bytes posthuvudet och post‑specifik data. |
| text_contrast | int | r/w | Hämtar eller anger gamma‑korrektionsvärdet X 1000, som kommer att tillämpas på<br/>            efterföljande textrenderingsoperationer. Tillåtet intervall är 1000 till 2200,<br/>            vilket representerar text‑gamma‑värden på 1,0 till 2,2. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Hämtar ett 16-bitars osignerat heltal som identifierar posttypen. |


### Constructor: EmfPlusSetTextContrast(source) {#EmfPlusSetTextContrast_source_1}


```
 EmfPlusSetTextContrast(source) 
```

Initierar en ny instans av klassen [EmfPlusSetTextContrast](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussettextcontrast/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | Källan. |

