---
title: "EmfMetafileHeaderExtension1"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il record EmfMetafileHeaderExtension1 è il record di intestazione usato nella prima estensione dei metafili EMF."
type: docs
weight: 71
url: /it/java/com.aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfMetafileHeader](../../com.aspose.imaging.fileformats.emf.emf.records/emfmetafileheader)
```
public class EmfMetafileHeaderExtension1 extends EmfMetafileHeader
```

Il record EmfMetafileHeaderExtension1 è il record di intestazione utilizzato nella prima estensione dei metafile EMF. Dopo il campo EmfHeaderExtension1, i campi rimanenti sono opzionali e possono essere presenti in qualsiasi ordine.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfMetafileHeaderExtension1(EmfMetafileHeader header)](#EmfMetafileHeaderExtension1-com.aspose.imaging.fileformats.emf.emf.records.EmfMetafileHeader-) | Inizializza una nuova istanza della classe `EmfMetafileHeaderExtension1`. |
| [EmfMetafileHeaderExtension1(EmfMetafileHeaderExtension1 header)](#EmfMetafileHeaderExtension1-com.aspose.imaging.fileformats.emf.emf.records.EmfMetafileHeaderExtension1-) | Inizializza una nuova istanza della classe `EmfMetafileHeaderExtension1`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getEmfHeaderExtension1()](#getEmfHeaderExtension1--) | Ottiene o imposta un oggetto HeaderExtension1, che specifica informazioni aggiuntive sull'immagine nel metafile. |
| [setEmfHeaderExtension1(EmfHeaderExtension1 value)](#setEmfHeaderExtension1-com.aspose.imaging.fileformats.emf.emf.objects.EmfHeaderExtension1-) | Ottiene o imposta un oggetto HeaderExtension1, che specifica informazioni aggiuntive sull'immagine nel metafile. |
| [getEmfPixelFormatBuffer()](#getEmfPixelFormatBuffer--) | Ottiene o imposta un array opzionale di byte che contiene il descrittore del formato pixel EMF, che non è necessario sia contiguo con la parte fissa del record EmfMetafileHeaderExtension1 né con la stringa di descrizione EMF. |
| [setEmfPixelFormatBuffer(byte[] value)](#setEmfPixelFormatBuffer-byte---) | Ottiene o imposta un array opzionale di byte che contiene il descrittore del formato pixel EMF, che non è necessario sia contiguo con la parte fissa del record EmfMetafileHeaderExtension1 né con la stringa di descrizione EMF. |
### EmfMetafileHeaderExtension1(EmfMetafileHeader header) {#EmfMetafileHeaderExtension1-com.aspose.imaging.fileformats.emf.emf.records.EmfMetafileHeader-}
```
public EmfMetafileHeaderExtension1(EmfMetafileHeader header)
```


Inizializza una nuova istanza della classe `EmfMetafileHeaderExtension1`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| header | [EmfMetafileHeader](../../com.aspose.imaging.fileformats.emf.emf.records/emfmetafileheader) | L'intestazione. |

### EmfMetafileHeaderExtension1(EmfMetafileHeaderExtension1 header) {#EmfMetafileHeaderExtension1-com.aspose.imaging.fileformats.emf.emf.records.EmfMetafileHeaderExtension1-}
```
public EmfMetafileHeaderExtension1(EmfMetafileHeaderExtension1 header)
```


Inizializza una nuova istanza della classe `EmfMetafileHeaderExtension1`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| header | [EmfMetafileHeaderExtension1](../../com.aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1) | L'intestazione. |

### getEmfHeaderExtension1() {#getEmfHeaderExtension1--}
```
public EmfHeaderExtension1 getEmfHeaderExtension1()
```


Ottiene o imposta un oggetto HeaderExtension1, che specifica informazioni aggiuntive sull'immagine nel metafile.

**Returns:**
[EmfHeaderExtension1](../../com.aspose.imaging.fileformats.emf.emf.objects/emfheaderextension1)
### setEmfHeaderExtension1(EmfHeaderExtension1 value) {#setEmfHeaderExtension1-com.aspose.imaging.fileformats.emf.emf.objects.EmfHeaderExtension1-}
```
public void setEmfHeaderExtension1(EmfHeaderExtension1 value)
```


Ottiene o imposta un oggetto HeaderExtension1, che specifica informazioni aggiuntive sull'immagine nel metafile.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [EmfHeaderExtension1](../../com.aspose.imaging.fileformats.emf.emf.objects/emfheaderextension1) |  |

### getEmfPixelFormatBuffer() {#getEmfPixelFormatBuffer--}
```
public byte[] getEmfPixelFormatBuffer()
```


Ottiene o imposta un array opzionale di byte che contiene il descrittore del formato pixel EMF, che non è necessario sia contiguo con la parte fissa del record EmfMetafileHeaderExtension1 né con la stringa di descrizione EMF. Di conseguenza, il campo in questo buffer etichettato "UndefinedSpace" è opzionale e DEVE essere ignorato.

**Returns:**
byte[]
### setEmfPixelFormatBuffer(byte[] value) {#setEmfPixelFormatBuffer-byte---}
```
public void setEmfPixelFormatBuffer(byte[] value)
```


Ottiene o imposta un array opzionale di byte che contiene il descrittore del formato pixel EMF, che non è necessario sia contiguo con la parte fissa del record EmfMetafileHeaderExtension1 né con la stringa di descrizione EMF. Di conseguenza, il campo in questo buffer etichettato "UndefinedSpace" è opzionale e DEVE essere ignorato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte[] |  |

