---
title: "ImageGrayscaleMask"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Décrit un masque d'image en niveaux de gris."
type: docs
weight: 15
url: /fr/java/com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.magicwand.imagemasks.IImageMask](../../com.aspose.imaging.magicwand.imagemasks/iimagemask)
```
public class ImageGrayscaleMask implements IImageMask
```

Décrit un masque d'image en niveaux de gris.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [ImageGrayscaleMask(int width, int height)](#ImageGrayscaleMask-int-int-) | Initialise une nouvelle instance de la classe [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) avec la largeur et la hauteur spécifiées. |
| [ImageGrayscaleMask(RasterImage image)](#ImageGrayscaleMask-com.aspose.imaging.RasterImage-) | Initialise une nouvelle instance de la classe [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) avec la taille du [RasterImage](../../com.aspose.imaging/rasterimage) existant spécifié. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getSource()](#getSource--) | Obtient l'image source utilisée pour créer ce masque, si elle existe. |
| [getWidth()](#getWidth--) | Obtient la largeur, en pixels, de ce masque. |
| [getHeight()](#getHeight--) | Obtient la hauteur, en pixels, de ce masque. |
| [getBounds()](#getBounds--) | Obtient les limites, en pixels, de ce masque. |
| [getSelectionBounds()](#getSelectionBounds--) | Obtient les limites de la partie sélectionnée du masque, en pixels. |
| [get_Item(int x, int y)](#get-Item-int-int-) | Obtient l'opacité du pixel spécifié. |
| [set_Item(int x, int y, byte value)](#set-Item-int-int-byte-) | Définit l'opacité du pixel spécifié. |
| [isOpaque(int x, int y)](#isOpaque-int-int-) | Vérifie si le pixel spécifié est opaque. |
| [isTransparent(int x, int y)](#isTransparent-int-int-) | Vérifie si le pixel spécifié est transparent. |
| [getByteOpacity(int x, int y)](#getByteOpacity-int-int-) | Obtient l'opacité du pixel spécifié avec une précision d'octet. |
| [deepClone()](#deepClone--) | Crée un nouvel objet qui est une copie de l'instance actuelle. |
| [apply()](#apply--) | Applique le masque actuel à la source [RasterImage](../../com.aspose.imaging/rasterimage), si elle existe. |
| [applyTo(RasterImage image)](#applyTo-com.aspose.imaging.RasterImage-) | Applique le masque actuel au [RasterImage](../../com.aspose.imaging/rasterimage) spécifié. |
| [crop(Size size)](#crop-com.aspose.imaging.Size-) | Recadre le masque avec la taille spécifiée. |
| [crop(int width, int height)](#crop-int-int-) | Recadre le masque avec la largeur et la hauteur spécifiées. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | Recadre le masque avec le rectangle spécifié. |
| [invert()](#invert--) | Obtient l'inversion du masque actuel. |
| [union(ImageGrayscaleMask mask)](#union-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-) | Union de deux masques. |
| [subtract(ImageGrayscaleMask mask)](#subtract-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-) | Obtient la soustraction du masque fourni du masque actuel. |
| [intersect(ImageGrayscaleMask mask)](#intersect-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-) | Obtient l'intersection du masque actuel avec celui fourni. |
| [exclusiveDisjunction(ImageGrayscaleMask mask)](#exclusiveDisjunction-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-) | Obtient la disjonction exclusive du masque actuel avec le fourni. |
| [op_LogicalNot(ImageGrayscaleMask a)](#op-LogicalNot-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-) | Inverse le masque. |
| [op_Addition(ImageGrayscaleMask a, ImageGrayscaleMask b)](#op-Addition-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-) | Union de deux masques. |
| [op_Subtraction(ImageGrayscaleMask a, ImageGrayscaleMask b)](#op-Subtraction-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-) | Soustraire le deuxième masque du premier. |
| [op_Multiply(ImageGrayscaleMask a, ImageGrayscaleMask b)](#op-Multiply-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-) | Intersection de deux masques. |
| [op_ExclusiveOr(ImageGrayscaleMask a, ImageGrayscaleMask b)](#op-ExclusiveOr-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-) | Disjonction exclusive de deux masques. |

## Example: The example shows how to select a complicated area of an image using Magic Wand tool and the ability to interact with masks (invert, union, subtract).

``` java
String imageFilePath = "input.png";
String outputFilePath = "masked-complex.png";
try (RasterImage image = (RasterImage)Image.load(imageFilePath))
{
    // Créez un nouveau masque en utilisant le magic wand tool basé sur la tonalité et la couleur du pixel (845, 128).
    MagicWandTool.select(image, new MagicWandSettings(845, 128))
            // Fusionnez le masque existant avec celui spécifié créé par le magic wand tool.
            .union(new MagicWandSettings(416, 387))
            // Inversez le masque existant.
            .invert()
            // Soustrayez le masque spécifié créé par le magic wand tool avec le seuil spécifié du masque existant.
            .subtract(new MagicWandSettings(1482, 346) {{ setThreshold(69); }})
            // Soustrayez quatre masques rectangulaires spécifiés du masque existant un par un.
            .subtract(new RectangleMask(0, 0, 800, 150))
            .subtract(new RectangleMask(0, 380, 600, 220))
            .subtract(new RectangleMask(930, 520, 110, 40))
            .subtract(new RectangleMask(1370, 400, 120, 200))
            // Adoucissez le masque avec les paramètres spécifiés.
            .getFeathered(new FeatheringSettings() {{ setSize(3); }})
            // Appliquez le masque à l'image.
            .apply();

    // Enregistrez l'image.
    image.save(outputFilePath);
}

```

### ImageGrayscaleMask(int width, int height) {#ImageGrayscaleMask-int-int-}
```
public ImageGrayscaleMask(int width, int height)
```


Initialise une nouvelle instance de la classe [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) avec la largeur et la hauteur spécifiées.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| width | int | Largeur du masque. |
| height | int | Hauteur du masque. |

### ImageGrayscaleMask(RasterImage image) {#ImageGrayscaleMask-com.aspose.imaging.RasterImage-}
```
public ImageGrayscaleMask(RasterImage image)
```


Initialise une nouvelle instance de la classe [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) avec la taille du [RasterImage](../../com.aspose.imaging/rasterimage) existant spécifié. Le [RasterImage](../../com.aspose.imaging/rasterimage) spécifié sera stocké comme image source.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Image source. |

### getSource() {#getSource--}
```
public final RasterImage getSource()
```


Obtient l'image source utilisée pour créer ce masque, si elle existe.

**Returns:**
[RasterImage](../../com.aspose.imaging/rasterimage) - the source image used to create this mask, if exists.
### getWidth() {#getWidth--}
```
public final int getWidth()
```


Obtient la largeur, en pixels, de ce masque.

**Returns:**
int - la largeur, en pixels, de ce masque.
### getHeight() {#getHeight--}
```
public final int getHeight()
```


Obtient la hauteur, en pixels, de ce masque.

**Returns:**
int - la hauteur, en pixels, de ce masque.
### getBounds() {#getBounds--}
```
public final Rectangle getBounds()
```


Obtient les limites, en pixels, de ce masque.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - the bounds, in pixels, of this mask.
### getSelectionBounds() {#getSelectionBounds--}
```
public final Rectangle getSelectionBounds()
```


Obtient les limites de la partie sélectionnée du masque, en pixels.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - the bounds of the selected part of the mask, in pixels.
### get_Item(int x, int y) {#get-Item-int-int-}
```
public final byte get_Item(int x, int y)
```


Obtient l'opacité du pixel spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | int | La coordonnée x du pixel. |
| y | int | La coordonnée y du pixel. Valeur : valeur d'octet ; 0 si transparent ; 255 si opaque. |

**Returns:**
byte
### set_Item(int x, int y, byte value) {#set-Item-int-int-byte-}
```
public final void set_Item(int x, int y, byte value)
```


Définit l'opacité du pixel spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | int | La coordonnée x du pixel. |
| y | int | La coordonnée y du pixel. Valeur : valeur d'octet ; 0 si transparent ; 255 si opaque. |
| valeur | byte | l'opacité du pixel spécifié. |

### isOpaque(int x, int y) {#isOpaque-int-int-}
```
public final boolean isOpaque(int x, int y)
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
public final boolean isTransparent(int x, int y)
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
public final byte getByteOpacity(int x, int y)
```


Obtient l'opacité du pixel spécifié avec une précision d'octet.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | int | La coordonnée x du pixel. |
| y | int | La coordonnée y du pixel. |

**Returns:**
byte - Valeur d'octet, représentant l'opacité du pixel spécifié.
### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Crée un nouvel objet qui est une copie de l'instance actuelle.

**Returns:**
java.lang.Object - Un nouvel objet qui est une copie de cette instance.
### apply() {#apply--}
```
public final void apply()
```


Applique le masque actuel à la source [RasterImage](../../com.aspose.imaging/rasterimage), si elle existe.

### applyTo(RasterImage image) {#applyTo-com.aspose.imaging.RasterImage-}
```
public final void applyTo(RasterImage image)
```


Applique le masque actuel au [RasterImage](../../com.aspose.imaging/rasterimage) spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Image à laquelle appliquer le masque. |

### crop(Size size) {#crop-com.aspose.imaging.Size-}
```
public final ImageGrayscaleMask crop(Size size)
```


Recadre le masque avec la taille spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| size | [Size](../../com.aspose.imaging/size) | La taille spécifiée. |

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - A cropped [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask).
### crop(int width, int height) {#crop-int-int-}
```
public final ImageGrayscaleMask crop(int width, int height)
```


Recadre le masque avec la largeur et la hauteur spécifiées.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| width | int | La largeur spécifiée. |
| height | int | La hauteur spécifiée. |

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - A cropped [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask).
### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public final ImageGrayscaleMask crop(Rectangle rectangle)
```


Recadre le masque avec le rectangle spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Le rectangle spécifié. |

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - A cropped [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask).
### invert() {#invert--}
```
public final ImageGrayscaleMask invert()
```


Obtient l'inversion du masque actuel.

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - New [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask).
### union(ImageGrayscaleMask mask) {#union-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-}
```
public final ImageGrayscaleMask union(ImageGrayscaleMask mask)
```


Union de deux masques.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| mask | [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) | Masque fourni |

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - New [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask).
### subtract(ImageGrayscaleMask mask) {#subtract-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-}
```
public final ImageGrayscaleMask subtract(ImageGrayscaleMask mask)
```


Obtient la soustraction du masque fourni du masque actuel.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| mask | [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) | Masque fourni |

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - New [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask).
### intersect(ImageGrayscaleMask mask) {#intersect-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-}
```
public final ImageGrayscaleMask intersect(ImageGrayscaleMask mask)
```


Obtient l'intersection du masque actuel avec celui fourni.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| mask | [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) | Masque fourni |

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - New [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask).
### exclusiveDisjunction(ImageGrayscaleMask mask) {#exclusiveDisjunction-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-}
```
public final ImageGrayscaleMask exclusiveDisjunction(ImageGrayscaleMask mask)
```


Obtient la disjonction exclusive du masque actuel avec le fourni.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| mask | [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) | Masque fourni |

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - New [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask).
### op_LogicalNot(ImageGrayscaleMask a) {#op-LogicalNot-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-}
```
public static ImageGrayscaleMask op_LogicalNot(ImageGrayscaleMask a)
```


Inverse le masque.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| a | [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) | Le masque à inverser. |

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - New [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask).
### op_Addition(ImageGrayscaleMask a, ImageGrayscaleMask b) {#op-Addition-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-}
```
public static ImageGrayscaleMask op_Addition(ImageGrayscaleMask a, ImageGrayscaleMask b)
```


Union de deux masques.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| a | [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) | Le premier masque. |
| b | [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) | Le deuxième masque. |

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - New [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask).
### op_Subtraction(ImageGrayscaleMask a, ImageGrayscaleMask b) {#op-Subtraction-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-}
```
public static ImageGrayscaleMask op_Subtraction(ImageGrayscaleMask a, ImageGrayscaleMask b)
```


Soustraire le deuxième masque du premier.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| a | [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) | Le premier masque. |
| b | [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) | Le deuxième masque. |

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - New [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask).
### op_Multiply(ImageGrayscaleMask a, ImageGrayscaleMask b) {#op-Multiply-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-}
```
public static ImageGrayscaleMask op_Multiply(ImageGrayscaleMask a, ImageGrayscaleMask b)
```


Intersection de deux masques.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| a | [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) | Le premier masque. |
| b | [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) | Le deuxième masque. |

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - New [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask).
### op_ExclusiveOr(ImageGrayscaleMask a, ImageGrayscaleMask b) {#op-ExclusiveOr-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-com.aspose.imaging.magicwand.imagemasks.ImageGrayscaleMask-}
```
public static ImageGrayscaleMask op_ExclusiveOr(ImageGrayscaleMask a, ImageGrayscaleMask b)
```


Disjonction exclusive de deux masques.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| a | [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) | Le premier masque. |
| b | [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) | Le deuxième masque. |

**Returns:**
[ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask) - New [ImageGrayscaleMask](../../com.aspose.imaging.magicwand.imagemasks/imagegrayscalemask).
