---
title: "FeatheringSettings"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Une classe de paramètres de plume."
type: docs
weight: 13
url: /fr/java/com.aspose.imaging.magicwand.imagemasks/featheringsettings/
---
**Inheritance:**
java.lang.Object
```
public class FeatheringSettings
```

Une classe de paramètres de plume.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [FeatheringSettings()](#FeatheringSettings--) | Initialise une nouvelle instance de la classe [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings). |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getSize()](#getSize--) | Obtient la taille du plume. |
| [setSize(int value)](#setSize-int-) | Définit la taille du plume. |
| [getMode()](#getMode--) | Obtient le mode d'algorithme du plume. |
| [setMode(int value)](#setMode-int-) | Définit le mode d'algorithme du plume. |

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

### FeatheringSettings() {#FeatheringSettings--}
```
public FeatheringSettings()
```


Initialise une nouvelle instance de la classe [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings).

### getSize() {#getSize--}
```
public final int getSize()
```


Obtient la taille du plume.

Valeur : La taille du pinceau de plume en pixels.

**Returns:**
int - la taille du plume.
### setSize(int value) {#setSize-int-}
```
public final void setSize(int value)
```


Définit la taille du plume.

Valeur : La taille du pinceau de plume en pixels.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | la taille du plume. |

### getMode() {#getMode--}
```
public final int getMode()
```


Obtient le mode d'algorithme du plume.

Valeur : Le mode d'algorithme du plume.

**Returns:**
int - le mode d'algorithme du plume.
### setMode(int value) {#setMode-int-}
```
public final void setMode(int value)
```


Définit le mode d'algorithme du plume.

Valeur : Le mode d'algorithme du plume.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | le mode d'algorithme de plume. |

