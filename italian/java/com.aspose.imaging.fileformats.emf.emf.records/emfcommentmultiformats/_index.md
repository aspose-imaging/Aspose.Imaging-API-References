---
title: "EmfCommentMultiFormats"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il record EMR_COMMENT_MULTIFORMATS specifica un'immagine in più formati grafici."
type: docs
weight: 30
url: /it/java/com.aspose.imaging.fileformats.emf.emf.records/emfcommentmultiformats/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfCommentRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype), [com.aspose.imaging.fileformats.emf.emf.records.EmfCommentPublicRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfcommentpublicrecordtype)
```
public final class EmfCommentMultiFormats extends EmfCommentPublicRecordType
```

Il record EMR\_COMMENT\_MULTIFORMATS specifica un'immagine in più formati grafici.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfCommentMultiFormats(EmfRecord source)](#EmfCommentMultiFormats-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inizializza una nuova istanza della classe `EmfCommentMultiFormats`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getOutputRect()](#getOutputRect--) | Ottiene o imposta un oggetto WMF RectL ([MS-WMF] sezione 2.2.2.19) che specifica il rettangolo di output, in coordinate logiche. |
| [setOutputRect(Rectangle value)](#setOutputRect-com.aspose.imaging.Rectangle-) | Ottiene o imposta un oggetto WMF RectL ([MS-WMF] sezione 2.2.2.19) che specifica il rettangolo di output, in coordinate logiche. |
| [getAFormats()](#getAFormats--) | Ottiene o imposta un array di lunghezza CountFormats di formati grafici, specificati da oggetti EmrFormat (sezione 2.2.4), in ordine di preferenza |
| [setAFormats(EmfFormat[] value)](#setAFormats-com.aspose.imaging.fileformats.emf.emf.objects.EmfFormat---) | Ottiene o imposta un array di lunghezza CountFormats di formati grafici, specificati da oggetti EmrFormat (sezione 2.2.4), in ordine di preferenza |
| [getFormatData()](#getFormatData--) | Ottiene o imposta un array di byte a lunghezza variabile contenente i dati dell'immagine per tutti i formati grafici contenuti in questo record. |
| [setFormatData(byte[][] value)](#setFormatData-byte-----) | Ottiene o imposta un array di byte a lunghezza variabile contenente i dati dell'immagine per tutti i formati grafici contenuti in questo record. |
### EmfCommentMultiFormats(EmfRecord source) {#EmfCommentMultiFormats-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfCommentMultiFormats(EmfRecord source)
```


Inizializza una nuova istanza della classe `EmfCommentMultiFormats`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La sorgente. |

### getOutputRect() {#getOutputRect--}
```
public Rectangle getOutputRect()
```


Ottiene o imposta un oggetto WMF RectL ([MS-WMF] sezione 2.2.2.19) che specifica il rettangolo di output, in coordinate logiche.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setOutputRect(Rectangle value) {#setOutputRect-com.aspose.imaging.Rectangle-}
```
public void setOutputRect(Rectangle value)
```


Ottiene o imposta un oggetto WMF RectL ([MS-WMF] sezione 2.2.2.19) che specifica il rettangolo di output, in coordinate logiche.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getAFormats() {#getAFormats--}
```
public EmfFormat[] getAFormats()
```


Ottiene o imposta un array di lunghezza CountFormats di formati grafici, specificati da oggetti EmrFormat (sezione 2.2.4), in ordine di preferenza

**Returns:**
com.aspose.imaging.fileformats.emf.emf.objects.EmfFormat[]
### setAFormats(EmfFormat[] value) {#setAFormats-com.aspose.imaging.fileformats.emf.emf.objects.EmfFormat---}
```
public void setAFormats(EmfFormat[] value)
```


Ottiene o imposta un array di lunghezza CountFormats di formati grafici, specificati da oggetti EmrFormat (sezione 2.2.4), in ordine di preferenza

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [EmfFormat\[\]](../../com.aspose.imaging.fileformats.emf.emf.objects/emfformat) |  |

### getFormatData() {#getFormatData--}
```
public byte[][] getFormatData()
```


Ottiene o imposta un array di byte a lunghezza variabile contenente i dati dell'immagine per tutti i formati grafici contenuti in questo record. La dimensione dei dati per ogni immagine è fornita dal campo DataSize nell'oggetto EmrFormat corrispondente. Pertanto, la dimensione totale di questo campo è la somma dei valori DataSize in tutti gli oggetti EmrFormat. Il formato grafico dei dati per ogni immagine è specificato dal campo Signature nell'oggetto EmrFormat corrispondente.

**Returns:**
byte[][]
### setFormatData(byte[][] value) {#setFormatData-byte-----}
```
public void setFormatData(byte[][] value)
```


Ottiene o imposta un array di byte a lunghezza variabile contenente i dati dell'immagine per tutti i formati grafici contenuti in questo record. La dimensione dei dati per ogni immagine è fornita dal campo DataSize nell'oggetto EmrFormat corrispondente. Pertanto, la dimensione totale di questo campo è la somma dei valori DataSize in tutti gli oggetti EmrFormat. Il formato grafico dei dati per ogni immagine è specificato dal campo Signature nell'oggetto EmrFormat corrispondente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte[][] |  |

