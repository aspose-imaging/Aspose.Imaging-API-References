---
title: "EmfPlusSetTsClip Class"
type: docs
weight: 570
url: /sv/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussettsclip/
---

**Summary:** The EmfPlusSetTSClip record specifies clipping areas in the graphics device context for a terminal server.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusSetTsClip

**Inheritance:** EmfPlusTerminalServerRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusSetTsClip(source)](#EmfPlusSetTsClip_source_1) | Initierar en ny instans av klassen [EmfPlusSetTsClip](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussettsclip/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| compressed | bool | r | Hämtar ett värde som indikerar om detta [EmfPlusSetTsClip](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussettsclip/) är komprimerat.<br/>            Denna bit specificerar formatet för rektangeldata i rects-fältet. Om satt, definieras varje<br/>            rektangel med 4 byte. Om rensad, definieras varje rektangel med 8 byte. |
| data_size | int | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som MÅSTE definiera det 32-bitars‑justerade antalet<br/>            databytes i RecordData‑fältet som följer. Detta tal inkluderar inte 12‑bytes posthuvudet. |
| flaggor | int | r/w | Hämtar eller anger ett 16-bitars osignerat heltal som innehåller information för vissa poster om hur<br/>            operationen ska utföras och om postens struktur. |
| num_rects | int | r | Hämtar antalet rektanglar.<br/>            Detta fält specificerar antalet rektanglar som är definierade i rect-fältet. |
| rects | [Rectangle[]](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Hämtar eller anger en array av NumRects-rektanglar som definierar beskärningsområden. Formatet för<br/>            dessa data bestäms av C-bit i Flag-fältet. |
| storlek | int | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar det 32-bitars‑justerade antalet bytes<br/>            i hela posten, inklusive 12‑bytes posthuvudet och post‑specifik data. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Hämtar ett 16-bitars osignerat heltal som identifierar posttypen. |


### Constructor: EmfPlusSetTsClip(source) {#EmfPlusSetTsClip_source_1}


```
 EmfPlusSetTsClip(source) 
```

Initierar en ny instans av klassen [EmfPlusSetTsClip](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussettsclip/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | Källan. |

