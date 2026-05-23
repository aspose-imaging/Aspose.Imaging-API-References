---
title: "EmfPlusSetPageTransform klass"
type: docs
weight: 520
url: /sv/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetpagetransform/
---

**Summary:** The EmfPlusSetPageTransform record specifies scaling factors and units for converting page space<br/>            coordinates to device space coordinates.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusSetPageTransform

**Inheritance:** EmfPlusTerminalServerRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusSetPageTransform(source)](#EmfPlusSetPageTransform_source_1) | Initierar en ny instans av klassen [EmfPlusSetPageTransform](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetpagetransform/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| data_size | int | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som MÅSTE definiera det 32-bitars‑justerade antalet<br/>            databytes i RecordData‑fältet som följer. Detta tal inkluderar inte 12‑bytes posthuvudet. |
| flaggor | int | r/w | Hämtar eller anger ett 16-bitars osignerat heltal som innehåller information för vissa poster om hur<br/>            operationen ska utföras och om postens struktur. |
| page_scale | float | r/w | Hämtar eller anger ett 32-bitars flyttal som specificerar skalningsfaktorn för att konvertera<br/>            sidrymdskoordinater till enhetsrymdskoordinater. |
| page_unit | [EmfPlusUnitType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusunittype/) | r | Hämtar måttenheten för sidrymdskoordinater, från UnitType‑enumerationen<br/>            (avsnitt 2.1.1.33). Detta värde BÖR INTE vara UnitTypeDisplay eller UnitTypeWorld. |
| storlek | int | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar det 32-bitars‑justerade antalet bytes<br/>            i hela posten, inklusive 12‑bytes posthuvudet och post‑specifik data. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Hämtar ett 16-bitars osignerat heltal som identifierar posttypen. |


### Constructor: EmfPlusSetPageTransform(source) {#EmfPlusSetPageTransform_source_1}


```
 EmfPlusSetPageTransform(source) 
```

Initierar en ny instans av klassen [EmfPlusSetPageTransform](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetpagetransform/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | Källan. |

