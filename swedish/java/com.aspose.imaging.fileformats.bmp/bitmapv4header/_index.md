---
title: "BitmapV4Header"
second_title: "Aspose.Imaging för Java API-referens"
description: "BitmapV4Header-strukturen är bitmap-informationens headerfil."
type: docs
weight: 13
url: /sv/java/com.aspose.imaging.fileformats.bmp/bitmapv4header/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.bmp.BitmapCoreHeader](../../com.aspose.imaging.fileformats.bmp/bitmapcoreheader), [com.aspose.imaging.fileformats.bmp.BitmapInfoHeader](../../com.aspose.imaging.fileformats.bmp/bitmapinfoheader)
```
public class BitmapV4Header extends BitmapInfoHeader
```

BitmapV4Header-strukturen är bitmapinformationens headerfil. Den är en utökad version av BITMAPINFOHEADER-strukturen.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getRedMask()](#getRedMask--) | Hämtar eller anger färgmasken som specificerar den röda komponenten för varje pixel, giltig endast om bV4Compression är inställd på BI\_BITFIELDS. |
| [setRedMask(int value)](#setRedMask-int-) | Hämtar eller anger färgmasken som specificerar den röda komponenten för varje pixel, giltig endast om bV4Compression är inställd på BI\_BITFIELDS. |
| [getGreenMask()](#getGreenMask--) | Hämtar eller anger färgmasken som specificerar den gröna komponenten för varje pixel, giltig endast om bV4Compression är inställd på BI\_BITFIELDS. |
| [setGreenMask(int value)](#setGreenMask-int-) | Hämtar eller anger färgmasken som specificerar den gröna komponenten för varje pixel, giltig endast om bV4Compression är inställd på BI\_BITFIELDS. |
| [getBlueMask()](#getBlueMask--) | Hämtar eller anger färgmasken som specificerar den blåa komponenten för varje pixel, giltig endast om bV4Compression är inställd på BI\_BITFIELDS. |
| [setBlueMask(int value)](#setBlueMask-int-) | Hämtar eller anger färgmasken som specificerar den blåa komponenten för varje pixel, giltig endast om bV4Compression är inställd på BI\_BITFIELDS. |
| [getAlphaMask()](#getAlphaMask--) | Hämtar eller anger färgmasken som specificerar alfakomponenten för varje pixel. |
| [setAlphaMask(int value)](#setAlphaMask-int-) | Hämtar eller anger färgmasken som specificerar alfakomponenten för varje pixel. |
| [getCSType()](#getCSType--) | Hämtar eller anger färgrymden för DIB. |
| [setCSType(int value)](#setCSType-int-) | Hämtar eller anger färgrymden för DIB. |
| [getEndpoints()](#getEndpoints--) | Hämtar eller anger CoordinatesTriple-klassen. |
| [setEndpoints(CieCoordinatesTriple value)](#setEndpoints-com.aspose.imaging.fileformats.bmp.structures.CieCoordinatesTriple-) | Hämtar eller anger CoordinatesTriple-klassen. |
| [getGammaRed()](#getGammaRed--) | Hämtar eller anger den röda gamma. |
| [setGammaRed(int value)](#setGammaRed-int-) | Hämtar eller anger den röda gamma. |
| [getGammaGreen()](#getGammaGreen--) | Hämtar eller anger den gröna gamma. |
| [setGammaGreen(int value)](#setGammaGreen-int-) | Hämtar eller anger den gröna gamma. |
| [getGammaBlue()](#getGammaBlue--) | Hämtar eller anger den blå gamma. |
| [setGammaBlue(int value)](#setGammaBlue-int-) | Hämtar eller anger den blå gamma. |
### getRedMask() {#getRedMask--}
```
public int getRedMask()
```


Hämtar eller anger färgmasken som specificerar den röda komponenten för varje pixel, giltig endast om bV4Compression är inställd på BI\_BITFIELDS.

**Returns:**
int
### setRedMask(int value) {#setRedMask-int-}
```
public void setRedMask(int value)
```


Hämtar eller anger färgmasken som specificerar den röda komponenten för varje pixel, giltig endast om bV4Compression är inställd på BI\_BITFIELDS.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getGreenMask() {#getGreenMask--}
```
public int getGreenMask()
```


Hämtar eller anger färgmasken som specificerar den gröna komponenten för varje pixel, giltig endast om bV4Compression är inställd på BI\_BITFIELDS.

**Returns:**
int
### setGreenMask(int value) {#setGreenMask-int-}
```
public void setGreenMask(int value)
```


Hämtar eller anger färgmasken som specificerar den gröna komponenten för varje pixel, giltig endast om bV4Compression är inställd på BI\_BITFIELDS.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getBlueMask() {#getBlueMask--}
```
public int getBlueMask()
```


Hämtar eller anger färgmasken som specificerar den blåa komponenten för varje pixel, giltig endast om bV4Compression är inställd på BI\_BITFIELDS.

**Returns:**
int
### setBlueMask(int value) {#setBlueMask-int-}
```
public void setBlueMask(int value)
```


Hämtar eller anger färgmasken som specificerar den blåa komponenten för varje pixel, giltig endast om bV4Compression är inställd på BI\_BITFIELDS.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getAlphaMask() {#getAlphaMask--}
```
public int getAlphaMask()
```


Hämtar eller anger färgmasken som specificerar alfakomponenten för varje pixel.

**Returns:**
int
### setAlphaMask(int value) {#setAlphaMask-int-}
```
public void setAlphaMask(int value)
```


Hämtar eller anger färgmasken som specificerar alfakomponenten för varje pixel.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getCSType() {#getCSType--}
```
public int getCSType()
```


Hämtar eller anger färgrymden för DIB.

**Returns:**
int
### setCSType(int value) {#setCSType-int-}
```
public void setCSType(int value)
```


Hämtar eller anger färgrymden för DIB.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getEndpoints() {#getEndpoints--}
```
public CieCoordinatesTriple getEndpoints()
```


Hämtar eller anger CoordinatesTriple-klassen.

**Returns:**
[CieCoordinatesTriple](../../com.aspose.imaging.fileformats.bmp.structures/ciecoordinatestriple) - The endpoints.
### setEndpoints(CieCoordinatesTriple value) {#setEndpoints-com.aspose.imaging.fileformats.bmp.structures.CieCoordinatesTriple-}
```
public void setEndpoints(CieCoordinatesTriple value)
```


Hämtar eller anger CoordinatesTriple-klassen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [CieCoordinatesTriple](../../com.aspose.imaging.fileformats.bmp.structures/ciecoordinatestriple) | Ändpunkterna. |

### getGammaRed() {#getGammaRed--}
```
public int getGammaRed()
```


Hämtar eller anger den röda gamma.

**Returns:**
int - Den röda gamma.
### setGammaRed(int value) {#setGammaRed-int-}
```
public void setGammaRed(int value)
```


Hämtar eller anger den röda gamma.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | Den röda gamma. |

### getGammaGreen() {#getGammaGreen--}
```
public int getGammaGreen()
```


Hämtar eller anger den gröna gamma.

**Returns:**
int - Den gröna gamma.
### setGammaGreen(int value) {#setGammaGreen-int-}
```
public void setGammaGreen(int value)
```


Hämtar eller anger den gröna gamma.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | Den gröna gamma. |

### getGammaBlue() {#getGammaBlue--}
```
public int getGammaBlue()
```


Hämtar eller anger den blå gamma.

**Returns:**
int - Den blå gamma.
### setGammaBlue(int value) {#setGammaBlue-int-}
```
public void setGammaBlue(int value)
```


Hämtar eller anger den blå gamma.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | Den gamma blå. |

