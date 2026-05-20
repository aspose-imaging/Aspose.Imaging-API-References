---
title: "WmfDibStrechBlt"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'enregistrement META_DIBSTRETCHBLT spécifie le transfert d'un bloc de pixels au format indépendant du dispositif selon une opération raster avec une éventuelle expansion ou contraction."
type: docs
weight: 30
url: /fr/java/com.aspose.imaging.fileformats.wmf.objects/wmfdibstrechblt/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging/fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfObject](../../com.aspose.imaging/fileformats.wmf.objects/wmfobject)
```
public class WmfDibStrechBlt extends WmfObject
```

L'enregistrement META\_DIBSTRETCHBLT spécifie le transfert d'un bloc de pixels au format indépendant du dispositif selon une opération raster, avec une éventuelle expansion ou contraction.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [WmfDibStrechBlt()](#WmfDibStrechBlt--) | WMFs l'enregistrement. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getRasterOperation()](#getRasterOperation--) | Obtient ou définit l'opération raster. |
| [setRasterOperation(int value)](#setRasterOperation-int-) | Obtient ou définit l'opération raster. |
| [getSrcHeight()](#getSrcHeight--) | Obtient ou définit la hauteur de la source. |
| [setSrcHeight(short value)](#setSrcHeight-short-) | Obtient ou définit la hauteur de la source. |
| [getSrcWidth()](#getSrcWidth--) | Obtient ou définit la largeur de la source. |
| [setSrcWidth(short value)](#setSrcWidth-short-) | Obtient ou définit la largeur de la source. |
| [getYSrc()](#getYSrc--) | Obtient ou définit la source y. |
| [setYSrc(short value)](#setYSrc-short-) | Obtient ou définit la source y. |
| [getXSrc()](#getXSrc--) | Obtient ou définit la source x. |
| [setXSrc(short value)](#setXSrc-short-) | Obtient ou définit la source x. |
| [getDestHeight()](#getDestHeight--) | Obtient ou définit la hauteur du dest. |
| [setDestHeight(short value)](#setDestHeight-short-) | Obtient ou définit la hauteur du dest. |
| [getDestWidth()](#getDestWidth--) | Obtient ou définit la largeur du dest. |
| [setDestWidth(short value)](#setDestWidth-short-) | Obtient ou définit la largeur du dest. |
| [getYDest()](#getYDest--) | Obtient ou définit le dest y. |
| [setYDest(short value)](#setYDest-short-) | Obtient ou définit le dest y. |
| [getXDest()](#getXDest--) | Obtient ou définit le dest x. |
| [setXDest(short value)](#setXDest-short-) | Obtient ou définit le dest x. |
| [getSourceBitmap()](#getSourceBitmap--) | Obtient ou définit le bitmap source. |
| [setSourceBitmap(WmfDeviceIndependentBitmap value)](#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | Obtient ou définit le bitmap source. |
### WmfDibStrechBlt() {#WmfDibStrechBlt--}
```
public WmfDibStrechBlt()
```


WMFs l'enregistrement.

### getRasterOperation() {#getRasterOperation--}
```
public int getRasterOperation()
```


Obtient ou définit l'opération raster.

Valeur : La brosse actuelle dans le contexte du dispositif de lecture, et les pixels de destination doivent être combinés pour former la nouvelle image. Ce code DOIT être l'une des valeurs de la Ternary Raster Operation Enumeration (section 2.1.1.31).

**Returns:**
int
### setRasterOperation(int value) {#setRasterOperation-int-}
```
public void setRasterOperation(int value)
```


Obtient ou définit l'opération raster.

Valeur : La brosse actuelle dans le contexte du dispositif de lecture, et les pixels de destination doivent être combinés pour former la nouvelle image. Ce code DOIT être l'une des valeurs de la Ternary Raster Operation Enumeration (section 2.1.1.31).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getSrcHeight() {#getSrcHeight--}
```
public short getSrcHeight()
```


Obtient ou définit la hauteur de la source.

Valeur : La hauteur, en unités logiques, du rectangle source.

**Returns:**
short
### setSrcHeight(short value) {#setSrcHeight-short-}
```
public void setSrcHeight(short value)
```


Obtient ou définit la hauteur de la source.

Valeur : La hauteur, en unités logiques, du rectangle source.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | short |  |

### getSrcWidth() {#getSrcWidth--}
```
public short getSrcWidth()
```


Obtient ou définit la largeur de la source.

Valeur : La largeur, en unités logiques, du rectangle source

**Returns:**
short
### setSrcWidth(short value) {#setSrcWidth-short-}
```
public void setSrcWidth(short value)
```


Obtient ou définit la largeur de la source.

Valeur : La largeur, en unités logiques, du rectangle source

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | short |  |

### getYSrc() {#getYSrc--}
```
public short getYSrc()
```


Obtient ou définit la source y.

Valeur : La coordonnée y, en unités logiques, du coin supérieur gauche du rectangle source.

**Returns:**
short
### setYSrc(short value) {#setYSrc-short-}
```
public void setYSrc(short value)
```


Obtient ou définit la source y.

Valeur : La coordonnée y, en unités logiques, du coin supérieur gauche du rectangle source.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | short |  |

### getXSrc() {#getXSrc--}
```
public short getXSrc()
```


Obtient ou définit la source x.

Valeur : La coordonnée x, en unités logiques, du coin supérieur gauche du rectangle source.

**Returns:**
short
### setXSrc(short value) {#setXSrc-short-}
```
public void setXSrc(short value)
```


Obtient ou définit la source x.

Valeur : La coordonnée x, en unités logiques, du coin supérieur gauche du rectangle source.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | short |  |

### getDestHeight() {#getDestHeight--}
```
public short getDestHeight()
```


Obtient ou définit la hauteur du dest.

Valeur : La hauteur, en unités logiques, du rectangle de destination.

**Returns:**
short
### setDestHeight(short value) {#setDestHeight-short-}
```
public void setDestHeight(short value)
```


Obtient ou définit la hauteur du dest.

Valeur : La hauteur, en unités logiques, du rectangle de destination.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | short |  |

### getDestWidth() {#getDestWidth--}
```
public short getDestWidth()
```


Obtient ou définit la largeur du dest.

Valeur : La largeur, en unités logiques, du rectangle de destination.

**Returns:**
short
### setDestWidth(short value) {#setDestWidth-short-}
```
public void setDestWidth(short value)
```


Obtient ou définit la largeur du dest.

Valeur : La largeur, en unités logiques, du rectangle de destination.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | short |  |

### getYDest() {#getYDest--}
```
public short getYDest()
```


Obtient ou définit le dest y.

Valeur : La coordonnée y, en unités logiques, du coin supérieur gauche du rectangle de destination.

**Returns:**
short
### setYDest(short value) {#setYDest-short-}
```
public void setYDest(short value)
```


Obtient ou définit le dest y.

Valeur : La coordonnée y, en unités logiques, du coin supérieur gauche du rectangle de destination.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | short |  |

### getXDest() {#getXDest--}
```
public short getXDest()
```


Obtient ou définit le dest x.

Valeur : La coordonnée x, en unités logiques, du coin supérieur gauche du rectangle de destination.

**Returns:**
short
### setXDest(short value) {#setXDest-short-}
```
public void setXDest(short value)
```


Obtient ou définit le dest x.

Valeur : La coordonnée x, en unités logiques, du coin supérieur gauche du rectangle de destination.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | short |  |

### getSourceBitmap() {#getSourceBitmap--}
```
public WmfDeviceIndependentBitmap getSourceBitmap()
```


Obtient ou définit le bitmap source.

Valeur : Le bitmap source.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setSourceBitmap(WmfDeviceIndependentBitmap value) {#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setSourceBitmap(WmfDeviceIndependentBitmap value)
```


Obtient ou définit le bitmap source.

Valeur : Le bitmap source.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

