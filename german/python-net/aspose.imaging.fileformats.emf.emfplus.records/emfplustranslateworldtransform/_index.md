---
title: "EmfPlusTranslateWorldTransform Klasse"
type: docs
weight: 630
url: /de/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplustranslateworldtransform/
---

**Summary:** The EmfPlusTranslateWorldTransform record performs a translation on the current world space transform.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusTranslateWorldTransform

**Inheritance:** EmfPlusTerminalServerRecordType

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [EmfPlusTranslateWorldTransform(source)](#EmfPlusTranslateWorldTransform_source_1) | Initialisiert eine neue Instanz der [EmfPlusTranslateWorldTransform](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplustranslateworldtransform/) Klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| data_size | int | r/w | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die DIE 32‑Bit‑ausgerichtete Anzahl von<br/>            Bytes an Daten im nachfolgenden RecordData‑Feld DEFINIEREN MUSS. Diese Zahl beinhaltet nicht den 12‑Byte‑Datensatz‑Header. |
| dx | float | r/w | Liest oder setzt einen 32‑Bit‑Gleitkommawert, der die horizontale Distanz definiert. Die Translation<br/>wird durchgeführt, indem aus den dx‑ und dy‑Feldern eine neue Welttransformationsmatrix erstellt wird. |
| dy | float | r/w | Liest oder setzt einen 32‑Bit‑Gleitkommawert, der den vertikalen Distanzwert definiert. |
| flags | int | r/w | Liest oder setzt eine 16‑Bit‑vorzeichenlose Ganzzahl, die Informationen für einige Datensätze darüber enthält, wie<br/>            die Operation auszuführen ist und wie die Struktur des Datensatzes beschaffen ist. |
| post_multiplied_matrix | bool | r | Liest einen Wert, der angibt, ob [post multiplied matrix].<br/>            Wenn gesetzt, sollte die Transformationsmatrix post‑multipliziert werden. Wenn nicht gesetzt, sollte sie pre‑multipliziert werden. |
| size | int | r/w | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die 32‑Bit‑ausgerichtete Anzahl von Bytes<br/>            im gesamten Datensatz angibt, einschließlich des 12‑Byte‑Datensatz‑Headers und der datensatzspezifischen Daten. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Liest eine 16‑Bit‑vorzeichenlose Ganzzahl, die den Datensatztyp identifiziert. |


### Constructor: EmfPlusTranslateWorldTransform(source) {#EmfPlusTranslateWorldTransform_source_1}


```
 EmfPlusTranslateWorldTransform(source) 
```

Initialisiert eine neue Instanz der [EmfPlusTranslateWorldTransform](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplustranslateworldtransform/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | Die Quelle. |

