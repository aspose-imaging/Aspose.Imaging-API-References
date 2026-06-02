---
title: "CdrImagePage"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "La page d'image Cdr"
type: docs
weight: 11
url: /fr/java/com.aspose.imaging.fileformats.cdr/cdrimagepage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage)

**All Implemented Interfaces:**
[com.aspose.imaging.fileformats.cdr.ICdrImage](../../com.aspose.imaging.fileformats.cdr/icdrimage)
```
public class CdrImagePage extends VectorImage implements ICdrImage
```

La page d'image Cdr
## Méthodes

| Méthode | Description |
| --- | --- |
| [getParentImage()](#getParentImage--) | Obtient l'image parente. |
| [getPageNumber()](#getPageNumber--) | Obtient le numéro de page. |
| [isCached()](#isCached--) | Obtient une valeur indiquant si les données de l'objet sont actuellement en cache et aucune lecture de données n'est requise. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Obtient le nombre de bits par pixel de l'image. |
| [getFileFormat()](#getFileFormat--) | Obtient une valeur du format de fichier |
| [getCdrDocument()](#getCdrDocument--) | Obtient le document CDR. |
| [getDefaultOptions(Object[] args)](#getDefaultOptions-java.lang.Object---) | Obtient les options par défaut. |
| [cacheData()](#cacheData--) | Met en cache les données et garantit qu'aucun chargement de données supplémentaire ne sera effectué à partir du `P:com.aspose.imaging.dataStreamSupporter.dataStreamContainer` sous-jacent. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.imaging.IColorPalette-boolean-) | Définit la palette de l'image. |
### getParentImage() {#getParentImage--}
```
public final CdrImage getParentImage()
```


Obtient l'image parente.

Valeur : l'image parente.

**Returns:**
[CdrImage](../../com.aspose.imaging.fileformats.cdr/cdrimage) - the parent image.
### getPageNumber() {#getPageNumber--}
```
public final int getPageNumber()
```


Obtient le numéro de page.

Valeur : le numéro de page.

**Returns:**
int - le numéro de page.
### isCached() {#isCached--}
```
public boolean isCached()
```


Obtient une valeur indiquant si les données de l'objet sont actuellement en cache et aucune lecture de données n'est requise.

**Returns:**
boolean
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Obtient le nombre de bits par pixel de l'image.

**Returns:**
int - le nombre de bits par pixel de l'image.
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Obtient une valeur du format de fichier

**Returns:**
long - une valeur du format de fichier
### getCdrDocument() {#getCdrDocument--}
```
public final CdrDocument getCdrDocument()
```


Obtient le document CDR.

Valeur : le document CDR.

**Returns:**
[CdrDocument](../../com.aspose.imaging.fileformats.cdr.objects/cdrdocument) - the CDR document.
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
public synchronized void cacheData()
```


Met en cache les données et garantit qu'aucun chargement de données supplémentaire ne sera effectué à partir du `P:com.aspose.imaging.dataStreamSupporter.dataStreamContainer` sous-jacent.

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

