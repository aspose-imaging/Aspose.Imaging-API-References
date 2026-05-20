---
title: "BitmapV4Header"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "La struttura BitmapV4Header è il file di intestazione delle informazioni bitmap."
type: docs
weight: 13
url: /it/java/com.aspose.imaging.fileformats.bmp/bitmapv4header/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.bmp.BitmapCoreHeader](../../com.aspose.imaging.fileformats.bmp/bitmapcoreheader), [com.aspose.imaging.fileformats.bmp.BitmapInfoHeader](../../com.aspose.imaging.fileformats.bmp/bitmapinfoheader)
```
public class BitmapV4Header extends BitmapInfoHeader
```

La struttura BitmapV4Header è il file di intestazione delle informazioni bitmap. È una versione estesa della struttura BITMAPINFOHEADER.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getRedMask()](#getRedMask--) | Ottiene o imposta la maschera di colore che specifica il componente rosso di ogni pixel, valida solo se bV4Compression è impostato su BI\_BITFIELDS. |
| [setRedMask(int value)](#setRedMask-int-) | Ottiene o imposta la maschera di colore che specifica il componente rosso di ogni pixel, valida solo se bV4Compression è impostato su BI\_BITFIELDS. |
| [getGreenMask()](#getGreenMask--) | Ottiene o imposta la maschera di colore che specifica il componente verde di ogni pixel, valida solo se bV4Compression è impostato su BI\_BITFIELDS. |
| [setGreenMask(int value)](#setGreenMask-int-) | Ottiene o imposta la maschera di colore che specifica il componente verde di ogni pixel, valida solo se bV4Compression è impostato su BI\_BITFIELDS. |
| [getBlueMask()](#getBlueMask--) | Ottiene o imposta la maschera di colore che specifica il componente blu di ogni pixel, valida solo se bV4Compression è impostato su BI\_BITFIELDS. |
| [setBlueMask(int value)](#setBlueMask-int-) | Ottiene o imposta la maschera di colore che specifica il componente blu di ogni pixel, valida solo se bV4Compression è impostato su BI\_BITFIELDS. |
| [getAlphaMask()](#getAlphaMask--) | Ottiene o imposta la maschera di colore che specifica il componente alfa di ogni pixel. |
| [setAlphaMask(int value)](#setAlphaMask-int-) | Ottiene o imposta la maschera di colore che specifica il componente alfa di ogni pixel. |
| [getCSType()](#getCSType--) | Ottiene o imposta lo spazio colore del DIB. |
| [setCSType(int value)](#setCSType-int-) | Ottiene o imposta lo spazio colore del DIB. |
| [getEndpoints()](#getEndpoints--) | Ottiene o imposta la classe CoordinatesTriple. |
| [setEndpoints(CieCoordinatesTriple value)](#setEndpoints-com.aspose.imaging.fileformats.bmp.structures.CieCoordinatesTriple-) | Ottiene o imposta la classe CoordinatesTriple. |
| [getGammaRed()](#getGammaRed--) | Ottiene o imposta il gamma rosso. |
| [setGammaRed(int value)](#setGammaRed-int-) | Ottiene o imposta il gamma rosso. |
| [getGammaGreen()](#getGammaGreen--) | Ottiene o imposta il gamma verde. |
| [setGammaGreen(int value)](#setGammaGreen-int-) | Ottiene o imposta il gamma verde. |
| [getGammaBlue()](#getGammaBlue--) | Ottiene o imposta il gamma blu. |
| [setGammaBlue(int value)](#setGammaBlue-int-) | Ottiene o imposta il gamma blu. |
### getRedMask() {#getRedMask--}
```
public int getRedMask()
```


Ottiene o imposta la maschera di colore che specifica il componente rosso di ogni pixel, valida solo se bV4Compression è impostato su BI\_BITFIELDS.

**Returns:**
int
### setRedMask(int value) {#setRedMask-int-}
```
public void setRedMask(int value)
```


Ottiene o imposta la maschera di colore che specifica il componente rosso di ogni pixel, valida solo se bV4Compression è impostato su BI\_BITFIELDS.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getGreenMask() {#getGreenMask--}
```
public int getGreenMask()
```


Ottiene o imposta la maschera di colore che specifica il componente verde di ogni pixel, valida solo se bV4Compression è impostato su BI\_BITFIELDS.

**Returns:**
int
### setGreenMask(int value) {#setGreenMask-int-}
```
public void setGreenMask(int value)
```


Ottiene o imposta la maschera di colore che specifica il componente verde di ogni pixel, valida solo se bV4Compression è impostato su BI\_BITFIELDS.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getBlueMask() {#getBlueMask--}
```
public int getBlueMask()
```


Ottiene o imposta la maschera di colore che specifica il componente blu di ogni pixel, valida solo se bV4Compression è impostato su BI\_BITFIELDS.

**Returns:**
int
### setBlueMask(int value) {#setBlueMask-int-}
```
public void setBlueMask(int value)
```


Ottiene o imposta la maschera di colore che specifica il componente blu di ogni pixel, valida solo se bV4Compression è impostato su BI\_BITFIELDS.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getAlphaMask() {#getAlphaMask--}
```
public int getAlphaMask()
```


Ottiene o imposta la maschera di colore che specifica il componente alfa di ogni pixel.

**Returns:**
int
### setAlphaMask(int value) {#setAlphaMask-int-}
```
public void setAlphaMask(int value)
```


Ottiene o imposta la maschera di colore che specifica il componente alfa di ogni pixel.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getCSType() {#getCSType--}
```
public int getCSType()
```


Ottiene o imposta lo spazio colore del DIB.

**Returns:**
int
### setCSType(int value) {#setCSType-int-}
```
public void setCSType(int value)
```


Ottiene o imposta lo spazio colore del DIB.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getEndpoints() {#getEndpoints--}
```
public CieCoordinatesTriple getEndpoints()
```


Ottiene o imposta la classe CoordinatesTriple.

**Returns:**
[CieCoordinatesTriple](../../com.aspose.imaging.fileformats.bmp.structures/ciecoordinatestriple) - The endpoints.
### setEndpoints(CieCoordinatesTriple value) {#setEndpoints-com.aspose.imaging.fileformats.bmp.structures.CieCoordinatesTriple-}
```
public void setEndpoints(CieCoordinatesTriple value)
```


Ottiene o imposta la classe CoordinatesTriple.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [CieCoordinatesTriple](../../com.aspose.imaging.fileformats.bmp.structures/ciecoordinatestriple) | Gli endpoint. |

### getGammaRed() {#getGammaRed--}
```
public int getGammaRed()
```


Ottiene o imposta il gamma rosso.

**Returns:**
int - Il gamma rosso.
### setGammaRed(int value) {#setGammaRed-int-}
```
public void setGammaRed(int value)
```


Ottiene o imposta il gamma rosso.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | Il gamma rosso. |

### getGammaGreen() {#getGammaGreen--}
```
public int getGammaGreen()
```


Ottiene o imposta il gamma verde.

**Returns:**
int - Il gamma verde.
### setGammaGreen(int value) {#setGammaGreen-int-}
```
public void setGammaGreen(int value)
```


Ottiene o imposta il gamma verde.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | Il gamma verde. |

### getGammaBlue() {#getGammaBlue--}
```
public int getGammaBlue()
```


Ottiene o imposta il gamma blu.

**Returns:**
int - Il gamma blu.
### setGammaBlue(int value) {#setGammaBlue-int-}
```
public void setGammaBlue(int value)
```


Ottiene o imposta il gamma blu.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | Il gamma blu. |

