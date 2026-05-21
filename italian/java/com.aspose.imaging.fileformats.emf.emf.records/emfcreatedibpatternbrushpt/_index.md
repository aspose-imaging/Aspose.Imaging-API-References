---
title: "EmfCreateDibPatternBrushPt"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il record EMR_CREATEDIBPATTERNBRUSHPT definisce un pennello pattern per le operazioni grafiche."
type: docs
weight: 38
url: /it/java/com.aspose.imaging.fileformats.emf.emf.records/emfcreatedibpatternbrushpt/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectCreationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectcreationrecordtype)
```
public final class EmfCreateDibPatternBrushPt extends EmfObjectCreationRecordType
```

Il record EMR\_CREATEDIBPATTERNBRUSHPT definisce un pennello pattern per le operazioni grafiche. Il pattern è specificato da un DIB.

L'oggetto pennello pattern definito da questo record può essere selezionato nel contesto del dispositivo di riproduzione mediante un record EMR\_SELECTOBJECT (sezione 2.3.8.5), che specifica il pennello pattern da utilizzare nelle successive operazioni grafiche.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfCreateDibPatternBrushPt(EmfRecord source)](#EmfCreateDibPatternBrushPt-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inizializza una nuova istanza della classe `EmfCreateDibPatternBrushPt`. |
| [EmfCreateDibPatternBrushPt()](#EmfCreateDibPatternBrushPt--) | Inizializza una nuova istanza della classe `EmfCreateDibPatternBrushPt`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getIhBrush()](#getIhBrush--) | Ottiene o imposta un intero senza segno a 32 bit che specifica l'indice dell'oggetto pennello pattern nella EMF Object Table (sezione 3.1.1.1). |
| [setIhBrush(int value)](#setIhBrush-int-) | Ottiene o imposta un intero senza segno a 32 bit che specifica l'indice dell'oggetto pennello pattern nella EMF Object Table (sezione 3.1.1.1). |
| [getUsage()](#getUsage--) | Ottiene o imposta un intero senza segno a 32 bit che specifica come interpretare i valori nella tavola dei colori nell'intestazione DIB. |
| [setUsage(int value)](#setUsage-int-) | Ottiene o imposta un intero senza segno a 32 bit che specifica come interpretare i valori nella tavola dei colori nell'intestazione DIB. |
| [getBitmapBuffer()](#getBitmapBuffer--) | Ottiene o imposta un buffer contenente un DIB compresso nella forma di un oggetto WMF DeviceIndependentBitmap ([MS-WMF] sezione 2.2.2.9). |
| [setBitmapBuffer(WmfDeviceIndependentBitmap value)](#setBitmapBuffer-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | Ottiene o imposta un buffer contenente un DIB compresso nella forma di un oggetto WMF DeviceIndependentBitmap ([MS-WMF] sezione 2.2.2.9). |
### EmfCreateDibPatternBrushPt(EmfRecord source) {#EmfCreateDibPatternBrushPt-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfCreateDibPatternBrushPt(EmfRecord source)
```


Inizializza una nuova istanza della classe `EmfCreateDibPatternBrushPt`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La sorgente. |

### EmfCreateDibPatternBrushPt() {#EmfCreateDibPatternBrushPt--}
```
public EmfCreateDibPatternBrushPt()
```


Inizializza una nuova istanza della classe `EmfCreateDibPatternBrushPt`.

### getIhBrush() {#getIhBrush--}
```
public int getIhBrush()
```


Ottiene o imposta un intero senza segno a 32 bit che specifica l'indice dell'oggetto pennello pattern nella EMF Object Table (sezione 3.1.1.1). Questo indice DEVE essere salvato affinché l'oggetto possa essere riutilizzato o modificato.

**Returns:**
int
### setIhBrush(int value) {#setIhBrush-int-}
```
public void setIhBrush(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che specifica l'indice dell'oggetto pennello pattern nella EMF Object Table (sezione 3.1.1.1). Questo indice DEVE essere salvato affinché l'oggetto possa essere riutilizzato o modificato.

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

