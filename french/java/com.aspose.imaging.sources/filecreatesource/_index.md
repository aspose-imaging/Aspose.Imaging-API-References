---
title: "FileCreateSource"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Représente une source de fichier pour la création."
type: docs
weight: 10
url: /fr/java/com.aspose.imaging.sources/filecreatesource/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.Source](../../com.aspose.imaging/source), [com.aspose.imaging.sources.FileSource](../../com.aspose.imaging.sources/filesource)
```
public final class FileCreateSource extends FileSource
```

Représente une source de fichier pour la création.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [FileCreateSource(String filePath)](#FileCreateSource-java.lang.String-) | Initialise une nouvelle instance de la classe `FileCreateSource`. |
| [FileCreateSource(String filePath, boolean isTemporal)](#FileCreateSource-java.lang.String-boolean-) | Initialise une nouvelle instance de la classe `FileCreateSource`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getFilePath()](#getFilePath--) | Obtient le chemin du fichier à créer. |
| [isTemporal()](#isTemporal--) | Obtient une valeur indiquant si le fichier sera temporaire. |
| [getStreamContainer()](#getStreamContainer--) | Obtient le conteneur de flux. |

## Example: This example demonstrates the use of Font and SolidBrush class to draw strings on Image surface.
Cet exemple montre l'utilisation des classes Font et SolidBrush pour dessiner des chaînes sur la surface d'une Image. L'exemple crée une nouvelle Image et dessine des formes à l'aide de Figures et de GraphicsPath
``` java
//Crée une instance de BmpOptions et définit ses différentes propriétés
com.aspose.imaging.imageoptions.BmpOptions bmpOptions = new com.aspose.imaging.imageoptions.BmpOptions();
bmpOptions.setBitsPerPixel(24);

//Créez une instance de FileCreateSource et affectez‑la comme Source pour l'instance de BmpOptions
//Le deuxième paramètre booléen détermine si le fichier à créer est IsTemporal ou non
bmpOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("C:\\temp\\sample.bmp", false));

//Crée une instance de Image
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(bmpOptions, 500, 500);
try {
    //Crée et initialise une instance de la classe Graphics
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);

    //Efface la surface Graphics
    graphics.clear(com.aspose.imaging.Color.getWheat());

    //Crée une instance de Font
    com.aspose.imaging.Font font = new com.aspose.imaging.Font("Times New Roman", 16);

    //Crée une instance de SolidBrush de couleur rouge
    com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getRed());

    //Dessine une chaîne
    graphics.drawString("Created by Aspose.Imaging for Java", font, brush, new com.aspose.imaging.PointF(100, 100));

    // enregistre toutes les modifications
    image.save();
} finally {
    image.dispose();
}
```

### FileCreateSource(String filePath) {#FileCreateSource-java.lang.String-}
```
public FileCreateSource(String filePath)
```


Initialise une nouvelle instance de la classe `FileCreateSource`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | Le chemin du fichier à créer. |

### FileCreateSource(String filePath, boolean isTemporal) {#FileCreateSource-java.lang.String-boolean-}
```
public FileCreateSource(String filePath, boolean isTemporal)
```


Initialise une nouvelle instance de la classe `FileCreateSource`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | Le chemin du fichier à créer. |
| isTemporal | boolean | Si défini sur `true`, le fichier créé sera temporaire. |

### getFilePath() {#getFilePath--}
```
public String getFilePath()
```


Obtient le chemin du fichier à créer.

Valeur : le chemin du fichier à créer.

**Returns:**
java.lang.String
### isTemporal() {#isTemporal--}
```
public boolean isTemporal()
```


Obtient une valeur indiquant si le fichier sera temporaire.

Valeur : `true` si le fichier sera temporaire ; sinon, `false`.

**Returns:**
boolean
### getStreamContainer() {#getStreamContainer--}
```
public StreamContainer getStreamContainer()
```


Obtient le conteneur de flux.

**Returns:**
[StreamContainer](../../com.aspose.imaging/streamcontainer) - the stream container.

Utilisez avec précaution. Vous devrez libérer le conteneur de flux après récupération.
