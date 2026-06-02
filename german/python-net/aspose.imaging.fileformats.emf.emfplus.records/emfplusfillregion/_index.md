---
title: "EmfPlusFillRegion Klasse"
type: docs
weight: 290
url: /de/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillregion/
---

**Summary:** The EmfPlusFillRegion record specifies filling the interior of a graphics region

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusFillRegion

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [EmfPlusFillRegion(source)](#EmfPlusFillRegion_source_1) | Initialisiert eine neue Instanz der [EmfPlusFillRegion](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillregion/) Klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| brush_id | int | r/w | Liest oder schreibt die Pinselkennung<br/> Eine 32‑Bit‑vorzeichenlose Ganzzahl, die den Pinsel definiert; ihr Inhalt wird durch das S‑Bit im Flags‑Feld bestimmt. |
| data_size | int | r/w | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die DIE 32‑Bit‑ausgerichtete Anzahl von<br/>            Bytes an Daten im nachfolgenden RecordData‑Feld DEFINIEREN MUSS. Diese Zahl beinhaltet nicht den 12‑Byte‑Datensatz‑Header. |
| flags | int | r/w | Liest oder setzt eine 16‑Bit‑vorzeichenlose Ganzzahl, die Informationen für einige Datensätze darüber enthält, wie<br/>            die Operation auszuführen ist und wie die Struktur des Datensatzes beschaffen ist. |
| is_color | bool | r/w | Liest oder setzt einen Wert, der angibt, ob diese Instanz eine Farbe ist.<br/>Wenn gesetzt, gibt BrushId eine Farbe als EmfPlusARGB‑Objekt an (Abschnitt 2.2.2.1).<br/>Wenn nicht gesetzt, enthält BrushId den Index eines EmfPlusBrush‑Objekts (Abschnitt 2.2.1.1) in der EMF+ Objekttabelle. |
| object_id | System.Byte | r/w | Liest oder setzt die Objektkennung.<br/>            Der Index des EmfPlusRegion‑Objekts (Abschnitt 2.2.1.8), das gefüllt werden soll, in der<br/>            EMF+ Objekttabelle. Der Wert MUSS zwischen 0 und 63 liegen, einschließlich. |
| size | int | r/w | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die 32‑Bit‑ausgerichtete Anzahl von Bytes<br/>            im gesamten Datensatz angibt, einschließlich des 12‑Byte‑Datensatz‑Headers und der datensatzspezifischen Daten. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Liest eine 16‑Bit‑vorzeichenlose Ganzzahl, die den Datensatztyp identifiziert. |


### Constructor: EmfPlusFillRegion(source) {#EmfPlusFillRegion_source_1}


```
 EmfPlusFillRegion(source) 
```

Initialisiert eine neue Instanz der [EmfPlusFillRegion](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillregion/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | Die Quelle. |

