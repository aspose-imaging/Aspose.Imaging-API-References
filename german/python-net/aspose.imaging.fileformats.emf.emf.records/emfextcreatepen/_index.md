---
title: "EmfExtCreatePen Klasse"
type: docs
weight: 430
url: /de/python-net/aspose.imaging.fileformats.emf.emf.records/emfextcreatepen/
---

**Summary:** The EMR_EXTCREATEPEN record defines an extended logical pen for graphics operations. An<br/>            optional DIB can be specified to use as the line style.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfExtCreatePen

**Inheritance:** EmfObjectCreationRecordType

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [EmfExtCreatePen()](#EmfExtCreatePen__1) | Initialisiert eine neue Instanz der [EmfExtCreatePen](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfextcreatepen/) Klasse. |
| [EmfExtCreatePen(record)](#EmfExtCreatePen_record_2) | Initialisiert eine neue Instanz der [EmfExtCreatePen](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfextcreatepen/) Klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| bitmap_buffer | [WmfDeviceIndependentBitmap](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap/) | r/w | Liest oder setzt einen optionalen Puffer, der ein gepacktes DIB in Form eines WMF DeviceIndependentBitmap-Objekts enthält<br/>            ([MS-WMF] Abschnitt 2.2.2.9). Es muss nicht zusammenhängend mit dem festen Teil des EMR_EXTCREATEPEN‑Datensatzes sein. |
| elp | [EmfLogPenEx](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emflogpenex/) | r/w | Liest oder setzt ein LogPenEx-Objekt (Abschnitt 2.2.20), das einen erweiterten logischen <br/>            Stift mit Attributen, einschließlich eines optionalen Linienstil-Arrays, spezifiziert. |
| ih_pen | int | r/w | Liest oder setzt einen 32‑Bit‑unsigned‑Integer, der den Index des erweiterten logischen <br/>            Stiftobjekts in der EMF‑Objekttabelle (Abschnitt 3.1.1.1) angibt. <br/>            Dieser Index MUSS gespeichert werden, damit dieses Objekt wiederverwendet oder geändert werden kann. |
| size | int | r/w | Liest oder setzt die Größe des Datensatzes |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Ruft ab oder legt den Typ fest. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initialisiert eine neue Instanz der [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) Klasse. |
| [create_from_type(type)](#create_from_type_type_2) | Initialisiert eine neue Instanz der [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) Klasse. |


### Constructor: EmfExtCreatePen() {#EmfExtCreatePen__1}


```
 EmfExtCreatePen() 
```

Initialisiert eine neue Instanz der [EmfExtCreatePen](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfextcreatepen/) Klasse.

### Constructor: EmfExtCreatePen(record) {#EmfExtCreatePen_record_2}


```
 EmfExtCreatePen(record) 
```

Initialisiert eine neue Instanz der [EmfExtCreatePen](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfextcreatepen/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| record | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) | Der Datensatz. |

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


