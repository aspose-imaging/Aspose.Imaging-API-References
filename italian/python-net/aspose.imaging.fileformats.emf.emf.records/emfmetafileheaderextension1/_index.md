---
title: "Classe EmfMetafileHeaderExtension1"
type: docs
weight: 620
url: /it/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/
---

**Summary:** The EmfMetafileHeaderExtension1 record is the header record used in the first extension to EMF metafiles.<br/>            Following the EmfHeaderExtension1 field, the remaining fields are optional and can be present in any order.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfMetafileHeaderExtension1

**Inheritance:** EmfMetafileHeader

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [EmfMetafileHeaderExtension1(header)](#EmfMetafileHeaderExtension1_header_1) | Inizializza una nuova istanza della classe [EmfMetafileHeaderExtension1](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/). |
| [EmfMetafileHeaderExtension1(header)](#EmfMetafileHeaderExtension1_header_2) | Inizializza una nuova istanza della classe [EmfMetafileHeaderExtension1](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| emf_description | string | r/w | Ottiene o imposta la descrizione EMF<br/>            Una stringa Unicode UTF16-LE opzionale, terminata da null, di lunghezza e contenuto arbitrari. <br/>            La sua posizione nel record e il numero di caratteri sono specificati dai campi offDescription <br/>            e nDescription, rispettivamente, in EmfHeader. Se il valore di uno dei due campi <br/>            è zero, non è presente alcuna stringa di descrizione. |
| emf_description_buffer | System.Byte | r/w | Ottiene o imposta il buffer della descrizione EMF<br/>            Un array di byte opzionale che contiene la stringa di descrizione EMF, che non è necessario <br/>            essere contiguo con la parte fissa del record EmfMetafileHeader. Di conseguenza, il campo in questo buffer etichettato "UndefinedSpace" <br/>            è opzionale e DEVE essere ignorato. |
| emf_header | [EmfHeaderObject](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/) | r/w | Ottiene o imposta un oggetto Header (sezione 2.2.9), che contiene informazioni sul contenuto<br/>            e sulla struttura del metafile |
| emf_header_extension1 | [EmfHeaderExtension1](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emfheaderextension1/) | r/w | Ottiene o imposta un oggetto HeaderExtension1, che specifica informazioni aggiuntive sull'immagine nel metafile. |
| emf_header_record_buffer | System.Byte | r/w | Ottiene o imposta un array di byte opzionale che contiene il resto del record dell'intestazione EMF. <br/>            La dimensione di questo campo DEVE essere un multiplo di 4 byte |
| emf_pixel_format_buffer | System.Byte | r/w | Ottiene o imposta un array di byte opzionale che contiene il descrittore del formato pixel EMF, che non è necessario <br/>            essere contiguo con la parte fissa del record EmfMetafileHeaderExtension1 o con la stringa di descrizione EMF. Di conseguenza, il campo in questo buffer etichettato "UndefinedSpace" è <br/>            opzionale e DEVE essere ignorato |
| dimensione | int | r/w | Ottiene o imposta la dimensione del record |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Ottiene o imposta il tipo. |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [create_from_header(header)](#create_from_header_header_1) | Inizializza una nuova istanza della classe [EmfMetafileHeaderExtension1](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/). |
| [create_from_header_extension1(header)](#create_from_header_extension1_header_2) | Inizializza una nuova istanza della classe [EmfMetafileHeaderExtension1](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/). |
| [create_from_record(record)](#create_from_record_record_3) | Inizializza una nuova istanza della classe [EmfMetafileHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/). |
| [create_from_type(type)](#create_from_type_type_4) | Inizializza una nuova istanza della classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfMetafileHeaderExtension1(header) {#EmfMetafileHeaderExtension1_header_1}


```
 EmfMetafileHeaderExtension1(header) 
```

Inizializza una nuova istanza della classe [EmfMetafileHeaderExtension1](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| header | [EmfMetafileHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/) | L'intestazione. |

### Constructor: EmfMetafileHeaderExtension1(header) {#EmfMetafileHeaderExtension1_header_2}


```
 EmfMetafileHeaderExtension1(header) 
```

Inizializza una nuova istanza della classe [EmfMetafileHeaderExtension1](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| header | [EmfMetafileHeaderExtension1](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/) | L'intestazione. |

### Method: create_from_header(header)  [static] {#create_from_header_header_1}


```
 create_from_header(header) 
```

Inizializza una nuova istanza della classe [EmfMetafileHeaderExtension1](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| header | [EmfMetafileHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/) | L'intestazione. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [EmfMetafileHeaderExtension1](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/) |  |


### Method: create_from_header_extension1(header)  [static] {#create_from_header_extension1_header_2}


```
 create_from_header_extension1(header) 
```

Inizializza una nuova istanza della classe [EmfMetafileHeaderExtension1](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| header | [EmfMetafileHeaderExtension1](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/) | L'intestazione. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [EmfMetafileHeaderExtension1](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/) |  |


### Method: create_from_record(record)  [static] {#create_from_record_record_3}


```
 create_from_record(record) 
```

Inizializza una nuova istanza della classe [EmfMetafileHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| record | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) | Il record. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [EmfMetafileHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/) |  |


### Method: create_from_type(type)  [static] {#create_from_type_type_4}


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


