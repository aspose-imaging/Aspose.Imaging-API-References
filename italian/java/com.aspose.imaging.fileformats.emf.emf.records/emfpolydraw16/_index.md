---
title: "EmfPolyDraw16"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il record EMR_POLYDRAW16 specifica un insieme di segmenti di linea e curve di Bézier."
type: docs
weight: 90
url: /it/java/com.aspose.imaging.fileformats.emf.emf.records/emfpolydraw16/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype), [com.aspose.imaging.fileformats.emf.emf.records.EmfBoundedRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfboundedrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfPolyShape](../../com.aspose.imaging.fileformats.emf.emf.records/emfpolyshape)
```
public final class EmfPolyDraw16 extends EmfPolyShape
```

Il record EMR\_POLYDRAW16 specifica un insieme di segmenti di linea e curve di Bézier.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfPolyDraw16(EmfRecord source)](#EmfPolyDraw16-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inizializza una nuova istanza della classe `EmfPolyDraw16`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getAbTypes()](#getAbTypes--) | Ottiene o imposta un array di byte di lunghezza Count che specifica i tipi di punto. |
| [setAbTypes(byte[] value)](#setAbTypes-byte---) | Imposta un array di byte di lunghezza Count che specifica i tipi di punto. |
### EmfPolyDraw16(EmfRecord source) {#EmfPolyDraw16-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfPolyDraw16(EmfRecord source)
```


Inizializza una nuova istanza della classe `EmfPolyDraw16`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La sorgente. |

### getAbTypes() {#getAbTypes--}
```
public byte[] getAbTypes()
```


Ottiene o imposta un array di byte di lunghezza Count che specifica i tipi di punto. Questo valore DEVE essere nell'enumerazione Point (sezione 2.1.26).

**Returns:**
byte[]
### setAbTypes(byte[] value) {#setAbTypes-byte---}
```
public void setAbTypes(byte[] value)
```


Imposta un array di byte di lunghezza Count che specifica i tipi di punto. Questo valore DEVE essere nell'enumerazione Point (sezione 2.1.26).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte[] | un array di byte di lunghezza Count che specifica i tipi di punto. |

