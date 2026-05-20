---
title: "EmfMetafileHeader"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "I tipi di record EMR_HEADER definiscono i punti di partenza dei metafile EMF e specificano le proprietà del dispositivo su cui è stata creata l'immagine nel metafile."
type: docs
weight: 70
url: /it/java/com.aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord)
```
public class EmfMetafileHeader extends EmfRecord
```

Il tipo di record EMR\_HEADER definisce i punti di partenza dei metafile EMF e specifica le proprietà del dispositivo su cui è stata creata l'immagine nel metafile. Le informazioni nel record di intestazione rendono possibile che i metafile EMF siano indipendenti da qualsiasi dispositivo di output specifico. Il valore del campo Size può essere usato per distinguere tra i diversi tipi di record EMR\_HEADER elencati in precedenza in questa sezione. Esistono tre intestazioni possibili: l'intestazione base, che è il record EmfMetafileHeader. La parte a dimensione fissa di questa intestazione è di 88 byte e contiene un oggetto Header. La prima intestazione di estensione, che è il record EmfMetafileHeaderExtension1. La parte a dimensione fissa di questa intestazione è di 100 byte e contiene un oggetto Header e un oggetto HeaderExtension1 (sezione 2.2.10). La seconda intestazione di estensione, che è il record EmfMetafileHeaderExtension2. La parte a dimensione fissa di questa intestazione è di 108 byte e contiene un oggetto Header, un oggetto HeaderExtension1 e un oggetto HeaderExtension2 (sezione 2.2.11).
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfMetafileHeader(EmfRecord record)](#EmfMetafileHeader-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inizializza una nuova istanza della classe `EmfMetafileHeader`. |
| [EmfMetafileHeader()](#EmfMetafileHeader--) | Inizializza una nuova istanza della classe `EmfMetafileHeader`. |
| [EmfMetafileHeader(EmfMetafileHeader header)](#EmfMetafileHeader-com.aspose.imaging.fileformats.emf.emf.records.EmfMetafileHeader-) | Inizializza una nuova istanza della classe `EmfMetafileHeader`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getEmfHeader()](#getEmfHeader--) | Ottiene un oggetto Header (sezione 2.2.9), che contiene informazioni sul contenuto e sulla struttura del metafile |
| [setEmfHeader(EmfHeaderObject value)](#setEmfHeader-com.aspose.imaging.fileformats.emf.emf.objects.EmfHeaderObject-) | Imposta un oggetto Header (sezione 2.2.9), che contiene informazioni sul contenuto e sulla struttura del metafile |
| [getEmfHeaderRecordBuffer()](#getEmfHeaderRecordBuffer--) | Ottiene un array opzionale di byte che contiene il resto del record di intestazione EMF. |
| [setEmfHeaderRecordBuffer(byte[] value)](#setEmfHeaderRecordBuffer-byte---) | Imposta un array opzionale di byte che contiene il resto del record di intestazione EMF. |
| [getEmfDescriptionBuffer()](#getEmfDescriptionBuffer--) | Ottiene il buffer di descrizione EMF Un array opzionale di byte che contiene la stringa di descrizione EMF, che non è necessario sia contiguo con la parte fissa del record EmfMetafileHeader. |
| [setEmfDescriptionBuffer(byte[] value)](#setEmfDescriptionBuffer-byte---) | Imposta il buffer di descrizione EMF Un array opzionale di byte che contiene la stringa di descrizione EMF, che non è necessario sia contiguo con la parte fissa del record EmfMetafileHeader. |
| [getEmfDescription()](#getEmfDescription--) | Ottiene la descrizione EMF Una stringa Unicode UTF16-LE opzionale, terminata da null, di lunghezza e contenuto arbitrari. |
| [setEmfDescription(String value)](#setEmfDescription-java.lang.String-) | Imposta la descrizione EMF Una stringa Unicode UTF16-LE opzionale, terminata da null, di lunghezza e contenuto arbitrari. |
### EmfMetafileHeader(EmfRecord record) {#EmfMetafileHeader-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfMetafileHeader(EmfRecord record)
```


Inizializza una nuova istanza della classe `EmfMetafileHeader`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| record | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Il record. |

### EmfMetafileHeader() {#EmfMetafileHeader--}
```
public EmfMetafileHeader()
```


Inizializza una nuova istanza della classe `EmfMetafileHeader`.

### EmfMetafileHeader(EmfMetafileHeader header) {#EmfMetafileHeader-com.aspose.imaging.fileformats.emf.emf.records.EmfMetafileHeader-}
```
public EmfMetafileHeader(EmfMetafileHeader header)
```


Inizializza una nuova istanza della classe `EmfMetafileHeader`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| header | [EmfMetafileHeader](../../com.aspose.imaging.fileformats.emf.emf.records/emfmetafileheader) | L'intestazione. |

### getEmfHeader() {#getEmfHeader--}
```
public EmfHeaderObject getEmfHeader()
```


Ottiene un oggetto Header (sezione 2.2.9), che contiene informazioni sul contenuto e sulla struttura del metafile

**Returns:**
[EmfHeaderObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfheaderobject)
### setEmfHeader(EmfHeaderObject value) {#setEmfHeader-com.aspose.imaging.fileformats.emf.emf.objects.EmfHeaderObject-}
```
public void setEmfHeader(EmfHeaderObject value)
```


Imposta un oggetto Header (sezione 2.2.9), che contiene informazioni sul contenuto e sulla struttura del metafile

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [EmfHeaderObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfheaderobject) |  |

### getEmfHeaderRecordBuffer() {#getEmfHeaderRecordBuffer--}
```
public byte[] getEmfHeaderRecordBuffer()
```


Ottiene un array opzionale di byte che contiene il resto del record di intestazione EMF. La dimensione di questo campo DEVE essere un multiplo di 4 byte

**Returns:**
byte[]
### setEmfHeaderRecordBuffer(byte[] value) {#setEmfHeaderRecordBuffer-byte---}
```
public void setEmfHeaderRecordBuffer(byte[] value)
```


Imposta un array opzionale di byte che contiene il resto del record di intestazione EMF. La dimensione di questo campo DEVE essere un multiplo di 4 byte

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte[] |  |

### getEmfDescriptionBuffer() {#getEmfDescriptionBuffer--}
```
public byte[] getEmfDescriptionBuffer()
```


Ottiene il buffer di descrizione EMF Un array opzionale di byte che contiene la stringa di descrizione EMF, che non è necessario sia contiguo con la parte fissa del record EmfMetafileHeader. Di conseguenza, il campo in questo buffer etichettato "UndefinedSpace" è opzionale e DEVE essere ignorato.

**Returns:**
byte[]
### setEmfDescriptionBuffer(byte[] value) {#setEmfDescriptionBuffer-byte---}
```
public void setEmfDescriptionBuffer(byte[] value)
```


Imposta il buffer di descrizione EMF Un array opzionale di byte che contiene la stringa di descrizione EMF, che non è necessario sia contiguo con la parte fissa del record EmfMetafileHeader. Di conseguenza, il campo in questo buffer etichettato "UndefinedSpace" è opzionale e DEVE essere ignorato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte[] |  |

### getEmfDescription() {#getEmfDescription--}
```
public String getEmfDescription()
```


Ottiene la descrizione EMF Una stringa Unicode UTF16-LE opzionale, terminata da null, di lunghezza e contenuto arbitrari. La sua posizione nel record e il numero di caratteri sono specificati rispettivamente dai campi offDescription e nDescription in EmfHeader. Se il valore di uno dei due campi è zero, non è presente alcuna stringa di descrizione.

**Returns:**
java.lang.String
### setEmfDescription(String value) {#setEmfDescription-java.lang.String-}
```
public void setEmfDescription(String value)
```


Imposta la descrizione EMF Una stringa Unicode UTF16-LE opzionale, terminata da null, di lunghezza e contenuto arbitrari. La sua posizione nel record e il numero di caratteri sono specificati rispettivamente dai campi offDescription e nDescription in EmfHeader. Se il valore di uno dei due campi è zero, non è presente alcuna stringa di descrizione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

