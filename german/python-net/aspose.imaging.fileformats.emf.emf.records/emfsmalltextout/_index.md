---
title: "EmfSmallTextOut Klasse"
type: docs
weight: 1380
url: /de/python-net/aspose.imaging.fileformats.emf.emf.records/emfsmalltextout/
---

**Summary:** The EMR_SMALLTEXTOUT record outputs a string.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfSmallTextOut

**Inheritance:** EmfDrawingRecordType

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [EmfSmallTextOut(source)](#EmfSmallTextOut_source_1) | Initialisiert eine neue Instanz der Klasse [EmfSmallTextOut](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsmalltextout/). |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Liest oder setzt ein optionales, 128‑Bit‑WMF‑RectL‑Objekt ([MS-WMF] Abschnitt 2.2.2.19), das<br/>            das begrenzende Rechteck in Geräte‑Einheiten angibt. |
| c_chars | int | r/w | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die Anzahl der 16‑Bit‑Zeichen in der<br/>            Zeichenkette angibt. Die Zeichenkette ist NICHT null‑terminiert. |
| ex_scale | float | r/w | Liest oder setzt einen 32‑Bit‑Gleitkommawert, der angibt, um wie viel der Text in x‑Richtung skaliert werden soll. |
| ey_scale | float | r/w | Liest oder setzt einen 32‑Bit‑Gleitkommawert, der angibt, um wie viel der Text in y‑Richtung skaliert werden soll. |
| fu_options | [EmfExtTextOutOptions](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfexttextoutoptions/) | r/w | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die zu verwendenden Textausgabeoptionen angibt. Diese<br/>            Optionen werden durch einen oder eine Kombination von Werten aus der Enumeration ExtTextOutOptions<br/>            (Abschnitt 2.1.11) festgelegt. |
| graphics_mode | [EmfGraphicsMode](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfgraphicsmode/) | r/w | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die den Grafikmodus aus der<br/>            Enumeration GraphicsMode (Abschnitt 2.1.16) angibt. |
| size | int | r/w | Liest oder setzt die Größe des Datensatzes |
| text_string | string | r/w | Liest oder setzt eine variable Zeichenkette, die die zu zeichnende Textzeichenkette enthält, entweder<br/>            in 8‑Bit‑ oder 16‑Bit‑Zeichencodes, je nach dem Wert des Feldes fuOptions. |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Ruft ab oder legt den Typ fest. |
| x | int | r/w | Liest oder setzt eine 32‑Bit‑vorzeichenbehaftete Ganzzahl, die die x‑Koordinate angibt, an der die Zeichenkette platziert werden soll. |
| y | int | r/w | Liest oder setzt eine 32‑Bit‑vorzeichenbehaftete Ganzzahl, die die y‑Koordinate angibt, an der die Zeichenkette platziert werden soll. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initialisiert eine neue Instanz der [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) Klasse. |
| [create_from_type(type)](#create_from_type_type_2) | Initialisiert eine neue Instanz der [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) Klasse. |


### Constructor: EmfSmallTextOut(source) {#EmfSmallTextOut_source_1}


```
 EmfSmallTextOut(source) 
```

Initialisiert eine neue Instanz der Klasse [EmfSmallTextOut](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsmalltextout/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) | Die Quelle. |

### Method: create_from_record(source)  [static] {#create_from_record_source_1}


```
 create_from_record(source) 
```

Initialisiert eine neue Instanz der [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) | Die Quelle. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) |  |


### Method: create_from_type(type)  [static] {#create_from_type_type_2}


```
 create_from_type(type) 
```

Initialisiert eine neue Instanz der [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | Der Datensatztyp. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) |  |


