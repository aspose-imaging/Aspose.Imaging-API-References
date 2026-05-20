---
title: "CmxImagePage"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'image de la page CMX"
type: docs
weight: 11
url: /fr/java/com.aspose.imaging.fileformats.cmx/cmximagepage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage)

**All Implemented Interfaces:**
[com.aspose.imaging.fileformats.cmx.ICmxImage](../../com.aspose.imaging.fileformats.cmx/icmximage)
```
public class CmxImagePage extends VectorImage implements ICmxImage
```

L'image de la page CMX
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [CmxImagePage(CmxPage cmxPage, Image container)](#CmxImagePage-com.aspose.imaging.fileformats.cmx.objectmodel.CmxPage-com.aspose.imaging.Image-) | Initialise une nouvelle instance de la classe [CmxImagePage](../../com.aspose.imaging.fileformats.cmx/cmximagepage). |
| [CmxImagePage(CmxPage cmxPage)](#CmxImagePage-com.aspose.imaging.fileformats.cmx.objectmodel.CmxPage-) | Initialise une nouvelle instance de la classe [CmxImagePage](../../com.aspose.imaging.fileformats.cmx/cmximagepage). |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getCmxPage()](#getCmxPage--) | Obtient la page CMX. |
| [getFileFormat()](#getFileFormat--) | Obtient une valeur du format de fichier |
| [getBitsPerPixel()](#getBitsPerPixel--) | Obtient le nombre de bits par pixel de l'image. |
| [isCached()](#isCached--) | Obtient une valeur indiquant si les données de l'objet sont actuellement en cache et aucune lecture de données n'est requise. |
| [getWidthF()](#getWidthF--) | Obtient la largeur de l'objet, en pouces. |
| [getHeightF()](#getHeightF--) | Obtient la hauteur de l'objet, en pouces. |
| [getWidth()](#getWidth--) | Obtient la largeur de l'image. |
| [getHeight()](#getHeight--) | Obtient la hauteur de l'image. |
| [getDefaultOptions(Object[] args)](#getDefaultOptions-java.lang.Object---) | Obtient les options par défaut. |
| [cacheData()](#cacheData--) | Le cache ne peut pas être utilisé. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.imaging.IColorPalette-boolean-) | Définit la palette de l'image. |
### CmxImagePage(CmxPage cmxPage, Image container) {#CmxImagePage-com.aspose.imaging.fileformats.cmx.objectmodel.CmxPage-com.aspose.imaging.Image-}
```
public CmxImagePage(CmxPage cmxPage, Image container)
```


Initialise une nouvelle instance de la classe [CmxImagePage](../../com.aspose.imaging.fileformats.cmx/cmximagepage).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| cmxPage | [CmxPage](../../com.aspose.imaging.fileformats.cmx.objectmodel/cmxpage) | La page CMX. |
| container | [Image](../../com.aspose.imaging/image) | Le conteneur. |

### CmxImagePage(CmxPage cmxPage) {#CmxImagePage-com.aspose.imaging.fileformats.cmx.objectmodel.CmxPage-}
```
public CmxImagePage(CmxPage cmxPage)
```


Initialise une nouvelle instance de la classe [CmxImagePage](../../com.aspose.imaging.fileformats.cmx/cmximagepage).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| cmxPage | [CmxPage](../../com.aspose.imaging.fileformats.cmx.objectmodel/cmxpage) | La page CMX. |

### getCmxPage() {#getCmxPage--}
```
public final CmxPage getCmxPage()
```


Obtient la page CMX.

**Returns:**
[CmxPage](../../com.aspose.imaging.fileformats.cmx.objectmodel/cmxpage) - the CMX page.
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Obtient une valeur du format de fichier

**Returns:**
long - une valeur du format de fichier
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Obtient le nombre de bits par pixel de l'image.

**Returns:**
int - le nombre de bits par pixel de l'image.
### isCached() {#isCached--}
```
public boolean isCached()
```


Obtient une valeur indiquant si les données de l'objet sont actuellement en cache et aucune lecture de données n'est requise.

Valeur : `true` si les données de l'objet sont mises en cache ; sinon, `false`.

**Returns:**
boolean - une valeur indiquant si les données de l'objet sont actuellement en cache et aucune lecture de données n'est requise.
### getWidthF() {#getWidthF--}
```
public float getWidthF()
```


Obtient la largeur de l'objet, en pouces.

**Returns:**
float - la largeur de l'objet, en pouces.
### getHeightF() {#getHeightF--}
```
public float getHeightF()
```


Obtient la hauteur de l'objet, en pouces.

**Returns:**
float - la hauteur de l'objet, en pouces.
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
### getDefaultOptions(Object[] args) {#getDefaultOptions-java.lang.Object---}
```
public ImageOptionsBase getDefaultOptions(Object[] args)
```


Obtient les options par défaut.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| args | java.lang.Object[] | Les arguments. |

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - Default options
### cacheData() {#cacheData--}
```
public void cacheData()
```


Le cache ne peut pas être utilisé.


**Example: The following example shows how to cache all pages of a CMX image.**

``` java
String dir = "c:\\temp\\";

// Chargez une image à partir d'un fichier CMX.
com.aspose.imaging.fileformats.cmx.CmxImage image = (com.aspose.imaging.fileformats.cmx.CmxImage) com.aspose.imaging.Image.load(dir + "sample.cmx");
try {
    // Cet appel met en cache uniquement la page par défaut.
    image.cacheData();

    // Mettez en cache toutes les pages afin qu'aucun chargement de données supplémentaire ne soit effectué depuis le flux de données sous-jacent.
    for (com.aspose.imaging.fileformats.cmx.CmxImagePage page : image.getPages()) {
        page.cacheData();
    }
} finally {
    image.dispose();
}
```

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

