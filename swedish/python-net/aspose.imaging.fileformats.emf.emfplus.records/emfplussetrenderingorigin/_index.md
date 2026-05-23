---
title: "EmfPlusSetRenderingOrigin-klass"
type: docs
weight: 540
url: /sv/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetrenderingorigin/
---

**Summary:** The EmfPlusSetRenderingOrigin record specifies the rendering origin for graphics output.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusSetRenderingOrigin

**Inheritance:** EmfPlusPropertyRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusSetRenderingOrigin(source)](#EmfPlusSetRenderingOrigin_source_1) | Initierar en ny instans av klassen [EmfPlusSetRenderingOrigin](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetrenderingorigin/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| data_size | int | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som MÅSTE definiera det 32-bitars‑justerade antalet<br/>            databytes i RecordData‑fältet som följer. Detta tal inkluderar inte 12‑bytes posthuvudet. |
| flaggor | int | r/w | Hämtar eller anger ett 16-bitars osignerat heltal som innehåller information för vissa poster om hur<br/>            operationen ska utföras och om postens struktur. |
| storlek | int | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar det 32-bitars‑justerade antalet bytes<br/>            i hela posten, inklusive 12‑bytes posthuvudet och post‑specifik data. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Hämtar ett 16-bitars osignerat heltal som identifierar posttypen. |
| x | int | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som definierar det horisontella koordinatvärdet för renderingsursprunget. |
| y | int | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som definierar det vertikala koordinatvärdet för renderingsursprunget. |


### Constructor: EmfPlusSetRenderingOrigin(source) {#EmfPlusSetRenderingOrigin_source_1}


```
 EmfPlusSetRenderingOrigin(source) 
```

Initierar en ny instans av klassen [EmfPlusSetRenderingOrigin](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetrenderingorigin/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | Källan. |

