---
title: "EmfPolyDraw"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il record EMR_POLYDRAW specifica un insieme di segmenti di linea e curve di Bézier."
type: docs
weight: 89
url: /it/java/com.aspose.imaging.fileformats.emf.emf.records/emfpolydraw/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype), [com.aspose.imaging.fileformats.emf.emf.records.EmfBoundedRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfboundedrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfPolyShape](../../com.aspose.imaging.fileformats.emf.emf.records/emfpolyshape)
```
public final class EmfPolyDraw extends EmfPolyShape
```

Il record EMR\_POLYDRAW specifica un insieme di segmenti di linea e curve di Bézier.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfPolyDraw(EmfRecord source)](#EmfPolyDraw-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inizializza una nuova istanza della classe `EmfPolyDraw`. |
| [EmfPolyDraw()](#EmfPolyDraw--) | Inizializza una nuova istanza della classe [EmfPolyDraw](../../com.aspose.imaging.fileformats.emf.emf.records/emfpolydraw). |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getAbTypes()](#getAbTypes--) | Ottiene un array di byte di lunghezza Count che specifica come viene utilizzato ciascun punto nell'array aPoints (Ottieni o imposta). |
| [setAbTypes(byte[] value)](#setAbTypes-byte---) | Imposta un array di byte di lunghezza Count che specifica come viene utilizzato ciascun punto nell'array aPoints (Ottieni o imposta). |
### EmfPolyDraw(EmfRecord source) {#EmfPolyDraw-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfPolyDraw(EmfRecord source)
```


Inizializza una nuova istanza della classe `EmfPolyDraw`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La sorgente. |

### EmfPolyDraw() {#EmfPolyDraw--}
```
public EmfPolyDraw()
```


Inizializza una nuova istanza della classe [EmfPolyDraw](../../com.aspose.imaging.fileformats.emf.emf.records/emfpolydraw).

### getAbTypes() {#getAbTypes--}
```
public byte[] getAbTypes()
```


Ottiene un array di byte di lunghezza Count che specifica come viene utilizzato ciascun punto nell'array aPoints (Ottieni o imposta). Questo valore DEVE appartenere all'enumerazione Point (sezione 2.1.26).

**Returns:**
byte[] - un array di byte di lunghezza Count che specifica come viene utilizzato ciascun punto nell'array aPoints (Ottieni o imposta).
### setAbTypes(byte[] value) {#setAbTypes-byte---}
```
public void setAbTypes(byte[] value)
```


Imposta un array di byte di lunghezza Count che specifica come viene utilizzato ciascun punto nell'array aPoints (Ottieni o imposta). Questo valore DEVE appartenere all'enumerazione Point (sezione 2.1.26).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte[] | un array di byte di lunghezza Count che specifica come viene utilizzato ciascun punto nell'array aPoints (Ottieni o imposta). |

