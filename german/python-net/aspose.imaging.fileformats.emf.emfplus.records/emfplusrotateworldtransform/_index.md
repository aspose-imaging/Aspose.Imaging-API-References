---
title: "EmfPlusRotateWorldTransform Klasse"
type: docs
weight: 410
url: /de/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrotateworldtransform/
---

**Summary:** The EmfPlusRotateWorldTransform record performs a rotation on the current world space transform.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRotateWorldTransform

**Inheritance:** EmfPlusTerminalServerRecordType

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [EmfPlusRotateWorldTransform(source)](#EmfPlusRotateWorldTransform_source_1) | Initialisiert eine neue Instanz der Klasse [EmfPlusRotateWorldTransform](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrotateworldtransform/). |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| angle | float | r/w | Liest oder setzt einen 32‑Bit‑Gleitkommawert, der den Rotationswinkel in Grad angibt.<br/>            Der Vorgang wird durchgeführt, indem aus dem folgenden<br/>            Diagramm eine neue Transformationsmatrix erstellt wird:<br/>            ---------------------------------<br/> | sin(Angle) | cos(Angle) | 0 | <br/> | cos(Angle) | sin(Angle) | 0 | <br/>            ---------------------------------<br/>            Abbildung 2: Rotations‑Transformationsmatrix<br/>            Die aktuelle Welt‑Raum‑Transformation wird mit dieser Matrix multipliziert, und das Ergebnis wird die<br/>            neue aktuelle Welt‑Raum‑Transformation. Das Feld Flags bestimmt die Reihenfolge der Multiplikation. |
| data_size | int | r/w | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die DIE 32‑Bit‑ausgerichtete Anzahl von<br/>            Bytes an Daten im nachfolgenden RecordData‑Feld DEFINIEREN MUSS. Diese Zahl beinhaltet nicht den 12‑Byte‑Datensatz‑Header. |
| flags | int | r/w | Liest oder setzt eine 16‑Bit‑vorzeichenlose Ganzzahl, die Informationen für einige Datensätze darüber enthält, wie<br/>            die Operation auszuführen ist und wie die Struktur des Datensatzes beschaffen ist. |
| post_multiplied_matrix | bool | r | Liest einen Wert, der angibt, ob [post multiplied matrix].<br/>            Wenn gesetzt, sollte die Transformationsmatrix post‑multipliziert werden. Wenn nicht gesetzt, sollte sie pre‑multipliziert werden. |
| size | int | r/w | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die 32‑Bit‑ausgerichtete Anzahl von Bytes<br/>            im gesamten Datensatz angibt, einschließlich des 12‑Byte‑Datensatz‑Headers und der datensatzspezifischen Daten. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Liest eine 16‑Bit‑vorzeichenlose Ganzzahl, die den Datensatztyp identifiziert. |


### Constructor: EmfPlusRotateWorldTransform(source) {#EmfPlusRotateWorldTransform_source_1}


```
 EmfPlusRotateWorldTransform(source) 
```

Initialisiert eine neue Instanz der Klasse [EmfPlusRotateWorldTransform](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrotateworldtransform/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | Die Quelle. |

