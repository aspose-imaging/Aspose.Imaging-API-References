---
title: "EmfPlusScaleWorldTransform klass"
type: docs
weight: 430
url: /sv/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusscaleworldtransform/
---

**Summary:** The EmfPlusScaleWorldTransform record performs a scaling on the current world space transform.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusScaleWorldTransform

**Inheritance:** EmfPlusTerminalServerRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusScaleWorldTransform(source)](#EmfPlusScaleWorldTransform_source_1) | Initierar en ny instans av klassen [EmfPlusScaleWorldTransform](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusscaleworldtransform/) . |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| data_size | int | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som MÅSTE definiera det 32-bitars‑justerade antalet<br/>            databytes i RecordData‑fältet som följer. Detta tal inkluderar inte 12‑bytes posthuvudet. |
| flaggor | int | r/w | Hämtar eller anger ett 16-bitars osignerat heltal som innehåller information för vissa poster om hur<br/>            operationen ska utföras och om postens struktur. |
| post_multiplied_matrix | bool | r | Hämtar ett värde som indikerar om [post multiplied matrix].<br/>Om satt, bör transformmatrisen post-multipliceras. Om rensad, bör den premultipliceras. |
| storlek | int | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar det 32-bitars‑justerade antalet bytes<br/>            i hela posten, inklusive 12‑bytes posthuvudet och post‑specifik data. |
| sx | float | r/w | Hämtar eller anger ett 32-bitars flyttal som definierar den horisontella skalningsfaktorn. Skalningen<br/>            utförs genom att konstruera en ny transformmatris från fältvärdena Sx och Sy, som<br/>            visas i följande tabell.<br/>            -----------------<br/> | Sx | 0 | 0 | <br/> | 0 | Sx | 0 | <br/>            -----------------<br/>            Figur 3: Skaltransformmatris |
| sy | float | r/w | Hämtar eller anger ett 32-bitars flyttal som definierar den vertikala skalningsfaktorn. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Hämtar ett 16-bitars osignerat heltal som identifierar posttypen. |


### Constructor: EmfPlusScaleWorldTransform(source) {#EmfPlusScaleWorldTransform_source_1}


```
 EmfPlusScaleWorldTransform(source) 
```

Initierar en ny instans av klassen [EmfPlusScaleWorldTransform](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusscaleworldtransform/) .

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | Källan. |

