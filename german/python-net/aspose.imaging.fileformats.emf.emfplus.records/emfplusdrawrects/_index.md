---
title: "EmfPlusDrawRects Klasse"
type: docs
weight: 180
url: /de/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawrects/
---

**Summary:** The EmfPlusDrawRects record specifies drawing a series of rectangles

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawRects

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [EmfPlusDrawRects(source)](#EmfPlusDrawRects_source_1) | Initialisiert eine neue Instanz der [EmfPlusDrawRects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawrects/) Klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| komprimiert | bool | r/w | Liest oder setzt einen Wert, der angibt, ob die PointData komprimiert ist.<br/>            Wenn gesetzt, enthält RectData ein EmfPlusRect‑Objekt (Abschnitt 2.2.2.38).<br/>            Wenn nicht gesetzt, enthält RectData ein EmfPlusRectF‑Objekt (Abschnitt 2.2.2.39). |
| data_size | int | r/w | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die DIE 32‑Bit‑ausgerichtete Anzahl von<br/>            Bytes an Daten im nachfolgenden RecordData‑Feld DEFINIEREN MUSS. Diese Zahl beinhaltet nicht den 12‑Byte‑Datensatz‑Header. |
| flags | int | r/w | Liest oder setzt eine 16‑Bit‑vorzeichenlose Ganzzahl, die Informationen für einige Datensätze darüber enthält, wie<br/>            die Operation auszuführen ist und wie die Struktur des Datensatzes beschaffen ist. |
| object_id | System.Byte | r/w | Liest oder setzt die Objektkennung.<br/>            Der Index eines EmfPlusPen-Objekts (Abschnitt 2.2.1.7) in der EMF+<br/>            Objekttabelle zum Zeichnen der Rechtecke. Der Wert MUSS zwischen 0 und 63 liegen, einschließlich. |
| rect_data | [RectangleF[]](/imaging/python-net/aspose.imaging/rectanglef/) | r/w | Liest oder setzt die Rechteckdaten<br/>            Ein Array aus entweder EmfPlusRect- oder EmfPlusRectF-Objekten mit der Länge Count, das die Rechteckdaten definiert. |
| size | int | r/w | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die 32‑Bit‑ausgerichtete Anzahl von Bytes<br/>            im gesamten Datensatz angibt, einschließlich des 12‑Byte‑Datensatz‑Headers und der datensatzspezifischen Daten. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Liest eine 16‑Bit‑vorzeichenlose Ganzzahl, die den Datensatztyp identifiziert. |


### Constructor: EmfPlusDrawRects(source) {#EmfPlusDrawRects_source_1}


```
 EmfPlusDrawRects(source) 
```

Initialisiert eine neue Instanz der [EmfPlusDrawRects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawrects/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | Die Quelle. |

