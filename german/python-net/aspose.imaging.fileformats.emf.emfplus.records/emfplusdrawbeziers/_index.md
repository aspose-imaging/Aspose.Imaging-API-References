---
title: "EmfPlusDrawBeziers Klasse"
type: docs
weight: 80
url: /de/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawbeziers/
---

**Summary:** The EmfPlusDrawBeziers record specifies drawing a sequence of connected Bezier curves. <br/>            The order for Bezier data points is the start point, control point 1, <br/>            control point 2 and end point. For more information see [MSDN-DrawBeziers].

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawBeziers

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [EmfPlusDrawBeziers(source)](#EmfPlusDrawBeziers_source_1) | Initialisiert eine neue Instanz der Klasse [EmfPlusDrawBeziers](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawbeziers/). |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| komprimiert | bool | r/w | Liest oder setzt einen Wert, der angibt, ob die PointData komprimiert ist. <br/>            Wenn gesetzt, gibt PointData absolute Positionen im Koordinatenraum mit <br/>            16‑Bit‑Ganzzahl‑Koordinaten an. Wenn gelöscht, gibt PointData absolute Positionen <br/>            im Koordinatenraum mit 32‑Bit‑Gleitkomma‑Koordinaten an.<br/>            Hinweis: Wenn das Relative‑Flag (unten) gesetzt ist, ist dieses Flag undefiniert und MUSS ignoriert werden. |
| data_size | int | r/w | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die DIE 32‑Bit‑ausgerichtete Anzahl von<br/>            Bytes an Daten im nachfolgenden RecordData‑Feld DEFINIEREN MUSS. Diese Zahl beinhaltet nicht den 12‑Byte‑Datensatz‑Header. |
| flags | int | r/w | Liest oder setzt eine 16‑Bit‑vorzeichenlose Ganzzahl, die Informationen für einige Datensätze darüber enthält, wie<br/>            die Operation auszuführen ist und wie die Struktur des Datensatzes beschaffen ist. |
| object_id | System.Byte | r/w | Liest oder setzt die Objektkennung.<br/>            Der Index eines EmfPlusPen‑Objekts (Abschnitt 2.2.1.7) in der EMF+‑Objekttabelle zum Zeichnen der Bézier‑Kurven. Der Wert MUSS zwischen 0 und 63 liegen, inklusiv. |
| point_data | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | r/w | Liest oder setzt die Punktdaten<br/>            Ein Array von Count‑Punkten, das die Start-, End‑ und Kontrollpunkte der Bézier‑Kurven angibt. Die Endkoordinate einer Bézier‑Kurve ist die Startkoordinate der nächsten. Die Kontrollpunkte werden verwendet, um den Bézier‑Effekt zu erzeugen.<br/>            Der Datentyp in diesem Array wird durch das Flags‑Feld angegeben, wie folgt: Datentyp Bedeutung<br/>            EmfPlusPointR‑Objekt (Abschnitt 2.2.2.37)<br/>            Wenn das P‑Flag im Flags‑Feld gesetzt ist, geben die Punkte relative Positionen an.<br/>            EmfPlusPointF‑Objekt (Abschnitt 2.2.2.36)<br/>            Wenn die P‑ und C‑Bits im Flags‑Feld gelöscht sind, geben die Punkte absolute Positionen an.<br/>            EmfPlusPoint‑Objekt (Abschnitt 2.2.2.35)<br/>            Wenn das P‑Bit gelöscht und das C‑Bit im Flags‑Feld gesetzt ist, geben die Punkte relative Positionen an.<br/>            Eine Bézier‑Kurve verläuft nicht durch ihre Kontrollpunkte. Die Kontrollpunkte dienen als |
| relative | bool | r/w | Liest oder setzt einen Wert, der angibt, ob die PointData relativ ist.<br/>            Wenn gesetzt, gibt jedes Element in PointData einen Ort im Koordinatenraum an, <br/>            der relativ zu dem vom vorherigen Element im Array angegebenen Ort ist. <br/>            Im Fall des ersten Elements in PointData wird ein vorheriger Ort bei den Koordinaten <br/>            (0,0) angenommen. Wenn nicht gesetzt, gibt PointData absolute Positionen gemäß dem C-Flag an.<br/>            Hinweis: Wenn dieses Flag gesetzt ist, ist das C-Flag (oben) undefiniert und MUSS ignoriert werden. |
| size | int | r/w | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die 32‑Bit‑ausgerichtete Anzahl von Bytes<br/>            im gesamten Datensatz angibt, einschließlich des 12‑Byte‑Datensatz‑Headers und der datensatzspezifischen Daten. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Liest eine 16‑Bit‑vorzeichenlose Ganzzahl, die den Datensatztyp identifiziert. |


### Constructor: EmfPlusDrawBeziers(source) {#EmfPlusDrawBeziers_source_1}


```
 EmfPlusDrawBeziers(source) 
```

Initialisiert eine neue Instanz der Klasse [EmfPlusDrawBeziers](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawbeziers/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | Die Quelle. |

