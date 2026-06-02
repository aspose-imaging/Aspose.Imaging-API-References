---
title: "OdImage"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Le document ouvert"
type: docs
weight: 10
url: /fr/java/com.aspose.imaging.fileformats.opendocument/odimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage), [com.aspose.imaging.VectorMultipageImage](../../com.aspose.imaging/vectormultipageimage)

**All Implemented Interfaces:**
com.aspose.internal.fileformats.opendocument.IOdImage
```
public abstract class OdImage extends VectorMultipageImage implements IOdImage
```

Le document ouvert
## Méthodes

| Méthode | Description |
| --- | --- |
| [getDefaultPage()](#getDefaultPage--) | Récupère la page par défaut associée à l'image, offrant un accès essentiel à la page principale de la collection d'images. |
| [isCached()](#isCached--) | Obtient une valeur booléenne indiquant si les données de l'objet sont actuellement mises en cache, éliminant ainsi la nécessité de lire les données. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Récupère le nombre de bits par pixel de l'image. |
| [getPageCount()](#getPageCount--) | Récupère le nombre total de pages dans l'image. |
| [getOdMetadata()](#getOdMetadata--) | Récupère les métadonnées spécifiques aux fichiers OpenDocument. |
| [getRecords()](#getRecords--) | Récupère les enregistrements OpenDocument stockés dans l'image. |
### getDefaultPage() {#getDefaultPage--}
```
public Image getDefaultPage()
```


Récupère la page par défaut associée à l'image, offrant un accès essentiel à la page principale de la collection d'images. Cette propriété simplifie la navigation et la manipulation des données d'image, améliorant l'efficacité des flux de travail de développement logiciel.

**Returns:**
[Image](../../com.aspose.imaging/image) - the default page.
### isCached() {#isCached--}
```
public boolean isCached()
```


Obtient une valeur booléenne indiquant si les données de l'objet sont actuellement mises en cache, éliminant ainsi le besoin de lecture des données. Cette propriété sert d'indicateur d'optimisation, améliorant les performances en minimisant les opérations d'accès redondantes aux données.

**Returns:**
boolean - une valeur indiquant si les données de l'objet sont actuellement en cache et aucune lecture de données n'est requise.
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Récupère le nombre de bits par pixel de l'image. Cette propriété fournit un aperçu du niveau de détail et de la profondeur de couleur représentés dans l'image, aidant à diverses tâches de traitement d'image et d'optimisations.

**Returns:**
int - le nombre de bits par pixel de l'image.
### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


Récupère le nombre total de pages dans l'image. Cette propriété est essentielle pour les applications gérant des images multipages, leur permettant de déterminer avec précision le nombre de pages disponibles pour le traitement ou l'affichage.

**Returns:**
int - le nombre de pages.
### getOdMetadata() {#getOdMetadata--}
```
public final OdMetadata getOdMetadata()
```


Récupère les métadonnées spécifiques aux fichiers OpenDocument. Cette propriété permet d'accéder aux informations essentielles intégrées dans les fichiers OD, facilitant diverses opérations telles que l'extraction, la modification ou l'analyse des métadonnées.

**Returns:**
[OdMetadata](../../com.aspose.imaging.fileformats.opendocument.objects/odmetadata) - the metadata.
### getRecords() {#getRecords--}
```
public final OdObject[] getRecords()
```


Récupère les enregistrements OpenDocument stockés dans l'image. Cette propriété donne accès à des éléments de données structurées spécifiques intégrés dans les fichiers OpenDocument, facilitant la récupération ou la manipulation d'informations pertinentes pour un traitement ou une analyse ultérieure.

**Returns:**
com.aspose.imaging.fileformats.opendocument.OdObject[] - les enregistrements.
