---
title: "WmfDibBitBlt"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'enregistrement META_DIBBITBLT spécifie le transfert d'un bloc de pixels au format indépendant du dispositif selon une opération raster."
type: docs
weight: 28
url: /fr/java/com.aspose.imaging.fileformats.wmf.objects/wmfdibbitblt/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging/fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfObject](../../com.aspose.imaging/fileformats.wmf.objects/wmfobject)
```
public class WmfDibBitBlt extends WmfObject
```

L'enregistrement META\_DIBBITBLT spécifie le transfert d'un bloc de pixels au format indépendant du dispositif selon une opération raster.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [WmfDibBitBlt()](#WmfDibBitBlt--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getRasterOperation()](#getRasterOperation--) | Obtient ou définit l'opération raster. |
| [setRasterOperation(int value)](#setRasterOperation-int-) | Obtient ou définit l'opération raster. |
| [getSrcPos()](#getSrcPos--) | Obtient ou définit la position source. |
| [setSrcPos(Point value)](#setSrcPos-com.aspose.imaging.Point-) | Obtient ou définit la position source. |
| [getHeight()](#getHeight--) | Obtient ou définit la hauteur. |
| [setHeight(short value)](#setHeight-short-) | Obtient ou définit la hauteur. |
| [getWidth()](#getWidth--) | Obtient ou définit la largeur. |
| [setWidth(short value)](#setWidth-short-) | Obtient ou définit la largeur. |
| [getDstPos()](#getDstPos--) | Obtient ou définit la position DST. |
| [setDstPos(Point value)](#setDstPos-com.aspose.imaging.Point-) | Obtient ou définit la position DST. |
| [getReserved()](#getReserved--) | Obtient ou définit le réservé. |
| [setReserved(int value)](#setReserved-int-) | Obtient ou définit le réservé. |
| [getSource()](#getSource--) | Obtient ou définit la source. |
| [setSource(WmfDeviceIndependentBitmap value)](#setSource-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | Obtient ou définit la source. |
### WmfDibBitBlt() {#WmfDibBitBlt--}
```
public WmfDibBitBlt()
```


### getRasterOperation() {#getRasterOperation--}
```
public int getRasterOperation()
```


Obtient ou définit l'opération raster.

Valeur : Les pixels source, la brosse actuelle dans le contexte du dispositif de lecture, et les pixels de destination doivent être combinés pour former la nouvelle image. Ce code DOIT être l'une des valeurs de l'énumération Ternary Raster Operation (section 2.1.1.31).

**Returns:**
int
### setRasterOperation(int value) {#setRasterOperation-int-}
```
public void setRasterOperation(int value)
```


Obtient ou définit l'opération raster.

Valeur : Les pixels source, la brosse actuelle dans le contexte du dispositif de lecture, et les pixels de destination doivent être combinés pour former la nouvelle image. Ce code DOIT être l'une des valeurs de l'énumération Ternary Raster Operation (section 2.1.1.31).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getSrcPos() {#getSrcPos--}
```
public Point getSrcPos()
```


Obtient ou définit la position source.

Valeur : Les coordonnées, en unités logiques, du rectangle source.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setSrcPos(Point value) {#setSrcPos-com.aspose.imaging.Point-}
```
public void setSrcPos(Point value)
```


Obtient ou définit la position source.

Valeur : Les coordonnées, en unités logiques, du rectangle source.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getHeight() {#getHeight--}
```
public short getHeight()
```


Obtient ou définit la hauteur.

Valeur : La hauteur, en unités logiques, des rectangles source et destination.

**Returns:**
short
### setHeight(short value) {#setHeight-short-}
```
public void setHeight(short value)
```


Obtient ou définit la hauteur.

Valeur : La hauteur, en unités logiques, des rectangles source et destination.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | short |  |

### getWidth() {#getWidth--}
```
public short getWidth()
```


Obtient ou définit la largeur.

Valeur : La largeur, en unités logiques, des rectangles source et destination.

**Returns:**
short
### setWidth(short value) {#setWidth-short-}
```
public void setWidth(short value)
```


Obtient ou définit la largeur.

Valeur : La largeur, en unités logiques, des rectangles source et destination.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | short |  |

### getDstPos() {#getDstPos--}
```
public Point getDstPos()
```


Obtient ou définit la position DST.

Valeur : Les coordonnées, en unités logiques, du coin supérieur gauche du rectangle destination.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setDstPos(Point value) {#setDstPos-com.aspose.imaging.Point-}
```
public void setDstPos(Point value)
```


Obtient ou définit la position DST.

Valeur : Les coordonnées, en unités logiques, du coin supérieur gauche du rectangle destination.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getReserved() {#getReserved--}
```
public int getReserved()
```


Obtient ou définit le réservé.

Valeur : le réservé.

**Returns:**
int
### setReserved(int value) {#setReserved-int-}
```
public void setReserved(int value)
```


Obtient ou définit le réservé.

Valeur : le réservé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getSource() {#getSource--}
```
public WmfDeviceIndependentBitmap getSource()
```


Obtient ou définit la source.

Valeur : Un objet DeviceIndependentBitmap de taille variable (section 2.2.2.9) qui définit le contenu de l'image. Cet objet DOIT être spécifié, même si l'opération raster ne nécessite pas de source.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setSource(WmfDeviceIndependentBitmap value) {#setSource-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setSource(WmfDeviceIndependentBitmap value)
```


Obtient ou définit la source.

Valeur : Un objet DeviceIndependentBitmap de taille variable (section 2.2.2.9) qui définit le contenu de l'image. Cet objet DOIT être spécifié, même si l'opération raster ne nécessite pas de source.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

