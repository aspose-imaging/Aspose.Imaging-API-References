---
title: "CircleMask"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Décrit un masque circulaire."
type: docs
weight: 10
url: /fr/java/com.aspose.imaging.magicwand.imagemasks/circlemask/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.magicwand.imagemasks.ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask)
```
public class CircleMask extends ImageMask
```

Décrit un masque circulaire.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [CircleMask(int x, int y, int radius)](#CircleMask-int-int-int-) | Initialise une nouvelle instance de la classe [CircleMask](../../com.aspose.imaging.magicwand.imagemasks/circlemask) avec le point central et le rayon spécifiés. |
| [CircleMask(Point center, int radius)](#CircleMask-com.aspose.imaging.Point-int-) | Initialise une nouvelle instance de la classe [CircleMask](../../com.aspose.imaging.magicwand.imagemasks/circlemask) avec le point central et le rayon spécifiés. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getSelectionBounds()](#getSelectionBounds--) | Obtient les limites, en pixels, de ce masque. |
| [get_Item(int x, int y)](#get-Item-int-int-) | Obtient l'opacité du pixel spécifié. |
| [inflate(int size)](#inflate-int-) | Agrandit ce masque du montant spécifié. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | Recadre le masque avec le rectangle spécifié. |
| [deepClone()](#deepClone--) | Crée un nouvel objet qui est une copie de l'instance actuelle. |
### CircleMask(int x, int y, int radius) {#CircleMask-int-int-int-}
```
public CircleMask(int x, int y, int radius)
```


Initialise une nouvelle instance de la classe [CircleMask](../../com.aspose.imaging.magicwand.imagemasks/circlemask) avec le point central et le rayon spécifiés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | int | La coordonnée x du point central de la zone sélectionnée. |
| y | int | La coordonnée y du point central de la zone sélectionnée. |
| rayon | int | Rayon de la zone sélectionnée. |

### CircleMask(Point center, int radius) {#CircleMask-com.aspose.imaging.Point-int-}
```
public CircleMask(Point center, int radius)
```


Initialise une nouvelle instance de la classe [CircleMask](../../com.aspose.imaging.magicwand.imagemasks/circlemask) avec le point central et le rayon spécifiés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| center | [Point](../../com.aspose.imaging/point) | Le point central de la zone sélectionnée. |
| rayon | int | Rayon de la zone sélectionnée. |

### getSelectionBounds() {#getSelectionBounds--}
```
public Rectangle getSelectionBounds()
```


Obtient les limites, en pixels, de ce masque.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - the bounds, in pixels, of this mask.
### get_Item(int x, int y) {#get-Item-int-int-}
```
public boolean get_Item(int x, int y)
```


Obtient l'opacité du pixel spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | int | La coordonnée x du pixel. |
| y | int | La coordonnée y du pixel. |

**Returns:**
boolean - vrai si le pixel spécifié est opaque ; sinon, faux.
### inflate(int size) {#inflate-int-}
```
public ImageMask inflate(int size)
```


Agrandit ce masque du montant spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| taille | int | La quantité à gonfler ce masque. |

**Returns:**
[ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) - An inflated CircleMask as ImageMask.
### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public ImageMask crop(Rectangle rectangle)
```


Recadre le masque avec le rectangle spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Le rectangle spécifié. |

**Returns:**
[ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) - A cropped CircleMask or ImageBitMask as ImageMask. As ImageBitMask may be returned, fluent call is recommended.
### deepClone() {#deepClone--}
```
public Object deepClone()
```


Crée un nouvel objet qui est une copie de l'instance actuelle.

**Returns:**
java.lang.Object - Un nouvel objet qui est une copie de cette instance.
