---
title: "ApngImage"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'API du format de fichier image Animated PNG Animated Portable Network Graphics est une solution polyvalente pour les développeurs souhaitant intégrer du contenu animé dans leurs applications."
type: docs
weight: 11
url: /fr/java/com.aspose.imaging.fileformats.apng/apngimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage), [com.aspose.imaging.RasterCachedMultipageImage](../../com.aspose.imaging/rastercachedmultipageimage)

**All Implemented Interfaces:**
[com.aspose.imaging.IMultipageImageExt](../../com.aspose.imaging/imultipageimageext)
```
public final class ApngImage extends RasterCachedMultipageImage implements IMultipageImageExt
```

L'API du format de fichier image Animated PNG (Animated Portable Network Graphics) est une solution polyvalente pour les développeurs souhaitant intégrer du contenu animé dans leurs applications. Cette API offre un contrôle étendu sur les paramètres des cadres, permettant aux utilisateurs de définir des paramètres spécifiques à chaque cadre, y compris la durée de la boucle et les paramètres du fichier PNG. Grâce à cet outil riche en fonctionnalités, vous pouvez gérer et optimiser facilement l'affichage des images APNG, importer et exporter des images, améliorant ainsi les aspects dynamiques et interactifs de vos applications.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [ApngImage(ApngOptions options, int width, int height)](#ApngImage-com.aspose.imaging.imageoptions.ApngOptions-int-int-) | Commencez à travailler avec la classe [ApngImage](../../com.aspose.imaging.fileformats.apng/apngimage) en initialisant facilement une nouvelle instance. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | Accédez rapidement aux informations sur le format de fichier grâce à cette propriété pratique. |
| [getPageCount()](#getPageCount--) | Récupérez facilement le nombre total de pages de votre fichier image grâce à cette propriété. |
| [getPages()](#getPages--) | Accédez sans effort aux pages de votre image grâce à cette propriété pratique. |
| [getNumPlays()](#getNumPlays--) | Contrôlez sans effort le nombre de boucles de votre animation grâce à cette propriété polyvalente. |
| [setNumPlays(int value)](#setNumPlays-int-) | Contrôlez sans effort le nombre de boucles de votre animation grâce à cette propriété polyvalente. |
| [getDefaultFrameTime()](#getDefaultFrameTime--) | Ajustez facilement la durée par défaut des cadres lors de la création de nouveaux cadres grâce à cette propriété flexible. |
| [setDefaultFrameTime(long value)](#setDefaultFrameTime-long-) | Ajustez facilement la durée par défaut des cadres lors de la création de nouveaux cadres grâce à cette propriété flexible. |
| [getInterlaced()](#getInterlaced--) | Déterminez rapidement si cet objet [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) est entrelacé grâce à cette propriété pratique. |
| [getOriginalOptions()](#getOriginalOptions--) | Récupérez facilement les options basées sur les paramètres du fichier original grâce à cette méthode intuitive. |
| [getDefaultOptions(Object[] args)](#getDefaultOptions-java.lang.Object---) | Récupérez sans effort les options par défaut avec cette méthode simple. |
| [getModifyDate(boolean useDefault)](#getModifyDate-boolean-) | Obtenez rapidement la date et l'heure de la dernière modification de l'image de ressource grâce à cette méthode conviviale. |
| [addPage(RasterImage page)](#addPage-com.aspose.imaging.RasterImage-) | Ajoutez une nouvelle page à l'image sans effort grâce à cette méthode intuitive. |
| [addFrame()](#addFrame--) | /\*\* |
| [addFrame(RasterImage frameImage)](#addFrame-com.aspose.imaging.RasterImage-) | Élargissez sans effort votre collection de cadres en ajoutant un nouveau cadre à la fin grâce à cette méthode intuitive. |
| [addFrame(RasterImage frameImage, long frameTime)](#addFrame-com.aspose.imaging.RasterImage-long-) | Étendez votre collection de cadres de manière fluide en ajoutant un nouveau cadre au avec cette méthode intuitive. |
| [insertFrame(int index)](#insertFrame-int-) | Insérez sans effort un nouveau cadre dans votre collection de cadres à l'emplacement spécifié avec cette méthode intuitive. |
| [insertFrame(int index, RasterImage frameImage)](#insertFrame-int-com.aspose.imaging.RasterImage-) | Insère un nouveau cadre dans sa propre collection de cadres à l'index spécifié. |
| [insertFrame(int index, RasterImage frameImage, long frameTime)](#insertFrame-int-com.aspose.imaging.RasterImage-long-) | Insère un nouveau cadre dans sa propre collection de cadres à l'index spécifié. |
| [popFrameAt(int index)](#popFrameAt-int-) | Supprimez et récupérez le cadre à l'index spécifié de votre collection de cadres grâce à cette méthode intuitive. |
| [removeFrameAt(int index)](#removeFrameAt-int-) | Supprimez le cadre à l'index spécifié de votre collection de cadres de manière fluide avec cette méthode. |
| [removeAllFrames()](#removeAllFrames--) | Videz votre collection de cadres en supprimant tous les cadres grâce à cette méthode intuitive. |
| [setDefaultImage(RasterImage image)](#setDefaultImage-com.aspose.imaging.RasterImage-) | Définissez l'image raster spécifiée comme image par défaut pour l'animation en cours sans effort grâce à cette méthode. |
| [resetDefaultImage()](#resetDefaultImage--) | Supprimez une image par défaut précédemment définie avec cette méthode intuitive. |

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

### ApngImage(ApngOptions options, int width, int height) {#ApngImage-com.aspose.imaging.imageoptions.ApngOptions-int-int-}
```
public ApngImage(ApngOptions options, int width, int height)
```


Commencez à travailler avec la classe [ApngImage](../../com.aspose.imaging.fileformats.apng/apngimage) en initialisant une nouvelle instance sans effort. Idéal pour les développeurs souhaitant commencer à utiliser les objets ApngImage rapidement et efficacement dans leurs projets.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| options | [ApngOptions](../../com.aspose.imaging.imageoptions/apngoptions) | Les options. |
| width | int | La largeur. |
| height | int | La hauteur. |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Accédez rapidement aux informations sur le format de fichier grâce à cette propriété pratique. Idéal pour les développeurs qui doivent récupérer facilement les détails du format de leurs fichiers Apng.

**Returns:**
long
### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


Récupérez le nombre total de pages de votre fichier image sans effort grâce à cette propriété. Idéal pour les développeurs ayant besoin d'un accès rapide aux informations de comptage des pages.

Valeur : le nombre de pages.

**Returns:**
int
### getPages() {#getPages--}
```
public Image[] getPages()
```


Accédez sans effort aux pages de votre image grâce à cette propriété pratique. Parfait pour les développeurs recherchant un accès rapide et facile aux pages individuelles pour les manipuler.

Valeur: Les pages.

**Returns:**
com.aspose.imaging.Image[]
### getNumPlays() {#getNumPlays--}
```
public int getNumPlays()
```


Contrôlez sans effort le nombre de répétitions de votre animation avec cette propriété polyvalente. Parfait pour les développeurs recherchant un contrôle précis du comportement de l'animation, avec prise en charge de la boucle infinie lorsque la valeur est égale à 0.

Valeur : Le nombre de répétitions.

**Returns:**
int
### setNumPlays(int value) {#setNumPlays-int-}
```
public void setNumPlays(int value)
```


Contrôlez sans effort le nombre de répétitions de votre animation avec cette propriété polyvalente. Parfait pour les développeurs recherchant un contrôle précis du comportement de l'animation, avec prise en charge de la boucle infinie lorsque la valeur est égale à 0.

Valeur : Le nombre de répétitions.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getDefaultFrameTime() {#getDefaultFrameTime--}
```
public long getDefaultFrameTime()
```


Ajustez facilement la durée par défaut des images clés pour créer de nouvelles images avec cette propriété flexible. Parfait pour les développeurs souhaitant personnaliser efficacement le timing des images dans leurs animations.

Valeur : La durée par défaut de l'image clé, en millisecondes.

**Returns:**
long
### setDefaultFrameTime(long value) {#setDefaultFrameTime-long-}
```
public void setDefaultFrameTime(long value)
```


Ajustez facilement la durée par défaut des images clés pour créer de nouvelles images avec cette propriété flexible. Parfait pour les développeurs souhaitant personnaliser efficacement le timing des images dans leurs animations.

Valeur : La durée par défaut de l'image clé, en millisecondes.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | long |  |

### getInterlaced() {#getInterlaced--}
```
public boolean getInterlaced()
```


Déterminez rapidement si cet objet [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) est entrelacé grâce à cette propriété pratique. Idéal pour les développeurs qui doivent vérifier facilement le statut d'entrelacement des images PNG.

Valeur : `true` si entrelacé ; sinon, `false`.

**Returns:**
boolean
### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


Récupérez les options basées sur les paramètres du fichier original sans effort avec cette méthode intuitive. Idéal pour les développeurs souhaitant accéder et utiliser des paramètres qui correspondent aux caractéristiques du fichier original. Cela peut être utile pour conserver la profondeur de couleur et d'autres paramètres de l'image originale inchangés. Par exemple, si nous chargeons une image PNG noir‑blanc avec 1 bit par pixel puis l'enregistrons en utilisant la méthode [DataStreamSupporter.save(String)](../../com.aspose.imaging/datastreamsupporter\#save-String-), l'image PNG de sortie avec 8 bits par pixel sera générée. Pour éviter cela et enregistrer l'image PNG avec 1 bit par pixel, utilisez cette méthode pour obtenir les options d'enregistrement correspondantes et les transmettre à la méthode [Image.save(String, ImageOptionsBase)](../../com.aspose.imaging/image\#save-String--ImageOptionsBase-) en tant que deuxième paramètre.

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - The options based on the original file settings.
### getDefaultOptions(Object[] args) {#getDefaultOptions-java.lang.Object---}
```
public ImageOptionsBase getDefaultOptions(Object[] args)
```


Récupérez les options par défaut sans effort avec cette méthode simple. Idéal pour les développeurs recherchant un accès rapide aux paramètres d'image Apng par défaut.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| args | java.lang.Object[] | Les arguments. |

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - Default options
### getModifyDate(boolean useDefault) {#getModifyDate-boolean-}
```
public Date getModifyDate(boolean useDefault)
```


Obtenez rapidement la date et l'heure de la dernière modification de l'image de ressource avec cette méthode conviviale. Idéal pour les développeurs qui doivent suivre les changements et gérer les ressources efficacement.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| useDefault | boolean | si défini sur `true`, utilise les informations de FileInfo comme valeur par défaut. |

**Returns:**
java.util.Date - La date et l'heure auxquelles l'image de ressource a été modifiée pour la dernière fois.
### addPage(RasterImage page) {#addPage-com.aspose.imaging.RasterImage-}
```
public void addPage(RasterImage page)
```


Ajoutez une nouvelle page à l'image sans effort avec cette méthode intuitive. Parfait pour les développeurs souhaitant élargir dynamiquement le contenu de leurs fichiers image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| page | [RasterImage](../../com.aspose.imaging/rasterimage) | La page à ajouter. |

### addFrame() {#addFrame--}
```
public ApngFrame addFrame()
```


/\*\*

Ajoutez facilement une nouvelle image clé à la fin de votre collection d'images clés avec cette méthode simple. Idéal pour les développeurs cherchant à agrandir dynamiquement leur collection d'images clés pour des animations avec des images multi‑cadres. Une nouvelle image clé sera créée en fonction de la taille de l'image actuelle.

**Returns:**
[ApngFrame](../../com.aspose.imaging.fileformats.apng/apngframe) - The newly created APNG frame.
### addFrame(RasterImage frameImage) {#addFrame-com.aspose.imaging.RasterImage-}
```
public void addFrame(RasterImage frameImage)
```


Élargissez sans effort votre collection d'images clés en ajoutant une nouvelle image clé à la fin avec cette méthode intuitive. Parfait pour les développeurs souhaitant améliorer dynamiquement leurs animations d'images multi‑cadres. Le contenu de la nouvelle image clé sera rempli à partir de l'image spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| frameImage | [RasterImage](../../com.aspose.imaging/rasterimage) | L'image de la trame. |

### addFrame(RasterImage frameImage, long frameTime) {#addFrame-com.aspose.imaging.RasterImage-long-}
```
public void addFrame(RasterImage frameImage, long frameTime)
```


Élargissez votre collection d'images clés de manière fluide en ajoutant une nouvelle trame avec cette méthode intuitive. Idéal pour les développeurs cherchant à enrichir leurs animations d'images multi‑cadres. Le contenu de la nouvelle trame sera rempli à partir de l'image spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| frameImage | [RasterImage](../../com.aspose.imaging/rasterimage) | L'image de la trame. |
| frameTime | long | La durée de la trame, en millisecondes. |

### insertFrame(int index) {#insertFrame-int-}
```
public ApngFrame insertFrame(int index)
```


Insérez sans effort une nouvelle trame dans votre collection d'images clés à l'index spécifié avec cette méthode intuitive. Idéal pour les développeurs recherchant un contrôle précis de l'agencement des trames dans leurs animations d'images multi‑cadres. Une nouvelle trame sera créée en fonction de la taille de l'image actuelle.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | L'index. |

**Returns:**
[ApngFrame](../../com.aspose.imaging.fileformats.apng/apngframe) - The newly created APNG frame.
### insertFrame(int index, RasterImage frameImage) {#insertFrame-int-com.aspose.imaging.RasterImage-}
```
public void insertFrame(int index, RasterImage frameImage)
```


Insère une nouvelle trame dans la collection de trames propre à l'index spécifié. Le contenu de la nouvelle trame sera rempli à partir de l'image spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | L'index. |
| frameImage | [RasterImage](../../com.aspose.imaging/rasterimage) | L'image de la trame. |

### insertFrame(int index, RasterImage frameImage, long frameTime) {#insertFrame-int-com.aspose.imaging.RasterImage-long-}
```
public void insertFrame(int index, RasterImage frameImage, long frameTime)
```


Insère une nouvelle trame dans la collection de trames propre à l'index spécifié. Le contenu de la nouvelle trame sera rempli à partir de l'image spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | L'index. |
| frameImage | [RasterImage](../../com.aspose.imaging/rasterimage) | L'image de la trame. |
| frameTime | long | La durée de la trame, en millisecondes. |

### popFrameAt(int index) {#popFrameAt-int-}
```
public ApngFrame popFrameAt(int index)
```


Supprimez et récupérez la trame à l'index spécifié de votre collection de trames avec cette méthode intuitive. Parfait pour les développeurs recherchant une gestion efficace des trames dans leurs animations.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | L'index. |

**Returns:**
[ApngFrame](../../com.aspose.imaging.fileformats.apng/apngframe) - The removed APNG frame.
### removeFrameAt(int index) {#removeFrameAt-int-}
```
public void removeFrameAt(int index)
```


Supprimez la trame à l'index spécifié de votre collection de trames de manière fluide avec cette méthode. Parfait pour les développeurs recherchant une gestion rationalisée des trames dans leurs images multi‑cadres. La trame à supprimer sera libérée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | L'index. |

### removeAllFrames() {#removeAllFrames--}
```
public void removeAllFrames()
```


Effacez votre collection de cadres en supprimant toutes les images avec cette méthode intuitive. Idéal pour les développeurs cherchant à réinitialiser ou rafraîchir leurs animations.

### setDefaultImage(RasterImage image) {#setDefaultImage-com.aspose.imaging.RasterImage-}
```
public void setDefaultImage(RasterImage image)
```


Définissez l'image raster spécifiée comme image par défaut pour l'animation en cours sans effort grâce à cette méthode. Parfait pour les développeurs souhaitant personnaliser l'image par défaut dans leurs animations.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | L'image. |

### resetDefaultImage() {#resetDefaultImage--}
```
public void resetDefaultImage()
```


Supprimez une image par défaut précédemment définie avec cette méthode intuitive. Idéal pour les développeurs cherchant à réinitialiser ou effacer l'image par défaut dans leur animation. Après cela, l'image par défaut est la première image de la collection de cadres (elle ne peut pas être supprimée avec cette méthode).

