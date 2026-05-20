---
title: "BitmapInfoHeader"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Specifica BITMAPINFOHEADER."
type: docs
weight: 12
url: /it/java/com.aspose.imaging.fileformats.bmp/bitmapinfoheader/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.bmp.BitmapCoreHeader](../../com.aspose.imaging.fileformats.bmp/bitmapcoreheader)
```
public class BitmapInfoHeader extends BitmapCoreHeader
```

Specifica BITMAPINFOHEADER. Supporto OS: Windows NT, 3.1x o versioni successive. Caratteristiche: Aggiunge formati a 16 bpp e 32 bpp. Aggiunge compressione RLE.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getBitmapCompression()](#getBitmapCompression--) | Ottiene la compressione bitmap. |
| [setBitmapCompression(long value)](#setBitmapCompression-long-) | Imposta la compressione bitmap. |
| [getBitmapImageSize()](#getBitmapImageSize--) | Ottiene la dimensione dei dati grezzi bitmap in byte. |
| [setBitmapImageSize(long value)](#setBitmapImageSize-long-) | Imposta la dimensione dei dati grezzi bitmap in byte. |
| [getBitmapXPelsPerMeter()](#getBitmapXPelsPerMeter--) | Ottiene la risoluzione orizzontale in pixel. |
| [setBitmapXPelsPerMeter(int value)](#setBitmapXPelsPerMeter-int-) | Ottiene o imposta la risoluzione orizzontale in pixel. |
| [getBitmapYPelsPerMeter()](#getBitmapYPelsPerMeter--) | Ottiene o imposta la risoluzione verticale in pixel. |
| [setBitmapYPelsPerMeter(int value)](#setBitmapYPelsPerMeter-int-) | Ottiene o imposta la risoluzione verticale in pixel. |
| [getBitmapColorsUsed()](#getBitmapColorsUsed--) | Ottiene il numero di colori della palette utilizzati. |
| [setBitmapColorsUsed(long value)](#setBitmapColorsUsed-long-) | Ottiene o imposta il numero di colori della palette utilizzati. |
| [getBitmapColorsImportant()](#getBitmapColorsImportant--) | Ottiene o imposta il numero di colori importanti della palette. |
| [setBitmapColorsImportant(long value)](#setBitmapColorsImportant-long-) | Ottiene o imposta il numero di colori importanti della palette. |
| [getExtraBitMasks()](#getExtraBitMasks--) | Ottiene o imposta le maschere di bit aggiuntive. |
| [setExtraBitMasks(int[] value)](#setExtraBitMasks-int---) | Ottiene o imposta le maschere di bit aggiuntive. |
### getBitmapCompression() {#getBitmapCompression--}
```
public long getBitmapCompression()
```


Ottiene la compressione bitmap.

**Returns:**
long - compressione bitmap.
### setBitmapCompression(long value) {#setBitmapCompression-long-}
```
public void setBitmapCompression(long value)
```


Imposta la compressione bitmap.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | long | compressione bitmap. |

### getBitmapImageSize() {#getBitmapImageSize--}
```
public long getBitmapImageSize()
```


Ottiene la dimensione dei dati grezzi bitmap in byte.

**Returns:**
long - dimensione dei dati grezzi bitmap in byte.
### setBitmapImageSize(long value) {#setBitmapImageSize-long-}
```
public void setBitmapImageSize(long value)
```


Imposta la dimensione dei dati grezzi bitmap in byte.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | long | dimensione dei dati grezzi bitmap in byte. |

### getBitmapXPelsPerMeter() {#getBitmapXPelsPerMeter--}
```
public int getBitmapXPelsPerMeter()
```


Ottiene la risoluzione orizzontale in pixel.

**Returns:**
int - risoluzione orizzontale in pixel.
### setBitmapXPelsPerMeter(int value) {#setBitmapXPelsPerMeter-int-}
```
public void setBitmapXPelsPerMeter(int value)
```


Ottiene o imposta la risoluzione orizzontale in pixel.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | risoluzione orizzontale in pixel. |

### getBitmapYPelsPerMeter() {#getBitmapYPelsPerMeter--}
```
public int getBitmapYPelsPerMeter()
```


Ottiene o imposta la risoluzione verticale in pixel.

**Returns:**
int - risoluzione verticale in pixel.
### setBitmapYPelsPerMeter(int value) {#setBitmapYPelsPerMeter-int-}
```
public void setBitmapYPelsPerMeter(int value)
```


Ottiene o imposta la risoluzione verticale in pixel.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | risoluzione verticale in pixel. |

### getBitmapColorsUsed() {#getBitmapColorsUsed--}
```
public long getBitmapColorsUsed()
```


Ottiene il numero di colori della palette utilizzati.

**Returns:**
long - numero di colori della palette utilizzati.
### setBitmapColorsUsed(long value) {#setBitmapColorsUsed-long-}
```
public void setBitmapColorsUsed(long value)
```


Ottiene o imposta il numero di colori della palette utilizzati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | long | numero di colori della palette utilizzati. |

### getBitmapColorsImportant() {#getBitmapColorsImportant--}
```
public long getBitmapColorsImportant()
```


Ottiene o imposta il numero di colori importanti della palette.

**Returns:**
long - numero di colori importanti della palette.
### setBitmapColorsImportant(long value) {#setBitmapColorsImportant-long-}
```
public void setBitmapColorsImportant(long value)
```


Ottiene o imposta il numero di colori importanti della palette.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | long | numero di colori importanti della tavolozza. |

### getExtraBitMasks() {#getExtraBitMasks--}
```
public int[] getExtraBitMasks()
```


Ottiene o imposta le maschere di bit aggiuntive. Presenti solo nel caso in cui l'intestazione DIB sia BITMAPINFOHEADER e il `BitmapCompression` sia impostato su `BitmapCompression.Bitfields` (RGB) o `BitmapCompression.AlphaBitfields` (RGBA).

**Returns:**
int[] - le maschere di bit aggiuntive.
### setExtraBitMasks(int[] value) {#setExtraBitMasks-int---}
```
public void setExtraBitMasks(int[] value)
```


Ottiene o imposta le maschere di bit aggiuntive. Presenti solo nel caso in cui l'intestazione DIB sia BITMAPINFOHEADER e il `BitmapCompression` sia impostato su `BitmapCompression.Bitfields` (RGB) o `BitmapCompression.AlphaBitfields` (RGBA).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int[] | le maschere di bit aggiuntive. |

