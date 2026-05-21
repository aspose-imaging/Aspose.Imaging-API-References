---
title: "Jpeg2000Options"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Créez des fichiers image JPEG2000 JP2 avec notre API en utilisant une technologie d'ondelettes avancée pour coder du contenu sans perte."
type: docs
weight: 25
url: /fr/java/com.aspose.imaging.imageoptions/jpeg2000options/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)
```
public class Jpeg2000Options extends ImageOptionsBase
```

Créez des fichiers image JPEG2000 (JP2) avec notre API, en utilisant une technologie d'ondelettes avancée pour coder du contenu sans perte. Bénéficiez d'une prise en charge de divers codecs, y compris la compression irréversible et sans perte, ainsi que des conteneurs de métadonnées XMP, garantissant polyvalence et création d'images de haute qualité adaptées à vos besoins.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Jpeg2000Options()](#Jpeg2000Options--) | Initialise une nouvelle instance de la classe `Jpeg2000Options`. |
| [Jpeg2000Options(Jpeg2000Options jpeg2000Options)](#Jpeg2000Options-com.aspose.imaging.imageoptions.Jpeg2000Options-) | Initialise une nouvelle instance de la classe `Jpeg2000Options`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getComments()](#getComments--) | Obtient ou définit les marqueurs de commentaire Jpeg. |
| [setComments(String[] value)](#setComments-java.lang.String---) | Obtient ou définit les marqueurs de commentaire Jpeg. |
| [getCodec()](#getCodec--) | Obtient ou définit le codec JPEG2000. |
| [setCodec(int value)](#setCodec-int-) | Obtient ou définit le codec JPEG2000. |
| [getCompressionRatios()](#getCompressionRatios--) | Obtient ou définit le tableau des rapports de compression. |
| [setCompressionRatios(int[] value)](#setCompressionRatios-int---) | Obtient ou définit le tableau des rapports de compression. |
| [getIrreversible()](#getIrreversible--) | Obtient une valeur indiquant s'il faut utiliser le DWT irréversible 9-7 (true) ou la compression DWT sans perte 5-3 (par défaut). |
| [setIrreversible(boolean value)](#setIrreversible-boolean-) | Définit une valeur indiquant s'il faut utiliser le DWT irréversible 9-7 (true) ou la compression DWT sans perte 5-3 (par défaut). |

## Example: The following example shows how to convert a multipage vector image to JPEG 2000 format in general way without referencing to a particular image type.

``` java
String dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
String inputFilePath = (dir + "Multipage.cdr");
String outputFilePath = (dir + "Multipage.cdr.j2k");

com.aspose.imaging.ImageOptionsBase exportOptions = new com.aspose.imaging.imageoptions.Jpeg2000Options();

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFilePath))
{
    exportOptions.setMultiPageOptions(null);

    // Exportez uniquement les deux premières pages. En fait, une seule page sera rasterisée car le JPEG 2000 n'est pas un format multi-pages.
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

### Jpeg2000Options() {#Jpeg2000Options--}
```
public Jpeg2000Options()
```


Initialise une nouvelle instance de la classe `Jpeg2000Options`.

### Jpeg2000Options(Jpeg2000Options jpeg2000Options) {#Jpeg2000Options-com.aspose.imaging.imageoptions.Jpeg2000Options-}
```
public Jpeg2000Options(Jpeg2000Options jpeg2000Options)
```


Initialise une nouvelle instance de la classe `Jpeg2000Options`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| jpeg2000Options | [Jpeg2000Options](../../com.aspose.imaging.imageoptions/jpeg2000options) | Les options du format de fichier Jpeg2000 dont copier les paramètres. |

### getComments() {#getComments--}
```
public String[] getComments()
```


Obtient ou définit les marqueurs de commentaire Jpeg.

**Returns:**
java.lang.String[] - Les marqueurs de commentaire Jpeg.
### setComments(String[] value) {#setComments-java.lang.String---}
```
public void setComments(String[] value)
```


Obtient ou définit les marqueurs de commentaire Jpeg.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String[] | Les marqueurs de commentaire Jpeg. |

### getCodec() {#getCodec--}
```
public int getCodec()
```


Obtient ou définit le codec JPEG2000.

**Returns:**
int - Le codec JPEG2000
### setCodec(int value) {#setCodec-int-}
```
public void setCodec(int value)
```


Obtient ou définit le codec JPEG2000.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | Le codec JPEG2000 |


**Example: This example shows how to create a PNG image and save it to JPEG2000 with the desired options.**

``` java
String dir = "c:\\temp\\";

// Créez une image PNG de 100 × 100 px.
com.aspose.imaging.fileformats.png.PngImage pngImage = new com.aspose.imaging.fileformats.png.PngImage(100, 100);
try {
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(pngImage);

    // Remplissez toute l'image en rouge.
    com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getRed());
    graphics.fillRectangle(brush, pngImage.getBounds());

    com.aspose.imaging.imageoptions.Jpeg2000Options saveOptions = new com.aspose.imaging.imageoptions.Jpeg2000Options();

    // Utilisez la Transformée en Ondelettes Discrète irréversible 9-7
    saveOptions.setIrreversible(true);

    // JP2 est le format "conteneur" pour les flux de codage JPEG 2000.
    // J2K est des données compressées brutes, sans enveloppe.
    saveOptions.setCodec(com.aspose.imaging.fileformats.jpeg2000.Jpeg2000Codec.J2K);

    // Enregistrer dans un fichier
    pngImage.save(dir + "output.j2k", saveOptions);
} finally {
    pngImage.dispose();
}
```

### getCompressionRatios() {#getCompressionRatios--}
```
public int[] getCompressionRatios()
```


Obtient ou définit le tableau des rapports de compression. Différents rapports de compression pour les couches successives. Le taux spécifié pour chaque niveau de qualité est le facteur de compression souhaité. Des rapports décroissants sont requis.

**Returns:**
int[] - Les rapports de compression.
### setCompressionRatios(int[] value) {#setCompressionRatios-int---}
```
public void setCompressionRatios(int[] value)
```


Obtient ou définit le tableau des rapports de compression. Différents rapports de compression pour les couches successives. Le taux spécifié pour chaque niveau de qualité est le facteur de compression souhaité. Des rapports décroissants sont requis.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int[] | Les rapports de compression. |

### getIrreversible() {#getIrreversible--}
```
public boolean getIrreversible()
```


Obtient une valeur indiquant s'il faut utiliser le DWT irréversible 9-7 (true) ou la compression DWT sans perte 5-3 (par défaut).

**Returns:**
boolean - une valeur indiquant si vous utilisez le DWT irréversible 9-7 (true) ou la compression DWT sans perte 5-3
### setIrreversible(boolean value) {#setIrreversible-boolean-}
```
public void setIrreversible(boolean value)
```


Définit une valeur indiquant s'il faut utiliser le DWT irréversible 9-7 (true) ou la compression DWT sans perte 5-3 (par défaut).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean | une valeur indiquant si vous utilisez le DWT irréversible 9-7 (true) ou la compression DWT sans perte 5-3 |


**Example: This example shows how to create a PNG image and save it to JPEG2000 with the desired options.**

``` java
String dir = "c:\\temp\\";

// Créez une image PNG de 100 × 100 px.
com.aspose.imaging.fileformats.png.PngImage pngImage = new com.aspose.imaging.fileformats.png.PngImage(100, 100);
try {
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(pngImage);

    // Remplissez toute l'image en rouge.
    com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getRed());
    graphics.fillRectangle(brush, pngImage.getBounds());

    com.aspose.imaging.imageoptions.Jpeg2000Options saveOptions = new com.aspose.imaging.imageoptions.Jpeg2000Options();

    // Utilisez la Transformée en Ondelettes Discrète irréversible 9-7
    saveOptions.setIrreversible(true);

    // JP2 est le format "conteneur" pour les flux de codage JPEG 2000.
    // J2K est des données compressées brutes, sans enveloppe.
    saveOptions.setCodec(com.aspose.imaging.fileformats.jpeg2000.Jpeg2000Codec.J2K);

    // Enregistrer dans un fichier
    pngImage.save(dir + "output.j2k", saveOptions);
} finally {
    pngImage.dispose();
}
```

