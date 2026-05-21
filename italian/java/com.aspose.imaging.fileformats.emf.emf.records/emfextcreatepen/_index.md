---
title: "EmfExtCreatePen"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il record EMR_EXTCREATEPEN definisce una penna logica estesa per le operazioni grafiche."
type: docs
weight: 52
url: /it/java/com.aspose.imaging.fileformats.emf.emf.records/emfextcreatepen/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectCreationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectcreationrecordtype)
```
public final class EmfExtCreatePen extends EmfObjectCreationRecordType
```

Il record EMR\_EXTCREATEPEN definisce una penna logica estesa per le operazioni grafiche. È possibile specificare un DIB opzionale da utilizzare come stile di linea.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfExtCreatePen(EmfRecord record)](#EmfExtCreatePen-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inizializza una nuova istanza della classe `EmfExtCreatePen`. |
| [EmfExtCreatePen()](#EmfExtCreatePen--) | Inizializza una nuova istanza della classe `EmfExtCreatePen`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getIhPen()](#getIhPen--) | Ottiene o imposta un intero senza segno a 32 bit che specifica l'indice dell'oggetto penna logica estesa nella EMF Object Table (sezione 3.1.1.1). |
| [setIhPen(int value)](#setIhPen-int-) | Ottiene o imposta un intero senza segno a 32 bit che specifica l'indice dell'oggetto penna logica estesa nella EMF Object Table (sezione 3.1.1.1). |
| [getElp()](#getElp--) | Ottiene o imposta un oggetto LogPenEx (sezione 2.2.20) che specifica una penna logica estesa con attributi, inclusa un'array di stile di linea opzionale. |
| [setElp(EmfLogPenEx value)](#setElp-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogPenEx-) | Ottiene o imposta un oggetto LogPenEx (sezione 2.2.20) che specifica una penna logica estesa con attributi, inclusa un'array di stile di linea opzionale. |
| [getBitmapBuffer()](#getBitmapBuffer--) | Ottiene o imposta un buffer opzionale contenente un DIB compresso nella forma di un oggetto WMF DeviceIndependentBitmap ([MS-WMF] sezione 2.2.2.9). |
| [setBitmapBuffer(WmfDeviceIndependentBitmap value)](#setBitmapBuffer-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | Ottiene o imposta un buffer opzionale contenente un DIB compresso nella forma di un oggetto WMF DeviceIndependentBitmap ([MS-WMF] sezione 2.2.2.9). |
### EmfExtCreatePen(EmfRecord record) {#EmfExtCreatePen-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfExtCreatePen(EmfRecord record)
```


Inizializza una nuova istanza della classe `EmfExtCreatePen`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| record | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Il record. |

### EmfExtCreatePen() {#EmfExtCreatePen--}
```
public EmfExtCreatePen()
```


Inizializza una nuova istanza della classe `EmfExtCreatePen`.

### getIhPen() {#getIhPen--}
```
public int getIhPen()
```


Ottiene o imposta un intero senza segno a 32 bit che specifica l'indice dell'oggetto penna logica estesa nella EMF Object Table (sezione 3.1.1.1). Questo indice DEVE essere salvato affinché l'oggetto possa essere riutilizzato o modificato.

**Returns:**
int
### setIhPen(int value) {#setIhPen-int-}
```
public void setIhPen(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che specifica l'indice dell'oggetto penna logica estesa nella EMF Object Table (sezione 3.1.1.1). Questo indice DEVE essere salvato affinché l'oggetto possa essere riutilizzato o modificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getElp() {#getElp--}
```
public EmfLogPenEx getElp()
```


Ottiene o imposta un oggetto LogPenEx (sezione 2.2.20) che specifica una penna logica estesa con attributi, inclusa un'array di stile di linea opzionale.

**Returns:**
[EmfLogPenEx](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogpenex)
### setElp(EmfLogPenEx value) {#setElp-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogPenEx-}
```
public void setElp(EmfLogPenEx value)
```


Ottiene o imposta un oggetto LogPenEx (sezione 2.2.20) che specifica una penna logica estesa con attributi, inclusa un'array di stile di linea opzionale.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [EmfLogPenEx](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogpenex) |  |

### getBitmapBuffer() {#getBitmapBuffer--}
```
public WmfDeviceIndependentBitmap getBitmapBuffer()
```


Ottiene o imposta un buffer opzionale contenente un DIB compresso nella forma di un oggetto WMF DeviceIndependentBitmap ([MS-WMF] sezione 2.2.2.9). Non è necessario che sia contiguo con la parte fissa del record EMR\_EXTCREATEPEN.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setBitmapBuffer(WmfDeviceIndependentBitmap value) {#setBitmapBuffer-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setBitmapBuffer(WmfDeviceIndependentBitmap value)
```


Ottiene o imposta un buffer opzionale contenente un DIB compresso nella forma di un oggetto WMF DeviceIndependentBitmap ([MS-WMF] sezione 2.2.2.9). Non è necessario che sia contiguo con la parte fissa del record EMR\_EXTCREATEPEN.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

