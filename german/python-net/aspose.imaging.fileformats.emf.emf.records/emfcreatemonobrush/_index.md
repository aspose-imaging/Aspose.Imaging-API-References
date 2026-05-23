---
title: "EmfCreateMonoBrush Klasse"
type: docs
weight: 300
url: /de/python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatemonobrush/
---

**Summary:** The EMR_CREATEMONOBRUSH record defines a monochrome pattern brush for graphics operations.<br/>            The pattern is specified by a monochrome DIB.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfCreateMonoBrush

**Inheritance:** EmfObjectCreationRecordType

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [EmfCreateMonoBrush(source)](#EmfCreateMonoBrush_source_1) | Initialisiert eine neue Instanz der Klasse [EmfCreateMonoBrush](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatemonobrush/). |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| bitmap_buffer | [WmfDeviceIndependentBitmap](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap/) | r/w | Liest oder setzt einen Puffer, der ein gepacktes DIB in Form eines WMF<br/>            DeviceIndependentBitmap‑Objekts ([MS-WMF] Abschnitt 2.2.2.9) enthält. Es muss nicht<br/>            zusammenhängend mit dem festen Teil des EMR_CREATEDIBPATTERNBRUSHPT‑Datensatzes sein. |
| ih_brush | int | r/w | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die den Index des monochromen<br/>            Musterpinselobjekts in der EMF‑Objekttabelle (Abschnitt 3.1.1.1) angibt. Dieser Index MUSS gespeichert werden, damit<br/>            dieses Objekt wiederverwendet oder geändert werden kann. |
| size | int | r/w | Liest oder setzt die Größe des Datensatzes |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Ruft ab oder legt den Typ fest. |
| usage | [EmfDibColors](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfdibcolors/) | r/w | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die angibt, wie Werte in der Farbtabelle im DIB‑Header zu interpretieren sind.<br/>            Dieser Wert MUSS in der DIBColors‑Aufzählung (Abschnitt 2.1.9) liegen. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initialisiert eine neue Instanz der [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) Klasse. |
| [create_from_type(type)](#create_from_type_type_2) | Initialisiert eine neue Instanz der [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) Klasse. |


### Constructor: EmfCreateMonoBrush(source) {#EmfCreateMonoBrush_source_1}


```
 EmfCreateMonoBrush(source) 
```

Initialisiert eine neue Instanz der Klasse [EmfCreateMonoBrush](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfcreatemonobrush/).

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


