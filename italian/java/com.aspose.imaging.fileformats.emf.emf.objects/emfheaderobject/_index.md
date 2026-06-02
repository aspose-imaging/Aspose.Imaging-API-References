---
title: "EmfHeaderObject"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "L'oggetto Header definisce l'intestazione del metafile EMF."
type: docs
weight: 20
url: /it/java/com.aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public class EmfHeaderObject extends EmfObject
```

L'oggetto Header definisce l'intestazione del metafile EMF. Specifica le proprietà del dispositivo su cui è stata creata l'immagine nel metafile.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfHeaderObject()](#EmfHeaderObject--) | Inizializza una nuova istanza della classe `EmfHeaderObject`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getBounds()](#getBounds--) | Ottiene o imposta un oggetto WMF RectL ([MS-WMF] sezione 2.2.2.19) che specifica i limiti rettangolari inclusivi-inclusivi in unità dispositivo del più piccolo rettangolo che può essere disegnato attorno all'immagine memorizzata nel metafile |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Ottiene o imposta un oggetto WMF RectL ([MS-WMF] sezione 2.2.2.19) che specifica i limiti rettangolari inclusivi-inclusivi in unità dispositivo del più piccolo rettangolo che può essere disegnato attorno all'immagine memorizzata nel metafile |
| [getFrame()](#getFrame--) | Ottiene o imposta un oggetto WMF RectL che specifica le dimensioni rettangolari inclusive-inclusive, in unità di 0,01 millimetri, di un rettangolo che circonda l'immagine memorizzata nel metafile |
| [setFrame(Rectangle value)](#setFrame-com.aspose.imaging.Rectangle-) | Ottiene o imposta un oggetto WMF RectL che specifica le dimensioni rettangolari inclusive-inclusive, in unità di 0,01 millimetri, di un rettangolo che circonda l'immagine memorizzata nel metafile |
| [getRecordSignature()](#getRecordSignature--) | Ottiene o imposta un intero senza segno a 32 bit che specifica la firma del record. |
| [setRecordSignature(int value)](#setRecordSignature-int-) | Ottiene o imposta un intero senza segno a 32 bit che specifica la firma del record. |
| [getVersion()](#getVersion--) | Ottiene o imposta Version (4 byte): un intero senza segno a 32 bit che specifica l'interoperabilità del metafile EMF. |
| [setVersion(int value)](#setVersion-int-) | Ottiene o imposta Version (4 byte): un intero senza segno a 32 bit che specifica l'interoperabilità del metafile EMF. |
| [getBytes()](#getBytes--) | Ottiene o imposta un intero senza segno a 32 bit che specifica la dimensione del metafile, in byte. |
| [setBytes(int value)](#setBytes-int-) | Ottiene o imposta un intero senza segno a 32 bit che specifica la dimensione del metafile, in byte. |
| [getRecords()](#getRecords--) | Ottiene o imposta un intero senza segno a 32 bit che specifica il numero di record nel metafile |
| [setRecords(int value)](#setRecords-int-) | Ottiene o imposta un intero senza segno a 32 bit che specifica il numero di record nel metafile |
| [getHandles()](#getHandles--) | Ottiene o imposta un intero senza segno a 16 bit che specifica il numero di oggetti grafici che verranno utilizzati durante l'elaborazione del metafile |
| [setHandles(short value)](#setHandles-short-) | Ottiene o imposta un intero senza segno a 16 bit che specifica il numero di oggetti grafici che verranno utilizzati durante l'elaborazione del metafile |
| [getReserved()](#getReserved--) | Ottiene o imposta un intero senza segno a 16 bit che DEVE essere 0x0000 e DEVE essere ignorato |
| [setReserved(short value)](#setReserved-short-) | Ottiene o imposta un intero senza segno a 16 bit che DEVE essere 0x0000 e DEVE essere ignorato |
| [getNDesription()](#getNDesription--) | Ottiene o imposta un intero senza segno a 32 bit che specifica il numero di caratteri nell'array che contiene la descrizione del contenuto del metafile. |
| [setNDesription(int value)](#setNDesription-int-) | Ottiene o imposta un intero senza segno a 32 bit che specifica il numero di caratteri nell'array che contiene la descrizione del contenuto del metafile. |
| [getOffDescription()](#getOffDescription--) | Ottiene o imposta un intero senza segno a 32 bit che specifica lo spostamento dall'inizio di questo record all'array che contiene la descrizione del contenuto del metafile |
| [setOffDescription(int value)](#setOffDescription-int-) | Ottiene o imposta un intero senza segno a 32 bit che specifica lo spostamento dall'inizio di questo record all'array che contiene la descrizione del contenuto del metafile |
| [getNPalEntries()](#getNPalEntries--) | Ottiene o imposta un intero senza segno a 32 bit che specifica il numero di voci nella tavolozza del metafile. |
| [setNPalEntries(int value)](#setNPalEntries-int-) | Ottiene o imposta un intero senza segno a 32 bit che specifica il numero di voci nella tavolozza del metafile. |
| [getDevice()](#getDevice--) | Ottiene o imposta un oggetto WMF SizeL ([MS-WMF] sezione 2.2.2.22) che specifica le dimensioni del dispositivo di riferimento, in pixel |
| [setDevice(Size value)](#setDevice-com.aspose.imaging.Size-) | Ottiene o imposta un oggetto WMF SizeL ([MS-WMF] sezione 2.2.2.22) che specifica le dimensioni del dispositivo di riferimento, in pixel |
| [getMillimeters()](#getMillimeters--) | Ottiene o imposta un oggetto WMF SizeL che specifica le dimensioni del dispositivo di riferimento, in millimetri |
| [setMillimeters(Size value)](#setMillimeters-com.aspose.imaging.Size-) | Ottiene o imposta un oggetto WMF SizeL che specifica le dimensioni del dispositivo di riferimento, in millimetri |
| [getValid()](#getValid--) | Ottiene un valore che indica se questo `EmfHeaderObject` è valido. |
### EmfHeaderObject() {#EmfHeaderObject--}
```
public EmfHeaderObject()
```


Inizializza una nuova istanza della classe `EmfHeaderObject`.

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


Ottiene o imposta un oggetto WMF RectL ([MS-WMF] sezione 2.2.2.19) che specifica i limiti rettangolari inclusivi-inclusivi in unità dispositivo del più piccolo rettangolo che può essere disegnato attorno all'immagine memorizzata nel metafile

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


Ottiene o imposta un oggetto WMF RectL ([MS-WMF] sezione 2.2.2.19) che specifica i limiti rettangolari inclusivi-inclusivi in unità dispositivo del più piccolo rettangolo che può essere disegnato attorno all'immagine memorizzata nel metafile

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getFrame() {#getFrame--}
```
public Rectangle getFrame()
```


Ottiene o imposta un oggetto WMF RectL che specifica le dimensioni rettangolari inclusive-inclusive, in unità di 0,01 millimetri, di un rettangolo che circonda l'immagine memorizzata nel metafile

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setFrame(Rectangle value) {#setFrame-com.aspose.imaging.Rectangle-}
```
public void setFrame(Rectangle value)
```


Ottiene o imposta un oggetto WMF RectL che specifica le dimensioni rettangolari inclusive-inclusive, in unità di 0,01 millimetri, di un rettangolo che circonda l'immagine memorizzata nel metafile

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getRecordSignature() {#getRecordSignature--}
```
public int getRecordSignature()
```


Ottiene o imposta un intero senza segno a 32 bit che specifica la firma del record. Questo DEVE essere ENHMETA\_SIGNATURE, dall'enumerazione FormatSignature (sezione 2.1.14).

**Returns:**
int
### setRecordSignature(int value) {#setRecordSignature-int-}
```
public void setRecordSignature(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che specifica la firma del record. Questo DEVE essere ENHMETA\_SIGNATURE, dall'enumerazione FormatSignature (sezione 2.1.14).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getVersion() {#getVersion--}
```
public int getVersion()
```


Ottiene o imposta Version (4 byte): un intero senza segno a 32 bit che specifica l'interoperabilità del metafile EMF. Questo DOVREBBE essere 0x00010000

**Returns:**
int
### setVersion(int value) {#setVersion-int-}
```
public void setVersion(int value)
```


Ottiene o imposta Version (4 byte): un intero senza segno a 32 bit che specifica l'interoperabilità del metafile EMF. Questo DOVREBBE essere 0x00010000

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getBytes() {#getBytes--}
```
public int getBytes()
```


Ottiene o imposta un intero senza segno a 32 bit che specifica la dimensione del metafile, in byte.

**Returns:**
int
### setBytes(int value) {#setBytes-int-}
```
public void setBytes(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che specifica la dimensione del metafile, in byte.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getRecords() {#getRecords--}
```
public int getRecords()
```


Ottiene o imposta un intero senza segno a 32 bit che specifica il numero di record nel metafile

**Returns:**
int
### setRecords(int value) {#setRecords-int-}
```
public void setRecords(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che specifica il numero di record nel metafile

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getHandles() {#getHandles--}
```
public short getHandles()
```


Ottiene o imposta un intero senza segno a 16 bit che specifica il numero di oggetti grafici che verranno utilizzati durante l'elaborazione del metafile

**Returns:**
short
### setHandles(short value) {#setHandles-short-}
```
public void setHandles(short value)
```


Ottiene o imposta un intero senza segno a 16 bit che specifica il numero di oggetti grafici che verranno utilizzati durante l'elaborazione del metafile

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | short |  |

### getReserved() {#getReserved--}
```
public short getReserved()
```


Ottiene o imposta un intero senza segno a 16 bit che DEVE essere 0x0000 e DEVE essere ignorato

**Returns:**
short
### setReserved(short value) {#setReserved-short-}
```
public void setReserved(short value)
```


Ottiene o imposta un intero senza segno a 16 bit che DEVE essere 0x0000 e DEVE essere ignorato

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | short |  |

### getNDesription() {#getNDesription--}
```
public int getNDesription()
```


Ottiene o imposta un intero senza segno a 32 bit che specifica il numero di caratteri nell'array che contiene la descrizione del contenuto del metafile. Questo è zero se non esiste alcuna stringa di descrizione.

**Returns:**
int
### setNDesription(int value) {#setNDesription-int-}
```
public void setNDesription(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che specifica il numero di caratteri nell'array che contiene la descrizione del contenuto del metafile. Questo è zero se non esiste alcuna stringa di descrizione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getOffDescription() {#getOffDescription--}
```
public int getOffDescription()
```


Ottiene o imposta un intero senza segno a 32 bit che specifica lo spostamento dall'inizio di questo record all'array che contiene la descrizione del contenuto del metafile

**Returns:**
int
### setOffDescription(int value) {#setOffDescription-int-}
```
public void setOffDescription(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che specifica lo spostamento dall'inizio di questo record all'array che contiene la descrizione del contenuto del metafile

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getNPalEntries() {#getNPalEntries--}
```
public int getNPalEntries()
```


Ottiene o imposta un intero senza segno a 32 bit che specifica il numero di voci nella tavolozza del metafile. La tavolozza si trova nel record EMR\_EOF

**Returns:**
int
### setNPalEntries(int value) {#setNPalEntries-int-}
```
public void setNPalEntries(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che specifica il numero di voci nella tavolozza del metafile. La tavolozza si trova nel record EMR\_EOF

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getDevice() {#getDevice--}
```
public Size getDevice()
```


Ottiene o imposta un oggetto WMF SizeL ([MS-WMF] sezione 2.2.2.22) che specifica le dimensioni del dispositivo di riferimento, in pixel

**Returns:**
[Size](../../com.aspose.imaging/size)
### setDevice(Size value) {#setDevice-com.aspose.imaging.Size-}
```
public void setDevice(Size value)
```


Ottiene o imposta un oggetto WMF SizeL ([MS-WMF] sezione 2.2.2.22) che specifica le dimensioni del dispositivo di riferimento, in pixel

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Size](../../com.aspose.imaging/size) |  |

### getMillimeters() {#getMillimeters--}
```
public Size getMillimeters()
```


Ottiene o imposta un oggetto WMF SizeL che specifica le dimensioni del dispositivo di riferimento, in millimetri

**Returns:**
[Size](../../com.aspose.imaging/size)
### setMillimeters(Size value) {#setMillimeters-com.aspose.imaging.Size-}
```
public void setMillimeters(Size value)
```


Ottiene o imposta un oggetto WMF SizeL che specifica le dimensioni del dispositivo di riferimento, in millimetri

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Size](../../com.aspose.imaging/size) |  |

### getValid() {#getValid--}
```
public boolean getValid()
```


Ottiene un valore che indica se questo `EmfHeaderObject` è valido.

Valore: `true` se valido; altrimenti, `false`.

**Returns:**
boolean
