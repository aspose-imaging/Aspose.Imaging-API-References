---
title: "EmfGlsBoundedRecord"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il record EMR_GLSBOUNDEDRECORD specifica una funzione OpenGL con un rettangolo di delimitazione per l'output."
type: docs
weight: 63
url: /it/java/com.aspose.imaging.fileformats.emf.emf.records/emfglsboundedrecord/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfOpenGlRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfopenglrecordtype)
```
public final class EmfGlsBoundedRecord extends EmfOpenGlRecordType
```

Il record EMR\_GLSBOUNDEDRECORD specifica una funzione OpenGL con un rettangolo di delimitazione per l'output.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfGlsBoundedRecord(EmfRecord source)](#EmfGlsBoundedRecord-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inizializza una nuova istanza della classe `EmfGlsBoundedRecord`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getBounds()](#getBounds--) | Ottiene o imposta un oggetto WMF RectL ([MS-WMF] sezione 2.2.2.19) che definisce un rettangolo di delimitazione, in unità dispositivo, per l'output prodotto dall'esecuzione della funzione OpenGL. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Ottiene o imposta un oggetto WMF RectL ([MS-WMF] sezione 2.2.2.19) che definisce un rettangolo di delimitazione, in unità dispositivo, per l'output prodotto dall'esecuzione della funzione OpenGL. |
| [getCbData()](#getCbData--) | Ottiene o imposta un intero senza segno a 32 bit che specifica la dimensione, in byte, del campo Data. |
| [setCbData(int value)](#setCbData-int-) | Ottiene o imposta un intero senza segno a 32 bit che specifica la dimensione, in byte, del campo Data. |
| [getData()](#getData--) | Ottiene o imposta un array opzionale di byte di lunghezza cbData che specifica i dati per la funzione OpenGL. |
| [setData(byte[] value)](#setData-byte---) | Ottiene o imposta un array opzionale di byte di lunghezza cbData che specifica i dati per la funzione OpenGL. |
### EmfGlsBoundedRecord(EmfRecord source) {#EmfGlsBoundedRecord-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfGlsBoundedRecord(EmfRecord source)
```


Inizializza una nuova istanza della classe `EmfGlsBoundedRecord`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La sorgente. |

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


Ottiene o imposta un oggetto WMF RectL ([MS-WMF] sezione 2.2.2.19) che definisce un rettangolo di delimitazione, in unità dispositivo, per l'output prodotto dall'esecuzione della funzione OpenGL.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


Ottiene o imposta un oggetto WMF RectL ([MS-WMF] sezione 2.2.2.19) che definisce un rettangolo di delimitazione, in unità dispositivo, per l'output prodotto dall'esecuzione della funzione OpenGL.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

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

