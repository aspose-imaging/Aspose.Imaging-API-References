---
title: "EmfPlusDrawPie Klasse"
type: docs
weight: 170
url: /de/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawpie/
---

**Summary:** The EmfPlusDrawPie record specifies drawing a section of the interior of an ellipse.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawPie

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [EmfPlusDrawPie(source)](#EmfPlusDrawPie_source_1) | Initialisiert eine neue Instanz der Klasse [EmfPlusDrawPie](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawpie/). |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| komprimiert | bool | r/w | Liest oder setzt einen Wert, der angibt, ob die PointData komprimiert ist.<br/>            Wenn gesetzt, enthält RectData ein EmfPlusRect‑Objekt (Abschnitt 2.2.2.38).<br/>            Wenn nicht gesetzt, enthält RectData ein EmfPlusRectF‑Objekt (Abschnitt 2.2.2.39). |
| data_size | int | r/w | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die DIE 32‑Bit‑ausgerichtete Anzahl von<br/>            Bytes an Daten im nachfolgenden RecordData‑Feld DEFINIEREN MUSS. Diese Zahl beinhaltet nicht den 12‑Byte‑Datensatz‑Header. |
| flags | int | r/w | Liest oder setzt eine 16‑Bit‑vorzeichenlose Ganzzahl, die Informationen für einige Datensätze darüber enthält, wie<br/>            die Operation auszuführen ist und wie die Struktur des Datensatzes beschaffen ist. |
| object_id | System.Byte | r/w | Liest oder setzt die Objektkennung.<br/>            Der Index eines EmfPlusPen‑Objekts (Abschnitt 2.2.1.7) in der EMF+<br/>            Objekttabelle zum Zeichnen des Kuchenstücks. Der Wert MUSS zwischen 0 und 63 liegen, inklusiv. |
| rect_data | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r/w | Liest oder setzt die Rechteckdaten<br/>            Entweder ein EmfPlusRect- oder EmfPlusRectF-Objekt, das das Begrenzungsrechteck der <br/>            Ellipse definiert, die das Kuchenstück enthält. Dieses Rechteck definiert die Position, Größe, <br/>            und Form des Kuchens. Der Typ des Objekts in diesem Feld wird durch den Wert <br/>            des Flags-Feldes angegeben. |
| size | int | r/w | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die 32‑Bit‑ausgerichtete Anzahl von Bytes<br/>            im gesamten Datensatz angibt, einschließlich des 12‑Byte‑Datensatz‑Headers und der datensatzspezifischen Daten. |
| start_angle | float | r/w | Liest oder setzt den Startwinkel<br/>            Ein 32‑Bit, nicht‑negativer Fließkommawert, der den Winkel zwischen der <br/>            x‑Achse und dem Startpunkt des Kuchenstücks angibt. Jeder Wert ist zulässig, aber er <br/>            MUSS modulo 360 interpretiert werden, wobei das Ergebnis im Bereich <br/>            0,0 (einschließlich) bis 360,0 (ausschließlich) liegen muss. |
| sweep_angle | float | r/w | Liest oder setzt den Sweep‑Winkel<br/>            Ein 32‑Bit Fließkommawert, der den Umfang des Bogens angibt, der das zu zeichnende Kuchenstück definiert, als Winkel in Grad gemessen vom Startpunkt, <br/>            der durch den StartAngle‑Wert festgelegt ist. Jeder Wert ist zulässig, aber er MUSS auf den Bereich -360,0 bis 360,0 (einschließlich) begrenzt werden. Ein positiver Wert zeigt an, dass der Sweep im Uhrzeigersinn definiert ist, ein negativer Wert zeigt an, dass der Sweep gegen den Uhrzeigersinn definiert ist. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Liest eine 16‑Bit‑vorzeichenlose Ganzzahl, die den Datensatztyp identifiziert. |


### Constructor: EmfPlusDrawPie(source) {#EmfPlusDrawPie_source_1}


```
 EmfPlusDrawPie(source) 
```

Initialisiert eine neue Instanz der Klasse [EmfPlusDrawPie](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawpie/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | Die Quelle. |

