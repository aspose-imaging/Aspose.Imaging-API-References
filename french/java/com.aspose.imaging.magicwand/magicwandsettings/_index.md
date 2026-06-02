---
title: "MagicWandSettings"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Une classe de paramètres de sélection magic wand."
type: docs
weight: 13
url: /fr/java/com.aspose.imaging.magicwand/magicwandsettings/
---
**Inheritance:**
java.lang.Object
```
public class MagicWandSettings
```

Une classe de paramètres de sélection magic wand.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [MagicWandSettings(Point point)](#MagicWandSettings-com.aspose.imaging.Point-) | Initialise une nouvelle instance de la classe [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings). |
| [MagicWandSettings(int x, int y)](#MagicWandSettings-int-int-) | Initialise une nouvelle instance de la classe [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings). |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getAreaOfInterest()](#getAreaOfInterest--) | Obtient les limites de la zone pour le travail de l'algorithme. |
| [setAreaOfInterest(Rectangle value)](#setAreaOfInterest-com.aspose.imaging.Rectangle-) | Définit les limites de la zone pour le travail de l'algorithme. |
| [getPoint()](#getPoint--) | Obtient le point de référence pour le travail de l'algorithme. |
| [getThreshold()](#getThreshold--) | Obtient le niveau de tolérance pour la comparaison de couleur des pixels. |
| [setThreshold(int value)](#setThreshold-int-) | Définit le niveau de tolérance pour la comparaison de couleur des pixels. |
| [getContiguousMode()](#getContiguousMode--) | Obtient une valeur indiquant si la baguette magique définira uniquement les pixels contigus. |
| [setContiguousMode(boolean value)](#setContiguousMode-boolean-) | Définit une valeur indiquant si la baguette magique ne définira que des pixels contigus. |
| [getDirectionalMode()](#getDirectionalMode--) | Obtient le mode de l'algorithme de recherche de remplissage par diffusion : recherche à quatre ou huit directions. |
| [setDirectionalMode(int value)](#setDirectionalMode-int-) | Définit le mode de l'algorithme de recherche de remplissage par diffusion : recherche à quatre ou huit directions. |
| [getColorCompareMode()](#getColorCompareMode--) | Obtient l'algorithme de comparaison des couleurs. |
| [setColorCompareMode(int value)](#setColorCompareMode-int-) | Définit l'algorithme de comparaison des couleurs. |
| [getColorComparisonDelegate()](#getColorComparisonDelegate--) | Obtient l'algorithme de comparaison de couleur personnalisé si `ColorCompareMode`(\#getColorCompareMode.getColorCompareMode/\#setColorCompareMode(int).setColorCompareMode(int)) est défini sur [ColorComparisonMode.Custom](../../com.aspose.imaging.magicwand/colorcomparisonmode\#Custom). |
| [setColorComparisonDelegate(MagicWandSettings.ColorComparison value)](#setColorComparisonDelegate-com.aspose.imaging.magicwand.MagicWandSettings.ColorComparison-) | Définit l'algorithme de comparaison de couleur personnalisé si `ColorCompareMode`(\#getColorCompareMode.getColorCompareMode/\#setColorCompareMode(int).setColorCompareMode(int)) est défini sur [ColorComparisonMode.Custom](../../com.aspose.imaging.magicwand/colorcomparisonmode\#Custom). |

## Example: The example shows how to select a simple area of an image based on tone and color of any pixel using Magic Wand tool.

``` java
String imageFilePath = "input.png";
String outputFilePath = "masked.png";
try (RasterImage image = (RasterImage)Image.load(imageFilePath))
{
    // Créez un nouveau masque en utilisant le magic wand tool basé sur la tonalité et la couleur du pixel (120, 100) avec un seuil personnalisé égal à 150.
    MagicWandTool
            .select(image, new MagicWandSettings(120, 100) {{ setThreshold(150); }})
            // Appliquez le masque à l'image.
            .apply();

    // Enregistrez l'image avec l'option de type de couleur de transparence forcée.
    image.save(outputFilePath, new PngOptions()
    {{
        setColorType(PngColorType.TruecolorWithAlpha);
    }});
}

```


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

### MagicWandSettings(Point point) {#MagicWandSettings-com.aspose.imaging.Point-}
```
public MagicWandSettings(Point point)
```


Initialise une nouvelle instance de la classe [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | Le point de référence. |

### MagicWandSettings(int x, int y) {#MagicWandSettings-int-int-}
```
public MagicWandSettings(int x, int y)
```


Initialise une nouvelle instance de la classe [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | int | La coordonnée x du point de référence. |
| y | int | La coordonnée y du point de référence. |

### getAreaOfInterest() {#getAreaOfInterest--}
```
public final Rectangle getAreaOfInterest()
```


Obtient les limites de la zone pour le travail de l'algorithme.

Valeur : Le rectangle représentant les limites de la zone d'intérêt.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - the bounds of the area for algorithm work.
### setAreaOfInterest(Rectangle value) {#setAreaOfInterest-com.aspose.imaging.Rectangle-}
```
public final void setAreaOfInterest(Rectangle value)
```


Définit les limites de la zone pour le travail de l'algorithme.

Valeur : Le rectangle représentant les limites de la zone d'intérêt.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) | les limites de la zone pour le fonctionnement de l'algorithme. |

### getPoint() {#getPoint--}
```
public final Point getPoint()
```


Obtient le point de référence pour le travail de l'algorithme.

Valeur : La valeur `Point`.

**Returns:**
[Point](../../com.aspose.imaging/point) - the reference point for algorithm work.
### getThreshold() {#getThreshold--}
```
public final int getThreshold()
```


Obtient le niveau de tolérance pour la comparaison de couleur des pixels.

Valeur : Le seuil de comparaison des couleurs.

**Returns:**
int - le niveau de tolérance pour la comparaison des couleurs des pixels.
### setThreshold(int value) {#setThreshold-int-}
```
public final void setThreshold(int value)
```


Définit le niveau de tolérance pour la comparaison de couleur des pixels.

Valeur : Le seuil de comparaison des couleurs.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | le niveau de tolérance pour la comparaison des couleurs des pixels. |

### getContiguousMode() {#getContiguousMode--}
```
public final boolean getContiguousMode()
```


Obtient une valeur indiquant si la baguette magique définira uniquement les pixels contigus.

Valeur : `true` si l'élément est activé ; sinon, `false`. La valeur par défaut est `true`.

**Returns:**
boolean - une valeur indiquant si la baguette magique ne définira que des pixels contigus.
### setContiguousMode(boolean value) {#setContiguousMode-boolean-}
```
public final void setContiguousMode(boolean value)
```


Définit une valeur indiquant si la baguette magique ne définira que des pixels contigus.

Valeur : `true` si l'élément est activé ; sinon, `false`. La valeur par défaut est `true`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean | une valeur indiquant si la baguette magique ne définira que des pixels contigus. |

### getDirectionalMode() {#getDirectionalMode--}
```
public final int getDirectionalMode()
```


Obtient le mode de l'algorithme de recherche de remplissage par diffusion : recherche à quatre ou huit directions.

Valeur : Le mode de l'algorithme de recherche de remplissage par diffusion.

**Returns:**
int - le mode de l'algorithme de recherche de remplissage par diffusion : recherche à quatre ou huit directions.
### setDirectionalMode(int value) {#setDirectionalMode-int-}
```
public final void setDirectionalMode(int value)
```


Définit le mode de l'algorithme de recherche de remplissage par diffusion : recherche à quatre ou huit directions.

Valeur : Le mode de l'algorithme de recherche de remplissage par diffusion.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | le mode de l'algorithme de recherche de remplissage par diffusion : recherche à quatre ou huit directions. |

### getColorCompareMode() {#getColorCompareMode--}
```
public final int getColorCompareMode()
```


Obtient l'algorithme de comparaison des couleurs.

Valeur : Le mode de comparaison des couleurs.

**Returns:**
int - l'algorithme de comparaison des couleurs.
### setColorCompareMode(int value) {#setColorCompareMode-int-}
```
public final void setColorCompareMode(int value)
```


Définit l'algorithme de comparaison des couleurs.

Valeur : Le mode de comparaison des couleurs.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | l'algorithme de comparaison des couleurs. |

### getColorComparisonDelegate() {#getColorComparisonDelegate--}
```
public final MagicWandSettings.ColorComparison getColorComparisonDelegate()
```


Obtient l'algorithme de comparaison de couleur personnalisé si `ColorCompareMode`(\#getColorCompareMode.getColorCompareMode/\#setColorCompareMode(int).setColorCompareMode(int)) est défini sur [ColorComparisonMode.Custom](../../com.aspose.imaging.magicwand/colorcomparisonmode\#Custom).

Valeur : le délégué de comparaison de couleur.

**Returns:**
[ColorComparison](../../com.aspose.imaging.magicwand/colorcomparison) - the custom color comparison algorithm if `ColorCompareMode`(\#getColorCompareMode.getColorCompareMode/\#setColorCompareMode(int).setColorCompareMode(int)) is set to [ColorComparisonMode.Custom](../../com.aspose.imaging.magicwand/colorcomparisonmode\#Custom).
### setColorComparisonDelegate(MagicWandSettings.ColorComparison value) {#setColorComparisonDelegate-com.aspose.imaging.magicwand.MagicWandSettings.ColorComparison-}
```
public final void setColorComparisonDelegate(MagicWandSettings.ColorComparison value)
```


Définit l'algorithme de comparaison de couleur personnalisé si `ColorCompareMode`(\#getColorCompareMode.getColorCompareMode/\#setColorCompareMode(int).setColorCompareMode(int)) est défini sur [ColorComparisonMode.Custom](../../com.aspose.imaging.magicwand/colorcomparisonmode\#Custom).

Valeur : le délégué de comparaison de couleur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [ColorComparison](../../com.aspose.imaging.magicwand/colorcomparison) | l'algorithme de comparaison de couleur personnalisé si `ColorCompareMode`(\#getColorCompareMode.getColorCompareMode/\#setColorCompareMode(int).setColorCompareMode(int)) est défini sur [ColorComparisonMode.Custom](../../com.aspose.imaging.magicwand/colorcomparisonmode\#Custom). |

