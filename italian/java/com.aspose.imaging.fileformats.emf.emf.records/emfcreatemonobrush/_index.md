---
title: "EmfCreateMonoBrush"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il record EMR_CREATEMONOBRUSH definisce un pennello a pattern monocromatico per operazioni grafiche."
type: docs
weight: 39
url: /it/java/com.aspose.imaging.fileformats.emf.emf.records/emfcreatemonobrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectCreationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectcreationrecordtype)
```
public final class EmfCreateMonoBrush extends EmfObjectCreationRecordType
```

Il record EMR\\_CREATEMONOBRUSH definisce un pennello a pattern monocromatico per operazioni grafiche. Il pattern è specificato da un DIB monocromatico.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfCreateMonoBrush(EmfRecord source)](#EmfCreateMonoBrush-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inizializza una nuova istanza della classe `EmfCreateMonoBrush`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getIhBrush()](#getIhBrush--) | Ottiene o imposta un intero senza segno a 32 bit che specifica l'indice dell'oggetto pennello a pattern monocromatico nella EMF Object Table (sezione 3.1.1.1). |
| [setIhBrush(int value)](#setIhBrush-int-) | Ottiene o imposta un intero senza segno a 32 bit che specifica l'indice dell'oggetto pennello a pattern monocromatico nella EMF Object Table (sezione 3.1.1.1). |
| [getUsage()](#getUsage--) | Ottiene o imposta un intero senza segno a 32 bit che specifica come interpretare i valori nella tavola dei colori nell'intestazione DIB. |
| [setUsage(int value)](#setUsage-int-) | Ottiene o imposta un intero senza segno a 32 bit che specifica come interpretare i valori nella tavola dei colori nell'intestazione DIB. |
| [getBitmapBuffer()](#getBitmapBuffer--) | Ottiene o imposta un buffer contenente un DIB compresso nella forma di un oggetto WMF DeviceIndependentBitmap ([MS-WMF] sezione 2.2.2.9). |
| [setBitmapBuffer(WmfDeviceIndependentBitmap value)](#setBitmapBuffer-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | Ottiene o imposta un buffer contenente un DIB compresso nella forma di un oggetto WMF DeviceIndependentBitmap ([MS-WMF] sezione 2.2.2.9). |
### EmfCreateMonoBrush(EmfRecord source) {#EmfCreateMonoBrush-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfCreateMonoBrush(EmfRecord source)
```


Inizializza una nuova istanza della classe `EmfCreateMonoBrush`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La sorgente. |

### getIhBrush() {#getIhBrush--}
```
public int getIhBrush()
```


Ottiene o imposta un intero senza segno a 32 bit che specifica l'indice dell'oggetto pennello a pattern monocromatico nella EMF Object Table (sezione 3.1.1.1). Questo indice DEVE essere salvato in modo che l'oggetto possa essere riutilizzato o modificato.

**Returns:**
int
### setIhBrush(int value) {#setIhBrush-int-}
```
public void setIhBrush(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che specifica l'indice dell'oggetto pennello a pattern monocromatico nella EMF Object Table (sezione 3.1.1.1). Questo indice DEVE essere salvato in modo che l'oggetto possa essere riutilizzato o modificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getUsage() {#getUsage--}
```
public int getUsage()
```


Ottiene o imposta un intero senza segno a 32 bit che specifica come interpretare i valori nella tabella dei colori nell'intestazione DIB. Questo valore DEVE essere nell'enumerazione DIBColors (sezione 2.1.9).

**Returns:**
int
### setUsage(int value) {#setUsage-int-}
```
public void setUsage(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che specifica come interpretare i valori nella tabella dei colori nell'intestazione DIB. Questo valore DEVE essere nell'enumerazione DIBColors (sezione 2.1.9).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getBitmapBuffer() {#getBitmapBuffer--}
```
public WmfDeviceIndependentBitmap getBitmapBuffer()
```


Ottiene o imposta un buffer contenente un DIB compresso nella forma di un oggetto WMF DeviceIndependentBitmap ([MS-WMF] sezione 2.2.2.9). Non è necessario che sia contiguo con la parte fissa del record EMR\_CREATEDIBPATTERNBRUSHPT.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setBitmapBuffer(WmfDeviceIndependentBitmap value) {#setBitmapBuffer-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setBitmapBuffer(WmfDeviceIndependentBitmap value)
```


Ottiene o imposta un buffer contenente un DIB compresso nella forma di un oggetto WMF DeviceIndependentBitmap ([MS-WMF] sezione 2.2.2.9). Non è necessario che sia contiguo con la parte fissa del record EMR\_CREATEDIBPATTERNBRUSHPT.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

