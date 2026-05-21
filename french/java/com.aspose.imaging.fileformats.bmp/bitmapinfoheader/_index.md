---
title: "BitmapInfoHeader"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Spécifie BITMAPINFOHEADER."
type: docs
weight: 12
url: /fr/java/com.aspose.imaging.fileformats.bmp/bitmapinfoheader/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.bmp.BitmapCoreHeader](../../com.aspose.imaging.fileformats.bmp/bitmapcoreheader)
```
public class BitmapInfoHeader extends BitmapCoreHeader
```

Spécifie BITMAPINFOHEADER. Prise en charge du système d'exploitation : Windows NT, 3.1x ou version ultérieure. Fonctionnalités : ajoute les formats 16 bpp et 32 bpp. Ajoute la compression RLE.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getBitmapCompression()](#getBitmapCompression--) | Obtient la compression du bitmap. |
| [setBitmapCompression(long value)](#setBitmapCompression-long-) | Définit la compression du bitmap. |
| [getBitmapImageSize()](#getBitmapImageSize--) | Obtient la taille brute des données du bitmap en octets. |
| [setBitmapImageSize(long value)](#setBitmapImageSize-long-) | Définit la taille brute des données du bitmap en octets. |
| [getBitmapXPelsPerMeter()](#getBitmapXPelsPerMeter--) | Obtient la résolution horizontale en pixels. |
| [setBitmapXPelsPerMeter(int value)](#setBitmapXPelsPerMeter-int-) | Obtient ou définit la résolution horizontale en pixels. |
| [getBitmapYPelsPerMeter()](#getBitmapYPelsPerMeter--) | Obtient ou définit la résolution verticale en pixels. |
| [setBitmapYPelsPerMeter(int value)](#setBitmapYPelsPerMeter-int-) | Obtient ou définit la résolution verticale en pixels. |
| [getBitmapColorsUsed()](#getBitmapColorsUsed--) | Obtient le nombre de couleurs de palette utilisées. |
| [setBitmapColorsUsed(long value)](#setBitmapColorsUsed-long-) | Obtient ou définit le nombre de couleurs de palette utilisées. |
| [getBitmapColorsImportant()](#getBitmapColorsImportant--) | Obtient ou définit le nombre de couleurs de palette importantes. |
| [setBitmapColorsImportant(long value)](#setBitmapColorsImportant-long-) | Obtient ou définit le nombre de couleurs de palette importantes. |
| [getExtraBitMasks()](#getExtraBitMasks--) | Obtient ou définit les masques de bits supplémentaires. |
| [setExtraBitMasks(int[] value)](#setExtraBitMasks-int---) | Obtient ou définit les masques de bits supplémentaires. |
### getBitmapCompression() {#getBitmapCompression--}
```
public long getBitmapCompression()
```


Obtient la compression du bitmap.

**Returns:**
long - compression du bitmap.
### setBitmapCompression(long value) {#setBitmapCompression-long-}
```
public void setBitmapCompression(long value)
```


Définit la compression du bitmap.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | long | compression du bitmap. |

### getBitmapImageSize() {#getBitmapImageSize--}
```
public long getBitmapImageSize()
```


Obtient la taille brute des données du bitmap en octets.

**Returns:**
long - taille brute des données du bitmap en octets.
### setBitmapImageSize(long value) {#setBitmapImageSize-long-}
```
public void setBitmapImageSize(long value)
```


Définit la taille brute des données du bitmap en octets.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | long | taille brute des données du bitmap en octets. |

### getBitmapXPelsPerMeter() {#getBitmapXPelsPerMeter--}
```
public int getBitmapXPelsPerMeter()
```


Obtient la résolution horizontale en pixels.

**Returns:**
int - résolution horizontale en pixels.
### setBitmapXPelsPerMeter(int value) {#setBitmapXPelsPerMeter-int-}
```
public void setBitmapXPelsPerMeter(int value)
```


Obtient ou définit la résolution horizontale en pixels.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | résolution horizontale en pixels. |

### getBitmapYPelsPerMeter() {#getBitmapYPelsPerMeter--}
```
public int getBitmapYPelsPerMeter()
```


Obtient ou définit la résolution verticale en pixels.

**Returns:**
int - résolution verticale en pixels.
### setBitmapYPelsPerMeter(int value) {#setBitmapYPelsPerMeter-int-}
```
public void setBitmapYPelsPerMeter(int value)
```


Obtient ou définit la résolution verticale en pixels.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | résolution verticale en pixels. |

### getBitmapColorsUsed() {#getBitmapColorsUsed--}
```
public long getBitmapColorsUsed()
```


Obtient le nombre de couleurs de palette utilisées.

**Returns:**
long - nombre de couleurs de palette utilisées.
### setBitmapColorsUsed(long value) {#setBitmapColorsUsed-long-}
```
public void setBitmapColorsUsed(long value)
```


Obtient ou définit le nombre de couleurs de palette utilisées.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | long | nombre de couleurs de palette utilisées. |

### getBitmapColorsImportant() {#getBitmapColorsImportant--}
```
public long getBitmapColorsImportant()
```


Obtient ou définit le nombre de couleurs de palette importantes.

**Returns:**
long - nombre de couleurs de palette importantes.
### setBitmapColorsImportant(long value) {#setBitmapColorsImportant-long-}
```
public void setBitmapColorsImportant(long value)
```


Obtient ou définit le nombre de couleurs de palette importantes.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | long | nombre de couleurs importantes de la palette. |

### getExtraBitMasks() {#getExtraBitMasks--}
```
public int[] getExtraBitMasks()
```


Obtient ou définit les masques de bits supplémentaires. Présent uniquement dans le cas où l'en-tête DIB est le BITMAPINFOHEADER et que le `BitmapCompression` est défini sur `BitmapCompression.Bitfields` (RGB) ou `BitmapCompression.AlphaBitfields` (RGBA).

**Returns:**
int[] - les masques de bits supplémentaires.
### setExtraBitMasks(int[] value) {#setExtraBitMasks-int---}
```
public void setExtraBitMasks(int[] value)
```


Obtient ou définit les masques de bits supplémentaires. Présent uniquement dans le cas où l'en-tête DIB est le BITMAPINFOHEADER et que le `BitmapCompression` est défini sur `BitmapCompression.Bitfields` (RGB) ou `BitmapCompression.AlphaBitfields` (RGBA).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int[] | les masques de bits supplémentaires. |

