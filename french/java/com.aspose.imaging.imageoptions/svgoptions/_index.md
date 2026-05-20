---
title: "SvgOptions"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Créez des fichiers d'image SVG (Scalar Vector Graphics) avec notre API en utilisant des options polyvalentes pour les types de couleur et les niveaux de compression."
type: docs
weight: 45
url: /fr/java/com.aspose.imaging.imageoptions/svgoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)

**All Implemented Interfaces:**
com.aspose.fileformats.core.imageoptions.ICompressOptions
```
public class SvgOptions extends ImageOptionsBase implements ICompressOptions
```

Créez des fichiers d'image SVG (Scalar Vector Graphics) avec notre API, en utilisant des options polyvalentes pour les types de couleur et les niveaux de compression. Personnalisez vos images SVG avec précision, en garantissant une qualité optimale et une compatibilité adaptée à vos besoins de conception.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [SvgOptions()](#SvgOptions--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getColorType()](#getColorType--) | Obtient ou définit le type de couleur pour l'image SVG. |
| [setColorType(int value)](#setColorType-int-) | Obtient ou définit le type de couleur pour l'image SVG. |
| [getTextAsShapes()](#getTextAsShapes--) | Obtient une valeur indiquant si le texte doit être rendu sous forme de formes. |
| [setTextAsShapes(boolean value)](#setTextAsShapes-boolean-) | Définit une valeur indiquant si le texte doit être rendu sous forme de formes. |
| [getCallback()](#getCallback--) | Obtient la stratégie de stockage des ressources intégrées de [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage) telles que les polices, les rasters imbriqués. |
| [setCallback(ISvgResourceKeeperCallback value)](#setCallback-com.aspose.imaging.fileformats.svg.ISvgResourceKeeperCallback-) | Définit la stratégie de stockage des ressources intégrées de [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage) telles que les polices, les rasters imbriqués. |
| [getCompress()](#getCompress--) | Obtient une valeur indiquant si l'image de sortie doit être compressée. |
| [setCompress(boolean value)](#setCompress-boolean-) | Définit une valeur indiquant si l'image de sortie doit être compressée. |

## Example: The following example shows how to convert a multipage vector image to SVG format in general way without referencing to a particular image type.

``` java
String dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
String inputFilePath = (dir + "Multipage.cdr");
String outputFilePath = (dir + "Multipage.cdr.svg");

com.aspose.imaging.ImageOptionsBase exportOptions = new com.aspose.imaging.imageoptions.SvgOptions();

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFilePath))
{
    exportOptions.setMultiPageOptions(null);

    // Exportez uniquement les deux premières pages. En fait, une seule page sera convertie car le SVG n'est pas un format multi-pages.
    com.aspose.imaging.IMultipageImage multipageImage = (image instanceof com.aspose.imaging.IMultipageImage) ? (com.aspose.imaging.IMultipageImage) image : null;
    if (multipageImage != null && (multipageImage.getPages() != null && multipageImage.getPageCount() > 2))
    {
        exportOptions.setMultiPageOptions(new com.aspose.imaging.imageoptions.MultiPageOptions(new com.aspose.imaging.IntRange(0, 2)));
    }

    if (image instanceof com.aspose.imaging.VectorImage)
    {
        com.aspose.imaging.imageoptions.VectorRasterizationOptions defaultOptions = (com.aspose.imaging.imageoptions.VectorRasterizationOptions) image.getDefaultOptions(new Object[]{Color.getWhite(), image.getWidth(), image.getHeight()});
        exportOptions.setVectorRasterizationOptions(defaultOptions);
        defaultOptions.setTextRenderingHint(com.aspose.imaging.TextRenderingHint.SingleBitPerPixel);
        defaultOptions.setSmoothingMode(com.aspose.imaging.SmoothingMode.None);
    }

    image.save(outputFilePath, exportOptions);
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

### SvgOptions() {#SvgOptions--}
```
public SvgOptions()
```


### getColorType() {#getColorType--}
```
public int getColorType()
```


Obtient ou définit le type de couleur pour l'image SVG.

**Returns:**
int - Le type de couleur de l'image SVG.
### setColorType(int value) {#setColorType-int-}
```
public void setColorType(int value)
```


Obtient ou définit le type de couleur pour l'image SVG.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | Le type de couleur de l'image SVG. |

### getTextAsShapes() {#getTextAsShapes--}
```
public boolean getTextAsShapes()
```


Obtient une valeur indiquant si le texte doit être rendu sous forme de formes.

Valeur : `true` si tout le texte est transformé en formes SVG lors de la conversion ; sinon, `false`.

**Returns:**
boolean - une valeur indiquant si le texte doit être rendu sous forme de formes.
### setTextAsShapes(boolean value) {#setTextAsShapes-boolean-}
```
public void setTextAsShapes(boolean value)
```


Définit une valeur indiquant si le texte doit être rendu sous forme de formes.

Valeur : `true` si tout le texte est transformé en formes SVG lors de la conversion ; sinon, `false`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean | une valeur indiquant si le texte doit être rendu sous forme de formes. |


**Example: This example shows how to load a WMF image from a file and convert it to SVG using WmfRasterizationOptions.**

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


**Example: This example shows how to load a EMF image from a file and convert it to SVG using EmfRasterizationOptions.**

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

### getCallback() {#getCallback--}
```
public ISvgResourceKeeperCallback getCallback()
```


Obtient la stratégie de stockage des ressources intégrées de [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage) telles que les polices, les rasters imbriqués.

**Returns:**
[ISvgResourceKeeperCallback](../../com.aspose.imaging.fileformats.svg/isvgresourcekeepercallback) - the storing strategy for embedded resources of [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage) such as fonts, nested rasters.
### setCallback(ISvgResourceKeeperCallback value) {#setCallback-com.aspose.imaging.fileformats.svg.ISvgResourceKeeperCallback-}
```
public void setCallback(ISvgResourceKeeperCallback value)
```


Définit la stratégie de stockage des ressources intégrées de [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage) telles que les polices, les rasters imbriqués.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [ISvgResourceKeeperCallback](../../com.aspose.imaging.fileformats.svg/isvgresourcekeepercallback) | la stratégie de stockage des ressources intégrées de [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage) telles que les polices, les rasters imbriqués. |

### getCompress() {#getCompress--}
```
public final boolean getCompress()
```


Obtient une valeur indiquant si l'image de sortie doit être compressée.

**Returns:**
booléen - une valeur indiquant si l'image de sortie doit être compressée.
### setCompress(boolean value) {#setCompress-boolean-}
```
public final void setCompress(boolean value)
```


Définit une valeur indiquant si l'image de sortie doit être compressée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean | une valeur indiquant si l'image de sortie doit être compressée. |


**Example: The following example shows how to convert a svg images to svgz format**

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

