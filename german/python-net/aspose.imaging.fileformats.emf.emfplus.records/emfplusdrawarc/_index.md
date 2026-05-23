---
title: "EmfPlusDrawArc Klasse"
type: docs
weight: 70
url: /de/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawarc/
---

**Summary:** The EmfPlusDrawArc record specifies drawing the arc of an ellipse.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawArc

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [EmfPlusDrawArc(source)](#EmfPlusDrawArc_source_1) | Initialisiert eine neue Instanz der Klasse [EmfPlusDrawArc](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawarc/). |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| data_size | int | r/w | Liest oder setzt die Größe der Daten.<br/>            Ein 32‑Bit vorzeichenloser Integer, der die 32‑Bit‑ausgerichtete Anzahl von<br/>            Bytes der nachfolgenden rekord­spezifischen Daten angibt.<br/>            Für diesen Rekordtyp MUSS der Wert einer der folgenden sein:<br/>            0x00000010, wenn das C‑Bit im Flags‑Feld gesetzt ist.<br/>            0x00000018, wenn das C‑Bit im Flags‑Feld gelöscht ist. |
| flags | int | r/w | Liest oder setzt eine 16‑Bit‑vorzeichenlose Ganzzahl, die Informationen für einige Datensätze darüber enthält, wie<br/>            die Operation auszuführen ist und wie die Struktur des Datensatzes beschaffen ist. |
| object_id | System.Byte | r/w | Liest oder setzt die Objektkennung.<br/>            Der Index eines EmfPlusPen‑Objekts (Abschnitt 2.2.1.7) in der<br/>            EMF+‑Objekttabelle zum Zeichnen des Bogens. Der Wert MUSS zwischen 0 und 63 liegen, inklusiv. |
| rect_float | bool | r/w | Liest oder setzt einen Wert, der angibt, ob die Daten <br/>            EmfPlusRectF‑ oder EmfPlusRect‑Datensätze enthalten<br/>            Dieses Bit gibt an, ob die Daten im Feld RectData komprimiert sind.<br/>            Wenn gesetzt, enthält RectData ein EmfPlusRect‑Objekt (Abschnitt 2.2.2.38).<br/>            Wenn gelöscht, enthält RectData ein EmfPlusRectF‑Objekt (Abschnitt 2.2.2.39). |
| rectangle_data | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r/w | Liest oder setzt die Rechteckdaten<br/>            Entweder ein EmfPlusRect‑ oder EmfPlusRectF‑Objekt, das die Begrenzungsbox<br/>            der Ellipse definiert, die mit dem Bogen kollinear ist. Dieses Rechteck definiert die<br/>            Position, Größe und Form des Bogens. Der Objekttyp in diesem Feld wird<br/>            durch den Wert des Flags‑Feldes angegeben. |
| size | int | r/w | Liest oder setzt die Größe.<br/>            Ein 32‑Bit vorzeichenloser Integer, der die 32‑Bit‑ausgerichtete Anzahl von<br/>            Bytes im gesamten Rekord angibt, einschließlich des 12‑Byte‑Rekordkopfes und<br/>            rekord­spezifischer Daten. Für diesen Rekordtyp MUSS der Wert einer der folgenden sein:<br/>            0x0000001C, wenn das C‑Bit im Flags‑Feld gesetzt ist.<br/>            0x00000024, wenn das C‑Bit im Flags‑Feld gelöscht ist. |
| start_angle | float | r/w | Liest oder setzt den Startwinkel<br/>            Ein 32‑Bit nicht‑negativer Gleitkommawert, der den Winkel zwischen<br/>            der x‑Achse und dem Startpunkt des Bogens angibt. Jeder Wert ist zulässig,<br/>            muss jedoch modulo 360 interpretiert werden, wobei das Ergebnis im Bereich<br/>            0,0 (inklusive) bis 360,0 (exklusiv) liegt. |
| sweep_angle | float | r/w | Liest oder setzt den Sweep‑Winkel<br/>            Ein 32‑Bit Gleitkommawert, der den Umfang des zu zeichnenden Bogens angibt,<br/>            als Winkel in Grad gemessen vom Startpunkt, der durch den<br/>            StartAngle‑Wert definiert ist. Jeder Wert ist zulässig, muss jedoch auf -360,0<br/>            bis 360,0 (inklusive) begrenzt werden. Ein positiver Wert bedeutet, dass der Sweep im<br/>            Uhrzeigersinn definiert ist, ein negativer Wert bedeutet, dass der Sweep im<br/>            Gegenuhrzeigersinn definiert ist. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Liest eine 16‑Bit‑vorzeichenlose Ganzzahl, die den Datensatztyp identifiziert. |


### Constructor: EmfPlusDrawArc(source) {#EmfPlusDrawArc_source_1}


```
 EmfPlusDrawArc(source) 
```

Initialisiert eine neue Instanz der Klasse [EmfPlusDrawArc](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawarc/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | Die Quelle. |

