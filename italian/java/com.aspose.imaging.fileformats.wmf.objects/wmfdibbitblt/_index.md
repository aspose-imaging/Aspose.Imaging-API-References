---
title: "WmfDibBitBlt"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il record META_DIBBITBLT specifica il trasferimento di un blocco di pixel in formato indipendente dal dispositivo secondo un'operazione raster."
type: docs
weight: 28
url: /it/java/com.aspose.imaging.fileformats.wmf.objects/wmfdibbitblt/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging/fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfObject](../../com.aspose.imaging/fileformats.wmf.objects/wmfobject)
```
public class WmfDibBitBlt extends WmfObject
```

Il record META\_DIBBITBLT specifica il trasferimento di un blocco di pixel in formato indipendente dal dispositivo secondo un'operazione raster.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [WmfDibBitBlt()](#WmfDibBitBlt--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getRasterOperation()](#getRasterOperation--) | Ottiene o imposta l'operazione raster. |
| [setRasterOperation(int value)](#setRasterOperation-int-) | Ottiene o imposta l'operazione raster. |
| [getSrcPos()](#getSrcPos--) | Ottiene o imposta la posizione della sorgente. |
| [setSrcPos(Point value)](#setSrcPos-com.aspose.imaging.Point-) | Ottiene o imposta la posizione della sorgente. |
| [getHeight()](#getHeight--) | Ottiene o imposta l'altezza. |
| [setHeight(short value)](#setHeight-short-) | Ottiene o imposta l'altezza. |
| [getWidth()](#getWidth--) | Ottiene o imposta la larghezza. |
| [setWidth(short value)](#setWidth-short-) | Ottiene o imposta la larghezza. |
| [getDstPos()](#getDstPos--) | Ottiene o imposta la posizione DST. |
| [setDstPos(Point value)](#setDstPos-com.aspose.imaging.Point-) | Ottiene o imposta la posizione DST. |
| [getReserved()](#getReserved--) | Ottiene o imposta il riservato. |
| [setReserved(int value)](#setReserved-int-) | Ottiene o imposta il riservato. |
| [getSource()](#getSource--) | Ottiene o imposta la sorgente. |
| [setSource(WmfDeviceIndependentBitmap value)](#setSource-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | Ottiene o imposta la sorgente. |
### WmfDibBitBlt() {#WmfDibBitBlt--}
```
public WmfDibBitBlt()
```


### getRasterOperation() {#getRasterOperation--}
```
public int getRasterOperation()
```


Ottiene o imposta l'operazione raster.

Valore: I pixel della sorgente, il pennello corrente nel contesto del dispositivo di riproduzione e i pixel di destinazione devono essere combinati per formare la nuova immagine. Questo codice DEVE essere uno dei valori nell'enumerazione Ternary Raster Operation (sezione 2.1.1.31).

**Returns:**
int
### setRasterOperation(int value) {#setRasterOperation-int-}
```
public void setRasterOperation(int value)
```


Ottiene o imposta l'operazione raster.

Valore: I pixel della sorgente, il pennello corrente nel contesto del dispositivo di riproduzione e i pixel di destinazione devono essere combinati per formare la nuova immagine. Questo codice DEVE essere uno dei valori nell'enumerazione Ternary Raster Operation (sezione 2.1.1.31).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getSrcPos() {#getSrcPos--}
```
public Point getSrcPos()
```


Ottiene o imposta la posizione della sorgente.

Valore: le coordinate, in unità logiche, del rettangolo di sorgente.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setSrcPos(Point value) {#setSrcPos-com.aspose.imaging.Point-}
```
public void setSrcPos(Point value)
```


Ottiene o imposta la posizione della sorgente.

Valore: le coordinate, in unità logiche, del rettangolo di sorgente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getHeight() {#getHeight--}
```
public short getHeight()
```


Ottiene o imposta l'altezza.

Valore: l'altezza, in unità logiche, dei rettangoli di sorgente e destinazione.

**Returns:**
short
### setHeight(short value) {#setHeight-short-}
```
public void setHeight(short value)
```


Ottiene o imposta l'altezza.

Valore: l'altezza, in unità logiche, dei rettangoli di sorgente e destinazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | short |  |

### getWidth() {#getWidth--}
```
public short getWidth()
```


Ottiene o imposta la larghezza.

Valore: la larghezza, in unità logiche, dei rettangoli di sorgente e destinazione.

**Returns:**
short
### setWidth(short value) {#setWidth-short-}
```
public void setWidth(short value)
```


Ottiene o imposta la larghezza.

Valore: la larghezza, in unità logiche, dei rettangoli di sorgente e destinazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | short |  |

### getDstPos() {#getDstPos--}
```
public Point getDstPos()
```


Ottiene o imposta la posizione DST.

Valore: le coordinate, in unità logiche, dell'angolo superiore sinistro del rettangolo di destinazione.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setDstPos(Point value) {#setDstPos-com.aspose.imaging.Point-}
```
public void setDstPos(Point value)
```


Ottiene o imposta la posizione DST.

Valore: le coordinate, in unità logiche, dell'angolo superiore sinistro del rettangolo di destinazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getReserved() {#getReserved--}
```
public int getReserved()
```


Ottiene o imposta il riservato.

Valore: il riservato.

**Returns:**
int
### setReserved(int value) {#setReserved-int-}
```
public void setReserved(int value)
```


Ottiene o imposta il riservato.

Valore: il riservato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getSource() {#getSource--}
```
public WmfDeviceIndependentBitmap getSource()
```


Ottiene o imposta la sorgente.

Valore: Un oggetto DeviceIndependentBitmap di dimensione variabile (sezione 2.2.2.9) che definisce il contenuto dell'immagine. Questo oggetto DEVE essere specificato, anche se l'operazione raster non richiede una sorgente.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setSource(WmfDeviceIndependentBitmap value) {#setSource-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setSource(WmfDeviceIndependentBitmap value)
```


Ottiene o imposta la sorgente.

Valore: Un oggetto DeviceIndependentBitmap di dimensione variabile (sezione 2.2.2.9) che definisce il contenuto dell'immagine. Questo oggetto DEVE essere specificato, anche se l'operazione raster non richiede una sorgente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

