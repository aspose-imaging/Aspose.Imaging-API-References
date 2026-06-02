---
title: "EmfGradientFill Klasse"
type: docs
weight: 560
url: /de/python-net/aspose.imaging.fileformats.emf.emf.records/emfgradientfill/
---

**Summary:** The EMR_GRADIENTFILL record specifies filling rectangles or triangles with gradients of color.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfGradientFill

**Inheritance:** EmfDrawingRecordType

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [EmfGradientFill(source)](#EmfGradientFill_source_1) | Initialisiert eine neue Instanz der Klasse [EmfGradientFill](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfgradientfill/). |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Liest oder setzt ein WMF RectL‑Objekt ([MS-WMF] Abschnitt 2.2.2.19), das ein <br/>            Begrenzungsrechteck in inklusiv‑inklusiven Geräte‑Einheiten angibt. |
| n_tri | int | r/w | Liest oder setzt eine 32‑Bit vorzeichenlose Ganzzahl, die die Anzahl der zu füllenden Rechtecke oder Dreiecke angibt. |
| n_ver | int | r/w | Liest oder setzt eine 32‑Bit vorzeichenlose Ganzzahl, die die Anzahl der Scheitelpunkte angibt. |
| size | int | r/w | Liest oder setzt die Größe des Datensatzes |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Ruft ab oder legt den Typ fest. |
| ul_mode | [EmfGradientFill](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfgradientfill/) | r/w | Liest oder setzt eine 32‑Bit vorzeichenlose Ganzzahl, die den Gradientenfüllmodus angibt. Der Wert <br/>            MUSS in der GradientFill‑Aufzählung (Abschnitt 2.1.15) enthalten sein. |
| vertex_data | [EmfVertexData](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfvertexdata/) | r/w | Liest oder setzt Objekte, die die Scheitelpunkte von Rechtecken oder Dreiecken sowie <br/>            die zugehörigen Farben angeben. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initialisiert eine neue Instanz der [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) Klasse. |
| [create_from_type(type)](#create_from_type_type_2) | Initialisiert eine neue Instanz der [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) Klasse. |


### Constructor: EmfGradientFill(source) {#EmfGradientFill_source_1}


```
 EmfGradientFill(source) 
```

Initialisiert eine neue Instanz der Klasse [EmfGradientFill](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfgradientfill/).

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


