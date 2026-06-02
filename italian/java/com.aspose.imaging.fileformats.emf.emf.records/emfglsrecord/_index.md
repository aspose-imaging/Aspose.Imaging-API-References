---
title: "EmfGlsRecord"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il record EMR_GLSRECORD specifica una funzione OpenGL."
type: docs
weight: 64
url: /it/java/com.aspose.imaging.fileformats.emf.emf.records/emfglsrecord/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfOpenGlRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfopenglrecordtype)
```
public final class EmfGlsRecord extends EmfOpenGlRecordType
```

Il record EMR\_GLSRECORD specifica una funzione OpenGL.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfGlsRecord(EmfRecord source)](#EmfGlsRecord-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inizializza una nuova istanza della classe `EmfGlsRecord`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getCbData()](#getCbData--) | Ottiene o imposta un intero senza segno a 32 bit che specifica la dimensione, in byte, del campo Data. |
| [setCbData(int value)](#setCbData-int-) | Ottiene o imposta un intero senza segno a 32 bit che specifica la dimensione, in byte, del campo Data. |
| [getData()](#getData--) | Ottiene o imposta un array opzionale di byte di lunghezza cbData che specifica i dati per la funzione OpenGL. |
| [setData(byte[] value)](#setData-byte---) | Ottiene o imposta un array opzionale di byte di lunghezza cbData che specifica i dati per la funzione OpenGL. |
### EmfGlsRecord(EmfRecord source) {#EmfGlsRecord-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfGlsRecord(EmfRecord source)
```


Inizializza una nuova istanza della classe `EmfGlsRecord`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La sorgente. |

### getCbData() {#getCbData--}
```
public int getCbData()
```


Ottiene o imposta un intero senza segno a 32 bit che specifica la dimensione, in byte, del campo Data. Se questo valore è zero, nessun dato è allegato a questo record.

**Returns:**
int
### setCbData(int value) {#setCbData-int-}
```
public void setCbData(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che specifica la dimensione, in byte, del campo Data. Se questo valore è zero, nessun dato è allegato a questo record.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getData() {#getData--}
```
public byte[] getData()
```


Ottiene o imposta un array opzionale di byte di lunghezza cbData che specifica i dati per la funzione OpenGL.

**Returns:**
byte[]
### setData(byte[] value) {#setData-byte---}
```
public void setData(byte[] value)
```


Ottiene o imposta un array opzionale di byte di lunghezza cbData che specifica i dati per la funzione OpenGL.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte[] |  |

