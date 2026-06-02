---
title: "EmfPlusDrawCurve Klasse"
type: docs
weight: 100
url: /de/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawcurve/
---

**Summary:** The EmfPlusDrawCurve record specifies drawing a cardinal spline<br/>            NOTE: ObjectID (1 byte): The index of an EmfPlusPen object (section 2.2.1.7)<br/>             in the EMF+ Object Table to draw the curve. The value MUST be zero to 63, inclusive.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawCurve

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [EmfPlusDrawCurve(source)](#EmfPlusDrawCurve_source_1) | Initialisiert eine neue Instanz der [EmfPlusDrawCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawcurve/) Klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| compressed | bool | r/w | Ruft einen Wert ab oder legt ihn fest, der angibt, ob dieses [EmfPlusDrawClosedCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/) komprimiert ist.<br/>            Dieses Bit gibt an, ob das Feld PointData komprimierte Daten enthält.<br/>            Wenn gesetzt, gibt PointData absolute Positionen im Koordinatenraum mit 16‑Bit‑Ganzzahlkoordinaten an. <br/>            Wenn nicht gesetzt, gibt PointData absolute Positionen im Koordinatenraum mit 32‑Bit‑Gleitkomma‑Koordinaten an.<br/>            Hinweis: Wenn das Relative‑Flag (unten) gesetzt ist, ist dieses Flag undefiniert und MUSS ignoriert werden |
| data_size | int | r/w | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die DIE 32‑Bit‑ausgerichtete Anzahl von<br/>            Bytes an Daten im nachfolgenden RecordData‑Feld DEFINIEREN MUSS. Diese Zahl beinhaltet nicht den 12‑Byte‑Datensatz‑Header. |
| flags | int | r/w | Liest oder setzt eine 16‑Bit‑vorzeichenlose Ganzzahl, die Informationen für einige Datensätze darüber enthält, wie<br/>            die Operation auszuführen ist und wie die Struktur des Datensatzes beschaffen ist. |
| num_segments | int | r/w | Liest oder setzt die Segmentanzahl <br/>            Ein 32‑Bit vorzeichenloser Integer, der die Anzahl der Liniensegmente angibt, aus denen die Spline besteht. |
| object_id | System.Byte | r/w | Liest oder setzt die Objektkennung.<br/>            Der Index eines EmfPlusPen‑Objekts (Abschnitt 2.2.1.7) in der EMF+<br/>            Objekttabelle zum Zeichnen der Kurve. Der Wert MUSS zwischen 0 und 63 liegen, einschließlich. |
| point_data | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | r/w | Liest oder setzt ein Array aus entweder 32‑Bit vorzeichenbehafteten Integern oder 32‑Bit Gleitkommazahlen von <br/>            Count‑Länge, das die Koordinatenwerte der Endpunkte der zu zeichnenden Linien definiert. |
| size | int | r/w | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die 32‑Bit‑ausgerichtete Anzahl von Bytes<br/>            im gesamten Datensatz angibt, einschließlich des 12‑Byte‑Datensatz‑Headers und der datensatzspezifischen Daten. |
| Spannung | float | r/w | Liest oder setzt die Spannung<br/>            Eine 32‑Bit‑Gleitkommazahl, die angibt, wie stark die Spline<br/>            sich beim Durchlaufen der Punkte biegt. Ein Wert von 0 bedeutet,<br/>            dass die Spline eine Reihe von Geraden ist. Mit zunehmendem Wert<br/>            wird die Kurve runder. Weitere Informationen finden Sie in [SPLINE77] und [PETZOLD]. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Liest eine 16‑Bit‑vorzeichenlose Ganzzahl, die den Datensatztyp identifiziert. |


### Constructor: EmfPlusDrawCurve(source) {#EmfPlusDrawCurve_source_1}


```
 EmfPlusDrawCurve(source) 
```

Initialisiert eine neue Instanz der [EmfPlusDrawCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawcurve/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | Die Quelle. |

