---
title: "BitmapV4Header"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "La estructura BitmapV4Header es el archivo de encabezado de información de mapa de bits."
type: docs
weight: 13
url: /es/java/com.aspose.imaging.fileformats.bmp/bitmapv4header/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.bmp.BitmapCoreHeader](../../com.aspose.imaging.fileformats.bmp/bitmapcoreheader), [com.aspose.imaging.fileformats.bmp.BitmapInfoHeader](../../com.aspose.imaging.fileformats.bmp/bitmapinfoheader)
```
public class BitmapV4Header extends BitmapInfoHeader
```

La estructura BitmapV4Header es el archivo de encabezado de información del mapa de bits. Es una versión ampliada de la estructura BITMAPINFOHEADER.
## Métodos

| Método | Descripción |
| --- | --- |
| [getRedMask()](#getRedMask--) | Obtiene o establece la máscara de color que especifica el componente rojo de cada píxel, válida solo si bV4Compression está configurado a BI\_BITFIELDS. |
| [setRedMask(int value)](#setRedMask-int-) | Obtiene o establece la máscara de color que especifica el componente rojo de cada píxel, válida solo si bV4Compression está configurado a BI\_BITFIELDS. |
| [getGreenMask()](#getGreenMask--) | Obtiene o establece la máscara de color que especifica el componente verde de cada píxel, válida solo si bV4Compression está configurado a BI\_BITFIELDS. |
| [setGreenMask(int value)](#setGreenMask-int-) | Obtiene o establece la máscara de color que especifica el componente verde de cada píxel, válida solo si bV4Compression está configurado a BI\_BITFIELDS. |
| [getBlueMask()](#getBlueMask--) | Obtiene o establece la máscara de color que especifica el componente azul de cada píxel, válida solo si bV4Compression está configurado a BI\_BITFIELDS. |
| [setBlueMask(int value)](#setBlueMask-int-) | Obtiene o establece la máscara de color que especifica el componente azul de cada píxel, válida solo si bV4Compression está configurado a BI\_BITFIELDS. |
| [getAlphaMask()](#getAlphaMask--) | Obtiene o establece la máscara de color que especifica el componente alfa de cada píxel. |
| [setAlphaMask(int value)](#setAlphaMask-int-) | Obtiene o establece la máscara de color que especifica el componente alfa de cada píxel. |
| [getCSType()](#getCSType--) | Obtiene o establece el espacio de color del DIB. |
| [setCSType(int value)](#setCSType-int-) | Obtiene o establece el espacio de color del DIB. |
| [getEndpoints()](#getEndpoints--) | Obtiene o establece la clase CoordinatesTriple. |
| [setEndpoints(CieCoordinatesTriple value)](#setEndpoints-com.aspose.imaging.fileformats.bmp.structures.CieCoordinatesTriple-) | Obtiene o establece la clase CoordinatesTriple. |
| [getGammaRed()](#getGammaRed--) | Obtiene o establece la gamma roja. |
| [setGammaRed(int value)](#setGammaRed-int-) | Obtiene o establece la gamma roja. |
| [getGammaGreen()](#getGammaGreen--) | Obtiene o establece la gamma verde. |
| [setGammaGreen(int value)](#setGammaGreen-int-) | Obtiene o establece la gamma verde. |
| [getGammaBlue()](#getGammaBlue--) | Obtiene o establece la gamma azul. |
| [setGammaBlue(int value)](#setGammaBlue-int-) | Obtiene o establece la gamma azul. |
### getRedMask() {#getRedMask--}
```
public int getRedMask()
```


Obtiene o establece la máscara de color que especifica el componente rojo de cada píxel, válida solo si bV4Compression está configurado a BI\_BITFIELDS.

**Returns:**
int
### setRedMask(int value) {#setRedMask-int-}
```
public void setRedMask(int value)
```


Obtiene o establece la máscara de color que especifica el componente rojo de cada píxel, válida solo si bV4Compression está configurado a BI\_BITFIELDS.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getGreenMask() {#getGreenMask--}
```
public int getGreenMask()
```


Obtiene o establece la máscara de color que especifica el componente verde de cada píxel, válida solo si bV4Compression está configurado a BI\_BITFIELDS.

**Returns:**
int
### setGreenMask(int value) {#setGreenMask-int-}
```
public void setGreenMask(int value)
```


Obtiene o establece la máscara de color que especifica el componente verde de cada píxel, válida solo si bV4Compression está configurado a BI\_BITFIELDS.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getBlueMask() {#getBlueMask--}
```
public int getBlueMask()
```


Obtiene o establece la máscara de color que especifica el componente azul de cada píxel, válida solo si bV4Compression está configurado a BI\_BITFIELDS.

**Returns:**
int
### setBlueMask(int value) {#setBlueMask-int-}
```
public void setBlueMask(int value)
```


Obtiene o establece la máscara de color que especifica el componente azul de cada píxel, válida solo si bV4Compression está configurado a BI\_BITFIELDS.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getAlphaMask() {#getAlphaMask--}
```
public int getAlphaMask()
```


Obtiene o establece la máscara de color que especifica el componente alfa de cada píxel.

**Returns:**
int
### setAlphaMask(int value) {#setAlphaMask-int-}
```
public void setAlphaMask(int value)
```


Obtiene o establece la máscara de color que especifica el componente alfa de cada píxel.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getCSType() {#getCSType--}
```
public int getCSType()
```


Obtiene o establece el espacio de color del DIB.

**Returns:**
int
### setCSType(int value) {#setCSType-int-}
```
public void setCSType(int value)
```


Obtiene o establece el espacio de color del DIB.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getEndpoints() {#getEndpoints--}
```
public CieCoordinatesTriple getEndpoints()
```


Obtiene o establece la clase CoordinatesTriple.

**Returns:**
[CieCoordinatesTriple](../../com.aspose.imaging.fileformats.bmp.structures/ciecoordinatestriple) - The endpoints.
### setEndpoints(CieCoordinatesTriple value) {#setEndpoints-com.aspose.imaging.fileformats.bmp.structures.CieCoordinatesTriple-}
```
public void setEndpoints(CieCoordinatesTriple value)
```


Obtiene o establece la clase CoordinatesTriple.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [CieCoordinatesTriple](../../com.aspose.imaging.fileformats.bmp.structures/ciecoordinatestriple) | Los puntos finales. |

### getGammaRed() {#getGammaRed--}
```
public int getGammaRed()
```


Obtiene o establece la gamma roja.

**Returns:**
int - La gamma roja.
### setGammaRed(int value) {#setGammaRed-int-}
```
public void setGammaRed(int value)
```


Obtiene o establece la gamma roja.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | La gamma roja. |

### getGammaGreen() {#getGammaGreen--}
```
public int getGammaGreen()
```


Obtiene o establece la gamma verde.

**Returns:**
int - La gamma verde.
### setGammaGreen(int value) {#setGammaGreen-int-}
```
public void setGammaGreen(int value)
```


Obtiene o establece la gamma verde.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | La gamma verde. |

### getGammaBlue() {#getGammaBlue--}
```
public int getGammaBlue()
```


Obtiene o establece la gamma azul.

**Returns:**
int - La gamma azul.
### setGammaBlue(int value) {#setGammaBlue-int-}
```
public void setGammaBlue(int value)
```


Obtiene o establece la gamma azul.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | El gamma azul. |

