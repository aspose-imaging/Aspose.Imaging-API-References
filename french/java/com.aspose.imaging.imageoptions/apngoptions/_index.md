---
title: "ApngOptions"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'API pour la création du format de fichier image Animated PNG Animated Portable Network Graphics est un outil dynamique destiné aux développeurs cherchant à générer des images animées captivantes."
type: docs
weight: 10
url: /fr/java/com.aspose.imaging.imageoptions/apngoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase), [com.aspose.imaging.imageoptions.PngOptions](../../com.aspose.imaging.imageoptions/pngoptions)
```
public class ApngOptions extends PngOptions
```

L'API pour la création du format de fichier image Animated PNG (Animated Portable Network Graphics) est un outil dynamique destiné aux développeurs cherchant à générer des images animées captivantes. Avec des options personnalisables telles que la durée d'une image et le nombre de boucles, cette API permet d'ajuster finement le contenu animé selon des besoins spécifiques. Que vous créiez des graphiques web attrayants ou des visuels interactifs, vous pouvez exploiter cette API pour intégrer parfaitement des images APNG avec un contrôle précis des paramètres d'animation.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [ApngOptions()](#ApngOptions--) | Initialise une nouvelle instance de la classe [ApngOptions](../../com.aspose.imaging.imageoptions/apngoptions). |
| [ApngOptions(ApngOptions apngOptions)](#ApngOptions-com.aspose.imaging.imageoptions.ApngOptions-) | Initialise une nouvelle instance de la classe `ApngOptions`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getNumPlays()](#getNumPlays--) | Obtient le nombre de fois que l'animation doit boucler. |
| [setNumPlays(int value)](#setNumPlays-int-) | Définit le nombre de fois que l'animation doit boucler. |
| [getDefaultFrameTime()](#getDefaultFrameTime--) | Obtient la durée d'image par défaut. |
| [setDefaultFrameTime(long value)](#setDefaultFrameTime-long-) | Définit la durée d'image par défaut. |

## Example: The following example shows how to export to APNG file format.

``` java

import com.aspose.imaging;
import com.aspose.imaging.imageoptions;

try (Image image = Image.load("Animation1.webp"))
{
    // Exporter vers une animation APNG avec des cycles d'animation illimités par défaut
    image.save("Animation1.webp.png", new ApngOptions());
    // Mise en place des cycles d'animation
    ApngOptions options = new ApngOptions();
    options.setNumPlays(5);
    image.save("Animation2.webp.png", options); // 5 cycles
}
```


## Example: The following example shows how to export apng APNG file format from other non-animated multi-page format.

``` java
import com.aspose.imaging;
import com.aspose.imaging.imageoptions;

try (Image image = Image.load("img4.tif"))
{
    // Mise en place de la durée d'image par défaut
    ApngOptions options = new ApngOptions();
    options.setDefaultFrameTime(500);
    image.save("img4.tif.500ms.png", options); // 500 ms
    options.setDefaultFrameTime(250);
    image.save("img4.tif.250ms.png", options); // 250 ms
}
```

### ApngOptions() {#ApngOptions--}
```
public ApngOptions()
```


Initialise une nouvelle instance de la classe [ApngOptions](../../com.aspose.imaging.imageoptions/apngoptions).

### ApngOptions(ApngOptions apngOptions) {#ApngOptions-com.aspose.imaging.imageoptions.ApngOptions-}
```
public ApngOptions(ApngOptions apngOptions)
```


Initialise une nouvelle instance de la classe `ApngOptions`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| apngOptions | [ApngOptions](../../com.aspose.imaging.imageoptions/apngoptions) | Les options PNG. |

### getNumPlays() {#getNumPlays--}
```
public final int getNumPlays()
```


Obtient le nombre de fois que l'animation doit boucler. 0 indique une boucle infinie.

**Returns:**
int

**Example: The following example shows how to export to APNG file format.**

``` java

import com.aspose.imaging;
import com.aspose.imaging.imageoptions;

try (Image image = Image.load("Animation1.webp"))
{
    // Exporter vers une animation APNG avec des cycles d'animation illimités par défaut
    image.save("Animation1.webp.png", new ApngOptions());
    // Mise en place des cycles d'animation
    ApngOptions options = new ApngOptions();
    options.setNumPlays(5);
    image.save("Animation2.webp.png", options); // 5 cycles
}
```

### setNumPlays(int value) {#setNumPlays-int-}
```
public final void setNumPlays(int value)
```


Définit le nombre de fois que l'animation doit boucler. 0 indique une boucle infinie.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |


**Example: The following example shows how to export to APNG file format.**

``` java

import com.aspose.imaging;
import com.aspose.imaging.imageoptions;

try (Image image = Image.load("Animation1.webp"))
{
    // Exporter vers une animation APNG avec des cycles d'animation illimités par défaut
    image.save("Animation1.webp.png", new ApngOptions());
    // Mise en place des cycles d'animation
    ApngOptions options = new ApngOptions();
    options.setNumPlays(5);
    image.save("Animation2.webp.png", options); // 5 cycles
}
```

### getDefaultFrameTime() {#getDefaultFrameTime--}
```
public final long getDefaultFrameTime()
```


Obtient la durée d'image par défaut.

**Returns:**
long
### setDefaultFrameTime(long value) {#setDefaultFrameTime-long-}
```
public final void setDefaultFrameTime(long value)
```


Définit la durée d'image par défaut.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | long |  |

