---
title: BitmapV4Header
second_title: Aspose.Imaging for Java API Reference
description: The BitmapV4Header structure is the bitmap information header file.
type: docs
weight: 13
url: /com.aspose.imaging.fileformats.bmp/bitmapv4header/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.bmp.BitmapCoreHeader](../../com.aspose.imaging.fileformats.bmp/bitmapcoreheader), [com.aspose.imaging.fileformats.bmp.BitmapInfoHeader](../../com.aspose.imaging.fileformats.bmp/bitmapinfoheader)
```
public class BitmapV4Header extends BitmapInfoHeader
```

The BitmapV4Header structure is the bitmap information header file. It is an extended version of the BITMAPINFOHEADER structure.
## Methods

| Method | Description |
| --- | --- |
| [getRedMask()](#getRedMask--) | Gets or sets the color mask that specifies the red component of each pixel, valid only if bV4Compression is set to BI\_BITFIELDS. |
| [setRedMask(int value)](#setRedMask-int-) | Gets or sets the color mask that specifies the red component of each pixel, valid only if bV4Compression is set to BI\_BITFIELDS. |
| [getGreenMask()](#getGreenMask--) | Gets or sets the color mask that specifies the green component of each pixel, valid only if bV4Compression is set to BI\_BITFIELDS. |
| [setGreenMask(int value)](#setGreenMask-int-) | Gets or sets the color mask that specifies the green component of each pixel, valid only if bV4Compression is set to BI\_BITFIELDS. |
| [getBlueMask()](#getBlueMask--) | Gets or sets the color mask that specifies the blue component of each pixel, valid only if bV4Compression is set to BI\_BITFIELDS. |
| [setBlueMask(int value)](#setBlueMask-int-) | Gets or sets the color mask that specifies the blue component of each pixel, valid only if bV4Compression is set to BI\_BITFIELDS. |
| [getAlphaMask()](#getAlphaMask--) | Gets or sets the color mask that specifies the alpha component of each pixel. |
| [setAlphaMask(int value)](#setAlphaMask-int-) | Gets or sets the color mask that specifies the alpha component of each pixel. |
| [getCSType()](#getCSType--) | Gets or sets the color space of the DIB. |
| [setCSType(int value)](#setCSType-int-) | Gets or sets the color space of the DIB. |
| [getEndpoints()](#getEndpoints--) | Gets or sets the CoordinatesTriple class. |
| [setEndpoints(CieCoordinatesTriple value)](#setEndpoints-com.aspose.imaging.fileformats.bmp.structures.CieCoordinatesTriple-) | Gets or sets the CoordinatesTriple class. |
| [getGammaRed()](#getGammaRed--) | Gets or sets the gamma red. |
| [setGammaRed(int value)](#setGammaRed-int-) | Gets or sets the gamma red. |
| [getGammaGreen()](#getGammaGreen--) | Gets or sets the gamma green. |
| [setGammaGreen(int value)](#setGammaGreen-int-) | Gets or sets the gamma green. |
| [getGammaBlue()](#getGammaBlue--) | Gets or sets the gamma blue. |
| [setGammaBlue(int value)](#setGammaBlue-int-) | Gets or sets the gamma blue. |
### getRedMask() {#getRedMask--}
```
public int getRedMask()
```


Gets or sets the color mask that specifies the red component of each pixel, valid only if bV4Compression is set to BI\_BITFIELDS.

**Returns:**
int
### setRedMask(int value) {#setRedMask-int-}
```
public void setRedMask(int value)
```


Gets or sets the color mask that specifies the red component of each pixel, valid only if bV4Compression is set to BI\_BITFIELDS.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getGreenMask() {#getGreenMask--}
```
public int getGreenMask()
```


Gets or sets the color mask that specifies the green component of each pixel, valid only if bV4Compression is set to BI\_BITFIELDS.

**Returns:**
int
### setGreenMask(int value) {#setGreenMask-int-}
```
public void setGreenMask(int value)
```


Gets or sets the color mask that specifies the green component of each pixel, valid only if bV4Compression is set to BI\_BITFIELDS.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getBlueMask() {#getBlueMask--}
```
public int getBlueMask()
```


Gets or sets the color mask that specifies the blue component of each pixel, valid only if bV4Compression is set to BI\_BITFIELDS.

**Returns:**
int
### setBlueMask(int value) {#setBlueMask-int-}
```
public void setBlueMask(int value)
```


Gets or sets the color mask that specifies the blue component of each pixel, valid only if bV4Compression is set to BI\_BITFIELDS.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getAlphaMask() {#getAlphaMask--}
```
public int getAlphaMask()
```


Gets or sets the color mask that specifies the alpha component of each pixel.

**Returns:**
int
### setAlphaMask(int value) {#setAlphaMask-int-}
```
public void setAlphaMask(int value)
```


Gets or sets the color mask that specifies the alpha component of each pixel.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getCSType() {#getCSType--}
```
public int getCSType()
```


Gets or sets the color space of the DIB.

**Returns:**
int
### setCSType(int value) {#setCSType-int-}
```
public void setCSType(int value)
```


Gets or sets the color space of the DIB.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getEndpoints() {#getEndpoints--}
```
public CieCoordinatesTriple getEndpoints()
```


Gets or sets the CoordinatesTriple class.

**Returns:**
[CieCoordinatesTriple](../../com.aspose.imaging.fileformats.bmp.structures/ciecoordinatestriple) - The endpoints.
### setEndpoints(CieCoordinatesTriple value) {#setEndpoints-com.aspose.imaging.fileformats.bmp.structures.CieCoordinatesTriple-}
```
public void setEndpoints(CieCoordinatesTriple value)
```


Gets or sets the CoordinatesTriple class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [CieCoordinatesTriple](../../com.aspose.imaging.fileformats.bmp.structures/ciecoordinatestriple) | The endpoints. |

### getGammaRed() {#getGammaRed--}
```
public int getGammaRed()
```


Gets or sets the gamma red.

**Returns:**
int - The gamma red.
### setGammaRed(int value) {#setGammaRed-int-}
```
public void setGammaRed(int value)
```


Gets or sets the gamma red.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The gamma red. |

### getGammaGreen() {#getGammaGreen--}
```
public int getGammaGreen()
```


Gets or sets the gamma green.

**Returns:**
int - The gamma green.
### setGammaGreen(int value) {#setGammaGreen-int-}
```
public void setGammaGreen(int value)
```


Gets or sets the gamma green.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The gamma green. |

### getGammaBlue() {#getGammaBlue--}
```
public int getGammaBlue()
```


Gets or sets the gamma blue.

**Returns:**
int - The gamma blue.
### setGammaBlue(int value) {#setGammaBlue-int-}
```
public void setGammaBlue(int value)
```


Gets or sets the gamma blue.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The gamma blue. |

