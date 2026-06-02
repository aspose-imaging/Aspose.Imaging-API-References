---
title: "EmfImage"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'API de prise en charge du format d'image vectorielle Enhanced Metafile Format EMF est un outil complet pour le traitement des images graphiques de manière indépendante du dispositif tout en préservant leurs propriétés d'origine."
type: docs
weight: 10
url: /fr/java/com.aspose.imaging.fileformats.emf/emfimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage), [com.aspose.imaging.fileformats.emf.MetaImage](../../com.aspose.imaging.fileformats.emf/metaimage)
```
public final class EmfImage extends MetaImage
```

L'API de prise en charge du format d'image vectorielle Enhanced Metafile Format (EMF) est un outil complet pour le traitement des images graphiques de manière indépendante du dispositif tout en préservant leurs propriétés d'origine. Développée pour maintenir les proportions, les dimensions, les couleurs et d'autres attributs graphiques, elle inclut la prise en charge du format EMF Plus et des fonctionnalités de recadrage des régions, de redimensionnement du canevas et des images, de rotation, de retournement, de définition des palettes d'images, d'exportation et d'importation vers le contexte de dispositif APS, de compression et de conversion d'EMF vers d'autres formats, garantissant une manipulation polyvalente et une intégration fluide des images EMF dans les applications.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfImage()](#EmfImage--) | Commencez à travailler avec les images EMF en initialisant une nouvelle instance de la classe [EmfImage](../../com.aspose.imaging.fileformats.emf/emfimage). |
| [EmfImage(int width, int height)](#EmfImage-int-int-) | Créez une nouvelle instance de la classe [EmfImage](../../com.aspose.imaging.fileformats.emf/emfimage) en spécifiant les paramètres de largeur et de hauteur. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getHeader()](#getHeader--) | Récupérez l'enregistrement d'en-tête du métafichier EMF avec cette propriété. |
| [setHeader(EmfMetafileHeader value)](#setHeader-com.aspose.imaging.fileformats.emf.emf.records.EmfMetafileHeader-) | Modifiez l'enregistrement d'en-tête du métafichier EMF avec cette propriété. |
| [isCached()](#isCached--) | Accédez à une valeur indiquant si les données de l'objet sont actuellement en cache, éliminant ainsi le besoin de lectures de données supplémentaires. |
| [getRecords()](#getRecords--) | Récupérez ou modifiez les enregistrements associés à l'objet. |
| [setRecords(MetaObjectList value)](#setRecords-com.aspose.imaging.fileformats.emf.MetaObjectList-) | Modifiez les enregistrements associés à l'objet. |
| [getFileFormat()](#getFileFormat--) | Accédez à la valeur du format de fichier associée à l'objet. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Récupérez le nombre de bits par pixel propre aux images raster, car ce paramètre ne s'applique pas aux images vectorielles. |
| [getWidthF()](#getWidthF--) | Accédez à la largeur de l'image, fournissant des informations essentielles pour un rendu et un traitement précis. |
| [getHeightF()](#getHeightF--) | Récupérez la hauteur de l'image, facilitant un rendu précis et des ajustements de mise en page. |
| [cacheData()](#cacheData--) | Mettez en cache les données de manière efficace et évitez le chargement redondant depuis le `DataStreamSupporter.DataStreamContainer`([DataStreamSupporter.getDataStreamContainer](../../com.aspose.imaging/datastreamsupporter\#getDataStreamContainer) avec cette méthode. |
| [getUsedFonts()](#getUsedFonts--) | Récupérez la liste des polices utilisées dans le métafichier avec cette méthode. |
| [resizeCanvas(Rectangle newRectangle)](#resizeCanvas-com.aspose.imaging.Rectangle-) | Redimensionnez le canevas facilement en utilisant cette fonction. |
| [getOriginalOptions()](#getOriginalOptions--) | Obtient les options d'image d'origine. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.imaging.IColorPalette-boolean-) | Définit la palette de l'image. |

## Example: This example shows how to load a EMF image from a file and convert it to SVG using EmfRasterizationOptions.

``` java
String dir = "c:\\temp\\";

// Utiliser Aspose.Imaging.Image.Load est une méthode unifiée pour charger tous les types d'images, y compris les EMF.
com.aspose.imaging.fileformats.emf.EmfImage emfImage = (com.aspose.imaging.fileformats.emf.EmfImage) com.aspose.imaging.Image.load(dir + "test.emf");
try {
    com.aspose.imaging.imageoptions.SvgOptions saveOptions = new com.aspose.imaging.imageoptions.SvgOptions();

    // Le texte sera converti en formes.
    saveOptions.setTextAsShapes(true);

    com.aspose.imaging.imageoptions.EmfRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.EmfRasterizationOptions();

    // La couleur de fond de la surface de dessin.
    rasterizationOptions.setBackgroundColor(com.aspose.imaging.Color.getWhiteSmoke());

    // La taille de la page.
    rasterizationOptions.setPageSize(new com.aspose.imaging.SizeF(emfImage.getWidth(), emfImage.getHeight()));

    // Si un emf intégré existe, alors rendre l'emf ; sinon rendre le wmf.
    rasterizationOptions.setRenderMode(com.aspose.imaging.fileformats.emf.EmfRenderMode.Auto);

    // Définissez la marge horizontale
    rasterizationOptions.setBorderX(50);

    // Définissez la marge verticale
    rasterizationOptions.setBorderY(50);

    saveOptions.setVectorRasterizationOptions(rasterizationOptions);

    emfImage.save(dir + "test.output.svg", saveOptions);
} finally {
    emfImage.dispose();
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


## Example: The following example shows how to convert a emz images to emf format

``` java
String file = "example.emz";
String baseFolder = "D:\\Compressed\\";
String inputFile = (baseFolder + file);
String outFile = inputFile + ".emf";
try (final com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFile))
{
    final com.aspose.imaging.imageoptions.VectorRasterizationOptions vectorRasterizationOptions = new com.aspose.imaging.imageoptions.EmfRasterizationOptions()
    {{
        setPageSize(com.aspose.imaging.Size.to_SizeF(image.getSize()));
    }};
    image.save(outFile, new com.aspose.imaging.imageoptions.EmfOptions()
    {{
        setVectorRasterizationOptions(vectorRasterizationOptions);
    }});
}
```


## Example: The following example shows how to convert a emf images to emz format

``` java
String file = "input.emf";
String baseFolder = "D:\\Compressed\\";
String inputFile = baseFolder + file;
String outFile = inputFile + ".emz";
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFile))
{
    com.aspose.imaging.imageoptions.VectorRasterizationOptions vectorRasterizationOptions = new com.aspose.imaging.imageoptions.EmfRasterizationOptions();
    vectorRasterizationOptions.setPageSize(com.aspose.imaging.Size.to_SizeF(image.getSize()));
    com.aspose.imaging.imageoptions.EmfOptions options = new com.aspose.imaging.imageoptions.EmfOptions();
    options.setVectorRasterizationOptions(vectorRasterizationOptions);
    options.setCompress(true);
    image.save(outFile, options);
}
```

### EmfImage() {#EmfImage--}
```
public EmfImage()
```


Commencez à travailler avec les images EMF en initialisant une nouvelle instance de la classe [EmfImage](../../com.aspose.imaging.fileformats.emf/emfimage). Idéal pour intégrer rapidement les images EMF dans vos projets avec aisance et efficacité.

### EmfImage(int width, int height) {#EmfImage-int-int-}
```
public EmfImage(int width, int height)
```


Créez une nouvelle instance de la classe [EmfImage](../../com.aspose.imaging.fileformats.emf/emfimage) en spécifiant les paramètres de largeur et de hauteur. Ce constructeur simplifie le processus d'initialisation des images EMF avec des dimensions spécifiques, améliorant l'efficacité de votre flux de travail de développement.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| width | int | La largeur. |
| height | int | La hauteur. |

### getHeader() {#getHeader--}
```
public EmfMetafileHeader getHeader()
```


Récupérez l'enregistrement d'en-tête du métafichier EMF avec cette propriété. Idéal pour gérer les données du métafichier efficacement au sein de votre application. Améliorez votre flux de travail grâce à un accès simplifié aux informations d'en-tête du métafichier.

**Returns:**
[EmfMetafileHeader](../../com.aspose.imaging.fileformats.emf.emf.records/emfmetafileheader)
### setHeader(EmfMetafileHeader value) {#setHeader-com.aspose.imaging.fileformats.emf.emf.records.EmfMetafileHeader-}
```
public void setHeader(EmfMetafileHeader value)
```


Modifiez l'enregistrement d'en-tête du métafichier EMF avec cette propriété. Idéal pour gérer les données du métafichier efficacement au sein de votre application. Améliorez votre flux de travail grâce à un accès simplifié aux informations d'en-tête du métafichier.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [EmfMetafileHeader](../../com.aspose.imaging.fileformats.emf.emf.records/emfmetafileheader) |  |

### isCached() {#isCached--}
```
public boolean isCached()
```


Accédez à une valeur indiquant si les données de l'objet sont actuellement en cache, éliminant ainsi le besoin de lectures de données supplémentaires. Augmentez l'efficacité en déterminant rapidement si des données en cache sont disponibles pour un accès immédiat. Optimisez votre flux de travail grâce à des processus de récupération de données simplifiés.

**Returns:**
booléen - `true` si les données de l'objet sont en cache ; sinon, `false`.
### getRecords() {#getRecords--}
```
public MetaObjectList getRecords()
```


Récupérez ou modifiez les enregistrements associés à l'objet. Accédez efficacement et gérez la collection d'enregistrements pour une manipulation et un traitement des données améliorés. Optimisez votre flux de travail en interagissant de manière fluide avec les enregistrements de l'objet.

**Returns:**
[MetaObjectList](../../com.aspose.imaging.fileformats.emf/metaobjectlist) - The records.
### setRecords(MetaObjectList value) {#setRecords-com.aspose.imaging.fileformats.emf.MetaObjectList-}
```
public void setRecords(MetaObjectList value)
```


Modifiez les enregistrements associés à l'objet. Accédez efficacement et gérez la collection d'enregistrements pour une manipulation et un traitement des données améliorés. Optimisez votre flux de travail en interagissant de manière fluide avec les enregistrements de l'objet.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [MetaObjectList](../../com.aspose.imaging.fileformats.emf/metaobjectlist) | Les enregistrements. |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Accédez à la valeur du format de fichier associée à l'objet. Déterminez facilement le format du fichier lié à l'objet pour un traitement simplifié et des vérifications de compatibilité. Simplifiez votre flux de travail en récupérant aisément les informations de format de fichier.

**Returns:**
long
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Récupérez le nombre de bits par pixel propre aux images raster, car ce paramètre ne s'applique pas aux images vectorielles. Déterminez rapidement la profondeur de pixel des images raster pour une analyse et une manipulation précises, garantissant une gestion exacte des données d'image.

**Returns:**
int - Le nombre de bits par pixel de l'image.
### getWidthF() {#getWidthF--}
```
public float getWidthF()
```


Accédez à la largeur de l'image, fournissant des informations essentielles pour un rendu et un traitement précis. Récupérez rapidement la largeur de l'image afin d'assurer la compatibilité et une mise en page correcte dans diverses applications et plateformes.

**Returns:**
float - La largeur de l'image en pixels.
### getHeightF() {#getHeightF--}
```
public float getHeightF()
```


Récupérez la hauteur de l'image, facilitant un rendu précis et des ajustements de mise en page. L'accès à la propriété de hauteur assure la compatibilité et une intégration fluide sur différentes plateformes et applications.

**Returns:**
float - La hauteur de l'image en pixels.
### cacheData() {#cacheData--}
```
public void cacheData()
```


Mettez en cache les données de manière efficace et évitez le chargement redondant depuis le `DataStreamSupporter.DataStreamContainer`([DataStreamSupporter.getDataStreamContainer](../../com.aspose.imaging/datastreamsupporter\#getDataStreamContainer) avec cette méthode. Améliorez les performances et rationalisez l'accès aux données dans votre application, en optimisant l'utilisation des ressources pour une meilleure réactivité.


**Example: This example shows how to load a EMF image from a file and list all of its records.**

``` java
String dir = "c:\\temp\\";

// Utiliser Aspose.Imaging.Image.Load est une méthode unifiée pour charger tous les types d'images, y compris WMF.
com.aspose.imaging.fileformats.emf.EmfImage emfImage = (com.aspose.imaging.fileformats.emf.EmfImage) com.aspose.imaging.Image.load(dir + "test.emf");
try {
    // Mettre en cache les données pour charger tous les enregistrements.
    emfImage.cacheData();
    System.out.println("The total number of records: " + emfImage.getRecords().size());

    // La clé est un type d'enregistrement, la valeur est le nombre d'enregistrements de ce type dans l'image WMF.
    java.util.HashMap<Class, Integer> types =
            new java.util.HashMap<>();

    // Collecter les statistiques
    for (Object obj : emfImage.getRecords()) {
        com.aspose.imaging.fileformats.emf.emf.records.EmfRecord record = (com.aspose.imaging.fileformats.emf.emf.records.EmfRecord) obj;

        Class objType = record.getClass();
        if (!types.containsKey(objType)) {
            types.put(objType, 1);
        } else {
            int n = types.get(objType);
            types.put(objType, n + 1);
        }
    }

    // Imprimer les statistiques
    System.out.println("Record Type                              Count");
    System.out.println("----------------------------------------------");
    for (java.util.Map.Entry<Class, Integer> entry : types.entrySet()) {
        String objectType = entry.getKey().getSimpleName();
        int numberOfEntrances = entry.getValue();

        // Aligner la sortie avec des espaces
        int alignmentPos = 40;
        char[] chars = new char[alignmentPos - objectType.length()];
        java.util.Arrays.fill(chars, ' ');
        String gap = new String(chars);

        System.out.println(objectType + ":" + gap + numberOfEntrances);
    }
} finally {
    emfImage.dispose();
}

//La sortie peut ressembler à ceci :
//Le nombre total d'enregistrements : 1188
//Type d'enregistrement                              Nombre
//----------------------------------------------
//EmfMetafileHeader:                       1
//EmfSetBkMode:                            1
//EmfSetTextAlign:                         1
//EmfSetRop2:                              1
//EmfSetWorldTransform:                    1
//EmfExtSelectClipRgn:                     1
//EmfCreateBrushIndirect:                  113
//EmfSelectObject:                         240
//EmfCreatePen:                            116
//EmfSetPolyFillMode:                      1
//EmfBeginPath:                            120
//EmfMoveToEx:                             122
//EmfPolyBezierTo16:                       36
//EmfLineTo:                               172
//EmfCloseFigure:                          14
//EmfEndPath:                              120
//EmfStrokeAndFillPath:                    113
//EmfStrokePath:                           7
//EmfSetTextColor:                         2
//EmfExtCreateFontIndirectW:               2
//EmfExtTextOutW:                          2
//EmfStretchBlt:                           1
//EmfEof:                                  1
```

### getUsedFonts() {#getUsedFonts--}
```
public String[] getUsedFonts()
```


Récupérez la liste des polices utilisées dans le métafichier avec cette méthode. Obtenez des informations sur l'utilisation des polices, facilitant une gestion efficace et l'optimisation des ressources de polices pour un rendu et une fidélité d'affichage améliorés.

**Returns:**
java.lang.String[] - La liste des polices
### resizeCanvas(Rectangle newRectangle) {#resizeCanvas-com.aspose.imaging.Rectangle-}
```
public void resizeCanvas(Rectangle newRectangle)
```


Redimensionnez le canevas facilement en utilisant cette fonction. Idéal pour ajuster les dimensions globales de l'image sans modifier son contenu. Améliorez la présentation et préparez les images pour diverses tailles d'affichage sans effort.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| newRectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Le nouveau rectangle. |

### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


Obtient les options d'image d'origine.

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - The original image options.
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

