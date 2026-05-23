---
title: "EmfPlusSetTextRenderingHint Klasse"
type: docs
weight: 560
url: /de/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussettextrenderinghint/
---

**Summary:** The EmfPlusSetTextRenderingHint record specifies the quality of text rendering, including the type of anti-aliasing.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusSetTextRenderingHint

**Inheritance:** EmfPlusPropertyRecordType

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [EmfPlusSetTextRenderingHint(source)](#EmfPlusSetTextRenderingHint_source_1) | Initialisiert eine neue Instanz der [EmfPlusSetTextRenderingHint](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussettextrenderinghint/) Klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| data_size | int | r/w | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die DIE 32‑Bit‑ausgerichtete Anzahl von<br/>            Bytes an Daten im nachfolgenden RecordData‑Feld DEFINIEREN MUSS. Diese Zahl beinhaltet nicht den 12‑Byte‑Datensatz‑Header. |
| flags | int | r/w | Liest oder setzt eine 16‑Bit‑vorzeichenlose Ganzzahl, die Informationen für einige Datensätze darüber enthält, wie<br/>            die Operation auszuführen ist und wie die Struktur des Datensatzes beschaffen ist. |
| size | int | r/w | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die 32‑Bit‑ausgerichtete Anzahl von Bytes<br/>            im gesamten Datensatz angibt, einschließlich des 12‑Byte‑Datensatz‑Headers und der datensatzspezifischen Daten. |
| text_rendering_hint | [EmfPlusTextRenderingHint](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplustextrenderinghint/) | r/w | Liest oder setzt den Textdarstellungs-Hinweiswert, aus der<br/>            TextRenderingHint‑Aufzählung (Abschnitt 2.1.1.32), die die Qualität für die nachfolgende Textdarstellung festlegt. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Liest eine 16‑Bit‑vorzeichenlose Ganzzahl, die den Datensatztyp identifiziert. |


### Constructor: EmfPlusSetTextRenderingHint(source) {#EmfPlusSetTextRenderingHint_source_1}


```
 EmfPlusSetTextRenderingHint(source) 
```

Initialisiert eine neue Instanz der [EmfPlusSetTextRenderingHint](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussettextrenderinghint/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | Die Quelle. |

