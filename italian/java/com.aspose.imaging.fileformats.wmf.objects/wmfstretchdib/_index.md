---
title: "WmfStretchDib"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "L'oggetto wmf Stretch DIB."
type: docs
weight: 94
url: /it/java/com.aspose.imaging.fileformats.wmf.objects/wmfstretchdib/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging/fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfObject](../../com.aspose.imaging/fileformats.wmf.objects/wmfobject)
```
public class WmfStretchDib extends WmfObject
```

L'oggetto wmf Stretch DIB.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [WmfStretchDib()](#WmfStretchDib--) | WMFs il record. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getRasterOperation()](#getRasterOperation--) | Ottiene o imposta l'operazione raster. |
| [setRasterOperation(int value)](#setRasterOperation-int-) | Ottiene o imposta l'operazione raster. |
| [getColorUsage()](#getColorUsage--) | Ottiene o imposta l'uso del colore. |
| [setColorUsage(int value)](#setColorUsage-int-) | Ottiene o imposta l'uso del colore. |
| [getSrcHeight()](#getSrcHeight--) | Ottiene o imposta l'altezza della sorgente. |
| [setSrcHeight(short value)](#setSrcHeight-short-) | Ottiene o imposta l'altezza della sorgente. |
| [getSrcWidth()](#getSrcWidth--) | Ottiene o imposta la larghezza della sorgente. |
| [setSrcWidth(short value)](#setSrcWidth-short-) | Ottiene o imposta la larghezza della sorgente. |
| [getYSrc()](#getYSrc--) | Ottiene o imposta la y della sorgente. |
| [setYSrc(short value)](#setYSrc-short-) | Ottiene o imposta la y della sorgente. |
| [getXSrc()](#getXSrc--) | Ottiene o imposta la x della sorgente. |
| [setXSrc(short value)](#setXSrc-short-) | Ottiene o imposta la x della sorgente. |
| [getDestHeight()](#getDestHeight--) | Ottiene o imposta l'altezza della destinazione. |
| [setDestHeight(short value)](#setDestHeight-short-) | Ottiene o imposta l'altezza della destinazione. |
| [getDestWidth()](#getDestWidth--) | Ottiene o imposta la larghezza della destinazione. |
| [setDestWidth(short value)](#setDestWidth-short-) | Ottiene o imposta la larghezza della destinazione. |
| [getYDest()](#getYDest--) | Ottiene o imposta la y della destinazione. |
| [setYDest(short value)](#setYDest-short-) | Ottiene o imposta la y della destinazione. |
| [getXDest()](#getXDest--) | Ottiene o imposta la x della destinazione. |
| [setXDest(short value)](#setXDest-short-) | Ottiene o imposta la x della destinazione. |
| [getSourceBitmap()](#getSourceBitmap--) | Ottiene o imposta il bitmap di origine. |
| [setSourceBitmap(WmfDeviceIndependentBitmap value)](#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | Ottiene o imposta il bitmap di origine. |
### WmfStretchDib() {#WmfStretchDib--}
```
public WmfStretchDib()
```


WMFs il record.

### getRasterOperation() {#getRasterOperation--}
```
public int getRasterOperation()
```


Ottiene o imposta l'operazione raster.

Valore: Il pennello corrente nel contesto del dispositivo di riproduzione, e i pixel di destinazione devono essere combinati per formare la nuova immagine. Questo codice DEVE essere uno dei valori nella Enumerazione delle Operazioni Raster Ternarie (sezione 2.1.1.31).

**Returns:**
int
### setRasterOperation(int value) {#setRasterOperation-int-}
```
public void setRasterOperation(int value)
```


Ottiene o imposta l'operazione raster.

Valore: Il pennello corrente nel contesto del dispositivo di riproduzione, e i pixel di destinazione devono essere combinati per formare la nuova immagine. Questo codice DEVE essere uno dei valori nella Enumerazione delle Operazioni Raster Ternarie (sezione 2.1.1.31).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getColorUsage() {#getColorUsage--}
```
public int getColorUsage()
```


Ottiene o imposta l'uso del colore.

Valore:

Il campo Colors del DIB contiene valori RGB espliciti o indici in una tavolozza. Questo valore DEVE essere nel `com.aspose.imaging.fileFormats.wmf.objects.wmfStretchDib.ColorUsage`

Enumerazione (sezione 2.1.1.6).

**Returns:**
int
### setColorUsage(int value) {#setColorUsage-int-}
```
public void setColorUsage(int value)
```


Ottiene o imposta l'uso del colore.

Valore:

Il campo Colors del DIB contiene valori RGB espliciti o indici in una tavolozza. Questo valore DEVE essere nel `com.aspose.imaging.fileFormats.wmf.objects.wmfStretchDib.ColorUsage`

Enumerazione (sezione 2.1.1.6).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getSrcHeight() {#getSrcHeight--}
```
public short getSrcHeight()
```


Ottiene o imposta l'altezza della sorgente.

Valore: L'altezza, in unità logiche, del rettangolo di origine.

**Returns:**
short
### setSrcHeight(short value) {#setSrcHeight-short-}
```
public void setSrcHeight(short value)
```


Ottiene o imposta l'altezza della sorgente.

Valore: L'altezza, in unità logiche, del rettangolo di origine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | short |  |

### getSrcWidth() {#getSrcWidth--}
```
public short getSrcWidth()
```


Ottiene o imposta la larghezza della sorgente.

Valore: La larghezza, in unità logiche, del rettangolo di origine

**Returns:**
short
### setSrcWidth(short value) {#setSrcWidth-short-}
```
public void setSrcWidth(short value)
```


Ottiene o imposta la larghezza della sorgente.

Valore: La larghezza, in unità logiche, del rettangolo di origine

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | short |  |

### getYSrc() {#getYSrc--}
```
public short getYSrc()
```


Ottiene o imposta la y della sorgente.

Valore: La coordinata y, in unità logiche, dell'angolo superiore sinistro del rettangolo di origine.

**Returns:**
short
### setYSrc(short value) {#setYSrc-short-}
```
public void setYSrc(short value)
```


Ottiene o imposta la y della sorgente.

Valore: La coordinata y, in unità logiche, dell'angolo superiore sinistro del rettangolo di origine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | short |  |

### getXSrc() {#getXSrc--}
```
public short getXSrc()
```


Ottiene o imposta la x della sorgente.

Valore: La coordinata x, in unità logiche, dell'angolo superiore sinistro del rettangolo di origine.

**Returns:**
short
### setXSrc(short value) {#setXSrc-short-}
```
public void setXSrc(short value)
```


Ottiene o imposta la x della sorgente.

Valore: La coordinata x, in unità logiche, dell'angolo superiore sinistro del rettangolo di origine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | short |  |

### getDestHeight() {#getDestHeight--}
```
public short getDestHeight()
```


Ottiene o imposta l'altezza della destinazione.

Valore: L'altezza, in unità logiche, del rettangolo di destinazione.

**Returns:**
short
### setDestHeight(short value) {#setDestHeight-short-}
```
public void setDestHeight(short value)
```


Ottiene o imposta l'altezza della destinazione.

Valore: L'altezza, in unità logiche, del rettangolo di destinazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | short |  |

### getDestWidth() {#getDestWidth--}
```
public short getDestWidth()
```


Ottiene o imposta la larghezza della destinazione.

Valore: La larghezza, in unità logiche, del rettangolo di destinazione.

**Returns:**
short
### setDestWidth(short value) {#setDestWidth-short-}
```
public void setDestWidth(short value)
```


Ottiene o imposta la larghezza della destinazione.

Valore: La larghezza, in unità logiche, del rettangolo di destinazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | short |  |

### getYDest() {#getYDest--}
```
public short getYDest()
```


Ottiene o imposta la y della destinazione.

Valore: La coordinata y, in unità logiche, dell'angolo superiore sinistro del rettangolo di destinazione.

**Returns:**
short
### setYDest(short value) {#setYDest-short-}
```
public void setYDest(short value)
```


Ottiene o imposta la y della destinazione.

Valore: La coordinata y, in unità logiche, dell'angolo superiore sinistro del rettangolo di destinazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | short |  |

### getXDest() {#getXDest--}
```
public short getXDest()
```


Ottiene o imposta la x della destinazione.

Valore: La coordinata x, in unità logiche, dell'angolo superiore sinistro del rettangolo di destinazione.

**Returns:**
short
### setXDest(short value) {#setXDest-short-}
```
public void setXDest(short value)
```


Ottiene o imposta la x della destinazione.

Valore: La coordinata x, in unità logiche, dell'angolo superiore sinistro del rettangolo di destinazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | short |  |

### getSourceBitmap() {#getSourceBitmap--}
```
public WmfDeviceIndependentBitmap getSourceBitmap()
```


Ottiene o imposta il bitmap di origine.

Valore: La bitmap di origine.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setSourceBitmap(WmfDeviceIndependentBitmap value) {#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setSourceBitmap(WmfDeviceIndependentBitmap value)
```


Ottiene o imposta il bitmap di origine.

Valore: La bitmap di origine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

