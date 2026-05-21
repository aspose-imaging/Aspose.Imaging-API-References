---
title: "EmfCommentEmfPlus"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il record EMR_COMMENT_EMFPLUS contiene record EMF incorporati."
type: docs
weight: 27
url: /it/java/com.aspose.imaging.fileformats.emf.emf.records/emfcommentemfplus/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfCommentRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype)
```
public final class EmfCommentEmfPlus extends EmfCommentRecordType
```

Il record EMR\\_COMMENT\\_EMFPLUS contiene record EMF+ incorporati. Nota: i campi che non sono descritti in questa sezione sono specificati nella sezione 2.3.3.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfCommentEmfPlus(EmfRecord source)](#EmfCommentEmfPlus-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inizializza una nuova istanza della classe `EmfCommentEmfPlus`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getCommentIdentifier()](#getCommentIdentifier--) | Ottiene o imposta un intero senza segno a 32 bit che identifica questo record di commento come contenente record EMF+. |
| [setCommentIdentifier(int value)](#setCommentIdentifier-int-) | Ottiene o imposta un intero senza segno a 32 bit che identifica questo record di commento come contenente record EMF+. |
| [getEmfPlusRecords()](#getEmfPlusRecords--) | Ottiene o imposta un array di byte che contiene uno o più record EMF+ ([MS-EMFPLUS] sezione 2.3.1). |
| [setEmfPlusRecords(EmfPlusRecord[] value)](#setEmfPlusRecords-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord---) | Ottiene o imposta un array di byte che contiene uno o più record EMF+ ([MS-EMFPLUS] sezione 2.3.1). |
### EmfCommentEmfPlus(EmfRecord source) {#EmfCommentEmfPlus-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfCommentEmfPlus(EmfRecord source)
```


Inizializza una nuova istanza della classe `EmfCommentEmfPlus`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La sorgente. |

### getCommentIdentifier() {#getCommentIdentifier--}
```
public int getCommentIdentifier()
```


Ottiene o imposta un intero senza segno a 32 bit che identifica questo record di commento come contenente record EMF+ . Il valore 0x2B464D45, che è la stringa ASCII \"+FME\", identifica questo come un record EMR\\_COMMENT\\_EMFPLUS.

**Returns:**
int
### setCommentIdentifier(int value) {#setCommentIdentifier-int-}
```
public void setCommentIdentifier(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che identifica questo record di commento come contenente record EMF+ . Il valore 0x2B464D45, che è la stringa ASCII \"+FME\", identifica questo come un record EMR\\_COMMENT\\_EMFPLUS.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getEmfPlusRecords() {#getEmfPlusRecords--}
```
public EmfPlusRecord[] getEmfPlusRecords()
```


Ottiene o imposta un array di byte che contiene uno o più record EMF+ ([MS-EMFPLUS] sezione 2.3.1).

**Returns:**
com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord[]
### setEmfPlusRecords(EmfPlusRecord[] value) {#setEmfPlusRecords-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord---}
```
public void setEmfPlusRecords(EmfPlusRecord[] value)
```


Ottiene o imposta un array di byte che contiene uno o più record EMF+ ([MS-EMFPLUS] sezione 2.3.1).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [EmfPlusRecord\[\]](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) |  |

