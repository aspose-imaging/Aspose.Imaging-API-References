---
title: "EmfPlusDrawImage Klasse"
type: docs
weight: 130
url: /de/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimage/
---

**Summary:** The EmfPlusDrawImage record specifies drawing a scaled image.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawImage

**Inheritance:** EmfPlusDrawingRecordType

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [EmfPlusDrawImage(source)](#EmfPlusDrawImage_source_1) | Initialisiert eine neue Instanz der [EmfPlusDrawImage](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimage/) Klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| komprimiert | bool | r/w | Liest oder setzt einen Wert, der angibt, ob die PointData komprimiert ist.<br/>            Wenn gesetzt, enthält RectData ein EmfPlusRect‑Objekt (Abschnitt 2.2.2.38).<br/>            Wenn nicht gesetzt, enthält RectData ein EmfPlusRectF‑Objekt (Abschnitt 2.2.2.39). |
| data_size | int | r/w | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die DIE 32‑Bit‑ausgerichtete Anzahl von<br/>            Bytes an Daten im nachfolgenden RecordData‑Feld DEFINIEREN MUSS. Diese Zahl beinhaltet nicht den 12‑Byte‑Datensatz‑Header. |
| flags | int | r/w | Liest oder setzt eine 16‑Bit‑vorzeichenlose Ganzzahl, die Informationen für einige Datensätze darüber enthält, wie<br/>            die Operation auszuführen ist und wie die Struktur des Datensatzes beschaffen ist. |
| image_attributes_id | int | r/w | Liest oder setzt die Bildattributkennung<br/>            Ein 32‑Bit vorzeichenloser Integer, der den Index eines optionalen EmfPlusImageAttributes‑Objekts (Abschnitt 2.2.1.5) in der EMF+ Objekttabelle angibt. |
| object_id | System.Byte | r/w | Liest oder setzt die Objektkennung.<br/>            Der Index eines EmfPlusImage‑Objekts (Abschnitt 2.2.1.4) in der EMF+‑Objekttabelle, das das zu rendernde Bild angibt. Der Wert MUSS zwischen 0 und 63 liegen, inklusiv. |
| rect_data | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r/w | Liest oder setzt die Rechteckdaten<br/>            Entweder ein EmfPlusRect‑ oder EmfPlusRectF‑Objekt, das die Begrenzungsbox des Bildes definiert.<br/>            Der durch das SrcRect‑Feld angegebene Bildausschnitt wird skaliert, um in dieses Rechteck zu passen. |
| size | int | r/w | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die 32‑Bit‑ausgerichtete Anzahl von Bytes<br/>            im gesamten Datensatz angibt, einschließlich des 12‑Byte‑Datensatz‑Headers und der datensatzspezifischen Daten. |
| src_rect | [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | r/w | Liest oder setzt das Quellrechteck<br/>            Ein EmfPlusRectF‑Objekt, das einen Teil des zu rendernden Bildes angibt.<br/>            Der durch dieses Rechteck angegebene Bildausschnitt wird skaliert, um in das Ziel‑<br/>            Rechteck zu passen, das durch das Feld RectData angegeben ist. |
| src_unit | [EmfPlusUnitType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusunittype/) | r/w | Liest oder setzt die Quell‑Einheit<br/>            32‑Bit vorzeichenbehafteter Integer, der die Einheiten des SrcRect‑Feldes angibt.<br/>            Er MUSS das Mitglied UnitTypePixel der Aufzählung UnitType sein (Abschnitt 2.1.1.33). |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Liest eine 16‑Bit‑vorzeichenlose Ganzzahl, die den Datensatztyp identifiziert. |


### Constructor: EmfPlusDrawImage(source) {#EmfPlusDrawImage_source_1}


```
 EmfPlusDrawImage(source) 
```

Initialisiert eine neue Instanz der [EmfPlusDrawImage](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimage/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | Die Quelle. |

