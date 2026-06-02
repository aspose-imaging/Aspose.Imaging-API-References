---
title: "EmfPlusRestore Klasse"
type: docs
weight: 400
url: /de/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrestore/
---

**Summary:** The EmfPlusRestore record restores the graphics state, identified by a specified index, from a stack of saved graphics states.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRestore

**Inheritance:** EmfPlusStateRecordType

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [EmfPlusRestore(source)](#EmfPlusRestore_source_1) | Initialisiert eine neue Instanz der [EmfPlusRestore](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrestore/) Klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| data_size | int | r/w | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die DIE 32‑Bit‑ausgerichtete Anzahl von<br/>            Bytes an Daten im nachfolgenden RecordData‑Feld DEFINIEREN MUSS. Diese Zahl beinhaltet nicht den 12‑Byte‑Datensatz‑Header. |
| flags | int | r/w | Liest oder setzt eine 16‑Bit‑vorzeichenlose Ganzzahl, die Informationen für einige Datensätze darüber enthält, wie<br/>            die Operation auszuführen ist und wie die Struktur des Datensatzes beschaffen ist. |
| size | int | r/w | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die 32‑Bit‑ausgerichtete Anzahl von Bytes<br/>            im gesamten Datensatz angibt, einschließlich des 12‑Byte‑Datensatz‑Headers und der datensatzspezifischen Daten. |
| stack_index | int | r/w | Liest oder setzt eine 32‑Bit vorzeichenlose Ganzzahl, die die mit einem<br/>            Grafikstatus verbundene Ebene angibt. Der Ebenenwert wurde dem Grafikstatus durch einen vorherigen EmfPlusSave‑Datensatz (Abschnitt 2.3.7.5) zugewiesen. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Liest eine 16‑Bit‑vorzeichenlose Ganzzahl, die den Datensatztyp identifiziert. |


### Constructor: EmfPlusRestore(source) {#EmfPlusRestore_source_1}


```
 EmfPlusRestore(source) 
```

Initialisiert eine neue Instanz der [EmfPlusRestore](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrestore/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | Die Quelle. |

