---
title: "RectangleMask"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Décrit un masque rectangulaire."
type: docs
weight: 17
url: /fr/java/com.aspose.imaging.magicwand.imagemasks/rectanglemask/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.magicwand.imagemasks.ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask)
```
public class RectangleMask extends ImageMask
```

Décrit un masque rectangulaire.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [RectangleMask(int x, int y, int width, int height)](#RectangleMask-int-int-int-int-) | Initialise une nouvelle instance de la classe [RectangleMask](../../com.aspose.imaging.magicwand.imagemasks/rectanglemask) avec le point supérieur gauche spécifié, la largeur et la hauteur. |
| [RectangleMask(Rectangle selectedArea)](#RectangleMask-com.aspose.imaging.Rectangle-) | Initialise une nouvelle instance de la classe [RectangleMask](../../com.aspose.imaging.magicwand.imagemasks/rectanglemask) avec le rectangle spécifié. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getSelectionBounds()](#getSelectionBounds--) | Obtient les limites de la partie sélectionnée du masque, en pixels. |
| [get_Item(int x, int y)](#get-Item-int-int-) | Obtient l'opacité du pixel spécifié. |
| [inflate(int size)](#inflate-int-) | Agrandit ce masque du montant spécifié. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | Recadre le masque avec le rectangle spécifié. |
| [deepClone()](#deepClone--) | Crée un nouvel objet qui est une copie de l'instance actuelle. |

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

### RectangleMask(int x, int y, int width, int height) {#RectangleMask-int-int-int-int-}
```
public RectangleMask(int x, int y, int width, int height)
```


Initialise une nouvelle instance de la classe [RectangleMask](../../com.aspose.imaging.magicwand.imagemasks/rectanglemask) avec le point supérieur gauche spécifié, la largeur et la hauteur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | int | La coordonnée x du point supérieur gauche de la zone sélectionnée. |
| y | int | La coordonnée y du point supérieur gauche de la zone sélectionnée. |
| width | int | Largeur de la zone sélectionnée. |
| height | int | Hauteur de la zone sélectionnée. |

### RectangleMask(Rectangle selectedArea) {#RectangleMask-com.aspose.imaging.Rectangle-}
```
public RectangleMask(Rectangle selectedArea)
```


Initialise une nouvelle instance de la classe [RectangleMask](../../com.aspose.imaging.magicwand.imagemasks/rectanglemask) avec le rectangle spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| selectedArea | [Rectangle](../../com.aspose.imaging/rectangle) | Zone sélectionnée spécifiée sous forme de rectangle. |

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
[ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) - An inflated RectangleMask as ImageMask.
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
[ImageMask](../../com.aspose.imaging.magicwand.imagemasks/imagemask) - A cropped RectangleMask as ImageMask.
### deepClone() {#deepClone--}
```
public Object deepClone()
```


Crée un nouvel objet qui est une copie de l'instance actuelle.

**Returns:**
java.lang.Object - Un nouvel objet qui est une copie de cette instance.
