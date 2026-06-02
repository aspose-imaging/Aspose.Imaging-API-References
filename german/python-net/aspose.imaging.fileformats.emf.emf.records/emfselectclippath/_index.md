---
title: "EmfSelectClipPath Klasse"
type: docs
weight: 1060
url: /de/python-net/aspose.imaging.fileformats.emf.emf.records/emfselectclippath/
---

**Summary:** The EMR_SELECTCLIPPATH record specifies the current path as a clipping region for a playback <br/>            device context, combining the new region with any existing clipping region using the specified mode.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfSelectClipPath

**Inheritance:** EmfClippingRecordType

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [EmfSelectClipPath()](#EmfSelectClipPath__1) | Initialisiert eine neue Instanz der [EmfSelectClipPath](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfselectclippath/) Klasse. |
| [EmfSelectClipPath(source)](#EmfSelectClipPath_source_2) | Initialisiert eine neue Instanz der [EmfSelectClipPath](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfselectclippath/) Klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| region_mode | [EmfRegionMode](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfregionmode/) | r/w | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die Art der Pfadverwendung angibt. Der <br/>            Wert MUSS in der RegionMode‑Aufzählung (Abschnitt 2.1.29) liegen. |
| size | int | r/w | Liest oder setzt die Größe des Datensatzes |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Ruft ab oder legt den Typ fest. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initialisiert eine neue Instanz der [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) Klasse. |
| [create_from_type(type)](#create_from_type_type_2) | Initialisiert eine neue Instanz der [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) Klasse. |


### Constructor: EmfSelectClipPath() {#EmfSelectClipPath__1}


```
 EmfSelectClipPath() 
```

Initialisiert eine neue Instanz der [EmfSelectClipPath](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfselectclippath/) Klasse.

### Constructor: EmfSelectClipPath(source) {#EmfSelectClipPath_source_2}


```
 EmfSelectClipPath(source) 
```

Initialisiert eine neue Instanz der [EmfSelectClipPath](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfselectclippath/) Klasse.

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


