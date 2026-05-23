---
title: "EmfPlusSetPixelOffsetMode‑Klasse"
type: docs
weight: 530
url: /de/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetpixeloffsetmode/
---

**Summary:** The EmfPlusSetPixelOffsetMode record specifies how pixels are centered with respect to the<br/>            coordinates of the drawing surface.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusSetPixelOffsetMode

**Inheritance:** EmfPlusPropertyRecordType

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [EmfPlusSetPixelOffsetMode(source)](#EmfPlusSetPixelOffsetMode_source_1) | Initialisiert eine neue Instanz der Klasse [EmfPlusSetPixelOffsetMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetpixeloffsetmode/). |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| data_size | int | r/w | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die DIE 32‑Bit‑ausgerichtete Anzahl von<br/>            Bytes an Daten im nachfolgenden RecordData‑Feld DEFINIEREN MUSS. Diese Zahl beinhaltet nicht den 12‑Byte‑Datensatz‑Header. |
| flags | int | r/w | Liest oder setzt eine 16‑Bit‑vorzeichenlose Ganzzahl, die Informationen für einige Datensätze darüber enthält, wie<br/>            die Operation auszuführen ist und wie die Struktur des Datensatzes beschaffen ist. |
| pixel_offset_mode | [EmfPlusPixelOffsetMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluspixeloffsetmode/) | r/w | Liest oder schreibt den Pixelversatz‑Moduswert, aus der PixelOffsetMode‑Aufzählung<br/> (Abschnitt 2.1.1.26). |
| size | int | r/w | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die 32‑Bit‑ausgerichtete Anzahl von Bytes<br/>            im gesamten Datensatz angibt, einschließlich des 12‑Byte‑Datensatz‑Headers und der datensatzspezifischen Daten. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Liest eine 16‑Bit‑vorzeichenlose Ganzzahl, die den Datensatztyp identifiziert. |


### Constructor: EmfPlusSetPixelOffsetMode(source) {#EmfPlusSetPixelOffsetMode_source_1}


```
 EmfPlusSetPixelOffsetMode(source) 
```

Initialisiert eine neue Instanz der Klasse [EmfPlusSetPixelOffsetMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussetpixeloffsetmode/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | Die Quelle. |

