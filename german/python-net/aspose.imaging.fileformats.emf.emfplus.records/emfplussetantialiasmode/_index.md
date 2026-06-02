---
title: "EmfPlusSetAntiAliasMode Klasse"
type: docs
weight: 450
url: /de/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetantialiasmode/
---

**Summary:** The EmfPlusSetAntiAliasMode record specifies the anti-aliasing mode for text output.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusSetAntiAliasMode

**Inheritance:** EmfPlusPropertyRecordType

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [EmfPlusSetAntiAliasMode(source)](#EmfPlusSetAntiAliasMode_source_1) | Initialisiert eine neue Instanz der Klasse [EmfPlusSetAntiAliasMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetantialiasmode/). |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| anti_aliasing | bool | r/w | Liest oder setzt einen Wert, der angibt, ob [anti aliasing].<br/>            Wenn gesetzt, sollte Antialiasing durchgeführt werden.<br/>            Wenn nicht gesetzt, sollte Antialiasing NICHT durchgeführt werden. |
| data_size | int | r/w | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die DIE 32‑Bit‑ausgerichtete Anzahl von<br/>            Bytes an Daten im nachfolgenden RecordData‑Feld DEFINIEREN MUSS. Diese Zahl beinhaltet nicht den 12‑Byte‑Datensatz‑Header. |
| flags | int | r/w | Liest oder setzt eine 16‑Bit‑vorzeichenlose Ganzzahl, die Informationen für einige Datensätze darüber enthält, wie<br/>            die Operation auszuführen ist und wie die Struktur des Datensatzes beschaffen ist. |
| size | int | r/w | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die 32‑Bit‑ausgerichtete Anzahl von Bytes<br/>            im gesamten Datensatz angibt, einschließlich des 12‑Byte‑Datensatz‑Headers und der datensatzspezifischen Daten. |
| smoothing_mode | [EmfPlusSmoothingMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplussmoothingmode/) | r/w | Liest oder setzt den Glättungsmodus.<br/>            (7 Bits): Der Wert des Glättungsmodus, aus der Aufzählung SmoothingMode (Abschnitt 2.1.1.28) |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Liest eine 16‑Bit‑vorzeichenlose Ganzzahl, die den Datensatztyp identifiziert. |


### Constructor: EmfPlusSetAntiAliasMode(source) {#EmfPlusSetAntiAliasMode_source_1}


```
 EmfPlusSetAntiAliasMode(source) 
```

Initialisiert eine neue Instanz der Klasse [EmfPlusSetAntiAliasMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetantialiasmode/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | Die Quelle. |

