---
title: "BitmapV4Header"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "La structure BitmapV4Header est le fichier d'en-tête d'information bitmap."
type: docs
weight: 13
url: /fr/java/com.aspose.imaging.fileformats.bmp/bitmapv4header/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.bmp.BitmapCoreHeader](../../com.aspose.imaging.fileformats.bmp/bitmapcoreheader), [com.aspose.imaging.fileformats.bmp.BitmapInfoHeader](../../com.aspose.imaging.fileformats.bmp/bitmapinfoheader)
```
public class BitmapV4Header extends BitmapInfoHeader
```

La structure BitmapV4Header est le fichier d'en-tête d'information bitmap. C'est une version étendue de la structure BITMAPINFOHEADER.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getRedMask()](#getRedMask--) | Obtient ou définit le masque de couleur qui spécifie le composant rouge de chaque pixel, valable uniquement si bV4Compression est défini sur BI\_BITFIELDS. |
| [setRedMask(int value)](#setRedMask-int-) | Obtient ou définit le masque de couleur qui spécifie le composant rouge de chaque pixel, valable uniquement si bV4Compression est défini sur BI\_BITFIELDS. |
| [getGreenMask()](#getGreenMask--) | Obtient ou définit le masque de couleur qui spécifie le composant vert de chaque pixel, valable uniquement si bV4Compression est défini sur BI\_BITFIELDS. |
| [setGreenMask(int value)](#setGreenMask-int-) | Obtient ou définit le masque de couleur qui spécifie le composant vert de chaque pixel, valable uniquement si bV4Compression est défini sur BI\_BITFIELDS. |
| [getBlueMask()](#getBlueMask--) | Obtient ou définit le masque de couleur qui spécifie le composant bleu de chaque pixel, valable uniquement si bV4Compression est défini sur BI\_BITFIELDS. |
| [setBlueMask(int value)](#setBlueMask-int-) | Obtient ou définit le masque de couleur qui spécifie le composant bleu de chaque pixel, valable uniquement si bV4Compression est défini sur BI\_BITFIELDS. |
| [getAlphaMask()](#getAlphaMask--) | Obtient ou définit le masque de couleur qui spécifie le composant alpha de chaque pixel. |
| [setAlphaMask(int value)](#setAlphaMask-int-) | Obtient ou définit le masque de couleur qui spécifie le composant alpha de chaque pixel. |
| [getCSType()](#getCSType--) | Obtient ou définit l'espace colorimétrique du DIB. |
| [setCSType(int value)](#setCSType-int-) | Obtient ou définit l'espace colorimétrique du DIB. |
| [getEndpoints()](#getEndpoints--) | Obtient ou définit la classe CoordinatesTriple. |
| [setEndpoints(CieCoordinatesTriple value)](#setEndpoints-com.aspose.imaging.fileformats.bmp.structures.CieCoordinatesTriple-) | Obtient ou définit la classe CoordinatesTriple. |
| [getGammaRed()](#getGammaRed--) | Obtient ou définit le gamma rouge. |
| [setGammaRed(int value)](#setGammaRed-int-) | Obtient ou définit le gamma rouge. |
| [getGammaGreen()](#getGammaGreen--) | Obtient ou définit le gamma vert. |
| [setGammaGreen(int value)](#setGammaGreen-int-) | Obtient ou définit le gamma vert. |
| [getGammaBlue()](#getGammaBlue--) | Obtient ou définit le gamma bleu. |
| [setGammaBlue(int value)](#setGammaBlue-int-) | Obtient ou définit le gamma bleu. |
### getRedMask() {#getRedMask--}
```
public int getRedMask()
```


Obtient ou définit le masque de couleur qui spécifie le composant rouge de chaque pixel, valable uniquement si bV4Compression est défini sur BI\_BITFIELDS.

**Returns:**
int
### setRedMask(int value) {#setRedMask-int-}
```
public void setRedMask(int value)
```


Obtient ou définit le masque de couleur qui spécifie le composant rouge de chaque pixel, valable uniquement si bV4Compression est défini sur BI\_BITFIELDS.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getGreenMask() {#getGreenMask--}
```
public int getGreenMask()
```


Obtient ou définit le masque de couleur qui spécifie le composant vert de chaque pixel, valable uniquement si bV4Compression est défini sur BI\_BITFIELDS.

**Returns:**
int
### setGreenMask(int value) {#setGreenMask-int-}
```
public void setGreenMask(int value)
```


Obtient ou définit le masque de couleur qui spécifie le composant vert de chaque pixel, valable uniquement si bV4Compression est défini sur BI\_BITFIELDS.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getBlueMask() {#getBlueMask--}
```
public int getBlueMask()
```


Obtient ou définit le masque de couleur qui spécifie le composant bleu de chaque pixel, valable uniquement si bV4Compression est défini sur BI\_BITFIELDS.

**Returns:**
int
### setBlueMask(int value) {#setBlueMask-int-}
```
public void setBlueMask(int value)
```


Obtient ou définit le masque de couleur qui spécifie le composant bleu de chaque pixel, valable uniquement si bV4Compression est défini sur BI\_BITFIELDS.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getAlphaMask() {#getAlphaMask--}
```
public int getAlphaMask()
```


Obtient ou définit le masque de couleur qui spécifie le composant alpha de chaque pixel.

**Returns:**
int
### setAlphaMask(int value) {#setAlphaMask-int-}
```
public void setAlphaMask(int value)
```


Obtient ou définit le masque de couleur qui spécifie le composant alpha de chaque pixel.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getCSType() {#getCSType--}
```
public int getCSType()
```


Obtient ou définit l'espace colorimétrique du DIB.

**Returns:**
int
### setCSType(int value) {#setCSType-int-}
```
public void setCSType(int value)
```


Obtient ou définit l'espace colorimétrique du DIB.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getEndpoints() {#getEndpoints--}
```
public CieCoordinatesTriple getEndpoints()
```


Obtient ou définit la classe CoordinatesTriple.

**Returns:**
[CieCoordinatesTriple](../../com.aspose.imaging.fileformats.bmp.structures/ciecoordinatestriple) - The endpoints.
### setEndpoints(CieCoordinatesTriple value) {#setEndpoints-com.aspose.imaging.fileformats.bmp.structures.CieCoordinatesTriple-}
```
public void setEndpoints(CieCoordinatesTriple value)
```


Obtient ou définit la classe CoordinatesTriple.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [CieCoordinatesTriple](../../com.aspose.imaging.fileformats.bmp.structures/ciecoordinatestriple) | Les points d'extrémité. |

### getGammaRed() {#getGammaRed--}
```
public int getGammaRed()
```


Obtient ou définit le gamma rouge.

**Returns:**
int - Le gamma rouge.
### setGammaRed(int value) {#setGammaRed-int-}
```
public void setGammaRed(int value)
```


Obtient ou définit le gamma rouge.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | Le gamma rouge. |

### getGammaGreen() {#getGammaGreen--}
```
public int getGammaGreen()
```


Obtient ou définit le gamma vert.

**Returns:**
int - Le gamma vert.
### setGammaGreen(int value) {#setGammaGreen-int-}
```
public void setGammaGreen(int value)
```


Obtient ou définit le gamma vert.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | Le gamma vert. |

### getGammaBlue() {#getGammaBlue--}
```
public int getGammaBlue()
```


Obtient ou définit le gamma bleu.

**Returns:**
int - Le gamma bleu.
### setGammaBlue(int value) {#setGammaBlue-int-}
```
public void setGammaBlue(int value)
```


Obtient ou définit le gamma bleu.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | Le gamma bleu. |

