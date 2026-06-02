---
title: "EmptyImageMask"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Décrit un masque vide non abstrait."
type: docs
weight: 11
url: /fr/java/com.aspose.imaging.magicwand.imagemasks/emptyimagemask/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.magicwand.imagemasks.ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask)
```
public class EmptyImageMask extends ImageMask
```

Décrit un masque vide non abstrait.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmptyImageMask(int width, int height)](#EmptyImageMask-int-int-) | Initialise une nouvelle instance de la classe [EmptyImageMask](../../com.aspose.imaging.magicwand.imagemasks/emptyimagemask) avec la largeur et la hauteur spécifiées. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getSelectionBounds()](#getSelectionBounds--) | Obtient les limites de la partie sélectionnée du masque, en pixels. |
| [get_Item(int x, int y)](#get-Item-int-int-) | Obtient l'opacité du pixel spécifié. |
| [inflate(int size)](#inflate-int-) | Agrandit ce masque du montant spécifié. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | Recadre le masque avec le rectangle spécifié. |
| [deepClone()](#deepClone--) | Crée un nouvel objet qui est une copie de l'instance actuelle. |
### EmptyImageMask(int width, int height) {#EmptyImageMask-int-int-}
```
public EmptyImageMask(int width, int height)
```


Initialise une nouvelle instance de la classe [EmptyImageMask](../../com.aspose.imaging.magicwand.imagemasks/emptyimagemask) avec la largeur et la hauteur spécifiées.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| width | int | Largeur du masque. |
| height | int | Hauteur du masque. |

### getSelectionBounds() {#getSelectionBounds--}
```
public Rectangle getSelectionBounds()
```


Obtient les limites de la partie sélectionnée du masque, en pixels.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - the bounds of the selected part of the mask, in pixels.
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
[ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) - An inflated EmptyImageMask as ImageMask.
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
[ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) - A cropped EmptyImageMask as ImageMask.
### deepClone() {#deepClone--}
```
public Object deepClone()
```


Crée un nouvel objet qui est une copie de l'instance actuelle.

**Returns:**
java.lang.Object - Un nouvel objet qui est une copie de cette instance.
