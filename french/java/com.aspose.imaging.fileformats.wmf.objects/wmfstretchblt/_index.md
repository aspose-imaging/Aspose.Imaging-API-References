---
title: "WmfStretchBlt"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'enregistrement META_STRETCHBLT spécifie le transfert d'un bloc de pixels selon une opération raster avec une éventuelle expansion ou contraction."
type: docs
weight: 93
url: /fr/java/com.aspose.imaging.fileformats.wmf.objects/wmfstretchblt/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging/fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfObject](../../com.aspose.imaging/fileformats.wmf.objects/wmfobject)
```
public class WmfStretchBlt extends WmfObject
```

L'enregistrement META\_STRETCHBLT spécifie le transfert d'un bloc de pixels selon une opération raster, avec une éventuelle expansion ou contraction.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [WmfStretchBlt()](#WmfStretchBlt--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getRasterOperation()](#getRasterOperation--) | Obtient ou définit l'opération raster. |
| [setRasterOperation(int value)](#setRasterOperation-int-) | Obtient ou définit l'opération raster. |
| [getSrcHeight()](#getSrcHeight--) | Obtient ou définit la hauteur de la source. |
| [setSrcHeight(short value)](#setSrcHeight-short-) | Obtient ou définit la hauteur de la source. |
| [getSrcWidth()](#getSrcWidth--) | Obtient ou définit la largeur de la source. |
| [setSrcWidth(short value)](#setSrcWidth-short-) | Obtient ou définit la largeur de la source. |
| [getSrcPosition()](#getSrcPosition--) | Obtient ou définit la position source. |
| [setSrcPosition(Point value)](#setSrcPosition-com.aspose.imaging.Point-) | Obtient ou définit la position source. |
| [getDestHeight()](#getDestHeight--) | Obtient ou définit la hauteur du dest. |
| [setDestHeight(short value)](#setDestHeight-short-) | Obtient ou définit la hauteur du dest. |
| [getDestWidth()](#getDestWidth--) | Obtient ou définit la largeur du dest. |
| [setDestWidth(short value)](#setDestWidth-short-) | Obtient ou définit la largeur du dest. |
| [getDstPosition()](#getDstPosition--) | Obtient ou définit la position DST. |
| [setDstPosition(Point value)](#setDstPosition-com.aspose.imaging.Point-) | Obtient ou définit la position DST. |
| [getReserved()](#getReserved--) | Obtient ou définit le réservé. |
| [setReserved(short value)](#setReserved-short-) | Obtient ou définit le réservé. |
| [getBitmap()](#getBitmap--) | Obtient ou définit le bitmap. |
| [setBitmap(WmfBitmap16 value)](#setBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfBitmap16-) | Obtient ou définit le bitmap. |
### WmfStretchBlt() {#WmfStretchBlt--}
```
public WmfStretchBlt()
```


### getRasterOperation() {#getRasterOperation--}
```
public int getRasterOperation()
```


Obtient ou définit l'opération raster.

Valeur : les pixels source, le pinceau actuel dans le contexte de périphérique de lecture, et les pixels de destination doivent être combinés pour former la nouvelle image. Ce code DOIT être l'une des valeurs de l'énumération Ternary Raster Operation.

**Returns:**
int
### setRasterOperation(int value) {#setRasterOperation-int-}
```
public void setRasterOperation(int value)
```


Obtient ou définit l'opération raster.

Valeur : les pixels source, le pinceau actuel dans le contexte de périphérique de lecture, et les pixels de destination doivent être combinés pour former la nouvelle image. Ce code DOIT être l'une des valeurs de l'énumération Ternary Raster Operation.

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

Valeur : la largeur, en unités logiques, du rectangle source.

**Returns:**
short
### setSrcWidth(short value) {#setSrcWidth-short-}
```
public void setSrcWidth(short value)
```


Obtient ou définit la largeur de la source.

Valeur : la largeur, en unités logiques, du rectangle source.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | short |  |

### getSrcPosition() {#getSrcPosition--}
```
public Point getSrcPosition()
```


Obtient ou définit la position source.

Valeur : la position source.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setSrcPosition(Point value) {#setSrcPosition-com.aspose.imaging.Point-}
```
public void setSrcPosition(Point value)
```


Obtient ou définit la position source.

Valeur : la position source.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

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

### getDstPosition() {#getDstPosition--}
```
public Point getDstPosition()
```


Obtient ou définit la position DST.

Valeur : la position DST.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setDstPosition(Point value) {#setDstPosition-com.aspose.imaging.Point-}
```
public void setDstPosition(Point value)
```


Obtient ou définit la position DST.

Valeur : la position DST.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getReserved() {#getReserved--}
```
public short getReserved()
```


Obtient ou définit le réservé.

Valeur : le réservé. Ce champ DOIT être ignoré.

**Returns:**
short
### setReserved(short value) {#setReserved-short-}
```
public void setReserved(short value)
```


Obtient ou définit le réservé.

Valeur : le réservé. Ce champ DOIT être ignoré.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | short |  |

### getBitmap() {#getBitmap--}
```
public WmfBitmap16 getBitmap()
```


Obtient ou définit le bitmap.

Valeur : le bitmap.

**Returns:**
[WmfBitmap16](../../com.aspose.imaging.fileformats.wmf.objects/wmfbitmap16)
### setBitmap(WmfBitmap16 value) {#setBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfBitmap16-}
```
public void setBitmap(WmfBitmap16 value)
```


Obtient ou définit le bitmap.

Valeur : le bitmap.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [WmfBitmap16](../../com.aspose.imaging.fileformats.wmf.objects/wmfbitmap16) |  |

