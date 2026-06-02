---
title: "EmfPlusFillPolygon Klasse"
type: docs
weight: 270
url: /de/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpolygon/
---

**Summary:** The EmfPlusFillPolygon record specifies filling the interior of a polygon.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusFillPolygon

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [EmfPlusFillPolygon(source)](#EmfPlusFillPolygon_source_1) | Initialisiert eine neue Instanz der [EmfPlusFillPolygon](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpolygon/) Klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| brush_id | int | r/w | Liest oder setzt die Pinsel‑Kennung<br/>Eine 32‑Bit‑vorzeichenlose Ganzzahl, die den Pinsel definiert, deren Inhalt<br/>durch das S‑Bit im Flags‑Feld bestimmt wird. |
| data_size | int | r/w | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die DIE 32‑Bit‑ausgerichtete Anzahl von<br/>            Bytes an Daten im nachfolgenden RecordData‑Feld DEFINIEREN MUSS. Diese Zahl beinhaltet nicht den 12‑Byte‑Datensatz‑Header. |
| flags | int | r/w | Liest oder setzt eine 16‑Bit‑vorzeichenlose Ganzzahl, die Informationen für einige Datensätze darüber enthält, wie<br/>            die Operation auszuführen ist und wie die Struktur des Datensatzes beschaffen ist. |
| is_color | bool | r/w | Liest oder setzt einen Wert, der angibt, ob diese Instanz eine Farbe ist.<br/>Wenn gesetzt, gibt BrushId eine Farbe als EmfPlusARGB‑Objekt an (Abschnitt 2.2.2.1).<br/>Wenn nicht gesetzt, enthält BrushId den Index eines EmfPlusBrush‑Objekts (Abschnitt 2.2.1.1) in der EMF+ Objekttabelle. |
| is_compressed | bool | r/w | Liest oder setzt einen Wert, der angibt, ob diese Instanz komprimiert ist.<br/>Wenn gesetzt, gibt PointData absolute Positionen im Koordinatenraum mit 16‑Bit‑Ganzzahlkoordinaten an. Wenn nicht gesetzt, gibt PointData absolute Positionen im Koordinatenraum mit 32‑Bit‑Gleitkomma‑Koordinaten an. |
| is_relative | bool | r/w | Liest oder setzt einen Wert, der angibt, ob diese Instanz relativ ist.<br/>Wenn gesetzt, gibt jedes Element in PointData einen Ort im Koordinatenraum an, der relativ zu dem vom vorherigen Element im Array angegebenen Ort ist.<br/>Im Fall des ersten Elements in PointData wird ein vorheriger Ort bei den Koordinaten (0,0) angenommen. Wenn nicht gesetzt, gibt PointData absolute Orte gemäß dem C‑Flag an. |
| point_data | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | r/w | Liest oder setzt die Punktdaten<br/>Ein Array von Count‑Punkten, die die Eckpunkte des Polygons definieren.<br/>Die ersten beiden Punkte im Array geben die erste Seite des Polygons an.<br/>Jeder weitere Punkt definiert eine neue Seite, deren Eckpunkte den Punkt und den vorherigen Punkt umfassen. Stimmen der letzte Punkt und der erste Punkt nicht überein, geben sie die letzte Seite des Polygons an. |
| size | int | r/w | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die 32‑Bit‑ausgerichtete Anzahl von Bytes<br/>            im gesamten Datensatz angibt, einschließlich des 12‑Byte‑Datensatz‑Headers und der datensatzspezifischen Daten. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Liest eine 16‑Bit‑vorzeichenlose Ganzzahl, die den Datensatztyp identifiziert. |


### Constructor: EmfPlusFillPolygon(source) {#EmfPlusFillPolygon_source_1}


```
 EmfPlusFillPolygon(source) 
```

Initialisiert eine neue Instanz der [EmfPlusFillPolygon](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillpolygon/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | Die Quelle. |

