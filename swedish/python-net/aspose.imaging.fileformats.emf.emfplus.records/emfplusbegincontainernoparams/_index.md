---
title: "EmfPlusBeginContainerNoParams klass"
type: docs
weight: 20
url: /sv/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusbegincontainernoparams/
---

**Summary:** The EmfPlusBeginContainerNoParams record opens a new graphics state container.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusBeginContainerNoParams

**Inheritance:** EmfPlusStateRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusBeginContainerNoParams(source)](#EmfPlusBeginContainerNoParams_source_1) | Initierar en ny instans av klassen [EmfPlusBeginContainerNoParams](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusbegincontainernoparams/) klass. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| data_size | int | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som MÅSTE definiera det 32-bitars‑justerade antalet<br/>            databytes i RecordData‑fältet som följer. Detta tal inkluderar inte 12‑bytes posthuvudet. |
| flaggor | int | r/w | Hämtar eller anger ett 16-bitars osignerat heltal som innehåller information för vissa poster om hur<br/>            operationen ska utföras och om postens struktur. |
| storlek | int | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar det 32-bitars‑justerade antalet bytes<br/>            i hela posten, inklusive 12‑bytes posthuvudet och post‑specifik data. |
| stack_index | int | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar ett index att associera med<br/>            grafikstatusbehållaren. Indexet MÅSTE refereras av en efterföljande<br/>            EmfPlusEndContainer‑post (avsnitt 2.3.7.3) för att stänga grafikstatusbehållaren. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Hämtar ett 16-bitars osignerat heltal som identifierar posttypen. |


### Constructor: EmfPlusBeginContainerNoParams(source) {#EmfPlusBeginContainerNoParams_source_1}


```
 EmfPlusBeginContainerNoParams(source) 
```

Initierar en ny instans av klassen [EmfPlusBeginContainerNoParams](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusbegincontainernoparams/) klass.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | Källan. |

