---
title: "EmfPlusResetClip Class"
type: docs
weight: 380
url: /sv/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusresetclip/
---

**Summary:** The EmfPlusResetClip record resets the current clipping region for the world space to infinity.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusResetClip

**Inheritance:** EmfPlusClippingRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusResetClip(source)](#EmfPlusResetClip_source_1) | Initierar en ny instans av klassen [EmfPlusResetClip](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusresetclip/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| data_size | int | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som MÅSTE definiera det 32-bitars‑justerade antalet<br/>            databytes i RecordData‑fältet som följer. Detta tal inkluderar inte 12‑bytes posthuvudet. |
| flaggor | int | r/w | Hämtar eller anger ett 16-bitars osignerat heltal som innehåller information för vissa poster om hur<br/>            operationen ska utföras och om postens struktur. |
| storlek | int | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar det 32-bitars‑justerade antalet bytes<br/>            i hela posten, inklusive 12‑bytes posthuvudet och post‑specifik data. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Hämtar ett 16-bitars osignerat heltal som identifierar posttypen. |


### Constructor: EmfPlusResetClip(source) {#EmfPlusResetClip_source_1}


```
 EmfPlusResetClip(source) 
```

Initierar en ny instans av klassen [EmfPlusResetClip](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusresetclip/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | Källan. |

