---
title: "EmfCommentBeginGroup"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il record EMR_COMMENT_BEGINGROUP specifica l'inizio di un gruppo di record di disegno."
type: docs
weight: 26
url: /it/java/com.aspose.imaging.fileformats.emf.emf.records/emfcommentbegingroup/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfCommentRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype), [com.aspose.imaging.fileformats.emf.emf.records.EmfCommentPublicRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfcommentpublicrecordtype)
```
public final class EmfCommentBeginGroup extends EmfCommentPublicRecordType
```

Il record EMR\_COMMENT\_BEGINGROUP specifica l'inizio di un gruppo di record di disegno.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfCommentBeginGroup(EmfRecord source)](#EmfCommentBeginGroup-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inizializza una nuova istanza della classe `EmfCommentBeginGroup`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getRectangle()](#getRectangle--) | Ottiene o imposta un oggetto WMF RectL ([MS-WMF] sezione 2.2.2.19) che specifica il rettangolo di output in coordinate logiche. |
| [setRectangle(Rectangle value)](#setRectangle-com.aspose.imaging.Rectangle-) | Ottiene o imposta un oggetto WMF RectL ([MS-WMF] sezione 2.2.2.19) che specifica il rettangolo di output in coordinate logiche. |
| [getNDescription()](#getNDescription--) | Ottiene o imposta il numero di caratteri Unicode nella stringa di descrizione opzionale che segue. |
| [setNDescription(int value)](#setNDescription-int-) | Ottiene o imposta il numero di caratteri Unicode nella stringa di descrizione opzionale che segue. |
| [getDescription()](#getDescription--) | Ottiene o imposta una stringa Unicode opzionale terminata da null che descrive questo gruppo di record. |
| [setDescription(String value)](#setDescription-java.lang.String-) | Ottiene o imposta una stringa Unicode opzionale terminata da null che descrive questo gruppo di record. |
### EmfCommentBeginGroup(EmfRecord source) {#EmfCommentBeginGroup-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfCommentBeginGroup(EmfRecord source)
```


Inizializza una nuova istanza della classe `EmfCommentBeginGroup`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La sorgente. |

### getRectangle() {#getRectangle--}
```
public Rectangle getRectangle()
```


Ottiene o imposta un oggetto WMF RectL ([MS-WMF] sezione 2.2.2.19) che specifica il rettangolo di output in coordinate logiche.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setRectangle(Rectangle value) {#setRectangle-com.aspose.imaging.Rectangle-}
```
public void setRectangle(Rectangle value)
```


Ottiene o imposta un oggetto WMF RectL ([MS-WMF] sezione 2.2.2.19) che specifica il rettangolo di output in coordinate logiche.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getNDescription() {#getNDescription--}
```
public int getNDescription()
```


Ottiene o imposta il numero di caratteri Unicode nella stringa di descrizione opzionale che segue.

**Returns:**
int
### setNDescription(int value) {#setNDescription-int-}
```
public void setNDescription(int value)
```


Ottiene o imposta il numero di caratteri Unicode nella stringa di descrizione opzionale che segue.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getDescription() {#getDescription--}
```
public String getDescription()
```


Ottiene o imposta una stringa Unicode opzionale terminata da null che descrive questo gruppo di record.

**Returns:**
java.lang.String
### setDescription(String value) {#setDescription-java.lang.String-}
```
public void setDescription(String value)
```


Ottiene o imposta una stringa Unicode opzionale terminata da null che descrive questo gruppo di record.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

