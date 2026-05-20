---
title: "OdgImage"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Manipulez le format de fichier image vectoriel OpenDocument Graphic ODG avec notre API, largement utilisé par les applications OpenOffice et LibreOffice Draw pour stocker des éléments de dessin au format vectoriel."
type: docs
weight: 12
url: /fr/java/com.aspose.imaging.fileformats.opendocument/odgimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage), [com.aspose.imaging.VectorMultipageImage](../../com.aspose.imaging/vectormultipageimage), [com.aspose.imaging.fileformats.opendocument.OdImage](../../com.aspose.imaging.fileformats.opendocument/odimage)
```
public class OdgImage extends OdImage
```

Manipulez le format de fichier image vectoriel OpenDocument Graphic (ODG) avec notre API, largement utilisé par les applications OpenOffice et LibreOffice Draw pour stocker des éléments de dessin au format vectoriel. Analysez les documents de manière fluide, accédez aux pages, redimensionnez et faites pivoter les images, garantissant un traitement efficace et une personnalisation des fichiers ODG pour répondre à vos exigences spécifiques.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [OdgImage(StreamContainer streamContainer, LoadOptions options)](#OdgImage-com.aspose.imaging.StreamContainer-com.aspose.imaging.LoadOptions-) | Commencez une nouvelle création de l'objet de classe [OdgImage](../../com.aspose.imaging.fileformats.opendocument/odgimage) avec l'initialisation d'une nouvelle instance. |
| [OdgImage(StreamContainer streamContainer)](#OdgImage-com.aspose.imaging.StreamContainer-) | Conçu pour une intégration fluide dans les solutions logicielles, le constructeur [OdgImage](../../com.aspose.imaging.fileformats.opendocument/odgimage) initialise une nouvelle instance en exploitant un conteneur de flux. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | Récupérez facilement la valeur du format de fichier avec cette propriété conviviale. |
| [getPages()](#getPages--) | En récupérant la collection de pages, cette propriété permet d'accéder à l'ensemble des pages associées à une image. |

## Example: This example loads a multi-page ODG image.

``` java
String dir = "c:\\temp\\";

// Utiliser Aspose.Imaging.Image.Load est une méthode unifiée pour charger une image.
com.aspose.imaging.fileformats.opendocument.MultiPageImage image = (com.aspose.imaging.fileformats.opendocument.MultiPageImage) com.aspose.imaging.Image.load(dir + "sample.odg");
try {
    // Convertir en OdgImage
    com.aspose.imaging.fileformats.opendocument.OdgImage odgImage = (com.aspose.imaging.fileformats.opendocument.OdgImage) image;

    // Obtenir toutes les pages
    com.aspose.imaging.Image[] pages = odgImage.getPages();

    // Effectuez un traitement d'image
} finally {
    image.dispose();
}
```


## Example: The following example shows how to export a FODG (Flat XML ODF Template) image to PDF format.

``` java
String dir = "c:\\aspose.imaging\\java\\issues\\1509\\";

String inputFileName = dir + "VariousObjectsMultiPage.fodg";
String outputFileName = inputFileName + ".pdf";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFileName);
try {
    com.aspose.imaging.imageoptions.OdgRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.OdgRasterizationOptions();
    rasterizationOptions.setBackgroundColor(com.aspose.imaging.Color.getWhite());
    rasterizationOptions.setPageSize(Size.to_SizeF(image.getSize()));

    com.aspose.imaging.imageoptions.PdfOptions saveOptions = new com.aspose.imaging.imageoptions.PdfOptions();
    saveOptions.setVectorRasterizationOptions(rasterizationOptions);

    image.save(outputFileName, saveOptions);
}
finally {
    image.close();
}
```

### OdgImage(StreamContainer streamContainer, LoadOptions options) {#OdgImage-com.aspose.imaging.StreamContainer-com.aspose.imaging.LoadOptions-}
```
public OdgImage(StreamContainer streamContainer, LoadOptions options)
```


Commencez une nouvelle création de l'objet de classe [OdgImage](../../com.aspose.imaging.fileformats.opendocument/odgimage) avec l'initialisation d'une nouvelle instance. Exploitez le potentiel d'un conteneur de flux associé à des paramètres d'options de chargement, en conservant un constructeur polyvalent pour charger les images de manière fluide. Ce constructeur permet une gestion efficace des images, offrant des configurations de chargement personnalisables pour une adaptabilité et des performances accrues dans divers scénarios.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | Le flux. |
| options | [LoadOptions](../../com.aspose.imaging/loadoptions) | Les options de chargement |

### OdgImage(StreamContainer streamContainer) {#OdgImage-com.aspose.imaging.StreamContainer-}
```
public OdgImage(StreamContainer streamContainer)
```


Conçu pour une intégration fluide dans les solutions logicielles, le constructeur [OdgImage](../../com.aspose.imaging.fileformats.opendocument/odgimage) initialise une nouvelle instance en exploitant un conteneur de flux. Cette méthode assure une manipulation efficace des données d'image ODG au sein des environnements logiciels, optimisant l'utilisation des ressources et facilitant des flux de travail de traitement d'images rationalisés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | Le conteneur de flux. |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Récupérez facilement la valeur du format de fichier avec cette propriété conviviale. Idéal pour les développeurs cherchant un accès rapide aux informations sur le format de fichier.

**Returns:**
long - une valeur du format de fichier
### getPages() {#getPages--}
```
public Image[] getPages()
```


En récupérant la collection de pages, cette propriété permet d'accéder à l'ensemble des pages associées à une image. En accédant à cette propriété, les développeurs peuvent parcourir les pages individuelles, récupérer des pages spécifiques en fonction de leur index, ou effectuer des opérations groupées sur l'ensemble de la collection.

**Returns:**
com.aspose.imaging.Image[] - les pages.
