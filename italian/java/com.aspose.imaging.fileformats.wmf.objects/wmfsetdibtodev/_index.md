---
title: "WmfSetDibToDev"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il record META_SETDIBTODEV imposta un blocco di pixel nel contesto del dispositivo di riproduzione utilizzando dati di colore indipendenti dal dispositivo."
type: docs
weight: 75
url: /it/java/com.aspose.imaging.fileformats.wmf.objects/wmfsetdibtodev/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging/fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfObject](../../com.aspose.imaging/fileformats.wmf.objects/wmfobject)
```
public class WmfSetDibToDev extends WmfObject
```

Il record META\\_SETDIBTODEV imposta un blocco di pixel nel contesto del dispositivo di riproduzione utilizzando dati di colore indipendenti dal dispositivo. La sorgente dei dati di colore è un DIB.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [WmfSetDibToDev()](#WmfSetDibToDev--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getColorUsage()](#getColorUsage--) | Ottiene o imposta l'uso del colore. |
| [setColorUsage(int value)](#setColorUsage-int-) | Ottiene o imposta l'uso del colore. |
| [getScanCount()](#getScanCount--) | Ottiene o imposta il conteggio delle scansioni. |
| [setScanCount(int value)](#setScanCount-int-) | Ottiene o imposta il conteggio delle scansioni. |
| [getStartScan()](#getStartScan--) | Ottiene o imposta la scansione iniziale. |
| [setStartScan(int value)](#setStartScan-int-) | Ottiene o imposta la scansione iniziale. |
| [getDibPos()](#getDibPos--) | Ottiene o imposta la posizione del dib. |
| [setDibPos(Point value)](#setDibPos-com.aspose.imaging.Point-) | Ottiene o imposta la posizione del dib. |
| [getHeight()](#getHeight--) | Ottiene o imposta l'altezza. |
| [setHeight(int value)](#setHeight-int-) | Ottiene o imposta l'altezza. |
| [getWidth()](#getWidth--) | Ottiene o imposta la larghezza. |
| [setWidth(int value)](#setWidth-int-) | Ottiene o imposta la larghezza. |
| [getDestPos()](#getDestPos--) | Ottiene o imposta la posizione di destinazione. |
| [setDestPos(Point value)](#setDestPos-com.aspose.imaging.Point-) | Ottiene o imposta la posizione di destinazione. |
| [getDib()](#getDib--) | Ottiene o imposta il dib. |
| [setDib(WmfDeviceIndependentBitmap value)](#setDib-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | Ottiene o imposta il dib. |
### WmfSetDibToDev() {#WmfSetDibToDev--}
```
public WmfSetDibToDev()
```


### getColorUsage() {#getColorUsage--}
```
public int getColorUsage()
```


Ottiene o imposta l'uso del colore.

Valore: Il campo Colors del DIB contiene valori RGB espliciti o indici in una tavolozza. Questo DEVE essere uno dei valori nell'enumerazione `com.aspose.imaging.fileFormats.wmf.objects.wmfSetDibToDev.ColorUsage` (sezione 2.1.1.6).

**Returns:**
int
### setColorUsage(int value) {#setColorUsage-int-}
```
public void setColorUsage(int value)
```


Ottiene o imposta l'uso del colore.

Valore: Il campo Colors del DIB contiene valori RGB espliciti o indici in una tavolozza. Questo DEVE essere uno dei valori nell'enumerazione `com.aspose.imaging.fileFormats.wmf.objects.wmfSetDibToDev.ColorUsage` (sezione 2.1.1.6).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getScanCount() {#getScanCount--}
```
public int getScanCount()
```


Ottiene o imposta il conteggio delle scansioni.

Valore: Il numero di linee di scansione nella sorgente.

**Returns:**
int
### setScanCount(int value) {#setScanCount-int-}
```
public void setScanCount(int value)
```


Ottiene o imposta il conteggio delle scansioni.

Valore: Il numero di linee di scansione nella sorgente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getStartScan() {#getStartScan--}
```
public int getStartScan()
```


Ottiene o imposta la scansione iniziale.

Valore: La linea di scansione iniziale nella sorgente.

**Returns:**
int
### setStartScan(int value) {#setStartScan-int-}
```
public void setStartScan(int value)
```


Ottiene o imposta la scansione iniziale.

Valore: La linea di scansione iniziale nella sorgente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getDibPos() {#getDibPos--}
```
public Point getDibPos()
```


Ottiene o imposta la posizione del dib.

Valore: le coordinate, in unità logiche, del rettangolo di sorgente.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setDibPos(Point value) {#setDibPos-com.aspose.imaging.Point-}
```
public void setDibPos(Point value)
```


Ottiene o imposta la posizione del dib.

Valore: le coordinate, in unità logiche, del rettangolo di sorgente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getHeight() {#getHeight--}
```
public int getHeight()
```


Ottiene o imposta l'altezza.

Valore: l'altezza, in unità logiche, dei rettangoli di sorgente e destinazione.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public void setHeight(int value)
```


Ottiene o imposta l'altezza.

Valore: l'altezza, in unità logiche, dei rettangoli di sorgente e destinazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getWidth() {#getWidth--}
```
public int getWidth()
```


Ottiene o imposta la larghezza.

Valore: la larghezza, in unità logiche, dei rettangoli di sorgente e destinazione.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


Ottiene o imposta la larghezza.

Valore: la larghezza, in unità logiche, dei rettangoli di sorgente e destinazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getDestPos() {#getDestPos--}
```
public Point getDestPos()
```


Ottiene o imposta la posizione di destinazione.

Valore: le coordinate, in unità logiche, dell'angolo superiore sinistro del rettangolo di destinazione.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setDestPos(Point value) {#setDestPos-com.aspose.imaging.Point-}
```
public void setDestPos(Point value)
```


Ottiene o imposta la posizione di destinazione.

Valore: le coordinate, in unità logiche, dell'angolo superiore sinistro del rettangolo di destinazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getDib() {#getDib--}
```
public WmfDeviceIndependentBitmap getDib()
```


Ottiene o imposta il dib.

Valore: Coordinata y, in unità logiche, dell'angolo superiore sinistro del rettangolo di destinazione.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setDib(WmfDeviceIndependentBitmap value) {#setDib-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setDib(WmfDeviceIndependentBitmap value)
```


Ottiene o imposta il dib.

Valore: Coordinata y, in unità logiche, dell'angolo superiore sinistro del rettangolo di destinazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

