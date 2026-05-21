---
title: "WmfSetDibToDev"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'enregistrement META_SETDIBTODEV définit un bloc de pixels dans le contexte de périphérique de lecture en utilisant des données de couleur indépendantes du dispositif."
type: docs
weight: 75
url: /fr/java/com.aspose.imaging.fileformats.wmf.objects/wmfsetdibtodev/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging/fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfObject](../../com.aspose.imaging/fileformats.wmf.objects/wmfobject)
```
public class WmfSetDibToDev extends WmfObject
```

L'enregistrement META\_SETDIBTODEV définit un bloc de pixels dans le contexte de périphérique de lecture en utilisant des données de couleur indépendantes du dispositif. La source des données de couleur est un DIB.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [WmfSetDibToDev()](#WmfSetDibToDev--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getColorUsage()](#getColorUsage--) | Obtient ou définit l'utilisation de la couleur. |
| [setColorUsage(int value)](#setColorUsage-int-) | Obtient ou définit l'utilisation de la couleur. |
| [getScanCount()](#getScanCount--) | Obtient ou définit le nombre de balayages. |
| [setScanCount(int value)](#setScanCount-int-) | Obtient ou définit le nombre de balayages. |
| [getStartScan()](#getStartScan--) | Obtient ou définit la numérisation de départ. |
| [setStartScan(int value)](#setStartScan-int-) | Obtient ou définit la numérisation de départ. |
| [getDibPos()](#getDibPos--) | Obtient ou définit la position du DIB. |
| [setDibPos(Point value)](#setDibPos-com.aspose.imaging.Point-) | Obtient ou définit la position du DIB. |
| [getHeight()](#getHeight--) | Obtient ou définit la hauteur. |
| [setHeight(int value)](#setHeight-int-) | Obtient ou définit la hauteur. |
| [getWidth()](#getWidth--) | Obtient ou définit la largeur. |
| [setWidth(int value)](#setWidth-int-) | Obtient ou définit la largeur. |
| [getDestPos()](#getDestPos--) | Obtient ou définit la position de destination. |
| [setDestPos(Point value)](#setDestPos-com.aspose.imaging.Point-) | Obtient ou définit la position de destination. |
| [getDib()](#getDib--) | Obtient ou définit le DIB. |
| [setDib(WmfDeviceIndependentBitmap value)](#setDib-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | Obtient ou définit le DIB. |
### WmfSetDibToDev() {#WmfSetDibToDev--}
```
public WmfSetDibToDev()
```


### getColorUsage() {#getColorUsage--}
```
public int getColorUsage()
```


Obtient ou définit l'utilisation de la couleur.

Valeur : Le champ Colors du DIB contient des valeurs RVB explicites ou des index dans une palette. Cela DOIT être l'une des valeurs de l'énumération `com.aspose.imaging.fileFormats.wmf.objects.wmfSetDibToDev.ColorUsage` (section 2.1.1.6).

**Returns:**
int
### setColorUsage(int value) {#setColorUsage-int-}
```
public void setColorUsage(int value)
```


Obtient ou définit l'utilisation de la couleur.

Valeur : Le champ Colors du DIB contient des valeurs RVB explicites ou des index dans une palette. Cela DOIT être l'une des valeurs de l'énumération `com.aspose.imaging.fileFormats.wmf.objects.wmfSetDibToDev.ColorUsage` (section 2.1.1.6).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getScanCount() {#getScanCount--}
```
public int getScanCount()
```


Obtient ou définit le nombre de balayages.

Valeur : Le nombre de lignes de numérisation dans la source.

**Returns:**
int
### setScanCount(int value) {#setScanCount-int-}
```
public void setScanCount(int value)
```


Obtient ou définit le nombre de balayages.

Valeur : Le nombre de lignes de numérisation dans la source.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getStartScan() {#getStartScan--}
```
public int getStartScan()
```


Obtient ou définit la numérisation de départ.

Valeur : La ligne de numérisation de départ dans la source.

**Returns:**
int
### setStartScan(int value) {#setStartScan-int-}
```
public void setStartScan(int value)
```


Obtient ou définit la numérisation de départ.

Valeur : La ligne de numérisation de départ dans la source.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getDibPos() {#getDibPos--}
```
public Point getDibPos()
```


Obtient ou définit la position du DIB.

Valeur : Les coordonnées, en unités logiques, du rectangle source.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setDibPos(Point value) {#setDibPos-com.aspose.imaging.Point-}
```
public void setDibPos(Point value)
```


Obtient ou définit la position du DIB.

Valeur : Les coordonnées, en unités logiques, du rectangle source.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getHeight() {#getHeight--}
```
public int getHeight()
```


Obtient ou définit la hauteur.

Valeur : La hauteur, en unités logiques, des rectangles source et destination.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public void setHeight(int value)
```


Obtient ou définit la hauteur.

Valeur : La hauteur, en unités logiques, des rectangles source et destination.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getWidth() {#getWidth--}
```
public int getWidth()
```


Obtient ou définit la largeur.

Valeur : La largeur, en unités logiques, des rectangles source et destination.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


Obtient ou définit la largeur.

Valeur : La largeur, en unités logiques, des rectangles source et destination.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getDestPos() {#getDestPos--}
```
public Point getDestPos()
```


Obtient ou définit la position de destination.

Valeur : Les coordonnées, en unités logiques, du coin supérieur gauche du rectangle destination.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setDestPos(Point value) {#setDestPos-com.aspose.imaging.Point-}
```
public void setDestPos(Point value)
```


Obtient ou définit la position de destination.

Valeur : Les coordonnées, en unités logiques, du coin supérieur gauche du rectangle destination.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getDib() {#getDib--}
```
public WmfDeviceIndependentBitmap getDib()
```


Obtient ou définit le DIB.

Valeur : La coordonnée y, en unités logiques, du coin supérieur gauche du rectangle de destination.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setDib(WmfDeviceIndependentBitmap value) {#setDib-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setDib(WmfDeviceIndependentBitmap value)
```


Obtient ou définit le DIB.

Valeur : La coordonnée y, en unités logiques, du coin supérieur gauche du rectangle de destination.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

