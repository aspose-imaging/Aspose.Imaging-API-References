---
title: "WmfImage"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Manipulez les images Microsoft Windows Metafile WMF avec notre API en gérant de manière transparente les données vectorielles et bitmap stockées dans des enregistrements de longueur variable."
type: docs
weight: 10
url: /fr/java/com.aspose.imaging.fileformats.wmf/wmfimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage), [com.aspose.imaging.fileformats.emf.MetaImage](../../com.aspose.imaging.fileformats.emf/metaimage)
```
public class WmfImage extends MetaImage
```

Manipulez les images Microsoft Windows Metafile (WMF) avec notre API, en gérant de manière transparente les données vectorielles et bitmap stockées dans des enregistrements de longueur variable. Redimensionnez, faites pivoter et retournez les images facilement tout en définissant des palettes d'images personnalisées. Convertissez les fichiers WMF en formats WMZ compressés ou enregistrez-les dans des formats d'images raster pour une utilisation polyvalente sur différentes plateformes et applications.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [WmfImage()](#WmfImage--) | Créez une nouvelle instance de la classe [WmfImage](../../com.aspose.imaging.fileformats.wmf/wmfimage), en l'initialisant pour une manipulation et un traitement ultérieurs des données d'image Windows Metafile (WMF). |
| [WmfImage(int width, int height)](#WmfImage-int-int-) | Instanciez une nouvelle instance de la classe [WmfImage](../../com.aspose.imaging.fileformats.wmf/wmfimage) avec des paramètres de largeur et de hauteur personnalisables, facilitant la création d'images WMF vierges adaptées à des dimensions spécifiques. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [isCached()](#isCached--) | Récupérez une valeur booléenne indiquant si les données de l'objet sont actuellement mises en cache, éliminant ainsi le besoin d'opérations de lecture de données supplémentaires. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Récupérez le nombre de bits par pixel de l'image, indiquant le niveau de profondeur de couleur ou de granularité. |
| [getWidthF()](#getWidthF--) | Accédez à la largeur de l'image, indiquant le nombre de pixels le long de son axe horizontal. |
| [getHeightF()](#getHeightF--) | Accédez à la hauteur de l'image, représentant le nombre de pixels le long de son axe vertical. |
| [getInch()](#getInch--) | Accédez ou modifiez la propriété inch, représentant une unité de mesure généralement utilisée pour spécifier les dimensions physiques dans les contextes d'impression ou d'affichage. |
| [setInch(int value)](#setInch-int-) | Accédez ou modifiez la propriété inch, représentant une unité de mesure généralement utilisée pour spécifier les dimensions physiques dans les contextes d'impression ou d'affichage. |
| [getFileFormat()](#getFileFormat--) | Accédez à la valeur du format de fichier associée à l'image, fournissant des informations sur le format dans lequel l'image est stockée. |
| [getFrameBounds()](#getFrameBounds--) | Accédez aux limites du cadre, indiquant sa position et ses dimensions au sein de l'image. |
| [cacheData()](#cacheData--) | Mettez en cache les données de manière efficace, éliminant le besoin de chargements supplémentaires depuis le `DataStreamSupporter.DataStreamContainer` sous-jacent ([DataStreamSupporter.getDataStreamContainer](../../com.aspose.imaging/datastreamsupporter\#getDataStreamContainer)). |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.imaging.IColorPalette-boolean-) | Appliquez une palette spécifiée à l'image, permettant la personnalisation de la représentation des couleurs. |
| [getUsedFonts()](#getUsedFonts--) | Récupérez la liste des polices utilisées dans le métafichier, offrant un aperçu des ressources de police utilisées dans l'image. |
| [resizeCanvas(Rectangle newRectangle)](#resizeCanvas-com.aspose.imaging.Rectangle-) | Redimensionnez le canevas de l'image, ajustant ses dimensions tout en conservant le contenu de l'image. |
| [addRecord(WmfObject record)](#addRecord-com.aspose.imaging.fileformats.wmf.objects.WmfObject-) | Incorporez l'objet d'enregistrement spécifié dans l'image, enrichissant son contenu avec des données ou métadonnées supplémentaires. |
| [getPostScript()](#getPostScript--) | Accédez aux données PostScript associées à l'image, fournissant des informations détaillées sur sa structure ou son contenu. |
| [getOriginalOptions()](#getOriginalOptions--) | Obtient les options d'image d'origine. |

## Example: This example shows how to load a WMF image from a file and convert it to SVG using WmfRasterizationOptions.

``` java
String dir = "c:\\temp\\";

// Utiliser Aspose.Imaging.Image.Load est une méthode unifiée pour charger tous les types d'images, y compris WMF.
try (com.aspose.imaging.fileformats.wmf.WmfImage wmfImage = (com.aspose.imaging.fileformats.wmf.WmfImage)com.aspose.imaging.Image.load(dir + "test.wmf"))
{
    com.aspose.imaging.imageoptions.SvgOptions saveOptions = new com.aspose.imaging.imageoptions.SvgOptions();
                    
    // Le texte sera converti en formes.
    saveOptions.setTextAsShapes(true);

    com.aspose.imaging.imageoptions.WmfRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.WmfRasterizationOptions();

    // La couleur de fond de la surface de dessin.
    rasterizationOptions.setBackgroundColor(com.aspose.imaging.Color.getWhiteSmoke());

    // La taille de la page.
    rasterizationOptions.setPageSize(Size.to_SizeF(wmfImage.getSize()));

    // Si un emf intégré existe, alors rendre l'emf ; sinon rendre le wmf.
    rasterizationOptions.setRenderMode(com.aspose.imaging.fileformats.wmf.WmfRenderMode.Auto);

    saveOptions.setVectorRasterizationOptions(rasterizationOptions);

    wmfImage.save(dir + "test.output.svg", saveOptions);
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


## Example: The following example shows how to convert a wmz images to wmf format

``` java
String file = "example.wmz";
String baseFolder = "D:\\Compressed\\";
String inputFile = baseFolder + file;
String outFile = inputFile + ".wmf";
try (final com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFile))
{
    final com.aspose.imaging.imageoptions.VectorRasterizationOptions vectorRasterizationOptions = new com.aspose.imaging.imageoptions.WmfRasterizationOptions()
    {{
        setPageSize(com.aspose.imaging.Size.to_SizeF(image.getSize()));
    }};
                
    image.save(outFile, new com.aspose.imaging.imageoptions.WmfOptions()
    {{
        setVectorRasterizationOptions(vectorRasterizationOptions);
    }});
}
```


## Example: The following example shows how to convert a wmf images to wmz format

``` java
String file = "castle.wmf";
String baseFolder = "D:\\Compressed\\";
String inputFile = baseFolder + file;
String outFile = inputFile + ".wmz";
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFile))
{
    com.aspose.imaging.imageoptions.VectorRasterizationOptions vectorRasterizationOptions = new com.aspose.imaging.imageoptions.WmfRasterizationOptions();
    vectorRasterizationOptions.setPageSize(com.aspose.imaging.Size.to_SizeF(image.getSize()));
    com.aspose.imaging.imageoptions.WmfOptions options = new com.aspose.imaging.imageoptions.WmfOptions();
    options.setVectorRasterizationOptions(vectorRasterizationOptions);
    options.setCompress(true);
    image.save(outFile, options);
}
```

### WmfImage() {#WmfImage--}
```
public WmfImage()
```


Créez une nouvelle instance de la classe [WmfImage](../../com.aspose.imaging.fileformats.wmf/wmfimage), en l'initialisant pour une manipulation et un traitement ultérieurs des données d'image Windows Metafile (WMF). Ce constructeur fournit un objet de base pour travailler avec les images WMF, permettant une intégration transparente des capacités de gestion des images WMF dans la fonctionnalité de votre application.

### WmfImage(int width, int height) {#WmfImage-int-int-}
```
public WmfImage(int width, int height)
```


Instanciez une nouvelle instance de la classe [WmfImage](../../com.aspose.imaging.fileformats.wmf/wmfimage) avec des paramètres de largeur et de hauteur personnalisables, facilitant la création d'images WMF vierges adaptées à des dimensions spécifiques. Utilisez ce constructeur pour générer dynamiquement des images WMF avec des dimensions précises, permettant une création et une manipulation d'images flexibles au sein de votre application.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| width | int | La largeur. |
| height | int | La hauteur. |

### isCached() {#isCached--}
```
public boolean isCached()
```


Récupérez une valeur booléenne indiquant si les données de l'objet sont actuellement mises en cache, éliminant ainsi le besoin d'opérations de lecture supplémentaires. Utilisez cette propriété pour optimiser les performances en déterminant si les données de l'objet sont immédiatement disponibles sans nécessiter de processus coûteux de récupération de données dans votre application.

**Returns:**
boolean
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Récupérez le nombre de bits par pixel de l'image, indiquant le niveau de profondeur ou de granularité des couleurs. Utilisez cette propriété pour déterminer la représentation couleur et la précision de l'image, facilitant les vérifications de compatibilité et le traitement lié aux couleurs dans votre application.

**Returns:**
int
### getWidthF() {#getWidthF--}
```
public float getWidthF()
```


Accédez à la largeur de l'image, indiquant le nombre de pixels le long de son axe horizontal. Utilisez cette propriété pour déterminer les dimensions spatiales et le ratio d'aspect de l'image, permettant des ajustements précis de mise en page et de rendu dans votre application.

**Returns:**
float - La largeur de l'image en pixels.
### getHeightF() {#getHeightF--}
```
public float getHeightF()
```


Accédez à la hauteur de l'image, représentant le nombre de pixels le long de son axe vertical. Utilisez cette propriété pour déterminer les dimensions spatiales et le ratio d'aspect de l'image, permettant des ajustements précis de mise en page et de rendu dans votre application.

**Returns:**
float - La hauteur de l'image en pixels.
### getInch() {#getInch--}
```
public int getInch()
```


Accédez ou modifiez la propriété inch, représentant une unité de mesure généralement utilisée pour spécifier les dimensions physiques dans les contextes d'impression ou d'affichage. Utilisez cette propriété pour établir ou récupérer les valeurs en pouces associées à l'image, facilitant une représentation précise des dimensions physiques dans votre application.

**Returns:**
int
### setInch(int value) {#setInch-int-}
```
public void setInch(int value)
```


Accédez ou modifiez la propriété inch, représentant une unité de mesure généralement utilisée pour spécifier les dimensions physiques dans les contextes d'impression ou d'affichage. Utilisez cette propriété pour établir ou récupérer les valeurs en pouces associées à l'image, facilitant une représentation précise des dimensions physiques dans votre application.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Accédez à la valeur du format de fichier associée à l'image, fournissant des informations sur le format dans lequel l'image est stockée. Utilisez cette propriété pour déterminer le format de fichier de l'image, facilitant les vérifications de compatibilité et le traitement spécifique au format dans votre application.

**Returns:**
long
### getFrameBounds() {#getFrameBounds--}
```
public final Rectangle getFrameBounds()
```


Accédez aux limites du cadre, indiquant sa position et ses dimensions au sein de l'image. Utilisez cette propriété pour récupérer des informations détaillées sur l'emplacement spatial du cadre, permettant une manipulation et un rendu précis dans votre application.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - the frame bounds.
### cacheData() {#cacheData--}
```
public void cacheData()
```


Mettez en cache les données de manière efficace, éliminant le besoin de chargement supplémentaire depuis le `DataStreamSupporter.DataStreamContainer`([DataStreamSupporter.getDataStreamContainer](../../com.aspose.imaging/datastreamsupporter\#getDataStreamContainer)). Utilisez cette méthode pour optimiser les performances et minimiser l'utilisation des ressources dans votre application en stockant et en accédant au cache de données local.


**Example: This example shows how to load a WMF image from a file and list all of its records.**

``` java
String dir = "c:\\temp\\";

// Utiliser Aspose.Imaging.Image.Load est une méthode unifiée pour charger tous les types d'images, y compris WMF.
com.aspose.imaging.fileformats.wmf.WmfImage wmfImage = (com.aspose.imaging.fileformats.wmf.WmfImage) com.aspose.imaging.Image.load(dir + "test.wmf");
try {
    // Mettre en cache les données pour charger tous les enregistrements.
    wmfImage.cacheData();
    System.out.println("The total number of records: " + wmfImage.getRecords().size());

    // La clé est un type d'enregistrement, la valeur est le nombre d'enregistrements de ce type dans l'image WMF.
    java.util.HashMap<Class, Integer> types = new java.util.HashMap<>();

    // Collecter les statistiques
    for (Object obj : wmfImage.getRecords()) {
        com.aspose.imaging.fileformats.wmf.objects.WmfObject wmfObj = (com.aspose.imaging.fileformats.wmf.objects.WmfObject) obj;

        Class objType = wmfObj.getClass();
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
    wmfImage.dispose();
}

//La sortie peut ressembler à ceci :
//Le nombre total d'enregistrements : 613
//Type d'enregistrement                              Nombre
//----------------------------------------------
//WmfSetBkMode:                            1
//WmfSetTextAlign:                         1
//WmfSetRop2:                              1
//WmfSetWindowOrg:                         1
//WmfSetWindowExt:                         1
//WmfCreateBrushInDirect:                  119
//WmfSelectObject:                         240
//WmfCreatePenInDirect:                    119
//WmfSetPolyFillMode:                      1
//WmfPolyPolygon:                          114
//WmfPolyLine:                             7
//WmfSetTextColor:                         2
//WmfCreateFontInDirect:                   2
//WmfExtTextOut:                           2
//WmfDibStrechBlt:                         1
//WmfEof:                                  1
```

### setPalette(IColorPalette palette, boolean updateColors) {#setPalette-com.aspose.imaging.IColorPalette-boolean-}
```
public void setPalette(IColorPalette palette, boolean updateColors)
```


Appliquez une palette spécifiée à l'image, permettant la personnalisation de la représentation des couleurs. Utilisez cette méthode pour améliorer le rendu visuel et obtenir des effets de couleur spécifiques dans votre application.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | La palette à définir. |
| updateColors | boolean | si défini sur `true`, les couleurs seront mises à jour selon la nouvelle palette ; sinon les index de couleur restent inchangés. Notez que les index inchangés peuvent provoquer un plantage de l'image lors du chargement si certains index n'ont aucune entrée correspondante dans la palette. |

### getUsedFonts() {#getUsedFonts--}
```
public String[] getUsedFonts()
```


Récupérez la liste des polices utilisées dans le métafichier, offrant un aperçu des ressources de polices utilisées dans l'image. Utilisez cette méthode pour analyser l'utilisation des polices et garantir leur disponibilité pour le rendu ou le traitement ultérieur dans votre application.

**Returns:**
java.lang.String[] - La liste des polices
### resizeCanvas(Rectangle newRectangle) {#resizeCanvas-com.aspose.imaging.Rectangle-}
```
public void resizeCanvas(Rectangle newRectangle)
```


Redimensionnez le canevas de l'image, en ajustant ses dimensions tout en conservant le contenu de l'image. Utilisez cette méthode pour modifier la taille du canevas sans altérer le contenu, facilitant les ajustements de mise en page et les changements de composition dans votre application.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| newRectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Le nouveau rectangle. |

### addRecord(WmfObject record) {#addRecord-com.aspose.imaging.fileformats.wmf.objects.WmfObject-}
```
public int addRecord(WmfObject record)
```


Incorporez l'objet d'enregistrement spécifié dans l'image, enrichissant son contenu avec des données ou des métadonnées supplémentaires. Utilisez cette méthode pour intégrer de manière fluide les objets d'enregistrement dans l'image, facilitant le stockage et l'organisation complets des données dans votre application.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| record | [WmfObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfobject) | L'enregistrement. |

**Returns:**
int - Nombre d'enregistrements.
### getPostScript() {#getPostScript--}
```
public final String getPostScript()
```


Accédez aux données PostScript associées à l'image, fournissant des informations détaillées sur sa structure ou son contenu. Utilisez cette méthode pour récupérer les données PostScript en vue d'une analyse ou d'un traitement supplémentaire dans votre application, permettant des fonctionnalités avancées liées au rendu ou à la manipulation de PostScript.

**Returns:**
java.lang.String - Le post script
### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


Obtient les options d'image d'origine.

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - The original image options.
