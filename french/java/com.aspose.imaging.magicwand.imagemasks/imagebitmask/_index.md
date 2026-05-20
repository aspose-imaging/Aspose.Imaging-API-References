---
title: "ImageBitMask"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Décrit un masque d'image binaire."
type: docs
weight: 14
url: /fr/java/com.aspose.imaging.magicwand.imagemasks/imagebitmask/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.magicwand.imagemasks.ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask)
```
public class ImageBitMask extends ImageMask
```

Décrit un masque d'image binaire.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [ImageBitMask(int width, int height)](#ImageBitMask-int-int-) | Initialise une nouvelle instance de la classe [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) avec la largeur et la hauteur spécifiées. |
| [ImageBitMask(RasterImage image)](#ImageBitMask-com.aspose.imaging.RasterImage-) | Initialise une nouvelle instance de la classe [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) avec la taille du [RasterImage](../../com.aspose.imaging/rasterimage) existant spécifié. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getSelectionBounds()](#getSelectionBounds--) | Obtient les limites de la partie sélectionnée du masque, en pixels. |
| [get_Item(int x, int y)](#get-Item-int-int-) | Obtient l'opacité du pixel spécifié. |
| [inflate(int size)](#inflate-int-) | Agrandit ce masque du montant spécifié. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | Recadre le masque avec le rectangle spécifié. |
| [deepClone()](#deepClone--) | Crée un nouvel objet qui est une copie de l'instance actuelle. |
| [setMaskPixel(int x, int y, boolean value)](#setMaskPixel-int-int-boolean-) | Définit l'opacité du pixel spécifié. |
| [op_LogicalNot(ImageBitMask a)](#op-LogicalNot-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-) | Inverse le masque. |
| [op_Addition(ImageBitMask a, ImageBitMask b)](#op-Addition-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-) | Union de deux masques. |
| [op_Subtraction(ImageBitMask a, ImageBitMask b)](#op-Subtraction-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-) | Soustraire le deuxième masque du premier. |
| [op_Multiply(ImageBitMask a, ImageBitMask b)](#op-Multiply-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-) | Intersection de deux masques. |
| [op_ExclusiveOr(ImageBitMask a, ImageBitMask b)](#op-ExclusiveOr-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-) | Disjonction exclusive de deux masques. |
### ImageBitMask(int width, int height) {#ImageBitMask-int-int-}
```
public ImageBitMask(int width, int height)
```


Initialise une nouvelle instance de la classe [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) avec la largeur et la hauteur spécifiées.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| width | int | Largeur du masque. |
| height | int | Hauteur du masque. |

### ImageBitMask(RasterImage image) {#ImageBitMask-com.aspose.imaging.RasterImage-}
```
public ImageBitMask(RasterImage image)
```


Initialise une nouvelle instance de la classe [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) avec la taille de l'[RasterImage](../../com.aspose.imaging/rasterimage) existant spécifié. L'[RasterImage](../../com.aspose.imaging/rasterimage) spécifié sera stocké comme image source.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Image source. |

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
| y | int | La coordonnée y du pixel. Valeur : true si le pixel spécifié est opaque ; sinon, false. |

**Returns:**
boolean
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
[ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) - An inflated [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) as [ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask).
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
[ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) - A cropped [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) as [ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask).
### deepClone() {#deepClone--}
```
public Object deepClone()
```


Crée un nouvel objet qui est une copie de l'instance actuelle.

**Returns:**
java.lang.Object - Un nouvel objet qui est une copie de cette instance.
### setMaskPixel(int x, int y, boolean value) {#setMaskPixel-int-int-boolean-}
```
public final void setMaskPixel(int x, int y, boolean value)
```


Définit l'opacité du pixel spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | int | La coordonnée x du pixel. |
| y | int | La coordonnée y du pixel. |
| valeur | boolean | true si le pixel spécifié est opaque ; sinon, false. |

### op_LogicalNot(ImageBitMask a) {#op-LogicalNot-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-}
```
public static ImageBitMask op_LogicalNot(ImageBitMask a)
```


Inverse le masque.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| a | [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) | Le masque à inverser. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### op_Addition(ImageBitMask a, ImageBitMask b) {#op-Addition-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-}
```
public static ImageBitMask op_Addition(ImageBitMask a, ImageBitMask b)
```


Union de deux masques.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| a | [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) | Le premier masque. |
| b | [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) | Le deuxième masque. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### op_Subtraction(ImageBitMask a, ImageBitMask b) {#op-Subtraction-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-}
```
public static ImageBitMask op_Subtraction(ImageBitMask a, ImageBitMask b)
```


Soustraire le deuxième masque du premier.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| a | [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) | Le premier masque. |
| b | [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) | Le deuxième masque. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### op_Multiply(ImageBitMask a, ImageBitMask b) {#op-Multiply-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-}
```
public static ImageBitMask op_Multiply(ImageBitMask a, ImageBitMask b)
```


Intersection de deux masques.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| a | [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) | Le premier masque. |
| b | [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) | Le deuxième masque. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### op_ExclusiveOr(ImageBitMask a, ImageBitMask b) {#op-ExclusiveOr-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-com.aspose.imaging.magicwand.imagemasks.ImageBitMask-}
```
public static ImageBitMask op_ExclusiveOr(ImageBitMask a, ImageBitMask b)
```


Disjonction exclusive de deux masques.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| a | [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) | Le premier masque. |
| b | [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) | Le deuxième masque. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
