---
title: "EmfPlusFillClosedCurve Klasse"
type: docs
weight: 230
url: /de/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/
---

**Summary:** The EmfPlusFillClosedCurve record specifies filling the interior of a closed cardinal spline

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusFillClosedCurve

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [EmfPlusFillClosedCurve(source)](#EmfPlusFillClosedCurve_source_1) | Initialisiert eine neue Instanz der [EmfPlusFillClosedCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/) Klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| brush_id | int | r/w | Liest oder setzt die Pinselkennung<br/>            Eine 32‑Bit vorzeichenlose Ganzzahl, die den EmfPlusBrush angibt, dessen Inhalt <br/>            durch das S‑Bit im Flags‑Feld bestimmt wird. Dieser Pinsel wird verwendet, um das Innere <br/>            der geschlossenen Kardinal‑Spline zu füllen. |
| compressed | bool | r/w | Liest oder setzt einen Wert, der angibt, ob dieses [EmfPlusFillClosedCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/) komprimiert ist.<br/>            Dieses Bit gibt an, ob das PointData‑Feld komprimierte Daten enthält.<br/>            Wenn gesetzt, gibt PointData absolute Positionen im Koordinatenraum mit 16‑Bit <br/>            Ganzzahlkoordinaten an. Wenn nicht gesetzt, gibt PointData absolute Positionen im <br/>            Koordinatenraum mit 32‑Bit Gleitkomma‑Koordinaten an.<br/>            ----------------------<br/>            Eine "winding"‑Fülloperation füllt Flächen nach der "even‑odd parity"‑Regel. <br/>            Nach dieser Regel kann ein Testpunkt als innerhalb oder außerhalb einer <br/>            geschlossenen Kurve bestimmt werden: Zeichnen Sie eine Linie vom Testpunkt zu einem Punkt, der weit entfernt von der Kurve liegt. Wenn diese Linie die Kurve eine ungerade Anzahl von Malen schneidet, liegt der Testpunkt innerhalb der Kurve; andernfalls liegt er außerhalb der Kurve.<br/>            ---------------------<br/>            Eine "alternate"‑Fülloperation füllt Flächen nach der "non-zero"‑Regel.<br/>             Nach dieser Regel kann ein Testpunkt als innerhalb oder außerhalb <br/>            einer geschlossenen Kurve bestimmt werden: Zeichnen Sie eine Linie von einem Testpunkt zu einem Punkt, der <br/>            weit von der Kurve entfernt ist. Zählen Sie, wie oft die Kurve die Testlinie von links nach rechts schneidet, und zählen Sie, wie oft die Kurve die Testlinie von rechts nach links schneidet. Wenn diese beiden Zahlen gleich sind, liegt der Testpunkt außerhalb der Kurve; andernfalls liegt er innerhalb der Kurve. |
| data_size | int | r/w | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die DIE 32‑Bit‑ausgerichtete Anzahl von<br/>            Bytes an Daten im nachfolgenden RecordData‑Feld DEFINIEREN MUSS. Diese Zahl beinhaltet nicht den 12‑Byte‑Datensatz‑Header. |
| flags | int | r/w | Liest oder setzt eine 16‑Bit‑vorzeichenlose Ganzzahl, die Informationen für einige Datensätze darüber enthält, wie<br/>            die Operation auszuführen ist und wie die Struktur des Datensatzes beschaffen ist. |
| is_color | bool | r/w | Liest oder setzt einen Wert, der angibt, ob diese Instanz farbig ist.<br/>            Wenn gesetzt, gibt BrushId eine Farbe als EmfPlusARGB‑Objekt (Abschnitt 2.2.2.1) an.<br/>            Wenn nicht gesetzt, enthält BrushId den Index eines EmfPlusBrush‑Objekts<br/>            (Abschnitt 2.2.1.1) in der EMF+‑Objekttabelle. |
| point_data | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | r/w | Liest oder setzt die Punktdaten<br/>            Ein Array von Count‑Punkten, die die Endpunkte der Linien angeben, die die Spline definieren. <br/>            In einer geschlossenen Kardinal‑Spline setzt die Kurve sich durch den letzten Punkt im PointData <br/>            Array fort und verbindet sich mit dem ersten Punkt im Array. |
| relative | bool | r/w | Liest oder setzt einen Wert, der angibt, ob dieses [EmfPlusFillClosedCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/) relativ ist.<br/>            Dieses Bit gibt an, ob das PointData‑Feld relative oder absolute Positionen angibt.<br/>            Wenn gesetzt, gibt jedes Element in PointData einen Ort im Koordinatenraum an, <br/>            der relativ zu dem vom vorherigen Element im Array angegebenen Ort ist. Im Fall <br/>            des ersten Elements in PointData wird ein vorheriger Ort bei den Koordinaten (0,0) angenommen. <br/>            Wenn nicht gesetzt, gibt PointData absolute Positionen gemäß dem C‑Flag an.<br/>            Hinweis: Wenn dieses Flag gesetzt ist, ist das C‑Flag (oben) undefiniert und MUSS ignoriert werden. |
| size | int | r/w | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die 32‑Bit‑ausgerichtete Anzahl von Bytes<br/>            im gesamten Datensatz angibt, einschließlich des 12‑Byte‑Datensatz‑Headers und der datensatzspezifischen Daten. |
| Spannung | float | r/w | Liest oder setzt die Spannung<br/>            Ein 32‑Bit Gleitkommawert, der angibt, wie stark die Spline beim Durchlaufen der Punkte gebogen wird. Ein Wert von 0,0 bedeutet, dass die Spline eine Folge gerader <br/>            Linien ist. Mit zunehmendem Wert wird die Kurve runder. Weitere Informationen finden Sie in [SPLINE77] und [PETZOLD]. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Liest eine 16‑Bit‑vorzeichenlose Ganzzahl, die den Datensatztyp identifiziert. |
| winding | bool | r/w | Liest oder setzt einen Wert, der angibt, ob dieses [EmfPlusFillClosedCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/) winding ist.<br/>            Dieses Bit gibt an, wie die Fülloperation ausgeführt wird.<br/>            Wenn gesetzt, ist die Füllung eine "winding"‑Füllung. Wenn nicht gesetzt, ist die Füllung eine "alternate"‑Füllung. |


### Constructor: EmfPlusFillClosedCurve(source) {#EmfPlusFillClosedCurve_source_1}


```
 EmfPlusFillClosedCurve(source) 
```

Initialisiert eine neue Instanz der [EmfPlusFillClosedCurve](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | Die Quelle. |

