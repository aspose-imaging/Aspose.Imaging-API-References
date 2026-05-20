---
title: "SvgImage"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Manipulez les fichiers d'images SVG Scalar Vector Graphics avec notre API en utilisant la puissance du format texte basé sur XML pour une personnalisation et une évolutivité transparentes."
type: docs
weight: 11
url: /fr/java/com.aspose.imaging.fileformats.svg/svgimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage)

**All Implemented Interfaces:**
[com.aspose.imaging.xmp.IHasXmpData](../../com.aspose.imaging.xmp/ihasxmpdata)
```
public final class SvgImage extends VectorImage implements IHasXmpData
```

Manipulez les fichiers d'images Scalar Vector Graphics (SVG) avec notre API, en utilisant la puissance du format texte basé sur XML pour une personnalisation et une évolutivité transparentes. Chargez facilement les images SVG, rasterisez les éléments vectoriels et convertissez-les vers d'autres formats, tout en contrôlant les niveaux de compression afin d'optimiser la taille du fichier et la qualité pour vos projets.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [SvgImage(String path)](#SvgImage-java.lang.String-) | Instancie un nouvel objet de la classe [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage), en utilisant le chemin spécifié pour localiser et charger l'image. |
| [SvgImage(InputStream stream)](#SvgImage-java.io.InputStream-) | Crée une nouvelle instance de la classe [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage), en chargeant l'image depuis le flux fourni. |
| [SvgImage(int width, int height)](#SvgImage-int-int-) | Instancie un nouvel objet [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage) avec la largeur et la hauteur spécifiées. |
| [SvgImage(SvgOptions svgOptions, int width, int height)](#SvgImage-com.aspose.imaging.imageoptions.SvgOptions-int-int-) | Crée une nouvelle instance de la classe [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage) avec les options SVG spécifiées, ainsi que les paramètres de largeur et de hauteur de l'image. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [isCached()](#isCached--) | Récupère une valeur booléenne indiquant si les données de l'objet sont actuellement en cache, éliminant ainsi le besoin d'opérations de lecture de données supplémentaires. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Récupère le nombre de bits par pixel de l'image. |
| [getFileFormat()](#getFileFormat--) | Récupère le format de fichier de l'image, fournissant des métadonnées essentielles pour le traitement et les vérifications de compatibilité. |
| [cacheData()](#cacheData--) | Mettez en cache les données et garantissez qu'aucun chargement supplémentaire de données ne proviendra du `DataStreamSupporter.DataStreamContainer` sous-jacent ([DataStreamSupporter.getDataStreamContainer](../../com.aspose.imaging/datastreamsupporter\#getDataStreamContainer)). |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | Redimensionnez l'image pour correspondre aux dimensions spécifiées tout en préservant son ratio d'aspect. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | Recadre le rectangle spécifié. |
| [rotate(float angle)](#rotate-float-) | Faire pivoter l'image autour du centre. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.imaging.IColorPalette-boolean-) | Applique une palette spécifiée à l'image, permettant la personnalisation des schémas de couleurs à des fins esthétiques ou fonctionnelles. |

## Example: This example shows how to load an SVG image from a file stream and rasterize it to PNG.

``` java
String dir = "c:\\temp\\";

// Chargez une image SVG depuis un flux de fichier.
java.io.InputStream stream = new java.io.FileInputStream(dir + "test.svg");
com.aspose.imaging.fileformats.svg.SvgImage svgImage = new com.aspose.imaging.fileformats.svg.SvgImage(stream);
try {
    // Pour rasteriser le SVG, nous devons spécifier les options de rasterisation.
    com.aspose.imaging.imageoptions.SvgRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.SvgRasterizationOptions();
    com.aspose.imaging.imageoptions.PngOptions saveOptions = new com.aspose.imaging.imageoptions.PngOptions();
    saveOptions.setVectorRasterizationOptions(rasterizationOptions);

    svgImage.save(dir + "test.output.png", saveOptions);
} finally {
    svgImage.dispose();
    stream.close();
}
```


## Example: The following example shows how to convert a compressed images (*.
L'exemple suivant montre comment convertir des images compressées (*.emz,*.wmz, *.svgz) en format raster
``` java
String[] files = new String[]{ "example.emz", "example.wmz", "example.svgz" };
String baseFolder = "D:\\Compressed\\";
for(String file : files)
{
    String inputFile = (baseFolder + file);
    String outFile = inputFile + ".png";
    try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFile))
    {
        final com.aspose.imaging.imageoptions.VectorRasterizationOptions vectorRasterizationOptions = 
                (com.aspose.imaging.imageoptions.VectorRasterizationOptions) image.getDefaultOptions(new Object[]{Color.getWhite(), image.getWidth(), image.getHeight()});
        image.save(outFile, new com.aspose.imaging.imageoptions.PngOptions()
        {{
            setVectorRasterizationOptions(vectorRasterizationOptions);
        }});
    }
}
```


## Example: The following example shows how to convert a svgz images to svg format

``` java
String file = "example.svgz";
String baseFolder = "D:\\Compressed\\";
String inputFile = baseFolder + file;
String outFile = inputFile + ".svg";
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFile))
{
    com.aspose.imaging.imageoptions.VectorRasterizationOptions vectorRasterizationOptions = new com.aspose.imaging.imageoptions.SvgRasterizationOptions();
    vectorRasterizationOptions.setPageSize(com.aspose.imaging.Size.to_SizeF(image.getSize()));
    com.aspose.imaging.imageoptions.SvgOptions options = new com.aspose.imaging.imageoptions.SvgOptions();
    options.setVectorRasterizationOptions(vectorRasterizationOptions);
    image.save(outFile, options);
}
```


## Example: The following example shows how to convert a svg images to svgz format

``` java
String file = "juanmontoya_lingerie.svg";
String baseFolder = "D:\\Compressed\\";
String inputFile = baseFolder + file;
String outFile = inputFile + ".svgz";
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFile))
{
    com.aspose.imaging.imageoptions.VectorRasterizationOptions vectorRasterizationOptions = new com.aspose.imaging.imageoptions.SvgRasterizationOptions();
    vectorRasterizationOptions.setPageSize(com.aspose.imaging.Size.to_SizeF(image.getSize()));
    com.aspose.imaging.imageoptions.SvgOptions options = new com.aspose.imaging.imageoptions.SvgOptions();
    options.setVectorRasterizationOptions(vectorRasterizationOptions);
    options.setCompress(true);
    image.save(outFile, options);
}
```

### SvgImage(String path) {#SvgImage-java.lang.String-}
```
public SvgImage(String path)
```


Instancie un nouvel objet de la classe [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage), en utilisant le chemin spécifié pour localiser et charger l'image. Ce constructeur facilite la création d'instances d'images SVG à partir de fichiers externes, permettant une intégration transparente dans les systèmes logiciels et les flux de travail.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| chemin | java.lang.String | Le chemin à partir duquel charger l'image et initialiser les données de pixels et de palette. |

### SvgImage(InputStream stream) {#SvgImage-java.io.InputStream-}
```
public SvgImage(InputStream stream)
```


Crée une nouvelle instance de la classe [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage), en chargeant l'image depuis le flux fourni. Ce constructeur permet le chargement direct d'images SVG depuis des flux, améliorant la flexibilité et l'efficacité dans la gestion des ressources d'image au sein des applications logicielles.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| flux | java.io.InputStream | Le flux à partir duquel charger l'image et initialiser les données de pixels et de palette. |

### SvgImage(int width, int height) {#SvgImage-int-int-}
```
public SvgImage(int width, int height)
```


Instancie un nouvel objet [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage) avec la largeur et la hauteur spécifiées. Ce constructeur permet aux développeurs de créer des images SVG avec des dimensions prédéfinies, facilitant un contrôle précis de la taille de l'image lors de l'initialisation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| width | int | La largeur de l'image. |
| height | int | La hauteur de l'image. |

### SvgImage(SvgOptions svgOptions, int width, int height) {#SvgImage-com.aspose.imaging.imageoptions.SvgOptions-int-int-}
```
public SvgImage(SvgOptions svgOptions, int width, int height)
```


Crée une nouvelle instance de la classe [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage) avec les options SVG spécifiées, ainsi que les paramètres de largeur et de hauteur de l'image. Ce constructeur permet aux développeurs d'initialiser des images SVG avec des options et des dimensions personnalisées, offrant une flexibilité dans la gestion du contenu et de la mise en page SVG.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| svgOptions | [SvgOptions](../../com.aspose.imaging.imageoptions/svgoptions) | Les options SVG. |
| width | int | Largeur de l'image. |
| height | int | Hauteur de l'image. |

### isCached() {#isCached--}
```
public boolean isCached()
```


Récupère une valeur booléenne indiquant si les données de l'objet sont actuellement mises en cache, éliminant ainsi le besoin d'opérations de lecture de données supplémentaires. Cette propriété fournit un aperçu de l'état actuel du cache, optimisant la récupération et le traitement des données pour améliorer les performances et l'efficacité.

**Returns:**
booléen - `true` si les données de l'objet sont en cache ; sinon, `false`.
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Récupère le nombre de bits par pixel de l'image. Il est important de noter que ce paramètre ne s'applique pas aux images vectorielles, car elles ne sont pas mesurées en pixels. Cette propriété fournit des informations essentielles sur la profondeur de couleur de l'image, facilitant les tâches de traitement et de manipulation.

**Returns:**
int - Le nombre de bits par pixel de l'image.
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Récupère le format de fichier de l'image, fournissant des métadonnées essentielles pour le traitement et les vérifications de compatibilité. Cette propriété est indispensable pour déterminer les stratégies de décodage et d'encodage appropriées afin de gérer efficacement les données de l'image sur différents systèmes et applications.

**Returns:**
long - format de fichier
### cacheData() {#cacheData--}
```
public void cacheData()
```


Mise en cache des données et garantie qu'aucune charge supplémentaire de données ne sera effectuée depuis le `DataStreamSupporter.DataStreamContainer`([DataStreamSupporter.getDataStreamContainer](../../com.aspose.imaging/datastreamsupporter\#getDataStreamContainer)). Cette optimisation améliore les performances en éliminant les opérations redondantes de récupération de données, surtout bénéfique dans les scénarios nécessitant un accès fréquent aux données de l'image.

### resize(int newWidth, int newHeight, int resizeType) {#resize-int-int-int-}
```
public void resize(int newWidth, int newHeight, int resizeType)
```


Redimensionne l'image pour l'adapter aux dimensions spécifiées tout en préservant son ratio d'aspect. Cette méthode offre un moyen pratique d'ajuster la taille de l'image sans déformer ses proportions, assurant un affichage ou un stockage optimal selon les dimensions souhaitées.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| newWidth | int | La nouvelle largeur. |
| newHeight | int | La nouvelle hauteur. |
| resizeType | int | Le type de redimensionnement. |

### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public void crop(Rectangle rectangle)
```


Recadre le rectangle spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Le rectangle. |

### rotate(float angle) {#rotate-float-}
```
public void rotate(float angle)
```


Faire pivoter l'image autour du centre.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| angle | float | L'angle de rotation en degrés. Les valeurs positives feront pivoter dans le sens des aiguilles d'une montre. |

### setPalette(IColorPalette palette, boolean updateColors) {#setPalette-com.aspose.imaging.IColorPalette-boolean-}
```
public void setPalette(IColorPalette palette, boolean updateColors)
```


Applique une palette spécifiée à l'image, permettant la personnalisation des schémas de couleurs à des fins esthétiques ou fonctionnelles. Cette méthode offre une flexibilité dans la gestion des palettes de couleurs pour répondre à diverses exigences de conception ou d'application.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | La palette à définir. |
| updateColors | boolean | si défini sur `true`, les couleurs seront mises à jour selon la nouvelle palette ; sinon les index de couleur restent inchangés. Notez que les index inchangés peuvent provoquer un plantage de l'image lors du chargement si certains index n'ont aucune entrée correspondante dans la palette. |

