---
title: "EmfPlusDrawClosedCurve Klasse"
type: docs
weight: 90
url: /de/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/
---

**Summary:** The EmfPlusDrawClosedCurve record specifies drawing a closed cardinal spline

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawClosedCurve

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [EmfPlusDrawClosedCurve(source)](#EmfPlusDrawClosedCurve_source_1) | Initialisiert eine neue Instanz der Klasse [EmfPlusDrawClosedCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/).<br/>            RecordType – Ein 16‑Bit‑vorzeichenloser Integer, der diesen Datensatztyp als EmfPlusDrawClosedCurve aus der RecordType‑Aufzählung (Abschnitt 2.1.1.1) identifiziert.<br/>            Der Wert MUSS 0x4017 sein. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| compressed | bool | r/w | Ruft einen Wert ab oder legt ihn fest, der angibt, ob dieses [EmfPlusDrawClosedCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/) komprimiert ist.<br/>            Dieses Bit gibt an, ob das Feld PointData komprimierte Daten enthält.<br/>            Wenn gesetzt, gibt PointData absolute Positionen im Koordinatenraum mit 16‑Bit‑Ganzzahlkoordinaten an. <br/>            Wenn nicht gesetzt, gibt PointData absolute Positionen im Koordinatenraum mit 32‑Bit‑Gleitkomma‑Koordinaten an.<br/>            Hinweis: Wenn das Relative‑Flag (unten) gesetzt ist, ist dieses Flag undefiniert und MUSS ignoriert werden |
| data_size | int | r/w | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die DIE 32‑Bit‑ausgerichtete Anzahl von<br/>            Bytes an Daten im nachfolgenden RecordData‑Feld DEFINIEREN MUSS. Diese Zahl beinhaltet nicht den 12‑Byte‑Datensatz‑Header. |
| flags | int | r/w | Liest oder setzt eine 16‑Bit‑vorzeichenlose Ganzzahl, die Informationen für einige Datensätze darüber enthält, wie<br/>            die Operation auszuführen ist und wie die Struktur des Datensatzes beschaffen ist. |
| object_id | System.Byte | r/w | Liest oder setzt die Objektkennung.<br/>            Der Index eines EmfPlusPen‑Objekts (Abschnitt 2.2.1.7) in der EMF+ Objekt‑Tabelle zum Zeichnen der geschlossenen Kurve. Der Wert MUSS zwischen 0 und 63 liegen, inklusiv. |
| point_data | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | r/w | Liest oder setzt die Punktdaten<br/>            Ein Array von Count‑Punkten, die die Endpunkte der Linien angeben, die die Spline definieren. Bei einer geschlossenen Kardinal‑Spline,<br/>            setzt die Kurve sich über den letzten Punkt im PointData‑Array fort und verbindet sich mit dem ersten Punkt des Arrays.<br/>            Der Datentyp in diesem Array wird durch das Flags‑Feld wie folgt angegeben: Datentyp Bedeutung<br/>            EmfPlusPointR‑Objekt (Abschnitt 2.2.2.37)<br/>            Wenn das P‑Flag im Flags‑Feld gesetzt ist, geben die Punkte relative Positionen an.<br/>            EmfPlusPointF‑Objekt (Abschnitt 2.2.2.36)<br/>            Wenn die P‑ und C‑Bits im Flags‑Feld gesetzt sind, geben die Punkte absolute Positionen an.<br/>            EmfPlusPoint‑Objekt (Abschnitt 2.2.2.35)<br/>            Wenn das P‑Bit nicht gesetzt und das C‑Bit im Flags‑Feld gesetzt ist, geben die Punkte relative Positionen an. |
| relative | bool | r/w | Liest oder setzt einen Wert, der angibt, ob dieses [EmfPlusDrawClosedCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/) relativ ist.<br/>            Dieses Bit gibt an, ob das Feld PointData relative oder absolute Positionen angibt.<br/>            Wenn gesetzt, gibt jedes Element in PointData eine Position im Koordinatenraum an, die relativ <br/>            zur Position des vorherigen Elements im Array ist. Im Fall des ersten <br/>            Elements in PointData wird eine vorherige Position bei den Koordinaten (0,0) angenommen. Wenn nicht gesetzt, <br/>            gibt PointData absolute Positionen gemäß dem C‑Flag an.<br/>            Hinweis: Wenn dieses Flag gesetzt ist, ist das Komprimiert‑Flag (oben) undefiniert und MUSS ignoriert werden |
| size | int | r/w | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die 32‑Bit‑ausgerichtete Anzahl von Bytes<br/>            im gesamten Datensatz angibt, einschließlich des 12‑Byte‑Datensatz‑Headers und der datensatzspezifischen Daten. |
| Spannung | float | r/w | Liest oder setzt die Spannung<br/>            Eine 32‑Bit‑Gleitkommazahl, die angibt, wie stark die Spline<br/>            sich beim Durchlaufen der Punkte biegt. Ein Wert von 0 bedeutet,<br/>            dass die Spline eine Reihe von Geraden ist. Mit zunehmendem Wert<br/>            wird die Kurve runder. Weitere Informationen finden Sie in [SPLINE77] und [PETZOLD]. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Liest eine 16‑Bit‑vorzeichenlose Ganzzahl, die den Datensatztyp identifiziert. |


### Constructor: EmfPlusDrawClosedCurve(source) {#EmfPlusDrawClosedCurve_source_1}


```
 EmfPlusDrawClosedCurve(source) 
```

Initialisiert eine neue Instanz der Klasse [EmfPlusDrawClosedCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/).<br/>            RecordType – Ein 16‑Bit‑vorzeichenloser Integer, der diesen Datensatztyp als EmfPlusDrawClosedCurve aus der RecordType‑Aufzählung (Abschnitt 2.1.1.1) identifiziert.<br/>            Der Wert MUSS 0x4017 sein.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | Die Quelle. |

