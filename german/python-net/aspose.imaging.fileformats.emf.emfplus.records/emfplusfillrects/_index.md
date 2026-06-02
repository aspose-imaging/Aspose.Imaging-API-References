---
title: "EmfPlusFillRects Klasse"
type: docs
weight: 280
url: /de/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillrects/
---

**Summary:** The EmfPlusFillRects record specifies filling the interiors of a series of rectangles

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusFillRects

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [EmfPlusFillRects(source)](#EmfPlusFillRects_source_1) | Initialisiert eine neue Instanz der Klasse [EmfPlusFillRects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillrects/). |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| brush_id | int | r/w | Liest oder schreibt die Pinselkennung<br/> Eine 32‑Bit‑vorzeichenlose Ganzzahl, die den Pinsel definiert; ihr Inhalt wird durch das S‑Bit im Flags‑Feld bestimmt. |
| compressed | bool | r/w | Liest oder schreibt einen Wert, der angibt, ob dieses [EmfPlusFillRects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillrects/) komprimiert ist.<br/> Wenn gesetzt, enthält RectData ein EmfPlusRect‑Objekt (Abschnitt 2.2.2.38). Wenn nicht gesetzt, enthält RectData ein EmfPlusRectF‑Objekt (Abschnitt 2.2.2.39). |
| data_size | int | r/w | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die DIE 32‑Bit‑ausgerichtete Anzahl von<br/>            Bytes an Daten im nachfolgenden RecordData‑Feld DEFINIEREN MUSS. Diese Zahl beinhaltet nicht den 12‑Byte‑Datensatz‑Header. |
| flags | int | r/w | Liest oder setzt eine 16‑Bit‑vorzeichenlose Ganzzahl, die Informationen für einige Datensätze darüber enthält, wie<br/>            die Operation auszuführen ist und wie die Struktur des Datensatzes beschaffen ist. |
| is_color | bool | r/w | Liest oder schreibt einen Wert, der angibt, ob diese Instanz eine Farbe ist.<br/> Wenn gesetzt, gibt BrushId eine Farbe als EmfPlusARGB‑Objekt an (Abschnitt 2.2.2.1).<br/> Wenn nicht gesetzt, enthält BrushId den Index eines EmfPlusBrush‑Objekts (Abschnitt 2.2.1.1) in der EMF+‑Objekttabelle. |
| rect_data | [RectangleF[]](/imaging/python-net/aspose.imaging/rectanglef/) | r/w | Liest oder schreibt die Rechteckdaten<br/> Ein Array aus entweder EmfPlusRect‑ oder EmfPlusRectF‑Objekten der Länge Count, das die Rechteckdaten definiert. |
| size | int | r/w | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die 32‑Bit‑ausgerichtete Anzahl von Bytes<br/>            im gesamten Datensatz angibt, einschließlich des 12‑Byte‑Datensatz‑Headers und der datensatzspezifischen Daten. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Liest eine 16‑Bit‑vorzeichenlose Ganzzahl, die den Datensatztyp identifiziert. |


### Constructor: EmfPlusFillRects(source) {#EmfPlusFillRects_source_1}


```
 EmfPlusFillRects(source) 
```

Initialisiert eine neue Instanz der Klasse [EmfPlusFillRects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillrects/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | Die Quelle. |

