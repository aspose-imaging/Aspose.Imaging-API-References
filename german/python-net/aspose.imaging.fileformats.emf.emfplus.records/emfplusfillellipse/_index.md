---
title: "EmfPlusFillEllipse Klasse"
type: docs
weight: 240
url: /de/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillellipse/
---

**Summary:** The EmfPlusFillEllipse record specifies filling the interior of an ellipse

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusFillEllipse

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [EmfPlusFillEllipse(source)](#EmfPlusFillEllipse_source_1) | Initialisiert eine neue Instanz der Klasse [EmfPlusFillEllipse](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillellipse/). |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| brush_id | int | r/w | Liest oder setzt die Pinselkennung<br/>            Eine 32‑Bit‑vorzeichenlose Ganzzahl, die den Pinsel angibt, dessen Inhalt durch das S‑Bit im Flags‑Feld bestimmt wird. Diese Definition wird verwendet <br/>            um das Innere der Ellipse zu füllen. |
| data_size | int | r/w | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die DIE 32‑Bit‑ausgerichtete Anzahl von<br/>            Bytes an Daten im nachfolgenden RecordData‑Feld DEFINIEREN MUSS. Diese Zahl beinhaltet nicht den 12‑Byte‑Datensatz‑Header. |
| flags | int | r/w | Liest oder setzt eine 16‑Bit‑vorzeichenlose Ganzzahl, die Informationen für einige Datensätze darüber enthält, wie<br/>            die Operation auszuführen ist und wie die Struktur des Datensatzes beschaffen ist. |
| is_color | bool | r/w | Liest oder setzt einen Wert, der angibt, ob diese Instanz farbig ist.<br/>            Wenn gesetzt, gibt BrushId eine Farbe als EmfPlusARGB‑Objekt (Abschnitt 2.2.2.1) an.<br/>            Wenn nicht gesetzt, enthält BrushId den Index eines EmfPlusBrush‑Objekts<br/>            (Abschnitt 2.2.1.1) in der EMF+‑Objekttabelle. |
| is_compressed | bool | r/w | Liest oder setzt einen Wert, der angibt, ob diese Instanz komprimiert ist.<br/>            Wenn gesetzt, enthält RectData ein EmfPlusRect‑Objekt (Abschnitt 2.2.2.38). <br/>            Wenn gelöscht, enthält RectData ein EmfPlusRectF‑Objekt (Abschnitt 2.2.2.39). |
| rect_data | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r/w | Liest oder setzt die Rechteckdaten<br/>            Entweder ein EmfPlusRect‑ oder EmfPlusRectF‑Objekt, das die Begrenzungsbox der Ellipse definiert. |
| size | int | r/w | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die 32‑Bit‑ausgerichtete Anzahl von Bytes<br/>            im gesamten Datensatz angibt, einschließlich des 12‑Byte‑Datensatz‑Headers und der datensatzspezifischen Daten. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Liest eine 16‑Bit‑vorzeichenlose Ganzzahl, die den Datensatztyp identifiziert. |


### Constructor: EmfPlusFillEllipse(source) {#EmfPlusFillEllipse_source_1}


```
 EmfPlusFillEllipse(source) 
```

Initialisiert eine neue Instanz der Klasse [EmfPlusFillEllipse](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillellipse/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | Die Quelle. |

