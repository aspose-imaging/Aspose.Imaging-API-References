---
title: "EmfCommentRecordType"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "I tipi di record di commento definiscono formati per specificare record di incorporamento di dati privati arbitrari in altri formati di metafile e per aggiungere comandi nuovi o a scopo speciale."
type: docs
weight: 32
url: /it/java/com.aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord)
```
public abstract class EmfCommentRecordType extends EmfRecord
```

I tipi di record di commento definiscono formati per specificare dati privati arbitrari, incorporare record in altri formati di metafile e aggiungere comandi nuovi o a scopo speciale.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getDataSize()](#getDataSize--) | Ottiene o imposta un intero senza segno a 32 bit che specifica la dimensione, in byte, dei campi CommentIdentifier e CommentRecordParm nel campo RecordBuffer che segue. |
| [setDataSize(int value)](#setDataSize-int-) | Ottiene o imposta un intero senza segno a 32 bit che specifica la dimensione, in byte, dei campi CommentIdentifier e CommentRecordParm nel campo RecordBuffer che segue. |
| [getCommentIdentifier()](#getCommentIdentifier--) | Ottiene o imposta l'identificatore del commento. |
| [setCommentIdentifier(int value)](#setCommentIdentifier-int-) | Ottiene o imposta l'identificatore del commento. |
### getDataSize() {#getDataSize--}
```
public int getDataSize()
```


Ottiene o imposta un intero senza segno a 32 bit che specifica la dimensione, in byte, dei campi CommentIdentifier e CommentRecordParm nel campo RecordBuffer che segue. NON DEVE includere la dimensione di se stesso o la dimensione del campo AlignmentPadding, se presente

**Returns:**
int
### setDataSize(int value) {#setDataSize-int-}
```
public void setDataSize(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che specifica la dimensione, in byte, dei campi CommentIdentifier e CommentRecordParm nel campo RecordBuffer che segue. NON DEVE includere la dimensione di se stesso o la dimensione del campo AlignmentPadding, se presente

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getCommentIdentifier() {#getCommentIdentifier--}
```
public int getCommentIdentifier()
```


Ottiene o imposta l'identificatore del commento.

Valore: l'identificatore del commento.

**Returns:**
int
### setCommentIdentifier(int value) {#setCommentIdentifier-int-}
```
public void setCommentIdentifier(int value)
```


Ottiene o imposta l'identificatore del commento.

Valore: l'identificatore del commento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

