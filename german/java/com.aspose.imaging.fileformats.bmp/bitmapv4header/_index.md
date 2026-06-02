---
title: "BitmapV4Header"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Die Struktur BitmapV4Header ist die Bitmap-Informations-Headerdatei."
type: docs
weight: 13
url: /de/java/com.aspose.imaging.fileformats.bmp/bitmapv4header/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.bmp.BitmapCoreHeader](../../com.aspose.imaging.fileformats.bmp/bitmapcoreheader), [com.aspose.imaging.fileformats.bmp.BitmapInfoHeader](../../com.aspose.imaging.fileformats.bmp/bitmapinfoheader)
```
public class BitmapV4Header extends BitmapInfoHeader
```

Die BitmapV4Header‑Struktur ist die Bitmap‑Informations‑Header‑Datei. Sie ist eine erweiterte Version der BITMAPINFOHEADER‑Struktur.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getRedMask()](#getRedMask--) | Liest oder setzt die Farbmaske, die die rote Komponente jedes Pixels angibt, gültig nur, wenn bV4Compression auf BI\_BITFIELDS gesetzt ist. |
| [setRedMask(int value)](#setRedMask-int-) | Liest oder setzt die Farbmaske, die die rote Komponente jedes Pixels angibt, gültig nur, wenn bV4Compression auf BI\_BITFIELDS gesetzt ist. |
| [getGreenMask()](#getGreenMask--) | Liest oder setzt die Farbmaske, die die grüne Komponente jedes Pixels angibt, gültig nur, wenn bV4Compression auf BI\_BITFIELDS gesetzt ist. |
| [setGreenMask(int value)](#setGreenMask-int-) | Liest oder setzt die Farbmaske, die die grüne Komponente jedes Pixels angibt, gültig nur, wenn bV4Compression auf BI\_BITFIELDS gesetzt ist. |
| [getBlueMask()](#getBlueMask--) | Liest oder setzt die Farbmaske, die die blaue Komponente jedes Pixels angibt, gültig nur, wenn bV4Compression auf BI\_BITFIELDS gesetzt ist. |
| [setBlueMask(int value)](#setBlueMask-int-) | Liest oder setzt die Farbmaske, die die blaue Komponente jedes Pixels angibt, gültig nur, wenn bV4Compression auf BI\_BITFIELDS gesetzt ist. |
| [getAlphaMask()](#getAlphaMask--) | Liest oder setzt die Farbmaske, die die Alpha‑Komponente jedes Pixels angibt. |
| [setAlphaMask(int value)](#setAlphaMask-int-) | Liest oder setzt die Farbmaske, die die Alpha‑Komponente jedes Pixels angibt. |
| [getCSType()](#getCSType--) | Liest oder setzt den Farbraum des DIB. |
| [setCSType(int value)](#setCSType-int-) | Liest oder setzt den Farbraum des DIB. |
| [getEndpoints()](#getEndpoints--) | Liest oder setzt die Klasse CoordinatesTriple. |
| [setEndpoints(CieCoordinatesTriple value)](#setEndpoints-com.aspose.imaging.fileformats.bmp.structures.CieCoordinatesTriple-) | Liest oder setzt die Klasse CoordinatesTriple. |
| [getGammaRed()](#getGammaRed--) | Liest oder setzt das Gamma‑Rot. |
| [setGammaRed(int value)](#setGammaRed-int-) | Liest oder setzt das Gamma‑Rot. |
| [getGammaGreen()](#getGammaGreen--) | Liest oder setzt das Gamma‑Grün. |
| [setGammaGreen(int value)](#setGammaGreen-int-) | Liest oder setzt das Gamma‑Grün. |
| [getGammaBlue()](#getGammaBlue--) | Liest oder setzt das Gamma‑Blau. |
| [setGammaBlue(int value)](#setGammaBlue-int-) | Liest oder setzt das Gamma‑Blau. |
### getRedMask() {#getRedMask--}
```
public int getRedMask()
```


Liest oder setzt die Farbmaske, die die rote Komponente jedes Pixels angibt, gültig nur, wenn bV4Compression auf BI\_BITFIELDS gesetzt ist.

**Returns:**
int
### setRedMask(int value) {#setRedMask-int-}
```
public void setRedMask(int value)
```


Liest oder setzt die Farbmaske, die die rote Komponente jedes Pixels angibt, gültig nur, wenn bV4Compression auf BI\_BITFIELDS gesetzt ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getGreenMask() {#getGreenMask--}
```
public int getGreenMask()
```


Liest oder setzt die Farbmaske, die die grüne Komponente jedes Pixels angibt, gültig nur, wenn bV4Compression auf BI\_BITFIELDS gesetzt ist.

**Returns:**
int
### setGreenMask(int value) {#setGreenMask-int-}
```
public void setGreenMask(int value)
```


Liest oder setzt die Farbmaske, die die grüne Komponente jedes Pixels angibt, gültig nur, wenn bV4Compression auf BI\_BITFIELDS gesetzt ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getBlueMask() {#getBlueMask--}
```
public int getBlueMask()
```


Liest oder setzt die Farbmaske, die die blaue Komponente jedes Pixels angibt, gültig nur, wenn bV4Compression auf BI\_BITFIELDS gesetzt ist.

**Returns:**
int
### setBlueMask(int value) {#setBlueMask-int-}
```
public void setBlueMask(int value)
```


Liest oder setzt die Farbmaske, die die blaue Komponente jedes Pixels angibt, gültig nur, wenn bV4Compression auf BI\_BITFIELDS gesetzt ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getAlphaMask() {#getAlphaMask--}
```
public int getAlphaMask()
```


Liest oder setzt die Farbmaske, die die Alpha‑Komponente jedes Pixels angibt.

**Returns:**
int
### setAlphaMask(int value) {#setAlphaMask-int-}
```
public void setAlphaMask(int value)
```


Liest oder setzt die Farbmaske, die die Alpha‑Komponente jedes Pixels angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getCSType() {#getCSType--}
```
public int getCSType()
```


Liest oder setzt den Farbraum des DIB.

**Returns:**
int
### setCSType(int value) {#setCSType-int-}
```
public void setCSType(int value)
```


Liest oder setzt den Farbraum des DIB.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getEndpoints() {#getEndpoints--}
```
public CieCoordinatesTriple getEndpoints()
```


Liest oder setzt die Klasse CoordinatesTriple.

**Returns:**
[CieCoordinatesTriple](../../com.aspose.imaging.fileformats.bmp.structures/ciecoordinatestriple) - The endpoints.
### setEndpoints(CieCoordinatesTriple value) {#setEndpoints-com.aspose.imaging.fileformats.bmp.structures.CieCoordinatesTriple-}
```
public void setEndpoints(CieCoordinatesTriple value)
```


Liest oder setzt die Klasse CoordinatesTriple.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [CieCoordinatesTriple](../../com.aspose.imaging.fileformats.bmp.structures/ciecoordinatestriple) | Die Endpunkte. |

### getGammaRed() {#getGammaRed--}
```
public int getGammaRed()
```


Liest oder setzt das Gamma‑Rot.

**Returns:**
int - das Gamma Rot.
### setGammaRed(int value) {#setGammaRed-int-}
```
public void setGammaRed(int value)
```


Liest oder setzt das Gamma‑Rot.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Das Gamma Rot. |

### getGammaGreen() {#getGammaGreen--}
```
public int getGammaGreen()
```


Liest oder setzt das Gamma‑Grün.

**Returns:**
int - das Gamma Grün.
### setGammaGreen(int value) {#setGammaGreen-int-}
```
public void setGammaGreen(int value)
```


Liest oder setzt das Gamma‑Grün.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Das Gamma Grün. |

### getGammaBlue() {#getGammaBlue--}
```
public int getGammaBlue()
```


Liest oder setzt das Gamma‑Blau.

**Returns:**
int - das Gamma Blau.
### setGammaBlue(int value) {#setGammaBlue-int-}
```
public void setGammaBlue(int value)
```


Liest oder setzt das Gamma‑Blau.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Das Gamma-Blau. |

