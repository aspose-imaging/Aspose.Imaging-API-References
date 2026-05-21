---
title: "EmfSetIcmProfileW"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il record EMR_SETICMPROFILEW specifica un profilo colore in un file il cui nome è composto da caratteri Unicode per l'output grafico."
type: docs
weight: 127
url: /it/java/com.aspose.imaging.fileformats.emf.emf.records/emfseticmprofilew/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSetIcmProfileW extends EmfStateRecordType
```

Il record EMR\_SETICMPROFILEW specifica un profilo colore in un file con un nome costituito da caratteri Unicode, per l'output grafico.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfSetIcmProfileW(EmfRecord source)](#EmfSetIcmProfileW-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inizializza una nuova istanza della classe `EmfSetIcmProfileW`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getDwFlags()](#getDwFlags--) | Ottiene o imposta un intero senza segno a 32 bit che contiene i flag del profilo colore. |
| [setDwFlags(int value)](#setDwFlags-int-) | Ottiene o imposta un intero senza segno a 32 bit che contiene i flag del profilo colore. |
| [getCbName()](#getCbName--) | Ottiene o imposta un intero senza segno a 32 bit che specifica il numero di byte nel nome Unicode UTF16-LE del profilo colore desiderato. |
| [setCbName(int value)](#setCbName-int-) | Ottiene o imposta un intero senza segno a 32 bit che specifica il numero di byte nel nome Unicode UTF16-LE del profilo colore desiderato. |
| [getCbData()](#getCbData--) | Ottiene o imposta un intero senza segno a 32 bit che specifica la dimensione dei dati del profilo colore, se allegati. |
| [setCbData(int value)](#setCbData-int-) | Ottiene o imposta un intero senza segno a 32 bit che specifica la dimensione dei dati del profilo colore, se allegati. |
| [getData()](#getData--) | Ottiene o imposta un array di dimensione (cbName + cbData) in byte, che specifica il nome UTF16-LE e i dati grezzi del profilo colore desiderato. |
| [setData(byte[] value)](#setData-byte---) | Ottiene o imposta un array di dimensione (cbName + cbData) in byte, che specifica il nome UTF16-LE e i dati grezzi del profilo colore desiderato. |
| [getName()](#getName--) | Ottiene il nome |
| [getRawData()](#getRawData--) | Ottiene i dati grezzi |
### EmfSetIcmProfileW(EmfRecord source) {#EmfSetIcmProfileW-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetIcmProfileW(EmfRecord source)
```


Inizializza una nuova istanza della classe `EmfSetIcmProfileW`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La sorgente. |

### getDwFlags() {#getDwFlags--}
```
public int getDwFlags()
```


Ottiene o imposta un intero senza segno a 32 bit che contiene i flag del profilo colore.

**Returns:**
int
### setDwFlags(int value) {#setDwFlags-int-}
```
public void setDwFlags(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che contiene i flag del profilo colore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getCbName() {#getCbName--}
```
public int getCbName()
```


Ottiene o imposta un intero senza segno a 32 bit che specifica il numero di byte nel nome Unicode UTF16-LE del profilo colore desiderato.

**Returns:**
int
### setCbName(int value) {#setCbName-int-}
```
public void setCbName(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che specifica il numero di byte nel nome Unicode UTF16-LE del profilo colore desiderato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getCbData() {#getCbData--}
```
public int getCbData()
```


Ottiene o imposta un intero senza segno a 32 bit che specifica la dimensione dei dati del profilo colore, se allegati.

**Returns:**
int
### setCbData(int value) {#setCbData-int-}
```
public void setCbData(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che specifica la dimensione dei dati del profilo colore, se allegati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getData() {#getData--}
```
public byte[] getData()
```


Ottiene o imposta un array di dimensione (cbName + cbData) in byte, che specifica il nome UTF16-LE e i dati grezzi del profilo colore desiderato.

**Returns:**
byte[]
### setData(byte[] value) {#setData-byte---}
```
public void setData(byte[] value)
```


Ottiene o imposta un array di dimensione (cbName + cbData) in byte, che specifica il nome UTF16-LE e i dati grezzi del profilo colore desiderato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte[] |  |

### getName() {#getName--}
```
public String getName()
```


Ottiene il nome

**Returns:**
java.lang.String
### getRawData() {#getRawData--}
```
public byte[] getRawData()
```


Ottiene i dati grezzi

**Returns:**
byte[]
