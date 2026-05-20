---
title: "OtgImage"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Traitez les fichiers d’image de dessin OTG de modèle OpenDocument avec notre API tirant parti du format XML OpenDocument avec du contenu graphique pour une manipulation fluide."
type: docs
weight: 13
url: /fr/java/com.aspose.imaging.fileformats.opendocument/otgimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage), [com.aspose.imaging.VectorMultipageImage](../../com.aspose.imaging/vectormultipageimage), [com.aspose.imaging.fileformats.opendocument.OdImage](../../com.aspose.imaging.fileformats.opendocument/odimage)
```
public class OtgImage extends OdImage
```

Traitez les fichiers d’image de dessin OpenDocument Template (OTG) avec notre API, en tirant parti du format XML OpenDocument avec du contenu graphique pour une manipulation fluide. Analysez facilement les documents, personnalisez les couleurs d’arrière‑plan et ajustez les dimensions des pages, garantissant un contrôle optimal et une flexibilité pour vos projets de graphiques vectoriels OTG.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [OtgImage(StreamContainer streamContainer, LoadOptions loadOptions)](#OtgImage-com.aspose.imaging.StreamContainer-com.aspose.imaging.LoadOptions-) | Initialisez un nouvel objet [OtgImage](../../com.aspose.imaging.fileformats.opendocument/otgimage) en fournissant un conteneur de flux et des options de chargement. |
| [OtgImage(StreamContainer streamContainer)](#OtgImage-com.aspose.imaging.StreamContainer-) | Créez un nouvel objet de la classe [OtgImage](../../com.aspose.imaging.fileformats.opendocument/otgimage) en fournissant un conteneur de flux. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | Cette propriété donne accès au format de fichier OTG, offrant des informations essentielles sur le type de données encapsulées dans le fichier image. |
| [getPages()](#getPages--) | Récupère la collection de pages associées à l'image, permettant aux développeurs de logiciels d'accéder à chaque page individuelle et de la manipuler efficacement. |
### OtgImage(StreamContainer streamContainer, LoadOptions loadOptions) {#OtgImage-com.aspose.imaging.StreamContainer-com.aspose.imaging.LoadOptions-}
```
public OtgImage(StreamContainer streamContainer, LoadOptions loadOptions)
```


Initialisez un nouvel objet [OtgImage](../../com.aspose.imaging.fileformats.opendocument/otgimage) en fournissant un conteneur de flux et des options de chargement. Ce constructeur permet aux développeurs de charger efficacement des images OTG depuis des flux tout en spécifiant des configurations de chargement personnalisées.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | Le flux. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Les options de chargement. |

### OtgImage(StreamContainer streamContainer) {#OtgImage-com.aspose.imaging.StreamContainer-}
```
public OtgImage(StreamContainer streamContainer)
```


Créez un nouvel objet de la classe [OtgImage](../../com.aspose.imaging.fileformats.opendocument/otgimage) en fournissant un conteneur de flux. Ce constructeur permet aux développeurs de créer des images OTG directement à partir de conteneurs de flux, simplifiant le processus de manipulation des données d'images OTG.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | Le conteneur de flux. |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Cette propriété donne accès au format de fichier OTG, offrant des informations essentielles sur le type de données encapsulées dans le fichier image. Elle constitue un point de référence crucial pour les développeurs, leur permettant de gérer efficacement les fichiers OTG au sein de leurs applications. En utilisant cette propriété, vous pouvez déterminer le format spécifique du fichier image, facilitant ainsi l'intégration et la manipulation transparentes des fichiers OTG dans leurs systèmes logiciels.

**Returns:**
long
### getPages() {#getPages--}
```
public Image[] getPages()
```


Récupère la collection de pages associées à l'image, permettant aux développeurs de logiciels d'accéder à chaque page individuelle et de la manipuler efficacement. Cette propriété facilite une itération fluide à travers les pages pour diverses opérations, améliorant la fonctionnalité et la polyvalence des applications de traitement d'images.

**Returns:**
com.aspose.imaging.Image[] - les pages.
