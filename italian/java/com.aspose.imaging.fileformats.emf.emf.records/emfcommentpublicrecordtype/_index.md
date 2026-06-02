---
title: "EmfCommentPublicRecordType"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "I tipi di record EMR_COMMENT_PUBLIC specificano estensioni all'elaborazione EMF."
type: docs
weight: 31
url: /it/java/com.aspose.imaging.fileformats.emf.emf.records/emfcommentpublicrecordtype/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfCommentRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype)
```
public abstract class EmfCommentPublicRecordType extends EmfCommentRecordType
```

I tipi di record EMR\_COMMENT\_PUBLIC specificano estensioni all'elaborazione EMF.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getCommentIdentifier()](#getCommentIdentifier--) | Ottiene o imposta un intero senza segno a 32 bit che identifica questo record di commento come contenente dati pubblici. |
| [setCommentIdentifier(int value)](#setCommentIdentifier-int-) | Ottiene o imposta un intero senza segno a 32 bit che identifica questo record di commento come contenente dati pubblici. |
| [getPublicCommentIdentifier()](#getPublicCommentIdentifier--) | Ottiene o imposta un intero senza segno a 32 bit che identifica il tipo di record di commento pubblico. |
| [setPublicCommentIdentifier(long value)](#setPublicCommentIdentifier-long-) | Ottiene o imposta un intero senza segno a 32 bit che identifica il tipo di record di commento pubblico. |
### getCommentIdentifier() {#getCommentIdentifier--}
```
public int getCommentIdentifier()
```


Ottiene o imposta un intero senza segno a 32 bit che identifica questo record di commento come contenente dati pubblici. Il valore 0x43494447, che è la stringa ASCII \"CIDG\", identifica questo come un record EMR\_COMMENT\_PUBLIC.

**Returns:**
int
### setCommentIdentifier(int value) {#setCommentIdentifier-int-}
```
public void setCommentIdentifier(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che identifica questo record di commento come contenente dati pubblici. Il valore 0x43494447, che è la stringa ASCII \"CIDG\", identifica questo come un record EMR\_COMMENT\_PUBLIC.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getPublicCommentIdentifier() {#getPublicCommentIdentifier--}
```
public long getPublicCommentIdentifier()
```


Ottiene o imposta un intero senza segno a 32 bit che identifica il tipo di record di commento pubblico. Questo DOVREBBE essere uno dei valori elencati nella tabella precedente, specificati nell'enumerazione EmrComment (sezione 2.1.10), a meno che non siano stati implementati ulteriori tipi di record di commento pubblico sul server di stampa.

**Returns:**
long
### setPublicCommentIdentifier(long value) {#setPublicCommentIdentifier-long-}
```
public void setPublicCommentIdentifier(long value)
```


Ottiene o imposta un intero senza segno a 32 bit che identifica il tipo di record di commento pubblico. Questo DOVREBBE essere uno dei valori elencati nella tabella precedente, specificati nell'enumerazione EmrComment (sezione 2.1.10), a meno che non siano stati implementati ulteriori tipi di record di commento pubblico sul server di stampa.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | long |  |

