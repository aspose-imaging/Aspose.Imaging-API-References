---
title: "EmfCommentEmfSpool"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il record EMR_COMMENT_EMFSPOOL contiene record EMFSPOOL incorporati."
type: docs
weight: 28
url: /it/java/com.aspose.imaging.fileformats.emf.emf.records/emfcommentemfspool/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfCommentRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype)
```
public final class EmfCommentEmfSpool extends EmfCommentRecordType
```

Il record EMR\\_COMMENT\\_EMFSPOOL contiene record EMFSPOOL incorporati. Nota: i campi che non sono descritti in questa sezione sono specificati nella sezione 2.3.3.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfCommentEmfSpool(EmfRecord source)](#EmfCommentEmfSpool-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inizializza una nuova istanza della classe `EmfCommentEmfSpool`. |
| [EmfCommentEmfSpool()](#EmfCommentEmfSpool--) | Inizializza una nuova istanza della classe `EmfCommentEmfSpool`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getCommentIdentifier()](#getCommentIdentifier--) | Ottiene o imposta un intero senza segno a 32 bit che identifica questo record di commento come contenente record EMFSPOOL. |
| [setCommentIdentifier(int value)](#setCommentIdentifier-int-) | Ottiene o imposta un intero senza segno a 32 bit che identifica questo record di commento come contenente record EMFSPOOL. |
| [getEmfSpoolRecordIdentifier()](#getEmfSpoolRecordIdentifier--) | Ottiene o imposta un intero senza segno a 32 bit che identifica il tipo di record EMR\\_COMMENT\\_EMFSPOOL. |
| [setEmfSpoolRecordIdentifier(int value)](#setEmfSpoolRecordIdentifier-int-) | Ottiene o imposta un intero senza segno a 32 bit che identifica il tipo di record EMR\\_COMMENT\\_EMFSPOOL. |
| [getEmfSpoolRecords()](#getEmfSpoolRecords--) | Ottiene o imposta un array di byte a lunghezza variabile che contiene uno o più record di definizione font EMFSPOOL ([MS-EMFSPOOL] sezione 2.2.3.3). |
| [setEmfSpoolRecords(EmfSpoolFontDefinitionRecordType[] value)](#setEmfSpoolRecords-com.aspose.imaging.fileformats.emf.emfspool.records.EmfSpoolFontDefinitionRecordType---) | Ottiene o imposta un array di byte a lunghezza variabile che contiene uno o più record di definizione font EMFSPOOL ([MS-EMFSPOOL] sezione 2.2.3.3). |
### EmfCommentEmfSpool(EmfRecord source) {#EmfCommentEmfSpool-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfCommentEmfSpool(EmfRecord source)
```


Inizializza una nuova istanza della classe `EmfCommentEmfSpool`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La sorgente. |

### EmfCommentEmfSpool() {#EmfCommentEmfSpool--}
```
public EmfCommentEmfSpool()
```


Inizializza una nuova istanza della classe `EmfCommentEmfSpool`.

### getCommentIdentifier() {#getCommentIdentifier--}
```
public int getCommentIdentifier()
```


Ottiene o imposta un intero senza segno a 32 bit che identifica questo record di commento come contenente record EMFSPOOL. Il valore 0x00000000 identifica questo come un record EMR\\_COMMENT\\_EMFSPOOL.

**Returns:**
int
### setCommentIdentifier(int value) {#setCommentIdentifier-int-}
```
public void setCommentIdentifier(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che identifica questo record di commento come contenente record EMFSPOOL. Il valore 0x00000000 identifica questo come un record EMR\\_COMMENT\\_EMFSPOOL.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getEmfSpoolRecordIdentifier() {#getEmfSpoolRecordIdentifier--}
```
public int getEmfSpoolRecordIdentifier()
```


Ottiene o imposta un intero senza segno a 32 bit che identifica il tipo di record EMR\\_COMMENT\\_EMFSPOOL.

**Returns:**
int
### setEmfSpoolRecordIdentifier(int value) {#setEmfSpoolRecordIdentifier-int-}
```
public void setEmfSpoolRecordIdentifier(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che identifica il tipo di record EMR\\_COMMENT\\_EMFSPOOL.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getEmfSpoolRecords() {#getEmfSpoolRecords--}
```
public EmfSpoolFontDefinitionRecordType[] getEmfSpoolRecords()
```


Ottiene o imposta un array di byte a lunghezza variabile che contiene uno o più record di definizione font EMFSPOOL ([MS-EMFSPOOL] sezione 2.2.3.3).

**Returns:**
com.aspose.imaging.fileformats.emf.emfspool.records.EmfSpoolFontDefinitionRecordType[]
### setEmfSpoolRecords(EmfSpoolFontDefinitionRecordType[] value) {#setEmfSpoolRecords-com.aspose.imaging.fileformats.emf.emfspool.records.EmfSpoolFontDefinitionRecordType---}
```
public void setEmfSpoolRecords(EmfSpoolFontDefinitionRecordType[] value)
```


Ottiene o imposta un array di byte a lunghezza variabile che contiene uno o più record di definizione font EMFSPOOL ([MS-EMFSPOOL] sezione 2.2.3.3).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [EmfSpoolFontDefinitionRecordType\[\]](../../com.aspose.imaging.fileformats.emf.emfspool.records/emfspoolfontdefinitionrecordtype) |  |

