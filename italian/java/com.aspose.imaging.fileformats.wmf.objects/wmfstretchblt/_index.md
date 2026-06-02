---
title: "WmfStretchBlt"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il record META_STRETCHBLT specifica il trasferimento di un blocco di pixel secondo un'operazione raster con possibile espansione o contrazione."
type: docs
weight: 93
url: /it/java/com.aspose.imaging.fileformats.wmf.objects/wmfstretchblt/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging/fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfObject](../../com.aspose.imaging/fileformats.wmf.objects/wmfobject)
```
public class WmfStretchBlt extends WmfObject
```

Il record META\_STRETCHBLT specifica il trasferimento di un blocco di pixel secondo un'operazione raster, con possibile espansione o contrazione.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [WmfStretchBlt()](#WmfStretchBlt--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getRasterOperation()](#getRasterOperation--) | Ottiene o imposta l'operazione raster. |
| [setRasterOperation(int value)](#setRasterOperation-int-) | Ottiene o imposta l'operazione raster. |
| [getSrcHeight()](#getSrcHeight--) | Ottiene o imposta l'altezza della sorgente. |
| [setSrcHeight(short value)](#setSrcHeight-short-) | Ottiene o imposta l'altezza della sorgente. |
| [getSrcWidth()](#getSrcWidth--) | Ottiene o imposta la larghezza della sorgente. |
| [setSrcWidth(short value)](#setSrcWidth-short-) | Ottiene o imposta la larghezza della sorgente. |
| [getSrcPosition()](#getSrcPosition--) | Ottiene o imposta la posizione della sorgente. |
| [setSrcPosition(Point value)](#setSrcPosition-com.aspose.imaging.Point-) | Ottiene o imposta la posizione della sorgente. |
| [getDestHeight()](#getDestHeight--) | Ottiene o imposta l'altezza della destinazione. |
| [setDestHeight(short value)](#setDestHeight-short-) | Ottiene o imposta l'altezza della destinazione. |
| [getDestWidth()](#getDestWidth--) | Ottiene o imposta la larghezza della destinazione. |
| [setDestWidth(short value)](#setDestWidth-short-) | Ottiene o imposta la larghezza della destinazione. |
| [getDstPosition()](#getDstPosition--) | Ottiene o imposta la posizione DST. |
| [setDstPosition(Point value)](#setDstPosition-com.aspose.imaging.Point-) | Ottiene o imposta la posizione DST. |
| [getReserved()](#getReserved--) | Ottiene o imposta il riservato. |
| [setReserved(short value)](#setReserved-short-) | Ottiene o imposta il riservato. |
| [getBitmap()](#getBitmap--) | Ottiene o imposta la bitmap. |
| [setBitmap(WmfBitmap16 value)](#setBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfBitmap16-) | Ottiene o imposta la bitmap. |
### WmfStretchBlt() {#WmfStretchBlt--}
```
public WmfStretchBlt()
```


### getRasterOperation() {#getRasterOperation--}
```
public int getRasterOperation()
```


Ottiene o imposta l'operazione raster.

Valore: I pixel di origine, il pennello corrente nel contesto del dispositivo di riproduzione e i pixel di destinazione devono essere combinati per formare la nuova immagine. Questo codice DEVE essere uno dei valori nell'enumerazione Ternary Raster Operation.

**Returns:**
int
### setRasterOperation(int value) {#setRasterOperation-int-}
```
public void setRasterOperation(int value)
```


Ottiene o imposta l'operazione raster.

Valore: I pixel di origine, il pennello corrente nel contesto del dispositivo di riproduzione e i pixel di destinazione devono essere combinati per formare la nuova immagine. Questo codice DEVE essere uno dei valori nell'enumerazione Ternary Raster Operation.

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

Valore: La larghezza, in unità logiche, del rettangolo di origine.

**Returns:**
short
### setSrcWidth(short value) {#setSrcWidth-short-}
```
public void setSrcWidth(short value)
```


Ottiene o imposta la larghezza della sorgente.

Valore: La larghezza, in unità logiche, del rettangolo di origine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | short |  |

### getSrcPosition() {#getSrcPosition--}
```
public Point getSrcPosition()
```


Ottiene o imposta la posizione della sorgente.

Valore: La posizione di origine.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setSrcPosition(Point value) {#setSrcPosition-com.aspose.imaging.Point-}
```
public void setSrcPosition(Point value)
```


Ottiene o imposta la posizione della sorgente.

Valore: La posizione di origine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

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

### getDstPosition() {#getDstPosition--}
```
public Point getDstPosition()
```


Ottiene o imposta la posizione DST.

Valore: La posizione DST.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setDstPosition(Point value) {#setDstPosition-com.aspose.imaging.Point-}
```
public void setDstPosition(Point value)
```


Ottiene o imposta la posizione DST.

Valore: La posizione DST.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getReserved() {#getReserved--}
```
public short getReserved()
```


Ottiene o imposta il riservato.

Valore: Il riservato. Questo campo DEVE essere ignorato.

**Returns:**
short
### setReserved(short value) {#setReserved-short-}
```
public void setReserved(short value)
```


Ottiene o imposta il riservato.

Valore: Il riservato. Questo campo DEVE essere ignorato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | short |  |

### getBitmap() {#getBitmap--}
```
public WmfBitmap16 getBitmap()
```


Ottiene o imposta la bitmap.

Valore: Il bitmap.

**Returns:**
[WmfBitmap16](../../com.aspose.imaging.fileformats.wmf.objects/wmfbitmap16)
### setBitmap(WmfBitmap16 value) {#setBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfBitmap16-}
```
public void setBitmap(WmfBitmap16 value)
```


Ottiene o imposta la bitmap.

Valore: Il bitmap.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [WmfBitmap16](../../com.aspose.imaging.fileformats.wmf.objects/wmfbitmap16) |  |

