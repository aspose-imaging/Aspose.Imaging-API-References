---
title: "EmfPlusDrawImagePoints Klasse"
type: docs
weight: 140
url: /de/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/
---

**Summary:** The EmfPlusDrawImagePoints record specifies drawing a scaled image inside a parallelogram.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawImagePoints

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [EmfPlusDrawImagePoints(source)](#EmfPlusDrawImagePoints_source_1) | Initialisiert eine neue Instanz der Klasse [EmfPlusDrawImagePoints](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/). |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| applying_an_effect | bool | r/w | Liest oder setzt einen Wert, der angibt, ob [applying an effect].<br/>            Dieses Bit zeigt an, dass die Bilddarstellung das Anwenden eines Effekts beinhaltet.<br/>            Wenn gesetzt, muss ein Objekt der Klasse Effect in einem früheren EmfPlusSerializableObject‑Datensatz (Abschnitt 2.3.5.2) angegeben worden sein. |
| komprimiert | bool | r/w | Liest oder setzt einen Wert, der angibt, ob die PointData komprimiert ist.<br/>            Dieses Bit gibt an, ob das PointData‑Feld komprimierte Daten spezifiziert.<br/>            Wenn gesetzt, gibt PointData absolute Positionen im Koordinatenraum mit 16‑Bit‑Ganzzahl‑Koordinaten an. Wenn gelöscht, gibt PointData absolute Positionen im Koordinatenraum mit 32‑Bit‑Gleitkomma‑Koordinaten an.<br/>            Hinweis: Wenn das P‑Flag (unten) gesetzt ist, ist dieses Flag undefiniert und MUSS ignoriert werden. |
| data_size | int | r/w | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die DIE 32‑Bit‑ausgerichtete Anzahl von<br/>            Bytes an Daten im nachfolgenden RecordData‑Feld DEFINIEREN MUSS. Diese Zahl beinhaltet nicht den 12‑Byte‑Datensatz‑Header. |
| flags | int | r/w | Liest oder setzt eine 16‑Bit‑vorzeichenlose Ganzzahl, die Informationen für einige Datensätze darüber enthält, wie<br/>            die Operation auszuführen ist und wie die Struktur des Datensatzes beschaffen ist. |
| image_attributes_id | int | r/w | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die den Index des optionalen EmfPlusImageAttributes‑Objekts (Abschnitt 2.2.1.5) in der EMF+‑Objekttabelle enthält. |
| object_id | System.Byte | r/w | Liest oder setzt die Objektkennung.<br/>            Der Index eines EmfPlusImage‑Objekts (Abschnitt 2.2.1.4) in der EMF+‑Objekttabelle, das das zu rendernde Bild angibt. Der Wert MUSS zwischen 0 und 63 liegen, inklusiv. |
| point_data | [PointF[]](/imaging/python-net/aspose.imaging/pointf/) | r/w | Liest oder setzt ein Array von Count‑Punkten, das drei Punkte eines Parallelogramms angibt.<br/>            Die drei Punkte repräsentieren die obere linke, obere rechte und untere linke Ecke des Parallelogramms. Der vierte Punkt des Parallelogramms wird aus den ersten drei extrapoliert. Der durch das SrcRect‑Feld angegebene Bildausschnitt SOLLTE bei Bedarf Skalierungs‑ und Scherungs‑Transformationen erhalten, um in das Parallelogramm zu passen. |
| relative | bool | r/w | Liest oder setzt einen Wert, der angibt, ob dieses [EmfPlusDrawImagePoints](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/) relativ ist.<br/>            Dieses Bit gibt an, ob das PointData‑Feld relative oder absolute Positionen angibt.<br/>            Wenn gesetzt, gibt jedes Element in PointData eine Position im Koordinatenraum an, die relativ zur Position des vorherigen Elements im Array ist. Im Fall des ersten Elements in PointData wird eine vorherige Position bei Koordinaten (0,0) angenommen. Wenn gelöscht, gibt PointData absolute Positionen gemäß dem C‑Flag an.<br/>            Hinweis: Wenn dieses Flag gesetzt ist, ist das C‑Flag (oben) undefiniert und MUSS ignoriert werden. |
| size | int | r/w | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die 32‑Bit‑ausgerichtete Anzahl von Bytes<br/>            im gesamten Datensatz angibt, einschließlich des 12‑Byte‑Datensatz‑Headers und der datensatzspezifischen Daten. |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r/w | Liest oder setzt ein EmfPlusRectF‑Objekt (Abschnitt 2.2.2.39), das einen Teil des zu rendernden Bildes definiert. |
| src_unit | [EmfPlusUnitType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusunittype/) | r/w | Liest oder setzt eine 32‑Bit‑vorzeichenbehaftete Ganzzahl, die die Einheiten des SrcRect‑Feldes definiert. Sie MUSS<br/>            den UnitPixel‑Wert der UnitType‑Aufzählung (Abschnitt 2.1.1.33) sein. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Liest eine 16‑Bit‑vorzeichenlose Ganzzahl, die den Datensatztyp identifiziert. |


### Constructor: EmfPlusDrawImagePoints(source) {#EmfPlusDrawImagePoints_source_1}


```
 EmfPlusDrawImagePoints(source) 
```

Initialisiert eine neue Instanz der Klasse [EmfPlusDrawImagePoints](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | Die Quelle. |

