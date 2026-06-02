---
title: "Classe EmfMetafileHeader"
type: docs
weight: 610
url: /it/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/
---

**Summary:** The EMR_HEADER record types define the starting points of EMF metafiles<br/>            and specify properties of the device on which the image in the metafile<br/>            was created. The information in the header record makes it possible for<br/>            EMF metafiles to be independent of any specific output device.<br/>            The value of the Size field can be used to distinguish between the different<br/>            EMR_HEADER record types listed earlier in this section.<br/>            There are three possible headers:<br/>            The base header, which is the EmfMetafileHeader record.<br/>            The fixed-size part of this header is 88 bytes, and it contains a Header object.<br/>            The first extension header, which is the EmfMetafileHeaderExtension1 record.<br/>            The fixed-size part of this header is 100 bytes, and it contains a Header object<br/>            and a HeaderExtension1 object (section 2.2.10).<br/>            The second extension header, which is the EmfMetafileHeaderExtension2 record.<br/>            The fixed-size part of this header is 108 bytes, and it contains a Header object,<br/>            a HeaderExtension1 object, and a HeaderExtension2 object (section 2.2.11).

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfMetafileHeader

**Inheritance:** EmfRecord

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [EmfMetafileHeader()](#EmfMetafileHeader__1) | Inizializza una nuova istanza della classe [EmfMetafileHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/). |
| [EmfMetafileHeader(header)](#EmfMetafileHeader_header_2) | Inizializza una nuova istanza della classe [EmfMetafileHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/). |
| [EmfMetafileHeader(record)](#EmfMetafileHeader_record_3) | Inizializza una nuova istanza della classe [EmfMetafileHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| emf_description | string | r/w | Ottiene o imposta la descrizione EMF<br/>            Una stringa Unicode UTF16-LE opzionale, terminata da null, di lunghezza e contenuto arbitrari. <br/>            La sua posizione nel record e il numero di caratteri sono specificati dai campi offDescription <br/>            e nDescription, rispettivamente, in EmfHeader. Se il valore di uno dei due campi <br/>            è zero, non è presente alcuna stringa di descrizione. |
| emf_description_buffer | System.Byte | r/w | Ottiene o imposta il buffer della descrizione EMF<br/>            Un array di byte opzionale che contiene la stringa di descrizione EMF, che non è necessario <br/>            essere contiguo con la parte fissa del record EmfMetafileHeader. Di conseguenza, il campo in questo buffer etichettato "UndefinedSpace" <br/>            è opzionale e DEVE essere ignorato. |
| emf_header | [EmfHeaderObject](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/) | r/w | Ottiene o imposta un oggetto Header (sezione 2.2.9), che contiene informazioni sul contenuto<br/>            e sulla struttura del metafile |
| emf_header_record_buffer | System.Byte | r/w | Ottiene o imposta un array di byte opzionale che contiene il resto del record dell'intestazione EMF. <br/>            La dimensione di questo campo DEVE essere un multiplo di 4 byte |
| dimensione | int | r/w | Ottiene o imposta la dimensione del record |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Ottiene o imposta il tipo. |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [create_from_header(header)](#create_from_header_header_1) | Inizializza una nuova istanza della classe [EmfMetafileHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/). |
| [create_from_record(record)](#create_from_record_record_2) | Inizializza una nuova istanza della classe [EmfMetafileHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/). |
| [create_from_type(type)](#create_from_type_type_3) | Inizializza una nuova istanza della classe [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfMetafileHeader() {#EmfMetafileHeader__1}


```
 EmfMetafileHeader() 
```

Inizializza una nuova istanza della classe [EmfMetafileHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/).

### Constructor: EmfMetafileHeader(header) {#EmfMetafileHeader_header_2}


```
 EmfMetafileHeader(header) 
```

Inizializza una nuova istanza della classe [EmfMetafileHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| header | [EmfMetafileHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/) | L'intestazione. |

### Constructor: EmfMetafileHeader(record) {#EmfMetafileHeader_record_3}


```
 EmfMetafileHeader(record) 
```

Inizializza una nuova istanza della classe [EmfMetafileHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| record | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) | Il record. |

### Method: create_from_header(header)  [static] {#create_from_header_header_1}


```
 create_from_header(header) 
```

Inizializza una nuova istanza della classe [EmfMetafileHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| header | [EmfMetafileHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/) | L'intestazione. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [EmfMetafileHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/) |  |


### Method: create_from_record(record)  [static] {#create_from_record_record_2}


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


### Method: create_from_type(type)  [static] {#create_from_type_type_3}


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


