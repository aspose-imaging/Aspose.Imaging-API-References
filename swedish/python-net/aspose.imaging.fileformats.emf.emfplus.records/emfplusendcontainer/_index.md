---
title: "EmfPlusEndContainer klass"
type: docs
weight: 210
url: /sv/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusendcontainer/
---

**Summary:** The EmfPlusEndContainer record closes a graphics state container that was previously opened by a begin container operation.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusEndContainer

**Inheritance:** EmfPlusStateRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusEndContainer(source)](#EmfPlusEndContainer_source_1) | Initierar en ny instans av klassen [EmfPlusEndContainer](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusendcontainer/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| data_size | int | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som MÅSTE definiera det 32-bitars‑justerade antalet<br/>            databytes i RecordData‑fältet som följer. Detta tal inkluderar inte 12‑bytes posthuvudet. |
| flaggor | int | r/w | Hämtar eller anger ett 16-bitars osignerat heltal som innehåller information för vissa poster om hur<br/>            operationen ska utföras och om postens struktur. |
| storlek | int | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar det 32-bitars‑justerade antalet bytes<br/>            i hela posten, inklusive 12‑bytes posthuvudet och post‑specifik data. |
| stack_index | int | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar indexet för en grafikstatus<br/>            behållare. Indexet MÅSTE matcha värdet som är associerat med en grafikstatusbehållare<br/>            som öppnades av en tidigare EmfPlusBeginContainer (avsnitt 2.3.7.1) eller<br/>            EmfPlusBeginContainerNoParams-post (avsnitt 2.3.7.2). |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Hämtar ett 16-bitars osignerat heltal som identifierar posttypen. |


### Constructor: EmfPlusEndContainer(source) {#EmfPlusEndContainer_source_1}


```
 EmfPlusEndContainer(source) 
```

Initierar en ny instans av klassen [EmfPlusEndContainer](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusendcontainer/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | Källan. |

