---
title: "EmfPlusSetPixelOffsetMode klass"
type: docs
weight: 530
url: /sv/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetpixeloffsetmode/
---

**Summary:** The EmfPlusSetPixelOffsetMode record specifies how pixels are centered with respect to the<br/>            coordinates of the drawing surface.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusSetPixelOffsetMode

**Inheritance:** EmfPlusPropertyRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusSetPixelOffsetMode(source)](#EmfPlusSetPixelOffsetMode_source_1) | Initierar en ny instans av klassen [EmfPlusSetPixelOffsetMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetpixeloffsetmode/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| data_size | int | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som MÅSTE definiera det 32-bitars‑justerade antalet<br/>            databytes i RecordData‑fältet som följer. Detta tal inkluderar inte 12‑bytes posthuvudet. |
| flaggor | int | r/w | Hämtar eller anger ett 16-bitars osignerat heltal som innehåller information för vissa poster om hur<br/>            operationen ska utföras och om postens struktur. |
| pixel_offset_mode | [EmfPlusPixelOffsetMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluspixeloffsetmode/) | r/w | Hämtar eller anger pixeloffsetlägesvärdet, från PixelOffsetMode<br/>            uppräkning (avsnitt 2.1.1.26). |
| storlek | int | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar det 32-bitars‑justerade antalet bytes<br/>            i hela posten, inklusive 12‑bytes posthuvudet och post‑specifik data. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Hämtar ett 16-bitars osignerat heltal som identifierar posttypen. |


### Constructor: EmfPlusSetPixelOffsetMode(source) {#EmfPlusSetPixelOffsetMode_source_1}


```
 EmfPlusSetPixelOffsetMode(source) 
```

Initierar en ny instans av klassen [EmfPlusSetPixelOffsetMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetpixeloffsetmode/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | Källan. |

