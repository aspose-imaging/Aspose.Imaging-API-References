---
title: "VectorMultipageImage"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'image multipage Vector"
type: docs
weight: 118
url: /fr/java/com.aspose.imaging/vectormultipageimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage)

**All Implemented Interfaces:**
[com.aspose.imaging.IMultipageImage](../../com.aspose.imaging/imultipageimage)
```
public abstract class VectorMultipageImage extends VectorImage implements IMultipageImage
```

L'image multipage Vector
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [VectorMultipageImage()](#VectorMultipageImage--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [isCached()](#isCached--) | Obtient une valeur indiquant si les données de l'objet sont actuellement en cache et aucune lecture de données n'est requise. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Obtient le nombre de bits par pixel de l'image. |
| [getWidth()](#getWidth--) | Obtient la largeur de l'image. |
| [getHeight()](#getHeight--) | Obtient la hauteur de l'image. |
| [getDefaultPage()](#getDefaultPage--) | Obtient la page par défaut. |
| [getPageExportingAction()](#getPageExportingAction--) | Obtient l'action d'exportation de la page. |
| [setPageExportingAction(PageExportingAction value)](#setPageExportingAction-com.aspose.imaging.PageExportingAction-) | Définit l'action d'exportation de la page. |
| [getMetadata()](#getMetadata--) | Obtient les métadonnées de l'image. |
| [cacheData()](#cacheData--) | Met en cache les données et garantit qu'aucun chargement de données supplémentaire ne sera effectué à partir du `DataStreamSupporter.getDataStreamContainer()`([DataStreamSupporter.getDataStreamContainer](../../com.aspose.imaging/datastreamsupporter\#getDataStreamContainer)). |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | Recadre le rectangle spécifié. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | Redimensionne l'image. |
| [rotate(float angle)](#rotate-float-) | Faire pivoter l'image autour du centre. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.imaging.ImageResizeSettings-) | Redimensionne l'image. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | Fait pivoter, retourner, ou pivoter et retourner l'image. |
| [removeBackground(RemoveBackgroundSettings settings)](#removeBackground-com.aspose.imaging.RemoveBackgroundSettings-) | Supprime l'arrière-plan. |
| [removeBackground()](#removeBackground--) | Supprime l'arrière-plan. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.imaging.IColorPalette-boolean-) | Définit la palette de l'image. |
| [getEmbeddedImages()](#getEmbeddedImages--) | Obtient les images intégrées. |
### VectorMultipageImage() {#VectorMultipageImage--}
```
public VectorMultipageImage()
```


### isCached() {#isCached--}
```
public boolean isCached()
```


Obtient une valeur indiquant si les données de l'objet sont actuellement en cache et aucune lecture de données n'est requise.

Valeur : `true` si les données de l'objet sont mises en cache ; sinon, `false`.

**Returns:**
boolean - une valeur indiquant si les données de l'objet sont actuellement en cache et aucune lecture de données n'est requise.
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Obtient le nombre de bits par pixel de l'image.

Valeur : le nombre de bits par pixel de l'image.

**Returns:**
int - le nombre de bits par pixel de l'image.
### getWidth() {#getWidth--}
```
public int getWidth()
```


Obtient la largeur de l'image.

Valeur : la largeur de l'image.

**Returns:**
int - la largeur de l'image.
### getHeight() {#getHeight--}
```
public int getHeight()
```


Obtient la hauteur de l'image.

Valeur : la hauteur de l'image.

**Returns:**
int - la hauteur de l'image.
### getDefaultPage() {#getDefaultPage--}
```
public abstract Image getDefaultPage()
```


Obtient la page par défaut.

Valeur : la page par défaut.

**Returns:**
[Image](../../com.aspose.imaging/image) - the default page.
### getPageExportingAction() {#getPageExportingAction--}
```
public PageExportingAction getPageExportingAction()
```


Obtient l'action d'exportation de la page. Veuillez noter que la définition de cette méthode libérera automatiquement les ressources de la page après son exécution. Elle sera exécutée juste avant que chaque page ne soit enregistrée.

Valeur : l'action d'exportation de la page.

**Returns:**
[PageExportingAction](../../com.aspose.imaging/pageexportingaction) - the page exporting action.
### setPageExportingAction(PageExportingAction value) {#setPageExportingAction-com.aspose.imaging.PageExportingAction-}
```
public void setPageExportingAction(PageExportingAction value)
```


Définit l'action d'exportation de la page. Veuillez noter que la définition de cette méthode libérera automatiquement les ressources de la page après son exécution. Elle sera exécutée juste avant que chaque page ne soit enregistrée.

Valeur : l'action d'exportation de la page.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [PageExportingAction](../../com.aspose.imaging/pageexportingaction) | l'action d'exportation de la page. |

### getMetadata() {#getMetadata--}
```
public ImageMetadata getMetadata()
```


Obtient les métadonnées de l'image.

**Returns:**
[ImageMetadata](../../com.aspose.imaging.metadata/imagemetadata) - the image metadata.
### cacheData() {#cacheData--}
```
public void cacheData()
```


Met en cache les données et garantit qu'aucun chargement de données supplémentaire ne sera effectué à partir du `DataStreamSupporter.getDataStreamContainer()`([DataStreamSupporter.getDataStreamContainer](../../com.aspose.imaging/datastreamsupporter\#getDataStreamContainer)).

### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public void crop(Rectangle rectangle)
```


Recadre le rectangle spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Le rectangle. |

### resize(int newWidth, int newHeight, int resizeType) {#resize-int-int-int-}
```
public void resize(int newWidth, int newHeight, int resizeType)
```


Redimensionne l'image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| newWidth | int | La nouvelle largeur. |
| newHeight | int | La nouvelle hauteur. |
| resizeType | int | Le type de redimensionnement. |

### rotate(float angle) {#rotate-float-}
```
public void rotate(float angle)
```


Faire pivoter l'image autour du centre.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| angle | float | L'angle de rotation en degrés. Les valeurs positives feront pivoter dans le sens des aiguilles d'une montre. |

### resize(int newWidth, int newHeight, ImageResizeSettings settings) {#resize-int-int-com.aspose.imaging.ImageResizeSettings-}
```
public void resize(int newWidth, int newHeight, ImageResizeSettings settings)
```


Redimensionne l'image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| newWidth | int | La nouvelle largeur. |
| newHeight | int | La nouvelle hauteur. |
| settings | [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) | Les paramètres de redimensionnement. |

### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


Fait pivoter, retourner, ou pivoter et retourner l'image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rotateFlipType | int | Type de rotation et de retournement. |

### removeBackground(RemoveBackgroundSettings settings) {#removeBackground-com.aspose.imaging.RemoveBackgroundSettings-}
```
public void removeBackground(RemoveBackgroundSettings settings)
```


Supprime l'arrière-plan.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| settings | [RemoveBackgroundSettings](../../com.aspose.imaging/removebackgroundsettings) | Les paramètres. |

### removeBackground() {#removeBackground--}
```
public void removeBackground()
```


Supprime l'arrière-plan.

### setPalette(IColorPalette palette, boolean updateColors) {#setPalette-com.aspose.imaging.IColorPalette-boolean-}
```
public void setPalette(IColorPalette palette, boolean updateColors)
```


Définit la palette de l'image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | La palette à définir. |
| updateColors | boolean | si défini sur `true`, les couleurs seront mises à jour selon la nouvelle palette ; sinon les index de couleur restent inchangés. Notez que les index inchangés peuvent provoquer un plantage de l'image lors du chargement si certains index n'ont aucune entrée correspondante dans la palette. |

### getEmbeddedImages() {#getEmbeddedImages--}
```
public EmbeddedImage[] getEmbeddedImages()
```


Obtient les images intégrées.

**Returns:**
com.aspose.imaging.EmbeddedImage[] - Tableau d'images
