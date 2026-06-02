---
title: "EmfPlusDrawLines Klasse"
type: docs
weight: 150
url: /de/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawlines/
---

**Summary:** The EmfPlusDrawlLines record specifies drawing a series of connected lines

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawLines

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [EmfPlusDrawLines(source)](#EmfPlusDrawLines_source_1) | Initialisiert eine neue Instanz der Klasse [EmfPlusDrawLines](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawlines/). |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| closed_shape | bool | r/w | Liest oder setzt einen Wert, der angibt, ob [closed shape] |
| compressed | bool | r/w | Ruft einen Wert ab oder legt ihn fest, der angibt, ob dieses [EmfPlusDrawClosedCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/) komprimiert ist.<br/>            Dieses Bit gibt an, ob das Feld PointData komprimierte Daten enthält.<br/>            Wenn gesetzt, gibt PointData absolute Positionen im Koordinatenraum mit 16‑Bit‑Ganzzahlkoordinaten an. <br/>            Wenn nicht gesetzt, gibt PointData absolute Positionen im Koordinatenraum mit 32‑Bit‑Gleitkomma‑Koordinaten an.<br/>            Hinweis: Wenn das Relative‑Flag (unten) gesetzt ist, ist dieses Flag undefiniert und MUSS ignoriert werden |
| data_size | int | r/w | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die DIE 32‑Bit‑ausgerichtete Anzahl von<br/>            Bytes an Daten im nachfolgenden RecordData‑Feld DEFINIEREN MUSS. Diese Zahl beinhaltet nicht den 12‑Byte‑Datensatz‑Header. |
| flags | int | r/w | Liest oder setzt eine 16‑Bit‑vorzeichenlose Ganzzahl, die Informationen für einige Datensätze darüber enthält, wie<br/>            die Operation auszuführen ist und wie die Struktur des Datensatzes beschaffen ist. |
| object_id | System.Byte | r/w | Liest oder setzt die Objektkennung.<br/>            Der Index eines EmfPlusPen‑Objekts (Abschnitt 2.2.1.7) in der EMF+<br/>            Objekttabelle zum Zeichnen der Linien. Der Wert MUSS zwischen 0 und 63 liegen, inklusiv. |
| point_data | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | r/w | Liest oder setzt die Punktdaten<br/>            Ein Array von Count‑Punkten, das die Start‑ und Endpunkte der zu zeichnenden Linien angibt. |
| relative | bool | r/w | Liest oder setzt einen Wert, der angibt, ob dieses [EmfPlusDrawClosedCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawclosedcurve/) relativ ist.<br/>            Dieses Bit gibt an, ob das Feld PointData relative oder absolute Positionen angibt.<br/>            Wenn gesetzt, gibt jedes Element in PointData eine Position im Koordinatenraum an, die relativ <br/>            zur Position des vorherigen Elements im Array ist. Im Fall des ersten <br/>            Elements in PointData wird eine vorherige Position bei den Koordinaten (0,0) angenommen. Wenn nicht gesetzt, <br/>            gibt PointData absolute Positionen gemäß dem C‑Flag an.<br/>            Hinweis: Wenn dieses Flag gesetzt ist, ist das Komprimiert‑Flag (oben) undefiniert und MUSS ignoriert werden |
| size | int | r/w | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die 32‑Bit‑ausgerichtete Anzahl von Bytes<br/>            im gesamten Datensatz angibt, einschließlich des 12‑Byte‑Datensatz‑Headers und der datensatzspezifischen Daten. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Liest eine 16‑Bit‑vorzeichenlose Ganzzahl, die den Datensatztyp identifiziert. |


### Constructor: EmfPlusDrawLines(source) {#EmfPlusDrawLines_source_1}


```
 EmfPlusDrawLines(source) 
```

Initialisiert eine neue Instanz der Klasse [EmfPlusDrawLines](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawlines/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | Die Quelle. |

