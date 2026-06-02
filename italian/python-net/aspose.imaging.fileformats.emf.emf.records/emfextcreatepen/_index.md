---
title: "EmfExtCreatePen Classe"
type: docs
weight: 430
url: /it/python-net/aspose.imaging.fileformats.emf.emf.records/emfextcreatepen/
---

**Summary:** The EMR_EXTCREATEPEN record defines an extended logical pen for graphics operations. An<br/>            optional DIB can be specified to use as the line style.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfExtCreatePen

**Inheritance:** EmfObjectCreationRecordType

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [EmfExtCreatePen()](#EmfExtCreatePen__1) | Inizializza una nuova istanza della classe [EmfExtCreatePen](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfextcreatepen/). |
| [EmfExtCreatePen(record)](#EmfExtCreatePen_record_2) | Inizializza una nuova istanza della classe [EmfExtCreatePen](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfextcreatepen/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| bitmap_buffer | [WmfDeviceIndependentBitmap](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap/) | r/w | Ottiene o imposta un buffer opzionale contenente un DIB compresso nella forma di un oggetto WMF DeviceIndependentBitmap<br/>            ([MS-WMF] sezione 2.2.2.9). Non è necessario che sia contiguo con la parte fissa del record EMR_EXTCREATEPEN |
| elp | [EmfLogPenEx](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emflogpenex/) | r/w | Ottiene o imposta un oggetto LogPenEx (sezione 2.2.20) che specifica una penna logica estesa <br/>            con attributi che includono un array opzionale di stili di linea. |
| ih_pen | int | r/w | Ottiene o imposta un intero senza segno a 32 bit che specifica l'indice dell'oggetto penna logica estesa <br/>            nella EMF Object Table (sezione 3.1.1.1). <br/>            Questo indice DEVE essere salvato affinché l'oggetto possa essere riutilizzato o modificato. |
| dimensione | int | r/w | Ottiene o imposta la dimensione del record |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Ottiene o imposta il tipo. |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Inizializza una nuova istanza della classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Inizializza una nuova istanza della classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfExtCreatePen() {#EmfExtCreatePen__1}


```
 EmfExtCreatePen() 
```

Inizializza una nuova istanza della classe [EmfExtCreatePen](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfextcreatepen/).

### Constructor: EmfExtCreatePen(record) {#EmfExtCreatePen_record_2}


```
 EmfExtCreatePen(record) 
```

Inizializza una nuova istanza della classe [EmfExtCreatePen](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfextcreatepen/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| record | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) | Il record. |

### Method: create_from_record(source)  [static] {#create_from_record_source_1}


```
 create_from_record(source) 
```

Inizializza una nuova istanza della classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| source | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) | La sorgente. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) |  |


### Method: create_from_type(type)  [static] {#create_from_type_type_2}


```
 create_from_type(type) 
```

Inizializza una nuova istanza della classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | Il tipo di record. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) |  |


