---
title: "WebPOptions"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Créez des images Web raster modernes au format WebP en utilisant notre API, offrant une prise en charge robuste de la compression sans perte et avec perte ainsi que des canaux alpha et des boucles d'animation."
type: docs
weight: 53
url: /fr/java/com.aspose.imaging.imageoptions/webpoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)
```
public class WebPOptions extends ImageOptionsBase
```

Créez des images Web raster modernes au format WebP en utilisant notre API, offrant une prise en charge robuste de la compression sans perte et avec perte, ainsi que des canaux alpha et des boucles d'animation. Améliorez votre contenu web avec des visuels dynamiques tout en optimisant la taille des fichiers pour améliorer les temps de chargement et l'expérience utilisateur.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [WebPOptions()](#WebPOptions--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getLossless()](#getLossless--) | Obtient ou définit une valeur indiquant si ce `WebPOptions` est sans perte. |
| [setLossless(boolean value)](#setLossless-boolean-) | Obtient ou définit une valeur indiquant si ce `WebPOptions` est sans perte. |
| [getQuality()](#getQuality--) | Obtient ou définit la qualité. |
| [setQuality(float value)](#setQuality-float-) | Obtient ou définit la qualité. |
| [getAnimLoopCount()](#getAnimLoopCount--) | Obtient ou définit le nombre de boucles d'animation. |
| [setAnimLoopCount(int value)](#setAnimLoopCount-int-) | Obtient ou définit le nombre de boucles d'animation. |
| [getAnimBackgroundColor()](#getAnimBackgroundColor--) | Obtient ou définit la couleur de l'arrière-plan de l'animation. |
| [setAnimBackgroundColor(long value)](#setAnimBackgroundColor-long-) | Obtient ou définit la couleur de l'arrière-plan de l'animation. |

## Example: The following example shows how to convert a multipage vector image to WEBP format in general way without referencing to a particular image type.

``` java
String dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548\\";
String inputFilePath = dir + "Multipage.cdr";
String outputFilePath = dir + "Multipage.cdr.webp";

com.aspose.imaging.ImageOptionsBase exportOptions = new com.aspose.imaging.imageoptions.WebPOptions();

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFilePath))
{
    exportOptions.setMultiPageOptions(null);

    // Exportez uniquement les deux premières pages. Ces pages seront présentées sous forme de cadres animés dans le WEBP de sortie.
    com.aspose.imaging.IMultipageImage multipageImage = (image instanceof com.aspose.imaging.IMultipageImage) ? (com.aspose.imaging.IMultipageImage)image : null;
    if (multipageImage != null && (multipageImage.getPages() != null && multipageImage.getPageCount() > 2))
    {
        exportOptions.setMultiPageOptions(new com.aspose.imaging.imageoptions.MultiPageOptions(new com.aspose.imaging.IntRange(0, 2)));
    }

    if (image instanceof com.aspose.imaging.VectorImage)
    {
        com.aspose.imaging.imageoptions.VectorRasterizationOptions defaultOptions = (com.aspose.imaging.imageoptions.VectorRasterizationOptions) image.getDefaultOptions(new Object[]{Color.getWhite(), image.getWidth(), image.getHeight()});
        exportOptions.setVectorRasterizationOptions(defaultOptions);
        defaultOptions.setTextRenderingHint(com.aspose.imaging.TextRenderingHint.SingleBitPerPixel);
        defaultOptions.setSmoothingMode(com.aspose.imaging.SmoothingMode.None);
    }

    image.save(outputFilePath, exportOptions);
}
```

### WebPOptions() {#WebPOptions--}
```
public WebPOptions()
```


### getLossless() {#getLossless--}
```
public boolean getLossless()
```


Obtient ou définit une valeur indiquant si ce `WebPOptions` est sans perte.

**Returns:**
booléen - `true` si sans perte ; sinon, `false`.
### setLossless(boolean value) {#setLossless-boolean-}
```
public void setLossless(boolean value)
```


Obtient ou définit une valeur indiquant si ce `WebPOptions` est sans perte.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean | `true` si sans perte ; sinon, `false`. |

### getQuality() {#getQuality--}
```
public float getQuality()
```


Obtient ou définit la qualité.

**Returns:**
float - La qualité.
### setQuality(float value) {#setQuality-float-}
```
public void setQuality(float value)
```


Obtient ou définit la qualité.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float | La qualité. |

### getAnimLoopCount() {#getAnimLoopCount--}
```
public int getAnimLoopCount()
```


Obtient ou définit le nombre de boucles d'animation.

**Returns:**
int - Le nombre de boucles d'animation, 0 - infini.
### setAnimLoopCount(int value) {#setAnimLoopCount-int-}
```
public void setAnimLoopCount(int value)
```


Obtient ou définit le nombre de boucles d'animation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | Le nombre de boucles d'animation, 0 - infini. |

### getAnimBackgroundColor() {#getAnimBackgroundColor--}
```
public long getAnimBackgroundColor()
```


Obtient ou définit la couleur de l'arrière-plan de l'animation.

**Returns:**
long - La couleur de l'arrière-plan de l'animation.
### setAnimBackgroundColor(long value) {#setAnimBackgroundColor-long-}
```
public void setAnimBackgroundColor(long value)
```


Obtient ou définit la couleur de l'arrière-plan de l'animation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | long | La couleur de l'arrière-plan de l'animation. |

