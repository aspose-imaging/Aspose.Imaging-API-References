---
title: "EmfPlusTranslateWorldTransform klass"
type: docs
weight: 630
url: /sv/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplustranslateworldtransform/
---

**Summary:** The EmfPlusTranslateWorldTransform record performs a translation on the current world space transform.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusTranslateWorldTransform

**Inheritance:** EmfPlusTerminalServerRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusTranslateWorldTransform(source)](#EmfPlusTranslateWorldTransform_source_1) | Initierar en ny instans av [EmfPlusTranslateWorldTransform](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplustranslateworldtransform/) klass. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| data_size | int | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som MÅSTE definiera det 32-bitars‑justerade antalet<br/>            databytes i RecordData‑fältet som följer. Detta tal inkluderar inte 12‑bytes posthuvudet. |
| dx | float | r/w | Hämtar eller anger ett 32-bitars flyttalsvärde som definierar den horisontella avståndet. Översättningen<br/>utförs genom att konstruera en ny world transform-matris från dx- och dy-fälten. |
| dy | float | r/w | Hämtar eller anger ett 32-bitars flyttalsvärde som definierar det vertikala avståndsvärdet. |
| flaggor | int | r/w | Hämtar eller anger ett 16-bitars osignerat heltal som innehåller information för vissa poster om hur<br/>            operationen ska utföras och om postens struktur. |
| post_multiplied_matrix | bool | r | Hämtar ett värde som indikerar om [post multiplied matrix].<br/>            Om satt, bör transformationsmatrisen post-multipliceras. Om rensad, bör den premultipliceras. |
| storlek | int | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar det 32-bitars‑justerade antalet bytes<br/>            i hela posten, inklusive 12‑bytes posthuvudet och post‑specifik data. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Hämtar ett 16-bitars osignerat heltal som identifierar posttypen. |


### Constructor: EmfPlusTranslateWorldTransform(source) {#EmfPlusTranslateWorldTransform_source_1}


```
 EmfPlusTranslateWorldTransform(source) 
```

Initierar en ny instans av [EmfPlusTranslateWorldTransform](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplustranslateworldtransform/) klass.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | Källan. |

