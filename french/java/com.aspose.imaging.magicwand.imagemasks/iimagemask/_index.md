---
title: "IImageMask"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Décrit un masque."
type: docs
weight: 18
url: /fr/java/com.aspose.imaging.magicwand.imagemasks/iimagemask/
---
**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable
```
public interface IImageMask extends System.ICloneable
```

Décrit un masque.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getSource()](#getSource--) | Obtient l'image source utilisée pour créer ce masque, si elle existe. |
| [getWidth()](#getWidth--) | Obtient la largeur, en pixels, de ce masque. |
| [getHeight()](#getHeight--) | Obtient la hauteur, en pixels, de ce masque. |
| [getBounds()](#getBounds--) | Obtient les limites, en pixels, de ce masque. |
| [getSelectionBounds()](#getSelectionBounds--) | Obtient les limites de la partie sélectionnée du masque, en pixels. |
| [isOpaque(int x, int y)](#isOpaque-int-int-) | Vérifie si le pixel spécifié est opaque. |
| [isTransparent(int x, int y)](#isTransparent-int-int-) | Vérifie si le pixel spécifié est transparent. |
| [getByteOpacity(int x, int y)](#getByteOpacity-int-int-) | Obtient l'opacité du pixel spécifié avec une précision d'octet. |
### getSource() {#getSource--}
```
public abstract RasterImage getSource()
```


Obtient l'image source utilisée pour créer ce masque, si elle existe.

**Returns:**
[RasterImage](../../com.aspose.imaging/rasterimage) - the source image used to create this mask, if exists.
### getWidth() {#getWidth--}
```
public abstract int getWidth()
```


Obtient la largeur, en pixels, de ce masque.

**Returns:**
int - la largeur, en pixels, de ce masque.
### getHeight() {#getHeight--}
```
public abstract int getHeight()
```


Obtient la hauteur, en pixels, de ce masque.

**Returns:**
int - la hauteur, en pixels, de ce masque.
### getBounds() {#getBounds--}
```
public abstract Rectangle getBounds()
```


Obtient les limites, en pixels, de ce masque.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - the bounds, in pixels, of this mask.
### getSelectionBounds() {#getSelectionBounds--}
```
public abstract Rectangle getSelectionBounds()
```


Obtient les limites de la partie sélectionnée du masque, en pixels.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - the bounds of the selected part of the mask, in pixels.
### isOpaque(int x, int y) {#isOpaque-int-int-}
```
public abstract boolean isOpaque(int x, int y)
```


Vérifie si le pixel spécifié est opaque.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | int | La coordonnée x du pixel. |
| y | int | La coordonnée y du pixel. |

**Returns:**
boolean - vrai si le pixel spécifié est opaque ; sinon, faux.
### isTransparent(int x, int y) {#isTransparent-int-int-}
```
public abstract boolean isTransparent(int x, int y)
```


Vérifie si le pixel spécifié est transparent.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | int | La coordonnée x du pixel. |
| y | int | La coordonnée y du pixel. |

**Returns:**
boolean - vrai si le pixel spécifié est transparent ; sinon, faux.
### getByteOpacity(int x, int y) {#getByteOpacity-int-int-}
```
public abstract byte getByteOpacity(int x, int y)
```


Obtient l'opacité du pixel spécifié avec une précision d'octet.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | int | La coordonnée x du pixel. |
| y | int | La coordonnée y du pixel. |

**Returns:**
byte - Valeur d'octet, représentant l'opacité du pixel spécifié.
