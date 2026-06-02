---
title: "EmfPlusSetWorldTransform Class"
type: docs
weight: 590
url: /sv/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetworldtransform/
---

**Summary:** The EmfPlusSetWorldTransform record sets the world transform according to the values in a<br/>            specified transform matrix.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusSetWorldTransform

**Inheritance:** EmfPlusTerminalServerRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusSetWorldTransform(source)](#EmfPlusSetWorldTransform_source_1) | Initierar en ny instans av klassen [EmfPlusSetWorldTransform](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetworldtransform/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| data_size | int | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som MÅSTE definiera det 32-bitars‑justerade antalet<br/>            databytes i RecordData‑fältet som följer. Detta tal inkluderar inte 12‑bytes posthuvudet. |
| flaggor | int | r/w | Hämtar eller anger ett 16-bitars osignerat heltal som innehåller information för vissa poster om hur<br/>            operationen ska utföras och om postens struktur. |
| matrix_data | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | Hämtar eller anger ett EmfPlusTransformMatrix-objekt (avsnitt 2.2.2.47) som definierar den<br/>            nya aktuella världstransformationen. |
| storlek | int | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar det 32-bitars‑justerade antalet bytes<br/>            i hela posten, inklusive 12‑bytes posthuvudet och post‑specifik data. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Hämtar ett 16-bitars osignerat heltal som identifierar posttypen. |


### Constructor: EmfPlusSetWorldTransform(source) {#EmfPlusSetWorldTransform_source_1}


```
 EmfPlusSetWorldTransform(source) 
```

Initierar en ny instans av klassen [EmfPlusSetWorldTransform](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetworldtransform/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | Källan. |

