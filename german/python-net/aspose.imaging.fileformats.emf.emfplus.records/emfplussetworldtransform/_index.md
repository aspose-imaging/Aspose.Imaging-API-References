---
title: "EmfPlusSetWorldTransform Klasse"
type: docs
weight: 590
url: /de/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetworldtransform/
---

**Summary:** The EmfPlusSetWorldTransform record sets the world transform according to the values in a<br/>            specified transform matrix.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusSetWorldTransform

**Inheritance:** EmfPlusTerminalServerRecordType

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [EmfPlusSetWorldTransform(source)](#EmfPlusSetWorldTransform_source_1) | Initialisiert eine neue Instanz der [EmfPlusSetWorldTransform](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetworldtransform/) Klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| data_size | int | r/w | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die DIE 32‑Bit‑ausgerichtete Anzahl von<br/>            Bytes an Daten im nachfolgenden RecordData‑Feld DEFINIEREN MUSS. Diese Zahl beinhaltet nicht den 12‑Byte‑Datensatz‑Header. |
| flags | int | r/w | Liest oder setzt eine 16‑Bit‑vorzeichenlose Ganzzahl, die Informationen für einige Datensätze darüber enthält, wie<br/>            die Operation auszuführen ist und wie die Struktur des Datensatzes beschaffen ist. |
| matrix_data | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | Liest oder setzt ein EmfPlusTransformMatrix‑Objekt (Abschnitt 2.2.2.47), das die<br/>            neue aktuelle Welttransformation definiert. |
| size | int | r/w | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die 32‑Bit‑ausgerichtete Anzahl von Bytes<br/>            im gesamten Datensatz angibt, einschließlich des 12‑Byte‑Datensatz‑Headers und der datensatzspezifischen Daten. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Liest eine 16‑Bit‑vorzeichenlose Ganzzahl, die den Datensatztyp identifiziert. |


### Constructor: EmfPlusSetWorldTransform(source) {#EmfPlusSetWorldTransform_source_1}


```
 EmfPlusSetWorldTransform(source) 
```

Initialisiert eine neue Instanz der [EmfPlusSetWorldTransform](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetworldtransform/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | Die Quelle. |

