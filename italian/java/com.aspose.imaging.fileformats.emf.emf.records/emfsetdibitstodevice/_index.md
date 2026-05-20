---
title: "EmfSetDiBitsToDevice"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il record EMR_SETDIBITSTODEVICE specifica un trasferimento a blocchi di pixel dalle linee di scansione specificate di una bitmap di origine a un rettangolo di destinazione."
type: docs
weight: 124
url: /it/java/com.aspose.imaging.fileformats.emf.emf.records/emfsetdibitstodevice/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfBitmapRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfbitmaprecordtype)
```
public final class EmfSetDiBitsToDevice extends EmfBitmapRecordType
```

Il record EMR\_SETDIBITSTODEVICE specifica un trasferimento a blocchi di pixel dalle linee di scansione specificate di una bitmap sorgente a un rettangolo di destinazione.

Questo record supporta immagini di origine in formato JPEG e PNG. Il campo Compression nell'intestazione della bitmap di origine specifica il formato dell'immagine.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfSetDiBitsToDevice(EmfRecord source)](#EmfSetDiBitsToDevice-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inizializza una nuova istanza della classe `EmfSetDiBitsToDevice`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getBounds()](#getBounds--) | Ottiene o imposta un oggetto WMF RectL ([MS-WMF] sezione 2.2.2.19) che definisce il rettangolo di delimitazione di destinazione in unità dispositivo. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Ottiene o imposta un oggetto WMF RectL ([MS-WMF] sezione 2.2.2.19) che definisce il rettangolo di delimitazione di destinazione in unità dispositivo. |
| [getXDest()](#getXDest--) | Ottiene o imposta un intero con segno a 32 bit che specifica la coordinata logica x dell'angolo superiore sinistro del rettangolo di destinazione. |
| [setXDest(int value)](#setXDest-int-) | Ottiene o imposta un intero con segno a 32 bit che specifica la coordinata logica x dell'angolo superiore sinistro del rettangolo di destinazione. |
| [getYDest()](#getYDest--) | Ottiene o imposta un intero con segno a 32 bit che specifica la coordinata logica y dell'angolo superiore sinistro del rettangolo di destinazione. |
| [setYDest(int value)](#setYDest-int-) | Ottiene o imposta un intero con segno a 32 bit che specifica la coordinata logica y dell'angolo superiore sinistro del rettangolo di destinazione. |
| [getXSrc()](#getXSrc--) | Ottiene o imposta un intero con segno a 32 bit che specifica la coordinata x in pixel dell'angolo inferiore sinistro del rettangolo di origine. |
| [setXSrc(int value)](#setXSrc-int-) | Ottiene o imposta un intero con segno a 32 bit che specifica la coordinata x in pixel dell'angolo inferiore sinistro del rettangolo di origine. |
| [getYSrc()](#getYSrc--) | Ottiene o imposta un intero con segno a 32 bit che specifica la coordinata y in pixel dell'angolo inferiore sinistro del rettangolo di origine. |
| [setYSrc(int value)](#setYSrc-int-) | Ottiene o imposta un intero con segno a 32 bit che specifica la coordinata y in pixel dell'angolo inferiore sinistro del rettangolo di origine. |
| [getCxSrc()](#getCxSrc--) | Ottiene o imposta un intero con segno a 32 bit che specifica la larghezza in pixel del rettangolo di origine. |
| [setCxSrc(int value)](#setCxSrc-int-) | Ottiene o imposta un intero con segno a 32 bit che specifica la larghezza in pixel del rettangolo di origine. |
| [getCySrc()](#getCySrc--) | Ottiene o imposta un intero con segno a 32 bit che specifica l'altezza in pixel del rettangolo di origine |
| [setCySrc(int value)](#setCySrc-int-) | Ottiene o imposta un intero con segno a 32 bit che specifica l'altezza in pixel del rettangolo di origine |
| [getUsageSrc()](#getUsageSrc--) | Ottiene o imposta un intero senza segno a 32 bit che specifica come interpretare i valori nella tavola dei colori nell'intestazione della bitmap di origine. |
| [setUsageSrc(int value)](#setUsageSrc-int-) | Ottiene o imposta un intero senza segno a 32 bit che specifica come interpretare i valori nella tavola dei colori nell'intestazione della bitmap di origine. |
| [getIStartScan()](#getIStartScan--) | Ottiene o imposta un intero senza segno a 32 bit che specifica la prima linea di scansione nell'array. |
| [setIStartScan(int value)](#setIStartScan-int-) | Ottiene o imposta un intero senza segno a 32 bit che specifica la prima linea di scansione nell'array. |
| [getCScans()](#getCScans--) | Ottiene o imposta un intero senza segno a 32 bit che specifica il numero di linee di scansione. |
| [setCScans(int value)](#setCScans-int-) | Ottiene o imposta un intero senza segno a 32 bit che specifica il numero di linee di scansione. |
| [getSourceBitmap()](#getSourceBitmap--) | Ottiene o imposta un buffer contenente la bitmap di origine, che non è necessario sia contiguo con la parte fissa del record EMR\_SETDIBITSTODEVICE. |
| [setSourceBitmap(WmfDeviceIndependentBitmap value)](#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | Ottiene o imposta un buffer contenente la bitmap di origine, che non è necessario sia contiguo con la parte fissa del record EMR\_SETDIBITSTODEVICE. |
### EmfSetDiBitsToDevice(EmfRecord source) {#EmfSetDiBitsToDevice-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetDiBitsToDevice(EmfRecord source)
```


Inizializza una nuova istanza della classe `EmfSetDiBitsToDevice`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La sorgente. |

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


Ottiene o imposta un oggetto WMF RectL ([MS-WMF] sezione 2.2.2.19) che definisce il rettangolo di delimitazione di destinazione in unità dispositivo.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


Ottiene o imposta un oggetto WMF RectL ([MS-WMF] sezione 2.2.2.19) che definisce il rettangolo di delimitazione di destinazione in unità dispositivo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getXDest() {#getXDest--}
```
public int getXDest()
```


Ottiene o imposta un intero con segno a 32 bit che specifica la coordinata logica x dell'angolo superiore sinistro del rettangolo di destinazione.

**Returns:**
int
### setXDest(int value) {#setXDest-int-}
```
public void setXDest(int value)
```


Ottiene o imposta un intero con segno a 32 bit che specifica la coordinata logica x dell'angolo superiore sinistro del rettangolo di destinazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getYDest() {#getYDest--}
```
public int getYDest()
```


Ottiene o imposta un intero con segno a 32 bit che specifica la coordinata logica y dell'angolo superiore sinistro del rettangolo di destinazione.

**Returns:**
int
### setYDest(int value) {#setYDest-int-}
```
public void setYDest(int value)
```


Ottiene o imposta un intero con segno a 32 bit che specifica la coordinata logica y dell'angolo superiore sinistro del rettangolo di destinazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getXSrc() {#getXSrc--}
```
public int getXSrc()
```


Ottiene o imposta un intero con segno a 32 bit che specifica la coordinata x in pixel dell'angolo inferiore sinistro del rettangolo di origine.

**Returns:**
int
### setXSrc(int value) {#setXSrc-int-}
```
public void setXSrc(int value)
```


Ottiene o imposta un intero con segno a 32 bit che specifica la coordinata x in pixel dell'angolo inferiore sinistro del rettangolo di origine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getYSrc() {#getYSrc--}
```
public int getYSrc()
```


Ottiene o imposta un intero con segno a 32 bit che specifica la coordinata y in pixel dell'angolo inferiore sinistro del rettangolo di origine.

**Returns:**
int
### setYSrc(int value) {#setYSrc-int-}
```
public void setYSrc(int value)
```


Ottiene o imposta un intero con segno a 32 bit che specifica la coordinata y in pixel dell'angolo inferiore sinistro del rettangolo di origine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getCxSrc() {#getCxSrc--}
```
public int getCxSrc()
```


Ottiene o imposta un intero con segno a 32 bit che specifica la larghezza in pixel del rettangolo di origine.

**Returns:**
int
### setCxSrc(int value) {#setCxSrc-int-}
```
public void setCxSrc(int value)
```


Ottiene o imposta un intero con segno a 32 bit che specifica la larghezza in pixel del rettangolo di origine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getCySrc() {#getCySrc--}
```
public int getCySrc()
```


Ottiene o imposta un intero con segno a 32 bit che specifica l'altezza in pixel del rettangolo di origine

**Returns:**
int
### setCySrc(int value) {#setCySrc-int-}
```
public void setCySrc(int value)
```


Ottiene o imposta un intero con segno a 32 bit che specifica l'altezza in pixel del rettangolo di origine

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getUsageSrc() {#getUsageSrc--}
```
public int getUsageSrc()
```


Ottiene o imposta un intero senza segno a 32 bit che specifica come interpretare i valori nella tavola dei colori nell'intestazione della bitmap di origine. Questo valore DEVE appartenere all'enumerazione DIBColors (sezione 2.1.9).

**Returns:**
int
### setUsageSrc(int value) {#setUsageSrc-int-}
```
public void setUsageSrc(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che specifica come interpretare i valori nella tavola dei colori nell'intestazione della bitmap di origine. Questo valore DEVE appartenere all'enumerazione DIBColors (sezione 2.1.9).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getIStartScan() {#getIStartScan--}
```
public int getIStartScan()
```


Ottiene o imposta un intero senza segno a 32 bit che specifica la prima linea di scansione nell'array.

**Returns:**
int
### setIStartScan(int value) {#setIStartScan-int-}
```
public void setIStartScan(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che specifica la prima linea di scansione nell'array.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getCScans() {#getCScans--}
```
public int getCScans()
```


Ottiene o imposta un intero senza segno a 32 bit che specifica il numero di linee di scansione.

**Returns:**
int
### setCScans(int value) {#setCScans-int-}
```
public void setCScans(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che specifica il numero di linee di scansione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getSourceBitmap() {#getSourceBitmap--}
```
public WmfDeviceIndependentBitmap getSourceBitmap()
```


Ottiene o imposta un buffer contenente la bitmap di origine, che non è necessario sia contiguo con la parte fissa del record EMR\_SETDIBITSTODEVICE. Di conseguenza, i campi in questo buffer etichettati \"UndefinedSpace\" sono opzionali e DEVONO essere ignorati.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setSourceBitmap(WmfDeviceIndependentBitmap value) {#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setSourceBitmap(WmfDeviceIndependentBitmap value)
```


Ottiene o imposta un buffer contenente la bitmap di origine, che non è necessario sia contiguo con la parte fissa del record EMR\_SETDIBITSTODEVICE. Di conseguenza, i campi in questo buffer etichettati \"UndefinedSpace\" sono opzionali e DEVONO essere ignorati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

